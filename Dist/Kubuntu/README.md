Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 6457

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [74c274a303](https://linux-hardware.org/?probe=74c274a303) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [123aa39382](https://linux-hardware.org/?probe=123aa39382) | Dec 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [1297c97e04](https://linux-hardware.org/?probe=1297c97e04) | Dec 24, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c1069bda0b](https://linux-hardware.org/?probe=c1069bda0b) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9549fcd83e](https://linux-hardware.org/?probe=9549fcd83e) | Dec 23, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [6d8c495e90](https://linux-hardware.org/?probe=6d8c495e90) | Dec 23, 2023 |
| HP            | 340S G7 Notebook PC         | Notebook    | [097603b65a](https://linux-hardware.org/?probe=097603b65a) | Dec 23, 2023 |
| Lenovo        | ThinkPad T500 20564RG       | Notebook    | [e17f4b51d6](https://linux-hardware.org/?probe=e17f4b51d6) | Dec 22, 2023 |
| Dell          | Latitude 7280               | Notebook    | [5397e7633e](https://linux-hardware.org/?probe=5397e7633e) | Dec 22, 2023 |
| Lenovo        | M30-70 80H8                 | Notebook    | [8ec7db7a8a](https://linux-hardware.org/?probe=8ec7db7a8a) | Dec 22, 2023 |
| Eluktronic... | MECH-17                     | Notebook    | [0a69b2e084](https://linux-hardware.org/?probe=0a69b2e084) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [db6db43604](https://linux-hardware.org/?probe=db6db43604) | Dec 22, 2023 |
| HP            | Notebook                    | Notebook    | [7541fcf0c8](https://linux-hardware.org/?probe=7541fcf0c8) | Dec 22, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [cdcc0b8368](https://linux-hardware.org/?probe=cdcc0b8368) | Dec 22, 2023 |
| Dell          | Precision 5480              | Notebook    | [382626cfb5](https://linux-hardware.org/?probe=382626cfb5) | Dec 21, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1b860f6465](https://linux-hardware.org/?probe=1b860f6465) | Dec 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [fb2877e727](https://linux-hardware.org/?probe=fb2877e727) | Dec 21, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [81855c7ee8](https://linux-hardware.org/?probe=81855c7ee8) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [98eee633b1](https://linux-hardware.org/?probe=98eee633b1) | Dec 20, 2023 |
| Micro Comp... | Venus series                | Notebook    | [e01ac2dc02](https://linux-hardware.org/?probe=e01ac2dc02) | Dec 20, 2023 |
| Google        | Cave                        | Notebook    | [ec9d49335f](https://linux-hardware.org/?probe=ec9d49335f) | Dec 20, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [c41952876f](https://linux-hardware.org/?probe=c41952876f) | Dec 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [449c36ff1c](https://linux-hardware.org/?probe=449c36ff1c) | Dec 19, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [031f8b45bd](https://linux-hardware.org/?probe=031f8b45bd) | Dec 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWA16R0... | Notebook    | [4f1e1945a7](https://linux-hardware.org/?probe=4f1e1945a7) | Dec 19, 2023 |
| MSI           | H97M-P35                    | Desktop     | [759943cd15](https://linux-hardware.org/?probe=759943cd15) | Dec 19, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [0fe8df6dfe](https://linux-hardware.org/?probe=0fe8df6dfe) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| HP            | 81B3                        | Desktop     | [86d9fc12a5](https://linux-hardware.org/?probe=86d9fc12a5) | Dec 19, 2023 |
| HP            | 828A                        | Desktop     | [94483ed23a](https://linux-hardware.org/?probe=94483ed23a) | Dec 19, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [d8f95bfd45](https://linux-hardware.org/?probe=d8f95bfd45) | Dec 18, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [f9a70833ee](https://linux-hardware.org/?probe=f9a70833ee) | Dec 18, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [d56dcc35b9](https://linux-hardware.org/?probe=d56dcc35b9) | Dec 18, 2023 |
| Gateway       | NV54 Series                 | Notebook    | [1bd87c77d2](https://linux-hardware.org/?probe=1bd87c77d2) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6115b25184](https://linux-hardware.org/?probe=6115b25184) | Dec 18, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [16550580d3](https://linux-hardware.org/?probe=16550580d3) | Dec 18, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [8507460974](https://linux-hardware.org/?probe=8507460974) | Dec 18, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [50ef2b12e3](https://linux-hardware.org/?probe=50ef2b12e3) | Dec 17, 2023 |
| Notebook      | W65_67SR                    | Notebook    | [8f970e8d4c](https://linux-hardware.org/?probe=8f970e8d4c) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [c88b531754](https://linux-hardware.org/?probe=c88b531754) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [e3d9d4d8a7](https://linux-hardware.org/?probe=e3d9d4d8a7) | Dec 17, 2023 |
| HP            | Notebook                    | Notebook    | [88e0b592ea](https://linux-hardware.org/?probe=88e0b592ea) | Dec 17, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [fe9179b1fb](https://linux-hardware.org/?probe=fe9179b1fb) | Dec 16, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [32af19e996](https://linux-hardware.org/?probe=32af19e996) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [f1f6a55f9c](https://linux-hardware.org/?probe=f1f6a55f9c) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [8b6e7627f9](https://linux-hardware.org/?probe=8b6e7627f9) | Dec 16, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [15c3d23fc9](https://linux-hardware.org/?probe=15c3d23fc9) | Dec 15, 2023 |
| HP            | G62                         | Notebook    | [fd110d99fd](https://linux-hardware.org/?probe=fd110d99fd) | Dec 15, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [ce943a3a49](https://linux-hardware.org/?probe=ce943a3a49) | Dec 15, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [d438fe20ff](https://linux-hardware.org/?probe=d438fe20ff) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [a7be5e66cd](https://linux-hardware.org/?probe=a7be5e66cd) | Dec 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [cf35bfbdf4](https://linux-hardware.org/?probe=cf35bfbdf4) | Dec 14, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [0b19e954c5](https://linux-hardware.org/?probe=0b19e954c5) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [42b02a9d8e](https://linux-hardware.org/?probe=42b02a9d8e) | Dec 14, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57cc6cbccf](https://linux-hardware.org/?probe=57cc6cbccf) | Dec 14, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [27c22f0c94](https://linux-hardware.org/?probe=27c22f0c94) | Dec 14, 2023 |
| HP            | 2AA7 H                      | Desktop     | [5e9703dff5](https://linux-hardware.org/?probe=5e9703dff5) | Dec 13, 2023 |
| Unknown       | AM02                        | Mini pc     | [6bd02968e3](https://linux-hardware.org/?probe=6bd02968e3) | Dec 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c5d4eabc9b](https://linux-hardware.org/?probe=c5d4eabc9b) | Dec 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [87fa57a3af](https://linux-hardware.org/?probe=87fa57a3af) | Dec 12, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [22dfb202b4](https://linux-hardware.org/?probe=22dfb202b4) | Dec 12, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [0a531cbda1](https://linux-hardware.org/?probe=0a531cbda1) | Dec 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [39a6569b14](https://linux-hardware.org/?probe=39a6569b14) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [4fd70c36f8](https://linux-hardware.org/?probe=4fd70c36f8) | Dec 12, 2023 |
| Acer          | Predator G3-572             | Notebook    | [7de00d4eab](https://linux-hardware.org/?probe=7de00d4eab) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [a73b0c39f2](https://linux-hardware.org/?probe=a73b0c39f2) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [b569f37962](https://linux-hardware.org/?probe=b569f37962) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [8bdb6d048e](https://linux-hardware.org/?probe=8bdb6d048e) | Dec 11, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [281cfa9ff7](https://linux-hardware.org/?probe=281cfa9ff7) | Dec 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [cea97f4e49](https://linux-hardware.org/?probe=cea97f4e49) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [b5d2cf7074](https://linux-hardware.org/?probe=b5d2cf7074) | Dec 10, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9c4f708056](https://linux-hardware.org/?probe=9c4f708056) | Dec 10, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [6e5abc0ea5](https://linux-hardware.org/?probe=6e5abc0ea5) | Dec 10, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [b85850b4c2](https://linux-hardware.org/?probe=b85850b4c2) | Dec 10, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [4c20f6a826](https://linux-hardware.org/?probe=4c20f6a826) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [2a22b3adb4](https://linux-hardware.org/?probe=2a22b3adb4) | Dec 10, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [3a6b7f5ae4](https://linux-hardware.org/?probe=3a6b7f5ae4) | Dec 09, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [215b8bc94a](https://linux-hardware.org/?probe=215b8bc94a) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a0919a7fc](https://linux-hardware.org/?probe=7a0919a7fc) | Dec 09, 2023 |
| Lenovo        | ThinkPad X220 4290B19       | Notebook    | [1515bfc49e](https://linux-hardware.org/?probe=1515bfc49e) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | Notebook    | [170b205714](https://linux-hardware.org/?probe=170b205714) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8395e5f595](https://linux-hardware.org/?probe=8395e5f595) | Dec 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | Notebook    | [f463c790b4](https://linux-hardware.org/?probe=f463c790b4) | Dec 08, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [4167bf6fe4](https://linux-hardware.org/?probe=4167bf6fe4) | Dec 08, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [0fb56c3b77](https://linux-hardware.org/?probe=0fb56c3b77) | Dec 08, 2023 |
| HP            | 843B                        | Desktop     | [27527dbb19](https://linux-hardware.org/?probe=27527dbb19) | Dec 07, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6f35ce12bd](https://linux-hardware.org/?probe=6f35ce12bd) | Dec 07, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [21847052d3](https://linux-hardware.org/?probe=21847052d3) | Dec 07, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [2edc689735](https://linux-hardware.org/?probe=2edc689735) | Dec 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [be768fb273](https://linux-hardware.org/?probe=be768fb273) | Dec 06, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7317dc8b5c](https://linux-hardware.org/?probe=7317dc8b5c) | Dec 06, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [65530f33de](https://linux-hardware.org/?probe=65530f33de) | Dec 06, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [1f68b6b7c7](https://linux-hardware.org/?probe=1f68b6b7c7) | Dec 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [1bf269cb9e](https://linux-hardware.org/?probe=1bf269cb9e) | Dec 05, 2023 |
| eMachines     | eME732G                     | Notebook    | [d94dd62bf1](https://linux-hardware.org/?probe=d94dd62bf1) | Dec 05, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [0d7f21475d](https://linux-hardware.org/?probe=0d7f21475d) | Dec 05, 2023 |
| Micro Comp... | Venus series                | Notebook    | [fab7ae9a17](https://linux-hardware.org/?probe=fab7ae9a17) | Dec 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e90c011500](https://linux-hardware.org/?probe=e90c011500) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e6e58d5148](https://linux-hardware.org/?probe=e6e58d5148) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX TRX40-XE GAMIN... | Desktop     | [31b3b0fd94](https://linux-hardware.org/?probe=31b3b0fd94) | Dec 05, 2023 |
| Samsung       | 730QED                      | Convertible | [e7b8057036](https://linux-hardware.org/?probe=e7b8057036) | Dec 04, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [b3a0f94dfd](https://linux-hardware.org/?probe=b3a0f94dfd) | Dec 04, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [e31c4454c6](https://linux-hardware.org/?probe=e31c4454c6) | Dec 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [8fd5e3b166](https://linux-hardware.org/?probe=8fd5e3b166) | Dec 04, 2023 |
| eMachines     | eME732G                     | Notebook    | [931569e396](https://linux-hardware.org/?probe=931569e396) | Dec 03, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [7a78497797](https://linux-hardware.org/?probe=7a78497797) | Dec 03, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [d12c9b1f20](https://linux-hardware.org/?probe=d12c9b1f20) | Dec 03, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [166b024a63](https://linux-hardware.org/?probe=166b024a63) | Dec 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [427b578e83](https://linux-hardware.org/?probe=427b578e83) | Dec 02, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [d923b4bdf8](https://linux-hardware.org/?probe=d923b4bdf8) | Dec 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [f9629d4399](https://linux-hardware.org/?probe=f9629d4399) | Dec 02, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [26d7ac2396](https://linux-hardware.org/?probe=26d7ac2396) | Dec 02, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9516f4d644](https://linux-hardware.org/?probe=9516f4d644) | Dec 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [abb3c226ed](https://linux-hardware.org/?probe=abb3c226ed) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [2fcc002511](https://linux-hardware.org/?probe=2fcc002511) | Dec 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ff37eb859a](https://linux-hardware.org/?probe=ff37eb859a) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [7f6b5fd810](https://linux-hardware.org/?probe=7f6b5fd810) | Dec 01, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [0b156341f6](https://linux-hardware.org/?probe=0b156341f6) | Dec 01, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [997c41ef61](https://linux-hardware.org/?probe=997c41ef61) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | Notebook    | [b52ce46b0d](https://linux-hardware.org/?probe=b52ce46b0d) | Dec 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [88bd7270db](https://linux-hardware.org/?probe=88bd7270db) | Dec 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [cafac3babc](https://linux-hardware.org/?probe=cafac3babc) | Dec 01, 2023 |
| Blue Bird     | Bluebird PC                 | Tablet      | [efcf788f14](https://linux-hardware.org/?probe=efcf788f14) | Nov 30, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [86519a17c4](https://linux-hardware.org/?probe=86519a17c4) | Nov 30, 2023 |
| AZW           | LZX TBD                     | Desktop     | [11f35f4369](https://linux-hardware.org/?probe=11f35f4369) | Nov 30, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [be4ecb6dfa](https://linux-hardware.org/?probe=be4ecb6dfa) | Nov 29, 2023 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [6fe23dd80e](https://linux-hardware.org/?probe=6fe23dd80e) | Nov 28, 2023 |
| HP            | 355 G2                      | Notebook    | [bb79df3643](https://linux-hardware.org/?probe=bb79df3643) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a35b8ef607](https://linux-hardware.org/?probe=a35b8ef607) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1f830eb37e](https://linux-hardware.org/?probe=1f830eb37e) | Nov 27, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [fc19161855](https://linux-hardware.org/?probe=fc19161855) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e38428746a](https://linux-hardware.org/?probe=e38428746a) | Nov 27, 2023 |
| Micro Comp... | Venus series                | Notebook    | [fd9dbf149e](https://linux-hardware.org/?probe=fd9dbf149e) | Nov 27, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4b4737d484](https://linux-hardware.org/?probe=4b4737d484) | Nov 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [16761c9d57](https://linux-hardware.org/?probe=16761c9d57) | Nov 27, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8474959120](https://linux-hardware.org/?probe=8474959120) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [12a76ad0cd](https://linux-hardware.org/?probe=12a76ad0cd) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1878fa087a](https://linux-hardware.org/?probe=1878fa087a) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [7a0adaf9f3](https://linux-hardware.org/?probe=7a0adaf9f3) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [b96e460a4f](https://linux-hardware.org/?probe=b96e460a4f) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [7c92224aed](https://linux-hardware.org/?probe=7c92224aed) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [57a3d9064a](https://linux-hardware.org/?probe=57a3d9064a) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [a4c63ff9b4](https://linux-hardware.org/?probe=a4c63ff9b4) | Nov 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [2b5e71ca1e](https://linux-hardware.org/?probe=2b5e71ca1e) | Nov 24, 2023 |
| DERE          | Unknown                     | Tablet      | [0b81551c86](https://linux-hardware.org/?probe=0b81551c86) | Nov 24, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [106d0f0bff](https://linux-hardware.org/?probe=106d0f0bff) | Nov 24, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [16e9af1d1a](https://linux-hardware.org/?probe=16e9af1d1a) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [48112cbfe0](https://linux-hardware.org/?probe=48112cbfe0) | Nov 24, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [1ad50e2862](https://linux-hardware.org/?probe=1ad50e2862) | Nov 23, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [c60e251b40](https://linux-hardware.org/?probe=c60e251b40) | Nov 23, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [7b466d7f56](https://linux-hardware.org/?probe=7b466d7f56) | Nov 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [39c4acf035](https://linux-hardware.org/?probe=39c4acf035) | Nov 22, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [8c6fd80245](https://linux-hardware.org/?probe=8c6fd80245) | Nov 22, 2023 |
| Lenovo        | ThinkCentre M91p 4518A31    | Desktop     | [9031421465](https://linux-hardware.org/?probe=9031421465) | Nov 22, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [30d6da52fa](https://linux-hardware.org/?probe=30d6da52fa) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [195e3a2ce6](https://linux-hardware.org/?probe=195e3a2ce6) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [af566d6f0c](https://linux-hardware.org/?probe=af566d6f0c) | Nov 22, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [47105264f8](https://linux-hardware.org/?probe=47105264f8) | Nov 22, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [cd86a8c45b](https://linux-hardware.org/?probe=cd86a8c45b) | Nov 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| HP            | 2AA7 H                      | Desktop     | [c98041f477](https://linux-hardware.org/?probe=c98041f477) | Nov 21, 2023 |
| CHIPHD        | NT125D                      | Notebook    | [44dab561a1](https://linux-hardware.org/?probe=44dab561a1) | Nov 21, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [e696c3dd13](https://linux-hardware.org/?probe=e696c3dd13) | Nov 21, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07e18044ae](https://linux-hardware.org/?probe=07e18044ae) | Nov 21, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a6763208d](https://linux-hardware.org/?probe=7a6763208d) | Nov 21, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [c3fc46a4a5](https://linux-hardware.org/?probe=c3fc46a4a5) | Nov 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6066ce2199](https://linux-hardware.org/?probe=6066ce2199) | Nov 20, 2023 |
| PC Special... | Lafite Pro II 15            | Notebook    | [b7b85ab8ce](https://linux-hardware.org/?probe=b7b85ab8ce) | Nov 20, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [7728c1ff4c](https://linux-hardware.org/?probe=7728c1ff4c) | Nov 20, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [6175f06df9](https://linux-hardware.org/?probe=6175f06df9) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | Desktop     | [dd2bdfb403](https://linux-hardware.org/?probe=dd2bdfb403) | Nov 20, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f4c78fb767](https://linux-hardware.org/?probe=f4c78fb767) | Nov 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [2f5e048964](https://linux-hardware.org/?probe=2f5e048964) | Nov 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [00c2d45d1d](https://linux-hardware.org/?probe=00c2d45d1d) | Nov 19, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [1aed7bfcb8](https://linux-hardware.org/?probe=1aed7bfcb8) | Nov 19, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [0de89fd40b](https://linux-hardware.org/?probe=0de89fd40b) | Nov 19, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [8c24f72ac9](https://linux-hardware.org/?probe=8c24f72ac9) | Nov 19, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8049743efd](https://linux-hardware.org/?probe=8049743efd) | Nov 19, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [883da32584](https://linux-hardware.org/?probe=883da32584) | Nov 18, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c845b4f25f](https://linux-hardware.org/?probe=c845b4f25f) | Nov 18, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8b7c376d](https://linux-hardware.org/?probe=4a8b7c376d) | Nov 18, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [43e84fe856](https://linux-hardware.org/?probe=43e84fe856) | Nov 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0c9b59ab03](https://linux-hardware.org/?probe=0c9b59ab03) | Nov 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [391e71ffae](https://linux-hardware.org/?probe=391e71ffae) | Nov 17, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [69d85e6c31](https://linux-hardware.org/?probe=69d85e6c31) | Nov 16, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [dc260fc224](https://linux-hardware.org/?probe=dc260fc224) | Nov 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [adab9bb3b4](https://linux-hardware.org/?probe=adab9bb3b4) | Nov 15, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [2902bc3e9f](https://linux-hardware.org/?probe=2902bc3e9f) | Nov 15, 2023 |
| Dell          | Latitude 5521               | Notebook    | [2cd2e72764](https://linux-hardware.org/?probe=2cd2e72764) | Nov 15, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [1f783e1865](https://linux-hardware.org/?probe=1f783e1865) | Nov 14, 2023 |
| Dell          | Latitude E7450              | Notebook    | [500f23ef78](https://linux-hardware.org/?probe=500f23ef78) | Nov 14, 2023 |
| HP            | ProBook 6570b               | Notebook    | [edf0d74b51](https://linux-hardware.org/?probe=edf0d74b51) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [b158de590e](https://linux-hardware.org/?probe=b158de590e) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [25455f055b](https://linux-hardware.org/?probe=25455f055b) | Nov 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [585ce3241c](https://linux-hardware.org/?probe=585ce3241c) | Nov 13, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0874caf8a9](https://linux-hardware.org/?probe=0874caf8a9) | Nov 13, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [8fd2ed0ba7](https://linux-hardware.org/?probe=8fd2ed0ba7) | Nov 13, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [2166a882d2](https://linux-hardware.org/?probe=2166a882d2) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6d1d512f69](https://linux-hardware.org/?probe=6d1d512f69) | Nov 12, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [872e6f2ca5](https://linux-hardware.org/?probe=872e6f2ca5) | Nov 12, 2023 |
| Jumper        | EZbook                      | Notebook    | [682c154cdb](https://linux-hardware.org/?probe=682c154cdb) | Nov 12, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [5ef7be7906](https://linux-hardware.org/?probe=5ef7be7906) | Nov 12, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [0afc087be6](https://linux-hardware.org/?probe=0afc087be6) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [8762b09fbd](https://linux-hardware.org/?probe=8762b09fbd) | Nov 12, 2023 |
| ASUSTek       | Q524UQ                      | Notebook    | [0fe339b29a](https://linux-hardware.org/?probe=0fe339b29a) | Nov 11, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [951f01b614](https://linux-hardware.org/?probe=951f01b614) | Nov 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [1215d8475b](https://linux-hardware.org/?probe=1215d8475b) | Nov 11, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [9d1efed149](https://linux-hardware.org/?probe=9d1efed149) | Nov 11, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [d9a8e46b60](https://linux-hardware.org/?probe=d9a8e46b60) | Nov 11, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [f34d67b79a](https://linux-hardware.org/?probe=f34d67b79a) | Nov 11, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [9fde81d361](https://linux-hardware.org/?probe=9fde81d361) | Nov 10, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [3442cd2670](https://linux-hardware.org/?probe=3442cd2670) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [d91c0b4b6f](https://linux-hardware.org/?probe=d91c0b4b6f) | Nov 10, 2023 |
| Lenovo        | ThinkPad T480s 20L7001MH... | Notebook    | [f5c3846dce](https://linux-hardware.org/?probe=f5c3846dce) | Nov 10, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [0ec19aab02](https://linux-hardware.org/?probe=0ec19aab02) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3f1d1d36ef](https://linux-hardware.org/?probe=3f1d1d36ef) | Nov 10, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [8775266ad7](https://linux-hardware.org/?probe=8775266ad7) | Nov 10, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [85e2b37a15](https://linux-hardware.org/?probe=85e2b37a15) | Nov 10, 2023 |
| HP            | 86F3 00100                  | All in one  | [5ac5555396](https://linux-hardware.org/?probe=5ac5555396) | Nov 09, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ecb49b0454](https://linux-hardware.org/?probe=ecb49b0454) | Nov 09, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5b67ed0642](https://linux-hardware.org/?probe=5b67ed0642) | Nov 09, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [faf465319b](https://linux-hardware.org/?probe=faf465319b) | Nov 09, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [76926e3f2c](https://linux-hardware.org/?probe=76926e3f2c) | Nov 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [f5a16ecf27](https://linux-hardware.org/?probe=f5a16ecf27) | Nov 09, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [a26aceca7f](https://linux-hardware.org/?probe=a26aceca7f) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [ab1a7393ef](https://linux-hardware.org/?probe=ab1a7393ef) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [6badd92c4f](https://linux-hardware.org/?probe=6badd92c4f) | Nov 08, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [dbfe362cd8](https://linux-hardware.org/?probe=dbfe362cd8) | Nov 08, 2023 |
| MSI           | MAG B660M MORTAR            | Desktop     | [a8c3434f4e](https://linux-hardware.org/?probe=a8c3434f4e) | Nov 07, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [34c0a2ec4c](https://linux-hardware.org/?probe=34c0a2ec4c) | Nov 07, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a599d9b486](https://linux-hardware.org/?probe=a599d9b486) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8ef23bbac8](https://linux-hardware.org/?probe=8ef23bbac8) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [003be2f197](https://linux-hardware.org/?probe=003be2f197) | Nov 07, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [9b3ffcb3d5](https://linux-hardware.org/?probe=9b3ffcb3d5) | Nov 07, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [fecc1b7dff](https://linux-hardware.org/?probe=fecc1b7dff) | Nov 07, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [530b650093](https://linux-hardware.org/?probe=530b650093) | Nov 07, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [01884ea8de](https://linux-hardware.org/?probe=01884ea8de) | Nov 07, 2023 |
| Dell          | Precision 3561              | Notebook    | [8fd1f7d515](https://linux-hardware.org/?probe=8fd1f7d515) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6f9ee3fea0](https://linux-hardware.org/?probe=6f9ee3fea0) | Nov 06, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [f72df0be76](https://linux-hardware.org/?probe=f72df0be76) | Nov 06, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [8cd8d5ade1](https://linux-hardware.org/?probe=8cd8d5ade1) | Nov 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [fef5a2e8ae](https://linux-hardware.org/?probe=fef5a2e8ae) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | Notebook    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [e16dbbaf8b](https://linux-hardware.org/?probe=e16dbbaf8b) | Nov 05, 2023 |
| Unknown       | H96 Max X3                  | Soc         | [362598f755](https://linux-hardware.org/?probe=362598f755) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [82bf4f530a](https://linux-hardware.org/?probe=82bf4f530a) | Nov 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [5f192519d4](https://linux-hardware.org/?probe=5f192519d4) | Nov 05, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [1d1311204e](https://linux-hardware.org/?probe=1d1311204e) | Nov 05, 2023 |
| HP            | 8184 X4                     | Desktop     | [fb7f295b44](https://linux-hardware.org/?probe=fb7f295b44) | Nov 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f154c5979f](https://linux-hardware.org/?probe=f154c5979f) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [85733c0ec0](https://linux-hardware.org/?probe=85733c0ec0) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8a4147b40a](https://linux-hardware.org/?probe=8a4147b40a) | Nov 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [482f1a0fe7](https://linux-hardware.org/?probe=482f1a0fe7) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [a386eceffe](https://linux-hardware.org/?probe=a386eceffe) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee2a20b30a](https://linux-hardware.org/?probe=ee2a20b30a) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [1e6407d9d5](https://linux-hardware.org/?probe=1e6407d9d5) | Nov 04, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a513bb8188](https://linux-hardware.org/?probe=a513bb8188) | Nov 04, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [04e96e2742](https://linux-hardware.org/?probe=04e96e2742) | Nov 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [dd81ed04ea](https://linux-hardware.org/?probe=dd81ed04ea) | Nov 04, 2023 |
| HP            | Notebook                    | Notebook    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ac9818b1f](https://linux-hardware.org/?probe=5ac9818b1f) | Nov 03, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [b91d7803a2](https://linux-hardware.org/?probe=b91d7803a2) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c9e7b12e63](https://linux-hardware.org/?probe=c9e7b12e63) | Nov 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c2df6f267b](https://linux-hardware.org/?probe=c2df6f267b) | Nov 03, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [3030ad2bc8](https://linux-hardware.org/?probe=3030ad2bc8) | Nov 02, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6aa1f3a294](https://linux-hardware.org/?probe=6aa1f3a294) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [3e65346dfd](https://linux-hardware.org/?probe=3e65346dfd) | Nov 02, 2023 |
| Wortmann      | 1220777_1400328             | Notebook    | [778b1abc73](https://linux-hardware.org/?probe=778b1abc73) | Nov 02, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [677490b7c2](https://linux-hardware.org/?probe=677490b7c2) | Nov 02, 2023 |
| ASRock        | P67 Professional            | Desktop     | [c998340fa9](https://linux-hardware.org/?probe=c998340fa9) | Nov 02, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [2efa290a39](https://linux-hardware.org/?probe=2efa290a39) | Nov 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [0f4435d620](https://linux-hardware.org/?probe=0f4435d620) | Nov 02, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [cde7923bf2](https://linux-hardware.org/?probe=cde7923bf2) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [493dcbc1f8](https://linux-hardware.org/?probe=493dcbc1f8) | Nov 01, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [67863a015a](https://linux-hardware.org/?probe=67863a015a) | Nov 01, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [f0b1ef4bc8](https://linux-hardware.org/?probe=f0b1ef4bc8) | Nov 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [6895dd827a](https://linux-hardware.org/?probe=6895dd827a) | Nov 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [50a30d4ebd](https://linux-hardware.org/?probe=50a30d4ebd) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [f65225d50a](https://linux-hardware.org/?probe=f65225d50a) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [69f7a5ebed](https://linux-hardware.org/?probe=69f7a5ebed) | Nov 01, 2023 |
| Sony          | VPCSA3J1E                   | Notebook    | [99b0d275ec](https://linux-hardware.org/?probe=99b0d275ec) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| HP            | 2AF7                        | Desktop     | [0a2c239b75](https://linux-hardware.org/?probe=0a2c239b75) | Nov 01, 2023 |
| Dell          | Latitude 7290               | Notebook    | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| ASUSTek       | BT1AD                       | Desktop     | [133784e5ee](https://linux-hardware.org/?probe=133784e5ee) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [1e3f228931](https://linux-hardware.org/?probe=1e3f228931) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [10382e8ed6](https://linux-hardware.org/?probe=10382e8ed6) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | Notebook    | [ebcacada49](https://linux-hardware.org/?probe=ebcacada49) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | Notebook    | [d8658ea415](https://linux-hardware.org/?probe=d8658ea415) | Oct 31, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [c889a29b7f](https://linux-hardware.org/?probe=c889a29b7f) | Oct 31, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [77d9982cf2](https://linux-hardware.org/?probe=77d9982cf2) | Oct 31, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [84064baf19](https://linux-hardware.org/?probe=84064baf19) | Oct 31, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [8a9f37b293](https://linux-hardware.org/?probe=8a9f37b293) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 15            | Notebook    | [2cad75b0fc](https://linux-hardware.org/?probe=2cad75b0fc) | Oct 31, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fe3816864f](https://linux-hardware.org/?probe=fe3816864f) | Oct 30, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [babfdba8f2](https://linux-hardware.org/?probe=babfdba8f2) | Oct 30, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [4825358a5d](https://linux-hardware.org/?probe=4825358a5d) | Oct 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5d7ab82de7](https://linux-hardware.org/?probe=5d7ab82de7) | Oct 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [986edacf9a](https://linux-hardware.org/?probe=986edacf9a) | Oct 30, 2023 |
| HP            | 2AF7                        | Desktop     | [04c535a13d](https://linux-hardware.org/?probe=04c535a13d) | Oct 30, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [7ffe987b92](https://linux-hardware.org/?probe=7ffe987b92) | Oct 30, 2023 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [b160015184](https://linux-hardware.org/?probe=b160015184) | Oct 29, 2023 |
| HP            | 1790                        | Desktop     | [8bde9984db](https://linux-hardware.org/?probe=8bde9984db) | Oct 29, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [42e6514c85](https://linux-hardware.org/?probe=42e6514c85) | Oct 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [90ab9dafc5](https://linux-hardware.org/?probe=90ab9dafc5) | Oct 29, 2023 |
| Dell          | Precision M6800             | Notebook    | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0f69bc7ea0](https://linux-hardware.org/?probe=0f69bc7ea0) | Oct 28, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9b3c09e73a](https://linux-hardware.org/?probe=9b3c09e73a) | Oct 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [e340ddc535](https://linux-hardware.org/?probe=e340ddc535) | Oct 27, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [9266111091](https://linux-hardware.org/?probe=9266111091) | Oct 27, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [3bc6d6cfda](https://linux-hardware.org/?probe=3bc6d6cfda) | Oct 27, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| EXTRA Comp... | MS-1758                     | Notebook    | [eced546e79](https://linux-hardware.org/?probe=eced546e79) | Oct 26, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [8516768801](https://linux-hardware.org/?probe=8516768801) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [d1c293b080](https://linux-hardware.org/?probe=d1c293b080) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| SYWZ          | S210H Series                | Desktop     | [9239922f80](https://linux-hardware.org/?probe=9239922f80) | Oct 26, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [35b07b6e34](https://linux-hardware.org/?probe=35b07b6e34) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [6e87d140be](https://linux-hardware.org/?probe=6e87d140be) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c64594fac3](https://linux-hardware.org/?probe=c64594fac3) | Oct 25, 2023 |
| WUYING        | NS01-4BGXG                  | Notebook    | [5c999216df](https://linux-hardware.org/?probe=5c999216df) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [36893aadc0](https://linux-hardware.org/?probe=36893aadc0) | Oct 25, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e25ec0e229](https://linux-hardware.org/?probe=e25ec0e229) | Oct 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [3bd963fd9e](https://linux-hardware.org/?probe=3bd963fd9e) | Oct 24, 2023 |
| HP            | 14                          | Notebook    | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | Notebook    | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [67564f88a0](https://linux-hardware.org/?probe=67564f88a0) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | Notebook    | [0f08eb340b](https://linux-hardware.org/?probe=0f08eb340b) | Oct 24, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [06247cab2e](https://linux-hardware.org/?probe=06247cab2e) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c74b24edc0](https://linux-hardware.org/?probe=c74b24edc0) | Oct 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| Colorful T... | BATTLE-AX B450M-HD V14      | Desktop     | [314500a8ed](https://linux-hardware.org/?probe=314500a8ed) | Oct 23, 2023 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [d71e04d478](https://linux-hardware.org/?probe=d71e04d478) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [55c5bbce9f](https://linux-hardware.org/?probe=55c5bbce9f) | Oct 23, 2023 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [806cdb2bef](https://linux-hardware.org/?probe=806cdb2bef) | Oct 23, 2023 |
| AZW           | SEi                         | Notebook    | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| Dell          | Latitude E6520              | Notebook    | [5d73c1d444](https://linux-hardware.org/?probe=5d73c1d444) | Oct 22, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [bd8cdfe190](https://linux-hardware.org/?probe=bd8cdfe190) | Oct 22, 2023 |
| HP            | ProBook 4340s               | Notebook    | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [db0826b2fc](https://linux-hardware.org/?probe=db0826b2fc) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [5962f780e9](https://linux-hardware.org/?probe=5962f780e9) | Oct 22, 2023 |
| ECS           | CHICAGO2                    | Desktop     | [e33ec52f5a](https://linux-hardware.org/?probe=e33ec52f5a) | Oct 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [9990a91f59](https://linux-hardware.org/?probe=9990a91f59) | Oct 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [33b1df369f](https://linux-hardware.org/?probe=33b1df369f) | Oct 21, 2023 |
| AZW           | SER V01                     | Mini pc     | [25ca388d81](https://linux-hardware.org/?probe=25ca388d81) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [130d199934](https://linux-hardware.org/?probe=130d199934) | Oct 21, 2023 |
| AZW           | SER V1                      | Desktop     | [60f9b9fdd9](https://linux-hardware.org/?probe=60f9b9fdd9) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [f23d0ff7da](https://linux-hardware.org/?probe=f23d0ff7da) | Oct 20, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4870f90403](https://linux-hardware.org/?probe=4870f90403) | Oct 20, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [91f29a5a63](https://linux-hardware.org/?probe=91f29a5a63) | Oct 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [09b04f5fd5](https://linux-hardware.org/?probe=09b04f5fd5) | Oct 20, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [a7f26cedd6](https://linux-hardware.org/?probe=a7f26cedd6) | Oct 20, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [acf7108592](https://linux-hardware.org/?probe=acf7108592) | Oct 20, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [38436a17ef](https://linux-hardware.org/?probe=38436a17ef) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [4bfe18fe76](https://linux-hardware.org/?probe=4bfe18fe76) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [e83ad29e5e](https://linux-hardware.org/?probe=e83ad29e5e) | Oct 20, 2023 |
| ASUSTek       | X450LCP                     | Notebook    | [ae3fec47c6](https://linux-hardware.org/?probe=ae3fec47c6) | Oct 19, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8fd9d07f5d](https://linux-hardware.org/?probe=8fd9d07f5d) | Oct 19, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [c2215ccabb](https://linux-hardware.org/?probe=c2215ccabb) | Oct 19, 2023 |
| Acer          | AOD270                      | Notebook    | [20d5a5477c](https://linux-hardware.org/?probe=20d5a5477c) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aad7482915](https://linux-hardware.org/?probe=aad7482915) | Oct 19, 2023 |
| HP            | G60                         | Notebook    | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0c25658c6d](https://linux-hardware.org/?probe=0c25658c6d) | Oct 18, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [0944131c12](https://linux-hardware.org/?probe=0944131c12) | Oct 18, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [413edf8cdb](https://linux-hardware.org/?probe=413edf8cdb) | Oct 18, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [dd8c738dc7](https://linux-hardware.org/?probe=dd8c738dc7) | Oct 18, 2023 |
| Dell          | Precision 7520              | Notebook    | [bd78f68578](https://linux-hardware.org/?probe=bd78f68578) | Oct 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [be8c08b665](https://linux-hardware.org/?probe=be8c08b665) | Oct 18, 2023 |
| Dell          | G7 7790                     | Notebook    | [250d61d6a7](https://linux-hardware.org/?probe=250d61d6a7) | Oct 18, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [05ee51f822](https://linux-hardware.org/?probe=05ee51f822) | Oct 18, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [77690da2b6](https://linux-hardware.org/?probe=77690da2b6) | Oct 17, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [86d888a421](https://linux-hardware.org/?probe=86d888a421) | Oct 17, 2023 |
| GMKtec        | NucBox5                     | Notebook    | [4b4319490d](https://linux-hardware.org/?probe=4b4319490d) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| Lenovo        | 01KN179                     | Server      | [9f36a4143d](https://linux-hardware.org/?probe=9f36a4143d) | Oct 16, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [5860734f3a](https://linux-hardware.org/?probe=5860734f3a) | Oct 16, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [6b4c286aca](https://linux-hardware.org/?probe=6b4c286aca) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| AMI           | Intel                       | Convertible | [38a3df30fe](https://linux-hardware.org/?probe=38a3df30fe) | Oct 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bc33324b0d](https://linux-hardware.org/?probe=bc33324b0d) | Oct 15, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [059145d98c](https://linux-hardware.org/?probe=059145d98c) | Oct 15, 2023 |
| Dell          | Latitude E7470              | Notebook    | [59258fc186](https://linux-hardware.org/?probe=59258fc186) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [e4bcb7e688](https://linux-hardware.org/?probe=e4bcb7e688) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [92049beb26](https://linux-hardware.org/?probe=92049beb26) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [3eff97b04d](https://linux-hardware.org/?probe=3eff97b04d) | Oct 15, 2023 |
| HP            | 829A                        | Mini pc     | [f9af7b48fe](https://linux-hardware.org/?probe=f9af7b48fe) | Oct 14, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1dba250310](https://linux-hardware.org/?probe=1dba250310) | Oct 14, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [09a90189ec](https://linux-hardware.org/?probe=09a90189ec) | Oct 14, 2023 |
| Intel         | JSL MRD                     | Desktop     | [a39b6e2f92](https://linux-hardware.org/?probe=a39b6e2f92) | Oct 14, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [1bea1dafbf](https://linux-hardware.org/?probe=1bea1dafbf) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7045758f33](https://linux-hardware.org/?probe=7045758f33) | Oct 13, 2023 |
| ASUSTek       | PRIME H310M-C               | Desktop     | [2696ecde8d](https://linux-hardware.org/?probe=2696ecde8d) | Oct 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f18ac93db8](https://linux-hardware.org/?probe=f18ac93db8) | Oct 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [8684995c92](https://linux-hardware.org/?probe=8684995c92) | Oct 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b5e38fe27e](https://linux-hardware.org/?probe=b5e38fe27e) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [bf26581f5d](https://linux-hardware.org/?probe=bf26581f5d) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [e6c5f903ce](https://linux-hardware.org/?probe=e6c5f903ce) | Oct 12, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [09d2bdba5b](https://linux-hardware.org/?probe=09d2bdba5b) | Oct 12, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [f48331f12b](https://linux-hardware.org/?probe=f48331f12b) | Oct 12, 2023 |
| HP            | ProBook 4540s               | Notebook    | [c3be7c74a0](https://linux-hardware.org/?probe=c3be7c74a0) | Oct 11, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Notebook      | W510LU                      | Notebook    | [7b46aa1486](https://linux-hardware.org/?probe=7b46aa1486) | Oct 11, 2023 |
| ASRock        | X79 Extreme9                | Desktop     | [4a0805a07a](https://linux-hardware.org/?probe=4a0805a07a) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [6ea5ba513f](https://linux-hardware.org/?probe=6ea5ba513f) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [f9c4374e7c](https://linux-hardware.org/?probe=f9c4374e7c) | Oct 11, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [3fe42a607c](https://linux-hardware.org/?probe=3fe42a607c) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [95ec4384f9](https://linux-hardware.org/?probe=95ec4384f9) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [4d218edfa4](https://linux-hardware.org/?probe=4d218edfa4) | Oct 10, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [3ba4207fd0](https://linux-hardware.org/?probe=3ba4207fd0) | Oct 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [f6dac1e5f6](https://linux-hardware.org/?probe=f6dac1e5f6) | Oct 09, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [5f179c5f02](https://linux-hardware.org/?probe=5f179c5f02) | Oct 09, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [02211f49db](https://linux-hardware.org/?probe=02211f49db) | Oct 08, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [38b7ffd223](https://linux-hardware.org/?probe=38b7ffd223) | Oct 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [26ba02b08e](https://linux-hardware.org/?probe=26ba02b08e) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7513e708f6](https://linux-hardware.org/?probe=7513e708f6) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [84ff0a9a08](https://linux-hardware.org/?probe=84ff0a9a08) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1505f63948](https://linux-hardware.org/?probe=1505f63948) | Oct 07, 2023 |
| Medion        | E15302                      | Notebook    | [d26c76cedf](https://linux-hardware.org/?probe=d26c76cedf) | Oct 07, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [5ff0e17804](https://linux-hardware.org/?probe=5ff0e17804) | Oct 07, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [5ac03d658c](https://linux-hardware.org/?probe=5ac03d658c) | Oct 07, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [7e01bc1824](https://linux-hardware.org/?probe=7e01bc1824) | Oct 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [364af80964](https://linux-hardware.org/?probe=364af80964) | Oct 06, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [31248aa2bf](https://linux-hardware.org/?probe=31248aa2bf) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [5b84610e15](https://linux-hardware.org/?probe=5b84610e15) | Oct 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [c5a3a209c0](https://linux-hardware.org/?probe=c5a3a209c0) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c35ab8ae2e](https://linux-hardware.org/?probe=c35ab8ae2e) | Oct 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [e796c2f9ba](https://linux-hardware.org/?probe=e796c2f9ba) | Oct 05, 2023 |
| Google        | Woomax                      | Notebook    | [2163941472](https://linux-hardware.org/?probe=2163941472) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ff1fcbaff6](https://linux-hardware.org/?probe=ff1fcbaff6) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7eca4901d4](https://linux-hardware.org/?probe=7eca4901d4) | Oct 04, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57b1771805](https://linux-hardware.org/?probe=57b1771805) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [2fdd309c6a](https://linux-hardware.org/?probe=2fdd309c6a) | Oct 04, 2023 |
| ASUSTek       | E2KM1I-DELUXE               | Desktop     | [bb9493309a](https://linux-hardware.org/?probe=bb9493309a) | Oct 04, 2023 |
| HP            | 3396                        | Desktop     | [e83b1b4945](https://linux-hardware.org/?probe=e83b1b4945) | Oct 03, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [8892c7239e](https://linux-hardware.org/?probe=8892c7239e) | Oct 03, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [56a4c9aa55](https://linux-hardware.org/?probe=56a4c9aa55) | Oct 03, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [a9e2c9b64e](https://linux-hardware.org/?probe=a9e2c9b64e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0d7876c259](https://linux-hardware.org/?probe=0d7876c259) | Oct 03, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [4074b6cda1](https://linux-hardware.org/?probe=4074b6cda1) | Oct 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f7231bda4](https://linux-hardware.org/?probe=3f7231bda4) | Oct 03, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [f349819e0a](https://linux-hardware.org/?probe=f349819e0a) | Oct 02, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [124cb639c1](https://linux-hardware.org/?probe=124cb639c1) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5fe25903c1](https://linux-hardware.org/?probe=5fe25903c1) | Oct 02, 2023 |
| Google        | Blorb                       | Notebook    | [04e37bafe3](https://linux-hardware.org/?probe=04e37bafe3) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [122f1d4ca8](https://linux-hardware.org/?probe=122f1d4ca8) | Oct 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [f8ee109cbd](https://linux-hardware.org/?probe=f8ee109cbd) | Oct 01, 2023 |
| Schenker      | VIA 15 Pro (M22)            | Notebook    | [1919690674](https://linux-hardware.org/?probe=1919690674) | Oct 01, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b3eb082c5e](https://linux-hardware.org/?probe=b3eb082c5e) | Oct 01, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [a44e0088f6](https://linux-hardware.org/?probe=a44e0088f6) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1330485afc](https://linux-hardware.org/?probe=1330485afc) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [4a47d466d9](https://linux-hardware.org/?probe=4a47d466d9) | Sep 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [c9aca83f04](https://linux-hardware.org/?probe=c9aca83f04) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [b87e9dd9ad](https://linux-hardware.org/?probe=b87e9dd9ad) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [89791e7bf0](https://linux-hardware.org/?probe=89791e7bf0) | Sep 29, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6f07d7c834](https://linux-hardware.org/?probe=6f07d7c834) | Sep 29, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [df48fa7e96](https://linux-hardware.org/?probe=df48fa7e96) | Sep 29, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| MSI           | H97M-G43                    | Desktop     | [b74346acb3](https://linux-hardware.org/?probe=b74346acb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [76937ddbce](https://linux-hardware.org/?probe=76937ddbce) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [a329c5630e](https://linux-hardware.org/?probe=a329c5630e) | Sep 28, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [e54490e96a](https://linux-hardware.org/?probe=e54490e96a) | Sep 27, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [3286090099](https://linux-hardware.org/?probe=3286090099) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [2f574aa287](https://linux-hardware.org/?probe=2f574aa287) | Sep 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [128658b9f0](https://linux-hardware.org/?probe=128658b9f0) | Sep 26, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9f32819945](https://linux-hardware.org/?probe=9f32819945) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| CHIPHD        | NT125D                      | Notebook    | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Acer          | FX58M                       | Desktop     | [e24f36e0bd](https://linux-hardware.org/?probe=e24f36e0bd) | Sep 26, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [37840dad1c](https://linux-hardware.org/?probe=37840dad1c) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [1b72e3fe1c](https://linux-hardware.org/?probe=1b72e3fe1c) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [0281cc244a](https://linux-hardware.org/?probe=0281cc244a) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe1163082c](https://linux-hardware.org/?probe=fe1163082c) | Sep 26, 2023 |
| Lenovo        | B480 20140                  | Notebook    | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [56cd5e0bfd](https://linux-hardware.org/?probe=56cd5e0bfd) | Sep 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4095fbc19e](https://linux-hardware.org/?probe=4095fbc19e) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [faf68444bc](https://linux-hardware.org/?probe=faf68444bc) | Sep 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2691aa5f87](https://linux-hardware.org/?probe=2691aa5f87) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7f88191a7b](https://linux-hardware.org/?probe=7f88191a7b) | Sep 23, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ad1f9f63c0](https://linux-hardware.org/?probe=ad1f9f63c0) | Sep 22, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [583c577b02](https://linux-hardware.org/?probe=583c577b02) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [dc831a82cd](https://linux-hardware.org/?probe=dc831a82cd) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| HP            | 18E7                        | Desktop     | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [b6d619d509](https://linux-hardware.org/?probe=b6d619d509) | Sep 21, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [d4060b585a](https://linux-hardware.org/?probe=d4060b585a) | Sep 20, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [42b79f2641](https://linux-hardware.org/?probe=42b79f2641) | Sep 20, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [c7142a0d96](https://linux-hardware.org/?probe=c7142a0d96) | Sep 20, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [a24c6808ba](https://linux-hardware.org/?probe=a24c6808ba) | Sep 20, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [e753271d63](https://linux-hardware.org/?probe=e753271d63) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [4ffee8598b](https://linux-hardware.org/?probe=4ffee8598b) | Sep 19, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c8a7f18e5d](https://linux-hardware.org/?probe=c8a7f18e5d) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [6f676cd559](https://linux-hardware.org/?probe=6f676cd559) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [17e0d2ab92](https://linux-hardware.org/?probe=17e0d2ab92) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [e6db76aa66](https://linux-hardware.org/?probe=e6db76aa66) | Sep 17, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [76d6f570a8](https://linux-hardware.org/?probe=76d6f570a8) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [37d6d12772](https://linux-hardware.org/?probe=37d6d12772) | Sep 15, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [fabf2bef4c](https://linux-hardware.org/?probe=fabf2bef4c) | Sep 15, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [a73abd96f1](https://linux-hardware.org/?probe=a73abd96f1) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [de7e036404](https://linux-hardware.org/?probe=de7e036404) | Sep 15, 2023 |
| HP            | 0A9Ch                       | Desktop     | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [3a1c100a69](https://linux-hardware.org/?probe=3a1c100a69) | Sep 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [15256fdeb2](https://linux-hardware.org/?probe=15256fdeb2) | Sep 14, 2023 |
| Notebook      | P65_P67SA                   | Notebook    | [4d11ae0ff7](https://linux-hardware.org/?probe=4d11ae0ff7) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [20ad52b9a4](https://linux-hardware.org/?probe=20ad52b9a4) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [959fc9f783](https://linux-hardware.org/?probe=959fc9f783) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [641089b224](https://linux-hardware.org/?probe=641089b224) | Sep 13, 2023 |
| AZW           | MINI S 10                   | Desktop     | [5cd0efea8b](https://linux-hardware.org/?probe=5cd0efea8b) | Sep 12, 2023 |
| HP            | 1998                        | Desktop     | [c3451afea8](https://linux-hardware.org/?probe=c3451afea8) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [9ea0aa4b28](https://linux-hardware.org/?probe=9ea0aa4b28) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [b12897892a](https://linux-hardware.org/?probe=b12897892a) | Sep 09, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [33cc2ca68e](https://linux-hardware.org/?probe=33cc2ca68e) | Sep 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [23da68a72c](https://linux-hardware.org/?probe=23da68a72c) | Sep 09, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [5180b1e51e](https://linux-hardware.org/?probe=5180b1e51e) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6f3051262d](https://linux-hardware.org/?probe=6f3051262d) | Sep 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [fe6b08c772](https://linux-hardware.org/?probe=fe6b08c772) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [c0422be924](https://linux-hardware.org/?probe=c0422be924) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Notebook      | W65_67SR                    | Notebook    | [7169bc1dbb](https://linux-hardware.org/?probe=7169bc1dbb) | Sep 07, 2023 |
| Google        | Robo360                     | Notebook    | [86308cca01](https://linux-hardware.org/?probe=86308cca01) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f081f44bda](https://linux-hardware.org/?probe=f081f44bda) | Sep 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Samsung       | 950QED                      | Convertible | [e15539dd35](https://linux-hardware.org/?probe=e15539dd35) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | Notebook    | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| AZW           | SER V01                     | Mini pc     | [b744dfb20a](https://linux-hardware.org/?probe=b744dfb20a) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [71da9ea288](https://linux-hardware.org/?probe=71da9ea288) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [31cb6a887e](https://linux-hardware.org/?probe=31cb6a887e) | Sep 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [cdf37a1590](https://linux-hardware.org/?probe=cdf37a1590) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [85cc9860f3](https://linux-hardware.org/?probe=85cc9860f3) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9028ba6c0f](https://linux-hardware.org/?probe=9028ba6c0f) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Dell          | XPS 9315                    | Notebook    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | Notebook    | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | Desktop     | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [5a4e0650a2](https://linux-hardware.org/?probe=5a4e0650a2) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| HP            | 212B                        | Desktop     | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| HP            | 18E7                        | Desktop     | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1f47bfe737](https://linux-hardware.org/?probe=1f47bfe737) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [65b6b29fc7](https://linux-hardware.org/?probe=65b6b29fc7) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3acc953bde](https://linux-hardware.org/?probe=3acc953bde) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccdc0814a8](https://linux-hardware.org/?probe=ccdc0814a8) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| Dell          | Precision 7780              | Notebook    | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [7bd62bca50](https://linux-hardware.org/?probe=7bd62bca50) | Aug 23, 2023 |
| Intel         | H55                         | Desktop     | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Irbis         | NB123                       | Notebook    | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c78c246642](https://linux-hardware.org/?probe=c78c246642) | Aug 20, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9a7f33c81b](https://linux-hardware.org/?probe=9a7f33c81b) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b5973b3c67](https://linux-hardware.org/?probe=b5973b3c67) | Aug 18, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [2da4b77f8a](https://linux-hardware.org/?probe=2da4b77f8a) | Aug 17, 2023 |
| Lenovo        | ThinkBook 14s Yoga G3 IR... | Convertible | [74da3f5482](https://linux-hardware.org/?probe=74da3f5482) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [f0d325d7d3](https://linux-hardware.org/?probe=f0d325d7d3) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [a395628119](https://linux-hardware.org/?probe=a395628119) | Aug 15, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [e338ac8876](https://linux-hardware.org/?probe=e338ac8876) | Aug 14, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | Notebook    | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [0c8514df53](https://linux-hardware.org/?probe=0c8514df53) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | Desktop     | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [97c78c17bd](https://linux-hardware.org/?probe=97c78c17bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| AZW           | SER V01                     | Mini pc     | [542d8da36c](https://linux-hardware.org/?probe=542d8da36c) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a71dc0067b](https://linux-hardware.org/?probe=a71dc0067b) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [3d156d18e6](https://linux-hardware.org/?probe=3d156d18e6) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [cb3d78955a](https://linux-hardware.org/?probe=cb3d78955a) | Aug 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Precision 7670              | Notebook    | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| HP            | 158A                        | Desktop     | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| HP            | 3031h                       | Desktop     | [95b5c80f67](https://linux-hardware.org/?probe=95b5c80f67) | Aug 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| HP            | 3031h                       | Desktop     | [04c8ac1eee](https://linux-hardware.org/?probe=04c8ac1eee) | Aug 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [5e552472e5](https://linux-hardware.org/?probe=5e552472e5) | Aug 03, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [4d21c35777](https://linux-hardware.org/?probe=4d21c35777) | Aug 03, 2023 |
| System76      | Galago Pro                  | Notebook    | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | 158A                        | Desktop     | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb493cc8c8](https://linux-hardware.org/?probe=cb493cc8c8) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Google        | Zako                        | Desktop     | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [65a741810c](https://linux-hardware.org/?probe=65a741810c) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [e5ad011556](https://linux-hardware.org/?probe=e5ad011556) | Jul 30, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Supermicro    | C7H61                       | Desktop     | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7c5e9b6bc6](https://linux-hardware.org/?probe=7c5e9b6bc6) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| AZW           | SER V01                     | Mini pc     | [440a88b8bf](https://linux-hardware.org/?probe=440a88b8bf) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [273533f7f8](https://linux-hardware.org/?probe=273533f7f8) | Jul 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| Dell          | 0757V0 A00                  | Desktop     | [e367a3740a](https://linux-hardware.org/?probe=e367a3740a) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HP            | G62                         | Notebook    | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | Presario CQ62               | Notebook    | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Dell          | Latitude 5289               | Convertible | [eeb009e8f5](https://linux-hardware.org/?probe=eeb009e8f5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | Notebook    | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c5028381e5](https://linux-hardware.org/?probe=c5028381e5) | Jul 20, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| HP            | 83E9                        | Desktop     | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [392b85a82b](https://linux-hardware.org/?probe=392b85a82b) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [0b447416c6](https://linux-hardware.org/?probe=0b447416c6) | Jul 15, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0008f72dbf](https://linux-hardware.org/?probe=0008f72dbf) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [745fa6a1b4](https://linux-hardware.org/?probe=745fa6a1b4) | Jul 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c453f1df6b](https://linux-hardware.org/?probe=c453f1df6b) | Jul 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [93b2067918](https://linux-hardware.org/?probe=93b2067918) | Jul 11, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [6f62e1063c](https://linux-hardware.org/?probe=6f62e1063c) | Jul 11, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | Notebook    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | Notebook    | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [9400bf75de](https://linux-hardware.org/?probe=9400bf75de) | Jul 09, 2023 |
| HP            | 2B3E                        | All in one  | [9ec58b6284](https://linux-hardware.org/?probe=9ec58b6284) | Jul 09, 2023 |
| Acer          | Predator G3-572             | Notebook    | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| MSI           | B360M MORTAR TITANIUM       | Desktop     | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Dell          | G3 3779                     | Notebook    | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [35b286ba6b](https://linux-hardware.org/?probe=35b286ba6b) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [44eaa3f5c1](https://linux-hardware.org/?probe=44eaa3f5c1) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| AZW           | SER V01                     | Mini pc     | [49552e2240](https://linux-hardware.org/?probe=49552e2240) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | Notebook    | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [673c5bfa9a](https://linux-hardware.org/?probe=673c5bfa9a) | Jul 04, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Dell          | Latitude 7530               | Notebook    | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [e76be78ba9](https://linux-hardware.org/?probe=e76be78ba9) | Jul 02, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | Desktop     | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | Notebook    | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [f953c21e8e](https://linux-hardware.org/?probe=f953c21e8e) | Jul 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| Huanan        | Unknown                     | Desktop     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | Notebook                    | Notebook    | [db641e216c](https://linux-hardware.org/?probe=db641e216c) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [e2c3a51177](https://linux-hardware.org/?probe=e2c3a51177) | Jun 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1418      | 30.55%  |
| Kubuntu 22.04   | 1189      | 25.61%  |
| Kubuntu 23.04   | 309       | 6.66%   |
| Kubuntu 22.10   | 297       | 6.4%    |
| Kubuntu 20.10   | 258       | 5.56%   |
| Kubuntu 21.10   | 242       | 5.21%   |
| Kubuntu 21.04   | 214       | 4.61%   |
| Kubuntu 18.04   | 202       | 4.35%   |
| Kubuntu 19.10   | 178       | 3.83%   |
| Kubuntu 23.10   | 145       | 3.12%   |
| Kubuntu 11      | 96        | 2.07%   |
| Kubuntu 11.1    | 26        | 0.56%   |
| Kubuntu 19.04   | 22        | 0.47%   |
| Kubuntu 16.04   | 13        | 0.28%   |
| Kubuntu         | 8         | 0.17%   |
| Kubuntu 18.10   | 7         | 0.15%   |
| Kubuntu 2.0     | 6         | 0.13%   |
| Kubuntu 17.10   | 3         | 0.06%   |
| Kubuntu 14.04   | 3         | 0.06%   |
| Kubuntu 24.04   | 2         | 0.04%   |
| Kubuntu 17.04   | 2         | 0.04%   |
| Kubuntu 20.08.3 | 1         | 0.02%   |
| Kubuntu 12.04   | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 4413      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 2.01%   |
| 5.15.0-52-generic | 84        | 1.64%   |
| 6.2.0-20-generic  | 81        | 1.58%   |
| 5.15.0-56-generic | 81        | 1.58%   |
| 5.19.0-35-generic | 70        | 1.37%   |
| 5.4.0-52-generic  | 68        | 1.33%   |
| 5.4.0-58-generic  | 59        | 1.15%   |
| 5.4.0-48-generic  | 59        | 1.15%   |
| 5.15.0-48-generic | 58        | 1.13%   |
| 6.2.0-26-generic  | 56        | 1.09%   |
| 5.15.0-46-generic | 53        | 1.04%   |
| 5.13.0-39-generic | 53        | 1.04%   |
| 5.19.0-23-generic | 52        | 1.02%   |
| 6.5.0-10-generic  | 48        | 0.94%   |
| 6.2.0-34-generic  | 47        | 0.92%   |
| 5.4.0-40-generic  | 47        | 0.92%   |
| 5.19.0-38-generic | 47        | 0.92%   |
| 5.15.0-43-generic | 44        | 0.86%   |
| 5.13.0-28-generic | 44        | 0.86%   |
| 5.19.0-31-generic | 43        | 0.84%   |
| 5.19.0-26-generic | 42        | 0.82%   |
| 5.15.0-58-generic | 42        | 0.82%   |
| 5.15.0-47-generic | 41        | 0.8%    |
| 5.15.0-41-generic | 39        | 0.76%   |
| 5.11.0-37-generic | 38        | 0.74%   |
| 5.11.0-25-generic | 38        | 0.74%   |
| 5.15.0-53-generic | 37        | 0.72%   |
| 5.13.0-30-generic | 37        | 0.72%   |
| 5.4.0-47-generic  | 36        | 0.7%    |
| 5.4.0-65-generic  | 35        | 0.68%   |
| 6.2.0-33-generic  | 34        | 0.66%   |
| 6.2.0-32-generic  | 34        | 0.66%   |
| 5.8.0-48-generic  | 34        | 0.66%   |
| 5.3.0-40-generic  | 34        | 0.66%   |
| 5.4.0-37-generic  | 33        | 0.65%   |
| 5.4.0-29-generic  | 33        | 0.65%   |
| 5.19.0-29-generic | 32        | 0.63%   |
| 5.15.0-60-generic | 32        | 0.63%   |
| 5.13.0-22-generic | 32        | 0.63%   |
| 5.4.0-45-generic  | 30        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 944       | 19.93%  |
| 5.15.0  | 927       | 19.57%  |
| 5.19.0  | 448       | 9.46%   |
| 6.2.0   | 433       | 9.14%   |
| 5.8.0   | 409       | 8.64%   |
| 5.13.0  | 409       | 8.64%   |
| 5.11.0  | 327       | 6.9%    |
| 5.3.0   | 224       | 4.73%   |
| 6.5.0   | 130       | 2.74%   |
| 4.15.0  | 70        | 1.48%   |
| 5.0.0   | 36        | 0.76%   |
| 5.17.0  | 21        | 0.44%   |
| 5.10.0  | 18        | 0.38%   |
| 5.6.0   | 15        | 0.32%   |
| 6.1.0   | 10        | 0.21%   |
| 4.4.0   | 10        | 0.21%   |
| 6.0.0   | 9         | 0.19%   |
| 5.14.0  | 9         | 0.19%   |
| 4.18.0  | 8         | 0.17%   |
| 6.0.9   | 6         | 0.13%   |
| 6.3.0   | 5         | 0.11%   |
| 5.9.0   | 5         | 0.11%   |
| 6.4.0   | 4         | 0.08%   |
| 6.3.8   | 4         | 0.08%   |
| 5.7.0   | 4         | 0.08%   |
| 6.6.1   | 3         | 0.06%   |
| 6.6.0   | 3         | 0.06%   |
| 6.4.8   | 3         | 0.06%   |
| 6.4.10  | 3         | 0.06%   |
| 6.3.6   | 3         | 0.06%   |
| 6.3.1   | 3         | 0.06%   |
| 6.1.5   | 3         | 0.06%   |
| 5.8.18  | 3         | 0.06%   |
| 5.18.4  | 3         | 0.06%   |
| 5.18.10 | 3         | 0.06%   |
| 5.16.0  | 3         | 0.06%   |
| 5.12.8  | 3         | 0.06%   |
| 5.12.0  | 3         | 0.06%   |
| 4.13.0  | 3         | 0.06%   |
| 4.10.0  | 3         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 951       | 20.11%  |
| 5.15    | 942       | 19.92%  |
| 5.19    | 454       | 9.6%    |
| 6.2     | 443       | 9.37%   |
| 5.8     | 425       | 8.99%   |
| 5.13    | 419       | 8.86%   |
| 5.11    | 333       | 7.04%   |
| 5.3     | 227       | 4.8%    |
| 6.5     | 137       | 2.9%    |
| 4.15    | 71        | 1.5%    |
| 5.0     | 37        | 0.78%   |
| 5.10    | 30        | 0.63%   |
| 6.1     | 29        | 0.61%   |
| 5.17    | 28        | 0.59%   |
| 6.3     | 23        | 0.49%   |
| 6.0     | 21        | 0.44%   |
| 5.6     | 20        | 0.42%   |
| 5.14    | 18        | 0.38%   |
| 6.4     | 14        | 0.3%    |
| 5.9     | 13        | 0.27%   |
| 5.12    | 13        | 0.27%   |
| 5.18    | 12        | 0.25%   |
| 5.7     | 11        | 0.23%   |
| 6.6     | 10        | 0.21%   |
| 5.16    | 10        | 0.21%   |
| 4.4     | 10        | 0.21%   |
| 4.18    | 10        | 0.21%   |
| 5.5     | 5         | 0.11%   |
| 4.13    | 3         | 0.06%   |
| 4.10    | 3         | 0.06%   |
| 5.1     | 2         | 0.04%   |
| 6.7     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4391      | 99.5%   |
| i686    | 12        | 0.27%   |
| aarch64 | 6         | 0.14%   |
| riscv64 | 4         | 0.09%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 3493      | 77.92%  |
| KDE        | 924       | 20.61%  |
| GNOME      | 25        | 0.56%   |
| Cinnamon   | 11        | 0.25%   |
| Budgie     | 8         | 0.18%   |
| MATE       | 7         | 0.16%   |
| KDE4       | 4         | 0.09%   |
| XFCE       | 3         | 0.07%   |
| LXQt       | 3         | 0.07%   |
| X-Cinnamon | 1         | 0.02%   |
| Unity      | 1         | 0.02%   |
| i3         | 1         | 0.02%   |
| GNUstep    | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4197      | 94.34%  |
| Wayland | 200       | 4.5%    |
| Tty     | 51        | 1.15%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2690      | 59.83%  |
| Unknown | 1502      | 33.41%  |
| GDM     | 114       | 2.54%   |
| GDM3    | 90        | 2%      |
| LightDM | 75        | 1.67%   |
| TDM     | 21        | 0.47%   |
| SLiM    | 2         | 0.04%   |
| LXDM    | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1914      | 43%     |
| de_DE   | 376       | 8.45%   |
| en_GB   | 223       | 5.01%   |
| ru_RU   | 220       | 4.94%   |
| fr_FR   | 201       | 4.52%   |
| it_IT   | 195       | 4.38%   |
| pt_BR   | 176       | 3.95%   |
| es_ES   | 96        | 2.16%   |
| en_CA   | 89        | 2%      |
| en_AU   | 83        | 1.86%   |
| pl_PL   | 78        | 1.75%   |
| Unknown | 77        | 1.73%   |
| en_IN   | 75        | 1.69%   |
| C       | 50        | 1.12%   |
| hu_HU   | 33        | 0.74%   |
| es_MX   | 31        | 0.7%    |
| nl_NL   | 26        | 0.58%   |
| en_ZA   | 25        | 0.56%   |
| cs_CZ   | 25        | 0.56%   |
| ru_UA   | 24        | 0.54%   |
| es_AR   | 24        | 0.54%   |
| de_AT   | 22        | 0.49%   |
| en_NZ   | 20        | 0.45%   |
| sv_SE   | 16        | 0.36%   |
| de_CH   | 16        | 0.36%   |
| zh_CN   | 15        | 0.34%   |
| tr_TR   | 15        | 0.34%   |
| es_CO   | 14        | 0.31%   |
| pt_PT   | 13        | 0.29%   |
| es_CL   | 12        | 0.27%   |
| en_PH   | 12        | 0.27%   |
| en_IE   | 12        | 0.27%   |
| fr_BE   | 11        | 0.25%   |
| fi_FI   | 11        | 0.25%   |
| en_IL   | 11        | 0.25%   |
| el_GR   | 11        | 0.25%   |
| uk_UA   | 9         | 0.2%    |
| nl_BE   | 9         | 0.2%    |
| es_VE   | 9         | 0.2%    |
| zh_TW   | 8         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2446      | 54.51%  |
| BIOS | 2041      | 45.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3889      | 87.28%  |
| Tmpfs    | 185       | 4.15%   |
| Btrfs    | 178       | 3.99%   |
| Overlay  | 111       | 2.49%   |
| Xfs      | 44        | 0.99%   |
| Zfs      | 22        | 0.49%   |
| Unknown  | 12        | 0.27%   |
| Ext3     | 5         | 0.11%   |
| Ext2     | 4         | 0.09%   |
| F2fs     | 2         | 0.04%   |
| XXXX     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| ExX4     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2366      | 52.68%  |
| Unknown | 1740      | 38.74%  |
| MBR     | 385       | 8.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3868      | 86.67%  |
| Yes       | 595       | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2782      | 62.28%  |
| Yes       | 1685      | 37.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 740       | 16.77%  |
| Lenovo              | 683       | 15.48%  |
| Hewlett-Packard     | 595       | 13.48%  |
| Dell                | 582       | 13.19%  |
| Gigabyte Technology | 338       | 7.66%   |
| MSI                 | 292       | 6.62%   |
| Acer                | 206       | 4.67%   |
| ASRock              | 155       | 3.51%   |
| Apple               | 70        | 1.59%   |
| Intel               | 54        | 1.22%   |
| Samsung Electronics | 51        | 1.16%   |
| HUAWEI              | 49        | 1.11%   |
| Unknown             | 40        | 0.91%   |
| Toshiba             | 29        | 0.66%   |
| Google              | 29        | 0.66%   |
| Notebook            | 28        | 0.63%   |
| Fujitsu             | 27        | 0.61%   |
| Sony                | 23        | 0.52%   |
| TUXEDO              | 21        | 0.48%   |
| Alienware           | 19        | 0.43%   |
| AZW                 | 18        | 0.41%   |
| Medion              | 16        | 0.36%   |
| Pegatron            | 15        | 0.34%   |
| Timi                | 14        | 0.32%   |
| Positivo            | 13        | 0.29%   |
| Biostar             | 13        | 0.29%   |
| Packard Bell        | 10        | 0.23%   |
| Microsoft           | 10        | 0.23%   |
| Foxconn             | 10        | 0.23%   |
| Supermicro          | 9         | 0.2%    |
| PC Specialist       | 9         | 0.2%    |
| ECS                 | 9         | 0.2%    |
| ZOTAC               | 8         | 0.18%   |
| System76            | 8         | 0.18%   |
| GPU Company         | 8         | 0.18%   |
| Chuwi               | 8         | 0.18%   |
| LG Electronics      | 7         | 0.16%   |
| Gateway             | 7         | 0.16%   |
| Shuttle             | 6         | 0.14%   |
| Schenker            | 6         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 55        | 1.25%   |
| ASUS All Series                    | 53        | 1.2%    |
| ASUS ROG STRIX B550-F GAMING       | 14        | 0.32%   |
| HP Notebook                        | 11        | 0.25%   |
| Gigabyte B450M DS3H                | 11        | 0.25%   |
| MSI MS-7C37                        | 10        | 0.23%   |
| MSI MS-7B79                        | 10        | 0.23%   |
| HP Pavilion g6                     | 10        | 0.23%   |
| HP Pavilion dv6                    | 9         | 0.2%    |
| Dell XPS 15 9560                   | 9         | 0.2%    |
| Dell OptiPlex 9020                 | 9         | 0.2%    |
| Dell OptiPlex 7010                 | 9         | 0.2%    |
| ASUS ROG STRIX X570-E GAMING       | 9         | 0.2%    |
| MSI MS-7C91                        | 8         | 0.18%   |
| MSI MS-7817                        | 8         | 0.18%   |
| HUAWEI NBLK-WAX9X                  | 8         | 0.18%   |
| HP Pavilion 15                     | 8         | 0.18%   |
| Gigabyte X570 AORUS MASTER         | 8         | 0.18%   |
| Gigabyte A320M-S2H                 | 8         | 0.18%   |
| Dell XPS 15 9570                   | 8         | 0.18%   |
| AZW SER                            | 8         | 0.18%   |
| ASUS PRIME B450M-A                 | 8         | 0.18%   |
| ASUS PRIME B350-PLUS               | 8         | 0.18%   |
| ASUS PRIME A320M-K                 | 8         | 0.18%   |
| MSI MS-7C56                        | 7         | 0.16%   |
| HP Pavilion dv7                    | 7         | 0.16%   |
| HP ENVY x360 Convertible 13-ay0xxx | 7         | 0.16%   |
| HP EliteBook 840 G6                | 7         | 0.16%   |
| HP EliteBook 840 G5                | 7         | 0.16%   |
| Gigabyte 970A-DS3P                 | 7         | 0.16%   |
| ASUS TUF Gaming X570-PLUS          | 7         | 0.16%   |
| ASUS TUF Gaming B550-PLUS          | 7         | 0.16%   |
| MSI MS-7B86                        | 6         | 0.14%   |
| MSI MS-7A34                        | 6         | 0.14%   |
| MSI MS-7693                        | 6         | 0.14%   |
| HUAWEI HVY-WXX9                    | 6         | 0.14%   |
| HP Pavilion Notebook               | 6         | 0.14%   |
| HP EliteBook 840 G3                | 6         | 0.14%   |
| Dell XPS 15 7590                   | 6         | 0.14%   |
| Dell Latitude 5480                 | 6         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 305       | 6.91%   |
| Dell Latitude      | 161       | 3.65%   |
| Dell Inspiron      | 138       | 3.13%   |
| Acer Aspire        | 131       | 2.97%   |
| Lenovo IdeaPad     | 130       | 2.95%   |
| HP Pavilion        | 116       | 2.63%   |
| ASUS ROG           | 108       | 2.45%   |
| ASUS PRIME         | 107       | 2.42%   |
| Dell XPS           | 84        | 1.9%    |
| HP ProBook         | 75        | 1.7%    |
| HP EliteBook       | 73        | 1.65%   |
| Dell Precision     | 67        | 1.52%   |
| ASUS VivoBook      | 66        | 1.5%    |
| HP Laptop          | 62        | 1.4%    |
| Dell OptiPlex      | 56        | 1.27%   |
| Unknown            | 55        | 1.25%   |
| ASUS TUF           | 54        | 1.22%   |
| ASUS All           | 53        | 1.2%    |
| Lenovo ThinkCentre | 41        | 0.93%   |
| Lenovo Yoga        | 37        | 0.84%   |
| HP ENVY            | 37        | 0.84%   |
| Lenovo Legion      | 35        | 0.79%   |
| HP Compaq          | 35        | 0.79%   |
| Dell Vostro        | 34        | 0.77%   |
| Acer Nitro         | 29        | 0.66%   |
| ASUS ASUS          | 28        | 0.63%   |
| Toshiba Satellite  | 25        | 0.57%   |
| Lenovo ThinkBook   | 25        | 0.57%   |
| HP ZBook           | 21        | 0.48%   |
| Gigabyte X570      | 21        | 0.48%   |
| ASUS ZenBook       | 21        | 0.48%   |
| Acer Swift         | 20        | 0.45%   |
| Gigabyte B450M     | 19        | 0.43%   |
| Gigabyte B550      | 15        | 0.34%   |
| HP Spectre         | 14        | 0.32%   |
| HP EliteDesk       | 14        | 0.32%   |
| Fujitsu ESPRIMO    | 13        | 0.29%   |
| Gigabyte A320M-S2H | 12        | 0.27%   |
| Dell G3            | 12        | 0.27%   |
| HP Notebook        | 11        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 543       | 12.3%   |
| 2019    | 502       | 11.38%  |
| 2018    | 458       | 10.38%  |
| 2021    | 405       | 9.18%   |
| 2017    | 309       | 7%      |
| 2012    | 304       | 6.89%   |
| 2013    | 292       | 6.62%   |
| 2014    | 260       | 5.89%   |
| 2011    | 244       | 5.53%   |
| 2022    | 220       | 4.99%   |
| 2016    | 203       | 4.6%    |
| 2015    | 193       | 4.37%   |
| 2010    | 138       | 3.13%   |
| 2009    | 105       | 2.38%   |
| 2008    | 102       | 2.31%   |
| 2023    | 69        | 1.56%   |
| 2007    | 43        | 0.97%   |
| 2006    | 9         | 0.2%    |
| Unknown | 8         | 0.18%   |
| 2005    | 3         | 0.07%   |
| 2024    | 2         | 0.05%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2435      | 55.18%  |
| Desktop        | 1645      | 37.28%  |
| Convertible    | 153       | 3.47%   |
| Mini pc        | 71        | 1.61%   |
| All in one     | 49        | 1.11%   |
| Tablet         | 33        | 0.75%   |
| Server         | 20        | 0.45%   |
| System on chip | 6         | 0.14%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4055      | 91.27%  |
| Enabled  | 388       | 8.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4377      | 99.18%  |
| Yes  | 36        | 0.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1136      | 25.49%  |
| 4.01-8.0        | 974       | 21.86%  |
| 8.01-16.0       | 815       | 18.29%  |
| 32.01-64.0      | 651       | 14.61%  |
| 3.01-4.0        | 494       | 11.09%  |
| 64.01-256.0     | 165       | 3.7%    |
| 24.01-32.0      | 134       | 3.01%   |
| 1.01-2.0        | 55        | 1.23%   |
| 2.01-3.0        | 26        | 0.58%   |
| More than 256.0 | 6         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1225      | 25.58%  |
| 4.01-8.0    | 1176      | 24.56%  |
| 1.01-2.0    | 1017      | 21.24%  |
| 3.01-4.0    | 831       | 17.36%  |
| 8.01-16.0   | 352       | 7.35%   |
| 0.51-1.0    | 90        | 1.88%   |
| 16.01-24.0  | 60        | 1.25%   |
| 24.01-32.0  | 18        | 0.38%   |
| 32.01-64.0  | 10        | 0.21%   |
| 0.01-0.5    | 7         | 0.15%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2411      | 53.09%  |
| 2      | 1230      | 27.09%  |
| 3      | 420       | 9.25%   |
| 4      | 242       | 5.33%   |
| 5      | 114       | 2.51%   |
| 6      | 52        | 1.15%   |
| 7      | 32        | 0.7%    |
| 0      | 15        | 0.33%   |
| 8      | 10        | 0.22%   |
| 9      | 5         | 0.11%   |
| 12     | 3         | 0.07%   |
| 11     | 3         | 0.07%   |
| 10     | 3         | 0.07%   |
| 13     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3038      | 68.42%  |
| Yes       | 1402      | 31.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3707      | 83.83%  |
| No        | 715       | 16.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3451      | 77.83%  |
| No        | 983       | 22.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2990      | 67.19%  |
| No        | 1460      | 32.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 856       | 19.34%  |
| Germany      | 505       | 11.41%  |
| Russia       | 293       | 6.62%   |
| Italy        | 250       | 5.65%   |
| France       | 249       | 5.63%   |
| Brazil       | 231       | 5.22%   |
| UK           | 207       | 4.68%   |
| Spain        | 134       | 3.03%   |
| Canada       | 114       | 2.58%   |
| Poland       | 112       | 2.53%   |
| Netherlands  | 103       | 2.33%   |
| Australia    | 82        | 1.85%   |
| India        | 81        | 1.83%   |
| Ukraine      | 64        | 1.45%   |
| Switzerland  | 55        | 1.24%   |
| Mexico       | 55        | 1.24%   |
| Hungary      | 55        | 1.24%   |
| Czechia      | 49        | 1.11%   |
| Belgium      | 43        | 0.97%   |
| Argentina    | 40        | 0.9%    |
| Turkey       | 37        | 0.84%   |
| Austria      | 37        | 0.84%   |
| Sweden       | 34        | 0.77%   |
| Indonesia    | 31        | 0.7%    |
| Finland      | 30        | 0.68%   |
| South Africa | 28        | 0.63%   |
| Bulgaria     | 27        | 0.61%   |
| Romania      | 26        | 0.59%   |
| Greece       | 26        | 0.59%   |
| Portugal     | 25        | 0.56%   |
| Slovenia     | 23        | 0.52%   |
| Denmark      | 23        | 0.52%   |
| China        | 23        | 0.52%   |
| Serbia       | 21        | 0.47%   |
| Norway       | 20        | 0.45%   |
| Colombia     | 20        | 0.45%   |
| New Zealand  | 19        | 0.43%   |
| Slovakia     | 18        | 0.41%   |
| Chile        | 18        | 0.41%   |
| Israel       | 16        | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 79        | 1.7%    |
| Berlin            | 50        | 1.08%   |
| Paris             | 40        | 0.86%   |
| Milan             | 36        | 0.78%   |
| St Petersburg     | 34        | 0.73%   |
| Hamburg           | 34        | 0.73%   |
| Warsaw            | 31        | 0.67%   |
| Rome              | 30        | 0.65%   |
| Budapest          | 27        | 0.58%   |
| Sao Paulo         | 26        | 0.56%   |
| Madrid            | 25        | 0.54%   |
| Cologne           | 23        | 0.5%    |
| Sydney            | 22        | 0.47%   |
| Munich            | 22        | 0.47%   |
| Amsterdam         | 22        | 0.47%   |
| Vienna            | 21        | 0.45%   |
| Frankfurt am Main | 21        | 0.45%   |
| London            | 20        | 0.43%   |
| Rio de Janeiro    | 19        | 0.41%   |
| Kyiv              | 19        | 0.41%   |
| Zurich            | 18        | 0.39%   |
| Melbourne         | 18        | 0.39%   |
| Prague            | 17        | 0.37%   |
| Montreal          | 15        | 0.32%   |
| Dallas            | 15        | 0.32%   |
| Sofia             | 14        | 0.3%    |
| Belgrade          | 14        | 0.3%    |
| Seattle           | 13        | 0.28%   |
| Minsk             | 13        | 0.28%   |
| Krakow            | 13        | 0.28%   |
| Jakarta           | 13        | 0.28%   |
| Istanbul          | 13        | 0.28%   |
| Novosibirsk       | 12        | 0.26%   |
| Helsinki          | 12        | 0.26%   |
| Athens            | 12        | 0.26%   |
| San Francisco     | 11        | 0.24%   |
| Phoenix           | 11        | 0.24%   |
| Miami             | 11        | 0.24%   |
| Los Angeles       | 11        | 0.24%   |
| Leipzig           | 11        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1243      | 1960   | 17.7%   |
| WDC                         | 988       | 1557   | 14.07%  |
| Seagate                     | 877       | 1380   | 12.49%  |
| SanDisk                     | 406       | 518    | 5.78%   |
| Kingston                    | 406       | 492    | 5.78%   |
| Toshiba                     | 394       | 550    | 5.61%   |
| Crucial                     | 295       | 364    | 4.2%    |
| Unknown                     | 227       | 283    | 3.23%   |
| Intel                       | 210       | 278    | 2.99%   |
| SK hynix                    | 194       | 230    | 2.76%   |
| Hitachi                     | 170       | 210    | 2.42%   |
| Micron Technology           | 129       | 148    | 1.84%   |
| HGST                        | 124       | 165    | 1.77%   |
| A-DATA Technology           | 105       | 122    | 1.5%    |
| KIOXIA                      | 67        | 76     | 0.95%   |
| China                       | 58        | 76     | 0.83%   |
| Phison                      | 55        | 70     | 0.78%   |
| Silicon Motion              | 47        | 55     | 0.67%   |
| SPCC                        | 44        | 59     | 0.63%   |
| PNY                         | 41        | 59     | 0.58%   |
| Apple                       | 41        | 47     | 0.58%   |
| Phison Electronics          | 37        | 37     | 0.53%   |
| Patriot                     | 35        | 47     | 0.5%    |
| Intenso                     | 35        | 43     | 0.5%    |
| Transcend                   | 32        | 34     | 0.46%   |
| Micron/Crucial Technology   | 31        | 41     | 0.44%   |
| Corsair                     | 31        | 47     | 0.44%   |
| OCZ                         | 28        | 35     | 0.4%    |
| LITEON                      | 28        | 30     | 0.4%    |
| Maxtor                      | 27        | 31     | 0.38%   |
| Unknown                     | 27        | 30     | 0.38%   |
| Kingston Technology Company | 24        | 30     | 0.34%   |
| JMicron Technology          | 24        | 26     | 0.34%   |
| GOODRAM                     | 20        | 35     | 0.28%   |
| Team                        | 19        | 20     | 0.27%   |
| SABRENT                     | 18        | 22     | 0.26%   |
| XPG                         | 17        | 18     | 0.24%   |
| LITEONIT                    | 15        | 17     | 0.21%   |
| KingSpec                    | 14        | 16     | 0.2%    |
| Gigabyte Technology         | 14        | 15     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 69        | 0.88%   |
| Kingston SA400S37240G 240GB SSD                     | 66        | 0.84%   |
| Samsung SSD 850 EVO 250GB                           | 56        | 0.71%   |
| Samsung SSD 850 EVO 500GB                           | 55        | 0.7%    |
| Kingston SA400S37480G 480GB SSD                     | 50        | 0.63%   |
| Samsung SSD 860 EVO 1TB                             | 48        | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 47        | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB                      | 44        | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 40        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                         | 40        | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB                      | 37        | 0.47%   |
| Unknown MMC Card  64GB                              | 36        | 0.46%   |
| Unknown MMC Card  32GB                              | 36        | 0.46%   |
| Toshiba MQ01ABD100 1TB                              | 34        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                        | 34        | 0.43%   |
| Toshiba MQ04ABF100 1TB                              | 33        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB                      | 33        | 0.42%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 31        | 0.39%   |
| HGST HTS721010A9E630 1TB                            | 31        | 0.39%   |
| Samsung NVMe SSD Drive 1TB                          | 30        | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 29        | 0.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 29        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 28        | 0.36%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                      | 27        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                      | 27        | 0.34%   |
| Unknown                                             | 27        | 0.34%   |
| Toshiba HDWD110 1TB                                 | 26        | 0.33%   |
| Seagate ST1000DM010-2EP102 1TB                      | 26        | 0.33%   |
| Seagate ST500DM002-1BD142 500GB                     | 25        | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB                      | 25        | 0.32%   |
| SanDisk NVMe SSD Drive 1TB                          | 25        | 0.32%   |
| Crucial CT500MX500SSD1 500GB                        | 25        | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB                      | 24        | 0.3%    |
| SanDisk SSD PLUS 240GB                              | 24        | 0.3%    |
| Seagate ST500LT012-1DG142 500GB                     | 23        | 0.29%   |
| Seagate Expansion 1TB                               | 23        | 0.29%   |
| Samsung SSD 980 1TB                                 | 23        | 0.29%   |
| Crucial CT240BX500SSD1 240GB                        | 23        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 851       | 1334   | 35.68%  |
| WDC                 | 732       | 1191   | 30.69%  |
| Toshiba             | 278       | 393    | 11.66%  |
| Hitachi             | 170       | 210    | 7.13%   |
| HGST                | 123       | 164    | 5.16%   |
| Samsung Electronics | 115       | 180    | 4.82%   |
| Maxtor              | 26        | 30     | 1.09%   |
| Unknown             | 25        | 30     | 1.05%   |
| Apple               | 16        | 16     | 0.67%   |
| Fujitsu             | 12        | 15     | 0.5%    |
| External            | 7         | 13     | 0.29%   |
| TO Exter            | 3         | 3      | 0.13%   |
| Hewlett-Packard     | 3         | 5      | 0.13%   |
| USB3.0              | 2         | 2      | 0.08%   |
| StoreJet            | 2         | 2      | 0.08%   |
| SAGE                | 2         | 2      | 0.08%   |
| LaCie               | 2         | 3      | 0.08%   |
| KESU                | 2         | 2      | 0.08%   |
| JMicron Technology  | 2         | 2      | 0.08%   |
| ASMT                | 2         | 2      | 0.08%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| USB                 | 1         | 1      | 0.04%   |
| SSI                 | 1         | 1      | 0.04%   |
| SABRENT             | 1         | 2      | 0.04%   |
| Magnetic Data       | 1         | 2      | 0.04%   |
| LIO-ORG             | 1         | 1      | 0.04%   |
| ipTIME              | 1         | 1      | 0.04%   |
| IET                 | 1         | 1      | 0.04%   |
| HPE                 | 1         | 6      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 613       | 894    | 25.79%  |
| Kingston            | 294       | 353    | 12.37%  |
| Crucial             | 242       | 304    | 10.18%  |
| SanDisk             | 230       | 290    | 9.68%   |
| WDC                 | 132       | 178    | 5.55%   |
| A-DATA Technology   | 75        | 88     | 3.16%   |
| Intel               | 61        | 81     | 2.57%   |
| China               | 57        | 75     | 2.4%    |
| Micron Technology   | 42        | 47     | 1.77%   |
| Toshiba             | 37        | 53     | 1.56%   |
| SPCC                | 37        | 50     | 1.56%   |
| PNY                 | 37        | 55     | 1.56%   |
| Patriot             | 33        | 45     | 1.39%   |
| SK hynix            | 29        | 31     | 1.22%   |
| Intenso             | 29        | 34     | 1.22%   |
| OCZ                 | 28        | 35     | 1.18%   |
| Transcend           | 26        | 26     | 1.09%   |
| LITEON              | 23        | 24     | 0.97%   |
| GOODRAM             | 20        | 35     | 0.84%   |
| Team                | 17        | 17     | 0.72%   |
| Corsair             | 16        | 29     | 0.67%   |
| LITEONIT            | 15        | 17     | 0.63%   |
| Apple               | 15        | 15     | 0.63%   |
| KingSpec            | 14        | 16     | 0.59%   |
| JMicron Technology  | 13        | 14     | 0.55%   |
| Apacer              | 11        | 16     | 0.46%   |
| Mushkin             | 10        | 11     | 0.42%   |
| Lexar               | 9         | 10     | 0.38%   |
| Verbatim            | 8         | 10     | 0.34%   |
| Emtec               | 8         | 9      | 0.34%   |
| Unknown             | 8         | 8      | 0.34%   |
| Seagate             | 7         | 12     | 0.29%   |
| Plextor             | 7         | 8      | 0.29%   |
| Netac               | 7         | 8      | 0.29%   |
| Hewlett-Packard     | 7         | 7      | 0.29%   |
| ASMT                | 7         | 8      | 0.29%   |
| Gigabyte Technology | 6         | 6      | 0.25%   |
| Dogfish             | 6         | 6      | 0.25%   |
| Unknown             | 4         | 4      | 0.17%   |
| KingDian            | 4         | 5      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2026      | 3099   | 32.72%  |
| NVMe    | 1940      | 2689   | 31.33%  |
| HDD     | 1919      | 3616   | 30.99%  |
| MMC     | 200       | 248    | 3.23%   |
| Unknown | 107       | 149    | 1.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3030      | 6468   | 55.71%  |
| NVMe | 1925      | 2654   | 35.39%  |
| SAS  | 284       | 431    | 5.22%   |
| MMC  | 200       | 248    | 3.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2116      | 3363   | 49.75%  |
| 0.51-1.0   | 1327      | 2017   | 31.2%   |
| 1.01-2.0   | 456       | 725    | 10.72%  |
| 3.01-4.0   | 152       | 291    | 3.57%   |
| 4.01-10.0  | 94        | 159    | 2.21%   |
| 2.01-3.0   | 93        | 133    | 2.19%   |
| 10.01-20.0 | 15        | 27     | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1091      | 23.8%   |
| 251-500        | 1082      | 23.6%   |
| 501-1000       | 858       | 18.72%  |
| 1001-2000      | 510       | 11.13%  |
| More than 3000 | 361       | 7.88%   |
| 51-100         | 221       | 4.82%   |
| 2001-3000      | 216       | 4.71%   |
| 1-20           | 128       | 2.79%   |
| 21-50          | 99        | 2.16%   |
| Unknown        | 18        | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1037      | 21.94%  |
| 101-250        | 826       | 17.47%  |
| 21-50          | 734       | 15.53%  |
| 51-100         | 624       | 13.2%   |
| 251-500        | 553       | 11.7%   |
| 501-1000       | 438       | 9.27%   |
| 1001-2000      | 249       | 5.27%   |
| More than 3000 | 169       | 3.58%   |
| 2001-3000      | 79        | 1.67%   |
| Unknown        | 18        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 6         | 6      | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 12     | 1.28%   |
| HGST HTS721010A9E630 1TB              | 6         | 7      | 1.28%   |
| Seagate ST31000524AS 1TB              | 5         | 6      | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB        | 5         | 5      | 1.07%   |
| WDC WD5000AAKS-00V1A0 500GB           | 4         | 5      | 0.86%   |
| Toshiba MQ04ABF100 1TB                | 4         | 4      | 0.86%   |
| Toshiba MQ01ABD100 1TB                | 4         | 6      | 0.86%   |
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 0.86%   |
| Seagate ST3500418AS 500GB             | 4         | 4      | 0.86%   |
| Seagate ST1000DM003-1CH162 1TB        | 4         | 10     | 0.86%   |
| HGST HTS545050A7E680 500GB            | 4         | 4      | 0.86%   |
| Crucial CT1050MX300SSD1 1050GB        | 4         | 4      | 0.86%   |
| WDC WD30EZRX-00MMMB0 3TB              | 3         | 3      | 0.64%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3         | 6      | 0.64%   |
| Seagate ST9500325AS 500GB             | 3         | 7      | 0.64%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.64%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.64%   |
| Seagate ST31000528AS 1TB              | 3         | 3      | 0.64%   |
| Seagate ST1000LM048-2E7172 1TB        | 3         | 3      | 0.64%   |
| SanDisk SSD PLUS 240GB                | 3         | 3      | 0.64%   |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 3      | 0.64%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.64%   |
| Hitachi HTS547564A9E384 640GB         | 3         | 3      | 0.64%   |
| HGST HTS541010A9E680 1TB              | 3         | 7      | 0.64%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 0.64%   |
| WDC WD5000AAKS-00A7B0 500GB           | 2         | 2      | 0.43%   |
| WDC WD40EZRZ-00GXCB0 4TB              | 2         | 2      | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB              | 2         | 4      | 0.43%   |
| WDC WD3200JD-22KLB0 320GB             | 2         | 2      | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 2      | 0.43%   |
| WDC WD20EARX-00PASB0 2TB              | 2         | 2      | 0.43%   |
| WDC WD15EARS-00Z5B1 1TB               | 2         | 2      | 0.43%   |
| WDC WD10EZEX-22MFCA0 1TB              | 2         | 3      | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 2      | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2         | 2      | 0.43%   |
| WDC WD10EARS-00MVWB0 1TB              | 2         | 4      | 0.43%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 2      | 0.43%   |
| WDC WD1001FALS-40U9B0 1TB             | 2         | 2      | 0.43%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD  | 2         | 2      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 100       | 124    | 22.08%  |
| Seagate             | 97        | 127    | 21.41%  |
| Samsung Electronics | 47        | 65     | 10.38%  |
| Toshiba             | 37        | 43     | 8.17%   |
| Hitachi             | 29        | 29     | 6.4%    |
| Crucial             | 19        | 23     | 4.19%   |
| SanDisk             | 17        | 18     | 3.75%   |
| HGST                | 16        | 21     | 3.53%   |
| Intel               | 15        | 20     | 3.31%   |
| SK hynix            | 11        | 11     | 2.43%   |
| Kingston            | 11        | 11     | 2.43%   |
| A-DATA Technology   | 7         | 7      | 1.55%   |
| Maxtor              | 6         | 7      | 1.32%   |
| Micron Technology   | 5         | 5      | 1.1%    |
| OCZ                 | 4         | 4      | 0.88%   |
| Apple               | 4         | 4      | 0.88%   |
| Neo                 | 2         | 2      | 0.44%   |
| LITEONIT            | 2         | 2      | 0.44%   |
| Intenso             | 2         | 2      | 0.44%   |
| Fujitsu             | 2         | 2      | 0.44%   |
| Zheino              | 1         | 2      | 0.22%   |
| XPG                 | 1         | 1      | 0.22%   |
| VISIPRO             | 1         | 2      | 0.22%   |
| VENO                | 1         | 1      | 0.22%   |
| tecmiyo             | 1         | 3      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| T-FORCE             | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 1      | 0.22%   |
| SPCC                | 1         | 1      | 0.22%   |
| SABRENT             | 1         | 1      | 0.22%   |
| R580                | 1         | 1      | 0.22%   |
| Phison Electronics  | 1         | 1      | 0.22%   |
| ORTIAL              | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| LITEON              | 1         | 1      | 0.22%   |
| Drevo               | 1         | 1      | 0.22%   |
| Corsair             | 1         | 1      | 0.22%   |
| BAITITON            | 1         | 3      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |
| ASENNO              | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 97        | 121    | 32.01%  |
| Seagate             | 97        | 127    | 32.01%  |
| Toshiba             | 32        | 38     | 10.56%  |
| Hitachi             | 29        | 29     | 9.57%   |
| Samsung Electronics | 19        | 35     | 6.27%   |
| HGST                | 16        | 21     | 5.28%   |
| Maxtor              | 6         | 7      | 1.98%   |
| Apple               | 4         | 4      | 1.32%   |
| Fujitsu             | 2         | 2      | 0.66%   |
| ASMT                | 1         | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 275       | 385    | 65.32%  |
| SSD  | 118       | 139    | 28.03%  |
| NVMe | 28        | 29     | 6.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 14.29%  |
| OCZ VERTEX460A 480GB SSD              | 1         | 1      | 14.29%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 14.29%  |
| Acer SSD FA100 256GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 28.57%  |
| Seagate             | 1         | 1      | 14.29%  |
| OCZ                 | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| Acer                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2290      | 5158   | 46.14%  |
| Works    | 2259      | 4082   | 45.52%  |
| Malfunc  | 408       | 553    | 8.22%   |
| Failed   | 6         | 8      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2748      | 45.82%  |
| AMD                              | 995       | 16.59%  |
| Samsung Electronics              | 629       | 10.49%  |
| SanDisk                          | 333       | 5.55%   |
| SK hynix                         | 164       | 2.73%   |
| Kingston Technology Company      | 137       | 2.28%   |
| Phison Electronics               | 114       | 1.9%    |
| ASMedia Technology               | 104       | 1.73%   |
| Toshiba America Info Systems     | 91        | 1.52%   |
| Micron Technology                | 87        | 1.45%   |
| Micron/Crucial Technology        | 82        | 1.37%   |
| Silicon Motion                   | 65        | 1.08%   |
| KIOXIA                           | 63        | 1.05%   |
| JMicron Technology               | 57        | 0.95%   |
| Marvell Technology Group         | 51        | 0.85%   |
| ADATA Technology                 | 47        | 0.78%   |
| Nvidia                           | 44        | 0.73%   |
| Realtek Semiconductor            | 29        | 0.48%   |
| Solid State Storage Technology   | 18        | 0.3%    |
| Union Memory (Shenzhen)          | 17        | 0.28%   |
| Broadcom / LSI                   | 16        | 0.27%   |
| LSI Logic / Symbios Logic        | 14        | 0.23%   |
| Silicon Image                    | 10        | 0.17%   |
| Lite-On Technology               | 10        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 9         | 0.15%   |
| VIA Technologies                 | 8         | 0.13%   |
| Seagate Technology               | 8         | 0.13%   |
| Apple                            | 8         | 0.13%   |
| Shenzhen Longsys Electronics     | 5         | 0.08%   |
| Lenovo                           | 5         | 0.08%   |
| INNOGRIT                         | 4         | 0.07%   |
| Yangtze Memory Technologies      | 3         | 0.05%   |
| Solidigm                         | 3         | 0.05%   |
| Netac Technology                 | 3         | 0.05%   |
| Zhaoxin                          | 2         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Biwin Storage Technology         | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 708       | 10.42%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 331       | 4.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 224       | 3.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 213       | 3.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 173       | 2.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 171       | 2.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 153       | 2.25%   |
| AMD 400 Series Chipset SATA Controller                                         | 137       | 2.02%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 114       | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 106       | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 104       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 104       | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 103       | 1.52%   |
| AMD 500 Series Chipset SATA Controller                                         | 98        | 1.44%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 96        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 94        | 1.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 93        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 87        | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 85        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 83        | 1.22%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 79        | 1.16%   |
| Intel SSD 660P Series                                                          | 74        | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 71        | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 69        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 67        | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                          | 66        | 0.97%   |
| Intel SATA Controller [RAID mode]                                              | 64        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 62        | 0.91%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 58        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 58        | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 57        | 0.84%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 55        | 0.81%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 50        | 0.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 50        | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 48        | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 47        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 47        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 47        | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 44        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 44        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3217      | 53.8%   |
| NVMe | 1919      | 32.1%   |
| RAID | 449       | 7.51%   |
| IDE  | 369       | 6.17%   |
| SAS  | 17        | 0.28%   |
| SCSI | 8         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 3147      | 71.31%  |
| AMD           | 1254      | 28.42%  |
| sifive,u74-mc | 4         | 0.09%   |
| ARM           | 4         | 0.09%   |
| CentaurHauls  | 2         | 0.05%   |
| QUALCOMM      | 1         | 0.02%   |
| Phytium       | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 70        | 1.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 57        | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 52        | 1.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 50        | 1.13%   |
| AMD Ryzen 5 3600 6-Core Processor             | 44        | 1%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 44        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 42        | 0.95%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 42        | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 40        | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 39        | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 39        | 0.88%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 39        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 38        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 34        | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 34        | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 32        | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 31        | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 30        | 0.68%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 30        | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.68%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 28        | 0.63%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 27        | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 26        | 0.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 25        | 0.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 24        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 23        | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 22        | 0.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 21        | 0.48%   |
| Intel 12th Gen Core i7-12700H                 | 21        | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 21        | 0.48%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 20        | 0.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 20        | 0.45%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 19        | 0.43%   |
| Intel 12th Gen Core i7-1260P                  | 19        | 0.43%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 19        | 0.43%   |
| AMD FX-8350 Eight-Core Processor              | 19        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 983       | 22.23%  |
| Intel Core i5           | 931       | 21.06%  |
| Other                   | 420       | 9.5%    |
| AMD Ryzen 5             | 357       | 8.08%   |
| AMD Ryzen 7             | 312       | 7.06%   |
| Intel Core i3           | 227       | 5.13%   |
| Intel Celeron           | 161       | 3.64%   |
| AMD Ryzen 9             | 108       | 2.44%   |
| Intel Core 2 Duo        | 97        | 2.19%   |
| Intel Xeon              | 91        | 2.06%   |
| Intel Pentium           | 74        | 1.67%   |
| AMD FX                  | 73        | 1.65%   |
| AMD Ryzen 3             | 53        | 1.2%    |
| Intel Core i9           | 42        | 0.95%   |
| AMD A6                  | 35        | 0.79%   |
| AMD Ryzen 7 PRO         | 34        | 0.77%   |
| AMD A10                 | 34        | 0.77%   |
| AMD A8                  | 32        | 0.72%   |
| Intel Pentium Dual-Core | 29        | 0.66%   |
| Intel Atom              | 29        | 0.66%   |
| AMD Phenom II X4        | 26        | 0.59%   |
| Intel Core 2 Quad       | 24        | 0.54%   |
| AMD Ryzen 5 PRO         | 18        | 0.41%   |
| Intel Pentium Silver    | 17        | 0.38%   |
| AMD Athlon              | 15        | 0.34%   |
| AMD A4                  | 15        | 0.34%   |
| AMD Athlon II X4        | 14        | 0.32%   |
| AMD Ryzen Threadripper  | 13        | 0.29%   |
| AMD E                   | 9         | 0.2%    |
| AMD Athlon II X2        | 9         | 0.2%    |
| AMD Athlon 64 X2        | 9         | 0.2%    |
| Intel Pentium Dual      | 8         | 0.18%   |
| Intel Genuine           | 8         | 0.18%   |
| Intel Core m3           | 8         | 0.18%   |
| AMD E1                  | 8         | 0.18%   |
| AMD Phenom II X6        | 7         | 0.16%   |
| AMD E2                  | 7         | 0.16%   |
| Intel Core 2            | 5         | 0.11%   |
| Intel Celeron Dual-Core | 5         | 0.11%   |
| AMD Sempron             | 5         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1729      | 39.12%  |
| 2       | 1319      | 29.84%  |
| 6       | 584       | 13.21%  |
| 8       | 451       | 10.2%   |
| 12      | 109       | 2.47%   |
| 16      | 56        | 1.27%   |
| 10      | 42        | 0.95%   |
| 14      | 40        | 0.9%    |
| 1       | 40        | 0.9%    |
| 24      | 17        | 0.38%   |
| 3       | 12        | 0.27%   |
| Unknown | 6         | 0.14%   |
| 32      | 5         | 0.11%   |
| 20      | 3         | 0.07%   |
| 64      | 2         | 0.05%   |
| 18      | 2         | 0.05%   |
| 44      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4373      | 99.09%  |
| 2       | 31        | 0.7%    |
| Unknown | 6         | 0.14%   |
| 4       | 2         | 0.05%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3332      | 75.32%  |
| 1       | 1086      | 24.55%  |
| Unknown | 6         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4405      | 99.82%  |
| Unknown        | 5         | 0.11%   |
| 32-bit         | 2         | 0.05%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1539      | 33.79%  |
| 0x306a9    | 183       | 4.02%   |
| 0x306c3    | 171       | 3.75%   |
| 0x206a7    | 158       | 3.47%   |
| 0x906ea    | 130       | 2.85%   |
| 0x806ec    | 113       | 2.48%   |
| 0x806c1    | 109       | 2.39%   |
| 0x806ea    | 103       | 2.26%   |
| 0x40651    | 82        | 1.8%    |
| 0x08701021 | 82        | 1.8%    |
| 0x1067a    | 80        | 1.76%   |
| 0x906e9    | 79        | 1.73%   |
| 0x806e9    | 76        | 1.67%   |
| 0x506e3    | 75        | 1.65%   |
| 0x0a50000c | 64        | 1.41%   |
| 0x406e3    | 63        | 1.38%   |
| 0x08108109 | 58        | 1.27%   |
| 0x08600106 | 48        | 1.05%   |
| 0x0800820d | 48        | 1.05%   |
| 0x306d4    | 46        | 1.01%   |
| 0x906a3    | 43        | 0.94%   |
| 0x08108102 | 40        | 0.88%   |
| 0x06000852 | 40        | 0.88%   |
| 0x706e5    | 39        | 0.86%   |
| 0x08701013 | 39        | 0.86%   |
| 0xa0652    | 37        | 0.81%   |
| 0x906ed    | 33        | 0.72%   |
| 0x08608103 | 33        | 0.72%   |
| 0x806eb    | 32        | 0.7%    |
| 0x20655    | 29        | 0.64%   |
| 0x010000c8 | 29        | 0.64%   |
| 0x706a1    | 28        | 0.61%   |
| 0x706a8    | 24        | 0.53%   |
| 0x08600104 | 24        | 0.53%   |
| 0x406c4    | 23        | 0.51%   |
| 0x06001119 | 21        | 0.46%   |
| 0x806d1    | 20        | 0.44%   |
| 0x30678    | 20        | 0.44%   |
| 0x0a50000d | 20        | 0.44%   |
| 0xa0653    | 19        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 808       | 18.25%  |
| Haswell          | 412       | 9.31%   |
| IvyBridge        | 296       | 6.69%   |
| Zen 2            | 287       | 6.48%   |
| SandyBridge      | 244       | 5.51%   |
| Unknown          | 224       | 5.06%   |
| Skylake          | 219       | 4.95%   |
| Zen+             | 214       | 4.83%   |
| Zen 3            | 192       | 4.34%   |
| TigerLake        | 187       | 4.22%   |
| Penryn           | 138       | 3.12%   |
| CometLake        | 113       | 2.55%   |
| Alderlake Hybrid | 105       | 2.37%   |
| IceLake          | 99        | 2.24%   |
| Zen              | 98        | 2.21%   |
| Piledriver       | 93        | 2.1%    |
| Goldmont plus    | 81        | 1.83%   |
| Broadwell        | 79        | 1.78%   |
| K10              | 76        | 1.72%   |
| Westmere         | 75        | 1.69%   |
| Silvermont       | 65        | 1.47%   |
| Core             | 55        | 1.24%   |
| Excavator        | 50        | 1.13%   |
| Nehalem          | 48        | 1.08%   |
| Goldmont         | 30        | 0.68%   |
| Puma             | 23        | 0.52%   |
| Steamroller      | 20        | 0.45%   |
| K10 Llano        | 19        | 0.43%   |
| K8 Hammer        | 16        | 0.36%   |
| Bobcat           | 16        | 0.36%   |
| Jaguar           | 15        | 0.34%   |
| Bulldozer        | 9         | 0.2%    |
| NetBurst         | 7         | 0.16%   |
| Bonnell          | 6         | 0.14%   |
| Tremont          | 5         | 0.11%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2445      | 45.74%  |
| Nvidia                           | 1594      | 29.82%  |
| AMD                              | 1283      | 24%     |
| Matrox Electronics Systems       | 9         | 0.17%   |
| ASPEED Technology                | 9         | 0.17%   |
| Zhaoxin                          | 2         | 0.04%   |
| ATI Technologies                 | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 171       | 3.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 170       | 3.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 165       | 3.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 140       | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 140       | 2.56%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 126       | 2.3%    |
| Intel UHD Graphics 620                                                                   | 120       | 2.19%   |
| Intel HD Graphics 620                                                                    | 103       | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 99        | 1.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 99        | 1.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 95        | 1.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 95        | 1.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 91        | 1.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 90        | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 85        | 1.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 82        | 1.5%    |
| Intel HD Graphics 530                                                                    | 70        | 1.28%   |
| Intel HD Graphics 630                                                                    | 67        | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 66        | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 64        | 1.17%   |
| Intel HD Graphics 5500                                                                   | 60        | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 60        | 1.1%    |
| AMD Lucienne                                                                             | 58        | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 57        | 1.04%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 56        | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 51        | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 44        | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 41        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 39        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 36        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 36        | 0.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 34        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 34        | 0.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 0.6%    |
| AMD Rembrandt [Radeon 680M]                                                              | 33        | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 31        | 0.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.57%   |
| Intel Iris Plus Graphics G7                                                              | 30        | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 29        | 0.53%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 29        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1619      | 36.53%  |
| 1 x AMD                  | 1000      | 22.56%  |
| 1 x Nvidia               | 814       | 18.37%  |
| Intel + Nvidia           | 655       | 14.78%  |
| Intel + AMD              | 115       | 2.59%   |
| AMD + Nvidia             | 97        | 2.19%   |
| 2 x AMD                  | 72        | 1.62%   |
| 2 x Nvidia               | 18        | 0.41%   |
| Other                    | 13        | 0.29%   |
| 1 x ASPEED               | 5         | 0.11%   |
| Nvidia + ASPEED          | 4         | 0.09%   |
| 1 x Matrox               | 4         | 0.09%   |
| 3 x Nvidia               | 3         | 0.07%   |
| Nvidia + Matrox          | 3         | 0.07%   |
| 2 x Intel                | 2         | 0.05%   |
| 1 x Zhaoxin              | 2         | 0.05%   |
| AMD + Matrox             | 2         | 0.05%   |
| 3 x AMD                  | 1         | 0.02%   |
| 1 x SiS                  | 1         | 0.02%   |
| Intel + 2 x AMD          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3220      | 72.1%   |
| Proprietary | 1152      | 25.79%  |
| Unknown     | 94        | 2.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2533      | 55.97%  |
| 1.01-2.0   | 490       | 10.83%  |
| 0.01-0.5   | 391       | 8.64%   |
| 3.01-4.0   | 337       | 7.45%   |
| 0.51-1.0   | 296       | 6.54%   |
| 7.01-8.0   | 229       | 5.06%   |
| 5.01-6.0   | 128       | 2.83%   |
| 8.01-16.0  | 65        | 1.44%   |
| 2.01-3.0   | 39        | 0.86%   |
| 16.01-24.0 | 13        | 0.29%   |
| 4.01-5.0   | 4         | 0.09%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 660       | 12.7%   |
| AU Optronics            | 548       | 10.55%  |
| BOE                     | 482       | 9.28%   |
| LG Display              | 435       | 8.37%   |
| Chimei Innolux          | 423       | 8.14%   |
| Dell                    | 344       | 6.62%   |
| Goldstar                | 285       | 5.48%   |
| Hewlett-Packard         | 185       | 3.56%   |
| Acer                    | 177       | 3.41%   |
| Philips                 | 129       | 2.48%   |
| BenQ                    | 129       | 2.48%   |
| Ancor Communications    | 124       | 2.39%   |
| AOC                     | 122       | 2.35%   |
| Sharp                   | 116       | 2.23%   |
| Lenovo                  | 73        | 1.4%    |
| Iiyama                  | 71        | 1.37%   |
| ASUSTek Computer        | 71        | 1.37%   |
| ViewSonic               | 60        | 1.15%   |
| Apple                   | 58        | 1.12%   |
| PANDA                   | 53        | 1.02%   |
| Chi Mei Optoelectronics | 49        | 0.94%   |
| InfoVision              | 40        | 0.77%   |
| LG Electronics          | 31        | 0.6%    |
| Sony                    | 26        | 0.5%    |
| Unknown                 | 24        | 0.46%   |
| NEC Computers           | 22        | 0.42%   |
| CSO                     | 21        | 0.4%    |
| Panasonic               | 20        | 0.38%   |
| Eizo                    | 20        | 0.38%   |
| MSI                     | 17        | 0.33%   |
| Sceptre Tech            | 15        | 0.29%   |
| HannStar                | 15        | 0.29%   |
| Gigabyte Technology     | 13        | 0.25%   |
| Medion                  | 12        | 0.23%   |
| Vizio                   | 11        | 0.21%   |
| Toshiba                 | 10        | 0.19%   |
| Vestel Elektronik       | 8         | 0.15%   |
| Idek Iiyama             | 8         | 0.15%   |
| RTK                     | 7         | 0.13%   |
| LG Philips              | 7         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 25        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 24        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 23        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 22        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 21        | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 20        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 18        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 18        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 18        | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 17        | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 15        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 15        | 0.28%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 14        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 14        | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 14        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 13        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 12        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 11        | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 11        | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 11        | 0.2%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 10        | 0.18%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 10        | 0.18%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                          | 10        | 0.18%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 9         | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.17%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 9         | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 8         | 0.15%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 8         | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 8         | 0.15%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 8         | 0.15%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 8         | 0.15%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                    | 8         | 0.15%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 8         | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 8         | 0.15%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 8         | 0.15%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 8         | 0.15%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 8         | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                        | 8         | 0.15%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 8         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2355      | 48.17%  |
| 1366x768 (WXGA)    | 675       | 13.81%  |
| 3840x2160 (4K)     | 360       | 7.36%   |
| 2560x1440 (QHD)    | 274       | 5.6%    |
| 1600x900 (HD+)     | 172       | 3.52%   |
| 1920x1200 (WUXGA)  | 164       | 3.35%   |
| 1680x1050 (WSXGA+) | 113       | 2.31%   |
| 1280x1024 (SXGA)   | 91        | 1.86%   |
| Unknown            | 77        | 1.57%   |
| 3440x1440          | 67        | 1.37%   |
| 1440x900 (WXGA+)   | 65        | 1.33%   |
| 2560x1080          | 53        | 1.08%   |
| 2560x1600          | 51        | 1.04%   |
| 1280x800 (WXGA)    | 42        | 0.86%   |
| 3840x1080          | 37        | 0.76%   |
| 2880x1800          | 35        | 0.72%   |
| 1360x768           | 33        | 0.67%   |
| 3840x2400          | 21        | 0.43%   |
| 2160x1440          | 21        | 0.43%   |
| 1920x540           | 14        | 0.29%   |
| 1600x1200          | 13        | 0.27%   |
| 1024x768 (XGA)     | 12        | 0.25%   |
| 2240x1400          | 11        | 0.22%   |
| 3840x1200          | 9         | 0.18%   |
| 3200x1800 (QHD+)   | 8         | 0.16%   |
| 2256x1504          | 8         | 0.16%   |
| 1920x1280          | 8         | 0.16%   |
| 4480x1440          | 6         | 0.12%   |
| 3840x1600          | 6         | 0.12%   |
| 1280x720 (HD)      | 6         | 0.12%   |
| 2736x1824          | 5         | 0.1%    |
| 5760x1080          | 4         | 0.08%   |
| 3456x2160          | 4         | 0.08%   |
| 3200x2000          | 4         | 0.08%   |
| 3072x1920          | 4         | 0.08%   |
| 2520x1680          | 4         | 0.08%   |
| 2288x1287          | 4         | 0.08%   |
| 5760x2160          | 3         | 0.06%   |
| 3600x1080          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1215      | 23.45%  |
| 27      | 454       | 8.76%   |
| 24      | 452       | 8.72%   |
| 13      | 420       | 8.11%   |
| 14      | 408       | 7.87%   |
| 23      | 361       | 6.97%   |
| 17      | 300       | 5.79%   |
| 21      | 284       | 5.48%   |
| Unknown | 245       | 4.73%   |
| 31      | 134       | 2.59%   |
| 34      | 105       | 2.03%   |
| 19      | 98        | 1.89%   |
| 22      | 70        | 1.35%   |
| 16      | 69        | 1.33%   |
| 20      | 68        | 1.31%   |
| 12      | 64        | 1.24%   |
| 11      | 57        | 1.1%    |
| 18      | 53        | 1.02%   |
| 32      | 32        | 0.62%   |
| 84      | 30        | 0.58%   |
| 72      | 29        | 0.56%   |
| 54      | 29        | 0.56%   |
| 40      | 28        | 0.54%   |
| 25      | 25        | 0.48%   |
| 26      | 15        | 0.29%   |
| 28      | 13        | 0.25%   |
| 46      | 12        | 0.23%   |
| 48      | 11        | 0.21%   |
| 42      | 8         | 0.15%   |
| 37      | 8         | 0.15%   |
| 10      | 7         | 0.14%   |
| 65      | 6         | 0.12%   |
| 52      | 6         | 0.12%   |
| 36      | 5         | 0.1%    |
| 29      | 5         | 0.1%    |
| 69      | 4         | 0.08%   |
| 60      | 4         | 0.08%   |
| 49      | 4         | 0.08%   |
| 39      | 4         | 0.08%   |
| 35      | 4         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1887      | 37.39%  |
| 501-600        | 1156      | 22.9%   |
| 401-500        | 508       | 10.07%  |
| 351-400        | 354       | 7.01%   |
| 201-300        | 335       | 6.64%   |
| Unknown        | 245       | 4.85%   |
| 601-700        | 201       | 3.98%   |
| 701-800        | 144       | 2.85%   |
| 1001-1500      | 85        | 1.68%   |
| 1501-2000      | 67        | 1.33%   |
| 801-900        | 46        | 0.91%   |
| 901-1000       | 11        | 0.22%   |
| More than 2000 | 3         | 0.06%   |
| 1-100          | 3         | 0.06%   |
| 101-200        | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3454      | 76.47%  |
| 16/10   | 526       | 11.64%  |
| Unknown | 212       | 4.69%   |
| 21/9    | 119       | 2.63%   |
| 5/4     | 85        | 1.88%   |
| 3/2     | 59        | 1.31%   |
| 4/3     | 28        | 0.62%   |
| 32/9    | 16        | 0.35%   |
| 6/5     | 5         | 0.11%   |
| 0.56    | 4         | 0.09%   |
| 1.00    | 3         | 0.07%   |
| 1.96    | 2         | 0.04%   |
| 3.40    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.25    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1214      | 23.83%  |
| 201-250        | 881       | 17.29%  |
| 81-90          | 657       | 12.9%   |
| 301-350        | 467       | 9.17%   |
| 351-500        | 287       | 5.63%   |
| Unknown        | 245       | 4.81%   |
| 151-200        | 235       | 4.61%   |
| 121-130        | 234       | 4.59%   |
| 71-80          | 178       | 3.49%   |
| 251-300        | 177       | 3.47%   |
| More than 1000 | 129       | 2.53%   |
| 141-150        | 83        | 1.63%   |
| 501-1000       | 82        | 1.61%   |
| 111-120        | 61        | 1.2%    |
| 51-60          | 58        | 1.14%   |
| 61-70          | 52        | 1.02%   |
| 131-140        | 28        | 0.55%   |
| 91-100         | 14        | 0.27%   |
| 41-50          | 7         | 0.14%   |
| 1-40           | 5         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1554      | 31.43%  |
| 121-160       | 1448      | 29.29%  |
| 101-120       | 1076      | 21.76%  |
| 161-240       | 353       | 7.14%   |
| Unknown       | 245       | 4.96%   |
| More than 240 | 148       | 2.99%   |
| 1-50          | 120       | 2.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3325      | 73.79%  |
| 2     | 948       | 21.04%  |
| 3     | 118       | 2.62%   |
| 0     | 98        | 2.17%   |
| 4     | 17        | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2500      | 37.46%  |
| Intel                             | 2296      | 34.41%  |
| Qualcomm Atheros                  | 623       | 9.34%   |
| Broadcom                          | 280       | 4.2%    |
| MediaTek                          | 153       | 2.29%   |
| TP-Link                           | 79        | 1.18%   |
| Ralink Technology                 | 67        | 1%      |
| Ralink                            | 59        | 0.88%   |
| Broadcom Limited                  | 48        | 0.72%   |
| ASIX Electronics                  | 39        | 0.58%   |
| Nvidia                            | 36        | 0.54%   |
| Marvell Technology Group          | 32        | 0.48%   |
| Samsung Electronics               | 30        | 0.45%   |
| DisplayLink                       | 26        | 0.39%   |
| Aquantia                          | 24        | 0.36%   |
| Qualcomm Atheros Communications   | 21        | 0.31%   |
| NetGear                           | 21        | 0.31%   |
| Lenovo                            | 21        | 0.31%   |
| Xiaomi                            | 20        | 0.3%    |
| Qualcomm                          | 20        | 0.3%    |
| Microsoft                         | 20        | 0.3%    |
| Huawei Technologies               | 19        | 0.28%   |
| Sierra Wireless                   | 16        | 0.24%   |
| D-Link                            | 15        | 0.22%   |
| Dell                              | 14        | 0.21%   |
| ASUSTek Computer                  | 14        | 0.21%   |
| Edimax Technology                 | 12        | 0.18%   |
| Hewlett-Packard                   | 11        | 0.16%   |
| Ericsson Business Mobile Networks | 11        | 0.16%   |
| JMicron Technology                | 8         | 0.12%   |
| Apple                             | 8         | 0.12%   |
| Linksys                           | 7         | 0.1%    |
| Google                            | 7         | 0.1%    |
| D-Link System                     | 7         | 0.1%    |
| Belkin Components                 | 7         | 0.1%    |
| AVM                               | 6         | 0.09%   |
| Fibocom                           | 5         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.06%   |
| VIA Technologies                  | 4         | 0.06%   |
| Arduino SA                        | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1683      | 21.54%  |
| Intel Wi-Fi 6 AX200                                               | 255       | 3.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 217       | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 156       | 2%      |
| Realtek RTL8125 2.5GbE Controller                                 | 155       | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 150       | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 143       | 1.83%   |
| Intel I211 Gigabit Network Connection                             | 135       | 1.73%   |
| Intel Wi-Fi 6 AX201                                               | 132       | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 119       | 1.52%   |
| Intel Wireless 7265                                               | 106       | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 103       | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 99        | 1.27%   |
| Intel Wireless 7260                                               | 99        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 97        | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 90        | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 83        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 80        | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 79        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 77        | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 77        | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 72        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 67        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 67        | 0.86%   |
| Intel Wireless 8260                                               | 66        | 0.84%   |
| Intel Wireless 3165                                               | 66        | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 65        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 59        | 0.76%   |
| Intel Wireless-AC 9260                                            | 53        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 51        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 50        | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 49        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 47        | 0.6%    |
| Intel Ethernet Connection (7) I219-V                              | 47        | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 44        | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 42        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 38        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 37        | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 36        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1762      | 48.42%  |
| Realtek Semiconductor                 | 606       | 16.65%  |
| Qualcomm Atheros                      | 491       | 13.49%  |
| Broadcom                              | 188       | 5.17%   |
| MediaTek                              | 147       | 4.04%   |
| TP-Link                               | 71        | 1.95%   |
| Ralink Technology                     | 67        | 1.84%   |
| Ralink                                | 59        | 1.62%   |
| Broadcom Limited                      | 37        | 1.02%   |
| Qualcomm Atheros Communications       | 21        | 0.58%   |
| NetGear                               | 21        | 0.58%   |
| Microsoft                             | 19        | 0.52%   |
| Sierra Wireless                       | 16        | 0.44%   |
| D-Link                                | 15        | 0.41%   |
| Qualcomm                              | 14        | 0.38%   |
| ASUSTek Computer                      | 14        | 0.38%   |
| Edimax Technology                     | 12        | 0.33%   |
| Dell                                  | 11        | 0.3%    |
| Belkin Components                     | 7         | 0.19%   |
| Marvell Technology Group              | 6         | 0.16%   |
| Linksys                               | 6         | 0.16%   |
| AVM                                   | 6         | 0.16%   |
| Fibocom                               | 5         | 0.14%   |
| Ericsson Business Mobile Networks     | 5         | 0.14%   |
| D-Link System                         | 5         | 0.14%   |
| Hewlett-Packard                       | 4         | 0.11%   |
| Wacom                                 | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| ZyDAS                                 | 2         | 0.05%   |
| Wilocity                              | 2         | 0.05%   |
| Mercucys                              | 2         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.05%   |
| Texas Instruments                     | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| LG Electronics                        | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 255       | 6.95%   |
| Intel Wireless 8265 / 8275                                     | 143       | 3.9%    |
| Intel Wi-Fi 6 AX201                                            | 132       | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 119       | 3.24%   |
| Intel Wireless 7265                                            | 106       | 2.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 103       | 2.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 99        | 2.7%    |
| Intel Wireless 7260                                            | 99        | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 97        | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 90        | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 83        | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 80        | 2.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 79        | 2.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 77        | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 67        | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 67        | 1.83%   |
| Intel Wireless 8260                                            | 66        | 1.8%    |
| Intel Wireless 3165                                            | 66        | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 59        | 1.61%   |
| Intel Wireless-AC 9260                                         | 53        | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 51        | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 50        | 1.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 47        | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 44        | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 42        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 38        | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 37        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 36        | 0.98%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 35        | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 34        | 0.93%   |
| Ralink MT7601U Wireless Adapter                                | 31        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 31        | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 29        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 29        | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 29        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 29        | 0.79%   |
| Realtek 802.11ac NIC                                           | 28        | 0.76%   |
| Intel Wireless 3160                                            | 28        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 27        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 24        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2225      | 55.96%  |
| Intel                            | 1131      | 28.45%  |
| Qualcomm Atheros                 | 173       | 4.35%   |
| Broadcom                         | 120       | 3.02%   |
| ASIX Electronics                 | 39        | 0.98%   |
| Nvidia                           | 36        | 0.91%   |
| Marvell Technology Group         | 26        | 0.65%   |
| DisplayLink                      | 26        | 0.65%   |
| Aquantia                         | 24        | 0.6%    |
| Samsung Electronics              | 21        | 0.53%   |
| Lenovo                           | 21        | 0.53%   |
| Xiaomi                           | 20        | 0.5%    |
| Huawei Technologies              | 16        | 0.4%    |
| Broadcom Limited                 | 12        | 0.3%    |
| TP-Link                          | 8         | 0.2%    |
| JMicron Technology               | 8         | 0.2%    |
| Apple                            | 8         | 0.2%    |
| Google                           | 7         | 0.18%   |
| Qualcomm                         | 6         | 0.15%   |
| MediaTek                         | 6         | 0.15%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.1%    |
| VIA Technologies                 | 4         | 0.1%    |
| T & A Mobile Phones              | 3         | 0.08%   |
| Mellanox Technologies            | 3         | 0.08%   |
| Solarflare Communications        | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| Motorola PCS                     | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| IBM                              | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| D-Link System                    | 2         | 0.05%   |
| American Megatrends              | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| Tehuti Networks                  | 1         | 0.03%   |
| Spreadtrum Communications        | 1         | 0.03%   |
| QNAP System                      | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| Motorola BCS                     | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1683      | 41.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 217       | 5.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 156       | 3.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 155       | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 150       | 3.67%   |
| Intel I211 Gigabit Network Connection                             | 135       | 3.3%    |
| Intel Ethernet Connection (2) I219-V                              | 77        | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 72        | 1.76%   |
| Intel Ethernet Connection I217-LM                                 | 65        | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 49        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 47        | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 35        | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 34        | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 31        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 28        | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 26        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 23        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 23        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 21        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 19        | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 18        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.37%   |
| Intel Ethernet Connection (13) I219-V                             | 15        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15        | 0.37%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3698      | 51.35%  |
| WiFi     | 3449      | 47.9%   |
| Modem    | 50        | 0.69%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2697      | 57.81%  |
| Ethernet | 1967      | 42.17%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2345      | 53.07%  |
| 1     | 1872      | 42.36%  |
| 3     | 109       | 2.47%   |
| 0     | 70        | 1.58%   |
| 4     | 17        | 0.38%   |
| 6     | 4         | 0.09%   |
| 5     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3530      | 78.85%  |
| Yes     | 946       | 21.13%  |
| Unknown | 1         | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1532      | 50.48%  |
| Realtek Semiconductor           | 316       | 10.41%  |
| Qualcomm Atheros Communications | 215       | 7.08%   |
| Cambridge Silicon Radio         | 200       | 6.59%   |
| Broadcom                        | 140       | 4.61%   |
| IMC Networks                    | 128       | 4.22%   |
| Lite-On Technology              | 93        | 3.06%   |
| Foxconn / Hon Hai               | 93        | 3.06%   |
| Apple                           | 62        | 2.04%   |
| ASUSTek Computer                | 54        | 1.78%   |
| Dell                            | 34        | 1.12%   |
| Realtek                         | 31        | 1.02%   |
| MediaTek                        | 23        | 0.76%   |
| Ralink                          | 19        | 0.63%   |
| Hewlett-Packard                 | 13        | 0.43%   |
| Toshiba                         | 12        | 0.4%    |
| TP-Link                         | 11        | 0.36%   |
| Foxconn International           | 9         | 0.3%    |
| Marvell Semiconductor           | 7         | 0.23%   |
| Ralink Technology               | 5         | 0.16%   |
| Dynex                           | 5         | 0.16%   |
| USI                             | 4         | 0.13%   |
| Edimax Technology               | 4         | 0.13%   |
| Alps Electric                   | 4         | 0.13%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Integrated System Solution      | 2         | 0.07%   |
| D-Link                          | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| GN Netcom                       | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 491       | 16.16%  |
| Intel AX201 Bluetooth                               | 307       | 10.1%   |
| Intel AX200 Bluetooth                               | 249       | 8.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 210       | 6.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 200       | 6.58%   |
| Realtek Bluetooth Radio                             | 175       | 5.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 111       | 3.65%   |
| Intel Bluetooth Device                              | 83        | 2.73%   |
| Realtek  Bluetooth 4.2 Adapter                      | 82        | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 50        | 1.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 47        | 1.55%   |
| Intel AX210 Bluetooth                               | 47        | 1.55%   |
| IMC Networks Bluetooth Radio                        | 45        | 1.48%   |
| IMC Networks Wireless_Device                        | 41        | 1.35%   |
| Realtek 802.11ac WLAN Adapter                       | 34        | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 34        | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 33        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 31        | 1.02%   |
| Lite-On Bluetooth Device                            | 30        | 0.99%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 29        | 0.95%   |
| Apple Bluetooth Host Controller                     | 27        | 0.89%   |
| Realtek 802.11ac WLAN Adapter                       | 24        | 0.79%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 24        | 0.79%   |
| MediaTek Wireless_Device                            | 23        | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 0.76%   |
| Lite-On Wireless_Device                             | 22        | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 21        | 0.69%   |
| IMC Networks Bluetooth Device                       | 20        | 0.66%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.63%   |
| Apple Bluetooth USB Host Controller                 | 18        | 0.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 17        | 0.56%   |
| ASUS ASUS USB-BT500                                 | 17        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 16        | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 0.46%   |
| Broadcom HP Portable SoftSailing                    | 14        | 0.46%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 13        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3065      | 47.09%  |
| AMD                        | 1464      | 22.49%  |
| Nvidia                     | 1173      | 18.02%  |
| C-Media Electronics        | 123       | 1.89%   |
| Logitech                   | 49        | 0.75%   |
| GN Netcom                  | 45        | 0.69%   |
| Creative Labs              | 39        | 0.6%    |
| Realtek Semiconductor      | 36        | 0.55%   |
| JMTek                      | 35        | 0.54%   |
| Texas Instruments          | 27        | 0.41%   |
| ASUSTek Computer           | 27        | 0.41%   |
| Generalplus Technology     | 24        | 0.37%   |
| Corsair                    | 22        | 0.34%   |
| Creative Technology        | 21        | 0.32%   |
| Razer USA                  | 19        | 0.29%   |
| Lenovo                     | 19        | 0.29%   |
| Hewlett-Packard            | 18        | 0.28%   |
| Focusrite-Novation         | 18        | 0.28%   |
| Plantronics                | 16        | 0.25%   |
| SteelSeries ApS            | 14        | 0.22%   |
| Kingston Technology        | 13        | 0.2%    |
| VIA Technologies           | 11        | 0.17%   |
| DSEA A/S                   | 9         | 0.14%   |
| Dell                       | 9         | 0.14%   |
| Blue Microphones           | 9         | 0.14%   |
| Tenx Technology            | 8         | 0.12%   |
| Sony                       | 7         | 0.11%   |
| Micro Star International   | 7         | 0.11%   |
| SAVITECH                   | 6         | 0.09%   |
| PreSonus Audio Electronics | 5         | 0.08%   |
| Yamaha                     | 4         | 0.06%   |
| Trust                      | 4         | 0.06%   |
| RODE Microphones           | 4         | 0.06%   |
| Nordic Semiconductor ASA   | 4         | 0.06%   |
| M-Audio                    | 4         | 0.06%   |
| GYROCOM C&C                | 4         | 0.06%   |
| BEHRINGER International    | 4         | 0.06%   |
| ZOOM                       | 3         | 0.05%   |
| XMOS                       | 3         | 0.05%   |
| TerraTec Electronic        | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 537       | 6.89%   |
| Intel Sunrise Point-LP HD Audio                                            | 332       | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 273       | 3.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 268       | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 240       | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 232       | 2.98%   |
| AMD Starship/Matisse HD Audio Controller                                   | 224       | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 217       | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 187       | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 186       | 2.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 168       | 2.16%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 141       | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 131       | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 122       | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 118       | 1.51%   |
| AMD FCH Azalia Controller                                                  | 112       | 1.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 106       | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 101       | 1.3%    |
| Intel 8 Series HD Audio Controller                                         | 100       | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 99        | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 97        | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 90        | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 90        | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 89        | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 84        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 80        | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 80        | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 77        | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 76        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 74        | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 74        | 0.95%   |
| Intel Broadwell-U Audio Controller                                         | 69        | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 68        | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 68        | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 62        | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 61        | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 58        | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 57        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 57        | 0.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 56        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 720       | 21.96%  |
| SK hynix            | 521       | 15.89%  |
| Kingston            | 417       | 12.72%  |
| Micron Technology   | 347       | 10.58%  |
| Crucial             | 239       | 7.29%   |
| Unknown             | 206       | 6.28%   |
| Corsair             | 206       | 6.28%   |
| G.Skill             | 147       | 4.48%   |
| A-DATA Technology   | 67        | 2.04%   |
| Ramaxel Technology  | 54        | 1.65%   |
| Unknown (ABCD)      | 46        | 1.4%    |
| Nanya Technology    | 38        | 1.16%   |
| Elpida              | 34        | 1.04%   |
| Team                | 25        | 0.76%   |
| Unknown             | 23        | 0.7%    |
| Patriot             | 22        | 0.67%   |
| Transcend           | 17        | 0.52%   |
| Smart               | 17        | 0.52%   |
| GOODRAM             | 9         | 0.27%   |
| Silicon Power       | 8         | 0.24%   |
| AMD                 | 8         | 0.24%   |
| Apacer              | 7         | 0.21%   |
| Avant               | 6         | 0.18%   |
| Wilk                | 5         | 0.15%   |
| Teikon              | 5         | 0.15%   |
| Smart Brazil        | 5         | 0.15%   |
| PNY                 | 4         | 0.12%   |
| ASint Technology    | 4         | 0.12%   |
| SHARETRONIC         | 3         | 0.09%   |
| Lexar               | 3         | 0.09%   |
| Goldkey             | 3         | 0.09%   |
| GeIL                | 3         | 0.09%   |
| CSX                 | 3         | 0.09%   |
| 4ea5                | 3         | 0.09%   |
| V-GeN               | 2         | 0.06%   |
| Unifosa             | 2         | 0.06%   |
| Reboto              | 2         | 0.06%   |
| Kllisre             | 2         | 0.06%   |
| Kingmax             | 2         | 0.06%   |
| KINGBANK            | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 37        | 1.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 30        | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 29        | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 27        | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.65%   |
| Unknown                                                          | 23        | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 21        | 0.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 21        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 19        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 18        | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 18        | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 14        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.37%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.37%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.31%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 11        | 0.31%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.28%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.28%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.28%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.28%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.28%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 10        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1581      | 56.32%  |
| DDR3    | 745       | 26.54%  |
| LPDDR4  | 141       | 5.02%   |
| DDR5    | 72        | 2.57%   |
| Unknown | 66        | 2.35%   |
| LPDDR3  | 61        | 2.17%   |
| DDR2    | 51        | 1.82%   |
| SDRAM   | 39        | 1.39%   |
| LPDDR5  | 39        | 1.39%   |
| DDR     | 10        | 0.36%   |
| DRAM    | 2         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1596      | 56.66%  |
| DIMM         | 943       | 33.48%  |
| Row Of Chips | 246       | 8.73%   |
| Chip         | 15        | 0.53%   |
| Unknown      | 12        | 0.43%   |
| FB-DIMM      | 3         | 0.11%   |
| RIMM         | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1330      | 43.21%  |
| 4096  | 743       | 24.14%  |
| 16384 | 598       | 19.43%  |
| 2048  | 241       | 7.83%   |
| 32768 | 131       | 4.26%   |
| 1024  | 31        | 1.01%   |
| 12288 | 1         | 0.03%   |
| 512   | 1         | 0.03%   |
| 256   | 1         | 0.03%   |
| 128   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 558       | 18.3%   |
| 2667    | 514       | 16.86%  |
| 1600    | 504       | 16.53%  |
| 2400    | 260       | 8.53%   |
| 1333    | 174       | 5.71%   |
| 2133    | 143       | 4.69%   |
| 3600    | 102       | 3.35%   |
| 4267    | 63        | 2.07%   |
| 1334    | 63        | 2.07%   |
| 4800    | 45        | 1.48%   |
| 1867    | 45        | 1.48%   |
| 6400    | 38        | 1.25%   |
| 800     | 35        | 1.15%   |
| 2666    | 31        | 1.02%   |
| 3733    | 30        | 0.98%   |
| 667     | 30        | 0.98%   |
| 3266    | 29        | 0.95%   |
| Unknown | 25        | 0.82%   |
| 3400    | 24        | 0.79%   |
| 2933    | 23        | 0.75%   |
| 3800    | 22        | 0.72%   |
| 3000    | 22        | 0.72%   |
| 1067    | 17        | 0.56%   |
| 1066    | 17        | 0.56%   |
| 1866    | 15        | 0.49%   |
| 8400    | 14        | 0.46%   |
| 3866    | 13        | 0.43%   |
| 1800    | 13        | 0.43%   |
| 5600    | 12        | 0.39%   |
| 2800    | 11        | 0.36%   |
| 4266    | 10        | 0.33%   |
| 4199    | 10        | 0.33%   |
| 3666    | 10        | 0.33%   |
| 3533    | 10        | 0.33%   |
| 400     | 9         | 0.3%    |
| 3333    | 8         | 0.26%   |
| 3466    | 7         | 0.23%   |
| 3066    | 7         | 0.23%   |
| 6000    | 6         | 0.2%    |
| 3534    | 6         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 50        | 37.59%  |
| Brother Industries     | 28        | 21.05%  |
| Seiko Epson            | 14        | 10.53%  |
| Samsung Electronics    | 11        | 8.27%   |
| Canon                  | 11        | 8.27%   |
| Dymo-CoStar            | 3         | 2.26%   |
| Zebra                  | 2         | 1.5%    |
| Xerox                  | 2         | 1.5%    |
| Prolific Technology    | 2         | 1.5%    |
| Pantum                 | 2         | 1.5%    |
| Ricoh                  | 1         | 0.75%   |
| QinHeng Electronics    | 1         | 0.75%   |
| Panasonic (Matsushita) | 1         | 0.75%   |
| Kyocera                | 1         | 0.75%   |
| ICS Advent             | 1         | 0.75%   |
| Datamax-O'Neil         | 1         | 0.75%   |
| BESTEASY               | 1         | 0.75%   |
| Apple                  | 1         | 0.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP HP OfficeJet Pro 8020 series                        | 3         | 2.22%   |
| Seiko Epson L360 Series                                | 2         | 1.48%   |
| Seiko Epson L3110 Series                               | 2         | 1.48%   |
| Samsung M2070 Series                                   | 2         | 1.48%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.48%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.48%   |
| HP LaserJet P2015 series                               | 2         | 1.48%   |
| HP LaserJet 1020                                       | 2         | 1.48%   |
| HP LaserJet 1018                                       | 2         | 1.48%   |
| HP ENVY 4500 series                                    | 2         | 1.48%   |
| HP DeskJet 2700 series                                 | 2         | 1.48%   |
| HP DeskJet 2620 All-in-One Printer                     | 2         | 1.48%   |
| Brother MFC-J460DW                                     | 2         | 1.48%   |
| Brother HL-L2320D series                               | 2         | 1.48%   |
| Brother HL-2230 series                                 | 2         | 1.48%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.74%   |
| Zebra Thrmal 2844                                      | 1         | 0.74%   |
| Xerox Phaser 6500N                                     | 1         | 0.74%   |
| Xerox Phaser 3140 and 3155                             | 1         | 0.74%   |
| Seiko Epson XP-7100 Series                             | 1         | 0.74%   |
| Seiko Epson XP-3100 Series                             | 1         | 0.74%   |
| Seiko Epson XP-2200 Series                             | 1         | 0.74%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.74%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.74%   |
| Seiko Epson Printer                                    | 1         | 0.74%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.74%   |
| Seiko Epson L3150 Series                               | 1         | 0.74%   |
| Seiko Epson L120 Series                                | 1         | 0.74%   |
| Seiko Epson ET-2700 Series                             | 1         | 0.74%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.74%   |
| Samsung SCX-3200 Series                                | 1         | 0.74%   |
| Samsung ML-2250 Series                                 | 1         | 0.74%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.74%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.74%   |
| Samsung M2020 Series                                   | 1         | 0.74%   |
| Samsung CLX-3180 Series                                | 1         | 0.74%   |
| Samsung CLX-3170 Series                                | 1         | 0.74%   |
| Samsung CLP-360 Series                                 | 1         | 0.74%   |
| Ricoh SP 211SU                                         | 1         | 0.74%   |
| QinHeng CH340S                                         | 1         | 0.74%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 51.72%  |
| Seiko Epson     | 8         | 27.59%  |
| Mustek Systems  | 3         | 10.34%  |
| Hewlett-Packard | 3         | 10.34%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 3         | 10.34%  |
| Canon CanoScan N670U/N676U/LiDE 20                      | 3         | 10.34%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 6.9%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 6.9%    |
| Canon CanoScan LIDE 25                                  | 2         | 6.9%    |
| Canon CanoScan LiDE 220                                 | 2         | 6.9%    |
| Canon CanoScan LiDE 210                                 | 2         | 6.9%    |
| Canon CanoScan LiDE 110                                 | 2         | 6.9%    |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 3.45%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 3.45%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 3.45%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 3.45%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 3.45%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 3.45%   |
| HP ScanJet G4010                                        | 1         | 3.45%   |
| HP ScanJet 82x0C                                        | 1         | 3.45%   |
| HP ScanJet 3770                                         | 1         | 3.45%   |
| Canon CanoScan LiDE 60                                  | 1         | 3.45%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.45%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 548       | 18.65%  |
| IMC Networks                           | 293       | 9.97%   |
| Microdia                               | 264       | 8.99%   |
| Logitech                               | 223       | 7.59%   |
| Realtek Semiconductor                  | 218       | 7.42%   |
| Bison Electronics                      | 188       | 6.4%    |
| Quanta                                 | 163       | 5.55%   |
| Sunplus Innovation Technology          | 153       | 5.21%   |
| Cheng Uei Precision Industry (Foxlink) | 114       | 3.88%   |
| Syntek                                 | 65        | 2.21%   |
| Apple                                  | 60        | 2.04%   |
| Acer                                   | 55        | 1.87%   |
| Suyin                                  | 52        | 1.77%   |
| Luxvisions Innotech Limited            | 51        | 1.74%   |
| Lite-On Technology                     | 49        | 1.67%   |
| Silicon Motion                         | 44        | 1.5%    |
| Microsoft                              | 39        | 1.33%   |
| Alcor Micro                            | 32        | 1.09%   |
| Samsung Electronics                    | 30        | 1.02%   |
| Sonix Technology                       | 18        | 0.61%   |
| Generalplus Technology                 | 18        | 0.61%   |
| Ricoh                                  | 17        | 0.58%   |
| Lenovo                                 | 14        | 0.48%   |
| Z-Star Microelectronics                | 13        | 0.44%   |
| SunplusIT                              | 12        | 0.41%   |
| MacroSilicon                           | 9         | 0.31%   |
| KYE Systems (Mouse Systems)            | 9         | 0.31%   |
| ARC International                      | 9         | 0.31%   |
| Y Media                                | 8         | 0.27%   |
| Genesys Logic                          | 8         | 0.27%   |
| icSpring                               | 7         | 0.24%   |
| Huawei Technologies                    | 7         | 0.24%   |
| GEMBIRD                                | 7         | 0.24%   |
| Cubeternet                             | 7         | 0.24%   |
| Sunplus Technology                     | 6         | 0.2%    |
| Importek                               | 6         | 0.2%    |
| Trust                                  | 5         | 0.17%   |
| ShineTech                              | 5         | 0.17%   |
| Razer USA                              | 5         | 0.17%   |
| Primax Electronics                     | 5         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 133       | 4.49%   |
| Microdia Integrated_Webcam_HD                                   | 113       | 3.81%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 90        | 3.04%   |
| IMC Networks Integrated Camera                                  | 88        | 2.97%   |
| Realtek Integrated_Webcam_HD                                    | 87        | 2.94%   |
| Bison Integrated Camera                                         | 73        | 2.46%   |
| Sunplus Integrated_Webcam_HD                                    | 61        | 2.06%   |
| Logitech HD Pro Webcam C920                                     | 50        | 1.69%   |
| Chicony HD Webcam                                               | 50        | 1.69%   |
| Syntek Integrated Camera                                        | 47        | 1.59%   |
| Logitech Webcam C270                                            | 42        | 1.42%   |
| Quanta HD User Facing                                           | 33        | 1.11%   |
| Chicony HP HD Camera                                            | 33        | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 29        | 0.98%   |
| Chicony HD User Facing                                          | 29        | 0.98%   |
| Bison HD Webcam                                                 | 26        | 0.88%   |
| Quanta HP HD Camera                                             | 23        | 0.78%   |
| Microdia Integrated Webcam                                      | 23        | 0.78%   |
| Microdia Webcam Vitade AF                                       | 22        | 0.74%   |
| Quanta HP TrueVision HD Camera                                  | 21        | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 21        | 0.71%   |
| Realtek USB Camera                                              | 20        | 0.67%   |
| Chicony USB2.0 Camera                                           | 20        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)                         | 20        | 0.67%   |
| Chicony HP Wide Vision HD Camera                                | 20        | 0.67%   |
| Lite-On Integrated Camera                                       | 18        | 0.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 18        | 0.61%   |
| Microdia Integrated_Webcam_FHD                                  | 17        | 0.57%   |
| Alcor Micro USB 2.0 Camera                                      | 17        | 0.57%   |
| Quanta HD Webcam                                                | 16        | 0.54%   |
| Microsoft LifeCam HD-3000                                       | 16        | 0.54%   |
| Chicony HP Truevision HD camera                                 | 16        | 0.54%   |
| Chicony HP TrueVision HD                                        | 16        | 0.54%   |
| Bison Lenovo EasyCamera                                         | 16        | 0.54%   |
| Acer BisonCam,NB Pro                                            | 16        | 0.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 15        | 0.51%   |
| Logitech C922 Pro Stream Webcam                                 | 15        | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 15        | 0.51%   |
| Realtek Integrated Webcam                                       | 14        | 0.47%   |
| Quanta HP Wide Vision HD Camera                                 | 14        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 195       | 33.11%  |
| Validity Sensors                   | 153       | 25.98%  |
| Shenzhen Goodix Technology         | 116       | 19.69%  |
| Elan Microelectronics              | 42        | 7.13%   |
| AuthenTec                          | 24        | 4.07%   |
| Upek                               | 22        | 3.74%   |
| LighTuning Technology              | 22        | 3.74%   |
| STMicroelectronics                 | 6         | 1.02%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.68%   |
| Focal-systems.Corp                 | 2         | 0.34%   |
| Samsung Electronics                | 1         | 0.17%   |
| HOLTEK                             | 1         | 0.17%   |
| DigitalPersona                     | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 67        | 11.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 60        | 10.19%  |
| Shenzhen Goodix Fingerprint Reader                                         | 32        | 5.43%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 31        | 5.26%   |
| Elan ELAN:Fingerprint                                                      | 23        | 3.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 3.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 3.74%   |
| Synaptics UWP WBDI                                                         | 19        | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 17        | 2.89%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 2.89%   |
| Elan ELAN:ARM-M4                                                           | 17        | 2.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 2.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 2.38%   |
| Synaptics WBDI                                                             | 13        | 2.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 2.04%   |
| Synaptics  WBDI                                                            | 12        | 2.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 1.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 1.7%    |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 1.7%    |
| AuthenTec AES2810                                                          | 9         | 1.53%   |
| Validity Sensors VFS491                                                    | 8         | 1.36%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 8         | 1.36%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.19%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.02%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.02%   |
| Synaptics TouchPad                                                         | 6         | 1.02%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.02%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.85%   |
| Unknown                                                                    | 5         | 0.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.68%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.68%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.68%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 109       | 43.25%  |
| Alcor Micro               | 74        | 29.37%  |
| Upek                      | 14        | 5.56%   |
| O2 Micro                  | 9         | 3.57%   |
| Lenovo                    | 8         | 3.17%   |
| Advanced Card Systems     | 7         | 2.78%   |
| SCM Microsystems          | 4         | 1.59%   |
| Yubico.com                | 3         | 1.19%   |
| OmniKey                   | 3         | 1.19%   |
| Gemalto (was Gemplus)     | 3         | 1.19%   |
| Reiner SCT Kartensysteme  | 2         | 0.79%   |
| Realtek Semiconductor     | 2         | 0.79%   |
| Fujitsu Siemens Computers | 2         | 0.79%   |
| Clay Logic                | 2         | 0.79%   |
| Bit4id                    | 2         | 0.79%   |
| Aladdin R.D.              | 2         | 0.79%   |
| Watchdata                 | 1         | 0.4%    |
| In Focus Systems          | 1         | 0.4%    |
| Giesecke & Devrient       | 1         | 0.4%    |
| Chicony Electronics       | 1         | 0.4%    |
| Aladdin Knowledge Systems | 1         | 0.4%    |
| Aktiv                     | 1         | 0.4%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 28.17%  |
| Broadcom 5880                                                                | 32        | 12.7%   |
| Broadcom 58200                                                               | 31        | 12.3%   |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 10.71%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 6.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 3.57%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.17%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.59%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.19%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.19%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.19%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.79%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.79%   |
| OmniKey CardMan 1021                                                         | 2         | 0.79%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.79%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.79%   |
| Bit4id miniLector EVO                                                        | 2         | 0.79%   |
| Aladdin R.D. JaCarta                                                         | 2         | 0.79%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.79%   |
| Watchdata USB Key                                                            | 1         | 0.4%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.4%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.4%    |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.4%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.4%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.4%    |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.4%    |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.4%    |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.4%    |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.4%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.4%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.4%    |
| Aktiv Rutoken lite                                                           | 1         | 0.4%    |
| Advanced Card Systems ACR1252 CL Reader PICC                                 | 1         | 0.4%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3075      | 68.27%  |
| 1     | 1156      | 25.67%  |
| 2     | 227       | 5.04%   |
| 3     | 25        | 0.56%   |
| 4     | 9         | 0.2%    |
| 7     | 4         | 0.09%   |
| 6     | 4         | 0.09%   |
| 5     | 3         | 0.07%   |
| 9     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 579       | 34%     |
| Graphics card            | 285       | 16.74%  |
| Chipcard                 | 218       | 12.8%   |
| Net/wireless             | 202       | 11.86%  |
| Multimedia controller    | 80        | 4.7%    |
| Camera                   | 80        | 4.7%    |
| Bluetooth                | 49        | 2.88%   |
| Sound                    | 47        | 2.76%   |
| Unassigned class         | 40        | 2.35%   |
| Communication controller | 39        | 2.29%   |
| Card reader              | 23        | 1.35%   |
| Storage                  | 20        | 1.17%   |
| Net/ethernet             | 11        | 0.65%   |
| Network                  | 8         | 0.47%   |
| Storage/ide              | 7         | 0.41%   |
| Modem                    | 7         | 0.41%   |
| Firewire controller      | 4         | 0.23%   |
| Dvb card                 | 3         | 0.18%   |
| Storage/raid             | 1         | 0.06%   |


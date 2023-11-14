Linux in Canada - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 4374

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | G61                         | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| Valve         | Jupiter                     | [aef9c84cf7](https://linux-hardware.org/?probe=aef9c84cf7) | Nov 06, 2023 |
| Valve         | Jupiter                     | [d8ac880948](https://linux-hardware.org/?probe=d8ac880948) | Nov 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [ad7dc81954](https://linux-hardware.org/?probe=ad7dc81954) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| Acer          | AO532h                      | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| HP            | EliteBook 840 G4            | [5abff2e87a](https://linux-hardware.org/?probe=5abff2e87a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1bdfa38b3e](https://linux-hardware.org/?probe=1bdfa38b3e) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [3c92af97b9](https://linux-hardware.org/?probe=3c92af97b9) | Nov 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [99992393e4](https://linux-hardware.org/?probe=99992393e4) | Nov 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [11c06a97d7](https://linux-hardware.org/?probe=11c06a97d7) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | [0ea1a71a53](https://linux-hardware.org/?probe=0ea1a71a53) | Oct 31, 2023 |
| Lenovo        | ThinkPad T440 20B7S03Q00    | [de24032ac7](https://linux-hardware.org/?probe=de24032ac7) | Oct 30, 2023 |
| Dell          | Latitude 5490               | [63f4fce332](https://linux-hardware.org/?probe=63f4fce332) | Oct 30, 2023 |
| Acer          | Nitro AN515-55              | [0325d9a6e8](https://linux-hardware.org/?probe=0325d9a6e8) | Oct 30, 2023 |
| Acer          | Nitro AN515-55              | [80e9a059c1](https://linux-hardware.org/?probe=80e9a059c1) | Oct 29, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [bf9ff8ba5b](https://linux-hardware.org/?probe=bf9ff8ba5b) | Oct 29, 2023 |
| System76      | Gazelle                     | [3bc4a66a13](https://linux-hardware.org/?probe=3bc4a66a13) | Oct 29, 2023 |
| Acer          | Aspire A315-21              | [7f9b48f63b](https://linux-hardware.org/?probe=7f9b48f63b) | Oct 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [22380583c4](https://linux-hardware.org/?probe=22380583c4) | Oct 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b83a355a39](https://linux-hardware.org/?probe=b83a355a39) | Oct 28, 2023 |
| HUAWEI        | MACHD-WXX9                  | [551a5c8aa2](https://linux-hardware.org/?probe=551a5c8aa2) | Oct 28, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4468cb093d](https://linux-hardware.org/?probe=4468cb093d) | Oct 28, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [c0aef363fa](https://linux-hardware.org/?probe=c0aef363fa) | Oct 28, 2023 |
| Dell          | Latitude E6520              | [dbbca588de](https://linux-hardware.org/?probe=dbbca588de) | Oct 26, 2023 |
| HP            | Laptop 15-da0xxx            | [6c18f4a4ef](https://linux-hardware.org/?probe=6c18f4a4ef) | Oct 25, 2023 |
| ASUSTek       | ZenBook UX434FL             | [139d1a74ed](https://linux-hardware.org/?probe=139d1a74ed) | Oct 25, 2023 |
| Matsushita... | CF-30CTWAZBM                | [4211783dac](https://linux-hardware.org/?probe=4211783dac) | Oct 25, 2023 |
| Dell          | Latitude E6420              | [54c82901c0](https://linux-hardware.org/?probe=54c82901c0) | Oct 25, 2023 |
| Lenovo        | ThinkPad P52 20MAS0WG00     | [e7e16a6ac8](https://linux-hardware.org/?probe=e7e16a6ac8) | Oct 25, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [7476940ad0](https://linux-hardware.org/?probe=7476940ad0) | Oct 25, 2023 |
| Toshiba       | Satellite L655              | [504b65f326](https://linux-hardware.org/?probe=504b65f326) | Oct 25, 2023 |
| Toshiba       | Satellite L655              | [6f1c644900](https://linux-hardware.org/?probe=6f1c644900) | Oct 25, 2023 |
| HP            | Victus by Laptop PC         | [53988c0c73](https://linux-hardware.org/?probe=53988c0c73) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [84883d560d](https://linux-hardware.org/?probe=84883d560d) | Oct 24, 2023 |
| Valve         | Jupiter                     | [fa38785b75](https://linux-hardware.org/?probe=fa38785b75) | Oct 23, 2023 |
| Dell          | XPS 15 7590                 | [e9ecf74d68](https://linux-hardware.org/?probe=e9ecf74d68) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [817367d444](https://linux-hardware.org/?probe=817367d444) | Oct 23, 2023 |
| Dell          | Latitude E6520              | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SS0... | [9877bb17c1](https://linux-hardware.org/?probe=9877bb17c1) | Oct 23, 2023 |
| Dell          | Inspiron 3521               | [43b2c926ef](https://linux-hardware.org/?probe=43b2c926ef) | Oct 22, 2023 |
| ASUSTek       | G750JW                      | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | XPS 13 9300                 | [ccf935ca37](https://linux-hardware.org/?probe=ccf935ca37) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| HP            | 2000                        | [743e2b0bdf](https://linux-hardware.org/?probe=743e2b0bdf) | Oct 22, 2023 |
| Acer          | Aspire 5742                 | [f30dc155bd](https://linux-hardware.org/?probe=f30dc155bd) | Oct 21, 2023 |
| Toshiba       | Satellite A660              | [a5e343d353](https://linux-hardware.org/?probe=a5e343d353) | Oct 21, 2023 |
| Dell          | Latitude E6410              | [5b363ffe33](https://linux-hardware.org/?probe=5b363ffe33) | Oct 21, 2023 |
| Acer          | Aspire 5253                 | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | G7 7700                     | [336bd76568](https://linux-hardware.org/?probe=336bd76568) | Oct 20, 2023 |
| Lenovo        | ThinkPad T510 4384DJ3       | [bd0354850e](https://linux-hardware.org/?probe=bd0354850e) | Oct 19, 2023 |
| Lenovo        | ThinkPad T510 4384DJ3       | [85099af926](https://linux-hardware.org/?probe=85099af926) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| HP            | G60                         | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Alienware     | 13                          | [15e7dfbbab](https://linux-hardware.org/?probe=15e7dfbbab) | Oct 19, 2023 |
| HP            | Pavilion dv7                | [13b6b396e9](https://linux-hardware.org/?probe=13b6b396e9) | Oct 18, 2023 |
| Valve         | Jupiter                     | [6eab7fbd58](https://linux-hardware.org/?probe=6eab7fbd58) | Oct 18, 2023 |
| Gateway       | NV59                        | [ec598a2d11](https://linux-hardware.org/?probe=ec598a2d11) | Oct 18, 2023 |
| Dell          | XPS 15 9500                 | [7e5d5dd6dd](https://linux-hardware.org/?probe=7e5d5dd6dd) | Oct 17, 2023 |
| Lenovo        | ThinkPad P52 20MAS0WG00     | [edfeee597d](https://linux-hardware.org/?probe=edfeee597d) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d5d89eba92](https://linux-hardware.org/?probe=d5d89eba92) | Oct 17, 2023 |
| Sony          | SVE15128CCW                 | [2d2c699b43](https://linux-hardware.org/?probe=2d2c699b43) | Oct 16, 2023 |
| Dell          | Latitude 7440               | [513083adb4](https://linux-hardware.org/?probe=513083adb4) | Oct 16, 2023 |
| Dell          | Latitude 7440               | [f8d4813ce1](https://linux-hardware.org/?probe=f8d4813ce1) | Oct 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [8e489a0275](https://linux-hardware.org/?probe=8e489a0275) | Oct 16, 2023 |
| Alienware     | 13                          | [24ce621e56](https://linux-hardware.org/?probe=24ce621e56) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | [df7395bd63](https://linux-hardware.org/?probe=df7395bd63) | Oct 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [d01a91e5bb](https://linux-hardware.org/?probe=d01a91e5bb) | Oct 15, 2023 |
| Acer          | Aspire A315-21              | [7476ed8679](https://linux-hardware.org/?probe=7476ed8679) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [ae2789f31f](https://linux-hardware.org/?probe=ae2789f31f) | Oct 14, 2023 |
| HP            | Pavilion dv7                | [de47e931a1](https://linux-hardware.org/?probe=de47e931a1) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d4be846a3c](https://linux-hardware.org/?probe=d4be846a3c) | Oct 13, 2023 |
| Acer          | Aspire 7750G                | [d634013b16](https://linux-hardware.org/?probe=d634013b16) | Oct 13, 2023 |
| Notebook      | P9XXEN_EF_ED                | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| Acer          | Aspire E5-523               | [e45e982b6e](https://linux-hardware.org/?probe=e45e982b6e) | Oct 13, 2023 |
| HP            | G61                         | [34e955886e](https://linux-hardware.org/?probe=34e955886e) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [21e9b8cbc9](https://linux-hardware.org/?probe=21e9b8cbc9) | Oct 11, 2023 |
| Chuwi         | GemiBook XPro               | [b9da20666a](https://linux-hardware.org/?probe=b9da20666a) | Oct 10, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d0abc8a7e8](https://linux-hardware.org/?probe=d0abc8a7e8) | Oct 10, 2023 |
| Lenovo        | ThinkPad L490 20Q6S07X00    | [07ebe46482](https://linux-hardware.org/?probe=07ebe46482) | Oct 10, 2023 |
| Gateway       | NV59                        | [79392cad25](https://linux-hardware.org/?probe=79392cad25) | Oct 09, 2023 |
| HP            | EliteBook 840 G3            | [29af84698a](https://linux-hardware.org/?probe=29af84698a) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [60a4c67d48](https://linux-hardware.org/?probe=60a4c67d48) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [65a1ff3587](https://linux-hardware.org/?probe=65a1ff3587) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [a1ae219e54](https://linux-hardware.org/?probe=a1ae219e54) | Oct 09, 2023 |
| Dell          | Latitude 7430               | [1de7d3085b](https://linux-hardware.org/?probe=1de7d3085b) | Oct 08, 2023 |
| Acer          | Aspire A515-54              | [30b5d7d52b](https://linux-hardware.org/?probe=30b5d7d52b) | Oct 08, 2023 |
| Apple         | MacBookPro11,1              | [b30fe669c6](https://linux-hardware.org/?probe=b30fe669c6) | Oct 07, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [aaa295fa26](https://linux-hardware.org/?probe=aaa295fa26) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3854d7db80](https://linux-hardware.org/?probe=3854d7db80) | Oct 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [84eebff0a6](https://linux-hardware.org/?probe=84eebff0a6) | Oct 06, 2023 |
| Dell          | Precision 5540              | [117d31349f](https://linux-hardware.org/?probe=117d31349f) | Oct 05, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [09c308ed3d](https://linux-hardware.org/?probe=09c308ed3d) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7700b3d342](https://linux-hardware.org/?probe=7700b3d342) | Oct 04, 2023 |
| Google        | Fleex                       | [534bbe966a](https://linux-hardware.org/?probe=534bbe966a) | Oct 04, 2023 |
| Valve         | Jupiter                     | [4c7b5edf25](https://linux-hardware.org/?probe=4c7b5edf25) | Oct 04, 2023 |
| HP            | EliteBook 850 G1            | [49b19b9f02](https://linux-hardware.org/?probe=49b19b9f02) | Oct 03, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [eb797a8074](https://linux-hardware.org/?probe=eb797a8074) | Oct 03, 2023 |
| Dell          | Vostro 3550                 | [3d22b8f169](https://linux-hardware.org/?probe=3d22b8f169) | Oct 03, 2023 |
| Fujitsu       | LIFEBOOK AH531              | [4746fb19fb](https://linux-hardware.org/?probe=4746fb19fb) | Oct 03, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [dfeeeb9cbc](https://linux-hardware.org/?probe=dfeeeb9cbc) | Oct 03, 2023 |
| Dell          | Precision 5540              | [2bf28ed41e](https://linux-hardware.org/?probe=2bf28ed41e) | Oct 03, 2023 |
| Dell          | Inspiron 3543               | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G73Jh                       | [0b9b84be03](https://linux-hardware.org/?probe=0b9b84be03) | Oct 01, 2023 |
| Acer          | AOA150                      | [969a729098](https://linux-hardware.org/?probe=969a729098) | Oct 01, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Apple         | MacBookAir6,1               | [b77b45ce58](https://linux-hardware.org/?probe=b77b45ce58) | Sep 29, 2023 |
| ASUSTek       | X505BA                      | [1caa3c5c7e](https://linux-hardware.org/?probe=1caa3c5c7e) | Sep 28, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [1492e2178d](https://linux-hardware.org/?probe=1492e2178d) | Sep 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [f86a0719d7](https://linux-hardware.org/?probe=f86a0719d7) | Sep 28, 2023 |
| Dell          | XPS 15 7590                 | [3c87964524](https://linux-hardware.org/?probe=3c87964524) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [3ee705f2f3](https://linux-hardware.org/?probe=3ee705f2f3) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [2b86c9fac4](https://linux-hardware.org/?probe=2b86c9fac4) | Sep 28, 2023 |
| Acer          | Swift SF314-42              | [f436f21240](https://linux-hardware.org/?probe=f436f21240) | Sep 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [17f9208e1a](https://linux-hardware.org/?probe=17f9208e1a) | Sep 27, 2023 |
| Dell          | Latitude 5420               | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d14e65fadf](https://linux-hardware.org/?probe=d14e65fadf) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [1c764be0e3](https://linux-hardware.org/?probe=1c764be0e3) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [b8b2b3ff7e](https://linux-hardware.org/?probe=b8b2b3ff7e) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [9e9ff26362](https://linux-hardware.org/?probe=9e9ff26362) | Sep 26, 2023 |
| HP            | EliteBook 850 G1            | [55b3c2717b](https://linux-hardware.org/?probe=55b3c2717b) | Sep 25, 2023 |
| Apple         | MacBookPro7,1               | [677446fafa](https://linux-hardware.org/?probe=677446fafa) | Sep 25, 2023 |
| Lenovo        | ThinkPad T60 2623DAU        | [b5edbc8fbf](https://linux-hardware.org/?probe=b5edbc8fbf) | Sep 24, 2023 |
| Lenovo        | ThinkPad T60 2623DAU        | [144d6b3290](https://linux-hardware.org/?probe=144d6b3290) | Sep 24, 2023 |
| HP            | EliteBook 850 G1            | [00bb1a3a44](https://linux-hardware.org/?probe=00bb1a3a44) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [575df2588e](https://linux-hardware.org/?probe=575df2588e) | Sep 23, 2023 |
| Google        | Asuka                       | [cf59aebc4c](https://linux-hardware.org/?probe=cf59aebc4c) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d6943b89de](https://linux-hardware.org/?probe=d6943b89de) | Sep 23, 2023 |
| Apple         | MacBookPro8,1               | [0c1f872edb](https://linux-hardware.org/?probe=0c1f872edb) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [eedf248084](https://linux-hardware.org/?probe=eedf248084) | Sep 23, 2023 |
| Alienware     | m15 R3                      | [d9628d131b](https://linux-hardware.org/?probe=d9628d131b) | Sep 22, 2023 |
| ASUSTek       | GL502VM                     | [ae49f40dca](https://linux-hardware.org/?probe=ae49f40dca) | Sep 22, 2023 |
| Dell          | Latitude 5590               | [068de61e23](https://linux-hardware.org/?probe=068de61e23) | Sep 22, 2023 |
| Lenovo        | Slim 7 14IRP8 83A4          | [b1ccf59045](https://linux-hardware.org/?probe=b1ccf59045) | Sep 21, 2023 |
| Apple         | MacBookPro9,1               | [27f3ee04f8](https://linux-hardware.org/?probe=27f3ee04f8) | Sep 21, 2023 |
| HP            | Pavilion g6                 | [11c60c8645](https://linux-hardware.org/?probe=11c60c8645) | Sep 21, 2023 |
| HP            | ProBook 650 G2              | [215bdc7f1c](https://linux-hardware.org/?probe=215bdc7f1c) | Sep 20, 2023 |
| Dell          | Latitude E5550              | [8e67cb247c](https://linux-hardware.org/?probe=8e67cb247c) | Sep 20, 2023 |
| Apple         | MacBookPro15,1              | [b74bbced53](https://linux-hardware.org/?probe=b74bbced53) | Sep 20, 2023 |
| Dell          | XPS 9320                    | [611c8a5cc8](https://linux-hardware.org/?probe=611c8a5cc8) | Sep 20, 2023 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [f8f954cde7](https://linux-hardware.org/?probe=f8f954cde7) | Sep 20, 2023 |
| Lenovo        | ThinkPad W540 20BG0014US    | [2d1c5101ea](https://linux-hardware.org/?probe=2d1c5101ea) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [210a1090b3](https://linux-hardware.org/?probe=210a1090b3) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [7678b8a06e](https://linux-hardware.org/?probe=7678b8a06e) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| Valve         | Jupiter                     | [9b95215db5](https://linux-hardware.org/?probe=9b95215db5) | Sep 17, 2023 |
| HP            | Pavilion g6                 | [dd1ade8736](https://linux-hardware.org/?probe=dd1ade8736) | Sep 17, 2023 |
| HP            | Laptop 15-da0xxx            | [43081eb0eb](https://linux-hardware.org/?probe=43081eb0eb) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| Unknown       | Unknown                     | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [9e2d4356b2](https://linux-hardware.org/?probe=9e2d4356b2) | Sep 16, 2023 |
| Google        | Terra                       | [c96e879351](https://linux-hardware.org/?probe=c96e879351) | Sep 15, 2023 |
| Google        | Terra                       | [3f63d76318](https://linux-hardware.org/?probe=3f63d76318) | Sep 14, 2023 |
| Fujitsu       | STYLISTIC Q702              | [f3ca596dc5](https://linux-hardware.org/?probe=f3ca596dc5) | Sep 14, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [5d79965e45](https://linux-hardware.org/?probe=5d79965e45) | Sep 14, 2023 |
| HP            | ProBook 650 G2              | [654bee8844](https://linux-hardware.org/?probe=654bee8844) | Sep 14, 2023 |
| HP            | ProBook 6570b               | [fc5c01d215](https://linux-hardware.org/?probe=fc5c01d215) | Sep 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [9ace0dfae8](https://linux-hardware.org/?probe=9ace0dfae8) | Sep 14, 2023 |
| Valve         | Jupiter                     | [17d891df44](https://linux-hardware.org/?probe=17d891df44) | Sep 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [cb29d8cb77](https://linux-hardware.org/?probe=cb29d8cb77) | Sep 13, 2023 |
| Apple         | MacBookPro11,2              | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Apple         | MacBookPro9,2               | [77db8877eb](https://linux-hardware.org/?probe=77db8877eb) | Sep 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [471faa50e0](https://linux-hardware.org/?probe=471faa50e0) | Sep 12, 2023 |
| Acer          | Swift SF314-512             | [4628c4e630](https://linux-hardware.org/?probe=4628c4e630) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5b93cd5b36](https://linux-hardware.org/?probe=5b93cd5b36) | Sep 11, 2023 |
| Unknown       | Unknown                     | [4944b22636](https://linux-hardware.org/?probe=4944b22636) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d8ac2101a](https://linux-hardware.org/?probe=6d8ac2101a) | Sep 10, 2023 |
| Dell          | Precision 5540              | [061e46a96c](https://linux-hardware.org/?probe=061e46a96c) | Sep 10, 2023 |
| HP            | Laptop 15-fd0xxx            | [470e6325a3](https://linux-hardware.org/?probe=470e6325a3) | Sep 10, 2023 |
| HP            | ProBook 6570b               | [3ed768081c](https://linux-hardware.org/?probe=3ed768081c) | Sep 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [6104b2383d](https://linux-hardware.org/?probe=6104b2383d) | Sep 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [ae24b6af25](https://linux-hardware.org/?probe=ae24b6af25) | Sep 09, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005QU... | [0a57a98442](https://linux-hardware.org/?probe=0a57a98442) | Sep 09, 2023 |
| Dell          | Latitude E6410              | [9b57eaa1eb](https://linux-hardware.org/?probe=9b57eaa1eb) | Sep 09, 2023 |
| MSI           | GP75 Leopard 10SEK          | [11e5581873](https://linux-hardware.org/?probe=11e5581873) | Sep 08, 2023 |
| Dell          | Latitude E6410              | [5371b3f488](https://linux-hardware.org/?probe=5371b3f488) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [0ede91c6cd](https://linux-hardware.org/?probe=0ede91c6cd) | Sep 08, 2023 |
| Apple         | MacBookPro5,5               | [3ab6390052](https://linux-hardware.org/?probe=3ab6390052) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [727b5526f9](https://linux-hardware.org/?probe=727b5526f9) | Sep 08, 2023 |
| ASUSTek       | X541UVK                     | [425b748769](https://linux-hardware.org/?probe=425b748769) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [29c824f7ef](https://linux-hardware.org/?probe=29c824f7ef) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [fd60499219](https://linux-hardware.org/?probe=fd60499219) | Sep 08, 2023 |
| Matsushita... | CF-74JCJBDAM                | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Google        | Blooguard                   | [c9dec98f0f](https://linux-hardware.org/?probe=c9dec98f0f) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [b5f142ae13](https://linux-hardware.org/?probe=b5f142ae13) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [7b717719f5](https://linux-hardware.org/?probe=7b717719f5) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [5728a3a48b](https://linux-hardware.org/?probe=5728a3a48b) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [fdecc11aba](https://linux-hardware.org/?probe=fdecc11aba) | Sep 05, 2023 |
| HP            | Pavilion dv7                | [2d6aa7667d](https://linux-hardware.org/?probe=2d6aa7667d) | Sep 05, 2023 |
| Toshiba       | Satellite C650              | [0b87bf5b4b](https://linux-hardware.org/?probe=0b87bf5b4b) | Sep 05, 2023 |
| HP            | ZBook 15 G2                 | [18d9c74d60](https://linux-hardware.org/?probe=18d9c74d60) | Sep 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [2a53f8dc55](https://linux-hardware.org/?probe=2a53f8dc55) | Sep 04, 2023 |
| Sony          | VPCEB27FX                   | [268d3a14a7](https://linux-hardware.org/?probe=268d3a14a7) | Sep 04, 2023 |
| Acer          | Aspire A515-51              | [91bc08d933](https://linux-hardware.org/?probe=91bc08d933) | Sep 03, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [20be702d65](https://linux-hardware.org/?probe=20be702d65) | Sep 03, 2023 |
| Apple         | MacBookPro8,2               | [8ed88aa6f1](https://linux-hardware.org/?probe=8ed88aa6f1) | Sep 03, 2023 |
| Lenovo        | G570 20079                  | [3e995d059e](https://linux-hardware.org/?probe=3e995d059e) | Sep 03, 2023 |
| Google        | Droid                       | [da26431a82](https://linux-hardware.org/?probe=da26431a82) | Sep 03, 2023 |
| Google        | Droid                       | [278861e9e8](https://linux-hardware.org/?probe=278861e9e8) | Sep 03, 2023 |
| Acer          | Aspire A315-21              | [9c71da2165](https://linux-hardware.org/?probe=9c71da2165) | Sep 03, 2023 |
| HP            | EliteBook 850 G1            | [adacf1a54a](https://linux-hardware.org/?probe=adacf1a54a) | Sep 02, 2023 |
| Dell          | Precision 5540              | [3d800b12e0](https://linux-hardware.org/?probe=3d800b12e0) | Sep 02, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [affa07b412](https://linux-hardware.org/?probe=affa07b412) | Sep 02, 2023 |
| Lenovo        | ThinkPad W510 438923U       | [b0648eccac](https://linux-hardware.org/?probe=b0648eccac) | Sep 02, 2023 |
| HP            | ProBook 650 G2              | [a00c4f0a62](https://linux-hardware.org/?probe=a00c4f0a62) | Sep 02, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [28fc3470c8](https://linux-hardware.org/?probe=28fc3470c8) | Sep 01, 2023 |
| Acer          | Aspire E5-571               | [04f5152e0c](https://linux-hardware.org/?probe=04f5152e0c) | Sep 01, 2023 |
| MOTION        | NVX00                       | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| MSI           | MS-7E06                     | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| Dell          | Latitude 3510               | [220b298103](https://linux-hardware.org/?probe=220b298103) | Aug 30, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| MSI           | GP72 7RDX                   | [071785ab97](https://linux-hardware.org/?probe=071785ab97) | Aug 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [958ecd81e5](https://linux-hardware.org/?probe=958ecd81e5) | Aug 30, 2023 |
| Apple         | MacBookPro8,1               | [2e3c70287a](https://linux-hardware.org/?probe=2e3c70287a) | Aug 30, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Acer          | Swift SF314-512             | [a41a08d4ae](https://linux-hardware.org/?probe=a41a08d4ae) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [62ff88eaf7](https://linux-hardware.org/?probe=62ff88eaf7) | Aug 29, 2023 |
| Acer          | Aspire 5742                 | [9bbb56c640](https://linux-hardware.org/?probe=9bbb56c640) | Aug 29, 2023 |
| System76      | Galago Pro                  | [31330746e6](https://linux-hardware.org/?probe=31330746e6) | Aug 29, 2023 |
| Toshiba       | Satellite Pro C70-C         | [eb9fbb104c](https://linux-hardware.org/?probe=eb9fbb104c) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [e165507af8](https://linux-hardware.org/?probe=e165507af8) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [329d960437](https://linux-hardware.org/?probe=329d960437) | Aug 27, 2023 |
| Apple         | MacBookPro9,1               | [20eda7fab5](https://linux-hardware.org/?probe=20eda7fab5) | Aug 26, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | [46a647db9b](https://linux-hardware.org/?probe=46a647db9b) | Aug 26, 2023 |
| Dell          | Precision M4600             | [fcc3763c08](https://linux-hardware.org/?probe=fcc3763c08) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 25222AU       | [fdc78cf5a0](https://linux-hardware.org/?probe=fdc78cf5a0) | Aug 26, 2023 |
| HP            | Laptop 17-ca2xxx            | [f6d894d339](https://linux-hardware.org/?probe=f6d894d339) | Aug 26, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3c528e98c6](https://linux-hardware.org/?probe=3c528e98c6) | Aug 26, 2023 |
| Lenovo        | V15-IIL 82C5                | [cee65701f2](https://linux-hardware.org/?probe=cee65701f2) | Aug 25, 2023 |
| Dell          | Inspiron 5585               | [49a9e7dbf0](https://linux-hardware.org/?probe=49a9e7dbf0) | Aug 25, 2023 |
| Acer          | Aspire 5742                 | [7d896ad750](https://linux-hardware.org/?probe=7d896ad750) | Aug 24, 2023 |
| System76      | Gazelle                     | [ee67365e0c](https://linux-hardware.org/?probe=ee67365e0c) | Aug 24, 2023 |
| Dell          | Latitude 5510               | [d0b9ab746d](https://linux-hardware.org/?probe=d0b9ab746d) | Aug 24, 2023 |
| Lenovo        | ThinkPad T450s 20BWS2M30... | [052c7eaa90](https://linux-hardware.org/?probe=052c7eaa90) | Aug 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [2431197665](https://linux-hardware.org/?probe=2431197665) | Aug 24, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | [2281d96afb](https://linux-hardware.org/?probe=2281d96afb) | Aug 24, 2023 |
| Xplore        | iX104C6                     | [5d8ea1a454](https://linux-hardware.org/?probe=5d8ea1a454) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| HP            | EliteBook 8530w             | [3ee1fe77ce](https://linux-hardware.org/?probe=3ee1fe77ce) | Aug 23, 2023 |
| MSI           | GP72 6QF                    | [3afc91a639](https://linux-hardware.org/?probe=3afc91a639) | Aug 23, 2023 |
| HP            | Presario V2000 (ES307UA#... | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| ASUSTek       | G751JM                      | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| HP            | EliteBook 2170p             | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| Dell          | Latitude 5510               | [e5d8770a77](https://linux-hardware.org/?probe=e5d8770a77) | Aug 21, 2023 |
| Lenovo        | ThinkPad X220 42902WU       | [9fd887dc27](https://linux-hardware.org/?probe=9fd887dc27) | Aug 21, 2023 |
| Toshiba       | Satellite Pro A50-C         | [ed71bba366](https://linux-hardware.org/?probe=ed71bba366) | Aug 19, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [030cbe1086](https://linux-hardware.org/?probe=030cbe1086) | Aug 19, 2023 |
| HP            | Pavilion g6                 | [8e7844a79d](https://linux-hardware.org/?probe=8e7844a79d) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Panasonic     | CF-31AQAAA1M                | [64416dbba5](https://linux-hardware.org/?probe=64416dbba5) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | [31447ef238](https://linux-hardware.org/?probe=31447ef238) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | [8c57c50f82](https://linux-hardware.org/?probe=8c57c50f82) | Aug 17, 2023 |
| Dell          | Precision 5540              | [a0a36884a0](https://linux-hardware.org/?probe=a0a36884a0) | Aug 17, 2023 |
| Dell          | Inspiron 1200               | [2340dcab47](https://linux-hardware.org/?probe=2340dcab47) | Aug 17, 2023 |
| Dell          | XPS 9320                    | [cb112d9f03](https://linux-hardware.org/?probe=cb112d9f03) | Aug 17, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | [a69ad2f7b8](https://linux-hardware.org/?probe=a69ad2f7b8) | Aug 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [2ac8f6838a](https://linux-hardware.org/?probe=2ac8f6838a) | Aug 15, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [65f7a020fe](https://linux-hardware.org/?probe=65f7a020fe) | Aug 14, 2023 |
| Dell          | XPS 13 9360                 | [69b51e3f5a](https://linux-hardware.org/?probe=69b51e3f5a) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [24b85b3417](https://linux-hardware.org/?probe=24b85b3417) | Aug 14, 2023 |
| Google        | Blooglet                    | [b9967e65c2](https://linux-hardware.org/?probe=b9967e65c2) | Aug 14, 2023 |
| HP            | ProBook 650 G2              | [b310a70636](https://linux-hardware.org/?probe=b310a70636) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Apple         | MacBookAir6,2               | [4eeea4cc95](https://linux-hardware.org/?probe=4eeea4cc95) | Aug 13, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| Unknown       | Unknown                     | [21abd7288e](https://linux-hardware.org/?probe=21abd7288e) | Aug 12, 2023 |
| HP            | Notebook                    | [de8a0230c4](https://linux-hardware.org/?probe=de8a0230c4) | Aug 11, 2023 |
| HP            | EliteBook 840 G1            | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| HP            | EliteBook 2560p             | [0b5cf409d8](https://linux-hardware.org/?probe=0b5cf409d8) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Google        | Bobba360                    | [128700115a](https://linux-hardware.org/?probe=128700115a) | Aug 10, 2023 |
| Dell          | Latitude 3540               | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| Google        | Snappy                      | [73ecdd5048](https://linux-hardware.org/?probe=73ecdd5048) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [75b55100a9](https://linux-hardware.org/?probe=75b55100a9) | Aug 10, 2023 |
| Dell          | Precision 5540              | [e68fee1e24](https://linux-hardware.org/?probe=e68fee1e24) | Aug 10, 2023 |
| Gateway       | NV57H                       | [826aaf5dd8](https://linux-hardware.org/?probe=826aaf5dd8) | Aug 10, 2023 |
| HP            | ProBook 650 G2              | [8fbbf1483d](https://linux-hardware.org/?probe=8fbbf1483d) | Aug 09, 2023 |
| Google        | Bobba360                    | [fa4a78b024](https://linux-hardware.org/?probe=fa4a78b024) | Aug 09, 2023 |
| System76      | Darter Pro                  | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| Dell          | Latitude 3350               | [77100b2ef6](https://linux-hardware.org/?probe=77100b2ef6) | Aug 09, 2023 |
| HP            | ProBook 650 G2              | [78859b39fb](https://linux-hardware.org/?probe=78859b39fb) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [f48f680274](https://linux-hardware.org/?probe=f48f680274) | Aug 08, 2023 |
| Dell          | Latitude E5470              | [f64529e38b](https://linux-hardware.org/?probe=f64529e38b) | Aug 08, 2023 |
| HP            | Laptop 14-dq3xxx            | [c547f01fbb](https://linux-hardware.org/?probe=c547f01fbb) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| Dell          | Latitude 7300               | [932f04033c](https://linux-hardware.org/?probe=932f04033c) | Aug 07, 2023 |
| HP            | Laptop 15-dy2xxx            | [5777798e8f](https://linux-hardware.org/?probe=5777798e8f) | Aug 07, 2023 |
| Acer          | E1-510                      | [2d6776c4fe](https://linux-hardware.org/?probe=2d6776c4fe) | Aug 06, 2023 |
| HP            | EliteBook 840 G5            | [9688966097](https://linux-hardware.org/?probe=9688966097) | Aug 06, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [bd989967e7](https://linux-hardware.org/?probe=bd989967e7) | Aug 06, 2023 |
| Dell          | Inspiron 15 3525            | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| Apple         | MacBookPro14,1              | [d3630fa2ed](https://linux-hardware.org/?probe=d3630fa2ed) | Aug 05, 2023 |
| Lenovo        | ThinkPad X131e 33671S2      | [3f83b5efac](https://linux-hardware.org/?probe=3f83b5efac) | Aug 05, 2023 |
| Corsair       | Voyager a1600               | [6dea5f2c0c](https://linux-hardware.org/?probe=6dea5f2c0c) | Aug 04, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [ff55512c0e](https://linux-hardware.org/?probe=ff55512c0e) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| HP            | Laptop 15-fd0xxx            | [8f3b8dea26](https://linux-hardware.org/?probe=8f3b8dea26) | Aug 04, 2023 |
| HP            | EliteBook Folio G1          | [b9bb38ddd4](https://linux-hardware.org/?probe=b9bb38ddd4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [7d86876920](https://linux-hardware.org/?probe=7d86876920) | Aug 03, 2023 |
| Dell          | Latitude 5440               | [5791d15bc8](https://linux-hardware.org/?probe=5791d15bc8) | Aug 02, 2023 |
| Dell          | Latitude 5540               | [e521b93e2f](https://linux-hardware.org/?probe=e521b93e2f) | Aug 02, 2023 |
| Dell          | Latitude 5440               | [5b0eb512d1](https://linux-hardware.org/?probe=5b0eb512d1) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [944afe5083](https://linux-hardware.org/?probe=944afe5083) | Aug 02, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [74f1782ead](https://linux-hardware.org/?probe=74f1782ead) | Aug 02, 2023 |
| Acer          | Aspire E1-532               | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Valve         | Jupiter                     | [896569d1d6](https://linux-hardware.org/?probe=896569d1d6) | Aug 01, 2023 |
| ASUSTek       | X751LA                      | [928a69b9af](https://linux-hardware.org/?probe=928a69b9af) | Aug 01, 2023 |
| Lenovo        | 3000 C100 07612GU           | [3941ecc4f2](https://linux-hardware.org/?probe=3941ecc4f2) | Aug 01, 2023 |
| HP            | ProBook 445 G7              | [96e95e4bd2](https://linux-hardware.org/?probe=96e95e4bd2) | Jul 31, 2023 |
| HP            | EliteBook 840 G2            | [067b112fb8](https://linux-hardware.org/?probe=067b112fb8) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0DT0... | [bd0d0f2888](https://linux-hardware.org/?probe=bd0d0f2888) | Jul 30, 2023 |
| HP            | ProBook 4540s               | [0fae07b574](https://linux-hardware.org/?probe=0fae07b574) | Jul 30, 2023 |
| Dell          | XPS 15 7590                 | [4f2f49a6b2](https://linux-hardware.org/?probe=4f2f49a6b2) | Jul 30, 2023 |
| BOSGAME       | U56                         | [39d52e51f5](https://linux-hardware.org/?probe=39d52e51f5) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | [c3101b6a76](https://linux-hardware.org/?probe=c3101b6a76) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | [915938d446](https://linux-hardware.org/?probe=915938d446) | Jul 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [74a7a53f6a](https://linux-hardware.org/?probe=74a7a53f6a) | Jul 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [cd073a7899](https://linux-hardware.org/?probe=cd073a7899) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e62cce964c](https://linux-hardware.org/?probe=e62cce964c) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Dell          | Latitude 5520               | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Acer          | Aspire 5810T                | [2d141d703d](https://linux-hardware.org/?probe=2d141d703d) | Jul 28, 2023 |
| MSI           | Katana GF66 11UE            | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Alienware     | m17 R4                      | [eece2da9ed](https://linux-hardware.org/?probe=eece2da9ed) | Jul 27, 2023 |
| Acer          | Aspire 5810T                | [9b7b328324](https://linux-hardware.org/?probe=9b7b328324) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| HP            | ProBook 4540s               | [f41d6c4f4b](https://linux-hardware.org/?probe=f41d6c4f4b) | Jul 26, 2023 |
| HP            | G60                         | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [3cb74490f6](https://linux-hardware.org/?probe=3cb74490f6) | Jul 25, 2023 |
| Google        | Droid                       | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [5c4b165cea](https://linux-hardware.org/?probe=5c4b165cea) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [4ad8be01ca](https://linux-hardware.org/?probe=4ad8be01ca) | Jul 25, 2023 |
| Lenovo        | ThinkPad T430 2347H91       | [0ed3c4bc6a](https://linux-hardware.org/?probe=0ed3c4bc6a) | Jul 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [5c52eecd16](https://linux-hardware.org/?probe=5c52eecd16) | Jul 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [562e6e1026](https://linux-hardware.org/?probe=562e6e1026) | Jul 25, 2023 |
| Dell          | Latitude 7490               | [066e3b9518](https://linux-hardware.org/?probe=066e3b9518) | Jul 25, 2023 |
| Lenovo        | ThinkPad T420s 417152U      | [22e09689b0](https://linux-hardware.org/?probe=22e09689b0) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Lenovo        | ThinkPad P53 20QN004BCA     | [04a2ed4bd2](https://linux-hardware.org/?probe=04a2ed4bd2) | Jul 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [1ee910fc1c](https://linux-hardware.org/?probe=1ee910fc1c) | Jul 22, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [d02b0e9f74](https://linux-hardware.org/?probe=d02b0e9f74) | Jul 22, 2023 |
| Gateway       | NV57H                       | [3209dcf267](https://linux-hardware.org/?probe=3209dcf267) | Jul 22, 2023 |
| Gateway       | NV57H                       | [35dac8980f](https://linux-hardware.org/?probe=35dac8980f) | Jul 22, 2023 |
| HP            | Pavilion dv7                | [a74719eac2](https://linux-hardware.org/?probe=a74719eac2) | Jul 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [27b5dabe8d](https://linux-hardware.org/?probe=27b5dabe8d) | Jul 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fb09f582c5](https://linux-hardware.org/?probe=fb09f582c5) | Jul 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2fcc9e6028](https://linux-hardware.org/?probe=2fcc9e6028) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0C800     | [b894a6d96b](https://linux-hardware.org/?probe=b894a6d96b) | Jul 19, 2023 |
| ASUSTek       | GL502VM                     | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Apple         | MacBookPro11,2              | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [efd490f52d](https://linux-hardware.org/?probe=efd490f52d) | Jul 18, 2023 |
| HP            | Pavilion Notebook           | [babb224527](https://linux-hardware.org/?probe=babb224527) | Jul 18, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | [574cd2e0f8](https://linux-hardware.org/?probe=574cd2e0f8) | Jul 17, 2023 |
| Google        | Phaser360                   | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| System76      | Serval WS                   | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | X751LA                      | [345fab37ab](https://linux-hardware.org/?probe=345fab37ab) | Jul 17, 2023 |
| Dell          | Latitude E6420              | [7006e50178](https://linux-hardware.org/?probe=7006e50178) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| HP            | Pavilion dv7                | [e983b50085](https://linux-hardware.org/?probe=e983b50085) | Jul 15, 2023 |
| System76      | Pangolin                    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Dell          | Precision 5480              | [57d3fff688](https://linux-hardware.org/?probe=57d3fff688) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| Panasonic     | CF-S10CDHEDM                | [55204a29c3](https://linux-hardware.org/?probe=55204a29c3) | Jul 12, 2023 |
| MSI           | GF65 Thin 10UE              | [414c5bc2c0](https://linux-hardware.org/?probe=414c5bc2c0) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | [27df8fc0e5](https://linux-hardware.org/?probe=27df8fc0e5) | Jul 11, 2023 |
| Dell          | Latitude E5540              | [cdad6cb751](https://linux-hardware.org/?probe=cdad6cb751) | Jul 11, 2023 |
| Lenovo        | IdeaPad Z570 10249UU        | [4179167c95](https://linux-hardware.org/?probe=4179167c95) | Jul 11, 2023 |
| MSI           | GF65 Thin 10UE              | [d73ac20739](https://linux-hardware.org/?probe=d73ac20739) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [beef3128c2](https://linux-hardware.org/?probe=beef3128c2) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [cf25605b3a](https://linux-hardware.org/?probe=cf25605b3a) | Jul 10, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [7d5e51d9a8](https://linux-hardware.org/?probe=7d5e51d9a8) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [3c3c2ac038](https://linux-hardware.org/?probe=3c3c2ac038) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [8dd1516457](https://linux-hardware.org/?probe=8dd1516457) | Jul 08, 2023 |
| Dell          | Latitude 5540               | [1bd623d7b0](https://linux-hardware.org/?probe=1bd623d7b0) | Jul 07, 2023 |
| Acer          | Nitro AN515-57              | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| Lenovo        | ThinkPad T510 4349RK6       | [e25d3f6783](https://linux-hardware.org/?probe=e25d3f6783) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Dell          | Latitude 3540               | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| ASUSTek       | GL703VD                     | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| Framework     | Laptop                      | [ea4c4585d0](https://linux-hardware.org/?probe=ea4c4585d0) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| ASUSTek       | TP501UA                     | [ee28aacdd1](https://linux-hardware.org/?probe=ee28aacdd1) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| HP            | Pavilion dv7                | [09627980f5](https://linux-hardware.org/?probe=09627980f5) | Jul 04, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [9ec1de725f](https://linux-hardware.org/?probe=9ec1de725f) | Jul 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [5d1b3596c1](https://linux-hardware.org/?probe=5d1b3596c1) | Jul 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [3290dd955a](https://linux-hardware.org/?probe=3290dd955a) | Jul 03, 2023 |
| Toshiba       | TECRA R950                  | [77a720dc31](https://linux-hardware.org/?probe=77a720dc31) | Jul 03, 2023 |
| MSI           | GT72VR 6RD                  | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [585ee2564e](https://linux-hardware.org/?probe=585ee2564e) | Jul 01, 2023 |
| HP            | ENVY m6                     | [b4f8d19895](https://linux-hardware.org/?probe=b4f8d19895) | Jun 30, 2023 |
| Dell          | Latitude E5440              | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| Samsung       | R430/R480                   | [485a09a0d2](https://linux-hardware.org/?probe=485a09a0d2) | Jun 30, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [c7e71c8c0b](https://linux-hardware.org/?probe=c7e71c8c0b) | Jun 29, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [0c3b48af38](https://linux-hardware.org/?probe=0c3b48af38) | Jun 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS0DL00    | [5d27a44710](https://linux-hardware.org/?probe=5d27a44710) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | [92a71d25d7](https://linux-hardware.org/?probe=92a71d25d7) | Jun 28, 2023 |
| Dell          | Latitude 3500               | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| Sony          | VPCEB37FD                   | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| MSI           | GP72 7RDX                   | [d61ba42fcf](https://linux-hardware.org/?probe=d61ba42fcf) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Gateway       | NV57H                       | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Gateway       | NV57H                       | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [d34d125de2](https://linux-hardware.org/?probe=d34d125de2) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [1858ae62ee](https://linux-hardware.org/?probe=1858ae62ee) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [501d3b5530](https://linux-hardware.org/?probe=501d3b5530) | Jun 25, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [68117675ab](https://linux-hardware.org/?probe=68117675ab) | Jun 25, 2023 |
| ASUSTek       | E403SA                      | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| Dell          | Inspiron 15-3567            | [614687bba4](https://linux-hardware.org/?probe=614687bba4) | Jun 25, 2023 |
| Xplore        | iX104C6                     | [23bb4c656b](https://linux-hardware.org/?probe=23bb4c656b) | Jun 24, 2023 |
| Dell          | XPS 13 9370                 | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| HP            | ProBook 450 G2              | [60babdeb16](https://linux-hardware.org/?probe=60babdeb16) | Jun 21, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [caaf6ce403](https://linux-hardware.org/?probe=caaf6ce403) | Jun 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e5db90d1b4](https://linux-hardware.org/?probe=e5db90d1b4) | Jun 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [f38684c33d](https://linux-hardware.org/?probe=f38684c33d) | Jun 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [e3ded6b5e4](https://linux-hardware.org/?probe=e3ded6b5e4) | Jun 19, 2023 |
| Apple         | MacBookPro8,1               | [70d76362e2](https://linux-hardware.org/?probe=70d76362e2) | Jun 19, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [125b4fefa5](https://linux-hardware.org/?probe=125b4fefa5) | Jun 19, 2023 |
| Dell          | System XPS L502X            | [463e017820](https://linux-hardware.org/?probe=463e017820) | Jun 19, 2023 |
| Lenovo        | ThinkPad E590 20NB001JUS    | [5fb441bf83](https://linux-hardware.org/?probe=5fb441bf83) | Jun 18, 2023 |
| Acer          | Aspire A315-22              | [f977b4851c](https://linux-hardware.org/?probe=f977b4851c) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| HP            | Pavilion dv7                | [166b70ddad](https://linux-hardware.org/?probe=166b70ddad) | Jun 18, 2023 |
| ASUSTek       | X553MA                      | [ef0c9e5597](https://linux-hardware.org/?probe=ef0c9e5597) | Jun 18, 2023 |
| Google        | Kefka                       | [86421e3d29](https://linux-hardware.org/?probe=86421e3d29) | Jun 18, 2023 |
| Valve         | Jupiter                     | [9da2af6fe5](https://linux-hardware.org/?probe=9da2af6fe5) | Jun 18, 2023 |
| HP            | ProBook 445 G7              | [71c3b52599](https://linux-hardware.org/?probe=71c3b52599) | Jun 17, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [d415965e91](https://linux-hardware.org/?probe=d415965e91) | Jun 17, 2023 |
| Dell          | Latitude E6400              | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [268b733c44](https://linux-hardware.org/?probe=268b733c44) | Jun 16, 2023 |
| Acer          | Aspire V3-572P              | [49302da0a9](https://linux-hardware.org/?probe=49302da0a9) | Jun 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [3b552a7f4a](https://linux-hardware.org/?probe=3b552a7f4a) | Jun 15, 2023 |
| Apple         | MacBookPro7,1               | [ae4444566b](https://linux-hardware.org/?probe=ae4444566b) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| MSI           | GE62 2QF                    | [aabf8f661a](https://linux-hardware.org/?probe=aabf8f661a) | Jun 14, 2023 |
| Acer          | Aspire 5733                 | [6291133649](https://linux-hardware.org/?probe=6291133649) | Jun 13, 2023 |
| Acer          | Aspire V3-572P              | [12f6b82789](https://linux-hardware.org/?probe=12f6b82789) | Jun 13, 2023 |
| Apple         | MacBookPro5,5               | [b303846ade](https://linux-hardware.org/?probe=b303846ade) | Jun 13, 2023 |
| Apple         | MacBookPro7,1               | [c1f5bf2148](https://linux-hardware.org/?probe=c1f5bf2148) | Jun 13, 2023 |
| Dell          | XPS 15 9560                 | [ca84981180](https://linux-hardware.org/?probe=ca84981180) | Jun 12, 2023 |
| Fujitsu       | T900                        | [4716750f3f](https://linux-hardware.org/?probe=4716750f3f) | Jun 12, 2023 |
| Apple         | MacBookPro5,5               | [cba5fb51f8](https://linux-hardware.org/?probe=cba5fb51f8) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| Dell          | XPS 13 9310                 | [740fb14b2f](https://linux-hardware.org/?probe=740fb14b2f) | Jun 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1a36e2fa98](https://linux-hardware.org/?probe=1a36e2fa98) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| Sony          | VPCEB2AFD                   | [1d9d6ddd74](https://linux-hardware.org/?probe=1d9d6ddd74) | Jun 09, 2023 |
| Panasonic     | CF-S10CDHEDM                | [19b6085754](https://linux-hardware.org/?probe=19b6085754) | Jun 09, 2023 |
| Apple         | MacBookPro5,5               | [09344fa63e](https://linux-hardware.org/?probe=09344fa63e) | Jun 09, 2023 |
| Dell          | Inspiron 5505               | [05973f7d9b](https://linux-hardware.org/?probe=05973f7d9b) | Jun 08, 2023 |
| Dell          | Inspiron 5547               | [7775c4c871](https://linux-hardware.org/?probe=7775c4c871) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | [3a43778152](https://linux-hardware.org/?probe=3a43778152) | Jun 07, 2023 |
| Lenovo        | ThinkPad W520 4282AB9       | [790550e99f](https://linux-hardware.org/?probe=790550e99f) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| Valve         | Jupiter                     | [aa2925f22f](https://linux-hardware.org/?probe=aa2925f22f) | Jun 05, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0DR0... | [6fad1535c3](https://linux-hardware.org/?probe=6fad1535c3) | Jun 04, 2023 |
| Dell          | Precision 5540              | [f9f2304792](https://linux-hardware.org/?probe=f9f2304792) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [29c4ba7312](https://linux-hardware.org/?probe=29c4ba7312) | Jun 01, 2023 |
| HP            | ZBook 15 G3                 | [28eec89b69](https://linux-hardware.org/?probe=28eec89b69) | Jun 01, 2023 |
| Lenovo        | ThinkPad W510 4391B49       | [1e1004a387](https://linux-hardware.org/?probe=1e1004a387) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Latitude E5540              | [83d7c0065d](https://linux-hardware.org/?probe=83d7c0065d) | Jun 01, 2023 |
| Apple         | MacBookPro9,1               | [0b958e0c5c](https://linux-hardware.org/?probe=0b958e0c5c) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| MSI           | GF65 Thin 10UE              | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Dell          | Latitude E6530              | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| Dell          | Latitude E6530              | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| Acer          | Aspire E1-572               | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Acer          | Aspire A315-41              | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [22cbc01649](https://linux-hardware.org/?probe=22cbc01649) | May 28, 2023 |
| Apple         | MacBookPro16,2              | [993b013d0a](https://linux-hardware.org/?probe=993b013d0a) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Dell          | Latitude E6330              | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| Acer          | Aspire ES1-523              | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Dell          | Latitude E6330              | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Apple         | MacBookPro5,5               | [f1b7ea69ea](https://linux-hardware.org/?probe=f1b7ea69ea) | May 27, 2023 |
| Lenovo        | Unknown                     | [dbf5c576b2](https://linux-hardware.org/?probe=dbf5c576b2) | May 27, 2023 |
| Samsung       | 910S3G/910S3T               | [e041a5365e](https://linux-hardware.org/?probe=e041a5365e) | May 26, 2023 |
| Acer          | Aspire A315-42              | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| Acer          | Aspire V3-551               | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Valve         | Jupiter                     | [84756c6406](https://linux-hardware.org/?probe=84756c6406) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Apple         | MacBookAir4,1               | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| Alienware     | 17 R3                       | [a567b379a1](https://linux-hardware.org/?probe=a567b379a1) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| HP            | EliteBook 8570w             | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| Lenovo        | ThinkPad T540p 20BF001NU... | [2a770d2eac](https://linux-hardware.org/?probe=2a770d2eac) | May 23, 2023 |
| Apple         | MacBookPro5,5               | [7978c97691](https://linux-hardware.org/?probe=7978c97691) | May 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
| Sony          | VPCF120FD                   | [a438459d06](https://linux-hardware.org/?probe=a438459d06) | May 21, 2023 |
| ASUSTek       | UX430UAR                    | [7815f47a45](https://linux-hardware.org/?probe=7815f47a45) | May 21, 2023 |
| HP            | EliteBook 840 G5            | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| BOSGAME       | B95                         | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| HP            | HDX18                       | [fbfe87f9b5](https://linux-hardware.org/?probe=fbfe87f9b5) | May 19, 2023 |
| HP            | HDX18                       | [a0d050763b](https://linux-hardware.org/?probe=a0d050763b) | May 19, 2023 |
| Acer          | Swift SF316-51              | [663e7fe745](https://linux-hardware.org/?probe=663e7fe745) | May 17, 2023 |
| Dell          | Precision 5540              | [a97a05dd0e](https://linux-hardware.org/?probe=a97a05dd0e) | May 16, 2023 |
| HP            | ProBook 450 G2              | [a399b17822](https://linux-hardware.org/?probe=a399b17822) | May 16, 2023 |
| HP            | EliteBook 8760w             | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| HP            | ProBook 450 G2              | [2ab0709f22](https://linux-hardware.org/?probe=2ab0709f22) | May 14, 2023 |
| Dell          | Precision 5540              | [22e1b4dbd4](https://linux-hardware.org/?probe=22e1b4dbd4) | May 14, 2023 |
| Dell          | Latitude 5490               | [57e94dd4b7](https://linux-hardware.org/?probe=57e94dd4b7) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5ce272e9ee](https://linux-hardware.org/?probe=5ce272e9ee) | May 13, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [79db0c9b3c](https://linux-hardware.org/?probe=79db0c9b3c) | May 13, 2023 |
| Acer          | Aspire E1-570               | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Google        | Kled                        | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Panasonic     | CF-19-8                     | [1aa7d4071a](https://linux-hardware.org/?probe=1aa7d4071a) | May 12, 2023 |
| System76      | Gazelle                     | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| Samsung       | R430/R480                   | [076f13d198](https://linux-hardware.org/?probe=076f13d198) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c590339049](https://linux-hardware.org/?probe=c590339049) | May 12, 2023 |
| Valve         | Jupiter                     | [9d7e434968](https://linux-hardware.org/?probe=9d7e434968) | May 12, 2023 |
| HP            | Laptop 17-by2xxx            | [21faeddba9](https://linux-hardware.org/?probe=21faeddba9) | May 10, 2023 |
| Google        | Edgar                       | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Valve         | Jupiter                     | [8cc543c6af](https://linux-hardware.org/?probe=8cc543c6af) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| ASUSTek       | K53TK                       | [baf643f95f](https://linux-hardware.org/?probe=baf643f95f) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [69dfa20c09](https://linux-hardware.org/?probe=69dfa20c09) | May 07, 2023 |
| Dell          | Inspiron 5521               | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| HP            | Pavilion dv6                | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| HP            | ENVY TS 17                  | [d18f9c3e77](https://linux-hardware.org/?probe=d18f9c3e77) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [620d5955bb](https://linux-hardware.org/?probe=620d5955bb) | May 06, 2023 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [21ef45e81c](https://linux-hardware.org/?probe=21ef45e81c) | May 06, 2023 |
| HP            | Pavilion 15                 | [308afd60ea](https://linux-hardware.org/?probe=308afd60ea) | May 06, 2023 |
| HP            | Pavilion 15                 | [2f59970cf9](https://linux-hardware.org/?probe=2f59970cf9) | May 05, 2023 |
| Dell          | Latitude 5401               | [671e11d184](https://linux-hardware.org/?probe=671e11d184) | May 05, 2023 |
| Dell          | Latitude E6520              | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [72336867ab](https://linux-hardware.org/?probe=72336867ab) | May 04, 2023 |
| Lenovo        | G505s 20255                 | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Dell          | XPS 15 9560                 | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [1c26fc22d1](https://linux-hardware.org/?probe=1c26fc22d1) | May 04, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| Acer          | Aspire E1-570               | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| Google        | Kip                         | [19b726ec68](https://linux-hardware.org/?probe=19b726ec68) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| Dell          | XPS 15 9570                 | [5b8daf89b4](https://linux-hardware.org/?probe=5b8daf89b4) | May 01, 2023 |
| Dell          | XPS 15 9570                 | [0f39841ca1](https://linux-hardware.org/?probe=0f39841ca1) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1605338d8f](https://linux-hardware.org/?probe=1605338d8f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [3695c070f9](https://linux-hardware.org/?probe=3695c070f9) | Apr 30, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [2545d9dd31](https://linux-hardware.org/?probe=2545d9dd31) | Apr 29, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [59b9a9ceb3](https://linux-hardware.org/?probe=59b9a9ceb3) | Apr 29, 2023 |
| HP            | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [346cbe0e48](https://linux-hardware.org/?probe=346cbe0e48) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [afafdbce36](https://linux-hardware.org/?probe=afafdbce36) | Apr 28, 2023 |
| HP            | EliteBook 2560p             | [ce35b62e32](https://linux-hardware.org/?probe=ce35b62e32) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [96006a1098](https://linux-hardware.org/?probe=96006a1098) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3df65a55c](https://linux-hardware.org/?probe=a3df65a55c) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| HP            | Pavilion dv7                | [e8318168c4](https://linux-hardware.org/?probe=e8318168c4) | Apr 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [cc14ce03b0](https://linux-hardware.org/?probe=cc14ce03b0) | Apr 25, 2023 |
| Dell          | Latitude E7240              | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| HP            | Pavilion dv7                | [0ca422761e](https://linux-hardware.org/?probe=0ca422761e) | Apr 23, 2023 |
| HP            | Pavilion dv7                | [8b90982317](https://linux-hardware.org/?probe=8b90982317) | Apr 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [db614f561e](https://linux-hardware.org/?probe=db614f561e) | Apr 23, 2023 |
| ASUSTek       | X510UAR                     | [3321ccb912](https://linux-hardware.org/?probe=3321ccb912) | Apr 23, 2023 |
| Google        | Kefka                       | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [f2f6b7ab4e](https://linux-hardware.org/?probe=f2f6b7ab4e) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| Dell          | Latitude E6420              | [6b5cc099a0](https://linux-hardware.org/?probe=6b5cc099a0) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Pavilion dv7                | [f5c84d7a1b](https://linux-hardware.org/?probe=f5c84d7a1b) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | [ce824f113c](https://linux-hardware.org/?probe=ce824f113c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | [7611d6e018](https://linux-hardware.org/?probe=7611d6e018) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Acer          | Nitro AN515-54              | [7b3a68ca48](https://linux-hardware.org/?probe=7b3a68ca48) | Apr 18, 2023 |
| MSI           | GF75 Thin 9SC               | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [f8a45caf43](https://linux-hardware.org/?probe=f8a45caf43) | Apr 17, 2023 |
| Toshiba       | Satellite L850              | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| Dell          | Latitude E6430s             | [5358f67a6d](https://linux-hardware.org/?probe=5358f67a6d) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [afc478cf27](https://linux-hardware.org/?probe=afc478cf27) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [872416fe62](https://linux-hardware.org/?probe=872416fe62) | Apr 16, 2023 |
| MSI           | Modern 14 B10MW             | [c655afe860](https://linux-hardware.org/?probe=c655afe860) | Apr 15, 2023 |
| HP            | EliteBook 8440p             | [f3b7c9c255](https://linux-hardware.org/?probe=f3b7c9c255) | Apr 14, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Dell          | Latitude E6420              | [7cf2e649e1](https://linux-hardware.org/?probe=7cf2e649e1) | Apr 14, 2023 |
| MSI           | GP72 7RDX                   | [2236248ba0](https://linux-hardware.org/?probe=2236248ba0) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [d4de10f812](https://linux-hardware.org/?probe=d4de10f812) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7c862e338c](https://linux-hardware.org/?probe=7c862e338c) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | Latitude 3590               | [eed6f4df10](https://linux-hardware.org/?probe=eed6f4df10) | Apr 14, 2023 |
| Toshiba       | Satellite L300D             | [76595cf176](https://linux-hardware.org/?probe=76595cf176) | Apr 12, 2023 |
| Dell          | Latitude 7390               | [9859e63f40](https://linux-hardware.org/?probe=9859e63f40) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a2c9f95f36](https://linux-hardware.org/?probe=a2c9f95f36) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [26358515bc](https://linux-hardware.org/?probe=26358515bc) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [509dbf780c](https://linux-hardware.org/?probe=509dbf780c) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| Gateway       | NE56R                       | [39a33d998b](https://linux-hardware.org/?probe=39a33d998b) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| Dell          | Latitude 7390               | [5c446957c5](https://linux-hardware.org/?probe=5c446957c5) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [7cec7666c8](https://linux-hardware.org/?probe=7cec7666c8) | Apr 11, 2023 |
| HP            | Pavilion dv7                | [e3583c2121](https://linux-hardware.org/?probe=e3583c2121) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Lenovo        | B575 1450ABU                | [ef58d2e8e6](https://linux-hardware.org/?probe=ef58d2e8e6) | Apr 09, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [fa54308baa](https://linux-hardware.org/?probe=fa54308baa) | Apr 09, 2023 |
| Acer          | Predator PH315-54           | [edbc0b98a4](https://linux-hardware.org/?probe=edbc0b98a4) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| HP            | EliteBook 840 G5            | [0d68e199a9](https://linux-hardware.org/?probe=0d68e199a9) | Apr 05, 2023 |
| Dell          | Precision 7670              | [b5e95f0d21](https://linux-hardware.org/?probe=b5e95f0d21) | Apr 05, 2023 |
| Dell          | Latitude 7490               | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Apple         | MacBookPro5,5               | [c674243118](https://linux-hardware.org/?probe=c674243118) | Apr 03, 2023 |
| Apple         | MacBookPro5,5               | [dca6973952](https://linux-hardware.org/?probe=dca6973952) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0b97a5a77a](https://linux-hardware.org/?probe=0b97a5a77a) | Apr 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7355f06eb3](https://linux-hardware.org/?probe=7355f06eb3) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [dabe76e4ca](https://linux-hardware.org/?probe=dabe76e4ca) | Apr 01, 2023 |
| Valve         | Jupiter                     | [a91aee62d3](https://linux-hardware.org/?probe=a91aee62d3) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| Dell          | XPS M1330                   | [46b9a5cfde](https://linux-hardware.org/?probe=46b9a5cfde) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Dell          | Latitude 7490               | [06928c624b](https://linux-hardware.org/?probe=06928c624b) | Mar 31, 2023 |
| Lenovo        | G550 2958                   | [41f23ded68](https://linux-hardware.org/?probe=41f23ded68) | Mar 30, 2023 |
| Lenovo        | N22 80S6                    | [c6cbeeb984](https://linux-hardware.org/?probe=c6cbeeb984) | Mar 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| Acer          | Swift SFX14-41G             | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Sony          | VPCCB32FD                   | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| Dell          | Studio 1558                 | [955946c74d](https://linux-hardware.org/?probe=955946c74d) | Mar 28, 2023 |
| Dell          | Latitude 7490               | [58ccd5d7e0](https://linux-hardware.org/?probe=58ccd5d7e0) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [7dbe4350b5](https://linux-hardware.org/?probe=7dbe4350b5) | Mar 26, 2023 |
| Lenovo        | ThinkPad X220 4290LR3       | [dffa03da18](https://linux-hardware.org/?probe=dffa03da18) | Mar 26, 2023 |
| Lenovo        | ThinkPad T430 4237ZC7       | [845a2ed117](https://linux-hardware.org/?probe=845a2ed117) | Mar 26, 2023 |
| Sony          | VPCCB32FD                   | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Apple         | MacBookPro11,2              | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [c91fa425a5](https://linux-hardware.org/?probe=c91fa425a5) | Mar 23, 2023 |
| Acer          | Aspire A515-55              | [ebbb5efcbc](https://linux-hardware.org/?probe=ebbb5efcbc) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Framework     | Laptop                      | [a7dc7b28c9](https://linux-hardware.org/?probe=a7dc7b28c9) | Mar 21, 2023 |
| Fujitsu       | FMVNP8AE                    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7df2952615](https://linux-hardware.org/?probe=7df2952615) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| HP            | Laptop 15-dy1xxx            | [63893daa0f](https://linux-hardware.org/?probe=63893daa0f) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [ae37b87da6](https://linux-hardware.org/?probe=ae37b87da6) | Mar 16, 2023 |
| Dell          | Inspiron 15-3552            | [10e835b353](https://linux-hardware.org/?probe=10e835b353) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Matsushita... | CF-18KH2ZXBC                | [9aa73891cd](https://linux-hardware.org/?probe=9aa73891cd) | Mar 15, 2023 |
| Toshiba       | Satellite P870              | [113fcf770d](https://linux-hardware.org/?probe=113fcf770d) | Mar 15, 2023 |
| Acer          | Aspire 5750Z                | [3ea59ee8c5](https://linux-hardware.org/?probe=3ea59ee8c5) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [7fbe857344](https://linux-hardware.org/?probe=7fbe857344) | Mar 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [9332803ca3](https://linux-hardware.org/?probe=9332803ca3) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |
| Google        | Droid                       | [b2a41c71ac](https://linux-hardware.org/?probe=b2a41c71ac) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | [2eb6d39ced](https://linux-hardware.org/?probe=2eb6d39ced) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | [01f61fad51](https://linux-hardware.org/?probe=01f61fad51) | Mar 12, 2023 |
| Unknown       | Unknown                     | [d1336c09a0](https://linux-hardware.org/?probe=d1336c09a0) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Acer          | Aspire ES1-531              | [bf2d3857fd](https://linux-hardware.org/?probe=bf2d3857fd) | Mar 09, 2023 |
| Dell          | Latitude 3180               | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [da38390eca](https://linux-hardware.org/?probe=da38390eca) | Mar 09, 2023 |
| Lenovo        | 3000 N200 0769AUU           | [faaa24cfbf](https://linux-hardware.org/?probe=faaa24cfbf) | Mar 07, 2023 |
| Dell          | Studio 1537                 | [2cadadec43](https://linux-hardware.org/?probe=2cadadec43) | Mar 07, 2023 |
| Dell          | Latitude E6520              | [5e7340faf5](https://linux-hardware.org/?probe=5e7340faf5) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | [fe3f99601c](https://linux-hardware.org/?probe=fe3f99601c) | Mar 07, 2023 |
| Datto         | 1000                        | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Acer          | Aspire E1-571               | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Apple         | MacBookPro9,2               | [64d9894f5e](https://linux-hardware.org/?probe=64d9894f5e) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| MSI           | PS42 8RB                    | [effde33b49](https://linux-hardware.org/?probe=effde33b49) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | [886fdbe7c9](https://linux-hardware.org/?probe=886fdbe7c9) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | [2fdc151d2f](https://linux-hardware.org/?probe=2fdc151d2f) | Mar 05, 2023 |
| Dell          | Precision M4800             | [b014753659](https://linux-hardware.org/?probe=b014753659) | Mar 05, 2023 |
| HP            | Presario CQ61               | [912b79009b](https://linux-hardware.org/?probe=912b79009b) | Mar 04, 2023 |
| Acer          | Swift SF314-42              | [b9a0465659](https://linux-hardware.org/?probe=b9a0465659) | Mar 04, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9aebf534a5](https://linux-hardware.org/?probe=9aebf534a5) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | ENVY 17                     | [52b43673bb](https://linux-hardware.org/?probe=52b43673bb) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Dell          | Precision 5520              | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| Valve         | Jupiter                     | [6525b5d0a4](https://linux-hardware.org/?probe=6525b5d0a4) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| Valve         | Jupiter                     | [a6c009eb9c](https://linux-hardware.org/?probe=a6c009eb9c) | Mar 01, 2023 |
| Acer          | Aspire E1-532P              | [8a23f06db4](https://linux-hardware.org/?probe=8a23f06db4) | Mar 01, 2023 |
| HP            | Pavilion dv6                | [c937edbfcd](https://linux-hardware.org/?probe=c937edbfcd) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [d8b58a8ea1](https://linux-hardware.org/?probe=d8b58a8ea1) | Feb 28, 2023 |
| Alienware     | x15 R2                      | [f0335542ce](https://linux-hardware.org/?probe=f0335542ce) | Feb 28, 2023 |
| Toshiba       | Satellite P870              | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | [a9a8184201](https://linux-hardware.org/?probe=a9a8184201) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | [07f46e8e62](https://linux-hardware.org/?probe=07f46e8e62) | Feb 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [8de57c03d5](https://linux-hardware.org/?probe=8de57c03d5) | Feb 27, 2023 |
| HP            | EliteBook 2530p             | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Apple         | MacBook5,1                  | [fbb2478f8c](https://linux-hardware.org/?probe=fbb2478f8c) | Feb 25, 2023 |
| HP            | G60                         | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| Google        | Kefka                       | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Dell          | Inspiron 5566               | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Dell          | Latitude E6520              | [4a9371ec87](https://linux-hardware.org/?probe=4a9371ec87) | Feb 22, 2023 |
| Dell          | Inspiron 5493               | [ad7bee8a6e](https://linux-hardware.org/?probe=ad7bee8a6e) | Feb 20, 2023 |
| Dell          | Latitude E5440              | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| Dell          | Precision M4500             | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Panasonic     | CF-S10CDHEDM                | [7228f7a915](https://linux-hardware.org/?probe=7228f7a915) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [58ca93166c](https://linux-hardware.org/?probe=58ca93166c) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9978dc62b3](https://linux-hardware.org/?probe=9978dc62b3) | Feb 18, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [6b7a3b68f3](https://linux-hardware.org/?probe=6b7a3b68f3) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | [041cf0d3d8](https://linux-hardware.org/?probe=041cf0d3d8) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | [20dc6d6c5c](https://linux-hardware.org/?probe=20dc6d6c5c) | Feb 18, 2023 |
| HP            | Pavilion 13 x360 PC         | [af3167a0d4](https://linux-hardware.org/?probe=af3167a0d4) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [9ab628bcf2](https://linux-hardware.org/?probe=9ab628bcf2) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | [aaa83a4af0](https://linux-hardware.org/?probe=aaa83a4af0) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | [18b6274238](https://linux-hardware.org/?probe=18b6274238) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [33d9c73cb9](https://linux-hardware.org/?probe=33d9c73cb9) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| Google        | Coral                       | [7a9869ff50](https://linux-hardware.org/?probe=7a9869ff50) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [0e694f49fe](https://linux-hardware.org/?probe=0e694f49fe) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| Dell          | Precision 7710              | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| HP            | EliteBook 840 G5            | [2d99eeaca6](https://linux-hardware.org/?probe=2d99eeaca6) | Feb 13, 2023 |
| Panasonic     | CF-C2CCEZXCM                | [c435502e6e](https://linux-hardware.org/?probe=c435502e6e) | Feb 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1VL0... | [d4b5ca228c](https://linux-hardware.org/?probe=d4b5ca228c) | Feb 13, 2023 |
| HP            | Pavilion dv2500             | [bea8c0162f](https://linux-hardware.org/?probe=bea8c0162f) | Feb 12, 2023 |
| Panasonic     | CF-C2CCEZXCM                | [3a0ce0730a](https://linux-hardware.org/?probe=3a0ce0730a) | Feb 12, 2023 |
| Acer          | Aspire 8942G                | [d517f63625](https://linux-hardware.org/?probe=d517f63625) | Feb 12, 2023 |
| Valve         | Jupiter                     | [10084e1b16](https://linux-hardware.org/?probe=10084e1b16) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3982ec4e74](https://linux-hardware.org/?probe=3982ec4e74) | Feb 12, 2023 |
| HP            | Presario V6000 (RN927UA#... | [0524b3b524](https://linux-hardware.org/?probe=0524b3b524) | Feb 11, 2023 |
| Google        | Droid                       | [33dbb43623](https://linux-hardware.org/?probe=33dbb43623) | Feb 10, 2023 |
| HP            | Notebook                    | [17664bf689](https://linux-hardware.org/?probe=17664bf689) | Feb 10, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [0a74293474](https://linux-hardware.org/?probe=0a74293474) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| HP            | EliteBook 8460p             | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [d236f5fa51](https://linux-hardware.org/?probe=d236f5fa51) | Feb 09, 2023 |
| HP            | Pavilion dv7                | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Lenovo        | Unknown                     | [67c2761551](https://linux-hardware.org/?probe=67c2761551) | Feb 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [ebe5940bd7](https://linux-hardware.org/?probe=ebe5940bd7) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | [bd02e4c770](https://linux-hardware.org/?probe=bd02e4c770) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | [43a7194d4b](https://linux-hardware.org/?probe=43a7194d4b) | Feb 07, 2023 |
| Acer          | Okinawa                     | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Acer          | Aspire A315-21              | [b452c164d0](https://linux-hardware.org/?probe=b452c164d0) | Feb 05, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [f3f4d9fc40](https://linux-hardware.org/?probe=f3f4d9fc40) | Feb 04, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Valve         | Jupiter                     | [d78de63927](https://linux-hardware.org/?probe=d78de63927) | Feb 04, 2023 |
| Acer          | Aspire A517-51G             | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| Dell          | Latitude 3400               | [c954aad23a](https://linux-hardware.org/?probe=c954aad23a) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Dell          | Inspiron 15-7579            | [b5bd231bf3](https://linux-hardware.org/?probe=b5bd231bf3) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| Dell          | Latitude D630               | [ff0aa8c4ed](https://linux-hardware.org/?probe=ff0aa8c4ed) | Jan 31, 2023 |
| Dell          | Latitude D630               | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS0BR00     | [6c05048c9d](https://linux-hardware.org/?probe=6c05048c9d) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Apple         | MacBookPro8,1               | [0eac708be5](https://linux-hardware.org/?probe=0eac708be5) | Jan 31, 2023 |
| HP            | Notebook                    | [fc93f8e357](https://linux-hardware.org/?probe=fc93f8e357) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [3fcf581653](https://linux-hardware.org/?probe=3fcf581653) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [3e7c902731](https://linux-hardware.org/?probe=3e7c902731) | Jan 28, 2023 |
| ASUSTek       | X555QA                      | [8eec8468fb](https://linux-hardware.org/?probe=8eec8468fb) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | [991bb71df8](https://linux-hardware.org/?probe=991bb71df8) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | [d86e915f12](https://linux-hardware.org/?probe=d86e915f12) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [55477da159](https://linux-hardware.org/?probe=55477da159) | Jan 27, 2023 |
| Dell          | Latitude E6540              | [2e014cf1ba](https://linux-hardware.org/?probe=2e014cf1ba) | Jan 27, 2023 |
| Acer          | Aspire R3-131T              | [021d999708](https://linux-hardware.org/?probe=021d999708) | Jan 27, 2023 |
| Dell          | Latitude E6420              | [9837928212](https://linux-hardware.org/?probe=9837928212) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [08204bf161](https://linux-hardware.org/?probe=08204bf161) | Jan 26, 2023 |
| Apple         | MacBookAir4,1               | [45ea832a59](https://linux-hardware.org/?probe=45ea832a59) | Jan 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Valve         | Jupiter                     | [ba217c947c](https://linux-hardware.org/?probe=ba217c947c) | Jan 25, 2023 |
| Valve         | Jupiter                     | [ffd9523db2](https://linux-hardware.org/?probe=ffd9523db2) | Jan 25, 2023 |
| Apple         | MacBookPro5,4               | [4bdccd0680](https://linux-hardware.org/?probe=4bdccd0680) | Jan 24, 2023 |
| ASUSTek       | X555QA                      | [f981af502a](https://linux-hardware.org/?probe=f981af502a) | Jan 24, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Acer          | AO722                       | [85f48171a2](https://linux-hardware.org/?probe=85f48171a2) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | [77d4494f3b](https://linux-hardware.org/?probe=77d4494f3b) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | [f3d76bcb70](https://linux-hardware.org/?probe=f3d76bcb70) | Jan 23, 2023 |
| Dell          | Inspiron 3521               | [ff122405db](https://linux-hardware.org/?probe=ff122405db) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | [bb77ccdda7](https://linux-hardware.org/?probe=bb77ccdda7) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | [2189958490](https://linux-hardware.org/?probe=2189958490) | Jan 22, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6ae7274931](https://linux-hardware.org/?probe=6ae7274931) | Jan 22, 2023 |
| Acer          | Aspire E1-531               | [217c63b8f6](https://linux-hardware.org/?probe=217c63b8f6) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| Dell          | XPS 15 9520                 | [330a3844cb](https://linux-hardware.org/?probe=330a3844cb) | Jan 21, 2023 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | [e0b197c0c4](https://linux-hardware.org/?probe=e0b197c0c4) | Jan 21, 2023 |
| HP            | Laptop 15-dy3xxx            | [1053d34e69](https://linux-hardware.org/?probe=1053d34e69) | Jan 20, 2023 |
| ASUSTek       | X555QA                      | [cd42f89819](https://linux-hardware.org/?probe=cd42f89819) | Jan 20, 2023 |
| Valve         | Jupiter                     | [e29a7a31ae](https://linux-hardware.org/?probe=e29a7a31ae) | Jan 20, 2023 |
| Dell          | Studio XPS 1647             | [4086a6120a](https://linux-hardware.org/?probe=4086a6120a) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| Toshiba       | Satellite L650D             | [86d99d74cd](https://linux-hardware.org/?probe=86d99d74cd) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [3ab44ae2f5](https://linux-hardware.org/?probe=3ab44ae2f5) | Jan 17, 2023 |
| HP            | Pavilion dv7                | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| Dell          | Inspiron 3521               | [2d46e86664](https://linux-hardware.org/?probe=2d46e86664) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [a602bcd50a](https://linux-hardware.org/?probe=a602bcd50a) | Jan 17, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | [1bd88ff8c7](https://linux-hardware.org/?probe=1bd88ff8c7) | Jan 17, 2023 |
| Valve         | Jupiter                     | [2b355faaee](https://linux-hardware.org/?probe=2b355faaee) | Jan 16, 2023 |
| Dell          | Inspiron 3521               | [da7f445f06](https://linux-hardware.org/?probe=da7f445f06) | Jan 16, 2023 |
| HP            | Pavilion 17                 | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [e04d230b62](https://linux-hardware.org/?probe=e04d230b62) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | [422f31719c](https://linux-hardware.org/?probe=422f31719c) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | [c16748dc74](https://linux-hardware.org/?probe=c16748dc74) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Toshiba       | Satellite L650              | [b893aecea2](https://linux-hardware.org/?probe=b893aecea2) | Jan 15, 2023 |
| Valve         | Jupiter                     | [c9bc8bf29b](https://linux-hardware.org/?probe=c9bc8bf29b) | Jan 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [9527eef253](https://linux-hardware.org/?probe=9527eef253) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | [6194c3a2fe](https://linux-hardware.org/?probe=6194c3a2fe) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [a24b95f891](https://linux-hardware.org/?probe=a24b95f891) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | [4776fc6062](https://linux-hardware.org/?probe=4776fc6062) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [f9fe88837c](https://linux-hardware.org/?probe=f9fe88837c) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [59607f5e75](https://linux-hardware.org/?probe=59607f5e75) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [a4b4747500](https://linux-hardware.org/?probe=a4b4747500) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | [4340505060](https://linux-hardware.org/?probe=4340505060) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [03f7a5fdea](https://linux-hardware.org/?probe=03f7a5fdea) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [9e4c15fff7](https://linux-hardware.org/?probe=9e4c15fff7) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | [77d37c245a](https://linux-hardware.org/?probe=77d37c245a) | Jan 14, 2023 |
| MSI           | GP72 7RDX                   | [9cf1da2d69](https://linux-hardware.org/?probe=9cf1da2d69) | Jan 14, 2023 |
| Dell          | Latitude E6420              | [e7c4823aee](https://linux-hardware.org/?probe=e7c4823aee) | Jan 14, 2023 |
| HP            | Notebook                    | [e242059a08](https://linux-hardware.org/?probe=e242059a08) | Jan 14, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [eeec2db688](https://linux-hardware.org/?probe=eeec2db688) | Jan 13, 2023 |
| Acer          | Aspire E1-572               | [fa6e296766](https://linux-hardware.org/?probe=fa6e296766) | Jan 13, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| Matsushita... | CF-18KH2ZXBC                | [41e8ef7b23](https://linux-hardware.org/?probe=41e8ef7b23) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Valve         | Jupiter                     | [6bfa934fb6](https://linux-hardware.org/?probe=6bfa934fb6) | Jan 11, 2023 |
| Dell          | G5 5590                     | [846a462365](https://linux-hardware.org/?probe=846a462365) | Jan 10, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [c6e3650e2b](https://linux-hardware.org/?probe=c6e3650e2b) | Jan 10, 2023 |
| System76      | Darter Pro                  | [ffaaf5c90e](https://linux-hardware.org/?probe=ffaaf5c90e) | Jan 10, 2023 |
| HP            | ENVY Notebook               | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| Google        | Blooglet                    | [bf644ec6f4](https://linux-hardware.org/?probe=bf644ec6f4) | Jan 10, 2023 |
| Dell          | Inspiron 5577               | [86cfa19622](https://linux-hardware.org/?probe=86cfa19622) | Jan 10, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | [302f3a5ebe](https://linux-hardware.org/?probe=302f3a5ebe) | Jan 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [2bbe617df6](https://linux-hardware.org/?probe=2bbe617df6) | Jan 09, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d6115e24c1](https://linux-hardware.org/?probe=d6115e24c1) | Jan 09, 2023 |
| GPU Compan... | GWNR71517                   | [5626a7c211](https://linux-hardware.org/?probe=5626a7c211) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [f884203e84](https://linux-hardware.org/?probe=f884203e84) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b518c0a817](https://linux-hardware.org/?probe=b518c0a817) | Jan 09, 2023 |
| ASUSTek       | X550ZA                      | [272bff51c5](https://linux-hardware.org/?probe=272bff51c5) | Jan 09, 2023 |
| GPU Compan... | GWNR71517                   | [11cb3f9636](https://linux-hardware.org/?probe=11cb3f9636) | Jan 08, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [c8e96fe453](https://linux-hardware.org/?probe=c8e96fe453) | Jan 08, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | [b95882e5cf](https://linux-hardware.org/?probe=b95882e5cf) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | [cfcc0a49c6](https://linux-hardware.org/?probe=cfcc0a49c6) | Jan 08, 2023 |
| Valve         | Jupiter                     | [4c96ccba44](https://linux-hardware.org/?probe=4c96ccba44) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2e22cc1bb2](https://linux-hardware.org/?probe=2e22cc1bb2) | Jan 08, 2023 |
| Lenovo        | ThinkPad W520 4284A24       | [263e00840a](https://linux-hardware.org/?probe=263e00840a) | Jan 08, 2023 |
| Dell          | XPS 9320                    | [55be119900](https://linux-hardware.org/?probe=55be119900) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [83ec1382a3](https://linux-hardware.org/?probe=83ec1382a3) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [354b2538a4](https://linux-hardware.org/?probe=354b2538a4) | Jan 07, 2023 |
| HP            | Pavilion dv4                | [5caee4abe0](https://linux-hardware.org/?probe=5caee4abe0) | Jan 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [15eaac1fac](https://linux-hardware.org/?probe=15eaac1fac) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| Dell          | Inspiron 7577               | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| ASUSTek       | X301A1                      | [e575482522](https://linux-hardware.org/?probe=e575482522) | Jan 06, 2023 |
| Dell          | G15 5525                    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [4d2721777a](https://linux-hardware.org/?probe=4d2721777a) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | [d2ee3f78a9](https://linux-hardware.org/?probe=d2ee3f78a9) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | [9c9801b860](https://linux-hardware.org/?probe=9c9801b860) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [907ceedda1](https://linux-hardware.org/?probe=907ceedda1) | Jan 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [2da57c3386](https://linux-hardware.org/?probe=2da57c3386) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [3d589a827c](https://linux-hardware.org/?probe=3d589a827c) | Jan 04, 2023 |
| Dell          | Latitude D520               | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Datto         | Unknown                     | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| HP            | Pavilion dv7                | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| Dell          | Latitude E5440              | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| HP            | Pavilion dv6                | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| Valve         | Jupiter                     | [1dedff3ad9](https://linux-hardware.org/?probe=1dedff3ad9) | Jan 01, 2023 |
| Dell          | Latitude E7450              | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| Acer          | Aspire E5-521               | [d9b5e3cfc3](https://linux-hardware.org/?probe=d9b5e3cfc3) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| ASUSTek       | TP501UA                     | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Acer          | Aspire A115-32              | [7c8ec90c8a](https://linux-hardware.org/?probe=7c8ec90c8a) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [1cab27a65e](https://linux-hardware.org/?probe=1cab27a65e) | Dec 29, 2022 |
| HP            | EliteBook 2540p             | [ec9251ac5d](https://linux-hardware.org/?probe=ec9251ac5d) | Dec 28, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [9e95d6a4ac](https://linux-hardware.org/?probe=9e95d6a4ac) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkPad T500 205545F       | [c12d9f8c6a](https://linux-hardware.org/?probe=c12d9f8c6a) | Dec 27, 2022 |
| Dell          | Latitude E7440              | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [877e3cd944](https://linux-hardware.org/?probe=877e3cd944) | Dec 26, 2022 |
| Dell          | Latitude E4310              | [f63df6ad2c](https://linux-hardware.org/?probe=f63df6ad2c) | Dec 26, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [90a67d3589](https://linux-hardware.org/?probe=90a67d3589) | Dec 25, 2022 |
| Valve         | Jupiter                     | [91be8cc560](https://linux-hardware.org/?probe=91be8cc560) | Dec 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 360       | 11.77%  |
| Ubuntu 18.04        | 200       | 6.54%   |
| Ubuntu 22.04        | 167       | 5.46%   |
| Pop!_OS 22.04       | 74        | 2.42%   |
| Zorin 16            | 68        | 2.22%   |
| Arch Rolling        | 58        | 1.9%    |
| OpenMandriva 4.3    | 57        | 1.86%   |
| Manjaro             | 54        | 1.77%   |
| Fedora 38           | 54        | 1.77%   |
| Debian 11           | 53        | 1.73%   |
| Linux Mint 20.3     | 52        | 1.7%    |
| KDE neon 20.04      | 50        | 1.63%   |
| OpenMandriva 4.2    | 49        | 1.6%    |
| Arch                | 48        | 1.57%   |
| Zorin 15            | 43        | 1.41%   |
| Xubuntu 20.04       | 43        | 1.41%   |
| ArcoLinux Rolling   | 43        | 1.41%   |
| Linux Mint 21.1     | 40        | 1.31%   |
| Ubuntu 19.10        | 39        | 1.27%   |
| Linux Mint 19.3     | 39        | 1.27%   |
| Pop!_OS 21.04       | 38        | 1.24%   |
| Pop!_OS 20.04       | 36        | 1.18%   |
| Fedora 37           | 36        | 1.18%   |
| Fedora 35           | 35        | 1.14%   |
| Ubuntu 21.10        | 33        | 1.08%   |
| Linux Mint 21       | 33        | 1.08%   |
| Ubuntu 20.10        | 31        | 1.01%   |
| Linux Mint 20.1     | 31        | 1.01%   |
| Linux Mint 20.2     | 30        | 0.98%   |
| Pop!_OS 20.10       | 29        | 0.95%   |
| Ubuntu 19.04        | 27        | 0.88%   |
| Ubuntu 23.04        | 26        | 0.85%   |
| Linux Mint 20       | 26        | 0.85%   |
| OpenMandriva 23.03  | 24        | 0.78%   |
| OpenMandriva 23.01  | 24        | 0.78%   |
| Fedora 32           | 24        | 0.78%   |
| EndeavourOS Rolling | 24        | 0.78%   |
| Ubuntu 21.04        | 23        | 0.75%   |
| Pop!_OS 21.10       | 23        | 0.75%   |
| Ubuntu 22.10        | 22        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 904       | 31.07%  |
| Linux Mint    | 264       | 9.07%   |
| Fedora        | 217       | 7.46%   |
| Pop!_OS       | 192       | 6.6%    |
| OpenMandriva  | 182       | 6.25%   |
| Zorin         | 116       | 3.99%   |
| Manjaro       | 107       | 3.68%   |
| Debian        | 104       | 3.57%   |
| Arch          | 101       | 3.47%   |
| Xubuntu       | 72        | 2.47%   |
| KDE neon      | 67        | 2.3%    |
| Kubuntu       | 56        | 1.92%   |
| ArcoLinux     | 46        | 1.58%   |
| SteamOS       | 43        | 1.48%   |
| ROSA          | 36        | 1.24%   |
| Gentoo        | 33        | 1.13%   |
| Kali          | 31        | 1.07%   |
| EndeavourOS   | 26        | 0.89%   |
| openSUSE      | 25        | 0.86%   |
| Elementary    | 25        | 0.86%   |
| Lubuntu       | 22        | 0.76%   |
| MX            | 20        | 0.69%   |
| Clear Linux   | 19        | 0.65%   |
| Endless       | 17        | 0.58%   |
| BlackPanther  | 16        | 0.55%   |
| Garuda Linux  | 15        | 0.52%   |
| Ubuntu Unity  | 12        | 0.41%   |
| Ubuntu Budgie | 12        | 0.41%   |
| Ubuntu MATE   | 9         | 0.31%   |
| Peppermint    | 9         | 0.31%   |
| LMDE          | 9         | 0.31%   |
| Parrot        | 8         | 0.27%   |
| Alpine        | 8         | 0.27%   |
| Xero          | 6         | 0.21%   |
| Nobara        | 6         | 0.21%   |
| CentOS        | 6         | 0.21%   |
| LinuxFX       | 5         | 0.17%   |
| Ubuntu Studio | 4         | 0.14%   |
| NixOS         | 4         | 0.14%   |
| Artix         | 4         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 51        | 1.5%    |
| 5.10.14-desktop-1omv4002 | 47        | 1.39%   |
| 5.4.0-42-generic         | 45        | 1.33%   |
| 5.11.0-27-generic        | 42        | 1.24%   |
| 5.15.0-56-generic        | 32        | 0.94%   |
| 5.3.0-40-generic         | 27        | 0.8%    |
| 6.2.6-desktop-1omv2390   | 24        | 0.71%   |
| 5.15.0-52-generic        | 24        | 0.71%   |
| 6.1.1-desktop-1omv2290   | 23        | 0.68%   |
| 5.4.0-29-generic         | 23        | 0.68%   |
| 5.15.0-58-generic        | 23        | 0.68%   |
| 5.4.0-52-generic         | 21        | 0.62%   |
| 5.4.0-40-generic         | 21        | 0.62%   |
| 5.0.0-37-generic         | 21        | 0.62%   |
| 5.8.0-7630-generic       | 20        | 0.59%   |
| 5.4.0-58-generic         | 20        | 0.59%   |
| 5.3.0-46-generic         | 20        | 0.59%   |
| 6.2.0-26-generic         | 18        | 0.53%   |
| 5.4.0-48-generic         | 18        | 0.53%   |
| 5.4.0-45-generic         | 18        | 0.53%   |
| 5.15.0-41-generic        | 18        | 0.53%   |
| 6.2.6-76060206-generic   | 17        | 0.5%    |
| 5.13.0-valve36-1-neptune | 17        | 0.5%    |
| 6.4.11-desktop-1omv2390  | 16        | 0.47%   |
| 5.15.0-71-generic        | 16        | 0.47%   |
| 5.15.0-46-generic        | 16        | 0.47%   |
| 5.4.0-37-generic         | 15        | 0.44%   |
| 5.4.0-26-generic         | 15        | 0.44%   |
| 5.15.0-47-generic        | 15        | 0.44%   |
| 5.13.0-7614-generic      | 15        | 0.44%   |
| 5.11.0-40-generic        | 15        | 0.44%   |
| 5.8.0-41-generic         | 14        | 0.41%   |
| 5.4.0-91-generic         | 14        | 0.41%   |
| 5.4.0-47-generic         | 14        | 0.41%   |
| 5.3.0-42-generic         | 14        | 0.41%   |
| 5.13.0-30-generic        | 14        | 0.41%   |
| 5.11.0-38-generic        | 14        | 0.41%   |
| 5.8.0-43-generic         | 13        | 0.38%   |
| 5.4.0-72-generic         | 13        | 0.38%   |
| 5.4.0-54-generic         | 13        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 475       | 14.97%  |
| 5.15.0  | 271       | 8.54%   |
| 5.11.0  | 178       | 5.61%   |
| 5.13.0  | 166       | 5.23%   |
| 5.8.0   | 147       | 4.63%   |
| 5.3.0   | 144       | 4.54%   |
| 4.15.0  | 140       | 4.41%   |
| 5.19.0  | 98        | 3.09%   |
| 5.0.0   | 88        | 2.77%   |
| 6.2.0   | 71        | 2.24%   |
| 5.10.0  | 69        | 2.17%   |
| 5.16.7  | 53        | 1.67%   |
| 5.10.14 | 48        | 1.51%   |
| 4.18.0  | 48        | 1.51%   |
| 6.2.6   | 43        | 1.35%   |
| 6.1.0   | 33        | 1.04%   |
| 6.1.1   | 27        | 0.85%   |
| 4.19.0  | 22        | 0.69%   |
| 6.4.11  | 19        | 0.6%    |
| 5.14.0  | 15        | 0.47%   |
| 6.2.9   | 14        | 0.44%   |
| 6.0.0   | 13        | 0.41%   |
| 5.17.5  | 13        | 0.41%   |
| 6.0.6   | 11        | 0.35%   |
| 5.16.13 | 11        | 0.35%   |
| 5.15.5  | 11        | 0.35%   |
| 4.18.16 | 11        | 0.35%   |
| 6.2.10  | 10        | 0.32%   |
| 6.0.12  | 10        | 0.32%   |
| 5.18.0  | 10        | 0.32%   |
| 5.9.16  | 9         | 0.28%   |
| 5.9.11  | 9         | 0.28%   |
| 5.15.11 | 9         | 0.28%   |
| 6.4.8   | 8         | 0.25%   |
| 6.4.12  | 8         | 0.25%   |
| 6.2.15  | 8         | 0.25%   |
| 5.17.9  | 8         | 0.25%   |
| 5.17.0  | 8         | 0.25%   |
| 5.16.0  | 8         | 0.25%   |
| 5.11.12 | 8         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 517       | 16.55%  |
| 5.15    | 366       | 11.72%  |
| 5.11    | 203       | 6.5%    |
| 5.8     | 197       | 6.31%   |
| 5.13    | 186       | 5.96%   |
| 6.2     | 170       | 5.44%   |
| 5.10    | 163       | 5.22%   |
| 5.3     | 153       | 4.9%    |
| 4.15    | 141       | 4.51%   |
| 5.19    | 122       | 3.91%   |
| 5.16    | 106       | 3.39%   |
| 6.1     | 99        | 3.17%   |
| 5.0     | 90        | 2.88%   |
| 6.0     | 72        | 2.31%   |
| 6.4     | 64        | 2.05%   |
| 4.18    | 59        | 1.89%   |
| 5.17    | 49        | 1.57%   |
| 5.9     | 44        | 1.41%   |
| 6.5     | 39        | 1.25%   |
| 5.14    | 38        | 1.22%   |
| 5.18    | 36        | 1.15%   |
| 6.3     | 35        | 1.12%   |
| 5.12    | 31        | 0.99%   |
| 4.19    | 29        | 0.93%   |
| 5.6     | 26        | 0.83%   |
| 4.9     | 24        | 0.77%   |
| 5.7     | 23        | 0.74%   |
| 5.5     | 13        | 0.42%   |
| 4.4     | 7         | 0.22%   |
| 3.10    | 3         | 0.1%    |
| 6.6     | 2         | 0.06%   |
| 5.2     | 2         | 0.06%   |
| 5.1     | 2         | 0.06%   |
| 4.8     | 2         | 0.06%   |
| 4.20    | 2         | 0.06%   |
| 4.14    | 2         | 0.06%   |
| 4.1     | 2         | 0.06%   |
| 4.16    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |
| 3.18    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2695      | 96.94%  |
| i686    | 81        | 2.91%   |
| armv7l  | 3         | 0.11%   |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| GNOME                | 1273      | 43.58%  |
| KDE5                 | 518       | 17.73%  |
| Unknown              | 324       | 11.09%  |
| XFCE                 | 229       | 7.84%   |
| X-Cinnamon           | 210       | 7.19%   |
| KDE                  | 76        | 2.6%    |
| MATE                 | 62        | 2.12%   |
| Cinnamon             | 34        | 1.16%   |
| KDE4                 | 25        | 0.86%   |
| LXQt                 | 24        | 0.82%   |
| Pantheon             | 23        | 0.79%   |
| i3                   | 23        | 0.79%   |
| LXDE                 | 16        | 0.55%   |
| Budgie               | 16        | 0.55%   |
| Unity                | 15        | 0.51%   |
| GNOME Flashback      | 10        | 0.34%   |
| DWM                  | 6         | 0.21%   |
| Deepin               | 5         | 0.17%   |
| sway                 | 4         | 0.14%   |
| qtile                | 4         | 0.14%   |
| enlightenment        | 4         | 0.14%   |
| xmonad               | 3         | 0.1%    |
| awesome              | 3         | 0.1%    |
| Hyprland             | 2         | 0.07%   |
| GNOME Classic        | 2         | 0.07%   |
| chadwm               | 2         | 0.07%   |
| xsession             | 1         | 0.03%   |
| wmaker-common        | 1         | 0.03%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.03%   |
| spectrwm             | 1         | 0.03%   |
| lightdm-xsession     | 1         | 0.03%   |
| Jwm                  | 1         | 0.03%   |
| GNOME-Classic        | 1         | 0.03%   |
| bspwm                | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2150      | 74.76%  |
| Wayland | 510       | 17.73%  |
| Unknown | 182       | 6.33%   |
| Tty     | 33        | 1.15%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1491      | 51.17%  |
| SDDM    | 433       | 14.86%  |
| GDM3    | 319       | 10.95%  |
| GDM     | 299       | 10.26%  |
| LightDM | 257       | 8.82%   |
| TDM     | 74        | 2.54%   |
| KDM     | 24        | 0.82%   |
| XDM     | 6         | 0.21%   |
| Ly      | 6         | 0.21%   |
| LXDM    | 4         | 0.14%   |
| LY-DM   | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_CA   | 1436      | 49.86%  |
| en_US   | 808       | 28.06%  |
| Unknown | 282       | 9.79%   |
| fr_CA   | 198       | 6.88%   |
| C       | 61        | 2.12%   |
| fr_FR   | 31        | 1.08%   |
| en_GB   | 14        | 0.49%   |
| C.UTF8  | 7         | 0.24%   |
| POSIX   | 5         | 0.17%   |
| en_AU   | 4         | 0.14%   |
| pt_BR   | 3         | 0.1%    |
| hu_HU   | 3         | 0.1%    |
| es_ES   | 3         | 0.1%    |
| en_IN   | 3         | 0.1%    |
| zh_CN   | 2         | 0.07%   |
| uk_UA   | 2         | 0.07%   |
| ru_RU   | 2         | 0.07%   |
| pl_PL   | 2         | 0.07%   |
| zh_TW   | 1         | 0.03%   |
| ro_RO   | 1         | 0.03%   |
| pa_IN   | 1         | 0.03%   |
| hr_HR   | 1         | 0.03%   |
| ga_IE   | 1         | 0.03%   |
| es_CL   | 1         | 0.03%   |
| en_ZA   | 1         | 0.03%   |
| en_NZ   | 1         | 0.03%   |
| en_IE   | 1         | 0.03%   |
| en_FI   | 1         | 0.03%   |
| en_DK   | 1         | 0.03%   |
| de_DE   | 1         | 0.03%   |
| co_FR   | 1         | 0.03%   |
| ar_EG   | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1464      | 51.3%   |
| EFI  | 1390      | 48.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2099      | 73.34%  |
| Btrfs   | 321       | 11.22%  |
| Overlay | 234       | 8.18%   |
| Unknown | 79        | 2.76%   |
| Tmpfs   | 61        | 2.13%   |
| Xfs     | 27        | 0.94%   |
| Zfs     | 26        | 0.91%   |
| Ext2    | 8         | 0.28%   |
| Ext3    | 3         | 0.1%    |
| Aufs    | 3         | 0.1%    |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1555      | 54.31%  |
| GPT     | 1034      | 36.12%  |
| MBR     | 274       | 9.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2486      | 87.72%  |
| Yes       | 348       | 12.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2159      | 76.29%  |
| Yes       | 671       | 23.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 574       | 20.66%  |
| Dell                           | 524       | 18.86%  |
| Hewlett-Packard                | 446       | 16.05%  |
| ASUSTek Computer               | 309       | 11.12%  |
| Acer                           | 284       | 10.22%  |
| Apple                          | 119       | 4.28%   |
| Toshiba                        | 106       | 3.82%   |
| MSI                            | 73        | 2.63%   |
| Valve                          | 41        | 1.48%   |
| Sony                           | 38        | 1.37%   |
| Google                         | 36        | 1.3%    |
| Alienware                      | 24        | 0.86%   |
| System76                       | 23        | 0.83%   |
| Samsung Electronics            | 23        | 0.83%   |
| Panasonic                      | 19        | 0.68%   |
| Gateway                        | 18        | 0.65%   |
| Unknown                        | 14        | 0.5%    |
| Fujitsu                        | 10        | 0.36%   |
| Gigabyte Technology            | 9         | 0.32%   |
| Razer                          | 8         | 0.29%   |
| Framework                      | 8         | 0.29%   |
| Notebook                       | 6         | 0.22%   |
| HUAWEI                         | 6         | 0.22%   |
| LG Electronics                 | 5         | 0.18%   |
| Matsushita Electric Industrial | 4         | 0.14%   |
| EUROCOM                        | 4         | 0.14%   |
| Intel Client Systems           | 3         | 0.11%   |
| GPU Company                    | 3         | 0.11%   |
| eMachines                      | 3         | 0.11%   |
| Purism                         | 2         | 0.07%   |
| Motion Computing               | 2         | 0.07%   |
| Intel                          | 2         | 0.07%   |
| Getac                          | 2         | 0.07%   |
| Datto                          | 2         | 0.07%   |
| BOSGAME                        | 2         | 0.07%   |
| AZW                            | 2         | 0.07%   |
| Xplore                         | 1         | 0.04%   |
| VIT                            | 1         | 0.04%   |
| Timi                           | 1         | 0.04%   |
| Teclast                        | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Valve Jupiter          | 41        | 1.48%   |
| HP Notebook            | 23        | 0.83%   |
| Unknown                | 23        | 0.83%   |
| HP Pavilion g6         | 20        | 0.72%   |
| Acer Aspire A315-21    | 17        | 0.61%   |
| Dell Latitude E6410    | 15        | 0.54%   |
| Dell XPS 15 7590       | 14        | 0.5%    |
| Dell Latitude E6420    | 14        | 0.5%    |
| Dell XPS 15 9500       | 13        | 0.47%   |
| Apple MacBookPro8,1    | 13        | 0.47%   |
| HP Pavilion dv6        | 12        | 0.43%   |
| Apple MacBookPro9,2    | 12        | 0.43%   |
| HP Pavilion 15         | 11        | 0.4%    |
| HP Pavilion Notebook   | 10        | 0.36%   |
| HP EliteBook 8460p     | 10        | 0.36%   |
| HP Pavilion dv7        | 9         | 0.32%   |
| Dell XPS 13 9310       | 9         | 0.32%   |
| Apple MacBookPro5,5    | 9         | 0.32%   |
| Acer Aspire 5742       | 9         | 0.32%   |
| Toshiba Satellite A200 | 8         | 0.29%   |
| HP Laptop 15-db0xxx    | 8         | 0.29%   |
| HP EliteBook 840 G3    | 8         | 0.29%   |
| Dell Latitude E6540    | 8         | 0.29%   |
| Dell Latitude 7490     | 8         | 0.29%   |
| Dell Inspiron 1545     | 8         | 0.29%   |
| Acer Aspire A315-42    | 8         | 0.29%   |
| Toshiba Satellite C650 | 7         | 0.25%   |
| HP 2000                | 7         | 0.25%   |
| Dell XPS 15 9570       | 7         | 0.25%   |
| Dell XPS 15 9560       | 7         | 0.25%   |
| Dell XPS 13 9360       | 7         | 0.25%   |
| Dell Latitude E6430    | 7         | 0.25%   |
| Dell Latitude D830     | 7         | 0.25%   |
| System76 Galago Pro    | 6         | 0.22%   |
| HP Laptop 14-fq0xxx    | 6         | 0.22%   |
| HP G60                 | 6         | 0.22%   |
| HP EliteBook 8570w     | 6         | 0.22%   |
| HP EliteBook 8470p     | 6         | 0.22%   |
| HP EliteBook 840 G5    | 6         | 0.22%   |
| HP EliteBook 840 G1    | 6         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 383       | 13.79%  |
| Acer Aspire        | 217       | 7.81%   |
| Dell Latitude      | 190       | 6.84%   |
| Dell Inspiron      | 132       | 4.75%   |
| HP Pavilion        | 115       | 4.14%   |
| Dell XPS           | 111       | 4%      |
| Lenovo IdeaPad     | 100       | 3.6%    |
| HP EliteBook       | 91        | 3.28%   |
| Toshiba Satellite  | 90        | 3.24%   |
| ASUS VivoBook      | 70        | 2.52%   |
| HP Laptop          | 64        | 2.3%    |
| HP ProBook         | 47        | 1.69%   |
| Valve Jupiter      | 41        | 1.48%   |
| Dell Precision     | 35        | 1.26%   |
| ASUS ROG           | 34        | 1.22%   |
| Acer Swift         | 25        | 0.9%    |
| HP Notebook        | 23        | 0.83%   |
| ASUS ZenBook       | 23        | 0.83%   |
| Unknown            | 23        | 0.83%   |
| Lenovo Legion      | 21        | 0.76%   |
| HP ENVY            | 21        | 0.76%   |
| Apple MacBookPro9  | 18        | 0.65%   |
| Dell Vostro        | 17        | 0.61%   |
| Apple MacBookPro8  | 17        | 0.61%   |
| ASUS ASUS          | 16        | 0.58%   |
| Acer Nitro         | 16        | 0.58%   |
| Apple MacBookPro5  | 14        | 0.5%    |
| HP Stream          | 13        | 0.47%   |
| Dell Studio        | 13        | 0.47%   |
| ASUS TUF           | 12        | 0.43%   |
| Apple MacBookPro11 | 12        | 0.43%   |
| HP Compaq          | 11        | 0.4%    |
| Lenovo ThinkBook   | 10        | 0.36%   |
| HP ZBook           | 10        | 0.36%   |
| HP Presario        | 9         | 0.32%   |
| Dell System        | 9         | 0.32%   |
| Framework Laptop   | 8         | 0.29%   |
| Apple MacBookPro6  | 8         | 0.29%   |
| Toshiba TECRA      | 7         | 0.25%   |
| Razer Blade        | 7         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 242       | 8.71%   |
| 2011    | 241       | 8.68%   |
| 2012    | 236       | 8.5%    |
| 2018    | 213       | 7.67%   |
| 2019    | 211       | 7.6%    |
| 2017    | 188       | 6.77%   |
| 2013    | 183       | 6.59%   |
| 2014    | 170       | 6.12%   |
| 2010    | 168       | 6.05%   |
| 2021    | 157       | 5.65%   |
| 2022    | 138       | 4.97%   |
| 2016    | 134       | 4.82%   |
| 2008    | 126       | 4.54%   |
| 2015    | 116       | 4.18%   |
| 2009    | 96        | 3.46%   |
| 2007    | 75        | 2.7%    |
| 2023    | 38        | 1.37%   |
| 2006    | 30        | 1.08%   |
| 2005    | 9         | 0.32%   |
| Unknown | 5         | 0.18%   |
| 2004    | 2         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2778      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2563      | 91.47%  |
| Enabled  | 239       | 8.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2724      | 98.02%  |
| Yes  | 55        | 1.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 842       | 29.81%  |
| 8.01-16.0   | 533       | 18.87%  |
| 3.01-4.0    | 532       | 18.83%  |
| 16.01-24.0  | 489       | 17.31%  |
| 32.01-64.0  | 186       | 6.58%   |
| 1.01-2.0    | 120       | 4.25%   |
| 2.01-3.0    | 45        | 1.59%   |
| 64.01-256.0 | 30        | 1.06%   |
| 24.01-32.0  | 27        | 0.96%   |
| 0.51-1.0    | 19        | 0.67%   |
| 0.01-0.5    | 2         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1089      | 35.08%  |
| 2.01-3.0   | 786       | 25.32%  |
| 4.01-8.0   | 463       | 14.92%  |
| 3.01-4.0   | 412       | 13.27%  |
| 0.51-1.0   | 180       | 5.8%    |
| 8.01-16.0  | 114       | 3.67%   |
| 0.01-0.5   | 41        | 1.32%   |
| 16.01-24.0 | 11        | 0.35%   |
| 24.01-32.0 | 6         | 0.19%   |
| 32.01-64.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2088      | 73.19%  |
| 2      | 624       | 21.87%  |
| 3      | 99        | 3.47%   |
| 0      | 24        | 0.84%   |
| 4      | 15        | 0.53%   |
| 5      | 2         | 0.07%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1743      | 62.43%  |
| Yes       | 1049      | 37.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2239      | 80.28%  |
| No        | 550       | 19.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2725      | 98.02%  |
| No        | 55        | 1.98%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2099      | 74.46%  |
| No        | 720       | 25.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 2778      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Toronto         | 281       | 9.59%   |
| Montreal        | 278       | 9.49%   |
| Vancouver       | 122       | 4.16%   |
| Calgary         | 120       | 4.1%    |
| Edmonton        | 97        | 3.31%   |
| Ottawa          | 95        | 3.24%   |
| Québec         | 67        | 2.29%   |
| Winnipeg        | 62        | 2.12%   |
| Mississauga     | 55        | 1.88%   |
| Victoria        | 50        | 1.71%   |
| London          | 37        | 1.26%   |
| Surrey          | 35        | 1.19%   |
| Regina          | 34        | 1.16%   |
| Brampton        | 33        | 1.13%   |
| Laval           | 30        | 1.02%   |
| Kitchener       | 30        | 1.02%   |
| Burnaby         | 26        | 0.89%   |
| Halifax         | 25        | 0.85%   |
| Hamilton        | 24        | 0.82%   |
| Saskatoon       | 23        | 0.78%   |
| Markham         | 23        | 0.78%   |
| Oshawa          | 22        | 0.75%   |
| Scarborough     | 21        | 0.72%   |
| Sherbrooke      | 20        | 0.68%   |
| Moncton         | 20        | 0.68%   |
| Windsor         | 18        | 0.61%   |
| Gatineau        | 17        | 0.58%   |
| New Westminster | 16        | 0.55%   |
| Kingston        | 15        | 0.51%   |
| Barrie          | 15        | 0.51%   |
| Richmond Hill   | 14        | 0.48%   |
| Kelowna         | 14        | 0.48%   |
| Fredericton     | 14        | 0.48%   |
| Vernon          | 13        | 0.44%   |
| Levis           | 13        | 0.44%   |
| Richmond        | 12        | 0.41%   |
| Longueuil       | 12        | 0.41%   |
| Waterloo        | 11        | 0.38%   |
| Thunder Bay     | 11        | 0.38%   |
| Red Deer        | 11        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 520       | 720    | 15.08%  |
| WDC                         | 445       | 556    | 12.9%   |
| Seagate                     | 391       | 511    | 11.34%  |
| Toshiba                     | 271       | 335    | 7.86%   |
| Unknown                     | 229       | 299    | 6.64%   |
| Sandisk                     | 206       | 249    | 5.97%   |
| Kingston                    | 203       | 262    | 5.89%   |
| Intel                       | 137       | 198    | 3.97%   |
| SK hynix                    | 127       | 162    | 3.68%   |
| Hitachi                     | 115       | 130    | 3.33%   |
| HGST                        | 100       | 121    | 2.9%    |
| Crucial                     | 83        | 111    | 2.41%   |
| Micron Technology           | 70        | 93     | 2.03%   |
| A-DATA Technology           | 53        | 67     | 1.54%   |
| Apple                       | 47        | 53     | 1.36%   |
| Fujitsu                     | 38        | 55     | 1.1%    |
| KIOXIA                      | 34        | 40     | 0.99%   |
| SPCC                        | 24        | 37     | 0.7%    |
| LITEONIT                    | 22        | 25     | 0.64%   |
| LITEON                      | 18        | 20     | 0.52%   |
| Kingston Technology Company | 16        | 18     | 0.46%   |
| China                       | 15        | 16     | 0.43%   |
| Unknown                     | 14        | 14     | 0.41%   |
| Phison Electronics          | 12        | 15     | 0.35%   |
| PNY                         | 11        | 19     | 0.32%   |
| Silicon Motion              | 10        | 10     | 0.29%   |
| Phison                      | 10        | 11     | 0.29%   |
| Micron/Crucial Technology   | 9         | 10     | 0.26%   |
| OCZ                         | 8         | 8      | 0.23%   |
| JMicron Technology          | 8         | 10     | 0.23%   |
| Dogfish                     | 8         | 11     | 0.23%   |
| ASMT                        | 8         | 8      | 0.23%   |
| Patriot                     | 7         | 7      | 0.2%    |
| KingFast                    | 7         | 9      | 0.2%    |
| Team                        | 6         | 8      | 0.17%   |
| External                    | 6         | 8      | 0.17%   |
| Union Memory (Shenzhen)     | 5         | 5      | 0.14%   |
| Timetec                     | 5         | 9      | 0.14%   |
| SABRENT                     | 5         | 5      | 0.14%   |
| Mushkin                     | 5         | 8      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 48        | 1.34%   |
| Toshiba MQ01ABD100 1TB                             | 45        | 1.25%   |
| Unknown MMC Card  64GB                             | 43        | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB                     | 40        | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 39        | 1.09%   |
| Unknown MMC Card  32GB                             | 37        | 1.03%   |
| HGST HTS721010A9E630 1TB                           | 30        | 0.84%   |
| Samsung SSD 860 EVO 500GB                          | 26        | 0.72%   |
| Unknown MMC Card  16GB                             | 21        | 0.58%   |
| Seagate ST9500325AS 500GB                          | 21        | 0.58%   |
| Kingston SA400S37480G 480GB SSD                    | 21        | 0.58%   |
| Kingston SA400S37120G 120GB SSD                    | 21        | 0.58%   |
| Seagate ST1000LX015-1U7172 1TB                     | 20        | 0.56%   |
| Samsung SSD 860 EVO 1TB                            | 20        | 0.56%   |
| Samsung NVMe SSD Drive 512GB                       | 20        | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 19        | 0.53%   |
| Intel NVMe SSD Drive 512GB                         | 19        | 0.53%   |
| HGST HTS725050A7E630 500GB                         | 19        | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 18        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                    | 18        | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                           | 17        | 0.47%   |
| Toshiba MQ04ABF100 1TB                             | 17        | 0.47%   |
| Samsung SSD 850 EVO 250GB                          | 17        | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 17        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                   | 17        | 0.47%   |
| SK hynix NVMe SSD Drive 512GB                      | 16        | 0.45%   |
| Samsung SSD 860 EVO 250GB                          | 16        | 0.45%   |
| HGST HTS541010A9E680 1TB                           | 16        | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                        | 16        | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 15        | 0.42%   |
| Toshiba MQ01ABF050 500GB                           | 15        | 0.42%   |
| Seagate ST500LM021-1KJ152 500GB                    | 15        | 0.42%   |
| Samsung SSD 850 EVO 500GB                          | 15        | 0.42%   |
| Intel SSD 660P Series 1024GB                       | 15        | 0.42%   |
| Unknown MMC Card  128GB                            | 14        | 0.39%   |
| Seagate Expansion 1TB                              | 14        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                         | 14        | 0.39%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 14        | 0.39%   |
| Unknown                                            | 14        | 0.39%   |
| Seagate ST1000LM048-2E7172 1TB                     | 13        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 378       | 487    | 32.01%  |
| WDC                 | 290       | 347    | 24.56%  |
| Toshiba             | 211       | 268    | 17.87%  |
| Hitachi             | 115       | 130    | 9.74%   |
| HGST                | 100       | 121    | 8.47%   |
| Fujitsu             | 38        | 55     | 3.22%   |
| Samsung Electronics | 16        | 30     | 1.35%   |
| Unknown             | 8         | 9      | 0.68%   |
| Apple               | 8         | 8      | 0.68%   |
| External            | 6         | 8      | 0.51%   |
| Maxone              | 3         | 3      | 0.25%   |
| USB 3.0             | 1         | 2      | 0.08%   |
| SINTECHI            | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 2      | 0.08%   |
| Generic-            | 1         | 1      | 0.08%   |
| DAS                 | 1         | 5      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 253       | 346    | 23.64%  |
| Kingston            | 169       | 213    | 15.79%  |
| SanDisk             | 94        | 112    | 8.79%   |
| Crucial             | 77        | 101    | 7.2%    |
| WDC                 | 73        | 105    | 6.82%   |
| A-DATA Technology   | 46        | 59     | 4.3%    |
| Intel               | 45        | 61     | 4.21%   |
| Micron Technology   | 32        | 49     | 2.99%   |
| Apple               | 30        | 31     | 2.8%    |
| SPCC                | 23        | 36     | 2.15%   |
| LITEONIT            | 22        | 25     | 2.06%   |
| Toshiba             | 19        | 22     | 1.78%   |
| SK hynix            | 19        | 26     | 1.78%   |
| China               | 15        | 16     | 1.4%    |
| LITEON              | 14        | 15     | 1.31%   |
| PNY                 | 11        | 19     | 1.03%   |
| OCZ                 | 8         | 8      | 0.75%   |
| Dogfish             | 8         | 11     | 0.75%   |
| Patriot             | 7         | 7      | 0.65%   |
| Seagate             | 6         | 9      | 0.56%   |
| ASMT                | 6         | 6      | 0.56%   |
| Team                | 5         | 7      | 0.47%   |
| TO Exter            | 4         | 5      | 0.37%   |
| Timetec             | 4         | 8      | 0.37%   |
| SABRENT             | 4         | 4      | 0.37%   |
| Mushkin             | 4         | 7      | 0.37%   |
| KingSpec            | 4         | 6      | 0.37%   |
| Transcend           | 3         | 4      | 0.28%   |
| Super Talent        | 3         | 5      | 0.28%   |
| OWC                 | 3         | 7      | 0.28%   |
| NGFF                | 3         | 3      | 0.28%   |
| KingFast            | 3         | 3      | 0.28%   |
| KingDian            | 3         | 3      | 0.28%   |
| Corsair             | 3         | 3      | 0.28%   |
| Unknown             | 3         | 3      | 0.28%   |
| Zheino              | 2         | 2      | 0.19%   |
| WDC WDS             | 2         | 2      | 0.19%   |
| Vaseky              | 2         | 2      | 0.19%   |
| Kingchuxing         | 2         | 2      | 0.19%   |
| Hewlett-Packard     | 2         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1131      | 1480   | 34.8%   |
| SSD     | 975       | 1401   | 30%     |
| NVMe    | 868       | 1192   | 26.71%  |
| MMC     | 231       | 305    | 7.11%   |
| Unknown | 45        | 53     | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1908      | 2728   | 60.57%  |
| NVMe | 863       | 1185   | 27.4%   |
| MMC  | 231       | 305    | 7.33%   |
| SAS  | 148       | 213    | 4.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1362      | 1878   | 65.01%  |
| 0.51-1.0   | 650       | 882    | 31.03%  |
| 1.01-2.0   | 55        | 81     | 2.63%   |
| 3.01-4.0   | 14        | 18     | 0.67%   |
| 4.01-10.0  | 9         | 15     | 0.43%   |
| 2.01-3.0   | 4         | 6      | 0.19%   |
| 10.01-20.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 776       | 26.11%  |
| 101-250        | 775       | 26.08%  |
| 501-1000       | 499       | 16.79%  |
| 1-20           | 262       | 8.82%   |
| 51-100         | 193       | 6.49%   |
| 1001-2000      | 170       | 5.72%   |
| 21-50          | 114       | 3.84%   |
| Unknown        | 85        | 2.86%   |
| More than 3000 | 61        | 2.05%   |
| 2001-3000      | 37        | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1278      | 41.59%  |
| 21-50          | 581       | 18.91%  |
| 51-100         | 381       | 12.4%   |
| 101-250        | 366       | 11.91%  |
| 251-500        | 210       | 6.83%   |
| 501-1000       | 109       | 3.55%   |
| Unknown        | 85        | 2.77%   |
| 1001-2000      | 39        | 1.27%   |
| More than 3000 | 15        | 0.49%   |
| 2001-3000      | 9         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 10     | 5.14%   |
| Toshiba MQ01ABD100 1TB              | 6         | 8      | 3.43%   |
| HGST HTS541010A9E680 1TB            | 6         | 6      | 3.43%   |
| Seagate ST9500325AS 500GB           | 5         | 5      | 2.86%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 4      | 2.29%   |
| Seagate ST500LM000-1EJ162 500GB     | 4         | 4      | 2.29%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 2.29%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 2.29%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 1.71%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 2      | 1.14%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 1.14%   |
| Toshiba MK6465GSX 640GB             | 2         | 2      | 1.14%   |
| Toshiba MK3261GSYN 320GB            | 2         | 2      | 1.14%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 1.14%   |
| Toshiba MK2035GSS 200GB             | 2         | 2      | 1.14%   |
| Seagate ST9750420AS 752GB           | 2         | 2      | 1.14%   |
| Seagate ST9500420ASG 500GB          | 2         | 2      | 1.14%   |
| Seagate ST9500420AS 500GB           | 2         | 2      | 1.14%   |
| Seagate ST9320423AS 320GB           | 2         | 4      | 1.14%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 1.14%   |
| Seagate ST320LT020-9YG142 320GB     | 2         | 2      | 1.14%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 2         | 2      | 1.14%   |
| Seagate ST1000LM014-1EJ164 1TB      | 2         | 2      | 1.14%   |
| Hitachi HTS725050A9A364 500GB       | 2         | 2      | 1.14%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 2      | 1.14%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 2      | 1.14%   |
| HGST HTS725050A7E630 500GB          | 2         | 3      | 1.14%   |
| A-DATA Technology SX900 256GB SSD   | 2         | 2      | 1.14%   |
| WDC WD7500BPKT-60PK4T0 752GB        | 1         | 1      | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.57%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 0.57%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 0.57%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1      | 0.57%   |
| WDC WD2500BEVT-00ZCT0 250GB         | 1         | 1      | 0.57%   |
| WDC WD2500BEVS-75UST0 250GB         | 1         | 1      | 0.57%   |
| WDC WD1600BEVS-22RST0 160GB         | 1         | 1      | 0.57%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 0.57%   |
| WDC WD10JPVX-08JC3T5 1TB            | 1         | 1      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 55     | 29.71%  |
| Toshiba             | 27        | 29     | 15.43%  |
| Hitachi             | 20        | 20     | 11.43%  |
| WDC                 | 18        | 21     | 10.29%  |
| HGST                | 18        | 19     | 10.29%  |
| Samsung Electronics | 9         | 19     | 5.14%   |
| Intel               | 7         | 7      | 4%      |
| A-DATA Technology   | 4         | 4      | 2.29%   |
| Kingston            | 3         | 3      | 1.71%   |
| SanDisk             | 2         | 2      | 1.14%   |
| Fujitsu             | 2         | 10     | 1.14%   |
| Timetec             | 1         | 3      | 0.57%   |
| Super Talent        | 1         | 1      | 0.57%   |
| SK hynix            | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| Micron Technology   | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| LITEON              | 1         | 1      | 0.57%   |
| LaCie               | 1         | 1      | 0.57%   |
| KingSpec            | 1         | 1      | 0.57%   |
| Crucial             | 1         | 1      | 0.57%   |
| Corsair             | 1         | 1      | 0.57%   |
| ASMT                | 1         | 1      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 55     | 37.96%  |
| Toshiba             | 25        | 27     | 18.25%  |
| Hitachi             | 20        | 20     | 14.6%   |
| HGST                | 18        | 19     | 13.14%  |
| WDC                 | 16        | 18     | 11.68%  |
| Samsung Electronics | 2         | 10     | 1.46%   |
| Fujitsu             | 2         | 10     | 1.46%   |
| LaCie               | 1         | 1      | 0.73%   |
| Apple               | 1         | 1      | 0.73%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 135       | 161    | 78.03%  |
| SSD  | 32        | 36     | 18.5%   |
| NVMe | 6         | 7      | 3.47%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM160HC 160GB | 1         | 4      | 50%     |
| LITEON CA3-8D512 512GB            | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 4      | 50%     |
| LITEON              | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1781      | 2864   | 60.6%   |
| Works    | 984       | 1357   | 33.48%  |
| Malfunc  | 172       | 204    | 5.85%   |
| Failed   | 2         | 6      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1819      | 57.67%  |
| AMD                            | 421       | 13.35%  |
| Samsung Electronics            | 288       | 9.13%   |
| SanDisk                        | 183       | 5.8%    |
| SK hynix                       | 104       | 3.3%    |
| Kingston Technology Company    | 48        | 1.52%   |
| Toshiba America Info Systems   | 42        | 1.33%   |
| Nvidia                         | 40        | 1.27%   |
| Micron Technology              | 39        | 1.24%   |
| KIOXIA                         | 37        | 1.17%   |
| Phison Electronics             | 25        | 0.79%   |
| Micron/Crucial Technology      | 16        | 0.51%   |
| Silicon Motion                 | 13        | 0.41%   |
| Union Memory (Shenzhen)        | 11        | 0.35%   |
| ADATA Technology               | 11        | 0.35%   |
| Marvell Technology Group       | 7         | 0.22%   |
| Lite-On Technology             | 7         | 0.22%   |
| Apple                          | 7         | 0.22%   |
| Solid State Storage Technology | 6         | 0.19%   |
| Realtek Semiconductor          | 6         | 0.19%   |
| Lenovo                         | 4         | 0.13%   |
| ASMedia Technology             | 4         | 0.13%   |
| O2 Micro                       | 3         | 0.1%    |
| JMicron Technology             | 3         | 0.1%    |
| Shenzhen Longsys Electronics   | 2         | 0.06%   |
| Seagate Technology             | 2         | 0.06%   |
| INNOGRIT                       | 2         | 0.06%   |
| Yangtze Memory Technologies    | 1         | 0.03%   |
| OCZ Technology Group           | 1         | 0.03%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.03%   |
| Biwin Storage Technology       | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 346       | 10.16%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 217       | 6.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 181       | 5.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 169       | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 153       | 4.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 121       | 3.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 104       | 3.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 101       | 2.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 89        | 2.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 88        | 2.58%   |
| Intel Volume Management Device NVMe RAID Controller                              | 74        | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 69        | 2.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 68        | 2%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 68        | 2%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 58        | 1.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 57        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 55        | 1.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 52        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 50        | 1.47%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 44        | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 44        | 1.29%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 42        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 36        | 1.06%   |
| Intel SSD 660P Series                                                            | 33        | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 30        | 0.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 28        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 25        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 23        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 22        | 0.65%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 21        | 0.62%   |
| Nvidia MCP79 AHCI Controller                                                     | 20        | 0.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 20        | 0.59%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 19        | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 19        | 0.56%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 19        | 0.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 18        | 0.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 18        | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 18        | 0.53%   |
| SK hynix BC511 NVMe SSD                                                          | 17        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1897      | 58.53%  |
| NVMe | 864       | 26.66%  |
| RAID | 263       | 8.11%   |
| IDE  | 217       | 6.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 2192      | 78.91%  |
| AMD     | 582       | 20.95%  |
| ARM     | 3         | 0.11%   |
| Unknown | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 48        | 1.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 47        | 1.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 44        | 1.58%   |
| AMD Custom APU 0405                           | 41        | 1.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 39        | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 1.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 1.22%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 31        | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 29        | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 28        | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 28        | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 27        | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 25        | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 0.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 22        | 0.79%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 21        | 0.76%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 20        | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 20        | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 18        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 0.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 17        | 0.61%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 16        | 0.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 16        | 0.58%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 15        | 0.54%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 15        | 0.54%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 15        | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 15        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.5%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 14        | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 0.5%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 13        | 0.47%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 13        | 0.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 677       | 24.35%  |
| Intel Core i7           | 654       | 23.53%  |
| Other                   | 254       | 9.14%   |
| Intel Core i3           | 160       | 5.76%   |
| Intel Core 2 Duo        | 152       | 5.47%   |
| Intel Celeron           | 113       | 4.06%   |
| AMD Ryzen 7             | 104       | 3.74%   |
| AMD Ryzen 5             | 68        | 2.45%   |
| Intel Pentium           | 62        | 2.23%   |
| AMD A6                  | 58        | 2.09%   |
| Intel Atom              | 46        | 1.65%   |
| AMD A10                 | 39        | 1.4%    |
| AMD A4                  | 29        | 1.04%   |
| Intel Pentium Dual-Core | 28        | 1.01%   |
| Intel Pentium Dual      | 24        | 0.86%   |
| AMD Ryzen 3             | 23        | 0.83%   |
| Intel Genuine           | 21        | 0.76%   |
| AMD Ryzen 9             | 21        | 0.76%   |
| AMD A8                  | 21        | 0.76%   |
| Intel Core i9           | 16        | 0.58%   |
| Intel Core 2            | 15        | 0.54%   |
| AMD E                   | 15        | 0.54%   |
| AMD E2                  | 13        | 0.47%   |
| AMD E1                  | 12        | 0.43%   |
| AMD A12                 | 12        | 0.43%   |
| AMD Turion 64 X2 Mobile | 10        | 0.36%   |
| AMD Ryzen 5 PRO         | 10        | 0.36%   |
| Intel Pentium Silver    | 9         | 0.32%   |
| AMD Athlon X2           | 9         | 0.32%   |
| Intel Xeon              | 7         | 0.25%   |
| AMD Ryzen 7 PRO         | 7         | 0.25%   |
| AMD Athlon 64 X2        | 7         | 0.25%   |
| AMD Athlon              | 7         | 0.25%   |
| AMD Phenom II           | 6         | 0.22%   |
| Intel Celeron M         | 5         | 0.18%   |
| AMD Turion 64 Mobile    | 5         | 0.18%   |
| AMD C-50                | 5         | 0.18%   |
| AMD Athlon II           | 5         | 0.18%   |
| Intel Pentium M         | 4         | 0.14%   |
| Intel Core m3           | 3         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1443      | 51.87%  |
| 4       | 848       | 30.48%  |
| 6       | 180       | 6.47%   |
| 8       | 166       | 5.97%   |
| 1       | 69        | 2.48%   |
| 14      | 31        | 1.11%   |
| 12      | 17        | 0.61%   |
| 10      | 17        | 0.61%   |
| 16      | 5         | 0.18%   |
| 24      | 2         | 0.07%   |
| 3       | 2         | 0.07%   |
| 7       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2777      | 99.96%  |
| Unknown | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2027      | 72.84%  |
| 1       | 754       | 27.09%  |
| 12      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2711      | 97.38%  |
| 32-bit         | 39        | 1.4%    |
| Unknown        | 33        | 1.19%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 903       | 31.16%  |
| 0x306a9    | 164       | 5.66%   |
| 0x206a7    | 158       | 5.45%   |
| 0x40651    | 86        | 2.97%   |
| 0x1067a    | 86        | 2.97%   |
| 0x806ea    | 75        | 2.59%   |
| 0x906ea    | 73        | 2.52%   |
| 0x20655    | 71        | 2.45%   |
| 0x406e3    | 62        | 2.14%   |
| 0x806e9    | 60        | 2.07%   |
| 0x306c3    | 58        | 2%      |
| 0x306d4    | 54        | 1.86%   |
| 0x806ec    | 52        | 1.79%   |
| 0x6fd      | 49        | 1.69%   |
| 0xa0652    | 46        | 1.59%   |
| 0x20652    | 42        | 1.45%   |
| 0x806c1    | 39        | 1.35%   |
| 0x906e9    | 36        | 1.24%   |
| 0x06001119 | 32        | 1.1%    |
| 0x906a3    | 30        | 1.04%   |
| 0x0a50000c | 30        | 1.04%   |
| 0x30678    | 29        | 1%      |
| 0x506e3    | 27        | 0.93%   |
| 0x06006705 | 27        | 0.93%   |
| 0x08108102 | 25        | 0.86%   |
| 0x706e5    | 24        | 0.83%   |
| 0x10676    | 24        | 0.83%   |
| 0x406c4    | 23        | 0.79%   |
| 0x08108109 | 21        | 0.72%   |
| 0x05000119 | 21        | 0.72%   |
| 0x406c3    | 20        | 0.69%   |
| 0x08600104 | 18        | 0.62%   |
| 0x07030105 | 18        | 0.62%   |
| 0x03000027 | 18        | 0.62%   |
| 0x106e5    | 17        | 0.59%   |
| 0x806eb    | 16        | 0.55%   |
| 0x010000c8 | 14        | 0.48%   |
| 0x6e8      | 13        | 0.45%   |
| 0x506c9    | 13        | 0.45%   |
| 0x106c2    | 13        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 453       | 16.27%  |
| IvyBridge        | 218       | 7.83%   |
| Haswell          | 211       | 7.58%   |
| SandyBridge      | 205       | 7.36%   |
| Westmere         | 145       | 5.21%   |
| Penryn           | 139       | 4.99%   |
| Unknown          | 131       | 4.71%   |
| Skylake          | 125       | 4.49%   |
| Silvermont       | 98        | 3.52%   |
| Core             | 94        | 3.38%   |
| Broadwell        | 84        | 3.02%   |
| Excavator        | 82        | 2.95%   |
| TigerLake        | 77        | 2.77%   |
| CometLake        | 73        | 2.62%   |
| Zen+             | 67        | 2.41%   |
| Zen 2            | 58        | 2.08%   |
| Alderlake Hybrid | 57        | 2.05%   |
| Zen 3            | 53        | 1.9%    |
| IceLake          | 49        | 1.76%   |
| Piledriver       | 42        | 1.51%   |
| Goldmont plus    | 35        | 1.26%   |
| Bobcat           | 34        | 1.22%   |
| Puma             | 32        | 1.15%   |
| K8 Hammer        | 28        | 1.01%   |
| P6               | 26        | 0.93%   |
| K10 Llano        | 24        | 0.86%   |
| Zen              | 23        | 0.83%   |
| Nehalem          | 23        | 0.83%   |
| Bonnell          | 23        | 0.83%   |
| K10              | 20        | 0.72%   |
| Jaguar           | 18        | 0.65%   |
| Goldmont         | 16        | 0.57%   |
| K8 & K10 hybrid  | 12        | 0.43%   |
| Steamroller      | 4         | 0.14%   |
| Tremont          | 3         | 0.11%   |
| NetBurst         | 1         | 0.04%   |
| Gracemont        | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1965      | 58.2%   |
| Nvidia | 711       | 21.06%  |
| AMD    | 700       | 20.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 191       | 5.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 184       | 5.25%   |
| Intel UHD Graphics 620                                                                   | 119       | 3.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 118       | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 114       | 3.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 102       | 2.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 96        | 2.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 79        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 78        | 2.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 73        | 2.08%   |
| Intel HD Graphics 620                                                                    | 73        | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 73        | 2.08%   |
| Intel HD Graphics 5500                                                                   | 70        | 2%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 61        | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 60        | 1.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 57        | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 53        | 1.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 53        | 1.51%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 52        | 1.48%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 1.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 48        | 1.37%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 41        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 37        | 1.06%   |
| Intel HD Graphics 630                                                                    | 37        | 1.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37        | 1.06%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 36        | 1.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 33        | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 32        | 0.91%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 32        | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 31        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 0.88%   |
| Intel HD Graphics 530                                                                    | 27        | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 27        | 0.77%   |
| AMD Lucienne                                                                             | 23        | 0.66%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 22        | 0.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 21        | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 21        | 0.6%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 20        | 0.57%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1417      | 50.77%  |
| 1 x AMD            | 541       | 19.38%  |
| Intel + Nvidia     | 470       | 16.84%  |
| 1 x Nvidia         | 179       | 6.41%   |
| Intel + AMD        | 65        | 2.33%   |
| AMD + Nvidia       | 59        | 2.11%   |
| 2 x AMD            | 36        | 1.29%   |
| Other              | 10        | 0.36%   |
| 2 x Intel          | 8         | 0.29%   |
| 2 x Nvidia         | 5         | 0.18%   |
| Intel + 2 x Nvidia | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2387      | 84.59%  |
| Proprietary | 363       | 12.86%  |
| Unknown     | 72        | 2.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1882      | 65.71%  |
| 0.01-0.5   | 386       | 13.48%  |
| 1.01-2.0   | 239       | 8.34%   |
| 0.51-1.0   | 130       | 4.54%   |
| 3.01-4.0   | 126       | 4.4%    |
| 7.01-8.0   | 43        | 1.5%    |
| 5.01-6.0   | 42        | 1.47%   |
| 2.01-3.0   | 8         | 0.28%   |
| 8.01-16.0  | 8         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 601       | 18.74%  |
| LG Display              | 434       | 13.53%  |
| Samsung Electronics     | 374       | 11.66%  |
| Chimei Innolux          | 336       | 10.48%  |
| BOE                     | 305       | 9.51%   |
| Sharp                   | 138       | 4.3%    |
| Apple                   | 116       | 3.62%   |
| Lenovo                  | 98        | 3.06%   |
| Dell                    | 93        | 2.9%    |
| Chi Mei Optoelectronics | 82        | 2.56%   |
| Goldstar                | 76        | 2.37%   |
| PANDA                   | 50        | 1.56%   |
| Hewlett-Packard         | 46        | 1.43%   |
| Acer                    | 42        | 1.31%   |
| LG Philips              | 32        | 1%      |
| ASUSTek Computer        | 32        | 1%      |
| BenQ                    | 31        | 0.97%   |
| Ancor Communications    | 28        | 0.87%   |
| Valve                   | 26        | 0.81%   |
| Toshiba                 | 25        | 0.78%   |
| InfoVision              | 23        | 0.72%   |
| Sony                    | 17        | 0.53%   |
| ViewSonic               | 16        | 0.5%    |
| CSO                     | 12        | 0.37%   |
| Philips                 | 11        | 0.34%   |
| Panasonic               | 11        | 0.34%   |
| AOC                     | 11        | 0.34%   |
| TMX                     | 10        | 0.31%   |
| Quanta Display          | 9         | 0.28%   |
| HannStar                | 9         | 0.28%   |
| HKC                     | 7         | 0.22%   |
| CPT                     | 7         | 0.22%   |
| Seiko/Epson             | 6         | 0.19%   |
| Insignia                | 6         | 0.19%   |
| LGD                     | 5         | 0.16%   |
| IBM                     | 5         | 0.16%   |
| MSI                     | 4         | 0.12%   |
| Gigabyte Technology     | 4         | 0.12%   |
| Unknown                 | 3         | 0.09%   |
| SANYO                   | 3         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 34        | 1.04%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 32        | 0.98%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 26        | 0.8%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.64%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 20        | 0.61%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 19        | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 19        | 0.58%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 17        | 0.52%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 17        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 17        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 17        | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.43%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                  | 13        | 0.4%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 13        | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 13        | 0.4%    |
| Toshiba TSB-TV TSB0206 1360x768 930x520mm 41.9-inch                      | 12        | 0.37%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 12        | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 12        | 0.37%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 11        | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 11        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 11        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 11        | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 10        | 0.31%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 10        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.31%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 10        | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.31%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 10        | 0.31%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 9         | 0.28%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 9         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch            | 9         | 0.28%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 9         | 0.28%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 8         | 0.25%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 8         | 0.25%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 8         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1078      | 35.57%  |
| 1366x768 (WXGA)    | 911       | 30.06%  |
| 1600x900 (HD+)     | 175       | 5.77%   |
| 1280x800 (WXGA)    | 163       | 5.38%   |
| 3840x2160 (4K)     | 134       | 4.42%   |
| 2560x1440 (QHD)    | 85        | 2.8%    |
| 1920x1200 (WUXGA)  | 72        | 2.38%   |
| 1440x900 (WXGA+)   | 70        | 2.31%   |
| 1680x1050 (WSXGA+) | 60        | 1.98%   |
| 2880x1800          | 36        | 1.19%   |
| 800x1280           | 28        | 0.92%   |
| 2560x1600          | 22        | 0.73%   |
| 3440x1440          | 17        | 0.56%   |
| 1280x1024 (SXGA)   | 17        | 0.56%   |
| 3840x2400          | 15        | 0.49%   |
| 1024x600           | 15        | 0.49%   |
| 3200x1800 (QHD+)   | 14        | 0.46%   |
| 2560x1080          | 14        | 0.46%   |
| 1024x768 (XGA)     | 12        | 0.4%    |
| 2256x1504          | 10        | 0.33%   |
| 1920x540           | 10        | 0.33%   |
| 1360x768           | 10        | 0.33%   |
| 3200x2000          | 7         | 0.23%   |
| Unknown            | 7         | 0.23%   |
| 3456x2160          | 5         | 0.16%   |
| 1920x1280          | 4         | 0.13%   |
| 3840x1080          | 3         | 0.1%    |
| 3000x2000          | 3         | 0.1%    |
| 2560x1700          | 3         | 0.1%    |
| 1680x945           | 3         | 0.1%    |
| 3840x1200          | 2         | 0.07%   |
| 3840x1100          | 2         | 0.07%   |
| 3072x1920          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 2160x1440          | 2         | 0.07%   |
| 2160x1350          | 2         | 0.07%   |
| 1600x1200          | 2         | 0.07%   |
| 1280x768           | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 1024x576           | 2         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1339      | 41.78%  |
| 13      | 419       | 13.07%  |
| 14      | 366       | 11.42%  |
| 17      | 222       | 6.93%   |
| 27      | 106       | 3.31%   |
| 24      | 96        | 3%      |
| 23      | 70        | 2.18%   |
| 21      | 68        | 2.12%   |
| 11      | 61        | 1.9%    |
| 12      | 57        | 1.78%   |
| Unknown | 53        | 1.65%   |
| 31      | 37        | 1.15%   |
| 34      | 32        | 1%      |
| 22      | 30        | 0.94%   |
| 16      | 26        | 0.81%   |
| 7       | 26        | 0.81%   |
| 18      | 24        | 0.75%   |
| 20      | 21        | 0.66%   |
| 19      | 20        | 0.62%   |
| 10      | 16        | 0.5%    |
| 84      | 14        | 0.44%   |
| 72      | 13        | 0.41%   |
| 74      | 12        | 0.37%   |
| 54      | 11        | 0.34%   |
| 32      | 10        | 0.31%   |
| 25      | 8         | 0.25%   |
| 40      | 6         | 0.19%   |
| 86      | 5         | 0.16%   |
| 48      | 5         | 0.16%   |
| 37      | 5         | 0.16%   |
| 43      | 3         | 0.09%   |
| 42      | 3         | 0.09%   |
| 28      | 3         | 0.09%   |
| 26      | 3         | 0.09%   |
| 8       | 3         | 0.09%   |
| 39      | 2         | 0.06%   |
| 3       | 2         | 0.06%   |
| 69      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 58      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1860      | 58.62%  |
| 201-300     | 354       | 11.16%  |
| 351-400     | 291       | 9.17%   |
| 501-600     | 252       | 7.94%   |
| 401-500     | 154       | 4.85%   |
| Unknown     | 53        | 1.67%   |
| 601-700     | 52        | 1.64%   |
| 701-800     | 42        | 1.32%   |
| 1501-2000   | 39        | 1.23%   |
| 1-100       | 28        | 0.88%   |
| 1001-1500   | 27        | 0.85%   |
| 801-900     | 13        | 0.41%   |
| 901-1000    | 5         | 0.16%   |
| 101-200     | 3         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2191      | 77.83%  |
| 16/10   | 448       | 15.91%  |
| 3/2     | 34        | 1.21%   |
| 21/9    | 32        | 1.14%   |
| Unknown | 30        | 1.07%   |
| 0.67    | 26        | 0.92%   |
| 5/4     | 18        | 0.64%   |
| 4/3     | 16        | 0.57%   |
| 0.56    | 5         | 0.18%   |
| 6/5     | 4         | 0.14%   |
| 32/9    | 3         | 0.11%   |
| 3.40    | 2         | 0.07%   |
| 1.96    | 2         | 0.07%   |
| 3.73    | 1         | 0.04%   |
| 3.33    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1321      | 41.44%  |
| 81-90          | 621       | 19.48%  |
| 201-250        | 213       | 6.68%   |
| 121-130        | 185       | 5.8%    |
| 71-80          | 150       | 4.71%   |
| 301-350        | 107       | 3.36%   |
| 351-500        | 80        | 2.51%   |
| 51-60          | 63        | 1.98%   |
| 151-200        | 61        | 1.91%   |
| More than 1000 | 60        | 1.88%   |
| 61-70          | 54        | 1.69%   |
| Unknown        | 53        | 1.66%   |
| 111-120        | 38        | 1.19%   |
| 131-140        | 34        | 1.07%   |
| 1-40           | 31        | 0.97%   |
| 251-300        | 31        | 0.97%   |
| 141-150        | 30        | 0.94%   |
| 501-1000       | 25        | 0.78%   |
| 41-50          | 16        | 0.5%    |
| 91-100         | 15        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1070      | 34.35%  |
| 101-120       | 1021      | 32.78%  |
| 51-100        | 568       | 18.23%  |
| 161-240       | 219       | 7.03%   |
| More than 240 | 121       | 3.88%   |
| 1-50          | 63        | 2.02%   |
| Unknown       | 53        | 1.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2234      | 78.41%  |
| 2     | 474       | 16.64%  |
| 3     | 73        | 2.56%   |
| 0     | 66        | 2.32%   |
| 4     | 2         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1511      | 35.09%  |
| Realtek Semiconductor           | 1252      | 29.08%  |
| Qualcomm Atheros                | 627       | 14.56%  |
| Broadcom                        | 342       | 7.94%   |
| Broadcom Limited                | 115       | 2.67%   |
| MediaTek                        | 62        | 1.44%   |
| Marvell Technology Group        | 51        | 1.18%   |
| ASIX Electronics                | 46        | 1.07%   |
| Nvidia                          | 33        | 0.77%   |
| TP-Link                         | 30        | 0.7%    |
| Ralink                          | 27        | 0.63%   |
| Ralink Technology               | 20        | 0.46%   |
| Linksys                         | 19        | 0.44%   |
| D-Link                          | 17        | 0.39%   |
| DisplayLink                     | 15        | 0.35%   |
| Lenovo                          | 14        | 0.33%   |
| Samsung Electronics             | 13        | 0.3%    |
| ASUSTek Computer                | 12        | 0.28%   |
| Qualcomm                        | 11        | 0.26%   |
| Sierra Wireless                 | 10        | 0.23%   |
| Qualcomm Atheros Communications | 10        | 0.23%   |
| Google                          | 7         | 0.16%   |
| NetGear                         | 6         | 0.14%   |
| AMD                             | 6         | 0.14%   |
| Hewlett-Packard                 | 4         | 0.09%   |
| Dell                            | 4         | 0.09%   |
| D-Link System                   | 4         | 0.09%   |
| Apple                           | 4         | 0.09%   |
| Research In Motion              | 3         | 0.07%   |
| JMicron Technology              | 3         | 0.07%   |
| Xiaomi                          | 2         | 0.05%   |
| U-Blox                          | 2         | 0.05%   |
| TRENDnet                        | 2         | 0.05%   |
| Microsoft                       | 2         | 0.05%   |
| LG Electronics                  | 2         | 0.05%   |
| Edimax Technology               | 2         | 0.05%   |
| Aquantia                        | 2         | 0.05%   |
| STMicroelectronics              | 1         | 0.02%   |
| Panasonic (Matsushita)          | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 678       | 12.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 259       | 4.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 3.1%    |
| Intel Wireless 8265 / 8275                                        | 132       | 2.48%   |
| Intel Wireless 7260                                               | 111       | 2.09%   |
| Intel Wi-Fi 6 AX200                                               | 110       | 2.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 103       | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 103       | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 93        | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 92        | 1.73%   |
| Intel Wireless 7265                                               | 89        | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 85        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 81        | 1.52%   |
| Intel Wireless 8260                                               | 77        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 68        | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 66        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 58        | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 56        | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 56        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 55        | 1.03%   |
| Intel Centrino Ultimate-N 6300                                    | 52        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 49        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 48        | 0.9%    |
| Intel Ethernet Connection I218-LM                                 | 46        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 44        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 44        | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 43        | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 40        | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 35        | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 34        | 0.64%   |
| Intel Wireless 3165                                               | 34        | 0.64%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 34        | 0.64%   |
| Intel Centrino Advanced-N 6200                                    | 33        | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 33        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 32        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 32        | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 32        | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 30        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1429      | 49.22%  |
| Qualcomm Atheros                      | 516       | 17.77%  |
| Realtek Semiconductor                 | 389       | 13.4%   |
| Broadcom                              | 268       | 9.23%   |
| Broadcom Limited                      | 73        | 2.51%   |
| MediaTek                              | 59        | 2.03%   |
| TP-Link                               | 28        | 0.96%   |
| Ralink                                | 27        | 0.93%   |
| Ralink Technology                     | 20        | 0.69%   |
| Linksys                               | 17        | 0.59%   |
| D-Link                                | 16        | 0.55%   |
| ASUSTek Computer                      | 12        | 0.41%   |
| Sierra Wireless                       | 10        | 0.34%   |
| Qualcomm Atheros Communications       | 10        | 0.34%   |
| Qualcomm                              | 9         | 0.31%   |
| NetGear                               | 6         | 0.21%   |
| D-Link System                         | 4         | 0.14%   |
| TRENDnet                              | 2         | 0.07%   |
| Edimax Technology                     | 2         | 0.07%   |
| Dell                                  | 2         | 0.07%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Microsoft                             | 1         | 0.03%   |
| Marvell Technology Group              | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 132       | 4.51%   |
| Intel Wireless 7260                                                     | 111       | 3.79%   |
| Intel Wi-Fi 6 AX200                                                     | 110       | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 103       | 3.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 93        | 3.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 92        | 3.14%   |
| Intel Wireless 7265                                                     | 89        | 3.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 85        | 2.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 81        | 2.77%   |
| Intel Wireless 8260                                                     | 77        | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 68        | 2.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 66        | 2.25%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 58        | 1.98%   |
| Intel Wi-Fi 6 AX201                                                     | 56        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 55        | 1.88%   |
| Intel Centrino Ultimate-N 6300                                          | 52        | 1.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 48        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 44        | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 43        | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 40        | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 34        | 1.16%   |
| Intel Wireless 3165                                                     | 34        | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 34        | 1.16%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 33        | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 32        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 32        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 30        | 1.02%   |
| Intel Centrino Wireless-N 2230                                          | 30        | 1.02%   |
| Intel Centrino Advanced-N 6235                                          | 30        | 1.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 30        | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 29        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 27        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 26        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 26        | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 25        | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 25        | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 1073      | 46.01%  |
| Intel                    | 657       | 28.17%  |
| Qualcomm Atheros         | 189       | 8.1%    |
| Broadcom                 | 154       | 6.6%    |
| Marvell Technology Group | 50        | 2.14%   |
| Broadcom Limited         | 47        | 2.02%   |
| ASIX Electronics         | 46        | 1.97%   |
| Nvidia                   | 32        | 1.37%   |
| DisplayLink              | 15        | 0.64%   |
| Lenovo                   | 14        | 0.6%    |
| Samsung Electronics      | 13        | 0.56%   |
| Google                   | 7         | 0.3%    |
| Hewlett-Packard          | 4         | 0.17%   |
| Apple                    | 4         | 0.17%   |
| TP-Link                  | 3         | 0.13%   |
| Research In Motion       | 3         | 0.13%   |
| JMicron Technology       | 3         | 0.13%   |
| Xiaomi                   | 2         | 0.09%   |
| Qualcomm                 | 2         | 0.09%   |
| MediaTek                 | 2         | 0.09%   |
| Linksys                  | 2         | 0.09%   |
| LG Electronics           | 2         | 0.09%   |
| Aquantia                 | 2         | 0.09%   |
| Motorola PCS             | 1         | 0.04%   |
| Microsoft                | 1         | 0.04%   |
| HTC (High Tech Computer) | 1         | 0.04%   |
| HMD Global               | 1         | 0.04%   |
| D-Link                   | 1         | 0.04%   |
| Attansic Technology      | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 678       | 28.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 259       | 10.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 6.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 103       | 4.36%   |
| Intel 82577LM Gigabit Network Connection                          | 56        | 2.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 49        | 2.07%   |
| Intel Ethernet Connection I218-LM                                 | 46        | 1.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 43        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 1.69%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 1.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 35        | 1.48%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 1.18%   |
| Intel 82567LM Gigabit Network Connection                          | 28        | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                             | 27        | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.97%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 22        | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19        | 0.8%    |
| Nvidia MCP79 Ethernet                                             | 19        | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 17        | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 17        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 16        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 15        | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 14        | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 12        | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.42%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 10        | 0.42%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 10        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 9         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 9         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2725      | 54.63%  |
| Ethernet | 2235      | 44.81%  |
| Modem    | 25        | 0.5%    |
| Unknown  | 3         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2306      | 77.38%  |
| Ethernet | 674       | 22.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2047      | 73.55%  |
| 1     | 673       | 24.18%  |
| 0     | 38        | 1.37%   |
| 3     | 25        | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2349      | 83.21%  |
| Yes  | 474       | 16.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1022      | 47.85%  |
| Broadcom                        | 161       | 7.54%   |
| Realtek Semiconductor           | 160       | 7.49%   |
| Qualcomm Atheros Communications | 158       | 7.4%    |
| IMC Networks                    | 141       | 6.6%    |
| Lite-On Technology              | 116       | 5.43%   |
| Apple                           | 106       | 4.96%   |
| Foxconn / Hon Hai               | 91        | 4.26%   |
| Dell                            | 40        | 1.87%   |
| Hewlett-Packard                 | 31        | 1.45%   |
| Cambridge Silicon Radio         | 31        | 1.45%   |
| Ralink                          | 15        | 0.7%    |
| Toshiba                         | 14        | 0.66%   |
| ASUSTek Computer                | 14        | 0.66%   |
| Alps Electric                   | 8         | 0.37%   |
| USI                             | 3         | 0.14%   |
| Realtek                         | 3         | 0.14%   |
| MediaTek                        | 3         | 0.14%   |
| TP-Link                         | 2         | 0.09%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| SINO WEALTH                     | 2         | 0.09%   |
| Logitech                        | 2         | 0.09%   |
| Dynex                           | 2         | 0.09%   |
| Ralink Technology               | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| Primax Electronics              | 1         | 0.05%   |
| Marvell Semiconductor           | 1         | 0.05%   |
| Kensington                      | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Foxconn International           | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 447       | 20.87%  |
| Intel AX201 Bluetooth                                                               | 171       | 7.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 114       | 5.32%   |
| Realtek Bluetooth Radio                                                             | 111       | 5.18%   |
| Intel AX200 Bluetooth                                                               | 107       | 5%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 84        | 3.92%   |
| IMC Networks Bluetooth Radio                                                        | 74        | 3.45%   |
| Intel Bluetooth Device                                                              | 71        | 3.31%   |
| Apple Bluetooth Host Controller                                                     | 67        | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 56        | 2.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 52        | 2.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 41        | 1.91%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 36        | 1.68%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 35        | 1.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 31        | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 29        | 1.35%   |
| Apple Bluetooth USB Host Controller                                                 | 29        | 1.35%   |
| Intel AX210 Bluetooth                                                               | 26        | 1.21%   |
| IMC Networks Wireless_Device                                                        | 25        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 24        | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 22        | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 21        | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 18        | 0.84%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 0.84%   |
| Broadcom HP Portable SoftSailing                                                    | 18        | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 16        | 0.75%   |
| Ralink RT3290 Bluetooth                                                             | 15        | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 15        | 0.7%    |
| IMC Networks Bluetooth Device                                                       | 14        | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 14        | 0.65%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 14        | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 13        | 0.61%   |
| Dell DW375 Bluetooth Module                                                         | 13        | 0.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 12        | 0.56%   |
| IMC Networks BCM20702A0                                                             | 11        | 0.51%   |
| Lite-On Bluetooth Device                                                            | 10        | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 9         | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 9         | 0.42%   |
| Realtek RTL8821A Bluetooth                                                          | 8         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2139      | 62.14%  |
| AMD                                  | 647       | 18.8%   |
| Nvidia                               | 422       | 12.26%  |
| C-Media Electronics                  | 27        | 0.78%   |
| Realtek Semiconductor                | 23        | 0.67%   |
| Logitech                             | 22        | 0.64%   |
| GN Netcom                            | 15        | 0.44%   |
| Lenovo                               | 13        | 0.38%   |
| Plantronics                          | 11        | 0.32%   |
| SteelSeries ApS                      | 6         | 0.17%   |
| JMTek                                | 6         | 0.17%   |
| Focusrite-Novation                   | 6         | 0.17%   |
| Razer USA                            | 5         | 0.15%   |
| Kingston Technology                  | 5         | 0.15%   |
| Hewlett-Packard                      | 5         | 0.15%   |
| Creative Technology                  | 5         | 0.15%   |
| Blue Microphones                     | 5         | 0.15%   |
| Sony                                 | 4         | 0.12%   |
| Sennheiser Communications            | 4         | 0.12%   |
| No brand                             | 4         | 0.12%   |
| Generalplus Technology               | 4         | 0.12%   |
| Corsair                              | 4         | 0.12%   |
| Apple                                | 4         | 0.12%   |
| Texas Instruments                    | 3         | 0.09%   |
| Dell                                 | 3         | 0.09%   |
| ASUSTek Computer                     | 3         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.06%   |
| Synaptics                            | 2         | 0.06%   |
| Samson Technologies                  | 2         | 0.06%   |
| Panasonic (Matsushita)               | 2         | 0.06%   |
| Native Instruments                   | 2         | 0.06%   |
| Jieli Technology                     | 2         | 0.06%   |
| DCMT Technology                      | 2         | 0.06%   |
| Audio-Technica                       | 2         | 0.06%   |
| XMOS                                 | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Shure                                | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| RODE Microphones                     | 1         | 0.03%   |
| RME                                  | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 287       | 6.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 245       | 5.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 239       | 5.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 177       | 4.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 167       | 3.99%   |
| AMD FCH Azalia Controller                                                                         | 131       | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 120       | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 118       | 2.82%   |
| Intel 8 Series HD Audio Controller                                                                | 118       | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 117       | 2.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 109       | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 93        | 2.22%   |
| Intel Broadwell-U Audio Controller                                                                | 84        | 2%      |
| AMD Kabini HDMI/DP Audio                                                                          | 82        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 81        | 1.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 80        | 1.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 80        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 79        | 1.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 77        | 1.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 71        | 1.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 64        | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 59        | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 58        | 1.38%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 57        | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 56        | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 51        | 1.22%   |
| AMD High Definition Audio Controller                                                              | 50        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 47        | 1.12%   |
| Intel CM238 HD Audio Controller                                                                   | 42        | 1%      |
| AMD Trinity HDMI Audio Controller                                                                 | 42        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 41        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 38        | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 38        | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 36        | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 35        | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 34        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 34        | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 33        | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 31        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 30        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 475       | 27.42%  |
| SK hynix                                         | 429       | 24.77%  |
| Micron Technology                                | 224       | 12.93%  |
| Kingston                                         | 134       | 7.74%   |
| Unknown                                          | 128       | 7.39%   |
| Crucial                                          | 71        | 4.1%    |
| Elpida                                           | 36        | 2.08%   |
| G.Skill                                          | 34        | 1.96%   |
| Nanya Technology                                 | 31        | 1.79%   |
| Ramaxel Technology                               | 30        | 1.73%   |
| Corsair                                          | 24        | 1.39%   |
| A-DATA Technology                                | 24        | 1.39%   |
| Unknown                                          | 14        | 0.81%   |
| Patriot                                          | 8         | 0.46%   |
| Timetec                                          | 6         | 0.35%   |
| ff                                               | 6         | 0.35%   |
| 4ea5                                             | 6         | 0.35%   |
| Toshiba                                          | 5         | 0.29%   |
| Goldkey                                          | 5         | 0.29%   |
| Unknown (ABCD)                                   | 3         | 0.17%   |
| PNY                                              | 3         | 0.17%   |
| Neo Forza                                        | 3         | 0.17%   |
| ASint Technology                                 | 3         | 0.17%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.12%   |
| Team                                             | 2         | 0.12%   |
| SHARETRONIC                                      | 2         | 0.12%   |
| fef5                                             | 2         | 0.12%   |
| CSX                                              | 2         | 0.12%   |
| Axiom                                            | 2         | 0.12%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.06%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.06%   |
| Unknown (0x48594D503132355336344350382D53362020) | 1         | 0.06%   |
| Unknown (0x0C26)                                 | 1         | 0.06%   |
| Unknown (0x0080)                                 | 1         | 0.06%   |
| Unknown (08AE)                                   | 1         | 0.06%   |
| Unknown (000080B30080)                           | 1         | 0.06%   |
| Unifosa                                          | 1         | 0.06%   |
| Transcend                                        | 1         | 0.06%   |
| Sesame                                           | 1         | 0.06%   |
| Qumo                                             | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 33        | 1.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 1.2%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 1.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 17        | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.76%   |
| Unknown                                                          | 14        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.71%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.71%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 12        | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 11        | 0.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 11        | 0.6%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 11        | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 10        | 0.55%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 9         | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.49%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 9         | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.49%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 9         | 0.49%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 595       | 41.46%  |
| DDR3    | 533       | 37.14%  |
| LPDDR4  | 76        | 5.3%    |
| LPDDR3  | 66        | 4.6%    |
| DDR2    | 65        | 4.53%   |
| DDR5    | 30        | 2.09%   |
| SDRAM   | 26        | 1.81%   |
| Unknown | 17        | 1.18%   |
| LPDDR5  | 15        | 1.05%   |
| DDR     | 10        | 0.7%    |
| DRAM    | 2         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1255      | 87.7%   |
| Row Of Chips    | 136       | 9.5%    |
| Chip            | 18        | 1.26%   |
| Unknown         | 16        | 1.12%   |
| DIMM            | 5         | 0.35%   |
| Proprietary Car | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 630       | 39.13%  |
| 4096  | 466       | 28.94%  |
| 16384 | 212       | 13.17%  |
| 2048  | 205       | 12.73%  |
| 1024  | 54        | 3.35%   |
| 32768 | 36        | 2.24%   |
| 512   | 4         | 0.25%   |
| 256   | 2         | 0.12%   |
| 65536 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 359       | 22.98%  |
| 2667    | 279       | 17.86%  |
| 3200    | 245       | 15.69%  |
| 2400    | 114       | 7.3%    |
| 2133    | 90        | 5.76%   |
| 1334    | 84        | 5.38%   |
| 1333    | 61        | 3.91%   |
| 667     | 36        | 2.3%    |
| 1067    | 35        | 2.24%   |
| 4267    | 32        | 2.05%   |
| 4800    | 29        | 1.86%   |
| 1867    | 26        | 1.66%   |
| Unknown | 26        | 1.66%   |
| 3266    | 19        | 1.22%   |
| 6400    | 17        | 1.09%   |
| 4199    | 15        | 0.96%   |
| 4266    | 14        | 0.9%    |
| 1066    | 14        | 0.9%    |
| 8400    | 13        | 0.83%   |
| 800     | 13        | 0.83%   |
| 975     | 10        | 0.64%   |
| 533     | 9         | 0.58%   |
| 3733    | 6         | 0.38%   |
| 2048    | 4         | 0.26%   |
| 1639    | 3         | 0.19%   |
| 400     | 2         | 0.13%   |
| 6000    | 1         | 0.06%   |
| 2933    | 1         | 0.06%   |
| 2666    | 1         | 0.06%   |
| 1866    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 933     | 1         | 0.06%   |
| 333     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 10        | 30.3%   |
| Hewlett-Packard     | 9         | 27.27%  |
| Samsung Electronics | 6         | 18.18%  |
| Canon               | 5         | 15.15%  |
| Xerox               | 1         | 3.03%   |
| QinHeng Electronics | 1         | 3.03%   |
| Prolific Technology | 1         | 3.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung M2070 Series                            | 2         | 5.71%   |
| HP OfficeJet 3830 series                        | 2         | 5.71%   |
| Canon PIXMA MG2900 Series                       | 2         | 5.71%   |
| Brother Printer                                 | 2         | 5.71%   |
| Xerox B210                                      | 1         | 2.86%   |
| Samsung ML-2510 Series                          | 1         | 2.86%   |
| Samsung M267x 287x Series                       | 1         | 2.86%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 2.86%   |
| Samsung M2020 Series                            | 1         | 2.86%   |
| QinHeng CH340S                                  | 1         | 2.86%   |
| Prolific PL2305 Parallel Port                   | 1         | 2.86%   |
| HP LaserJet Professional P1102w                 | 1         | 2.86%   |
| HP LaserJet 1160 series                         | 1         | 2.86%   |
| HP LaserJet 1020                                | 1         | 2.86%   |
| HP LaserJet 1018                                | 1         | 2.86%   |
| HP ENVY 5000 series                             | 1         | 2.86%   |
| HP ENVY 4520 series                             | 1         | 2.86%   |
| HP DeskJet 2600 series                          | 1         | 2.86%   |
| Canon MG2100 series                             | 1         | 2.86%   |
| Canon MF3010                                    | 1         | 2.86%   |
| Canon G3060 series                              | 1         | 2.86%   |
| Brother MFC-L2730DW series                      | 1         | 2.86%   |
| Brother MFC-L2717DW                             | 1         | 2.86%   |
| Brother MFC-J6945DW                             | 1         | 2.86%   |
| Brother MFC-J480DW                              | 1         | 2.86%   |
| Brother MFC-9330CDW                             | 1         | 2.86%   |
| Brother HL-L2390DW                              | 1         | 2.86%   |
| Brother HL-2270DW Laser Printer                 | 1         | 2.86%   |
| Brother HL-2240 series                          | 1         | 2.86%   |
| Brother HL-2170W series                         | 1         | 2.86%   |
| Brother DCP-L2550DW series                      | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 85.71%  |
| AGFA-Gevaert NV | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220            | 2         | 28.57%  |
| Canon CanoScan LiDE 120            | 2         | 28.57%  |
| Canon CanoScan LiDE 700F           | 1         | 14.29%  |
| Canon CanoScan 4200F               | 1         | 14.29%  |
| AGFA-Gevaert NV SnapScan 1212U (?) | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 555       | 23.22%  |
| Microdia                               | 260       | 10.88%  |
| IMC Networks                           | 255       | 10.67%  |
| Realtek Semiconductor                  | 187       | 7.82%   |
| Bison Electronics                      | 153       | 6.4%    |
| Sunplus Innovation Technology          | 150       | 6.28%   |
| Quanta                                 | 109       | 4.56%   |
| Suyin                                  | 100       | 4.18%   |
| Apple                                  | 100       | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 67        | 2.8%    |
| Logitech                               | 53        | 2.22%   |
| Lite-On Technology                     | 44        | 1.84%   |
| Acer                                   | 43        | 1.8%    |
| Ricoh                                  | 32        | 1.34%   |
| Syntek                                 | 31        | 1.3%    |
| Silicon Motion                         | 30        | 1.26%   |
| Luxvisions Innotech Limited            | 30        | 1.26%   |
| Lenovo                                 | 25        | 1.05%   |
| Importek                               | 21        | 0.88%   |
| Samsung Electronics                    | 19        | 0.79%   |
| Sonix Technology                       | 16        | 0.67%   |
| Alcor Micro                            | 16        | 0.67%   |
| Microsoft                              | 11        | 0.46%   |
| ALi                                    | 10        | 0.42%   |
| Primax Electronics                     | 8         | 0.33%   |
| OmniVision Technologies                | 8         | 0.33%   |
| Z-Star Microelectronics                | 5         | 0.21%   |
| LG Electronics                         | 4         | 0.17%   |
| YGTek                                  | 3         | 0.13%   |
| Sunplus Technology                     | 3         | 0.13%   |
| MacroSilicon                           | 3         | 0.13%   |
| AVerMedia Technologies                 | 3         | 0.13%   |
| 8SSC20F27114V1SR0BK1X4S                | 3         | 0.13%   |
| SunplusIT                              | 2         | 0.08%   |
| HRY                                    | 2         | 0.08%   |
| Genesys Logic                          | 2         | 0.08%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.08%   |
| ZOOM                                   | 1         | 0.04%   |
| WaveRider Communications               | 1         | 0.04%   |
| Tripath Technology                     | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 131       | 5.45%   |
| Microdia Integrated_Webcam_HD                       | 119       | 4.95%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 89        | 3.7%    |
| Realtek Integrated_Webcam_HD                        | 79        | 3.29%   |
| IMC Networks Integrated Camera                      | 54        | 2.25%   |
| Chicony HD WebCam                                   | 45        | 1.87%   |
| Sunplus Integrated_Webcam_HD                        | 35        | 1.46%   |
| Bison Integrated Camera                             | 34        | 1.41%   |
| Microdia Integrated Webcam                          | 33        | 1.37%   |
| Apple Built-in iSight                               | 33        | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 32        | 1.33%   |
| Apple FaceTime HD Camera                            | 30        | 1.25%   |
| Sunplus HD WebCam                                   | 27        | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 27        | 1.12%   |
| Quanta VGA WebCam                                   | 23        | 0.96%   |
| Lite-On Integrated Camera                           | 22        | 0.92%   |
| Chicony VGA WebCam                                  | 22        | 0.92%   |
| Quanta HD User Facing                               | 21        | 0.87%   |
| Chicony HP TrueVision HD                            | 21        | 0.87%   |
| Chicony HP HD Camera                                | 21        | 0.87%   |
| Bison HD Webcam                                     | 20        | 0.83%   |
| Syntek Integrated Camera                            | 19        | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)             | 19        | 0.79%   |
| Quanta HP TrueVision HD Camera                      | 19        | 0.79%   |
| Chicony USB2.0 HD UVC WebCam                        | 18        | 0.75%   |
| Bison SunplusIT Integrated Camera                   | 18        | 0.75%   |
| Bison Lenovo EasyCamera                             | 18        | 0.75%   |
| Acer Integrated Camera                              | 18        | 0.75%   |
| Chicony USB 2.0 Camera                              | 16        | 0.67%   |
| Chicony TOSHIBA Web Camera - HD                     | 16        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)             | 16        | 0.67%   |
| IMC Networks VGA UVC WebCam                         | 15        | 0.62%   |
| Chicony HD User Facing                              | 15        | 0.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 14        | 0.58%   |
| Sunplus HP HD Webcam [Fixed]                        | 14        | 0.58%   |
| Microdia Laptop_Integrated_Webcam_HD                | 14        | 0.58%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 14        | 0.58%   |
| Bison BisonCam,NB Pro                               | 14        | 0.58%   |
| Realtek USB Camera                                  | 13        | 0.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 13        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 218       | 40.67%  |
| Synaptics                          | 112       | 20.9%   |
| Shenzhen Goodix Technology         | 50        | 9.33%   |
| Upek                               | 38        | 7.09%   |
| Elan Microelectronics              | 38        | 7.09%   |
| AuthenTec                          | 35        | 6.53%   |
| LighTuning Technology              | 22        | 4.1%    |
| STMicroelectronics                 | 16        | 2.99%   |
| Focal-systems.Corp                 | 3         | 0.56%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.19%   |
| Microsoft                          | 1         | 0.19%   |
| HOLTEK                             | 1         | 0.19%   |
| Dell                               | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 50        | 9.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 8.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 40        | 7.46%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 37        | 6.9%    |
| Elan ELAN:Fingerprint                                                      | 32        | 5.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 31        | 5.78%   |
| Shenzhen Goodix FingerPrint                                                | 27        | 5.04%   |
| Validity Sensors Synaptics WBDI                                            | 25        | 4.66%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 3.73%   |
| Validity Sensors VFS491                                                    | 20        | 3.73%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 2.99%   |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 2.99%   |
| AuthenTec AES2810                                                          | 15        | 2.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.61%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 2.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.05%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.49%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.31%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 1.31%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.31%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.31%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.12%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.12%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.93%   |
| Synaptics  WBDI                                                            | 5         | 0.93%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.75%   |
| Synaptics TouchPad                                                         | 4         | 0.75%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.56%   |
| Synaptics WBDI                                                             | 3         | 0.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.56%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.56%   |
| AuthenTec AES1600                                                          | 3         | 0.56%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.37%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.37%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 97        | 48.26%  |
| Alcor Micro               | 38        | 18.91%  |
| O2 Micro                  | 25        | 12.44%  |
| Upek                      | 22        | 10.95%  |
| Lenovo                    | 12        | 5.97%   |
| Gemalto (was Gemplus)     | 4         | 1.99%   |
| Yubico.com                | 1         | 0.5%    |
| Giesecke & Devrient       | 1         | 0.5%    |
| Aladdin Knowledge Systems | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 53        | 26.37%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 18.41%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 10.95%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 9.45%   |
| Broadcom 5880                                                                | 14        | 6.97%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 5.97%   |
| Broadcom 58200                                                               | 10        | 4.98%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.99%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 1.99%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.5%    |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.5%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.5%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1781      | 62.49%  |
| 1     | 846       | 29.68%  |
| 2     | 186       | 6.53%   |
| 3     | 28        | 0.98%   |
| 4     | 6         | 0.21%   |
| 7     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 524       | 40.56%  |
| Graphics card            | 221       | 17.11%  |
| Chipcard                 | 186       | 14.4%   |
| Net/wireless             | 111       | 8.59%   |
| Multimedia controller    | 76        | 5.88%   |
| Storage                  | 36        | 2.79%   |
| Camera                   | 27        | 2.09%   |
| Bluetooth                | 27        | 2.09%   |
| Communication controller | 23        | 1.78%   |
| Net/ethernet             | 14        | 1.08%   |
| Modem                    | 11        | 0.85%   |
| Card reader              | 10        | 0.77%   |
| Sound                    | 9         | 0.7%    |
| Network                  | 5         | 0.39%   |
| Flash memory             | 5         | 0.39%   |
| Storage/ide              | 2         | 0.15%   |
| Firewire controller      | 2         | 0.15%   |
| Unclassified device      | 1         | 0.08%   |
| Tv card                  | 1         | 0.08%   |
| Dvb card                 | 1         | 0.08%   |


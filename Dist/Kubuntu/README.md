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

Total: 4039

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [ed9cd240cc](https://linux-hardware.org/?probe=ed9cd240cc) | Oct 01, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [08db9e8d75](https://linux-hardware.org/?probe=08db9e8d75) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [e38fd71e40](https://linux-hardware.org/?probe=e38fd71e40) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [2b78a7c7f1](https://linux-hardware.org/?probe=2b78a7c7f1) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [8e77417877](https://linux-hardware.org/?probe=8e77417877) | Sep 28, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [4b198e87aa](https://linux-hardware.org/?probe=4b198e87aa) | Sep 28, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [541a21ceb8](https://linux-hardware.org/?probe=541a21ceb8) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| Dell          | Latitude E5400              | Notebook    | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| AZW           | SER                         | Mini pc     | [9e9ee5be74](https://linux-hardware.org/?probe=9e9ee5be74) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [2a27e3cb58](https://linux-hardware.org/?probe=2a27e3cb58) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [f52114ac39](https://linux-hardware.org/?probe=f52114ac39) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [f10501b259](https://linux-hardware.org/?probe=f10501b259) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Google        | Blooglet                    | Notebook    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [97b748d5d3](https://linux-hardware.org/?probe=97b748d5d3) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Dell          | Latitude 7430               | Notebook    | [4fdf1a303c](https://linux-hardware.org/?probe=4fdf1a303c) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [eb49db3a8c](https://linux-hardware.org/?probe=eb49db3a8c) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ca8786a47](https://linux-hardware.org/?probe=1ca8786a47) | Sep 13, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [20b4c0a5b2](https://linux-hardware.org/?probe=20b4c0a5b2) | Sep 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [8aac6d779b](https://linux-hardware.org/?probe=8aac6d779b) | Sep 13, 2022 |
| Unknown       | Unknown                     | Other       | [1e94b50834](https://linux-hardware.org/?probe=1e94b50834) | Sep 12, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | Notebook    | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [a27d14af07](https://linux-hardware.org/?probe=a27d14af07) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Dell          | Latitude 7430               | Notebook    | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Acer          | Predator G3-571             | Notebook    | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | Z97-G43                     | Desktop     | [eeea153bb2](https://linux-hardware.org/?probe=eeea153bb2) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [8a1c5532d6](https://linux-hardware.org/?probe=8a1c5532d6) | Sep 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [58062d2ad3](https://linux-hardware.org/?probe=58062d2ad3) | Sep 06, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5c53e30fe6](https://linux-hardware.org/?probe=5c53e30fe6) | Sep 06, 2022 |
| HP            | 2B3E                        | All in one  | [4ccdce6df9](https://linux-hardware.org/?probe=4ccdce6df9) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [d496e01f0e](https://linux-hardware.org/?probe=d496e01f0e) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [45dceb981a](https://linux-hardware.org/?probe=45dceb981a) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| HP            | Notebook                    | Notebook    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [71ff7749aa](https://linux-hardware.org/?probe=71ff7749aa) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0789b27bdb](https://linux-hardware.org/?probe=0789b27bdb) | Sep 02, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [33784347f5](https://linux-hardware.org/?probe=33784347f5) | Sep 02, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [e93c1732ec](https://linux-hardware.org/?probe=e93c1732ec) | Sep 02, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [f77ecfe3bc](https://linux-hardware.org/?probe=f77ecfe3bc) | Sep 02, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [27840cf8d2](https://linux-hardware.org/?probe=27840cf8d2) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [b99f4a264b](https://linux-hardware.org/?probe=b99f4a264b) | Sep 01, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | Notebook    | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [54f5dc3cf8](https://linux-hardware.org/?probe=54f5dc3cf8) | Aug 26, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8517e82248](https://linux-hardware.org/?probe=8517e82248) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [676e223d96](https://linux-hardware.org/?probe=676e223d96) | Aug 25, 2022 |
| HP            | ProBook 4540s               | Notebook    | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | Notebook    | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [348dc86c64](https://linux-hardware.org/?probe=348dc86c64) | Aug 23, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [83e175bed9](https://linux-hardware.org/?probe=83e175bed9) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [10973eca34](https://linux-hardware.org/?probe=10973eca34) | Aug 22, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [bdc4179004](https://linux-hardware.org/?probe=bdc4179004) | Aug 21, 2022 |
| HP            | ProBook 6570b               | Notebook    | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| Dell          | G3 3779                     | Notebook    | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Samsung       | 950QDB                      | Convertible | [d4fc73ce00](https://linux-hardware.org/?probe=d4fc73ce00) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| ASUSTek       | Z10PC-D8 Series             | Desktop     | [1cb7c569c1](https://linux-hardware.org/?probe=1cb7c569c1) | Aug 17, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [30820abfa2](https://linux-hardware.org/?probe=30820abfa2) | Aug 14, 2022 |
| HP            | ProBook 6570b               | Notebook    | [fb2fa26698](https://linux-hardware.org/?probe=fb2fa26698) | Aug 13, 2022 |
| ASUSTek       | NAGAMI                      | Desktop     | [c6c8918483](https://linux-hardware.org/?probe=c6c8918483) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| Panasonic     | CF-53JSWZGFF                | Notebook    | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Dell          | Latitude 5590               | Notebook    | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Timi          | TM1709                      | Notebook    | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [9c53dae23e](https://linux-hardware.org/?probe=9c53dae23e) | Aug 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| Unknown       | Unknown                     | Other       | [23e67d3f72](https://linux-hardware.org/?probe=23e67d3f72) | Aug 10, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | Notebook    | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| HP            | 212A                        | Desktop     | [3b1662cede](https://linux-hardware.org/?probe=3b1662cede) | Aug 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [b2e805c687](https://linux-hardware.org/?probe=b2e805c687) | Aug 07, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23905636a4](https://linux-hardware.org/?probe=23905636a4) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fd78986d01](https://linux-hardware.org/?probe=fd78986d01) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| Dell          | Precision 7530              | Notebook    | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [3a73f1ffdd](https://linux-hardware.org/?probe=3a73f1ffdd) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9814fa3bca](https://linux-hardware.org/?probe=9814fa3bca) | Aug 03, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [83e4b444ae](https://linux-hardware.org/?probe=83e4b444ae) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [4e335cb7ce](https://linux-hardware.org/?probe=4e335cb7ce) | Aug 01, 2022 |
| Intel         | Unknown                     | Notebook    | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [105d26b09c](https://linux-hardware.org/?probe=105d26b09c) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [4ae44495ba](https://linux-hardware.org/?probe=4ae44495ba) | Jul 30, 2022 |
| Dell          | 0F8098                      | Desktop     | [4e6058685a](https://linux-hardware.org/?probe=4e6058685a) | Jul 30, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| HP            | 158A                        | Desktop     | [788844c3df](https://linux-hardware.org/?probe=788844c3df) | Jul 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [1b47c32e5d](https://linux-hardware.org/?probe=1b47c32e5d) | Jul 29, 2022 |
| HP            | 8754                        | Mini pc     | [1b0ae59d1f](https://linux-hardware.org/?probe=1b0ae59d1f) | Jul 28, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2d3706b78b](https://linux-hardware.org/?probe=2d3706b78b) | Jul 28, 2022 |
| HP            | 8459                        | Desktop     | [a1d6ae45cb](https://linux-hardware.org/?probe=a1d6ae45cb) | Jul 28, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| Dell          | Latitude 5590               | Notebook    | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [8b027b07d9](https://linux-hardware.org/?probe=8b027b07d9) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [2b505d28f7](https://linux-hardware.org/?probe=2b505d28f7) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [51bf4e60d3](https://linux-hardware.org/?probe=51bf4e60d3) | Jul 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| HP            | 86E9 A                      | Desktop     | [6634eaee32](https://linux-hardware.org/?probe=6634eaee32) | Jul 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [3e40b1abe6](https://linux-hardware.org/?probe=3e40b1abe6) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [158c8d142b](https://linux-hardware.org/?probe=158c8d142b) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [88530d3d60](https://linux-hardware.org/?probe=88530d3d60) | Jul 23, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [24bc799d14](https://linux-hardware.org/?probe=24bc799d14) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [1177e7dbe0](https://linux-hardware.org/?probe=1177e7dbe0) | Jul 21, 2022 |
| HP            | G62                         | Notebook    | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [379da1a196](https://linux-hardware.org/?probe=379da1a196) | Jul 21, 2022 |
| HP            | 8054                        | Desktop     | [466d7f5591](https://linux-hardware.org/?probe=466d7f5591) | Jul 21, 2022 |
| HP            | 18E9                        | Desktop     | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | Notebook    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [468283ab86](https://linux-hardware.org/?probe=468283ab86) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | 1790                        | Desktop     | [ff91b0d921](https://linux-hardware.org/?probe=ff91b0d921) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [02a5205d57](https://linux-hardware.org/?probe=02a5205d57) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [3ea67a64cb](https://linux-hardware.org/?probe=3ea67a64cb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASRock        | J4105M                      | Desktop     | [509b122b9b](https://linux-hardware.org/?probe=509b122b9b) | Jul 12, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| Dell          | Latitude E5520              | Notebook    | [e04cdad7b7](https://linux-hardware.org/?probe=e04cdad7b7) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0967e17760](https://linux-hardware.org/?probe=0967e17760) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | Notebook    | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | Notebook    | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [435e7998bd](https://linux-hardware.org/?probe=435e7998bd) | Jul 08, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| HP            | G42                         | Notebook    | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2240dc8dde](https://linux-hardware.org/?probe=2240dc8dde) | Jul 03, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 620                         | Notebook    | [cc970fdd77](https://linux-hardware.org/?probe=cc970fdd77) | Jul 02, 2022 |
| Lenovo        | ThinkPad T420 4180M8P       | Notebook    | [8a94c5bc15](https://linux-hardware.org/?probe=8a94c5bc15) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | 8459                        | Desktop     | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [91408af847](https://linux-hardware.org/?probe=91408af847) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | Desktop     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [32e2995911](https://linux-hardware.org/?probe=32e2995911) | Jun 30, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [530c44caa8](https://linux-hardware.org/?probe=530c44caa8) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [66b40738ff](https://linux-hardware.org/?probe=66b40738ff) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| Jumper        | EZpad                       | Notebook    | [3ea5b3080d](https://linux-hardware.org/?probe=3ea5b3080d) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| Haier         | A1420EM                     | Notebook    | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [183f3e59fb](https://linux-hardware.org/?probe=183f3e59fb) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [fd93206df4](https://linux-hardware.org/?probe=fd93206df4) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Intel         | X99                         | Desktop     | [4322217bc5](https://linux-hardware.org/?probe=4322217bc5) | Jun 26, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Medion        | E3216 MD60900               | Convertible | [2890f2581b](https://linux-hardware.org/?probe=2890f2581b) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [554ba1726f](https://linux-hardware.org/?probe=554ba1726f) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3dffa312da](https://linux-hardware.org/?probe=3dffa312da) | Jun 24, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [10d0c2a6ea](https://linux-hardware.org/?probe=10d0c2a6ea) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ece1eb60ef](https://linux-hardware.org/?probe=ece1eb60ef) | Jun 24, 2022 |
| Dell          | Latitude XT3                | Notebook    | [87377f03e2](https://linux-hardware.org/?probe=87377f03e2) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ba64ef130a](https://linux-hardware.org/?probe=ba64ef130a) | Jun 23, 2022 |
| Clevo         | Modified by dsanke          | Notebook    | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2727a44bcd](https://linux-hardware.org/?probe=2727a44bcd) | Jun 22, 2022 |
| ASUSTek       | GR8                         | Notebook    | [90afe7bdd7](https://linux-hardware.org/?probe=90afe7bdd7) | Jun 20, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Medion        | AXIR                        | All in one  | [c3acbcaea0](https://linux-hardware.org/?probe=c3acbcaea0) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Packard Be... | H17HV                       | Notebook    | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | Notebook    | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| HP            | 0A60h                       | Desktop     | [cb42238223](https://linux-hardware.org/?probe=cb42238223) | Jun 17, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [c5763f8865](https://linux-hardware.org/?probe=c5763f8865) | Jun 17, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | Notebook    | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Jumper        | EZpad                       | Notebook    | [b1a0e53c08](https://linux-hardware.org/?probe=b1a0e53c08) | Jun 16, 2022 |
| ASUSTek       | X99-A/USB                   | Desktop     | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [b4a87914f3](https://linux-hardware.org/?probe=b4a87914f3) | Jun 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [91316a0904](https://linux-hardware.org/?probe=91316a0904) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | Notebook    | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | 620                         | Notebook    | [fe1a420f17](https://linux-hardware.org/?probe=fe1a420f17) | Jun 13, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [8b6f8e8952](https://linux-hardware.org/?probe=8b6f8e8952) | Jun 13, 2022 |
| Jumper        | EZpad                       | Notebook    | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 1428               | Notebook    | [e47c98983f](https://linux-hardware.org/?probe=e47c98983f) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [13a04a66d8](https://linux-hardware.org/?probe=13a04a66d8) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7f7678265b](https://linux-hardware.org/?probe=7f7678265b) | Jun 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c8d1e1be32](https://linux-hardware.org/?probe=c8d1e1be32) | Jun 10, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | 0A98h                       | Desktop     | [d3c54ab2d6](https://linux-hardware.org/?probe=d3c54ab2d6) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [54a2c4fa94](https://linux-hardware.org/?probe=54a2c4fa94) | Jun 08, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3a58a9889b](https://linux-hardware.org/?probe=3a58a9889b) | Jun 08, 2022 |
| HP            | 620                         | Notebook    | [1adcb99573](https://linux-hardware.org/?probe=1adcb99573) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [42aaad44bc](https://linux-hardware.org/?probe=42aaad44bc) | Jun 06, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [acf0372bdc](https://linux-hardware.org/?probe=acf0372bdc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Toshiba       | Satellite C75D-A            | Notebook    | [a5aee20b56](https://linux-hardware.org/?probe=a5aee20b56) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| Positivo      | Q464C                       | Notebook    | [e00b91e529](https://linux-hardware.org/?probe=e00b91e529) | Jun 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [eb62d09265](https://linux-hardware.org/?probe=eb62d09265) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [96f8c08754](https://linux-hardware.org/?probe=96f8c08754) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e858488f6f](https://linux-hardware.org/?probe=e858488f6f) | Jun 03, 2022 |
| MSI           | CX61 2PC                    | Notebook    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [c8e2700624](https://linux-hardware.org/?probe=c8e2700624) | Jun 02, 2022 |
| Dell          | Latitude 7420               | Notebook    | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | Notebook    | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | TX201LA                     | Notebook    | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | Notebook    | [0436371728](https://linux-hardware.org/?probe=0436371728) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | Notebook    | [20d1a7e37b](https://linux-hardware.org/?probe=20d1a7e37b) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| Dell          | G7 7588                     | Notebook    | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [b450673fc0](https://linux-hardware.org/?probe=b450673fc0) | May 31, 2022 |
| Google        | Coral                       | Notebook    | [c517ad03c1](https://linux-hardware.org/?probe=c517ad03c1) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| Dell          | Precision 7710              | Notebook    | [f24e29d104](https://linux-hardware.org/?probe=f24e29d104) | May 30, 2022 |
| Dell          | Precision 7710              | Notebook    | [1bae5a0bf0](https://linux-hardware.org/?probe=1bae5a0bf0) | May 30, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [57e0b15d17](https://linux-hardware.org/?probe=57e0b15d17) | May 30, 2022 |
| HP            | Pavilion g4                 | Notebook    | [39cdebfff4](https://linux-hardware.org/?probe=39cdebfff4) | May 29, 2022 |
| Medion        | S6445 MD61489               | Notebook    | [a933286b06](https://linux-hardware.org/?probe=a933286b06) | May 29, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [326c7a11e6](https://linux-hardware.org/?probe=326c7a11e6) | May 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| HP            | 304Bh                       | Desktop     | [eaf30cead9](https://linux-hardware.org/?probe=eaf30cead9) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | Notebook    | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [1eddee7bcd](https://linux-hardware.org/?probe=1eddee7bcd) | May 26, 2022 |
| Lenovo        | ThinkCentre M90p 5864AL2    | Desktop     | [679cfd5a27](https://linux-hardware.org/?probe=679cfd5a27) | May 26, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [d153ce4509](https://linux-hardware.org/?probe=d153ce4509) | May 26, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [540416deba](https://linux-hardware.org/?probe=540416deba) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [63a10ce1e0](https://linux-hardware.org/?probe=63a10ce1e0) | May 23, 2022 |
| Acer          | Aspire M5-581TG             | Notebook    | [c6ffc6271c](https://linux-hardware.org/?probe=c6ffc6271c) | May 23, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [765d22e752](https://linux-hardware.org/?probe=765d22e752) | May 23, 2022 |
| HP            | 15                          | Notebook    | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [52dce4d0c3](https://linux-hardware.org/?probe=52dce4d0c3) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [2a6ba92f67](https://linux-hardware.org/?probe=2a6ba92f67) | May 22, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | Notebook    | [06ec4e94a2](https://linux-hardware.org/?probe=06ec4e94a2) | May 22, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | Notebook    | [d333d63d80](https://linux-hardware.org/?probe=d333d63d80) | May 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [3d856e6f83](https://linux-hardware.org/?probe=3d856e6f83) | May 22, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [dfa1010543](https://linux-hardware.org/?probe=dfa1010543) | May 21, 2022 |
| MSI           | 2AE0                        | Desktop     | [d99294cadc](https://linux-hardware.org/?probe=d99294cadc) | May 21, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [445a484f8d](https://linux-hardware.org/?probe=445a484f8d) | May 21, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [49df794b0b](https://linux-hardware.org/?probe=49df794b0b) | May 20, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [8266843e53](https://linux-hardware.org/?probe=8266843e53) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b098eb44db](https://linux-hardware.org/?probe=b098eb44db) | May 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [cf5954d738](https://linux-hardware.org/?probe=cf5954d738) | May 18, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [e08308603a](https://linux-hardware.org/?probe=e08308603a) | May 18, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [eb5d08e402](https://linux-hardware.org/?probe=eb5d08e402) | May 18, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [ee6e90c751](https://linux-hardware.org/?probe=ee6e90c751) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| HP            | ProBook 6470b               | Notebook    | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [78fe695a2f](https://linux-hardware.org/?probe=78fe695a2f) | May 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| HP            | Unknown                     | Notebook    | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [cd20eb0809](https://linux-hardware.org/?probe=cd20eb0809) | May 14, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d1e8a0642](https://linux-hardware.org/?probe=2d1e8a0642) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [2152787c64](https://linux-hardware.org/?probe=2152787c64) | May 13, 2022 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [823a7381c9](https://linux-hardware.org/?probe=823a7381c9) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [d7733a6d5e](https://linux-hardware.org/?probe=d7733a6d5e) | May 13, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0a6e09b95](https://linux-hardware.org/?probe=a0a6e09b95) | May 13, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [2ba7ecdb55](https://linux-hardware.org/?probe=2ba7ecdb55) | May 10, 2022 |
| Dell          | Latitude E6540              | Notebook    | [a5bb9f2b58](https://linux-hardware.org/?probe=a5bb9f2b58) | May 10, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | Desktop     | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [f3abe22dd6](https://linux-hardware.org/?probe=f3abe22dd6) | May 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | Notebook    | [0cfd533226](https://linux-hardware.org/?probe=0cfd533226) | May 08, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [dc9b228486](https://linux-hardware.org/?probe=dc9b228486) | May 08, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4c4a006287](https://linux-hardware.org/?probe=4c4a006287) | May 07, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| HP            | ProBook 6470b               | Notebook    | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [f1d427d32b](https://linux-hardware.org/?probe=f1d427d32b) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [ef836a5eca](https://linux-hardware.org/?probe=ef836a5eca) | May 06, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aefe7a52e0](https://linux-hardware.org/?probe=aefe7a52e0) | May 06, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [71c0c4f257](https://linux-hardware.org/?probe=71c0c4f257) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| HP            | ProBook 6450b               | Notebook    | [0c23a5cbc2](https://linux-hardware.org/?probe=0c23a5cbc2) | May 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [978f98cef3](https://linux-hardware.org/?probe=978f98cef3) | May 04, 2022 |
| Alienware     | 17                          | Notebook    | [1a4cd056f8](https://linux-hardware.org/?probe=1a4cd056f8) | May 04, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e126640b3b](https://linux-hardware.org/?probe=e126640b3b) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | Notebook    | [b303038c87](https://linux-hardware.org/?probe=b303038c87) | May 01, 2022 |
| Lenovo        | ThinkPad X201 3680AC2       | Notebook    | [5c4515d51e](https://linux-hardware.org/?probe=5c4515d51e) | May 01, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [75362e2061](https://linux-hardware.org/?probe=75362e2061) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [9f7923bcd2](https://linux-hardware.org/?probe=9f7923bcd2) | Apr 29, 2022 |
| HP            | 3396                        | Desktop     | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP            | 3396                        | Desktop     | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [12a0105da3](https://linux-hardware.org/?probe=12a0105da3) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [3206e0f075](https://linux-hardware.org/?probe=3206e0f075) | Apr 27, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [a7061bdb08](https://linux-hardware.org/?probe=a7061bdb08) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e4ecdec958](https://linux-hardware.org/?probe=e4ecdec958) | Apr 27, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [fa33f58948](https://linux-hardware.org/?probe=fa33f58948) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [fcd8a2962e](https://linux-hardware.org/?probe=fcd8a2962e) | Apr 26, 2022 |
| HP            | ENVY 17                     | Notebook    | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | Notebook    | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e466d79804](https://linux-hardware.org/?probe=e466d79804) | Apr 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [89debf3e0e](https://linux-hardware.org/?probe=89debf3e0e) | Apr 25, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [82c13f2b01](https://linux-hardware.org/?probe=82c13f2b01) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Dell          | Studio 1558                 | Notebook    | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ef1e814871](https://linux-hardware.org/?probe=ef1e814871) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3ea846ae2a](https://linux-hardware.org/?probe=3ea846ae2a) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [9877ddeaf6](https://linux-hardware.org/?probe=9877ddeaf6) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Intel         | NUC6CAYB J23203-402         | Mini pc     | [86964dccfd](https://linux-hardware.org/?probe=86964dccfd) | Apr 23, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [848b9d8f5c](https://linux-hardware.org/?probe=848b9d8f5c) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [da630d58cf](https://linux-hardware.org/?probe=da630d58cf) | Apr 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [8ee6cabf43](https://linux-hardware.org/?probe=8ee6cabf43) | Apr 22, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [28690580aa](https://linux-hardware.org/?probe=28690580aa) | Apr 22, 2022 |
| HP            | 2B4B                        | Desktop     | [c3dd8ed52a](https://linux-hardware.org/?probe=c3dd8ed52a) | Apr 22, 2022 |
| ASRock        | Z87 Pro4                    | Desktop     | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [8c7c0bd289](https://linux-hardware.org/?probe=8c7c0bd289) | Apr 21, 2022 |
| Dynabook      | PORTEGE X30L-J              | Notebook    | [5894fd3a34](https://linux-hardware.org/?probe=5894fd3a34) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Positivo      | W940TU                      | Notebook    | [4d03effd28](https://linux-hardware.org/?probe=4d03effd28) | Apr 20, 2022 |
| Positivo      | W940TU                      | Notebook    | [971493b883](https://linux-hardware.org/?probe=971493b883) | Apr 20, 2022 |
| Dell          | Latitude XT3                | Notebook    | [6db9585e20](https://linux-hardware.org/?probe=6db9585e20) | Apr 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53199db8c8](https://linux-hardware.org/?probe=53199db8c8) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f8e7d70919](https://linux-hardware.org/?probe=f8e7d70919) | Apr 18, 2022 |
| Shuttle       | FH61V                       | Desktop     | [2fae1ee493](https://linux-hardware.org/?probe=2fae1ee493) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| Dell          | Latitude XT3                | Notebook    | [c4d7d751b7](https://linux-hardware.org/?probe=c4d7d751b7) | Apr 17, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Dell          | Latitude 7410               | Notebook    | [da82f8bba8](https://linux-hardware.org/?probe=da82f8bba8) | Apr 15, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c00611352d](https://linux-hardware.org/?probe=c00611352d) | Apr 15, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Dell          | Latitude XT3                | Notebook    | [ce6c2e43a0](https://linux-hardware.org/?probe=ce6c2e43a0) | Apr 15, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [f52ef2faf2](https://linux-hardware.org/?probe=f52ef2faf2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [2ee68b5f38](https://linux-hardware.org/?probe=2ee68b5f38) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [6846ee88e0](https://linux-hardware.org/?probe=6846ee88e0) | Apr 14, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [e172be90b8](https://linux-hardware.org/?probe=e172be90b8) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [3e09de906e](https://linux-hardware.org/?probe=3e09de906e) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 41786UU       | Notebook    | [2211278055](https://linux-hardware.org/?probe=2211278055) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | ThinkPad P51 20HH000AUS     | Notebook    | [b7365a4abd](https://linux-hardware.org/?probe=b7365a4abd) | Apr 14, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [bd5a2f5943](https://linux-hardware.org/?probe=bd5a2f5943) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [a21bd26d1e](https://linux-hardware.org/?probe=a21bd26d1e) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Lenovo        | IdeaPad 710S Plus Touch-... | Notebook    | [f4578ea652](https://linux-hardware.org/?probe=f4578ea652) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [744144c472](https://linux-hardware.org/?probe=744144c472) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [479b8d48fc](https://linux-hardware.org/?probe=479b8d48fc) | Apr 13, 2022 |
| MSI           | Z270 SLI PLUS               | Desktop     | [fa00f6ccd6](https://linux-hardware.org/?probe=fa00f6ccd6) | Apr 13, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [74191e7ffb](https://linux-hardware.org/?probe=74191e7ffb) | Apr 13, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [2d44f4a10b](https://linux-hardware.org/?probe=2d44f4a10b) | Apr 13, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [f74831788b](https://linux-hardware.org/?probe=f74831788b) | Apr 13, 2022 |
| Dell          | Latitude 5591               | Notebook    | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5923be4543](https://linux-hardware.org/?probe=5923be4543) | Apr 13, 2022 |
| Dell          | Latitude 7400               | Notebook    | [2c32d69a57](https://linux-hardware.org/?probe=2c32d69a57) | Apr 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [db6bf8f1b9](https://linux-hardware.org/?probe=db6bf8f1b9) | Apr 13, 2022 |
| Dell          | Precision 5520              | Notebook    | [eb5bfc87ed](https://linux-hardware.org/?probe=eb5bfc87ed) | Apr 12, 2022 |
| Lenovo        | ThinkPad T430 2349T2A       | Notebook    | [344710cc3a](https://linux-hardware.org/?probe=344710cc3a) | Apr 12, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Dell          | Inspiron 7786               | Convertible | [cdf7aa0cb8](https://linux-hardware.org/?probe=cdf7aa0cb8) | Apr 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [c3d5951840](https://linux-hardware.org/?probe=c3d5951840) | Apr 10, 2022 |
| Lenovo        | IdeaPad Z585                | Notebook    | [5f84c70657](https://linux-hardware.org/?probe=5f84c70657) | Apr 10, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cf76bb9e39](https://linux-hardware.org/?probe=cf76bb9e39) | Apr 10, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [13dff6f000](https://linux-hardware.org/?probe=13dff6f000) | Apr 10, 2022 |
| Dell          | G7 7790                     | Notebook    | [6cdb296d8e](https://linux-hardware.org/?probe=6cdb296d8e) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [848a486145](https://linux-hardware.org/?probe=848a486145) | Apr 10, 2022 |
| eMachines     | G525                        | Notebook    | [6ba45c519c](https://linux-hardware.org/?probe=6ba45c519c) | Apr 09, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [18045cb759](https://linux-hardware.org/?probe=18045cb759) | Apr 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [272c9f107a](https://linux-hardware.org/?probe=272c9f107a) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Positivo      | N1250                       | Notebook    | [c64a47d6fc](https://linux-hardware.org/?probe=c64a47d6fc) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Sony          | SVE1511W1ESI                | Notebook    | [403773664b](https://linux-hardware.org/?probe=403773664b) | Apr 08, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6891954221](https://linux-hardware.org/?probe=6891954221) | Apr 08, 2022 |
| HP            | ENVY 15                     | Notebook    | [cdd8aea3c3](https://linux-hardware.org/?probe=cdd8aea3c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [dea231bf61](https://linux-hardware.org/?probe=dea231bf61) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b02ac7d8ce](https://linux-hardware.org/?probe=b02ac7d8ce) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64c2c15492](https://linux-hardware.org/?probe=64c2c15492) | Apr 05, 2022 |
| HP            | 3047h                       | Desktop     | [6766d428ef](https://linux-hardware.org/?probe=6766d428ef) | Apr 05, 2022 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [ee8ada5124](https://linux-hardware.org/?probe=ee8ada5124) | Apr 05, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [e7576083a0](https://linux-hardware.org/?probe=e7576083a0) | Apr 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f98a0cf73b](https://linux-hardware.org/?probe=f98a0cf73b) | Apr 05, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a63f363043](https://linux-hardware.org/?probe=a63f363043) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| HP            | 805D                        | Desktop     | [198cff1b8e](https://linux-hardware.org/?probe=198cff1b8e) | Apr 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [73ecbc62b1](https://linux-hardware.org/?probe=73ecbc62b1) | Apr 04, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [9aea13fa1b](https://linux-hardware.org/?probe=9aea13fa1b) | Apr 04, 2022 |
| HP            | 1790                        | Desktop     | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [ec2fb21c00](https://linux-hardware.org/?probe=ec2fb21c00) | Apr 03, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [5a4174b74d](https://linux-hardware.org/?probe=5a4174b74d) | Apr 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [a3aea1cbf5](https://linux-hardware.org/?probe=a3aea1cbf5) | Apr 02, 2022 |
| HP            | 805D                        | Desktop     | [709488e1da](https://linux-hardware.org/?probe=709488e1da) | Mar 31, 2022 |
| Lenovo        | ThinkPad T540p 20BEA00FR... | Notebook    | [c9323a9c40](https://linux-hardware.org/?probe=c9323a9c40) | Mar 31, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [3d76ab6a14](https://linux-hardware.org/?probe=3d76ab6a14) | Mar 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [b61b3e31e7](https://linux-hardware.org/?probe=b61b3e31e7) | Mar 30, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [f47336bbed](https://linux-hardware.org/?probe=f47336bbed) | Mar 30, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f398041b40](https://linux-hardware.org/?probe=f398041b40) | Mar 29, 2022 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [b6f8d31fa5](https://linux-hardware.org/?probe=b6f8d31fa5) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [5dae1dd2a5](https://linux-hardware.org/?probe=5dae1dd2a5) | Mar 28, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [323ca65327](https://linux-hardware.org/?probe=323ca65327) | Mar 28, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [f457ad3a65](https://linux-hardware.org/?probe=f457ad3a65) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | Notebook    | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [fe29ba6b10](https://linux-hardware.org/?probe=fe29ba6b10) | Mar 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [dc2a2c1054](https://linux-hardware.org/?probe=dc2a2c1054) | Mar 25, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [f0a08eb35b](https://linux-hardware.org/?probe=f0a08eb35b) | Mar 25, 2022 |
| Dell          | Inspiron 5379               | Notebook    | [85c7a99f91](https://linux-hardware.org/?probe=85c7a99f91) | Mar 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eef252e4f2](https://linux-hardware.org/?probe=eef252e4f2) | Mar 25, 2022 |
| Avell High... | B.ON                        | Notebook    | [19b689aa12](https://linux-hardware.org/?probe=19b689aa12) | Mar 25, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [c3cd38fd2d](https://linux-hardware.org/?probe=c3cd38fd2d) | Mar 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [a2db3c2cab](https://linux-hardware.org/?probe=a2db3c2cab) | Mar 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [cb089466a3](https://linux-hardware.org/?probe=cb089466a3) | Mar 24, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [43e7eab371](https://linux-hardware.org/?probe=43e7eab371) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [c136393c4b](https://linux-hardware.org/?probe=c136393c4b) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [713ff9dcb8](https://linux-hardware.org/?probe=713ff9dcb8) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [e5fe628a7b](https://linux-hardware.org/?probe=e5fe628a7b) | Mar 23, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [5b74db2557](https://linux-hardware.org/?probe=5b74db2557) | Mar 22, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [d398e3284e](https://linux-hardware.org/?probe=d398e3284e) | Mar 22, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c90c0f1819](https://linux-hardware.org/?probe=c90c0f1819) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [0d7edce12d](https://linux-hardware.org/?probe=0d7edce12d) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d3b1757cf5](https://linux-hardware.org/?probe=d3b1757cf5) | Mar 21, 2022 |
| ASUSTek       | K73E                        | Notebook    | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| HP            | 212B                        | Desktop     | [fd6a569226](https://linux-hardware.org/?probe=fd6a569226) | Mar 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3607969e9d](https://linux-hardware.org/?probe=3607969e9d) | Mar 20, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [b1a437de4c](https://linux-hardware.org/?probe=b1a437de4c) | Mar 19, 2022 |
| HP            | 212B                        | Desktop     | [a85896bd48](https://linux-hardware.org/?probe=a85896bd48) | Mar 19, 2022 |
| HP            | 1589                        | Desktop     | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [05780b53fa](https://linux-hardware.org/?probe=05780b53fa) | Mar 19, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d1f5b906e4](https://linux-hardware.org/?probe=d1f5b906e4) | Mar 19, 2022 |
| Panasonic     | FZ-M1CC-51BE                | Notebook    | [94e014ee40](https://linux-hardware.org/?probe=94e014ee40) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [df958219ab](https://linux-hardware.org/?probe=df958219ab) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [d46b854bd5](https://linux-hardware.org/?probe=d46b854bd5) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [b05ec1dbda](https://linux-hardware.org/?probe=b05ec1dbda) | Mar 18, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| Dell          | Precision M6300             | Notebook    | [aac71b9e66](https://linux-hardware.org/?probe=aac71b9e66) | Mar 17, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [77c6485b0f](https://linux-hardware.org/?probe=77c6485b0f) | Mar 17, 2022 |
| Packard Be... | IMEDIA S2885                | Desktop     | [1cf614db1e](https://linux-hardware.org/?probe=1cf614db1e) | Mar 17, 2022 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c0db7c9966](https://linux-hardware.org/?probe=c0db7c9966) | Mar 17, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [8713806c38](https://linux-hardware.org/?probe=8713806c38) | Mar 17, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [42b5f424ce](https://linux-hardware.org/?probe=42b5f424ce) | Mar 17, 2022 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [d0253d1ffc](https://linux-hardware.org/?probe=d0253d1ffc) | Mar 16, 2022 |
| GEO           | GeoFlex 110                 | Convertible | [763a31bbc5](https://linux-hardware.org/?probe=763a31bbc5) | Mar 16, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [e2ad81141c](https://linux-hardware.org/?probe=e2ad81141c) | Mar 16, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [acdee8aa65](https://linux-hardware.org/?probe=acdee8aa65) | Mar 15, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [bf80f02a40](https://linux-hardware.org/?probe=bf80f02a40) | Mar 15, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [c8809e0561](https://linux-hardware.org/?probe=c8809e0561) | Mar 15, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [162abf1031](https://linux-hardware.org/?probe=162abf1031) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [96b413780f](https://linux-hardware.org/?probe=96b413780f) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8ab5133b14](https://linux-hardware.org/?probe=8ab5133b14) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [39cdee5411](https://linux-hardware.org/?probe=39cdee5411) | Mar 11, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [09d876ab23](https://linux-hardware.org/?probe=09d876ab23) | Mar 11, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [e0e30a9273](https://linux-hardware.org/?probe=e0e30a9273) | Mar 11, 2022 |
| ASRock        | B360 Gaming K4              | Desktop     | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| HP            | 82F1                        | Desktop     | [390462d20a](https://linux-hardware.org/?probe=390462d20a) | Mar 10, 2022 |
| HP            | 82F1                        | Desktop     | [63273af14a](https://linux-hardware.org/?probe=63273af14a) | Mar 10, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [066fecf595](https://linux-hardware.org/?probe=066fecf595) | Mar 10, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [e7a3d16cc0](https://linux-hardware.org/?probe=e7a3d16cc0) | Mar 09, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [2032fbba77](https://linux-hardware.org/?probe=2032fbba77) | Mar 09, 2022 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [508a68f09e](https://linux-hardware.org/?probe=508a68f09e) | Mar 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c7b32ff620](https://linux-hardware.org/?probe=c7b32ff620) | Mar 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [257f76a0df](https://linux-hardware.org/?probe=257f76a0df) | Mar 09, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [8dbe399133](https://linux-hardware.org/?probe=8dbe399133) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c7025ac75e](https://linux-hardware.org/?probe=c7025ac75e) | Mar 08, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [e06660b923](https://linux-hardware.org/?probe=e06660b923) | Mar 08, 2022 |
| Medion        | E2292 MD63390               | Convertible | [6f0eb8e6d7](https://linux-hardware.org/?probe=6f0eb8e6d7) | Mar 07, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [f0f74fc82a](https://linux-hardware.org/?probe=f0f74fc82a) | Mar 07, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [bde9b00de4](https://linux-hardware.org/?probe=bde9b00de4) | Mar 07, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [9f17c99bb5](https://linux-hardware.org/?probe=9f17c99bb5) | Mar 06, 2022 |
| ASUSTek       | UX331UN                     | Notebook    | [f1cf640532](https://linux-hardware.org/?probe=f1cf640532) | Mar 06, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [0f5c637f94](https://linux-hardware.org/?probe=0f5c637f94) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [052e483cb5](https://linux-hardware.org/?probe=052e483cb5) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [19c66b47da](https://linux-hardware.org/?probe=19c66b47da) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [e66faafcce](https://linux-hardware.org/?probe=e66faafcce) | Mar 06, 2022 |
| HP            | 8266                        | Desktop     | [e0991ef205](https://linux-hardware.org/?probe=e0991ef205) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [7a52c91d68](https://linux-hardware.org/?probe=7a52c91d68) | Mar 05, 2022 |
| Unknown       | KN12A                       | Notebook    | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [1fb41e944f](https://linux-hardware.org/?probe=1fb41e944f) | Mar 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [1c879cd60e](https://linux-hardware.org/?probe=1c879cd60e) | Mar 04, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [7d46bb8f25](https://linux-hardware.org/?probe=7d46bb8f25) | Mar 03, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [fda73ff759](https://linux-hardware.org/?probe=fda73ff759) | Mar 02, 2022 |
| Dell          | Latitude E6530              | Notebook    | [f13c84346e](https://linux-hardware.org/?probe=f13c84346e) | Mar 02, 2022 |
| ASUSTek       | UX331UN                     | Notebook    | [463899cdb7](https://linux-hardware.org/?probe=463899cdb7) | Mar 02, 2022 |
| ASUSTek       | K55N                        | Notebook    | [6143b27a96](https://linux-hardware.org/?probe=6143b27a96) | Mar 02, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | H81M-E34                    | Desktop     | [563e906e47](https://linux-hardware.org/?probe=563e906e47) | Mar 01, 2022 |
| MSI           | 09AC                        | Desktop     | [a5c7015fca](https://linux-hardware.org/?probe=a5c7015fca) | Mar 01, 2022 |
| Schenker      | VIA 15                      | Notebook    | [c84aacc342](https://linux-hardware.org/?probe=c84aacc342) | Feb 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [f2e18241da](https://linux-hardware.org/?probe=f2e18241da) | Feb 28, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [25c0e14020](https://linux-hardware.org/?probe=25c0e14020) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d3f2971c3c](https://linux-hardware.org/?probe=d3f2971c3c) | Feb 27, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7db8c9806](https://linux-hardware.org/?probe=c7db8c9806) | Feb 27, 2022 |
| HP            | Notebook                    | Notebook    | [bcc74ebe77](https://linux-hardware.org/?probe=bcc74ebe77) | Feb 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [e0d39731a0](https://linux-hardware.org/?probe=e0d39731a0) | Feb 27, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [83dec4f285](https://linux-hardware.org/?probe=83dec4f285) | Feb 26, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [17586d38de](https://linux-hardware.org/?probe=17586d38de) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [fb4c469104](https://linux-hardware.org/?probe=fb4c469104) | Feb 26, 2022 |
| Biostar       | B450MH                      | Desktop     | [40f413ddcb](https://linux-hardware.org/?probe=40f413ddcb) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9013eb37ee](https://linux-hardware.org/?probe=9013eb37ee) | Feb 25, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [8e648c583a](https://linux-hardware.org/?probe=8e648c583a) | Feb 25, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [0149efd00d](https://linux-hardware.org/?probe=0149efd00d) | Feb 25, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [fbed153592](https://linux-hardware.org/?probe=fbed153592) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [904717059e](https://linux-hardware.org/?probe=904717059e) | Feb 24, 2022 |
| Unknown       | TB-4000                     | Desktop     | [70155eb876](https://linux-hardware.org/?probe=70155eb876) | Feb 24, 2022 |
| Toshiba       | IS 1412                     | Notebook    | [3621d1064d](https://linux-hardware.org/?probe=3621d1064d) | Feb 24, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [9d9c4fe241](https://linux-hardware.org/?probe=9d9c4fe241) | Feb 23, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [84b8eefa6d](https://linux-hardware.org/?probe=84b8eefa6d) | Feb 23, 2022 |
| Supermicro    | X10DAI                      | Desktop     | [4de85d4700](https://linux-hardware.org/?probe=4de85d4700) | Feb 23, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |
| Lenovo        | ThinkPad T430 23495P8       | Notebook    | [03266eea0a](https://linux-hardware.org/?probe=03266eea0a) | Feb 23, 2022 |
| HP            | Notebook                    | Notebook    | [93a85593c3](https://linux-hardware.org/?probe=93a85593c3) | Feb 23, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c4b59e08bc](https://linux-hardware.org/?probe=c4b59e08bc) | Feb 22, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [e1e83bde9c](https://linux-hardware.org/?probe=e1e83bde9c) | Feb 22, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [cc9d99be2a](https://linux-hardware.org/?probe=cc9d99be2a) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| Lenovo        | ThinkPad T460s 20F9S1G20... | Notebook    | [6a6c0b0b39](https://linux-hardware.org/?probe=6a6c0b0b39) | Feb 21, 2022 |
| Medion        | TJ4125                      | Desktop     | [04d5f95a16](https://linux-hardware.org/?probe=04d5f95a16) | Feb 21, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [0ee9dcd568](https://linux-hardware.org/?probe=0ee9dcd568) | Feb 20, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [a73c8072f9](https://linux-hardware.org/?probe=a73c8072f9) | Feb 20, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [a457ae32df](https://linux-hardware.org/?probe=a457ae32df) | Feb 20, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [e12ba75c05](https://linux-hardware.org/?probe=e12ba75c05) | Feb 19, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [5ee5668ab1](https://linux-hardware.org/?probe=5ee5668ab1) | Feb 19, 2022 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [a4a57f2b26](https://linux-hardware.org/?probe=a4a57f2b26) | Feb 19, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [259dd8bc78](https://linux-hardware.org/?probe=259dd8bc78) | Feb 19, 2022 |
| Lenovo        | ThinkPad L430 2468CTO       | Notebook    | [9244a0f8f9](https://linux-hardware.org/?probe=9244a0f8f9) | Feb 18, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [59a321d574](https://linux-hardware.org/?probe=59a321d574) | Feb 18, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [83a05f5d1e](https://linux-hardware.org/?probe=83a05f5d1e) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [ff74abc44d](https://linux-hardware.org/?probe=ff74abc44d) | Feb 18, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [ffb9eb537e](https://linux-hardware.org/?probe=ffb9eb537e) | Feb 17, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [9628754bf4](https://linux-hardware.org/?probe=9628754bf4) | Feb 17, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [c4314fa1c4](https://linux-hardware.org/?probe=c4314fa1c4) | Feb 17, 2022 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [4b198a6b46](https://linux-hardware.org/?probe=4b198a6b46) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [9fdad76c68](https://linux-hardware.org/?probe=9fdad76c68) | Feb 16, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d1f8637478](https://linux-hardware.org/?probe=d1f8637478) | Feb 16, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [9773bc9c72](https://linux-hardware.org/?probe=9773bc9c72) | Feb 16, 2022 |
| Dell          | Latitude E6320              | Notebook    | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [88c9f0db96](https://linux-hardware.org/?probe=88c9f0db96) | Feb 16, 2022 |
| Gateway       | IPISB-VR                    | Desktop     | [af56b8d361](https://linux-hardware.org/?probe=af56b8d361) | Feb 16, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [20aafa92dd](https://linux-hardware.org/?probe=20aafa92dd) | Feb 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [4e3b8bfbb1](https://linux-hardware.org/?probe=4e3b8bfbb1) | Feb 16, 2022 |
| Jumper        | EZbook                      | Notebook    | [f27f93bafe](https://linux-hardware.org/?probe=f27f93bafe) | Feb 16, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [725807db6f](https://linux-hardware.org/?probe=725807db6f) | Feb 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [3db88acec8](https://linux-hardware.org/?probe=3db88acec8) | Feb 15, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [905ad02036](https://linux-hardware.org/?probe=905ad02036) | Feb 14, 2022 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [d42d70a45a](https://linux-hardware.org/?probe=d42d70a45a) | Feb 14, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [b4db24332b](https://linux-hardware.org/?probe=b4db24332b) | Feb 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [5768ab0770](https://linux-hardware.org/?probe=5768ab0770) | Feb 13, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [9df9f66476](https://linux-hardware.org/?probe=9df9f66476) | Feb 13, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [fc4efd1eff](https://linux-hardware.org/?probe=fc4efd1eff) | Feb 13, 2022 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [524246985d](https://linux-hardware.org/?probe=524246985d) | Feb 13, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [fdba4d1aab](https://linux-hardware.org/?probe=fdba4d1aab) | Feb 13, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [c756082899](https://linux-hardware.org/?probe=c756082899) | Feb 13, 2022 |
| Google        | Homestar (rev3)             | Soc         | [313894dec8](https://linux-hardware.org/?probe=313894dec8) | Feb 12, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a98c8db3ad](https://linux-hardware.org/?probe=a98c8db3ad) | Feb 12, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5795d9b341](https://linux-hardware.org/?probe=5795d9b341) | Feb 12, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [a9271fbd9f](https://linux-hardware.org/?probe=a9271fbd9f) | Feb 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [ed39168e58](https://linux-hardware.org/?probe=ed39168e58) | Feb 12, 2022 |
| Dell          | Latitude 5580               | Notebook    | [77466f0d8f](https://linux-hardware.org/?probe=77466f0d8f) | Feb 11, 2022 |
| Dell          | Latitude 5580               | Notebook    | [8d65e0f7c7](https://linux-hardware.org/?probe=8d65e0f7c7) | Feb 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [5061491140](https://linux-hardware.org/?probe=5061491140) | Feb 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [cd89130dcd](https://linux-hardware.org/?probe=cd89130dcd) | Feb 11, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [11d24586e8](https://linux-hardware.org/?probe=11d24586e8) | Feb 11, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2885a7e3ed](https://linux-hardware.org/?probe=2885a7e3ed) | Feb 11, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| MSI           | Prestige 14 A10RB           | Notebook    | [7195cacd54](https://linux-hardware.org/?probe=7195cacd54) | Feb 10, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [fe18f09b36](https://linux-hardware.org/?probe=fe18f09b36) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [df5a829402](https://linux-hardware.org/?probe=df5a829402) | Feb 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [1564cdd40b](https://linux-hardware.org/?probe=1564cdd40b) | Feb 09, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [b53861af9b](https://linux-hardware.org/?probe=b53861af9b) | Feb 09, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [60c47d2f55](https://linux-hardware.org/?probe=60c47d2f55) | Feb 09, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [bca05a8467](https://linux-hardware.org/?probe=bca05a8467) | Feb 09, 2022 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [780b5cb42e](https://linux-hardware.org/?probe=780b5cb42e) | Feb 09, 2022 |
| Dell          | Latitude E5440              | Notebook    | [8ddea24991](https://linux-hardware.org/?probe=8ddea24991) | Feb 08, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [011e0963bd](https://linux-hardware.org/?probe=011e0963bd) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c3722a690](https://linux-hardware.org/?probe=9c3722a690) | Feb 07, 2022 |
| HP            | 0A60h                       | Desktop     | [8c9b5ec56f](https://linux-hardware.org/?probe=8c9b5ec56f) | Feb 06, 2022 |
| HP            | 843C                        | Desktop     | [65121c676e](https://linux-hardware.org/?probe=65121c676e) | Feb 06, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [0c22c792a0](https://linux-hardware.org/?probe=0c22c792a0) | Feb 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [4f80537faf](https://linux-hardware.org/?probe=4f80537faf) | Feb 06, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [784b1b0c3b](https://linux-hardware.org/?probe=784b1b0c3b) | Feb 06, 2022 |
| Dell          | System XPS L502X            | Notebook    | [c2a3b5d930](https://linux-hardware.org/?probe=c2a3b5d930) | Feb 05, 2022 |
| Medion        | E4241 MD60996               | Notebook    | [d89f5e4089](https://linux-hardware.org/?probe=d89f5e4089) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [f9a64bf682](https://linux-hardware.org/?probe=f9a64bf682) | Feb 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36bac5a046](https://linux-hardware.org/?probe=36bac5a046) | Feb 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4e8e488a2](https://linux-hardware.org/?probe=e4e8e488a2) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [1f4e97ac28](https://linux-hardware.org/?probe=1f4e97ac28) | Feb 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3e8a21888f](https://linux-hardware.org/?probe=3e8a21888f) | Feb 04, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| HP            | Laptop 15g-br1xx            | Notebook    | [092ea39c7e](https://linux-hardware.org/?probe=092ea39c7e) | Feb 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [4c55c42084](https://linux-hardware.org/?probe=4c55c42084) | Feb 03, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [a2fbd7d84e](https://linux-hardware.org/?probe=a2fbd7d84e) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [ba1cbdf586](https://linux-hardware.org/?probe=ba1cbdf586) | Feb 03, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [3df622872c](https://linux-hardware.org/?probe=3df622872c) | Feb 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [3035fdad91](https://linux-hardware.org/?probe=3035fdad91) | Feb 03, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [99abdcb1fe](https://linux-hardware.org/?probe=99abdcb1fe) | Feb 02, 2022 |

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
| Kubuntu 20.04   | 1342      | 46.44%  |
| Kubuntu 22.04   | 312       | 10.8%   |
| Kubuntu 20.10   | 254       | 8.79%   |
| Kubuntu 21.10   | 239       | 8.27%   |
| Kubuntu 21.04   | 212       | 7.34%   |
| Kubuntu 18.04   | 192       | 6.64%   |
| Kubuntu 19.10   | 178       | 6.16%   |
| Kubuntu 11      | 64        | 2.21%   |
| Kubuntu 11.1    | 25        | 0.87%   |
| Kubuntu 19.04   | 22        | 0.76%   |
| Kubuntu 16.04   | 12        | 0.42%   |
| Kubuntu 22.10   | 8         | 0.28%   |
| Kubuntu         | 8         | 0.28%   |
| Kubuntu 18.10   | 7         | 0.24%   |
| Kubuntu 2.0     | 6         | 0.21%   |
| Kubuntu 17.10   | 3         | 0.1%    |
| Kubuntu 17.04   | 2         | 0.07%   |
| Kubuntu 14.04   | 2         | 0.07%   |
| Kubuntu 20.08.3 | 1         | 0.03%   |
| Kubuntu 12.04   | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 2764      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 3.25%   |
| 5.4.0-52-generic  | 68        | 2.14%   |
| 5.4.0-58-generic  | 59        | 1.86%   |
| 5.4.0-48-generic  | 59        | 1.86%   |
| 5.13.0-39-generic | 52        | 1.64%   |
| 5.15.0-46-generic | 48        | 1.51%   |
| 5.4.0-40-generic  | 47        | 1.48%   |
| 5.13.0-28-generic | 44        | 1.39%   |
| 5.15.0-41-generic | 39        | 1.23%   |
| 5.11.0-37-generic | 38        | 1.2%    |
| 5.11.0-25-generic | 38        | 1.2%    |
| 5.13.0-30-generic | 37        | 1.17%   |
| 5.4.0-47-generic  | 36        | 1.14%   |
| 5.4.0-65-generic  | 35        | 1.1%    |
| 5.15.0-47-generic | 35        | 1.1%    |
| 5.8.0-48-generic  | 34        | 1.07%   |
| 5.3.0-40-generic  | 34        | 1.07%   |
| 5.4.0-37-generic  | 33        | 1.04%   |
| 5.4.0-29-generic  | 33        | 1.04%   |
| 5.13.0-22-generic | 31        | 0.98%   |
| 5.4.0-45-generic  | 30        | 0.95%   |
| 5.8.0-50-generic  | 29        | 0.91%   |
| 5.13.0-35-generic | 29        | 0.91%   |
| 5.8.0-63-generic  | 28        | 0.88%   |
| 5.4.0-54-generic  | 28        | 0.88%   |
| 5.3.0-26-generic  | 28        | 0.88%   |
| 5.13.0-40-generic | 28        | 0.88%   |
| 5.8.0-44-generic  | 27        | 0.85%   |
| 5.8.0-43-generic  | 27        | 0.85%   |
| 5.15.0-40-generic | 26        | 0.82%   |
| 5.11.0-22-generic | 26        | 0.82%   |
| 5.4.0-26-generic  | 25        | 0.79%   |
| 5.15.0-48-generic | 25        | 0.79%   |
| 5.15.0-27-generic | 25        | 0.79%   |
| 5.15.0-43-generic | 24        | 0.76%   |
| 5.13.0-27-generic | 24        | 0.76%   |
| 5.4.0-56-generic  | 23        | 0.73%   |
| 5.3.0-42-generic  | 23        | 0.73%   |
| 5.13.0-19-generic | 23        | 0.73%   |
| 5.11.0-27-generic | 23        | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 915       | 31.14%  |
| 5.8.0   | 404       | 13.75%  |
| 5.13.0  | 404       | 13.75%  |
| 5.15.0  | 327       | 11.13%  |
| 5.11.0  | 322       | 10.96%  |
| 5.3.0   | 224       | 7.62%   |
| 4.15.0  | 67        | 2.28%   |
| 5.0.0   | 36        | 1.23%   |
| 5.10.0  | 17        | 0.58%   |
| 5.6.0   | 15        | 0.51%   |
| 5.17.0  | 9         | 0.31%   |
| 4.4.0   | 9         | 0.31%   |
| 4.18.0  | 8         | 0.27%   |
| 5.14.0  | 7         | 0.24%   |
| 5.9.0   | 5         | 0.17%   |
| 5.7.0   | 4         | 0.14%   |
| 5.8.18  | 3         | 0.1%    |
| 5.18.4  | 3         | 0.1%    |
| 5.16.0  | 3         | 0.1%    |
| 5.12.8  | 3         | 0.1%    |
| 5.12.0  | 3         | 0.1%    |
| 4.13.0  | 3         | 0.1%    |
| 4.10.0  | 3         | 0.1%    |
| 5.9.16  | 2         | 0.07%   |
| 5.9.10  | 2         | 0.07%   |
| 5.8.5   | 2         | 0.07%   |
| 5.8.2   | 2         | 0.07%   |
| 5.8.12  | 2         | 0.07%   |
| 5.8.1   | 2         | 0.07%   |
| 5.7.10  | 2         | 0.07%   |
| 5.7.1   | 2         | 0.07%   |
| 5.5.13  | 2         | 0.07%   |
| 5.19.5  | 2         | 0.07%   |
| 5.19.0  | 2         | 0.07%   |
| 5.18.10 | 2         | 0.07%   |
| 5.17.5  | 2         | 0.07%   |
| 5.16.2  | 2         | 0.07%   |
| 5.16.10 | 2         | 0.07%   |
| 5.15.5  | 2         | 0.07%   |
| 5.15.34 | 2         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 922       | 31.42%  |
| 5.8     | 420       | 14.31%  |
| 5.13    | 414       | 14.11%  |
| 5.15    | 340       | 11.59%  |
| 5.11    | 328       | 11.18%  |
| 5.3     | 227       | 7.74%   |
| 4.15    | 68        | 2.32%   |
| 5.0     | 37        | 1.26%   |
| 5.10    | 28        | 0.95%   |
| 5.6     | 20        | 0.68%   |
| 5.17    | 16        | 0.55%   |
| 5.14    | 16        | 0.55%   |
| 5.9     | 13        | 0.44%   |
| 5.12    | 13        | 0.44%   |
| 5.7     | 11        | 0.37%   |
| 5.18    | 10        | 0.34%   |
| 4.18    | 10        | 0.34%   |
| 5.16    | 9         | 0.31%   |
| 4.4     | 9         | 0.31%   |
| 5.19    | 6         | 0.2%    |
| 5.5     | 5         | 0.17%   |
| 4.13    | 3         | 0.1%    |
| 4.10    | 3         | 0.1%    |
| 5.1     | 2         | 0.07%   |
| 6.0     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2748      | 99.42%  |
| i686    | 12        | 0.43%   |
| aarch64 | 3         | 0.11%   |
| riscv64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 1883      | 66.92%  |
| KDE      | 891       | 31.66%  |
| GNOME    | 9         | 0.32%   |
| Cinnamon | 9         | 0.32%   |
| Budgie   | 7         | 0.25%   |
| MATE     | 5         | 0.18%   |
| KDE4     | 3         | 0.11%   |
| XFCE     | 2         | 0.07%   |
| LXQt     | 2         | 0.07%   |
| Unity    | 1         | 0.04%   |
| GNUstep  | 1         | 0.04%   |
| Unknown  | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2674      | 96.15%  |
| Wayland | 80        | 2.88%   |
| Tty     | 27        | 0.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1550      | 55.02%  |
| Unknown | 1074      | 38.13%  |
| GDM     | 104       | 3.69%   |
| LightDM | 34        | 1.21%   |
| GDM3    | 32        | 1.14%   |
| TDM     | 21        | 0.75%   |
| SLiM    | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1134      | 40.57%  |
| de_DE   | 225       | 8.05%   |
| ru_RU   | 153       | 5.47%   |
| pt_BR   | 140       | 5.01%   |
| en_GB   | 136       | 4.87%   |
| fr_FR   | 127       | 4.54%   |
| it_IT   | 98        | 3.51%   |
| Unknown | 77        | 2.75%   |
| en_CA   | 66        | 2.36%   |
| es_ES   | 57        | 2.04%   |
| pl_PL   | 54        | 1.93%   |
| en_AU   | 53        | 1.9%    |
| en_IN   | 48        | 1.72%   |
| C       | 30        | 1.07%   |
| es_MX   | 23        | 0.82%   |
| ru_UA   | 22        | 0.79%   |
| hu_HU   | 22        | 0.79%   |
| en_ZA   | 19        | 0.68%   |
| cs_CZ   | 18        | 0.64%   |
| es_AR   | 17        | 0.61%   |
| de_AT   | 15        | 0.54%   |
| nl_NL   | 13        | 0.47%   |
| en_NZ   | 13        | 0.47%   |
| de_CH   | 12        | 0.43%   |
| sv_SE   | 9         | 0.32%   |
| pt_PT   | 9         | 0.32%   |
| es_CO   | 9         | 0.32%   |
| en_IL   | 9         | 0.32%   |
| tr_TR   | 8         | 0.29%   |
| en_IE   | 8         | 0.29%   |
| uk_UA   | 7         | 0.25%   |
| es_VE   | 7         | 0.25%   |
| el_GR   | 7         | 0.25%   |
| sl_SI   | 6         | 0.21%   |
| sk_SK   | 6         | 0.21%   |
| nl_BE   | 6         | 0.21%   |
| ja_JP   | 6         | 0.21%   |
| fi_FI   | 6         | 0.21%   |
| es_CL   | 6         | 0.21%   |
| ca_ES   | 6         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1566      | 55.73%  |
| BIOS | 1244      | 44.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2536      | 91.12%  |
| Btrfs    | 112       | 4.02%   |
| Overlay  | 64        | 2.3%    |
| Xfs      | 33        | 1.19%   |
| Zfs      | 17        | 0.61%   |
| Unknown  | 12        | 0.43%   |
| Ext3     | 3         | 0.11%   |
| Ext2     | 2         | 0.07%   |
| XXXX     | 1         | 0.04%   |
| Reiserfs | 1         | 0.04%   |
| Jfs      | 1         | 0.04%   |
| ExX4     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1316      | 47.03%  |
| GPT     | 1211      | 43.28%  |
| MBR     | 271       | 9.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2406      | 86.05%  |
| Yes       | 390       | 13.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1694      | 60.52%  |
| Yes       | 1105      | 39.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 444       | 16.06%  |
| Lenovo              | 411       | 14.87%  |
| Dell                | 395       | 14.29%  |
| Hewlett-Packard     | 380       | 13.75%  |
| Gigabyte Technology | 223       | 8.07%   |
| MSI                 | 191       | 6.91%   |
| Acer                | 121       | 4.38%   |
| ASRock              | 108       | 3.91%   |
| Samsung Electronics | 36        | 1.3%    |
| Apple               | 34        | 1.23%   |
| Intel               | 31        | 1.12%   |
| HUAWEI              | 24        | 0.87%   |
| Unknown             | 24        | 0.87%   |
| Toshiba             | 22        | 0.8%    |
| TUXEDO              | 18        | 0.65%   |
| Sony                | 17        | 0.62%   |
| Fujitsu             | 16        | 0.58%   |
| Notebook            | 15        | 0.54%   |
| Google              | 14        | 0.51%   |
| Positivo            | 12        | 0.43%   |
| Pegatron            | 12        | 0.43%   |
| Timi                | 10        | 0.36%   |
| Biostar             | 10        | 0.36%   |
| Medion              | 9         | 0.33%   |
| Alienware           | 9         | 0.33%   |
| ZOTAC               | 8         | 0.29%   |
| Packard Bell        | 8         | 0.29%   |
| Foxconn             | 8         | 0.29%   |
| Microsoft           | 7         | 0.25%   |
| ECS                 | 7         | 0.25%   |
| System76            | 6         | 0.22%   |
| Supermicro          | 6         | 0.22%   |
| Chuwi               | 6         | 0.22%   |
| PC Specialist       | 5         | 0.18%   |
| LG Electronics      | 5         | 0.18%   |
| Huanan              | 5         | 0.18%   |
| Fujitsu Siemens     | 5         | 0.18%   |
| Shuttle             | 4         | 0.14%   |
| Schenker            | 4         | 0.14%   |
| Razer               | 4         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 37        | 1.34%   |
| Unknown                            | 35        | 1.27%   |
| Gigabyte B450M DS3H                | 11        | 0.4%    |
| MSI MS-7C37                        | 9         | 0.33%   |
| ASUS ROG STRIX B550-F GAMING       | 9         | 0.33%   |
| HP Pavilion dv6                    | 8         | 0.29%   |
| HP Notebook                        | 8         | 0.29%   |
| Dell OptiPlex 9020                 | 8         | 0.29%   |
| MSI MS-7B79                        | 7         | 0.25%   |
| HUAWEI NBLK-WAX9X                  | 7         | 0.25%   |
| HP Pavilion g6                     | 7         | 0.25%   |
| Gigabyte 970A-DS3P                 | 7         | 0.25%   |
| Dell XPS 15 9560                   | 7         | 0.25%   |
| ASUS ROG STRIX X570-E GAMING       | 7         | 0.25%   |
| ASUS PRIME B450M-A                 | 7         | 0.25%   |
| MSI MS-7A34                        | 6         | 0.22%   |
| MSI MS-7817                        | 6         | 0.22%   |
| HP Pavilion dv7                    | 6         | 0.22%   |
| HP EliteBook 840 G5                | 6         | 0.22%   |
| HP EliteBook 840 G3                | 6         | 0.22%   |
| Gigabyte A320M-S2H                 | 6         | 0.22%   |
| ASUS PRIME B350-PLUS               | 6         | 0.22%   |
| MSI MS-7C02                        | 5         | 0.18%   |
| HP Pavilion 15                     | 5         | 0.18%   |
| HP EliteBook 840 G6                | 5         | 0.18%   |
| Gigabyte X570 AORUS MASTER         | 5         | 0.18%   |
| Dell XPS 15 9570                   | 5         | 0.18%   |
| Dell XPS 15 7590                   | 5         | 0.18%   |
| Dell XPS 13 9310                   | 5         | 0.18%   |
| Dell Latitude E6540                | 5         | 0.18%   |
| Dell Latitude 5480                 | 5         | 0.18%   |
| ASRock AB350 Pro4                  | 5         | 0.18%   |
| MSI MS-7693                        | 4         | 0.14%   |
| Lenovo Legion Y530-15ICH 81FV      | 4         | 0.14%   |
| Lenovo IdeaPad 330-15IKB 81DE      | 4         | 0.14%   |
| HP Laptop 15s-eq0xxx               | 4         | 0.14%   |
| HP ENVY x360 Convertible 13-ay0xxx | 4         | 0.14%   |
| HP EliteDesk 800 G1 SFF            | 4         | 0.14%   |
| HP 2000                            | 4         | 0.14%   |
| HP 15                              | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 198       | 7.16%   |
| Dell Latitude      | 109       | 3.94%   |
| Dell Inspiron      | 100       | 3.62%   |
| HP Pavilion        | 82        | 2.97%   |
| Acer Aspire        | 80        | 2.89%   |
| Lenovo IdeaPad     | 73        | 2.64%   |
| Dell XPS           | 59        | 2.13%   |
| ASUS PRIME         | 57        | 2.06%   |
| ASUS ROG           | 56        | 2.03%   |
| HP ProBook         | 47        | 1.7%    |
| HP EliteBook       | 47        | 1.7%    |
| HP Laptop          | 39        | 1.41%   |
| Dell Precision     | 37        | 1.34%   |
| ASUS All           | 37        | 1.34%   |
| Dell OptiPlex      | 36        | 1.3%    |
| Unknown            | 35        | 1.27%   |
| ASUS VivoBook      | 33        | 1.19%   |
| ASUS TUF           | 29        | 1.05%   |
| HP Compaq          | 24        | 0.87%   |
| Lenovo ThinkCentre | 23        | 0.83%   |
| HP ENVY            | 22        | 0.8%    |
| Dell Vostro        | 22        | 0.8%    |
| Lenovo Yoga        | 20        | 0.72%   |
| Toshiba Satellite  | 18        | 0.65%   |
| Gigabyte B450M     | 17        | 0.62%   |
| Lenovo Legion      | 16        | 0.58%   |
| Lenovo ThinkBook   | 15        | 0.54%   |
| Gigabyte X570      | 14        | 0.51%   |
| ASUS ZenBook       | 14        | 0.51%   |
| Acer Nitro         | 14        | 0.51%   |
| ASUS ASUS          | 11        | 0.4%    |
| Acer Swift         | 11        | 0.4%    |
| Gigabyte A320M-S2H | 10        | 0.36%   |
| MSI MS-7C37        | 9         | 0.33%   |
| HP ZBook           | 9         | 0.33%   |
| HP Notebook        | 8         | 0.29%   |
| HP EliteDesk       | 8         | 0.29%   |
| Gigabyte B550      | 8         | 0.29%   |
| Fujitsu ESPRIMO    | 8         | 0.29%   |
| Dell G3            | 8         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 362       | 13.1%   |
| 2020    | 337       | 12.19%  |
| 2018    | 330       | 11.94%  |
| 2017    | 221       | 8%      |
| 2013    | 208       | 7.53%   |
| 2012    | 199       | 7.2%    |
| 2011    | 174       | 6.3%    |
| 2021    | 169       | 6.11%   |
| 2014    | 169       | 6.11%   |
| 2016    | 136       | 4.92%   |
| 2015    | 134       | 4.85%   |
| 2010    | 106       | 3.84%   |
| 2008    | 81        | 2.93%   |
| 2009    | 68        | 2.46%   |
| 2007    | 30        | 1.09%   |
| 2022    | 22        | 0.8%    |
| 2006    | 9         | 0.33%   |
| Unknown | 5         | 0.18%   |
| 2005    | 3         | 0.11%   |
| 2004    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1534      | 55.5%   |
| Desktop        | 1055      | 38.17%  |
| Convertible    | 82        | 2.97%   |
| Mini pc        | 36        | 1.3%    |
| All in one     | 26        | 0.94%   |
| Tablet         | 18        | 0.65%   |
| Server         | 9         | 0.33%   |
| System on chip | 3         | 0.11%   |
| Other          | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2550      | 91.69%  |
| Enabled  | 231       | 8.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2745      | 99.31%  |
| Yes  | 19        | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 733       | 26.3%   |
| 4.01-8.0    | 617       | 22.14%  |
| 8.01-16.0   | 516       | 18.51%  |
| 3.01-4.0    | 356       | 12.77%  |
| 32.01-64.0  | 350       | 12.56%  |
| 64.01-256.0 | 80        | 2.87%   |
| 24.01-32.0  | 69        | 2.48%   |
| 1.01-2.0    | 47        | 1.69%   |
| 2.01-3.0    | 19        | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 779       | 26.01%  |
| 1.01-2.0   | 721       | 24.07%  |
| 4.01-8.0   | 670       | 22.37%  |
| 3.01-4.0   | 475       | 15.86%  |
| 8.01-16.0  | 223       | 7.45%   |
| 0.51-1.0   | 76        | 2.54%   |
| 16.01-24.0 | 30        | 1%      |
| 24.01-32.0 | 10        | 0.33%   |
| 32.01-64.0 | 6         | 0.2%    |
| 0.01-0.5   | 4         | 0.13%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1506      | 53.03%  |
| 2      | 774       | 27.25%  |
| 3      | 259       | 9.12%   |
| 4      | 146       | 5.14%   |
| 5      | 76        | 2.68%   |
| 6      | 35        | 1.23%   |
| 7      | 16        | 0.56%   |
| 0      | 11        | 0.39%   |
| 8      | 5         | 0.18%   |
| 9      | 4         | 0.14%   |
| 10     | 3         | 0.11%   |
| 12     | 2         | 0.07%   |
| 11     | 2         | 0.07%   |
| 13     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1827      | 65.55%  |
| Yes       | 960       | 34.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2372      | 85.69%  |
| No        | 396       | 14.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2124      | 76.49%  |
| No        | 653       | 23.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1812      | 64.95%  |
| No        | 978       | 35.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 494       | 17.84%  |
| Germany      | 302       | 10.91%  |
| Russia       | 220       | 7.95%   |
| Brazil       | 185       | 6.68%   |
| France       | 160       | 5.78%   |
| UK           | 126       | 4.55%   |
| Italy        | 126       | 4.55%   |
| Spain        | 85        | 3.07%   |
| Canada       | 74        | 2.67%   |
| Poland       | 70        | 2.53%   |
| Netherlands  | 67        | 2.42%   |
| Ukraine      | 60        | 2.17%   |
| Australia    | 51        | 1.84%   |
| India        | 50        | 1.81%   |
| Mexico       | 39        | 1.41%   |
| Hungary      | 36        | 1.3%    |
| Switzerland  | 35        | 1.26%   |
| Czechia      | 33        | 1.19%   |
| Austria      | 26        | 0.94%   |
| Belgium      | 25        | 0.9%    |
| Argentina    | 25        | 0.9%    |
| South Africa | 21        | 0.76%   |
| Greece       | 21        | 0.76%   |
| Indonesia    | 20        | 0.72%   |
| Sweden       | 19        | 0.69%   |
| Bulgaria     | 18        | 0.65%   |
| Turkey       | 16        | 0.58%   |
| Finland      | 16        | 0.58%   |
| Slovenia     | 15        | 0.54%   |
| Romania      | 15        | 0.54%   |
| Denmark      | 15        | 0.54%   |
| Colombia     | 14        | 0.51%   |
| Portugal     | 13        | 0.47%   |
| New Zealand  | 13        | 0.47%   |
| China        | 13        | 0.47%   |
| Belarus      | 13        | 0.47%   |
| Serbia       | 11        | 0.4%    |
| Israel       | 11        | 0.4%    |
| Ireland      | 11        | 0.4%    |
| Norway       | 10        | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 58        | 2.01%   |
| Berlin            | 29        | 1.01%   |
| St Petersburg     | 26        | 0.9%    |
| Paris             | 24        | 0.83%   |
| Hamburg           | 22        | 0.76%   |
| Warsaw            | 21        | 0.73%   |
| Sao Paulo         | 21        | 0.73%   |
| Rome              | 20        | 0.69%   |
| Budapest          | 19        | 0.66%   |
| Kyiv              | 18        | 0.62%   |
| Milan             | 17        | 0.59%   |
| Sydney            | 16        | 0.55%   |
| Rio de Janeiro    | 16        | 0.55%   |
| Madrid            | 16        | 0.55%   |
| Cologne           | 15        | 0.52%   |
| Amsterdam         | 15        | 0.52%   |
| Zurich            | 14        | 0.49%   |
| Vienna            | 13        | 0.45%   |
| Munich            | 13        | 0.45%   |
| Novosibirsk       | 12        | 0.42%   |
| Minsk             | 12        | 0.42%   |
| Frankfurt am Main | 12        | 0.42%   |
| Sofia             | 11        | 0.38%   |
| Prague            | 11        | 0.38%   |
| Melbourne         | 10        | 0.35%   |
| London            | 10        | 0.35%   |
| Jakarta           | 10        | 0.35%   |
| Athens            | 10        | 0.35%   |
| Seattle           | 9         | 0.31%   |
| Los Angeles       | 9         | 0.31%   |
| Dallas            | 9         | 0.31%   |
| Belgrade          | 9         | 0.31%   |
| Phoenix           | 8         | 0.28%   |
| Marseille         | 8         | 0.28%   |
| Brasília         | 8         | 0.28%   |
| Wroclaw           | 7         | 0.24%   |
| Sindelfingen      | 7         | 0.24%   |
| Montreal          | 7         | 0.24%   |
| Leipzig           | 7         | 0.24%   |
| Krakow            | 7         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 793       | 1187   | 18.12%  |
| WDC                 | 665       | 1086   | 15.2%   |
| Seagate             | 607       | 904    | 13.87%  |
| Toshiba             | 273       | 359    | 6.24%   |
| Kingston            | 260       | 312    | 5.94%   |
| SanDisk             | 215       | 253    | 4.91%   |
| Crucial             | 177       | 221    | 4.04%   |
| Unknown             | 152       | 190    | 3.47%   |
| Intel               | 130       | 177    | 2.97%   |
| Hitachi             | 120       | 145    | 2.74%   |
| SK hynix            | 112       | 132    | 2.56%   |
| HGST                | 84        | 106    | 1.92%   |
| A-DATA Technology   | 68        | 74     | 1.55%   |
| Micron Technology   | 60        | 67     | 1.37%   |
| Phison              | 35        | 49     | 0.8%    |
| KIOXIA              | 32        | 35     | 0.73%   |
| China               | 28        | 38     | 0.64%   |
| Transcend           | 27        | 29     | 0.62%   |
| Silicon Motion      | 27        | 31     | 0.62%   |
| Apple               | 24        | 27     | 0.55%   |
| PNY                 | 22        | 25     | 0.5%    |
| Patriot             | 22        | 28     | 0.5%    |
| Intenso             | 22        | 25     | 0.5%    |
| OCZ                 | 21        | 28     | 0.48%   |
| LITEON              | 21        | 23     | 0.48%   |
| SPCC                | 20        | 23     | 0.46%   |
| Corsair             | 18        | 24     | 0.41%   |
| Maxtor              | 16        | 17     | 0.37%   |
| GOODRAM             | 15        | 30     | 0.34%   |
| XPG                 | 14        | 15     | 0.32%   |
| JMicron Technology  | 14        | 16     | 0.32%   |
| KingSpec            | 13        | 15     | 0.3%    |
| Fujitsu             | 11        | 14     | 0.25%   |
| Unknown             | 11        | 11     | 0.25%   |
| Team                | 10        | 11     | 0.23%   |
| LITEONIT            | 9         | 11     | 0.21%   |
| Gigabyte Technology | 9         | 10     | 0.21%   |
| Apacer              | 9         | 14     | 0.21%   |
| SABRENT             | 8         | 9      | 0.18%   |
| Mushkin             | 8         | 8      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 48        | 0.98%   |
| Kingston SA400S37240G 240GB SSD    | 44        | 0.89%   |
| Samsung SSD 850 EVO 500GB          | 42        | 0.85%   |
| Samsung SSD 850 EVO 250GB          | 41        | 0.83%   |
| Samsung SSD 860 EVO 1TB            | 33        | 0.67%   |
| Samsung NVMe SSD Drive 500GB       | 33        | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB     | 31        | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 31        | 0.63%   |
| Samsung NVMe SSD Drive 1TB         | 30        | 0.61%   |
| Samsung NVMe SSD Drive 512GB       | 28        | 0.57%   |
| Kingston SA400S37480G 480GB SSD    | 28        | 0.57%   |
| Crucial CT1000MX500SSD1 1TB        | 26        | 0.53%   |
| Unknown MMC Card  32GB             | 25        | 0.51%   |
| Toshiba MQ01ABD100 1TB             | 25        | 0.51%   |
| Toshiba MQ04ABF100 1TB             | 24        | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB     | 23        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB           | 22        | 0.45%   |
| HGST HTS721010A9E630 1TB           | 22        | 0.45%   |
| Unknown MMC Card  64GB             | 21        | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB     | 20        | 0.41%   |
| Crucial CT500MX500SSD1 500GB       | 19        | 0.39%   |
| Toshiba DT01ACA100 1TB             | 18        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB     | 18        | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB     | 18        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB     | 18        | 0.37%   |
| SanDisk SSD PLUS 240GB             | 18        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB       | 18        | 0.37%   |
| Samsung SSD 860 EVO 250GB          | 18        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 17        | 0.35%   |
| Toshiba HDWD110 1TB                | 17        | 0.35%   |
| Seagate ST500LT012-1DG142 500GB    | 17        | 0.35%   |
| Seagate ST500DM002-1BD142 500GB    | 17        | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB     | 16        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB     | 16        | 0.33%   |
| Seagate Expansion 1TB              | 16        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD   | 16        | 0.33%   |
| Kingston SA400S37120G 120GB SSD    | 16        | 0.33%   |
| SanDisk NVMe SSD Drive 512GB       | 15        | 0.31%   |
| Samsung SSD 860 EVO M.2 500GB      | 15        | 0.31%   |
| Kingston SUV400S37240G 240GB SSD   | 15        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 594       | 876    | 35.83%  |
| WDC                 | 510       | 863    | 30.76%  |
| Toshiba             | 191       | 254    | 11.52%  |
| Hitachi             | 120       | 145    | 7.24%   |
| Samsung Electronics | 88        | 136    | 5.31%   |
| HGST                | 83        | 105    | 5.01%   |
| Unknown             | 19        | 22     | 1.15%   |
| Maxtor              | 15        | 16     | 0.9%    |
| Fujitsu             | 10        | 13     | 0.6%    |
| Apple               | 9         | 9      | 0.54%   |
| Hewlett-Packard     | 3         | 5      | 0.18%   |
| USB3.0              | 2         | 2      | 0.12%   |
| SAGE                | 2         | 2      | 0.12%   |
| JMicron Technology  | 2         | 2      | 0.12%   |
| WD MediaMax         | 1         | 1      | 0.06%   |
| USB                 | 1         | 1      | 0.06%   |
| Magnetic Data       | 1         | 2      | 0.06%   |
| LIO-ORG             | 1         | 1      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| ipTIME              | 1         | 1      | 0.06%   |
| IET                 | 1         | 1      | 0.06%   |
| HGST HTS            | 1         | 1      | 0.06%   |
| ASMT                | 1         | 1      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 427       | 582    | 27.8%   |
| Kingston            | 199       | 238    | 12.96%  |
| Crucial             | 154       | 195    | 10.03%  |
| SanDisk             | 149       | 175    | 9.7%    |
| WDC                 | 81        | 103    | 5.27%   |
| A-DATA Technology   | 47        | 52     | 3.06%   |
| Intel               | 41        | 50     | 2.67%   |
| Toshiba             | 28        | 40     | 1.82%   |
| Micron Technology   | 28        | 31     | 1.82%   |
| China               | 27        | 37     | 1.76%   |
| Transcend           | 22        | 22     | 1.43%   |
| Patriot             | 22        | 28     | 1.43%   |
| SK hynix            | 21        | 23     | 1.37%   |
| OCZ                 | 21        | 28     | 1.37%   |
| PNY                 | 19        | 22     | 1.24%   |
| Intenso             | 19        | 22     | 1.24%   |
| SPCC                | 18        | 20     | 1.17%   |
| LITEON              | 16        | 17     | 1.04%   |
| GOODRAM             | 15        | 30     | 0.98%   |
| KingSpec            | 13        | 15     | 0.85%   |
| Corsair             | 11        | 15     | 0.72%   |
| Apple               | 10        | 10     | 0.65%   |
| Team                | 9         | 9      | 0.59%   |
| LITEONIT            | 9         | 11     | 0.59%   |
| Apacer              | 9         | 14     | 0.59%   |
| Mushkin             | 7         | 7      | 0.46%   |
| Verbatim            | 5         | 5      | 0.33%   |
| Plextor             | 5         | 6      | 0.33%   |
| Emtec               | 5         | 5      | 0.33%   |
| ASMT                | 5         | 6      | 0.33%   |
| Unknown             | 4         | 4      | 0.26%   |
| Seagate             | 4         | 9      | 0.26%   |
| KingDian            | 4         | 5      | 0.26%   |
| Unknown             | 4         | 4      | 0.26%   |
| Zheino              | 3         | 5      | 0.2%    |
| TO Exter            | 3         | 3      | 0.2%    |
| Netac               | 3         | 4      | 0.2%    |
| Lexar               | 3         | 3      | 0.2%    |
| Gigabyte Technology | 3         | 3      | 0.2%    |
| Drevo               | 3         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1332      | 2461   | 34.57%  |
| SSD     | 1313      | 1935   | 34.08%  |
| NVMe    | 1024      | 1383   | 26.58%  |
| MMC     | 132       | 165    | 3.43%   |
| Unknown | 52        | 72     | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2049      | 4257   | 61.04%  |
| NVMe | 1015      | 1360   | 30.24%  |
| SAS  | 161       | 234    | 4.8%    |
| MMC  | 132       | 165    | 3.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1457      | 2254   | 51.32%  |
| 0.51-1.0   | 892       | 1355   | 31.42%  |
| 1.01-2.0   | 275       | 429    | 9.69%   |
| 3.01-4.0   | 93        | 167    | 3.28%   |
| 2.01-3.0   | 71        | 102    | 2.5%    |
| 4.01-10.0  | 44        | 78     | 1.55%   |
| 10.01-20.0 | 7         | 11     | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 724       | 25.3%   |
| 251-500        | 687       | 24%     |
| 501-1000       | 521       | 18.2%   |
| 1001-2000      | 279       | 9.75%   |
| More than 3000 | 213       | 7.44%   |
| 51-100         | 154       | 5.38%   |
| 2001-3000      | 124       | 4.33%   |
| 1-20           | 74        | 2.59%   |
| 21-50          | 73        | 2.55%   |
| Unknown        | 13        | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 699       | 23.67%  |
| 101-250        | 494       | 16.73%  |
| 21-50          | 460       | 15.58%  |
| 51-100         | 389       | 13.17%  |
| 251-500        | 339       | 11.48%  |
| 501-1000       | 262       | 8.87%   |
| 1001-2000      | 142       | 4.81%   |
| More than 3000 | 105       | 3.56%   |
| 2001-3000      | 50        | 1.69%   |
| Unknown        | 13        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 5         | 6      | 1.55%   |
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 1.24%   |
| Seagate ST31000524AS 1TB              | 4         | 5      | 1.24%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 10     | 1.24%   |
| Seagate ST1000DM003-1CH162 1TB        | 4         | 9      | 1.24%   |
| Toshiba MQ01ABD100 1TB                | 3         | 5      | 0.93%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.93%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 0.93%   |
| Seagate ST31000528AS 1TB              | 3         | 3      | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB        | 3         | 3      | 0.93%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.93%   |
| Hitachi HTS547564A9E384 640GB         | 3         | 3      | 0.93%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 0.93%   |
| Crucial CT1050MX300SSD1 1TB           | 3         | 3      | 0.93%   |
| WDC WD5000AAKS-00V1A0 500GB           | 2         | 3      | 0.62%   |
| WDC WD5000AAKS-00A7B0 500GB           | 2         | 2      | 0.62%   |
| WDC WD3200JD-22KLB0 320GB             | 2         | 2      | 0.62%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 4      | 0.62%   |
| WDC WD15EARS-00Z5B1 1TB               | 2         | 2      | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 2      | 0.62%   |
| WDC WD1001FALS-40U9B0 1TB             | 2         | 2      | 0.62%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 0.62%   |
| Toshiba MK1652GSX 160GB               | 2         | 2      | 0.62%   |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.62%   |
| SK hynix SC401 SATA 512GB SSD         | 2         | 2      | 0.62%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.62%   |
| Seagate ST9250315AS 250GB             | 2         | 3      | 0.62%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 0.62%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.62%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.62%   |
| Seagate ST32000542AS 2TB              | 2         | 2      | 0.62%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 2      | 0.62%   |
| SanDisk SSD PLUS 240GB                | 2         | 2      | 0.62%   |
| SanDisk SSD PLUS 240 GB               | 2         | 2      | 0.62%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 0.62%   |
| Samsung Electronics SSD 840 EVO 500GB | 2         | 3      | 0.62%   |
| Samsung Electronics HD502HJ 500GB     | 2         | 2      | 0.62%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 2      | 0.62%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 93     | 23.4%   |
| WDC                 | 68        | 83     | 21.79%  |
| Samsung Electronics | 32        | 38     | 10.26%  |
| Toshiba             | 29        | 34     | 9.29%   |
| Hitachi             | 20        | 20     | 6.41%   |
| Crucial             | 13        | 16     | 4.17%   |
| HGST                | 12        | 13     | 3.85%   |
| SanDisk             | 11        | 11     | 3.53%   |
| Intel               | 9         | 9      | 2.88%   |
| SK hynix            | 8         | 8      | 2.56%   |
| Kingston            | 6         | 6      | 1.92%   |
| A-DATA Technology   | 5         | 5      | 1.6%    |
| Micron Technology   | 4         | 4      | 1.28%   |
| OCZ                 | 3         | 3      | 0.96%   |
| Maxtor              | 3         | 4      | 0.96%   |
| Apple               | 3         | 3      | 0.96%   |
| Fujitsu             | 2         | 2      | 0.64%   |
| Zheino              | 1         | 2      | 0.32%   |
| XPG                 | 1         | 1      | 0.32%   |
| VENO                | 1         | 1      | 0.32%   |
| tecmiyo             | 1         | 2      | 0.32%   |
| SPCC                | 1         | 1      | 0.32%   |
| Mushkin             | 1         | 1      | 0.32%   |
| LITEONIT            | 1         | 1      | 0.32%   |
| Drevo               | 1         | 1      | 0.32%   |
| BAITITON            | 1         | 1      | 0.32%   |
| ASMT                | 1         | 1      | 0.32%   |
| ASENNO              | 1         | 1      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 93     | 32.74%  |
| WDC                 | 67        | 82     | 30.04%  |
| Toshiba             | 25        | 30     | 11.21%  |
| Hitachi             | 20        | 20     | 8.97%   |
| Samsung Electronics | 17        | 22     | 7.62%   |
| HGST                | 12        | 13     | 5.38%   |
| Maxtor              | 3         | 4      | 1.35%   |
| Apple               | 3         | 3      | 1.35%   |
| Fujitsu             | 2         | 2      | 0.9%    |
| ASMT                | 1         | 1      | 0.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 204       | 270    | 70.1%   |
| SSD  | 71        | 79     | 24.4%   |
| NVMe | 16        | 16     | 5.5%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB         | 1         | 1      | 20%     |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 20%     |
| OCZ VERTEX460A 480GB SSD          | 1         | 1      | 20%     |
| Intel SSDSC2KB960G8 960GB         | 1         | 1      | 20%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| OCZ                 | 1         | 1      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1414      | 3189   | 45.52%  |
| Works    | 1402      | 2457   | 45.14%  |
| Malfunc  | 286       | 365    | 9.21%   |
| Failed   | 4         | 5      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1788      | 49.12%  |
| AMD                              | 637       | 17.5%   |
| Samsung Electronics              | 347       | 9.53%   |
| SanDisk                          | 167       | 4.59%   |
| SK hynix                         | 90        | 2.47%   |
| ASMedia Technology               | 67        | 1.84%   |
| Kingston Technology Company      | 65        | 1.79%   |
| Toshiba America Info Systems     | 63        | 1.73%   |
| Phison Electronics               | 55        | 1.51%   |
| JMicron Technology               | 41        | 1.13%   |
| Silicon Motion                   | 38        | 1.04%   |
| Marvell Technology Group         | 35        | 0.96%   |
| Micron Technology                | 33        | 0.91%   |
| Nvidia                           | 32        | 0.88%   |
| Micron/Crucial Technology        | 31        | 0.85%   |
| ADATA Technology                 | 31        | 0.85%   |
| KIOXIA                           | 27        | 0.74%   |
| Realtek Semiconductor            | 15        | 0.41%   |
| Broadcom / LSI                   | 10        | 0.27%   |
| Solid State Storage Technology   | 9         | 0.25%   |
| Lite-On Technology               | 9         | 0.25%   |
| VIA Technologies                 | 7         | 0.19%   |
| Silicon Image                    | 7         | 0.19%   |
| Union Memory (Shenzhen)          | 6         | 0.16%   |
| LSI Logic / Symbios Logic        | 6         | 0.16%   |
| Lenovo                           | 4         | 0.11%   |
| Apple                            | 4         | 0.11%   |
| Seagate Technology               | 3         | 0.08%   |
| Unknown                          | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| Integrated Technology Express    | 2         | 0.05%   |
| Adaptec                          | 2         | 0.05%   |
| Zhaoxin                          | 1         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Promise Technology               | 1         | 0.03%   |
| 3ware                            | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 457       | 10.98%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 221       | 5.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 156       | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 142       | 3.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 130       | 3.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 114       | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                         | 96        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 82        | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 75        | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 74        | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 72        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 69        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 64        | 1.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 61        | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                            | 58        | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 57        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 53        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                | 51        | 1.23%   |
| Intel SSD 660P Series                                                          | 51        | 1.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 51        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 48        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 44        | 1.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 44        | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 43        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 42        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 41        | 0.98%   |
| Intel SATA Controller [RAID mode]                                              | 40        | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 40        | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 37        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 37        | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 36        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 35        | 0.84%   |
| Micron Non-Volatile memory controller                                          | 33        | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                         | 33        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 31        | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 31        | 0.74%   |
| AMD FCH SATA Controller D                                                      | 30        | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 28        | 0.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 27        | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 27        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2076      | 56.99%  |
| NVMe | 1014      | 27.83%  |
| IDE  | 278       | 7.63%   |
| RAID | 259       | 7.11%   |
| SAS  | 10        | 0.27%   |
| SCSI | 6         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2001      | 72.4%   |
| AMD           | 758       | 27.42%  |
| ARM           | 2         | 0.07%   |
| sifive,u74-mc | 1         | 0.04%   |
| QUALCOMM      | 1         | 0.04%   |
| CentaurHauls  | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 1.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 1.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 34        | 1.23%   |
| AMD Ryzen 5 3600 6-Core Processor             | 34        | 1.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 33        | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 33        | 1.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 31        | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 31        | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 30        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 27        | 0.98%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 26        | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 25        | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 24        | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 22        | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 22        | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 21        | 0.76%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 19        | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 18        | 0.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 17        | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 16        | 0.58%   |
| AMD FX-8350 Eight-Core Processor              | 16        | 0.58%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 15        | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 15        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 14        | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 14        | 0.51%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 14        | 0.51%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 13        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.47%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 13        | 0.47%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 13        | 0.47%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 0.47%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 13        | 0.47%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 13        | 0.47%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 13        | 0.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 674       | 24.34%  |
| Intel Core i5           | 627       | 22.64%  |
| AMD Ryzen 5             | 217       | 7.84%   |
| AMD Ryzen 7             | 156       | 5.63%   |
| Other                   | 153       | 5.53%   |
| Intel Core i3           | 152       | 5.49%   |
| Intel Celeron           | 89        | 3.21%   |
| Intel Core 2 Duo        | 70        | 2.53%   |
| Intel Xeon              | 64        | 2.31%   |
| AMD Ryzen 9             | 55        | 1.99%   |
| AMD FX                  | 54        | 1.95%   |
| Intel Pentium           | 50        | 1.81%   |
| AMD Ryzen 3             | 35        | 1.26%   |
| AMD A10                 | 28        | 1.01%   |
| Intel Core i9           | 24        | 0.87%   |
| Intel Atom              | 24        | 0.87%   |
| AMD A6                  | 22        | 0.79%   |
| AMD A8                  | 21        | 0.76%   |
| Intel Pentium Dual-Core | 20        | 0.72%   |
| Intel Core 2 Quad       | 19        | 0.69%   |
| AMD Ryzen 7 PRO         | 19        | 0.69%   |
| AMD Phenom II X4        | 18        | 0.65%   |
| AMD Athlon II X4        | 13        | 0.47%   |
| AMD A4                  | 12        | 0.43%   |
| Intel Pentium Silver    | 10        | 0.36%   |
| AMD Athlon              | 9         | 0.33%   |
| Intel Genuine           | 8         | 0.29%   |
| AMD Ryzen Threadripper  | 8         | 0.29%   |
| AMD Ryzen 5 PRO         | 8         | 0.29%   |
| Intel Pentium Dual      | 7         | 0.25%   |
| AMD E1                  | 7         | 0.25%   |
| AMD E                   | 7         | 0.25%   |
| AMD E2                  | 6         | 0.22%   |
| AMD Athlon II X2        | 6         | 0.22%   |
| AMD Athlon 64 X2        | 6         | 0.22%   |
| Intel Core m3           | 5         | 0.18%   |
| Intel Core 2            | 5         | 0.18%   |
| Intel Celeron Dual-Core | 5         | 0.18%   |
| AMD Phenom II X2        | 5         | 0.18%   |
| Intel Pentium 4         | 4         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1149      | 41.51%  |
| 2       | 912       | 32.95%  |
| 6       | 348       | 12.57%  |
| 8       | 230       | 8.31%   |
| 12      | 47        | 1.7%    |
| 1       | 30        | 1.08%   |
| 16      | 23        | 0.83%   |
| 10      | 7         | 0.25%   |
| 14      | 6         | 0.22%   |
| 3       | 5         | 0.18%   |
| 20      | 3         | 0.11%   |
| 32      | 2         | 0.07%   |
| 24      | 2         | 0.07%   |
| 18      | 2         | 0.07%   |
| Unknown | 2         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2742      | 99.2%   |
| 2       | 19        | 0.69%   |
| Unknown | 2         | 0.07%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2058      | 74.3%   |
| 1       | 710       | 25.63%  |
| Unknown | 2         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2760      | 99.86%  |
| 32-bit         | 2         | 0.07%   |
| Unknown        | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 602       | 21.17%  |
| 0x306a9    | 151       | 5.31%   |
| 0x206a7    | 141       | 4.96%   |
| 0x306c3    | 137       | 4.82%   |
| 0x906ea    | 103       | 3.62%   |
| 0x806ec    | 92        | 3.23%   |
| 0x40651    | 73        | 2.57%   |
| 0x806ea    | 72        | 2.53%   |
| 0x806c1    | 71        | 2.5%    |
| 0x1067a    | 68        | 2.39%   |
| 0x08701021 | 66        | 2.32%   |
| 0x806e9    | 65        | 2.29%   |
| 0x906e9    | 60        | 2.11%   |
| 0x506e3    | 57        | 2%      |
| 0x406e3    | 49        | 1.72%   |
| 0x08108109 | 42        | 1.48%   |
| 0x0800820d | 42        | 1.48%   |
| 0x306d4    | 40        | 1.41%   |
| 0x08701013 | 38        | 1.34%   |
| 0x08600106 | 36        | 1.27%   |
| 0x06000852 | 35        | 1.23%   |
| 0x08108102 | 34        | 1.2%    |
| 0xa0652    | 30        | 1.05%   |
| 0x806eb    | 30        | 1.05%   |
| 0x706e5    | 28        | 0.98%   |
| 0x0a50000c | 27        | 0.95%   |
| 0x906ed    | 24        | 0.84%   |
| 0x010000c8 | 24        | 0.84%   |
| 0x20655    | 23        | 0.81%   |
| 0x406c4    | 21        | 0.74%   |
| 0x706a1    | 20        | 0.7%    |
| 0x30678    | 18        | 0.63%   |
| 0x06001119 | 18        | 0.63%   |
| 0x08600104 | 17        | 0.6%    |
| 0x6fb      | 16        | 0.56%   |
| 0x10676    | 16        | 0.56%   |
| 0x306f2    | 15        | 0.53%   |
| 0xa0653    | 14        | 0.49%   |
| 0x506c9    | 14        | 0.49%   |
| 0x20652    | 14        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 548       | 19.78%  |
| Haswell          | 286       | 10.32%  |
| Zen 2            | 205       | 7.4%    |
| IvyBridge        | 191       | 6.89%   |
| SandyBridge      | 176       | 6.35%   |
| Zen+             | 145       | 5.23%   |
| Skylake          | 144       | 5.2%    |
| Penryn           | 100       | 3.61%   |
| TigerLake        | 99        | 3.57%   |
| Zen 3            | 73        | 2.63%   |
| Zen              | 71        | 2.56%   |
| CometLake        | 71        | 2.56%   |
| Piledriver       | 70        | 2.53%   |
| Westmere         | 57        | 2.06%   |
| K10              | 56        | 2.02%   |
| IceLake          | 53        | 1.91%   |
| Broadwell        | 52        | 1.88%   |
| Silvermont       | 49        | 1.77%   |
| Goldmont plus    | 45        | 1.62%   |
| Core             | 45        | 1.62%   |
| Unknown          | 37        | 1.34%   |
| Excavator        | 34        | 1.23%   |
| Nehalem          | 32        | 1.15%   |
| Goldmont         | 18        | 0.65%   |
| Steamroller      | 16        | 0.58%   |
| Puma             | 15        | 0.54%   |
| K8 Hammer        | 13        | 0.47%   |
| K10 Llano        | 13        | 0.47%   |
| Bobcat           | 13        | 0.47%   |
| Jaguar           | 12        | 0.43%   |
| Alderlake Hybrid | 10        | 0.36%   |
| NetBurst         | 7         | 0.25%   |
| Bulldozer        | 7         | 0.25%   |
| Bonnell          | 5         | 0.18%   |
| Tremont          | 1         | 0.04%   |
| K8 & K10 hybrid  | 1         | 0.04%   |
| K6               | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1537      | 46.11%  |
| Nvidia                           | 1016      | 30.48%  |
| AMD                              | 768       | 23.04%  |
| ASPEED Technology                | 5         | 0.15%   |
| Matrox Electronics Systems       | 4         | 0.12%   |
| Zhaoxin                          | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 120       | 3.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 109       | 3.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 98        | 2.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 93        | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 92        | 2.7%    |
| AMD Renoir                                                                               | 85        | 2.49%   |
| Intel UHD Graphics 620                                                                   | 81        | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 80        | 2.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 79        | 2.32%   |
| Intel HD Graphics 620                                                                    | 67        | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 63        | 1.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 62        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 60        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 57        | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 56        | 1.64%   |
| Intel HD Graphics 630                                                                    | 47        | 1.38%   |
| Intel HD Graphics 5500                                                                   | 44        | 1.29%   |
| Intel HD Graphics 530                                                                    | 44        | 1.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 39        | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 39        | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 1.06%   |
| AMD Cezanne                                                                              | 34        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 33        | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 30        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 26        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 26        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 23        | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 21        | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 20        | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 20        | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 18        | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 18        | 0.53%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 18        | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.53%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 18        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1020      | 36.76%  |
| 1 x AMD                  | 604       | 21.77%  |
| 1 x Nvidia               | 537       | 19.35%  |
| Intel + Nvidia           | 419       | 15.1%   |
| Intel + AMD              | 75        | 2.7%    |
| 2 x AMD                  | 47        | 1.69%   |
| AMD + Nvidia             | 42        | 1.51%   |
| 2 x Nvidia               | 13        | 0.47%   |
| Other                    | 5         | 0.18%   |
| 1 x ASPEED               | 3         | 0.11%   |
| Nvidia + Matrox          | 2         | 0.07%   |
| Nvidia + ASPEED          | 2         | 0.07%   |
| 3 x Nvidia               | 1         | 0.04%   |
| 1 x Zhaoxin              | 1         | 0.04%   |
| 1 x SiS                  | 1         | 0.04%   |
| 1 x Matrox               | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2013      | 71.94%  |
| Proprietary | 728       | 26.02%  |
| Unknown     | 57        | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1449      | 51.17%  |
| 1.01-2.0   | 366       | 12.92%  |
| 0.01-0.5   | 243       | 8.58%   |
| 3.01-4.0   | 235       | 8.3%    |
| 0.51-1.0   | 230       | 8.12%   |
| 7.01-8.0   | 155       | 5.47%   |
| 5.01-6.0   | 88        | 3.11%   |
| 2.01-3.0   | 30        | 1.06%   |
| 8.01-16.0  | 30        | 1.06%   |
| 4.01-5.0   | 3         | 0.11%   |
| 16.01-24.0 | 2         | 0.07%   |
| 32.01-64.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 410       | 12.55%  |
| AU Optronics            | 357       | 10.93%  |
| LG Display              | 289       | 8.85%   |
| Chimei Innolux          | 262       | 8.02%   |
| BOE                     | 259       | 7.93%   |
| Dell                    | 222       | 6.8%    |
| Goldstar                | 174       | 5.33%   |
| Acer                    | 129       | 3.95%   |
| Hewlett-Packard         | 108       | 3.31%   |
| BenQ                    | 92        | 2.82%   |
| AOC                     | 88        | 2.69%   |
| Ancor Communications    | 86        | 2.63%   |
| Sharp                   | 83        | 2.54%   |
| Philips                 | 74        | 2.27%   |
| Lenovo                  | 48        | 1.47%   |
| ViewSonic               | 45        | 1.38%   |
| Iiyama                  | 39        | 1.19%   |
| PANDA                   | 38        | 1.16%   |
| Chi Mei Optoelectronics | 36        | 1.1%    |
| ASUSTek Computer        | 31        | 0.95%   |
| LG Electronics          | 28        | 0.86%   |
| Apple                   | 28        | 0.86%   |
| Unknown                 | 22        | 0.67%   |
| InfoVision              | 22        | 0.67%   |
| Sony                    | 19        | 0.58%   |
| Panasonic               | 17        | 0.52%   |
| NEC Computers           | 16        | 0.49%   |
| HannStar                | 10        | 0.31%   |
| Eizo                    | 10        | 0.31%   |
| Medion                  | 8         | 0.24%   |
| CSO                     | 8         | 0.24%   |
| Vizio                   | 7         | 0.21%   |
| MSI                     | 7         | 0.21%   |
| Idek Iiyama             | 7         | 0.21%   |
| Vestel Elektronik       | 6         | 0.18%   |
| Toshiba                 | 6         | 0.18%   |
| Sceptre Tech            | 6         | 0.18%   |
| LG Philips              | 5         | 0.15%   |
| Seiko/Epson             | 4         | 0.12%   |
| Gateway                 | 4         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 18        | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 16        | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 15        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 15        | 0.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 14        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 14        | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 13        | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 11        | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 11        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 11        | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 10        | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.23%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 7         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7         | 0.2%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 7         | 0.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 7         | 0.2%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 7         | 0.2%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.2%    |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 6         | 0.18%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 6         | 0.18%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 6         | 0.18%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 6         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 6         | 0.18%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.18%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 6         | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 6         | 0.18%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 6         | 0.18%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 6         | 0.18%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6         | 0.18%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 6         | 0.18%   |
| Dell U3415W DELA0A6 3440x1440 798x335mm 34.1-inch                     | 6         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.18%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch      | 6         | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 6         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1481      | 47.93%  |
| 1366x768 (WXGA)    | 464       | 15.02%  |
| 3840x2160 (4K)     | 214       | 6.93%   |
| 2560x1440 (QHD)    | 152       | 4.92%   |
| 1600x900 (HD+)     | 114       | 3.69%   |
| 1920x1200 (WUXGA)  | 92        | 2.98%   |
| 1680x1050 (WSXGA+) | 75        | 2.43%   |
| 1280x1024 (SXGA)   | 71        | 2.3%    |
| Unknown            | 68        | 2.2%    |
| 1440x900 (WXGA+)   | 42        | 1.36%   |
| 2560x1080          | 33        | 1.07%   |
| 3440x1440          | 32        | 1.04%   |
| 1280x800 (WXGA)    | 32        | 1.04%   |
| 3840x1080          | 26        | 0.84%   |
| 1360x768           | 25        | 0.81%   |
| 2560x1600          | 18        | 0.58%   |
| 2160x1440          | 14        | 0.45%   |
| 3840x2400          | 12        | 0.39%   |
| 2880x1800          | 12        | 0.39%   |
| 1600x1200          | 9         | 0.29%   |
| 1024x768 (XGA)     | 9         | 0.29%   |
| 3840x1200          | 8         | 0.26%   |
| 1920x540           | 8         | 0.26%   |
| 3200x1800 (QHD+)   | 7         | 0.23%   |
| 4480x1440          | 6         | 0.19%   |
| 1920x1280          | 4         | 0.13%   |
| 5760x1080          | 3         | 0.1%    |
| 3840x1600          | 3         | 0.1%    |
| 3600x1080          | 3         | 0.1%    |
| 3456x2160          | 3         | 0.1%    |
| 3200x1080          | 3         | 0.1%    |
| 2736x1824          | 3         | 0.1%    |
| 2288x1287          | 3         | 0.1%    |
| 7680x2160          | 2         | 0.06%   |
| 5760x2160          | 2         | 0.06%   |
| 4480x1080          | 2         | 0.06%   |
| 3600x1200          | 2         | 0.06%   |
| 2520x1680          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 803       | 24.71%  |
| 13      | 274       | 8.43%   |
| 24      | 270       | 8.31%   |
| 27      | 266       | 8.18%   |
| 14      | 238       | 7.32%   |
| 23      | 229       | 7.05%   |
| Unknown | 206       | 6.34%   |
| 21      | 181       | 5.57%   |
| 17      | 181       | 5.57%   |
| 31      | 76        | 2.34%   |
| 19      | 66        | 2.03%   |
| 34      | 58        | 1.78%   |
| 22      | 51        | 1.57%   |
| 20      | 45        | 1.38%   |
| 12      | 44        | 1.35%   |
| 18      | 39        | 1.2%    |
| 11      | 35        | 1.08%   |
| 84      | 19        | 0.58%   |
| 16      | 19        | 0.58%   |
| 32      | 18        | 0.55%   |
| 25      | 16        | 0.49%   |
| 54      | 14        | 0.43%   |
| 72      | 13        | 0.4%    |
| 40      | 10        | 0.31%   |
| 26      | 7         | 0.22%   |
| 47      | 6         | 0.18%   |
| 46      | 6         | 0.18%   |
| 42      | 6         | 0.18%   |
| 52      | 5         | 0.15%   |
| 48      | 5         | 0.15%   |
| 60      | 4         | 0.12%   |
| 39      | 4         | 0.12%   |
| 37      | 4         | 0.12%   |
| 28      | 4         | 0.12%   |
| 43      | 3         | 0.09%   |
| 29      | 3         | 0.09%   |
| 10      | 3         | 0.09%   |
| 142     | 2         | 0.06%   |
| 65      | 2         | 0.06%   |
| 55      | 2         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1197      | 37.87%  |
| 501-600        | 688       | 21.77%  |
| 401-500        | 334       | 10.57%  |
| 201-300        | 217       | 6.86%   |
| 351-400        | 214       | 6.77%   |
| Unknown        | 206       | 6.52%   |
| 601-700        | 113       | 3.57%   |
| 701-800        | 79        | 2.5%    |
| 1001-1500      | 47        | 1.49%   |
| 1501-2000      | 33        | 1.04%   |
| 801-900        | 19        | 0.6%    |
| 901-1000       | 9         | 0.28%   |
| More than 2000 | 2         | 0.06%   |
| 1-100          | 2         | 0.06%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2171      | 76.2%   |
| 16/10   | 294       | 10.32%  |
| Unknown | 182       | 6.39%   |
| 5/4     | 69        | 2.42%   |
| 21/9    | 63        | 2.21%   |
| 3/2     | 30        | 1.05%   |
| 4/3     | 23        | 0.81%   |
| 32/9    | 8         | 0.28%   |
| 6/5     | 2         | 0.07%   |
| 1.96    | 2         | 0.07%   |
| 1.00    | 2         | 0.07%   |
| 1.98    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 801       | 25.11%  |
| 201-250        | 546       | 17.12%  |
| 81-90          | 391       | 12.26%  |
| 301-350        | 271       | 8.5%    |
| Unknown        | 206       | 6.46%   |
| 151-200        | 163       | 5.11%   |
| 351-500        | 158       | 4.95%   |
| 71-80          | 129       | 4.04%   |
| 121-130        | 129       | 4.04%   |
| 251-300        | 106       | 3.32%   |
| More than 1000 | 64        | 2.01%   |
| 141-150        | 64        | 2.01%   |
| 501-1000       | 46        | 1.44%   |
| 61-70          | 36        | 1.13%   |
| 51-60          | 35        | 1.1%    |
| 131-140        | 18        | 0.56%   |
| 111-120        | 14        | 0.44%   |
| 91-100         | 7         | 0.22%   |
| 41-50          | 3         | 0.09%   |
| 1-40           | 3         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 974       | 31.38%  |
| 121-160       | 889       | 28.64%  |
| 101-120       | 697       | 22.45%  |
| Unknown       | 206       | 6.64%   |
| 161-240       | 174       | 5.61%   |
| More than 240 | 94        | 3.03%   |
| 1-50          | 70        | 2.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2088      | 74.07%  |
| 2     | 589       | 20.89%  |
| 3     | 75        | 2.66%   |
| 0     | 60        | 2.13%   |
| 4     | 7         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1595      | 38.26%  |
| Intel                             | 1420      | 34.06%  |
| Qualcomm Atheros                  | 446       | 10.7%   |
| Broadcom                          | 174       | 4.17%   |
| Ralink Technology                 | 53        | 1.27%   |
| TP-Link                           | 48        | 1.15%   |
| Ralink                            | 40        | 0.96%   |
| Broadcom Limited                  | 32        | 0.77%   |
| MediaTek                          | 28        | 0.67%   |
| Nvidia                            | 26        | 0.62%   |
| Marvell Technology Group          | 23        | 0.55%   |
| Microsoft                         | 16        | 0.38%   |
| Aquantia                          | 16        | 0.38%   |
| Samsung Electronics               | 15        | 0.36%   |
| Qualcomm Atheros Communications   | 15        | 0.36%   |
| NetGear                           | 14        | 0.34%   |
| Xiaomi                            | 13        | 0.31%   |
| DisplayLink                       | 13        | 0.31%   |
| ASIX Electronics                  | 13        | 0.31%   |
| Qualcomm                          | 12        | 0.29%   |
| Huawei Technologies               | 12        | 0.29%   |
| D-Link                            | 11        | 0.26%   |
| Lenovo                            | 10        | 0.24%   |
| Dell                              | 9         | 0.22%   |
| Ericsson Business Mobile Networks | 8         | 0.19%   |
| Edimax Technology                 | 8         | 0.19%   |
| Sierra Wireless                   | 7         | 0.17%   |
| ASUSTek Computer                  | 7         | 0.17%   |
| Linksys                           | 6         | 0.14%   |
| JMicron Technology                | 6         | 0.14%   |
| D-Link System                     | 5         | 0.12%   |
| Belkin Components                 | 4         | 0.1%    |
| Apple                             | 4         | 0.1%    |
| VIA Technologies                  | 3         | 0.07%   |
| T & A Mobile Phones               | 3         | 0.07%   |
| Google                            | 3         | 0.07%   |
| Fibocom                           | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.05%   |
| STMicroelectronics                | 2         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1132      | 23.22%  |
| Intel Wi-Fi 6 AX200                                               | 173       | 3.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 153       | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 99        | 2.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 95        | 1.95%   |
| Intel Wireless 8265 / 8275                                        | 92        | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 92        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 74        | 1.52%   |
| Intel Wi-Fi 6 AX201                                               | 72        | 1.48%   |
| Intel Wireless 7260                                               | 71        | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 68        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 64        | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 62        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 61        | 1.25%   |
| Intel Wireless 7265                                               | 59        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 57        | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 56        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 55        | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 51        | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 48        | 0.98%   |
| Intel Wireless 3165                                               | 47        | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 46        | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 45        | 0.92%   |
| Intel Wireless-AC 9260                                            | 43        | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 43        | 0.88%   |
| Intel Wireless 8260                                               | 37        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 37        | 0.76%   |
| Realtek 802.11ac NIC                                              | 33        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 32        | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 29        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 29        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 28        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 0.55%   |
| Ralink MT7601U Wireless Adapter                                   | 25        | 0.51%   |
| Intel Wireless 3160                                               | 22        | 0.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 22        | 0.45%   |
| Intel Ethernet Controller I225-V                                  | 22        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1097      | 49.15%  |
| Realtek Semiconductor                 | 353       | 15.82%  |
| Qualcomm Atheros                      | 347       | 15.55%  |
| Broadcom                              | 119       | 5.33%   |
| Ralink Technology                     | 53        | 2.37%   |
| TP-Link                               | 43        | 1.93%   |
| Ralink                                | 40        | 1.79%   |
| Broadcom Limited                      | 26        | 1.16%   |
| MediaTek                              | 24        | 1.08%   |
| Qualcomm Atheros Communications       | 15        | 0.67%   |
| Microsoft                             | 15        | 0.67%   |
| NetGear                               | 14        | 0.63%   |
| D-Link                                | 11        | 0.49%   |
| Edimax Technology                     | 8         | 0.36%   |
| Sierra Wireless                       | 7         | 0.31%   |
| Qualcomm                              | 7         | 0.31%   |
| ASUSTek Computer                      | 7         | 0.31%   |
| Linksys                               | 6         | 0.27%   |
| Marvell Technology Group              | 5         | 0.22%   |
| Dell                                  | 5         | 0.22%   |
| Belkin Components                     | 4         | 0.18%   |
| FIBOCOM                               | 3         | 0.13%   |
| D-Link System                         | 3         | 0.13%   |
| Mercucys                              | 2         | 0.09%   |
| Ericsson Business Mobile Networks     | 2         | 0.09%   |
| AVM                                   | 2         | 0.09%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| ZyDAS                                 | 1         | 0.04%   |
| Wilocity                              | 1         | 0.04%   |
| Wacom                                 | 1         | 0.04%   |
| Tenda                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Philips (or NXP)                      | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Guillemot                             | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| AirTies Wireless Networks             | 1         | 0.04%   |
| Accton Technology                     | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 173       | 7.69%   |
| Intel Wireless 8265 / 8275                                     | 92        | 4.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 74        | 3.29%   |
| Intel Wi-Fi 6 AX201                                            | 72        | 3.2%    |
| Intel Wireless 7260                                            | 71        | 3.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 68        | 3.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 64        | 2.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 62        | 2.76%   |
| Intel Wireless 7265                                            | 59        | 2.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 57        | 2.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 56        | 2.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 55        | 2.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 51        | 2.27%   |
| Intel Wireless 3165                                            | 47        | 2.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 46        | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 45        | 2%      |
| Intel Wireless-AC 9260                                         | 43        | 1.91%   |
| Intel Wireless 8260                                            | 37        | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 37        | 1.65%   |
| Realtek 802.11ac NIC                                           | 33        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 32        | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 29        | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 29        | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 28        | 1.24%   |
| Ralink MT7601U Wireless Adapter                                | 25        | 1.11%   |
| Intel Wireless 3160                                            | 22        | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 22        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 22        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 21        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 20        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 19        | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 19        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 18        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 0.71%   |
| Intel Centrino Advanced-N 6235                                 | 15        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 14        | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                | 14        | 0.62%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 13        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1448      | 57.26%  |
| Intel                            | 691       | 27.32%  |
| Qualcomm Atheros                 | 130       | 5.14%   |
| Broadcom                         | 69        | 2.73%   |
| Nvidia                           | 26        | 1.03%   |
| Marvell Technology Group         | 18        | 0.71%   |
| Aquantia                         | 16        | 0.63%   |
| Samsung Electronics              | 15        | 0.59%   |
| Xiaomi                           | 13        | 0.51%   |
| DisplayLink                      | 13        | 0.51%   |
| ASIX Electronics                 | 13        | 0.51%   |
| Lenovo                           | 10        | 0.4%    |
| Huawei Technologies              | 9         | 0.36%   |
| Broadcom Limited                 | 7         | 0.28%   |
| JMicron Technology               | 6         | 0.24%   |
| TP-Link                          | 5         | 0.2%    |
| Qualcomm                         | 5         | 0.2%    |
| MediaTek                         | 4         | 0.16%   |
| Apple                            | 4         | 0.16%   |
| VIA Technologies                 | 3         | 0.12%   |
| T & A Mobile Phones              | 3         | 0.12%   |
| Google                           | 3         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| D-Link System                    | 2         | 0.08%   |
| 3Com                             | 2         | 0.08%   |
| QNAP System                      | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.04%   |
| Motorola PCS                     | 1         | 0.04%   |
| Motorola BCS                     | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| Mellanox Technologies            | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Hewlett-Packard                  | 1         | 0.04%   |
| Elecom                           | 1         | 0.04%   |
| Davicom Semiconductor            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1132      | 43.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 153       | 5.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 99        | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 95        | 3.66%   |
| Intel I211 Gigabit Network Connection                             | 92        | 3.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 61        | 2.35%   |
| Intel Ethernet Connection (2) I219-V                              | 48        | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 43        | 1.65%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 22        | 0.85%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 20        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 17        | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 14        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 14        | 0.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 14        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 11        | 0.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10        | 0.38%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 0.38%   |
| Intel 82578DM Gigabit Network Connection                          | 10        | 0.38%   |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2367      | 52.37%  |
| WiFi     | 2125      | 47.01%  |
| Modem    | 26        | 0.58%   |
| Unknown  | 2         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1662      | 56.74%  |
| Ethernet | 1266      | 43.22%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1499      | 54.17%  |
| 1     | 1157      | 41.81%  |
| 3     | 59        | 2.13%   |
| 0     | 41        | 1.48%   |
| 4     | 8         | 0.29%   |
| 6     | 3         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 2373      | 84.69%  |
| Yes     | 428       | 15.27%  |
| Unknown | 1         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 927       | 50.41%  |
| Realtek Semiconductor           | 179       | 9.73%   |
| Qualcomm Atheros Communications | 154       | 8.37%   |
| Cambridge Silicon Radio         | 136       | 7.4%    |
| Broadcom                        | 102       | 5.55%   |
| IMC Networks                    | 65        | 3.53%   |
| Lite-On Technology              | 60        | 3.26%   |
| Foxconn / Hon Hai               | 38        | 2.07%   |
| Apple                           | 30        | 1.63%   |
| ASUSTek Computer                | 29        | 1.58%   |
| Dell                            | 28        | 1.52%   |
| Realtek                         | 17        | 0.92%   |
| Hewlett-Packard                 | 11        | 0.6%    |
| Ralink                          | 10        | 0.54%   |
| Toshiba                         | 9         | 0.49%   |
| Marvell Semiconductor           | 6         | 0.33%   |
| Foxconn International           | 6         | 0.33%   |
| Ralink Technology               | 5         | 0.27%   |
| Dynex                           | 4         | 0.22%   |
| TP-Link                         | 3         | 0.16%   |
| Edimax Technology               | 3         | 0.16%   |
| Alps Electric                   | 3         | 0.16%   |
| Unknown                         | 2         | 0.11%   |
| Taiyo Yuden                     | 2         | 0.11%   |
| Integrated System Solution      | 2         | 0.11%   |
| Belkin Components               | 2         | 0.11%   |
| Micro Star International        | 1         | 0.05%   |
| Kensington                      | 1         | 0.05%   |
| D-Link                          | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| Corsair                         | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 316       | 17.16%  |
| Intel AX201 Bluetooth                               | 170       | 9.23%   |
| Intel AX200 Bluetooth                               | 169       | 9.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 141       | 7.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 136       | 7.38%   |
| Realtek Bluetooth Radio                             | 101       | 5.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 81        | 4.4%    |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 3.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 30        | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 25        | 1.36%   |
| Lite-On Bluetooth Device                            | 24        | 1.3%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 24        | 1.3%    |
| IMC Networks Bluetooth Radio                        | 23        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.14%   |
| Realtek Bluetooth Radio                             | 17        | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 0.92%   |
| IMC Networks Bluetooth Device                       | 17        | 0.92%   |
| Intel AX210 Bluetooth                               | 16        | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 16        | 0.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.71%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.65%   |
| Apple Bluetooth USB Host Controller                 | 12        | 0.65%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.6%    |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.6%    |
| Apple Bluetooth Host Controller                     | 11        | 0.6%    |
| Ralink RT3290 Bluetooth                             | 10        | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 9         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.43%   |
| Intel Bluetooth Device                              | 8         | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.43%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.43%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.38%   |
| IMC Networks Wireless_Device                        | 7         | 0.38%   |
| IMC Networks Bluetooth USB Host Controller          | 7         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1947      | 47.88%  |
| AMD                        | 895       | 22.01%  |
| Nvidia                     | 730       | 17.95%  |
| C-Media Electronics        | 75        | 1.84%   |
| Logitech                   | 33        | 0.81%   |
| Creative Labs              | 33        | 0.81%   |
| GN Netcom                  | 30        | 0.74%   |
| JMTek                      | 23        | 0.57%   |
| Realtek Semiconductor      | 22        | 0.54%   |
| Texas Instruments          | 17        | 0.42%   |
| Creative Technology        | 14        | 0.34%   |
| Plantronics                | 13        | 0.32%   |
| Generalplus Technology     | 13        | 0.32%   |
| Corsair                    | 12        | 0.3%    |
| ASUSTek Computer           | 11        | 0.27%   |
| Razer USA                  | 10        | 0.25%   |
| Lenovo                     | 8         | 0.2%    |
| Kingston Technology        | 8         | 0.2%    |
| Focusrite-Novation         | 8         | 0.2%    |
| SteelSeries ApS            | 7         | 0.17%   |
| VIA Technologies           | 6         | 0.15%   |
| Tenx Technology            | 6         | 0.15%   |
| Sony                       | 6         | 0.15%   |
| Hewlett-Packard            | 6         | 0.15%   |
| Dell                       | 5         | 0.12%   |
| Blue Microphones           | 5         | 0.12%   |
| Yamaha                     | 4         | 0.1%    |
| SAVITECH                   | 4         | 0.1%    |
| ZOOM                       | 3         | 0.07%   |
| Sennheiser Communications  | 3         | 0.07%   |
| RODE Microphones           | 3         | 0.07%   |
| QinHeng Electronics        | 3         | 0.07%   |
| PreSonus Audio Electronics | 3         | 0.07%   |
| GYROCOM C&C                | 3         | 0.07%   |
| CMX Systems                | 3         | 0.07%   |
| Best Buy                   | 3         | 0.07%   |
| BEHRINGER International    | 3         | 0.07%   |
| XMOS                       | 2         | 0.05%   |
| Unknown                    | 2         | 0.05%   |
| Trust                      | 2         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 261       | 5.39%   |
| Intel Sunrise Point-LP HD Audio                                            | 220       | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 178       | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 162       | 3.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 157       | 3.24%   |
| AMD Starship/Matisse HD Audio Controller                                   | 147       | 3.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 144       | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 123       | 2.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 118       | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 111       | 2.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 101       | 2.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 99        | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 91        | 1.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 90        | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 86        | 1.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 84        | 1.74%   |
| AMD FCH Azalia Controller                                                  | 84        | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 81        | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 80        | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 67        | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 65        | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 65        | 1.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 60        | 1.24%   |
| Nvidia TU116 High Definition Audio Controller                              | 54        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 52        | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 51        | 1.05%   |
| Intel 200 Series PCH HD Audio                                              | 51        | 1.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 49        | 1.01%   |
| Intel Broadwell-U Audio Controller                                         | 48        | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 47        | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 45        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 43        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 43        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 42        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 40        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 39        | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 39        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 35        | 0.72%   |
| Intel CM238 HD Audio Controller                                            | 35        | 0.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 34        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 448       | 21.85%  |
| SK hynix            | 331       | 16.15%  |
| Kingston            | 273       | 13.32%  |
| Micron Technology   | 190       | 9.27%   |
| Unknown             | 155       | 7.56%   |
| Crucial             | 140       | 6.83%   |
| Corsair             | 135       | 6.59%   |
| G.Skill             | 99        | 4.83%   |
| A-DATA Technology   | 38        | 1.85%   |
| Ramaxel Technology  | 31        | 1.51%   |
| Elpida              | 27        | 1.32%   |
| Nanya Technology    | 24        | 1.17%   |
| Unknown (ABCD)      | 19        | 0.93%   |
| Team                | 16        | 0.78%   |
| Patriot             | 14        | 0.68%   |
| Transcend           | 12        | 0.59%   |
| Smart               | 12        | 0.59%   |
| Unknown             | 8         | 0.39%   |
| Goodram             | 7         | 0.34%   |
| AMD                 | 6         | 0.29%   |
| Smart Brazil        | 5         | 0.24%   |
| Silicon Power       | 5         | 0.24%   |
| Apacer              | 5         | 0.24%   |
| Wilk                | 3         | 0.15%   |
| Teikon              | 3         | 0.15%   |
| ASint Technology    | 3         | 0.15%   |
| SHARETRONIC         | 2         | 0.1%    |
| Reboto              | 2         | 0.1%    |
| Kllisre             | 2         | 0.1%    |
| Kingmax             | 2         | 0.1%    |
| GLOWAY              | 2         | 0.1%    |
| GeIL                | 2         | 0.1%    |
| CSX                 | 2         | 0.1%    |
| Avant               | 2         | 0.1%    |
| V-GeN               | 1         | 0.05%   |
| V-Color             | 1         | 0.05%   |
| Unknown (8A02)      | 1         | 0.05%   |
| Unknown (82B5)      | 1         | 0.05%   |
| Unknown (0x29E)     | 1         | 0.05%   |
| Unknown (0x0C97)    | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 21        | 0.95%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 16        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 14        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 0.59%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 13        | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.5%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 11        | 0.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 10        | 0.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.45%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 10        | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 9         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.41%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 9         | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.36%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 8         | 0.36%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 8         | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 8         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.36%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.36%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 8         | 0.36%   |
| Unknown                                                          | 8         | 0.36%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.32%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 999       | 56.63%  |
| DDR3    | 530       | 30.05%  |
| LPDDR4  | 62        | 3.51%   |
| Unknown | 47        | 2.66%   |
| LPDDR3  | 43        | 2.44%   |
| DDR2    | 43        | 2.44%   |
| SDRAM   | 27        | 1.53%   |
| DDR     | 6         | 0.34%   |
| DDR5    | 4         | 0.23%   |
| LPDDR5  | 2         | 0.11%   |
| DRAM    | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1007      | 57.12%  |
| DIMM         | 625       | 35.45%  |
| Row Of Chips | 112       | 6.35%   |
| Chip         | 10        | 0.57%   |
| Unknown      | 5         | 0.28%   |
| RIMM         | 2         | 0.11%   |
| FB-DIMM      | 2         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 800       | 41.58%  |
| 4096  | 530       | 27.55%  |
| 16384 | 339       | 17.62%  |
| 2048  | 178       | 9.25%   |
| 32768 | 48        | 2.49%   |
| 1024  | 26        | 1.35%   |
| 512   | 1         | 0.05%   |
| 256   | 1         | 0.05%   |
| 128   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 373       | 19.48%  |
| 1600    | 359       | 18.75%  |
| 3200    | 280       | 14.62%  |
| 2400    | 164       | 8.56%   |
| 1333    | 120       | 6.27%   |
| 2133    | 107       | 5.59%   |
| 3600    | 68        | 3.55%   |
| 1334    | 51        | 2.66%   |
| 800     | 31        | 1.62%   |
| 4267    | 27        | 1.41%   |
| 1867    | 26        | 1.36%   |
| 667     | 24        | 1.25%   |
| 3000    | 21        | 1.1%    |
| 2666    | 21        | 1.1%    |
| 3266    | 18        | 0.94%   |
| Unknown | 18        | 0.94%   |
| 3466    | 15        | 0.78%   |
| 2933    | 14        | 0.73%   |
| 1067    | 14        | 0.73%   |
| 3733    | 13        | 0.68%   |
| 3400    | 13        | 0.68%   |
| 1066    | 12        | 0.63%   |
| 8400    | 11        | 0.57%   |
| 3800    | 9         | 0.47%   |
| 1866    | 9         | 0.47%   |
| 4199    | 7         | 0.37%   |
| 2800    | 7         | 0.37%   |
| 400     | 6         | 0.31%   |
| 4266    | 5         | 0.26%   |
| 3333    | 5         | 0.26%   |
| 3066    | 5         | 0.26%   |
| 2048    | 5         | 0.26%   |
| 4800    | 4         | 0.21%   |
| 3866    | 4         | 0.21%   |
| 3151    | 4         | 0.21%   |
| 2000    | 4         | 0.21%   |
| 1800    | 4         | 0.21%   |
| 975     | 3         | 0.16%   |
| 533     | 3         | 0.16%   |
| 49926   | 2         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 40        | 44.44%  |
| Brother Industries     | 20        | 22.22%  |
| Samsung Electronics    | 9         | 10%     |
| Seiko Epson            | 6         | 6.67%   |
| Canon                  | 6         | 6.67%   |
| Xerox                  | 2         | 2.22%   |
| SAT                    | 1         | 1.11%   |
| Prolific Technology    | 1         | 1.11%   |
| Pantum                 | 1         | 1.11%   |
| Panasonic (Matsushita) | 1         | 1.11%   |
| ICS Advent             | 1         | 1.11%   |
| Datamax-O'Neil         | 1         | 1.11%   |
| Apple                  | 1         | 1.11%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                    | 3         | 3.26%   |
| HP OfficeJet Pro 7740 series                    | 2         | 2.17%   |
| HP LaserJet 1018                                | 2         | 2.17%   |
| HP ENVY 4500 series                             | 2         | 2.17%   |
| HP DeskJet 2620 All-in-One Printer              | 2         | 2.17%   |
| Xerox Phaser 6500DN                             | 1         | 1.09%   |
| Xerox Phaser 3140 and 3155                      | 1         | 1.09%   |
| Seiko Epson WF-2530 Series                      | 1         | 1.09%   |
| Seiko Epson Printer                             | 1         | 1.09%   |
| Seiko Epson L3110 Series                        | 1         | 1.09%   |
| Seiko Epson L222 Series                         | 1         | 1.09%   |
| Seiko Epson L120 Series                         | 1         | 1.09%   |
| Seiko Epson ET-2710 Series                      | 1         | 1.09%   |
| SAT SAT38TUSE                                   | 1         | 1.09%   |
| Samsung Xerox Phaser 3117 Laser Printer         | 1         | 1.09%   |
| Samsung SCX-3200 Series                         | 1         | 1.09%   |
| Samsung ML-2250 Series                          | 1         | 1.09%   |
| Samsung ML-216x Series Laser Printer            | 1         | 1.09%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 1.09%   |
| Samsung M2070 Series                            | 1         | 1.09%   |
| Samsung CLX-3180 Series                         | 1         | 1.09%   |
| Samsung CLX-3170 Series                         | 1         | 1.09%   |
| Samsung CLP-360 Series                          | 1         | 1.09%   |
| Prolific PL2305 Parallel Port                   | 1         | 1.09%   |
| Pantum P2200 series                             | 1         | 1.09%   |
| Panasonic (Matsushita) KX-MB1500RU              | 1         | 1.09%   |
| ICS Advent Parallel Adapter                     | 1         | 1.09%   |
| HP OfficeJet Pro 9010 series                    | 1         | 1.09%   |
| HP OfficeJet 9010 series                        | 1         | 1.09%   |
| HP OfficeJet 5500 series                        | 1         | 1.09%   |
| HP OfficeJet 4650 series                        | 1         | 1.09%   |
| HP Officejet 4630 series                        | 1         | 1.09%   |
| HP OfficeJet 3830 series                        | 1         | 1.09%   |
| HP LaserJet Pro M202dw                          | 1         | 1.09%   |
| HP LaserJet P2055 series                        | 1         | 1.09%   |
| HP LaserJet P2035                               | 1         | 1.09%   |
| HP LaserJet P2015 series                        | 1         | 1.09%   |
| HP LaserJet P1102                               | 1         | 1.09%   |
| HP LaserJet P1005                               | 1         | 1.09%   |
| HP LaserJet M402dn                              | 1         | 1.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 47.62%  |
| Seiko Epson     | 5         | 23.81%  |
| Mustek Systems  | 3         | 14.29%  |
| Hewlett-Packard | 3         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 9.52%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2         | 9.52%   |
| Canon CanoScan LiDE 220                                 | 2         | 9.52%   |
| Canon CanoScan LiDE 110                                 | 2         | 9.52%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 4.76%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4.76%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 4.76%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 4.76%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 4.76%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 4.76%   |
| HP ScanJet G4010                                        | 1         | 4.76%   |
| HP ScanJet 82x0C                                        | 1         | 4.76%   |
| HP ScanJet 3770                                         | 1         | 4.76%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                  | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                 | 1         | 4.76%   |
| Canon CanoScan LiDE 120                                 | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 362       | 19.59%  |
| IMC Networks                           | 179       | 9.69%   |
| Microdia                               | 172       | 9.31%   |
| Acer                                   | 151       | 8.17%   |
| Logitech                               | 147       | 7.95%   |
| Realtek Semiconductor                  | 146       | 7.9%    |
| Sunplus Innovation Technology          | 95        | 5.14%   |
| Quanta                                 | 82        | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 72        | 3.9%    |
| Silicon Motion                         | 38        | 2.06%   |
| Suyin                                  | 37        | 2%      |
| Syntek                                 | 34        | 1.84%   |
| Lite-On Technology                     | 32        | 1.73%   |
| Apple                                  | 29        | 1.57%   |
| Microsoft                              | 28        | 1.52%   |
| Luxvisions Innotech Limited            | 27        | 1.46%   |
| Alcor Micro                            | 23        | 1.24%   |
| Samsung Electronics                    | 19        | 1.03%   |
| Ricoh                                  | 14        | 0.76%   |
| Generalplus Technology                 | 12        | 0.65%   |
| Z-Star Microelectronics                | 11        | 0.6%    |
| Lenovo                                 | 10        | 0.54%   |
| KYE Systems (Mouse Systems)            | 8         | 0.43%   |
| Genesys Logic                          | 8         | 0.43%   |
| MacroSilicon                           | 6         | 0.32%   |
| ARC International                      | 6         | 0.32%   |
| SunplusIT                              | 5         | 0.27%   |
| Sunplus Technology                     | 5         | 0.27%   |
| Importek                               | 5         | 0.27%   |
| Huawei Technologies                    | 5         | 0.27%   |
| Sonix Technology                       | 4         | 0.22%   |
| Intel                                  | 4         | 0.22%   |
| Cubeternet                             | 4         | 0.22%   |
| Y Media                                | 3         | 0.16%   |
| Unknown                                | 3         | 0.16%   |
| Razer USA                              | 3         | 0.16%   |
| Novatek Microelectronics               | 3         | 0.16%   |
| LG Electronics                         | 3         | 0.16%   |
| Jieli Technology                       | 3         | 0.16%   |
| GEMBIRD                                | 3         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 77        | 4.12%   |
| Microdia Integrated_Webcam_HD                                              | 71        | 3.8%    |
| Realtek Integrated_Webcam_HD                                               | 66        | 3.53%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 55        | 2.94%   |
| IMC Networks Integrated Camera                                             | 51        | 2.73%   |
| Acer Integrated Camera                                                     | 49        | 2.62%   |
| Sunplus Integrated_Webcam_HD                                               | 41        | 2.19%   |
| Chicony HD WebCam                                                          | 39        | 2.09%   |
| Logitech HD Pro Webcam C920                                                | 32        | 1.71%   |
| Logitech Webcam C270                                                       | 31        | 1.66%   |
| Chicony USB2.0 Camera                                                      | 27        | 1.44%   |
| Chicony HP HD Camera                                                       | 24        | 1.28%   |
| Syntek Integrated Camera                                                   | 23        | 1.23%   |
| Acer Lenovo EasyCamera                                                     | 22        | 1.18%   |
| Microdia Integrated Webcam                                                 | 20        | 1.07%   |
| Samsung Galaxy A5 (MTP)                                                    | 18        | 0.96%   |
| Quanta HD User Facing                                                      | 17        | 0.91%   |
| Microdia Webcam Vitade AF                                                  | 17        | 0.91%   |
| Chicony HD User Facing                                                     | 16        | 0.86%   |
| Acer HD Webcam                                                             | 16        | 0.86%   |
| Lite-On Integrated Camera                                                  | 15        | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 13        | 0.7%    |
| Chicony HP Wide Vision HD Camera                                           | 13        | 0.7%    |
| Chicony HP TrueVision HD                                                   | 13        | 0.7%    |
| Apple iPhone5/5C/5S/6                                                      | 13        | 0.7%    |
| Acer BisonCam, NB Pro                                                      | 13        | 0.7%    |
| Quanta HP TrueVision HD Camera                                             | 12        | 0.64%   |
| Quanta HP HD Camera                                                        | 12        | 0.64%   |
| Chicony USB 2.0 Camera                                                     | 12        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)                                    | 12        | 0.64%   |
| Realtek Integrated Webcam HD                                               | 11        | 0.59%   |
| Quanta HD Webcam                                                           | 10        | 0.53%   |
| Microsoft LifeCam HD-3000                                                  | 10        | 0.53%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 10        | 0.53%   |
| IMC Networks ov9734_azurewave_camera                                       | 10        | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 10        | 0.53%   |
| Realtek USB Camera                                                         | 9         | 0.48%   |
| Realtek Integrated Webcam                                                  | 9         | 0.48%   |
| Quanta HP Webcam                                                           | 9         | 0.48%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 9         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 126       | 32.64%  |
| Validity Sensors           | 100       | 25.91%  |
| Shenzhen Goodix Technology | 75        | 19.43%  |
| Elan Microelectronics      | 27        | 6.99%   |
| AuthenTec                  | 20        | 5.18%   |
| Upek                       | 16        | 4.15%   |
| LighTuning Technology      | 14        | 3.63%   |
| STMicroelectronics         | 6         | 1.55%   |
| Focal-systems.Corp         | 1         | 0.26%   |
| DigitalPersona             | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 46        | 11.92%  |
| Shenzhen Goodix  FingerPrint Device                                        | 38        | 9.84%   |
| Unknown                                                                    | 34        | 8.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 5.7%    |
| Elan ELAN:Fingerprint                                                      | 17        | 4.4%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 4.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 4.15%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 3.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 3.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 3.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.59%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.33%   |
| Synaptics  WBDI                                                            | 9         | 2.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 2.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 2.07%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.07%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.07%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.07%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.81%   |
| AuthenTec AES2810                                                          | 7         | 1.81%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.55%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.3%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 1.04%   |
| Validity Sensors VFS491                                                    | 4         | 1.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.04%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.78%   |
| Synaptics WBDI Device                                                      | 2         | 0.52%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.52%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.52%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.26%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.26%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.26%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 69        | 41.07%  |
| Alcor Micro               | 46        | 27.38%  |
| Upek                      | 11        | 6.55%   |
| O2 Micro                  | 8         | 4.76%   |
| Lenovo                    | 6         | 3.57%   |
| Advanced Card Systems     | 4         | 2.38%   |
| SCM Microsystems          | 3         | 1.79%   |
| Gemalto (was Gemplus)     | 3         | 1.79%   |
| Yubico.com                | 2         | 1.19%   |
| Realtek Semiconductor     | 2         | 1.19%   |
| OmniKey                   | 2         | 1.19%   |
| Fujitsu Siemens Computers | 2         | 1.19%   |
| Watchdata                 | 1         | 0.6%    |
| Reiner SCT Kartensysteme  | 1         | 0.6%    |
| In Focus Systems          | 1         | 0.6%    |
| Giesecke & Devrient       | 1         | 0.6%    |
| Clay Logic                | 1         | 0.6%    |
| Chicony Electronics       | 1         | 0.6%    |
| Bit4id                    | 1         | 0.6%    |
| Aladdin R.D.              | 1         | 0.6%    |
| Aladdin Knowledge Systems | 1         | 0.6%    |
| Aktiv                     | 1         | 0.6%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 26.19%  |
| Broadcom 5880                                                                | 20        | 11.9%   |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 10.71%  |
| Broadcom 58200                                                               | 17        | 10.12%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 6.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.57%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 2.38%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.79%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.19%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.19%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.19%   |
| Watchdata USB Key                                                            | 1         | 0.6%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.6%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.6%    |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.6%    |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.6%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.6%    |
| OmniKey CardMan 1021                                                         | 1         | 0.6%    |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.6%    |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.6%    |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.6%    |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.6%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.6%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.6%    |
| Bit4id miniLector EVO                                                        | 1         | 0.6%    |
| Aladdin R.D. JaCarta                                                         | 1         | 0.6%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.6%    |
| Aktiv Rutoken lite                                                           | 1         | 0.6%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1927      | 68.53%  |
| 1     | 716       | 25.46%  |
| 2     | 136       | 4.84%   |
| 3     | 15        | 0.53%   |
| 4     | 7         | 0.25%   |
| 6     | 4         | 0.14%   |
| 7     | 3         | 0.11%   |
| 5     | 3         | 0.11%   |
| 9     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 380       | 35.35%  |
| Graphics card            | 173       | 16.09%  |
| Chipcard                 | 145       | 13.49%  |
| Net/wireless             | 126       | 11.72%  |
| Multimedia controller    | 43        | 4%      |
| Camera                   | 39        | 3.63%   |
| Sound                    | 33        | 3.07%   |
| Bluetooth                | 31        | 2.88%   |
| Communication controller | 29        | 2.7%    |
| Unassigned class         | 26        | 2.42%   |
| Card reader              | 16        | 1.49%   |
| Storage                  | 12        | 1.12%   |
| Network                  | 5         | 0.47%   |
| Net/ethernet             | 5         | 0.47%   |
| Storage/ide              | 4         | 0.37%   |
| Modem                    | 3         | 0.28%   |
| Firewire controller      | 3         | 0.28%   |
| Dvb card                 | 2         | 0.19%   |


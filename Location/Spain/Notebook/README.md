Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 3757

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro11,1              | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | G62                         | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | X555LD                      | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| Toshiba       | NB520                       | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | Latitude 5410               | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| Dell          | Latitude 7490               | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| eMachines     | E725                        | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| ASUSTek       | K53U                        | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [be6a0a28e1](https://linux-hardware.org/?probe=be6a0a28e1) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| ASUSTek       | K53SC                       | [002a8bdf0c](https://linux-hardware.org/?probe=002a8bdf0c) | Jan 09, 2023 |
| Acer          | Aspire E5-551G              | [dc659db065](https://linux-hardware.org/?probe=dc659db065) | Jan 09, 2023 |
| ASUSTek       | K54L                        | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| Dell          | Studio 1558                 | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Bravo 17 A4DDK              | [cf73810d98](https://linux-hardware.org/?probe=cf73810d98) | Jan 08, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| ASUSTek       | X540YA                      | [b7021632b6](https://linux-hardware.org/?probe=b7021632b6) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Acer          | TravelMate P256-MG          | [e090a2b61c](https://linux-hardware.org/?probe=e090a2b61c) | Jan 07, 2023 |
| ASUSTek       | K53U                        | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| Google        | Candy                       | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| Chuwi         | HeroBook Air                | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| Apple         | MacBookPro4,1               | [9fd9040304](https://linux-hardware.org/?probe=9fd9040304) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| MSI           | Stealth 15M B12UE           | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| HP            | 250 G2                      | [430425dd1c](https://linux-hardware.org/?probe=430425dd1c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Samsung       | RF510/RF410/RF710           | [3da2c535f7](https://linux-hardware.org/?probe=3da2c535f7) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| ASUSTek       | X550VX                      | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| Samsung       | RF510/RF410/RF710           | [220854be2e](https://linux-hardware.org/?probe=220854be2e) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [5ada77ec03](https://linux-hardware.org/?probe=5ada77ec03) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [817985e5bf](https://linux-hardware.org/?probe=817985e5bf) | Jan 01, 2023 |
| ASUSTek       | K53SC                       | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| Alienware     | x17 R1                      | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Valve         | Jupiter                     | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Dell          | Latitude E6500              | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Valve         | Jupiter                     | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Apple         | MacBook5,1                  | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| HP            | Pavilion 15                 | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Valve         | Jupiter                     | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [80dc1502e1](https://linux-hardware.org/?probe=80dc1502e1) | Nov 06, 2022 |
| LG Electro... | 15Z990-V.AA78B              | [5ca4c426d8](https://linux-hardware.org/?probe=5ca4c426d8) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Valve         | Jupiter                     | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [bd3b4f723e](https://linux-hardware.org/?probe=bd3b4f723e) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Valve         | Jupiter                     | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| HP            | G62                         | [a00ba1aae7](https://linux-hardware.org/?probe=a00ba1aae7) | Nov 03, 2022 |
| HP            | 250 G4                      | [ff497e0d4c](https://linux-hardware.org/?probe=ff497e0d4c) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Apple         | MacBookPro16,1              | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| ASUSTek       | X550EA                      | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| ASUSTek       | K54C                        | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| Valve         | Jupiter                     | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| MSI           | Stealth GS66 12UGS          | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| ASUSTek       | X540LA                      | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| HP            | Laptop 17-cn2xxx            | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Dell          | Latitude E7240              | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Toshiba       | Satellite R830              | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Valve         | Jupiter                     | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| Sony          | VPCEB1Z1E                   | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Dell          | Latitude 7420               | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Dell          | Latitude E7240              | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| HP            | Laptop 15-db0xxx            | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| ASUSTek       | F3F                         | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HUAWEI        | NBD-WXX9                    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| Lenovo        | M30-70 80H8                 | [d254ca63b4](https://linux-hardware.org/?probe=d254ca63b4) | Aug 22, 2022 |
| Chuwi         | GemiBook Pro                | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| SLIMBOOK      | PROX14-AMD                  | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| HP            | 250 G7 Notebook PC          | [ec15e7b0c5](https://linux-hardware.org/?probe=ec15e7b0c5) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| ASUSTek       | N75SF                       | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [1cdee0174f](https://linux-hardware.org/?probe=1cdee0174f) | Aug 16, 2022 |
| Valve         | Jupiter                     | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Valve         | Jupiter                     | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| GPD           | G1618-03                    | [64b056ddb1](https://linux-hardware.org/?probe=64b056ddb1) | Aug 14, 2022 |
| GPD           | G1618-03                    | [7316acf7a6](https://linux-hardware.org/?probe=7316acf7a6) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| Dell          | Latitude D630               | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X555LAB                     | [9c41cf4c2c](https://linux-hardware.org/?probe=9c41cf4c2c) | Aug 10, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Dell          | Latitude 5520               | [33888d0477](https://linux-hardware.org/?probe=33888d0477) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [ca0e99f941](https://linux-hardware.org/?probe=ca0e99f941) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Dell          | Latitude 5420               | [d4717e9bb1](https://linux-hardware.org/?probe=d4717e9bb1) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| ASUSTek       | X540SA                      | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Chuwi         | GemiBook Pro                | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| Unknown       | Unknown                     | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Dell          | XPS 15 7590                 | [f1c4c81832](https://linux-hardware.org/?probe=f1c4c81832) | Jul 26, 2022 |
| eMachines     | D730                        | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Alienware     | m15 R4                      | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| Acer          | Aspire 5749                 | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |
| Dell          | Latitude E6540              | [281f1b4a30](https://linux-hardware.org/?probe=281f1b4a30) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| HP            | Stream Notebook             | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Unknown       | Unknown                     | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Lenovo        | ThinkPad T450 20BUS04A0B    | [afc6d3d00a](https://linux-hardware.org/?probe=afc6d3d00a) | Jul 22, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| Dell          | XPS 15 9510                 | [cf3548c6b4](https://linux-hardware.org/?probe=cf3548c6b4) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| Acer          | Aspire 5750G                | [08beab61a7](https://linux-hardware.org/?probe=08beab61a7) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Toshiba       | Satellite Pro A50-C         | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| Dell          | Latitude 7390               | [fca3ed2ef5](https://linux-hardware.org/?probe=fca3ed2ef5) | Jul 17, 2022 |
| Toshiba       | Satellite L670              | [d753323f22](https://linux-hardware.org/?probe=d753323f22) | Jul 16, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Valve         | Jupiter                     | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Chuwi         | HeroBook Air                | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| Apple         | MacBookAir7,2               | [19c5e2272a](https://linux-hardware.org/?probe=19c5e2272a) | Jul 14, 2022 |
| Dell          | Latitude E5540              | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| MSI           | Modern 15 A5M               | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| MSI           | Katana GF66 12UD            | [2822036910](https://linux-hardware.org/?probe=2822036910) | Jul 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | [470a18c94b](https://linux-hardware.org/?probe=470a18c94b) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f3de47ac1f](https://linux-hardware.org/?probe=f3de47ac1f) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Dell          | Latitude 5285               | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire 5742G                | [3d76189da7](https://linux-hardware.org/?probe=3d76189da7) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire 5738                 | [3b93414575](https://linux-hardware.org/?probe=3b93414575) | Jul 05, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| Valve         | Jupiter                     | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60e5b2ef2c](https://linux-hardware.org/?probe=60e5b2ef2c) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Unknown       | Unknown                     | [f7dd6e9a70](https://linux-hardware.org/?probe=f7dd6e9a70) | Jul 02, 2022 |
| Lenovo        | V110-15IAP 80TG             | [05d0271371](https://linux-hardware.org/?probe=05d0271371) | Jul 01, 2022 |
| Lenovo        | V110-15IAP 80TG             | [23519c6427](https://linux-hardware.org/?probe=23519c6427) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | F3JR                        | [b56d8007d7](https://linux-hardware.org/?probe=b56d8007d7) | Jul 01, 2022 |
| Dell          | XPS 9320                    | [f04b491e6d](https://linux-hardware.org/?probe=f04b491e6d) | Jun 30, 2022 |
| Valve         | Jupiter                     | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Acer          | Aspire 5740                 | [1db26fc575](https://linux-hardware.org/?probe=1db26fc575) | Jun 29, 2022 |
| Acer          | Aspire 5740                 | [44a72b9a94](https://linux-hardware.org/?probe=44a72b9a94) | Jun 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6491230956](https://linux-hardware.org/?probe=6491230956) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [13c3e19573](https://linux-hardware.org/?probe=13c3e19573) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [c99e2d656f](https://linux-hardware.org/?probe=c99e2d656f) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [d0e2e3232c](https://linux-hardware.org/?probe=d0e2e3232c) | Jun 26, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| Samsung       | RF510/RF410/RF710           | [c68de3d559](https://linux-hardware.org/?probe=c68de3d559) | Jun 23, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [e0dfa460b6](https://linux-hardware.org/?probe=e0dfa460b6) | Jun 23, 2022 |
| Dell          | Precision 5540              | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W06    | [d1a1093555](https://linux-hardware.org/?probe=d1a1093555) | Jun 22, 2022 |
| Toshiba       | Satellite L50D-B            | [500756a7e3](https://linux-hardware.org/?probe=500756a7e3) | Jun 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b248434bc6](https://linux-hardware.org/?probe=b248434bc6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| HP            | 250 G5 Notebook PC          | [0b40800023](https://linux-hardware.org/?probe=0b40800023) | Jun 21, 2022 |
| Dell          | Latitude E4310              | [180f09a85f](https://linux-hardware.org/?probe=180f09a85f) | Jun 20, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [65359ef780](https://linux-hardware.org/?probe=65359ef780) | Jun 18, 2022 |
| Acer          | Aspire V3-572G              | [efef888970](https://linux-hardware.org/?probe=efef888970) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | Latitude E7270              | [bdf2e224f1](https://linux-hardware.org/?probe=bdf2e224f1) | Jun 18, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| HP            | EliteBook 8460p             | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [2599b4c75d](https://linux-hardware.org/?probe=2599b4c75d) | Jun 12, 2022 |
| Alienware     | m15 R4                      | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| HP            | Compaq 6715b (GR667ET#AB... | [44de2345bb](https://linux-hardware.org/?probe=44de2345bb) | Jun 09, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| Dell          | Inspiron 13-7359            | [c46dcc9b6f](https://linux-hardware.org/?probe=c46dcc9b6f) | Jun 07, 2022 |
| HP            | Stream Notebook PC 13       | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| ASUSTek       | 1000H                       | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3dd8394bb5](https://linux-hardware.org/?probe=3dd8394bb5) | Jun 04, 2022 |
| eMachines     | eME732                      | [c6d57c850c](https://linux-hardware.org/?probe=c6d57c850c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| ASUSTek       | TX201LA                     | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| TEKNOSERVI... | PORTATIL TTL 14             | [7af14493e8](https://linux-hardware.org/?probe=7af14493e8) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [185587d5e1](https://linux-hardware.org/?probe=185587d5e1) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | [65f67bae3c](https://linux-hardware.org/?probe=65f67bae3c) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | [41cad28720](https://linux-hardware.org/?probe=41cad28720) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| HP            | Laptop 14-dk1xxx            | [c996bce6b5](https://linux-hardware.org/?probe=c996bce6b5) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | [08fe1f2d0f](https://linux-hardware.org/?probe=08fe1f2d0f) | May 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a1dfbe3337](https://linux-hardware.org/?probe=a1dfbe3337) | May 31, 2022 |
| Acer          | TravelMate P256-MG          | [22b617425d](https://linux-hardware.org/?probe=22b617425d) | May 31, 2022 |
| Fujitsu       | LIFEBOOK E5511              | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [4fadee73e4](https://linux-hardware.org/?probe=4fadee73e4) | May 29, 2022 |
| Chuwi         | GemiBook                    | [432c1135b8](https://linux-hardware.org/?probe=432c1135b8) | May 29, 2022 |
| Lenovo        | G580 20150                  | [60128f5782](https://linux-hardware.org/?probe=60128f5782) | May 29, 2022 |
| Valve         | Jupiter                     | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Toshiba       | Satellite L10W-B-101        | [774d5a9eae](https://linux-hardware.org/?probe=774d5a9eae) | May 28, 2022 |
| MSI           | PR600                       | [09b736e706](https://linux-hardware.org/?probe=09b736e706) | May 27, 2022 |
| Medion        | S6421 MD60703               | [9fffed019c](https://linux-hardware.org/?probe=9fffed019c) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [f5488ccb22](https://linux-hardware.org/?probe=f5488ccb22) | May 26, 2022 |
| HONOR         | HLYL-WXX9                   | [57d71fca8a](https://linux-hardware.org/?probe=57d71fca8a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [86f00d534a](https://linux-hardware.org/?probe=86f00d534a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [3929f17532](https://linux-hardware.org/?probe=3929f17532) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| MSI           | Prestige 15 A11SCS          | [2433529434](https://linux-hardware.org/?probe=2433529434) | May 24, 2022 |
| Toshiba       | Satellite L10W-B-101        | [bb4ce9afdd](https://linux-hardware.org/?probe=bb4ce9afdd) | May 24, 2022 |
| Unknown       | Aspire E                    | [d437b15b97](https://linux-hardware.org/?probe=d437b15b97) | May 24, 2022 |
| Unknown       | Aspire E                    | [f46b38824f](https://linux-hardware.org/?probe=f46b38824f) | May 24, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| MSI           | GF63 Thin 9SC               | [a2a182a63e](https://linux-hardware.org/?probe=a2a182a63e) | May 23, 2022 |
| HP            | 15                          | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [d972595598](https://linux-hardware.org/?probe=d972595598) | May 22, 2022 |
| Dell          | G15 5510                    | [0ca1f736f9](https://linux-hardware.org/?probe=0ca1f736f9) | May 22, 2022 |
| Samsung       | RF510/RF410/RF710           | [c146b79bd6](https://linux-hardware.org/?probe=c146b79bd6) | May 22, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8f9ca8d66b](https://linux-hardware.org/?probe=8f9ca8d66b) | May 20, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| HP            | EliteBook 840 G5            | [48e5424ecb](https://linux-hardware.org/?probe=48e5424ecb) | May 19, 2022 |
| MSI           | Prestige 14 A12UC           | [189b62a372](https://linux-hardware.org/?probe=189b62a372) | May 19, 2022 |
| Dell          | Latitude E4310              | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| Valve         | Jupiter                     | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve         | Jupiter                     | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Lenovo        | V145-15AST 81MT             | [badf4d0a88](https://linux-hardware.org/?probe=badf4d0a88) | May 18, 2022 |
| Chuwi         | HeroBook Air                | [7d96e10672](https://linux-hardware.org/?probe=7d96e10672) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| Lenovo        | G580 2189                   | [e7de790c8a](https://linux-hardware.org/?probe=e7de790c8a) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| HP            | ENVY Notebook 13-ab0XX      | [26ed58e99a](https://linux-hardware.org/?probe=26ed58e99a) | May 16, 2022 |
| Dell          | Latitude 5480               | [bccdb55064](https://linux-hardware.org/?probe=bccdb55064) | May 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [70cde2437b](https://linux-hardware.org/?probe=70cde2437b) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS0LE00    | [59eecf466b](https://linux-hardware.org/?probe=59eecf466b) | May 15, 2022 |
| Acer          | Aspire E1-522               | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Acer          | Aspire E1-522               | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| Dell          | Latitude 5420               | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| Samsung       | RF510/RF410/RF710           | [8134289438](https://linux-hardware.org/?probe=8134289438) | May 12, 2022 |
| HP            | Pavilion g6                 | [4f5ac891f4](https://linux-hardware.org/?probe=4f5ac891f4) | May 11, 2022 |
| Acer          | Aspire 5742G                | [f720d9e031](https://linux-hardware.org/?probe=f720d9e031) | May 11, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e6d1749248](https://linux-hardware.org/?probe=e6d1749248) | May 10, 2022 |
| MSI           | Modern 14 B11MO             | [75bc7c18db](https://linux-hardware.org/?probe=75bc7c18db) | May 10, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [02925e8fac](https://linux-hardware.org/?probe=02925e8fac) | May 10, 2022 |
| Acer          | TravelMate 6592             | [353516147d](https://linux-hardware.org/?probe=353516147d) | May 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [ae80aa69fe](https://linux-hardware.org/?probe=ae80aa69fe) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| MSI           | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | [f269fd3294](https://linux-hardware.org/?probe=f269fd3294) | May 09, 2022 |
| Acer          | Aspire A515-54              | [1d37964706](https://linux-hardware.org/?probe=1d37964706) | May 08, 2022 |
| MSI           | GE62 2QD                    | [cef8637026](https://linux-hardware.org/?probe=cef8637026) | May 08, 2022 |
| SLIMBOOK      | Essential15L                | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| Dell          | Inspiron 5515               | [aa0534d7af](https://linux-hardware.org/?probe=aa0534d7af) | May 07, 2022 |
| Chuwi         | HeroBook Air                | [255ff705ac](https://linux-hardware.org/?probe=255ff705ac) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HP            | 340S G7 Notebook PC         | [c0d0f6435b](https://linux-hardware.org/?probe=c0d0f6435b) | May 06, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| Dell          | Latitude 5420               | [dbe0cffc08](https://linux-hardware.org/?probe=dbe0cffc08) | May 06, 2022 |
| HP            | Compaq 6730s                | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| HP            | Compaq 15                   | [25db1ef15f](https://linux-hardware.org/?probe=25db1ef15f) | May 06, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [1467c3bb41](https://linux-hardware.org/?probe=1467c3bb41) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | [e8556f4acf](https://linux-hardware.org/?probe=e8556f4acf) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | [917add86ab](https://linux-hardware.org/?probe=917add86ab) | May 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [5cba3c93ba](https://linux-hardware.org/?probe=5cba3c93ba) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| Apple         | MacBookPro5,1               | [d6293e8334](https://linux-hardware.org/?probe=d6293e8334) | May 05, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [0afdbf373d](https://linux-hardware.org/?probe=0afdbf373d) | May 04, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a30b11f1a0](https://linux-hardware.org/?probe=a30b11f1a0) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ecc7f176ff](https://linux-hardware.org/?probe=ecc7f176ff) | May 03, 2022 |
| Chuwi         | Hi10 Go                     | [33ea61404a](https://linux-hardware.org/?probe=33ea61404a) | May 03, 2022 |
| Acer          | Aspire A315-56              | [4321ddf926](https://linux-hardware.org/?probe=4321ddf926) | May 03, 2022 |
| Acer          | Aspire one 1-131            | [ade813cf7f](https://linux-hardware.org/?probe=ade813cf7f) | May 03, 2022 |
| Acer          | Aspire 5742G                | [37dfe53a95](https://linux-hardware.org/?probe=37dfe53a95) | May 02, 2022 |
| Acer          | Aspire 5742G                | [aff42aff28](https://linux-hardware.org/?probe=aff42aff28) | May 02, 2022 |
| HP            | Notebook                    | [3bdd2a5e96](https://linux-hardware.org/?probe=3bdd2a5e96) | May 01, 2022 |
| HP            | Pavilion g6                 | [bc4107a3bf](https://linux-hardware.org/?probe=bc4107a3bf) | May 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b152a1215a](https://linux-hardware.org/?probe=b152a1215a) | Apr 30, 2022 |
| HP            | 650                         | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e14a2c047d](https://linux-hardware.org/?probe=e14a2c047d) | Apr 30, 2022 |
| HP            | Stream Notebook PC 13       | [f4eb2d351c](https://linux-hardware.org/?probe=f4eb2d351c) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Acer          | TravelMate 6592             | [7d4878ff33](https://linux-hardware.org/?probe=7d4878ff33) | Apr 29, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [dc1c531e45](https://linux-hardware.org/?probe=dc1c531e45) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [c3dad3331c](https://linux-hardware.org/?probe=c3dad3331c) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [b72fe24642](https://linux-hardware.org/?probe=b72fe24642) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [4dc675b81c](https://linux-hardware.org/?probe=4dc675b81c) | Apr 27, 2022 |
| Lenovo        | Z50-70 20354                | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| Dell          | G15 5510                    | [5126d58147](https://linux-hardware.org/?probe=5126d58147) | Apr 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [3fcb247b21](https://linux-hardware.org/?probe=3fcb247b21) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| MSI           | GX700                       | [b2cc52d381](https://linux-hardware.org/?probe=b2cc52d381) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [998ea03b05](https://linux-hardware.org/?probe=998ea03b05) | Apr 22, 2022 |
| Lenovo        | ThinkPad P53 20QN000ESP     | [16b3189bd8](https://linux-hardware.org/?probe=16b3189bd8) | Apr 22, 2022 |
| Dell          | XPS 13 7390                 | [b2cc2161d3](https://linux-hardware.org/?probe=b2cc2161d3) | Apr 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e0d5f104b9](https://linux-hardware.org/?probe=e0d5f104b9) | Apr 21, 2022 |
| eMachines     | D730                        | [09350021b3](https://linux-hardware.org/?probe=09350021b3) | Apr 20, 2022 |
| Lenovo        | Z50-70 20354                | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Toshiba       | Satellite Pro C660          | [678e3209cb](https://linux-hardware.org/?probe=678e3209cb) | Apr 18, 2022 |
| Chuwi         | Unknown                     | [a44bd392c5](https://linux-hardware.org/?probe=a44bd392c5) | Apr 18, 2022 |
| Lenovo        | Z50-70 20354                | [e693d05883](https://linux-hardware.org/?probe=e693d05883) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [4058d0c1ca](https://linux-hardware.org/?probe=4058d0c1ca) | Apr 17, 2022 |
| Acer          | Aspire 5750                 | [4ce545cc86](https://linux-hardware.org/?probe=4ce545cc86) | Apr 16, 2022 |
| Toshiba       | Satellite L10W-B-101        | [65edd32378](https://linux-hardware.org/?probe=65edd32378) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| LG Electro... | 15Z95P-G.AA78B              | [f5ef9987a4](https://linux-hardware.org/?probe=f5ef9987a4) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| Toshiba       | NB520                       | [105666a973](https://linux-hardware.org/?probe=105666a973) | Apr 15, 2022 |
| AMI           | Intel                       | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| Acer          | TravelMate P256-MG          | [55b07b48b3](https://linux-hardware.org/?probe=55b07b48b3) | Apr 14, 2022 |
| HP            | Laptop 15s-fq1xxx           | [48794f7ff0](https://linux-hardware.org/?probe=48794f7ff0) | Apr 14, 2022 |
| SLIMBOOK      | PRO                         | [97f545c3d4](https://linux-hardware.org/?probe=97f545c3d4) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3e5c6ada15](https://linux-hardware.org/?probe=3e5c6ada15) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | IdeaPad S540-13ARE 82DL     | [17363a1a13](https://linux-hardware.org/?probe=17363a1a13) | Apr 14, 2022 |
| HP            | Presario C500 (RY512EA#A... | [558d84adac](https://linux-hardware.org/?probe=558d84adac) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| Unknown       | Unknown                     | [63f76ffc2b](https://linux-hardware.org/?probe=63f76ffc2b) | Apr 13, 2022 |
| Unknown       | Unknown                     | [3a9245cdab](https://linux-hardware.org/?probe=3a9245cdab) | Apr 13, 2022 |
| Acer          | Aspire E5-573G              | [0fbee9d8dc](https://linux-hardware.org/?probe=0fbee9d8dc) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| HP            | Compaq Mini CQ10-100        | [1acc227c33](https://linux-hardware.org/?probe=1acc227c33) | Apr 13, 2022 |
| Sony          | VGN-NW21EF_S                | [4ade997baf](https://linux-hardware.org/?probe=4ade997baf) | Apr 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| MSI           | Prestige 15 A11SCX          | [a5bf5ddddf](https://linux-hardware.org/?probe=a5bf5ddddf) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| HP            | Pavilion g6                 | [19ccaef18f](https://linux-hardware.org/?probe=19ccaef18f) | Apr 11, 2022 |
| HP            | Pavilion g6                 | [dabfb4bb05](https://linux-hardware.org/?probe=dabfb4bb05) | Apr 11, 2022 |
| ASUSTek       | X540LJ                      | [2eb11881fa](https://linux-hardware.org/?probe=2eb11881fa) | Apr 09, 2022 |
| Dell          | Latitude D630               | [6c715d7619](https://linux-hardware.org/?probe=6c715d7619) | Apr 09, 2022 |
| HP            | Laptop 15s-fq2xxx           | [a0001e2492](https://linux-hardware.org/?probe=a0001e2492) | Apr 09, 2022 |
| HP            | Compaq 15                   | [e3c3ac6478](https://linux-hardware.org/?probe=e3c3ac6478) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| HP            | 250 G7 Notebook PC          | [6271f39c13](https://linux-hardware.org/?probe=6271f39c13) | Apr 08, 2022 |
| HP            | ProBook 650 G1              | [9bd404657b](https://linux-hardware.org/?probe=9bd404657b) | Apr 08, 2022 |
| HP            | Laptop 14s-dq1xxx           | [72c98b5e79](https://linux-hardware.org/?probe=72c98b5e79) | Apr 07, 2022 |
| Dell          | Studio 1749                 | [14d44c44fc](https://linux-hardware.org/?probe=14d44c44fc) | Apr 07, 2022 |
| Acer          | Nitro AN517-41              | [b7cc683cc7](https://linux-hardware.org/?probe=b7cc683cc7) | Apr 05, 2022 |
| Acer          | Extensa 2511                | [00d24bfb95](https://linux-hardware.org/?probe=00d24bfb95) | Apr 05, 2022 |
| Dell          | XPS 15 9570                 | [0437f62b89](https://linux-hardware.org/?probe=0437f62b89) | Apr 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [91bae7b644](https://linux-hardware.org/?probe=91bae7b644) | Apr 05, 2022 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | [c5fcd04bc5](https://linux-hardware.org/?probe=c5fcd04bc5) | Apr 04, 2022 |
| HP            | Laptop 15-da0xxx            | [7894bcc256](https://linux-hardware.org/?probe=7894bcc256) | Apr 03, 2022 |
| Acer          | Aspire F5-571               | [68cb5f9f95](https://linux-hardware.org/?probe=68cb5f9f95) | Apr 03, 2022 |
| Lenovo        | G580 2189                   | [da5b37bf9f](https://linux-hardware.org/?probe=da5b37bf9f) | Apr 02, 2022 |
| Toshiba       | Satellite L300              | [d3d1814f5d](https://linux-hardware.org/?probe=d3d1814f5d) | Apr 01, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [afd4df967a](https://linux-hardware.org/?probe=afd4df967a) | Mar 29, 2022 |
| HP            | 355 G2                      | [5a5271a7df](https://linux-hardware.org/?probe=5a5271a7df) | Mar 29, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dddc946b70](https://linux-hardware.org/?probe=dddc946b70) | Mar 29, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [e2dcac3e1a](https://linux-hardware.org/?probe=e2dcac3e1a) | Mar 29, 2022 |
| Chuwi         | LapBook SE                  | [69b963a8c0](https://linux-hardware.org/?probe=69b963a8c0) | Mar 28, 2022 |
| LG Electro... | 14Z90N-V.AR55B              | [4942a692f0](https://linux-hardware.org/?probe=4942a692f0) | Mar 28, 2022 |
| Dell          | XPS 13 9360                 | [9579421df6](https://linux-hardware.org/?probe=9579421df6) | Mar 28, 2022 |
| Lenovo        | ThinkPad T61 6464W4J        | [5f73680acf](https://linux-hardware.org/?probe=5f73680acf) | Mar 28, 2022 |
| HP            | Pavilion g6                 | [954723d6f4](https://linux-hardware.org/?probe=954723d6f4) | Mar 27, 2022 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [078c1af4c3](https://linux-hardware.org/?probe=078c1af4c3) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ba743bbb3b](https://linux-hardware.org/?probe=ba743bbb3b) | Mar 27, 2022 |
| Apple         | MacBook10,1                 | [62a1f4a38b](https://linux-hardware.org/?probe=62a1f4a38b) | Mar 25, 2022 |
| Apple         | MacBook10,1                 | [b58112c801](https://linux-hardware.org/?probe=b58112c801) | Mar 25, 2022 |
| Acer          | Aspire 5750G                | [4a7e22384f](https://linux-hardware.org/?probe=4a7e22384f) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8064b23bf4](https://linux-hardware.org/?probe=8064b23bf4) | Mar 25, 2022 |
| HP            | Laptop 17-cn0xxx            | [9400fdbebf](https://linux-hardware.org/?probe=9400fdbebf) | Mar 24, 2022 |
| HP            | Laptop 15-da0xxx            | [794139f740](https://linux-hardware.org/?probe=794139f740) | Mar 24, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [5a64dc1855](https://linux-hardware.org/?probe=5a64dc1855) | Mar 23, 2022 |
| Dell          | XPS 13 9360                 | [30003161fe](https://linux-hardware.org/?probe=30003161fe) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | Latitude E6330              | [a8d483108b](https://linux-hardware.org/?probe=a8d483108b) | Mar 22, 2022 |
| Acer          | TravelMate P256-MG          | [ec8aff9fc7](https://linux-hardware.org/?probe=ec8aff9fc7) | Mar 21, 2022 |
| Timi          | RedmiBook 16                | [0d8a2d4ea4](https://linux-hardware.org/?probe=0d8a2d4ea4) | Mar 21, 2022 |
| DIODE         | MS-N014                     | [0b95290c21](https://linux-hardware.org/?probe=0b95290c21) | Mar 21, 2022 |
| ASUSTek       | X553MA                      | [56d8c8496b](https://linux-hardware.org/?probe=56d8c8496b) | Mar 20, 2022 |
| HUAWEI        | HN-WX9X                     | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E5430 non-vPro     | [28d7818dd8](https://linux-hardware.org/?probe=28d7818dd8) | Mar 19, 2022 |
| HP            | EliteBook 2740p             | [b0fbd4018d](https://linux-hardware.org/?probe=b0fbd4018d) | Mar 18, 2022 |
| HP            | Presario CQ57               | [d5985051c5](https://linux-hardware.org/?probe=d5985051c5) | Mar 18, 2022 |
| HP            | Laptop 17-cn0xxx            | [cf2893ebfd](https://linux-hardware.org/?probe=cf2893ebfd) | Mar 16, 2022 |
| Acer          | Aspire SW3-016              | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| HP            | Laptop 15-bs0xx             | [2dd60fe836](https://linux-hardware.org/?probe=2dd60fe836) | Mar 13, 2022 |
| HP            | Pavilion Notebook           | [1de76aac69](https://linux-hardware.org/?probe=1de76aac69) | Mar 12, 2022 |
| HP            | EliteBook 2540p             | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| ASUSTek       | K53U                        | [7f78b941ce](https://linux-hardware.org/?probe=7f78b941ce) | Mar 11, 2022 |
| Acer          | Aspire A114-31              | [aa9bcbb679](https://linux-hardware.org/?probe=aa9bcbb679) | Mar 11, 2022 |
| HP            | Pavilion g6                 | [a7ca755c8e](https://linux-hardware.org/?probe=a7ca755c8e) | Mar 11, 2022 |
| HP            | ENVY Notebook               | [591f84e3bb](https://linux-hardware.org/?probe=591f84e3bb) | Mar 11, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS08Q0... | [10655c6e60](https://linux-hardware.org/?probe=10655c6e60) | Mar 11, 2022 |
| HP            | Pavilion g6                 | [570c07ee5c](https://linux-hardware.org/?probe=570c07ee5c) | Mar 10, 2022 |
| Acer          | Aspire S3                   | [6ae9c3b307](https://linux-hardware.org/?probe=6ae9c3b307) | Mar 10, 2022 |
| Dell          | Latitude 5520               | [bb234c5fd0](https://linux-hardware.org/?probe=bb234c5fd0) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | [3df16e8d72](https://linux-hardware.org/?probe=3df16e8d72) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | [a67d3468f1](https://linux-hardware.org/?probe=a67d3468f1) | Mar 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 383       | 13.92%  |
| Ubuntu 18.04       | 251       | 9.12%   |
| Debian 11          | 118       | 4.29%   |
| Ubuntu 22.04       | 108       | 3.93%   |
| OpenMandriva 4.2   | 83        | 3.02%   |
| KDE neon 20.04     | 63        | 2.29%   |
| OpenMandriva 4.3   | 58        | 2.11%   |
| Zorin 16           | 53        | 1.93%   |
| Linux Mint 20.3    | 41        | 1.49%   |
| Arch               | 41        | 1.49%   |
| Ubuntu 20.10       | 39        | 1.42%   |
| Xubuntu 20.04      | 37        | 1.34%   |
| Linux Mint 19.3    | 36        | 1.31%   |
| Debian 10          | 36        | 1.31%   |
| Ubuntu 19.10       | 34        | 1.24%   |
| Manjaro            | 34        | 1.24%   |
| Ubuntu 21.04       | 32        | 1.16%   |
| Ubuntu 19.04       | 32        | 1.16%   |
| Linux Mint 20.1    | 31        | 1.13%   |
| Linux Mint 20      | 30        | 1.09%   |
| Ubuntu 21.10       | 29        | 1.05%   |
| Fedora 36          | 29        | 1.05%   |
| Kubuntu 20.04      | 28        | 1.02%   |
| Xubuntu 18.04      | 27        | 0.98%   |
| Linux Mint 20.2    | 27        | 0.98%   |
| Arch Rolling       | 27        | 0.98%   |
| Zorin 15           | 25        | 0.91%   |
| Fedora 35          | 25        | 0.91%   |
| Fedora 34          | 24        | 0.87%   |
| Fedora 33          | 24        | 0.87%   |
| OpenMandriva 23.01 | 23        | 0.84%   |
| ROSA R10           | 22        | 0.8%    |
| Ubuntu 18.10       | 21        | 0.76%   |
| Pop!_OS 20.04      | 21        | 0.76%   |
| Pop!_OS 22.04      | 20        | 0.73%   |
| Linux Mint 21      | 20        | 0.73%   |
| Pop!_OS 20.10      | 19        | 0.69%   |
| Linux Mint 19.2    | 17        | 0.62%   |
| Debian Testing     | 17        | 0.62%   |
| Ubuntu 16.04       | 16        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 920       | 35.09%  |
| Linux Mint    | 210       | 8.01%   |
| Debian        | 183       | 6.98%   |
| OpenMandriva  | 179       | 6.83%   |
| Fedora        | 131       | 5%      |
| Endless       | 100       | 3.81%   |
| Manjaro       | 92        | 3.51%   |
| Zorin         | 81        | 3.09%   |
| KDE neon      | 77        | 2.94%   |
| Xubuntu       | 73        | 2.78%   |
| Pop!_OS       | 73        | 2.78%   |
| Arch          | 67        | 2.56%   |
| Kubuntu       | 64        | 2.44%   |
| ROSA          | 54        | 2.06%   |
| Ubuntu MATE   | 30        | 1.14%   |
| Elementary    | 27        | 1.03%   |
| Ubuntu Unity  | 23        | 0.88%   |
| Kali          | 20        | 0.76%   |
| openSUSE      | 19        | 0.72%   |
| Lubuntu       | 17        | 0.65%   |
| BlackPanther  | 16        | 0.61%   |
| ArcoLinux     | 16        | 0.61%   |
| SteamOS       | 15        | 0.57%   |
| Gentoo        | 13        | 0.5%    |
| Parrot        | 12        | 0.46%   |
| LMDE          | 12        | 0.46%   |
| EndeavourOS   | 9         | 0.34%   |
| Ubuntu Budgie | 7         | 0.27%   |
| MX            | 7         | 0.27%   |
| Clear Linux   | 6         | 0.23%   |
| Deepin        | 5         | 0.19%   |
| CentOS        | 5         | 0.19%   |
| RHEL          | 4         | 0.15%   |
| Nobara        | 4         | 0.15%   |
| Garuda Linux  | 4         | 0.15%   |
| Ubuntu Studio | 3         | 0.11%   |
| Solus         | 3         | 0.11%   |
| Reborn OS     | 3         | 0.11%   |
| Q4OS          | 3         | 0.11%   |
| Peppermint    | 3         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 81        | 2.72%   |
| 5.16.7-desktop-1omv4003         | 58        | 1.95%   |
| 5.4.0-42-generic                | 48        | 1.61%   |
| 5.10.0-8-amd64                  | 34        | 1.14%   |
| 5.4.0-58-generic                | 33        | 1.11%   |
| 5.15.0-56-generic               | 33        | 1.11%   |
| 5.15.0-52-generic               | 32        | 1.07%   |
| 5.3.0-28-generic                | 31        | 1.04%   |
| 5.4.0-54-generic                | 27        | 0.91%   |
| 5.4.0-52-generic                | 26        | 0.87%   |
| 5.4.0-26-generic                | 26        | 0.87%   |
| 5.10.0-18-amd64                 | 25        | 0.84%   |
| 6.1.1-desktop-1omv2290          | 22        | 0.74%   |
| 5.15.0-53-generic               | 22        | 0.74%   |
| 5.0.0-37-generic                | 22        | 0.74%   |
| 5.3.0-46-generic                | 21        | 0.7%    |
| 5.3.0-40-generic                | 21        | 0.7%    |
| 5.15.0-48-generic               | 21        | 0.7%    |
| 5.11.0-27-generic               | 21        | 0.7%    |
| 5.4.0-65-generic                | 20        | 0.67%   |
| 5.4.0-48-generic                | 20        | 0.67%   |
| 5.11.0-43-generic               | 19        | 0.64%   |
| 5.11.0-41-generic               | 19        | 0.64%   |
| 5.4.0-72-generic                | 18        | 0.6%    |
| 5.4.0-40-generic                | 18        | 0.6%    |
| 5.0.0-32-generic                | 18        | 0.6%    |
| 5.8.0-44-generic                | 17        | 0.57%   |
| 5.4.0-19-generic                | 16        | 0.54%   |
| 5.3.0-45-generic                | 16        | 0.54%   |
| 5.15.0-58-generic               | 16        | 0.54%   |
| 5.8.0-14-generic                | 15        | 0.5%    |
| 5.4.0-29-generic                | 15        | 0.5%    |
| 5.15.0-47-generic               | 15        | 0.5%    |
| 5.13.0-28-generic               | 15        | 0.5%    |
| 5.8.0-43-generic                | 14        | 0.47%   |
| 5.4.0-70-generic                | 14        | 0.47%   |
| 5.4.0-53-generic                | 14        | 0.47%   |
| 5.3.0-51-generic                | 14        | 0.47%   |
| 5.3.0-42-generic                | 14        | 0.47%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 530       | 18.83%  |
| 5.15.0  | 222       | 7.89%   |
| 4.15.0  | 201       | 7.14%   |
| 5.11.0  | 166       | 5.9%    |
| 5.3.0   | 153       | 5.44%   |
| 5.8.0   | 150       | 5.33%   |
| 5.10.0  | 140       | 4.97%   |
| 5.13.0  | 128       | 4.55%   |
| 5.0.0   | 109       | 3.87%   |
| 5.10.14 | 82        | 2.91%   |
| 4.18.0  | 71        | 2.52%   |
| 5.16.7  | 62        | 2.2%    |
| 4.19.0  | 41        | 1.46%   |
| 5.19.0  | 33        | 1.17%   |
| 6.1.1   | 28        | 0.99%   |
| 4.9.60  | 15        | 0.53%   |
| 6.0.0   | 14        | 0.5%    |
| 5.14.0  | 14        | 0.5%    |
| 5.18.0  | 13        | 0.46%   |
| 4.4.0   | 13        | 0.46%   |
| 4.18.16 | 13        | 0.46%   |
| 5.9.16  | 10        | 0.36%   |
| 6.0.12  | 8         | 0.28%   |
| 5.17.5  | 8         | 0.28%   |
| 5.3.18  | 7         | 0.25%   |
| 5.17.1  | 7         | 0.25%   |
| 5.16.0  | 7         | 0.25%   |
| 5.13.12 | 7         | 0.25%   |
| 5.11.12 | 7         | 0.25%   |
| 6.0.6   | 6         | 0.21%   |
| 5.9.0   | 6         | 0.21%   |
| 5.16.11 | 6         | 0.21%   |
| 5.12.4  | 6         | 0.21%   |
| 6.0.10  | 5         | 0.18%   |
| 5.7.0   | 5         | 0.18%   |
| 5.19.2  | 5         | 0.18%   |
| 5.16.9  | 5         | 0.18%   |
| 5.15.12 | 5         | 0.18%   |
| 5.10.7  | 5         | 0.18%   |
| 4.9.20  | 5         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 562       | 20.19%  |
| 5.15    | 275       | 9.88%   |
| 5.10    | 259       | 9.31%   |
| 4.15    | 201       | 7.22%   |
| 5.11    | 194       | 6.97%   |
| 5.8     | 176       | 6.32%   |
| 5.3     | 168       | 6.04%   |
| 5.13    | 148       | 5.32%   |
| 5.0     | 111       | 3.99%   |
| 5.16    | 97        | 3.49%   |
| 4.18    | 84        | 3.02%   |
| 5.19    | 66        | 2.37%   |
| 6.0     | 51        | 1.83%   |
| 4.19    | 49        | 1.76%   |
| 6.1     | 41        | 1.47%   |
| 5.14    | 39        | 1.4%    |
| 4.9     | 38        | 1.37%   |
| 5.18    | 37        | 1.33%   |
| 5.9     | 29        | 1.04%   |
| 5.17    | 29        | 1.04%   |
| 5.6     | 25        | 0.9%    |
| 5.7     | 24        | 0.86%   |
| 5.12    | 23        | 0.83%   |
| 5.5     | 14        | 0.5%    |
| 4.4     | 14        | 0.5%    |
| 4.16    | 5         | 0.18%   |
| 5.2     | 4         | 0.14%   |
| 4.1     | 4         | 0.14%   |
| 3.10    | 4         | 0.14%   |
| 5.1     | 3         | 0.11%   |
| 4.20    | 3         | 0.11%   |
| 4.13    | 3         | 0.11%   |
| 4.8     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 3.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2424      | 95.43%  |
| i686   | 116       | 4.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1165      | 43.78%  |
| KDE5             | 444       | 16.69%  |
| Unknown          | 324       | 12.18%  |
| XFCE             | 211       | 7.93%   |
| X-Cinnamon       | 159       | 5.98%   |
| MATE             | 78        | 2.93%   |
| KDE              | 76        | 2.86%   |
| Cinnamon         | 28        | 1.05%   |
| Pantheon         | 26        | 0.98%   |
| Unity            | 22        | 0.83%   |
| LXQt             | 22        | 0.83%   |
| KDE4             | 22        | 0.83%   |
| i3               | 16        | 0.6%    |
| LXDE             | 14        | 0.53%   |
| GNOME Flashback  | 11        | 0.41%   |
| Budgie           | 11        | 0.41%   |
| Deepin           | 9         | 0.34%   |
| openbox          | 4         | 0.15%   |
| GNOME Classic    | 4         | 0.15%   |
| bspwm            | 3         | 0.11%   |
| DWM              | 2         | 0.08%   |
| trinity          | 1         | 0.04%   |
| river            | 1         | 0.04%   |
| qtile            | 1         | 0.04%   |
| Lubuntu          | 1         | 0.04%   |
| lightdm-xsession | 1         | 0.04%   |
| LeftWM           | 1         | 0.04%   |
| i3-with-shmlog   | 1         | 0.04%   |
| enlightenment    | 1         | 0.04%   |
| Cutefish         | 1         | 0.04%   |
| awesome          | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2067      | 79.1%   |
| Wayland | 344       | 13.16%  |
| Unknown | 185       | 7.08%   |
| Tty     | 17        | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1368      | 51.98%  |
| SDDM    | 383       | 14.55%  |
| GDM     | 339       | 12.88%  |
| GDM3    | 211       | 8.02%   |
| LightDM | 204       | 7.75%   |
| TDM     | 90        | 3.42%   |
| KDM     | 24        | 0.91%   |
| XDM     | 7         | 0.27%   |
| SLiM    | 3         | 0.11%   |
| Ly      | 3         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 1497      | 57.4%   |
| en_US          | 465       | 17.83%  |
| Unknown        | 334       | 12.81%  |
| ca_ES          | 101       | 3.87%   |
| en_GB          | 61        | 2.34%   |
| C              | 25        | 0.96%   |
| de_DE          | 18        | 0.69%   |
| gl_ES          | 12        | 0.46%   |
| eu_ES          | 11        | 0.42%   |
| fr_FR          | 9         | 0.35%   |
| ru_RU          | 8         | 0.31%   |
| it_IT          | 8         | 0.31%   |
| an_ES          | 8         | 0.31%   |
| es_AR          | 6         | 0.23%   |
| es_MX          | 5         | 0.19%   |
| pt_BR          | 4         | 0.15%   |
| en_AG          | 4         | 0.15%   |
| ca_AD          | 4         | 0.15%   |
| fr_BE          | 3         | 0.12%   |
| pl_PL          | 2         | 0.08%   |
| nl_NL          | 2         | 0.08%   |
| es_US          | 2         | 0.08%   |
| es_BO          | 2         | 0.08%   |
| en_IE          | 2         | 0.08%   |
| sp_SP          | 1         | 0.04%   |
| POSIX          | 1         | 0.04%   |
| nb_NO          | 1         | 0.04%   |
| fr_CH          | 1         | 0.04%   |
| et_EE          | 1         | 0.04%   |
| es_VE          | 1         | 0.04%   |
| es_PE          | 1         | 0.04%   |
| en_NZ          | 1         | 0.04%   |
| en_HK          | 1         | 0.04%   |
| en_CA          | 1         | 0.04%   |
| en_AU          | 1         | 0.04%   |
| de_CH          | 1         | 0.04%   |
| de_AT          | 1         | 0.04%   |
| ca_ES@valencia | 1         | 0.04%   |
| C.UTF8         | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1383      | 53.44%  |
| BIOS | 1205      | 46.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2056      | 79.23%  |
| Overlay | 196       | 7.55%   |
| Btrfs   | 160       | 6.17%   |
| Unknown | 111       | 4.28%   |
| Xfs     | 32        | 1.23%   |
| Zfs     | 17        | 0.66%   |
| Ext2    | 10        | 0.39%   |
| Tmpfs   | 4         | 0.15%   |
| Ext3    | 4         | 0.15%   |
| Jfs     | 2         | 0.08%   |
| Aufs    | 2         | 0.08%   |
| F2fs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1466      | 56.58%  |
| GPT     | 857       | 33.08%  |
| MBR     | 268       | 10.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2289      | 88.79%  |
| Yes       | 289       | 11.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1795      | 69.57%  |
| Yes       | 785       | 30.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 488       | 19.22%  |
| Lenovo              | 433       | 17.05%  |
| ASUSTek Computer    | 385       | 15.16%  |
| Acer                | 256       | 10.08%  |
| Dell                | 204       | 8.03%   |
| MSI                 | 159       | 6.26%   |
| Toshiba             | 103       | 4.06%   |
| Apple               | 63        | 2.48%   |
| Sony                | 38        | 1.5%    |
| Packard Bell        | 34        | 1.34%   |
| HUAWEI              | 34        | 1.34%   |
| Unknown             | 28        | 1.1%    |
| Samsung Electronics | 27        | 1.06%   |
| Notebook            | 26        | 1.02%   |
| Chuwi               | 26        | 1.02%   |
| SLIMBOOK            | 25        | 0.98%   |
| LG Electronics      | 20        | 0.79%   |
| Valve               | 15        | 0.59%   |
| Medion              | 13        | 0.51%   |
| Fujitsu             | 13        | 0.51%   |
| Timi                | 12        | 0.47%   |
| Fujitsu Siemens     | 11        | 0.43%   |
| eMachines           | 10        | 0.39%   |
| Clevo               | 8         | 0.32%   |
| Teclast             | 7         | 0.28%   |
| Dynabook            | 6         | 0.24%   |
| Intel               | 5         | 0.2%    |
| Gigabyte Technology | 5         | 0.2%    |
| PC Specialist       | 4         | 0.16%   |
| HONOR               | 4         | 0.16%   |
| Razer               | 3         | 0.12%   |
| Qilive              | 3         | 0.12%   |
| IBM                 | 3         | 0.12%   |
| Google              | 3         | 0.12%   |
| Compal              | 3         | 0.12%   |
| Alienware           | 3         | 0.12%   |
| TUXEDO              | 2         | 0.08%   |
| Thomson             | 2         | 0.08%   |
| TEKNOSERVICE        | 2         | 0.08%   |
| OEM                 | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 47        | 1.85%   |
| HP Pavilion g6                             | 21        | 0.83%   |
| HP Pavilion dv6                            | 19        | 0.75%   |
| HP Notebook                                | 18        | 0.71%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.71%   |
| Valve Jupiter                              | 15        | 0.59%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.59%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.59%   |
| HP G62                                     | 11        | 0.43%   |
| HP Laptop 15-da0xxx                        | 10        | 0.39%   |
| Dell XPS 13 7390                           | 10        | 0.39%   |
| HP Pavilion 15                             | 9         | 0.35%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.35%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.32%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 8         | 0.32%   |
| ASUS X555LAB                               | 8         | 0.32%   |
| ASUS X550VX                                | 8         | 0.32%   |
| ASUS X540NA                                | 8         | 0.32%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.32%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.28%   |
| Lenovo G50-70 20351                        | 7         | 0.28%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.28%   |
| HP Pavilion dv7                            | 7         | 0.28%   |
| HP OMEN by Laptop                          | 7         | 0.28%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.28%   |
| HP Laptop 15-bw0xx                         | 7         | 0.28%   |
| Acer Aspire 5750G                          | 7         | 0.28%   |
| Acer Aspire 5738                           | 7         | 0.28%   |
| Lenovo Y520-15IKBN 80WK                    | 6         | 0.24%   |
| Lenovo Legion 5 15ACH6H 82JU               | 6         | 0.24%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 6         | 0.24%   |
| HUAWEI NBLK-WAX9X                          | 6         | 0.24%   |
| HUAWEI BOHK-WAX9X                          | 6         | 0.24%   |
| HP Pavilion Notebook 15-bc5xxx             | 6         | 0.24%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 6         | 0.24%   |
| HP Laptop 15-bs0xx                         | 6         | 0.24%   |
| HP EliteBook 840 G5                        | 6         | 0.24%   |
| HP 250 G7 Notebook PC                      | 6         | 0.24%   |
| HP 250 G6 Notebook PC                      | 6         | 0.24%   |
| Dell XPS 13 9370                           | 6         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 189       | 7.44%   |
| Lenovo ThinkPad       | 162       | 6.38%   |
| Lenovo IdeaPad        | 126       | 4.96%   |
| HP Pavilion           | 119       | 4.69%   |
| Dell Latitude         | 85        | 3.35%   |
| Toshiba Satellite     | 80        | 3.15%   |
| ASUS VivoBook         | 70        | 2.76%   |
| HP Laptop             | 68        | 2.68%   |
| HP EliteBook          | 57        | 2.24%   |
| Dell XPS              | 49        | 1.93%   |
| Unknown               | 47        | 1.85%   |
| HP ProBook            | 39        | 1.54%   |
| HP Compaq             | 37        | 1.46%   |
| Dell Inspiron         | 33        | 1.3%    |
| ASUS ZenBook          | 32        | 1.26%   |
| Packard Bell EasyNote | 31        | 1.22%   |
| HP 250                | 31        | 1.22%   |
| ASUS ROG              | 26        | 1.02%   |
| MSI Prestige          | 24        | 0.95%   |
| Lenovo Legion         | 21        | 0.83%   |
| MSI Modern            | 20        | 0.79%   |
| HP OMEN               | 19        | 0.75%   |
| HP Notebook           | 18        | 0.71%   |
| Lenovo ThinkBook      | 17        | 0.67%   |
| Acer Extensa          | 17        | 0.67%   |
| Acer TravelMate       | 16        | 0.63%   |
| Valve Jupiter         | 15        | 0.59%   |
| ASUS TUF              | 15        | 0.59%   |
| HP ENVY               | 14        | 0.55%   |
| ASUS ASUS             | 14        | 0.55%   |
| Lenovo Yoga           | 12        | 0.47%   |
| Fujitsu LIFEBOOK      | 12        | 0.47%   |
| Dell Vostro           | 12        | 0.47%   |
| HP G62                | 11        | 0.43%   |
| Toshiba PORTEGE       | 10        | 0.39%   |
| HP Victus             | 9         | 0.35%   |
| Chuwi GemiBook        | 9         | 0.35%   |
| Apple MacBookPro11    | 9         | 0.35%   |
| Toshiba TECRA         | 8         | 0.32%   |
| HP ZBook              | 8         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 264       | 10.4%   |
| 2019    | 257       | 10.12%  |
| 2020    | 239       | 9.41%   |
| 2021    | 185       | 7.29%   |
| 2014    | 172       | 6.77%   |
| 2015    | 168       | 6.62%   |
| 2011    | 163       | 6.42%   |
| 2017    | 152       | 5.99%   |
| 2010    | 139       | 5.47%   |
| 2013    | 129       | 5.08%   |
| 2012    | 127       | 5%      |
| 2008    | 127       | 5%      |
| 2016    | 114       | 4.49%   |
| 2009    | 105       | 4.14%   |
| 2007    | 81        | 3.19%   |
| 2022    | 66        | 2.6%    |
| 2006    | 28        | 1.1%    |
| 2005    | 10        | 0.39%   |
| 2004    | 5         | 0.2%    |
| 2003    | 3         | 0.12%   |
| Unknown | 3         | 0.12%   |
| 2002    | 1         | 0.04%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2539      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2326      | 91%     |
| Enabled  | 230       | 9%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2533      | 99.76%  |
| Yes  | 6         | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 670       | 26.13%  |
| 3.01-4.0    | 580       | 22.62%  |
| 8.01-16.0   | 466       | 18.17%  |
| 16.01-24.0  | 451       | 17.59%  |
| 32.01-64.0  | 147       | 5.73%   |
| 1.01-2.0    | 133       | 5.19%   |
| 2.01-3.0    | 47        | 1.83%   |
| 0.51-1.0    | 42        | 1.64%   |
| 24.01-32.0  | 13        | 0.51%   |
| 64.01-256.0 | 13        | 0.51%   |
| 0.01-0.5    | 2         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1086      | 38.84%  |
| 2.01-3.0   | 737       | 26.36%  |
| 4.01-8.0   | 331       | 11.84%  |
| 3.01-4.0   | 299       | 10.69%  |
| 0.51-1.0   | 224       | 8.01%   |
| 8.01-16.0  | 89        | 3.18%   |
| 0.01-0.5   | 24        | 0.86%   |
| 24.01-32.0 | 3         | 0.11%   |
| 16.01-24.0 | 3         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1951      | 75.71%  |
| 2      | 542       | 21.03%  |
| 3      | 55        | 2.13%   |
| 0      | 23        | 0.89%   |
| 4      | 4         | 0.16%   |
| 5      | 2         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1620      | 63.5%   |
| Yes       | 931       | 36.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2056      | 80.56%  |
| No        | 496       | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2488      | 97.99%  |
| No        | 51        | 2.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1875      | 73.21%  |
| No        | 686       | 26.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 2539      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 429       | 15.53%  |
| Barcelona                  | 292       | 10.57%  |
| Seville                    | 98        | 3.55%   |
| Valencia                   | 86        | 3.11%   |
| Zaragoza                   | 43        | 1.56%   |
| Granada                    | 41        | 1.48%   |
| Málaga                    | 37        | 1.34%   |
| Alcobendas                 | 36        | 1.3%    |
| Palma                      | 30        | 1.09%   |
| Valladolid                 | 28        | 1.01%   |
| Sabadell                   | 28        | 1.01%   |
| Vigo                       | 24        | 0.87%   |
| Córdoba                   | 23        | 0.83%   |
| Bilbao                     | 23        | 0.83%   |
| Las Palmas de Gran Canaria | 21        | 0.76%   |
| Alicante                   | 20        | 0.72%   |
| Alcalá de Henares         | 20        | 0.72%   |
| Santiago de Compostela     | 19        | 0.69%   |
| Pamplona                   | 19        | 0.69%   |
| Donostia / San Sebastian   | 19        | 0.69%   |
| A Coruña                  | 17        | 0.62%   |
| Murcia                     | 16        | 0.58%   |
| Mostoles                   | 16        | 0.58%   |
| León                      | 16        | 0.58%   |
| Oviedo                     | 15        | 0.54%   |
| Gijón                     | 15        | 0.54%   |
| Burgos                     | 14        | 0.51%   |
| Barakaldo                  | 13        | 0.47%   |
| Vitoria-Gasteiz            | 12        | 0.43%   |
| Salamanca                  | 12        | 0.43%   |
| Reus                       | 12        | 0.43%   |
| Getxo                      | 12        | 0.43%   |
| Albacete                   | 11        | 0.4%    |
| Pozuelo de Alarcón        | 10        | 0.36%   |
| Pontevedra                 | 10        | 0.36%   |
| Ourense                    | 10        | 0.36%   |
| Dos Hermanas               | 10        | 0.36%   |
| Cartagena                  | 10        | 0.36%   |
| Almería                   | 10        | 0.36%   |
| Alcorcón                  | 10        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 433       | 524    | 14.16%  |
| WDC                         | 343       | 424    | 11.22%  |
| Seagate                     | 320       | 379    | 10.47%  |
| Kingston                    | 314       | 394    | 10.27%  |
| Toshiba                     | 267       | 329    | 8.73%   |
| SanDisk                     | 197       | 251    | 6.44%   |
| Unknown                     | 149       | 195    | 4.87%   |
| SK hynix                    | 134       | 163    | 4.38%   |
| Hitachi                     | 114       | 135    | 3.73%   |
| HGST                        | 97        | 120    | 3.17%   |
| Intel                       | 96        | 130    | 3.14%   |
| Micron Technology           | 92        | 111    | 3.01%   |
| Crucial                     | 92        | 111    | 3.01%   |
| Fujitsu                     | 32        | 36     | 1.05%   |
| KIOXIA                      | 30        | 36     | 0.98%   |
| China                       | 27        | 38     | 0.88%   |
| Phison                      | 26        | 28     | 0.85%   |
| Apple                       | 23        | 30     | 0.75%   |
| LITEON                      | 16        | 17     | 0.52%   |
| Netac                       | 15        | 23     | 0.49%   |
| KingSpec                    | 14        | 18     | 0.46%   |
| Micron/Crucial Technology   | 12        | 14     | 0.39%   |
| A-DATA Technology           | 11        | 13     | 0.36%   |
| Kingston Technology Company | 9         | 11     | 0.29%   |
| JMicron Technology          | 9         | 9      | 0.29%   |
| Transcend                   | 8         | 14     | 0.26%   |
| PNY                         | 8         | 13     | 0.26%   |
| OCZ                         | 8         | 9      | 0.26%   |
| USB30                       | 7         | 8      | 0.23%   |
| FORESEE                     | 7         | 9      | 0.23%   |
| Unknown                     | 7         | 7      | 0.23%   |
| Phison Electronics          | 6         | 6      | 0.2%    |
| Teclast                     | 5         | 5      | 0.16%   |
| Patriot                     | 5         | 6      | 0.16%   |
| LITEONIT                    | 5         | 6      | 0.16%   |
| KingDian                    | 5         | 5      | 0.16%   |
| Emtec                       | 5         | 5      | 0.16%   |
| Silicon Motion              | 4         | 4      | 0.13%   |
| Gigabyte Technology         | 4         | 5      | 0.13%   |
| Corsair                     | 4         | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 114       | 3.62%   |
| Kingston SA400S37480G 480GB SSD        | 42        | 1.33%   |
| Seagate ST500LT012-1DG142 500GB        | 39        | 1.24%   |
| Unknown MMC Card  32GB                 | 35        | 1.11%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 1.08%   |
| HGST HTS721010A9E630 1TB               | 33        | 1.05%   |
| Samsung NVMe SSD Drive 512GB           | 31        | 0.98%   |
| Toshiba MQ01ABF050 500GB               | 30        | 0.95%   |
| Unknown MMC Card  64GB                 | 29        | 0.92%   |
| Toshiba MQ01ABD100 1TB                 | 29        | 0.92%   |
| Seagate ST9500325AS 500GB              | 29        | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 29        | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB         | 28        | 0.89%   |
| Toshiba MQ04ABF100 1TB                 | 27        | 0.86%   |
| SanDisk NVMe SSD Drive 512GB           | 26        | 0.82%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 22        | 0.7%    |
| Samsung SSD 850 EVO 250GB              | 21        | 0.67%   |
| Intel NVMe SSD Drive 512GB             | 21        | 0.67%   |
| Toshiba MQ01ABD050 500GB               | 20        | 0.63%   |
| Samsung SSD 860 EVO 500GB              | 19        | 0.6%    |
| Kingston RBUSC180DS37256GJ 256GB SSD   | 19        | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB               | 18        | 0.57%   |
| Kingston SUV400S37240G 240GB SSD       | 18        | 0.57%   |
| HGST HTS545050A7E680 500GB             | 18        | 0.57%   |
| HGST HTS541010A9E680 1TB               | 18        | 0.57%   |
| Unknown MMC Card  128GB                | 17        | 0.54%   |
| SanDisk SSD PLUS 480GB                 | 17        | 0.54%   |
| SanDisk NVMe SSD Drive 256GB           | 17        | 0.54%   |
| Kingston SA400S37120G 120GB SSD        | 17        | 0.54%   |
| Crucial CT500MX500SSD1 500GB           | 15        | 0.48%   |
| Seagate ST1000LM049-2GH172 1TB         | 14        | 0.44%   |
| Samsung SSD 850 EVO 500GB              | 14        | 0.44%   |
| Micron NVMe SSD Drive 512GB            | 13        | 0.41%   |
| SK hynix NVMe SSD Drive 256GB          | 11        | 0.35%   |
| Seagate Expansion 240GB                | 11        | 0.35%   |
| SanDisk SSD PLUS 1000GB                | 11        | 0.35%   |
| SanDisk NVMe SSD Drive 1024GB          | 11        | 0.35%   |
| Samsung NVMe SSD Drive 1024GB          | 11        | 0.35%   |
| Seagate ST9500420AS 500GB              | 10        | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 10        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 316       | 375    | 31.32%  |
| WDC                 | 221       | 266    | 21.9%   |
| Toshiba             | 181       | 213    | 17.94%  |
| Hitachi             | 114       | 135    | 11.3%   |
| HGST                | 97        | 120    | 9.61%   |
| Fujitsu             | 32        | 36     | 3.17%   |
| Samsung Electronics | 25        | 26     | 2.48%   |
| Unknown             | 6         | 9      | 0.59%   |
| Apple               | 4         | 4      | 0.4%    |
| USB3.0              | 3         | 3      | 0.3%    |
| ASMT                | 3         | 3      | 0.3%    |
| USB                 | 2         | 2      | 0.2%    |
| PHD 3.0             | 1         | 1      | 0.1%    |
| OEM                 | 1         | 1      | 0.1%    |
| Maxone              | 1         | 1      | 0.1%    |
| LaCie               | 1         | 1      | 0.1%    |
| IBM                 | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 271       | 341    | 27.05%  |
| Samsung Electronics | 170       | 205    | 16.97%  |
| SanDisk             | 111       | 135    | 11.08%  |
| Crucial             | 83        | 100    | 8.28%   |
| WDC                 | 40        | 52     | 3.99%   |
| Toshiba             | 40        | 50     | 3.99%   |
| SK hynix            | 31        | 34     | 3.09%   |
| Micron Technology   | 31        | 39     | 3.09%   |
| China               | 27        | 38     | 2.69%   |
| Intel               | 19        | 32     | 1.9%    |
| Netac               | 15        | 23     | 1.5%    |
| LITEON              | 15        | 15     | 1.5%    |
| KingSpec            | 14        | 18     | 1.4%    |
| Apple               | 13        | 15     | 1.3%    |
| A-DATA Technology   | 9         | 11     | 0.9%    |
| OCZ                 | 8         | 9      | 0.8%    |
| USB30               | 7         | 8      | 0.7%    |
| Transcend           | 7         | 13     | 0.7%    |
| FORESEE             | 7         | 9      | 0.7%    |
| PNY                 | 6         | 11     | 0.6%    |
| Teclast             | 5         | 5      | 0.5%    |
| LITEONIT            | 5         | 6      | 0.5%    |
| JMicron Technology  | 5         | 5      | 0.5%    |
| Patriot             | 4         | 5      | 0.4%    |
| KingDian            | 4         | 4      | 0.4%    |
| Emtec               | 4         | 4      | 0.4%    |
| Corsair             | 4         | 5      | 0.4%    |
| Unknown             | 3         | 3      | 0.3%    |
| Unknown             | 3         | 3      | 0.3%    |
| TCSUNBOW            | 2         | 2      | 0.2%    |
| ShanDianZhe         | 2         | 2      | 0.2%    |
| Plextor             | 2         | 3      | 0.2%    |
| KIOXIA-EXCERIA      | 2         | 3      | 0.2%    |
| Intenso             | 2         | 2      | 0.2%    |
| Dogfish             | 2         | 2      | 0.2%    |
| BAITITON            | 2         | 2      | 0.2%    |
| Yeyian              | 1         | 1      | 0.1%    |
| W800S               | 1         | 2      | 0.1%    |
| Vaseky              | 1         | 1      | 0.1%    |
| Union Memory        | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 986       | 1197   | 33.63%  |
| SSD     | 937       | 1253   | 31.96%  |
| NVMe    | 826       | 1080   | 28.17%  |
| MMC     | 148       | 192    | 5.05%   |
| Unknown | 35        | 40     | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1712      | 2384   | 61.58%  |
| NVMe | 825       | 1077   | 29.68%  |
| MMC  | 148       | 192    | 5.32%   |
| SAS  | 95        | 109    | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1384      | 1865   | 74.05%  |
| 0.51-1.0   | 445       | 536    | 23.81%  |
| 1.01-2.0   | 31        | 38     | 1.66%   |
| 3.01-4.0   | 5         | 6      | 0.27%   |
| 4.01-10.0  | 3         | 4      | 0.16%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 830       | 31.37%  |
| 251-500        | 745       | 28.16%  |
| 501-1000       | 325       | 12.28%  |
| 1-20           | 199       | 7.52%   |
| 51-100         | 199       | 7.52%   |
| 21-50          | 128       | 4.84%   |
| 1001-2000      | 108       | 4.08%   |
| Unknown        | 54        | 2.04%   |
| 2001-3000      | 31        | 1.17%   |
| More than 3000 | 27        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1164      | 42.02%  |
| 21-50          | 520       | 18.77%  |
| 101-250        | 383       | 13.83%  |
| 51-100         | 307       | 11.08%  |
| 251-500        | 199       | 7.18%   |
| 501-1000       | 100       | 3.61%   |
| Unknown        | 54        | 1.95%   |
| 1001-2000      | 26        | 0.94%   |
| 2001-3000      | 8         | 0.29%   |
| More than 3000 | 7         | 0.25%   |
| 0              | 2         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                | 6         | 7      | 3.95%   |
| Seagate ST500LT012-1DG142 500GB          | 5         | 5      | 3.29%   |
| SanDisk SSD PLUS 480GB                   | 5         | 6      | 3.29%   |
| HGST HTS545050A7E680 500GB               | 5         | 7      | 3.29%   |
| Seagate ST9500420AS 500GB                | 4         | 4      | 2.63%   |
| Seagate ST9250827AS 250GB                | 4         | 4      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB           | 4         | 4      | 2.63%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 2.63%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 1.97%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 1.97%   |
| WDC WD5000BPVT-60HXZT3 500GB             | 2         | 2      | 1.32%   |
| Toshiba Q300. 240GB SSD                  | 2         | 2      | 1.32%   |
| Toshiba MK5076GSX 500GB                  | 2         | 2      | 1.32%   |
| Seagate ST9500420ASG 500GB               | 2         | 2      | 1.32%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 2      | 1.32%   |
| Seagate ST320LT012-9WS14C 320GB          | 2         | 2      | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 1.32%   |
| Kingston SV300S37A120G 120GB SSD         | 2         | 2      | 1.32%   |
| Kingston SA400S37480G 480GB SSD          | 2         | 2      | 1.32%   |
| Intel SSDSC2BF180A5H SED 180GB           | 2         | 2      | 1.32%   |
| Hitachi HTS543232A7A384 320GB            | 2         | 2      | 1.32%   |
| HGST HTS545050A7E380 500GB               | 2         | 2      | 1.32%   |
| Fujitsu MHZ2250BH G2 250GB               | 2         | 2      | 1.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.66%   |
| WDC WD7500BPVT-60HXZT1 752GB             | 1         | 1      | 0.66%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1      | 0.66%   |
| WDC WD3200BEVT-00A0RT0 320GB             | 1         | 1      | 0.66%   |
| WDC WD3200BEKT-60V5T1 320GB              | 1         | 1      | 0.66%   |
| WDC WD3200BEKT-60F3T1 320GB              | 1         | 2      | 0.66%   |
| WDC WD2500BEVS-60UST0 250GB              | 1         | 1      | 0.66%   |
| WDC WD2500BEVS-22UST0 250GB              | 1         | 1      | 0.66%   |
| WDC WD1600BEVT-60ZCT0 160GB              | 1         | 1      | 0.66%   |
| WDC WD1600BEVS-60RST0 160GB              | 1         | 1      | 0.66%   |
| WDC WD1600BEVS-22RST0 160GB              | 1         | 1      | 0.66%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.66%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 0.66%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.66%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.66%   |
| Toshiba THNSNJ256G8NY 256GB SSD          | 1         | 1      | 0.66%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.66%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 46     | 28.95%  |
| Hitachi             | 19        | 20     | 12.5%   |
| Toshiba             | 18        | 19     | 11.84%  |
| HGST                | 16        | 19     | 10.53%  |
| WDC                 | 15        | 16     | 9.87%   |
| Samsung Electronics | 9         | 9      | 5.92%   |
| SanDisk             | 6         | 7      | 3.95%   |
| Kingston            | 6         | 7      | 3.95%   |
| Intel               | 6         | 6      | 3.95%   |
| Fujitsu             | 4         | 4      | 2.63%   |
| Micron Technology   | 3         | 3      | 1.97%   |
| SK hynix            | 2         | 2      | 1.32%   |
| Crucial             | 2         | 3      | 1.32%   |
| OCZ                 | 1         | 1      | 0.66%   |
| IBM                 | 1         | 1      | 0.66%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 46     | 37.93%  |
| Hitachi             | 19        | 20     | 16.38%  |
| HGST                | 16        | 19     | 13.79%  |
| WDC                 | 14        | 15     | 12.07%  |
| Toshiba             | 13        | 14     | 11.21%  |
| Samsung Electronics | 5         | 5      | 4.31%   |
| Fujitsu             | 4         | 4      | 3.45%   |
| IBM                 | 1         | 1      | 0.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 114       | 124    | 76.51%  |
| SSD  | 32        | 36     | 21.48%  |
| NVMe | 3         | 3      | 2.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1578      | 2391   | 58.95%  |
| Works    | 950       | 1207   | 35.49%  |
| Malfunc  | 148       | 163    | 5.53%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1780      | 60.83%  |
| AMD                              | 290       | 9.91%   |
| Samsung Electronics              | 264       | 9.02%   |
| SanDisk                          | 162       | 5.54%   |
| SK hynix                         | 97        | 3.32%   |
| Micron Technology                | 61        | 2.08%   |
| Kingston Technology Company      | 51        | 1.74%   |
| Toshiba America Info Systems     | 47        | 1.61%   |
| Phison Electronics               | 37        | 1.26%   |
| KIOXIA                           | 35        | 1.2%    |
| Nvidia                           | 26        | 0.89%   |
| Micron/Crucial Technology        | 18        | 0.62%   |
| Silicon Integrated Systems [SiS] | 13        | 0.44%   |
| Silicon Motion                   | 7         | 0.24%   |
| VIA Technologies                 | 5         | 0.17%   |
| JMicron Technology               | 5         | 0.17%   |
| Apple                            | 5         | 0.17%   |
| Union Memory (Shenzhen)          | 4         | 0.14%   |
| Solid State Storage Technology   | 3         | 0.1%    |
| O2 Micro                         | 3         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 2         | 0.07%   |
| Marvell Technology Group         | 2         | 0.07%   |
| Lite-On Technology               | 2         | 0.07%   |
| Lenovo                           | 2         | 0.07%   |
| ADATA Technology                 | 2         | 0.07%   |
| Silicon Image                    | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 245       | 7.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 201       | 6.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 131       | 4.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 130       | 4.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 125       | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 122       | 3.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 118       | 3.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 103       | 3.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 87        | 2.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 84        | 2.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 77        | 2.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 70        | 2.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 67        | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                            | 64        | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 64        | 2.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 64        | 2.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 63        | 1.98%   |
| Samsung NVMe SSD Controller 980                                                | 62        | 1.95%   |
| Micron Non-Volatile memory controller                                          | 61        | 1.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 49        | 1.54%   |
| Intel SSD 660P Series                                                          | 49        | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 37        | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 35        | 1.1%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 32        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 32        | 1.01%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 31        | 0.98%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 31        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 31        | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 29        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 28        | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 28        | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 27        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 26        | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 26        | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 26        | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 24        | 0.76%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 24        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 24        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1799      | 58.69%  |
| NVMe | 834       | 27.21%  |
| IDE  | 232       | 7.57%   |
| RAID | 200       | 6.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2105      | 82.91%  |
| AMD          | 433       | 17.05%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 55        | 2.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 52        | 2.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 47        | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 1.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 37        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 1.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 35        | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 35        | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 35        | 1.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 35        | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 31        | 1.22%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 30        | 1.18%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.98%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 25        | 0.98%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.98%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.91%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.87%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 0.83%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 17        | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 17        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 17        | 0.67%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 17        | 0.67%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 17        | 0.67%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 16        | 0.63%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 16        | 0.63%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 15        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 15        | 0.59%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 15        | 0.59%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 15        | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 15        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 606       | 23.86%  |
| Intel Core i5           | 512       | 20.16%  |
| Other                   | 211       | 8.31%   |
| Intel Celeron           | 191       | 7.52%   |
| Intel Core i3           | 190       | 7.48%   |
| Intel Core 2 Duo        | 156       | 6.14%   |
| AMD Ryzen 7             | 121       | 4.76%   |
| Intel Atom              | 93        | 3.66%   |
| AMD Ryzen 5             | 81        | 3.19%   |
| Intel Pentium           | 35        | 1.38%   |
| Intel Pentium Dual-Core | 33        | 1.3%    |
| Intel Pentium Dual      | 29        | 1.14%   |
| AMD A6                  | 27        | 1.06%   |
| AMD A4                  | 26        | 1.02%   |
| Intel Genuine           | 22        | 0.87%   |
| Intel Core 2            | 22        | 0.87%   |
| AMD E1                  | 21        | 0.83%   |
| AMD A8                  | 16        | 0.63%   |
| AMD E                   | 13        | 0.51%   |
| AMD Ryzen 7 PRO         | 10        | 0.39%   |
| AMD Ryzen 3             | 10        | 0.39%   |
| Intel Pentium M         | 9         | 0.35%   |
| AMD Ryzen 9             | 9         | 0.35%   |
| AMD Athlon              | 9         | 0.35%   |
| AMD A10                 | 9         | 0.35%   |
| Intel Core i9           | 8         | 0.31%   |
| Intel Celeron M         | 7         | 0.28%   |
| Intel Core m3           | 5         | 0.2%    |
| Intel Pentium 4         | 4         | 0.16%   |
| AMD Turion II Dual-Core | 4         | 0.16%   |
| AMD Turion 64 X2 Mobile | 4         | 0.16%   |
| AMD FX                  | 4         | 0.16%   |
| AMD Athlon II           | 4         | 0.16%   |
| AMD Turion 64 Mobile    | 3         | 0.12%   |
| AMD A12                 | 3         | 0.12%   |
| Intel Xeon              | 2         | 0.08%   |
| Intel Pentium Silver    | 2         | 0.08%   |
| Intel Core m5           | 2         | 0.08%   |
| Intel Core Duo          | 2         | 0.08%   |
| AMD Ryzen 5 PRO         | 2         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1291      | 50.81%  |
| 4       | 794       | 31.25%  |
| 6       | 165       | 6.49%   |
| 8       | 150       | 5.9%    |
| 1       | 108       | 4.25%   |
| 14      | 16        | 0.63%   |
| 10      | 7         | 0.28%   |
| 12      | 6         | 0.24%   |
| Unknown | 4         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2538      | 99.96%  |
| 2      | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1786      | 70.29%  |
| 1       | 751       | 29.56%  |
| Unknown | 4         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2429      | 95.14%  |
| 32-bit         | 56        | 2.19%   |
| Unknown        | 54        | 2.12%   |
| 64-bit         | 14        | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 474       | 18.12%  |
| 0x206a7    | 134       | 5.12%   |
| 0x306a9    | 110       | 4.2%    |
| 0x806c1    | 94        | 3.59%   |
| 0x806ea    | 92        | 3.52%   |
| 0x40651    | 92        | 3.52%   |
| 0x906ea    | 90        | 3.44%   |
| 0x806ec    | 85        | 3.25%   |
| 0x406e3    | 76        | 2.91%   |
| 0x20655    | 75        | 2.87%   |
| 0x1067a    | 75        | 2.87%   |
| 0x6fd      | 74        | 2.83%   |
| 0x806e9    | 69        | 2.64%   |
| 0x306d4    | 65        | 2.48%   |
| 0x306c3    | 59        | 2.26%   |
| 0x30678    | 47        | 1.8%    |
| 0x706e5    | 38        | 1.45%   |
| 0x10676    | 38        | 1.45%   |
| 0x08108109 | 38        | 1.45%   |
| 0xa0652    | 37        | 1.41%   |
| 0x706a1    | 34        | 1.3%    |
| 0x0a50000c | 33        | 1.26%   |
| 0x06006705 | 33        | 1.26%   |
| 0x506e3    | 31        | 1.19%   |
| 0x20652    | 31        | 1.19%   |
| 0x08108102 | 29        | 1.11%   |
| 0x806eb    | 25        | 0.96%   |
| 0x08600106 | 25        | 0.96%   |
| 0x906e9    | 24        | 0.92%   |
| 0x106ca    | 24        | 0.92%   |
| 0x506c9    | 23        | 0.88%   |
| 0x406c4    | 23        | 0.88%   |
| 0x406c3    | 21        | 0.8%    |
| 0x906a3    | 20        | 0.76%   |
| 0x706a8    | 20        | 0.76%   |
| 0x106c2    | 19        | 0.73%   |
| 0x08600103 | 19        | 0.73%   |
| 0x806d1    | 18        | 0.69%   |
| 0x6f6      | 17        | 0.65%   |
| 0x08608103 | 16        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 464       | 18.27%  |
| Haswell          | 196       | 7.72%   |
| SandyBridge      | 156       | 6.14%   |
| Penryn           | 140       | 5.51%   |
| Core             | 133       | 5.24%   |
| Skylake          | 130       | 5.12%   |
| TigerLake        | 121       | 4.77%   |
| IvyBridge        | 121       | 4.77%   |
| Westmere         | 117       | 4.61%   |
| Silvermont       | 109       | 4.29%   |
| Broadwell        | 82        | 3.23%   |
| Zen+             | 77        | 3.03%   |
| Zen 2            | 71        | 2.8%    |
| Goldmont plus    | 64        | 2.52%   |
| Unknown          | 60        | 2.36%   |
| Excavator        | 57        | 2.24%   |
| Bonnell          | 56        | 2.21%   |
| IceLake          | 54        | 2.13%   |
| CometLake        | 52        | 2.05%   |
| Zen 3            | 45        | 1.77%   |
| Goldmont         | 28        | 1.1%    |
| P6               | 27        | 1.06%   |
| Puma             | 25        | 0.98%   |
| Zen              | 23        | 0.91%   |
| Jaguar           | 23        | 0.91%   |
| Alderlake Hybrid | 21        | 0.83%   |
| Bobcat           | 20        | 0.79%   |
| K8 Hammer        | 14        | 0.55%   |
| K10              | 14        | 0.55%   |
| Nehalem          | 9         | 0.35%   |
| Piledriver       | 8         | 0.32%   |
| Tremont          | 6         | 0.24%   |
| Steamroller      | 5         | 0.2%    |
| NetBurst         | 5         | 0.2%    |
| K8 & K10 hybrid  | 3         | 0.12%   |
| K10 Llano        | 3         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1872      | 57.65%  |
| Nvidia                           | 754       | 23.22%  |
| AMD                              | 608       | 18.72%  |
| Silicon Integrated Systems [SiS] | 8         | 0.25%   |
| VIA Technologies                 | 5         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 141       | 4.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 117       | 3.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 116       | 3.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 115       | 3.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 105       | 3.11%   |
| Intel UHD Graphics 620                                                                   | 101       | 3%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 86        | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 84        | 2.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 81        | 2.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 77        | 2.28%   |
| Intel HD Graphics 620                                                                    | 77        | 2.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 73        | 2.17%   |
| Intel HD Graphics 5500                                                                   | 70        | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 70        | 2.08%   |
| AMD Renoir                                                                               | 68        | 2.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 60        | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 58        | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 53        | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 49        | 1.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 45        | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 45        | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 43        | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 43        | 1.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 1.28%   |
| Intel HD Graphics 530                                                                    | 41        | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 40        | 1.19%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 36        | 1.07%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 34        | 1.01%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 30        | 0.89%   |
| Intel HD Graphics 630                                                                    | 28        | 0.83%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 27        | 0.8%    |
| Intel HD Graphics 500                                                                    | 26        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 25        | 0.74%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 25        | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 24        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 23        | 0.68%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 21        | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 21        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1234      | 48.54%  |
| Intel + Nvidia | 547       | 21.52%  |
| 1 x AMD        | 409       | 16.09%  |
| 1 x Nvidia     | 131       | 5.15%   |
| Intel + AMD    | 86        | 3.38%   |
| AMD + Nvidia   | 73        | 2.87%   |
| 2 x AMD        | 39        | 1.53%   |
| 1 x SiS        | 8         | 0.31%   |
| 1 x VIA        | 5         | 0.2%    |
| 2 x Nvidia     | 4         | 0.16%   |
| 2 x Intel      | 4         | 0.16%   |
| Other          | 2         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2138      | 83.26%  |
| Proprietary | 350       | 13.63%  |
| Unknown     | 80        | 3.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1566      | 60.09%  |
| 0.01-0.5   | 334       | 12.82%  |
| 1.01-2.0   | 321       | 12.32%  |
| 3.01-4.0   | 175       | 6.72%   |
| 0.51-1.0   | 145       | 5.56%   |
| 5.01-6.0   | 38        | 1.46%   |
| 7.01-8.0   | 21        | 0.81%   |
| 2.01-3.0   | 3         | 0.12%   |
| 8.01-16.0  | 3         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 510       | 17.84%  |
| Chimei Innolux          | 451       | 15.77%  |
| LG Display              | 401       | 14.03%  |
| BOE                     | 324       | 11.33%  |
| Samsung Electronics     | 272       | 9.51%   |
| Chi Mei Optoelectronics | 84        | 2.94%   |
| Sharp                   | 80        | 2.8%    |
| Goldstar                | 75        | 2.62%   |
| Dell                    | 64        | 2.24%   |
| Apple                   | 62        | 2.17%   |
| PANDA                   | 56        | 1.96%   |
| Hewlett-Packard         | 56        | 1.96%   |
| BenQ                    | 41        | 1.43%   |
| Lenovo                  | 40        | 1.4%    |
| LG Philips              | 39        | 1.36%   |
| Acer                    | 26        | 0.91%   |
| Philips                 | 24        | 0.84%   |
| Ancor Communications    | 22        | 0.77%   |
| HannStar                | 20        | 0.7%    |
| AOC                     | 20        | 0.7%    |
| Sony                    | 17        | 0.59%   |
| InfoVision              | 16        | 0.56%   |
| CPT                     | 11        | 0.38%   |
| ASUSTek Computer        | 11        | 0.38%   |
| Quanta Display          | 8         | 0.28%   |
| CSO                     | 7         | 0.24%   |
| Analogix                | 7         | 0.24%   |
| ViewSonic               | 6         | 0.21%   |
| Unknown                 | 6         | 0.21%   |
| Valve                   | 5         | 0.17%   |
| Seiko/Epson             | 5         | 0.17%   |
| Panasonic               | 5         | 0.17%   |
| MSI                     | 5         | 0.17%   |
| ANX                     | 5         | 0.17%   |
| Toshiba                 | 3         | 0.1%    |
| TMX                     | 3         | 0.1%    |
| Mi                      | 3         | 0.1%    |
| Hitachi                 | 3         | 0.1%    |
| BOE Technology Group    | 3         | 0.1%    |
| AGO                     | 3         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 64        | 2.21%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 33        | 1.14%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 1.04%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 29        | 1%      |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 25        | 0.87%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.73%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.73%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 19        | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 17        | 0.59%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.55%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.52%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.48%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 14        | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 13        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 13        | 0.45%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.42%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 12        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 12        | 0.42%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 12        | 0.42%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 11        | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 10        | 0.35%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 10        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.35%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 9         | 0.31%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 9         | 0.31%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 9         | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 8         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1071      | 40.32%  |
| 1366x768 (WXGA)    | 900       | 33.89%  |
| 1280x800 (WXGA)    | 152       | 5.72%   |
| 1600x900 (HD+)     | 71        | 2.67%   |
| 3840x2160 (4K)     | 69        | 2.6%    |
| 1440x900 (WXGA+)   | 59        | 2.22%   |
| 2560x1440 (QHD)    | 49        | 1.84%   |
| 1024x600           | 40        | 1.51%   |
| 1920x1200 (WUXGA)  | 30        | 1.13%   |
| 1280x1024 (SXGA)   | 27        | 1.02%   |
| 1680x1050 (WSXGA+) | 24        | 0.9%    |
| 2560x1600          | 22        | 0.83%   |
| 2160x1440          | 18        | 0.68%   |
| 800x1280           | 15        | 0.56%   |
| 3440x1440          | 13        | 0.49%   |
| 2880x1800          | 13        | 0.49%   |
| 2560x1080          | 13        | 0.49%   |
| 3200x1800 (QHD+)   | 7         | 0.26%   |
| 1360x768           | 7         | 0.26%   |
| 1024x768 (XGA)     | 7         | 0.26%   |
| 3840x2400          | 5         | 0.19%   |
| Unknown            | 5         | 0.19%   |
| 2288x1287          | 3         | 0.11%   |
| 1920x540           | 3         | 0.11%   |
| 1600x1200          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 1280x768           | 3         | 0.11%   |
| 3840x1080          | 2         | 0.08%   |
| 3456x2160          | 2         | 0.08%   |
| 3200x2000          | 2         | 0.08%   |
| 3072x1920          | 2         | 0.08%   |
| 1920x1280          | 2         | 0.08%   |
| 5760x1080          | 1         | 0.04%   |
| 3840x1600          | 1         | 0.04%   |
| 3200x1080          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2736x1824          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1410      | 49.39%  |
| 13      | 328       | 11.49%  |
| 14      | 229       | 8.02%   |
| 17      | 162       | 5.67%   |
| 24      | 96        | 3.36%   |
| 27      | 81        | 2.84%   |
| 21      | 74        | 2.59%   |
| 23      | 72        | 2.52%   |
| 12      | 56        | 1.96%   |
| Unknown | 48        | 1.68%   |
| 11      | 45        | 1.58%   |
| 10      | 45        | 1.58%   |
| 16      | 35        | 1.23%   |
| 34      | 27        | 0.95%   |
| 31      | 22        | 0.77%   |
| 19      | 18        | 0.63%   |
| 18      | 14        | 0.49%   |
| 84      | 13        | 0.46%   |
| 20      | 13        | 0.46%   |
| 72      | 7         | 0.25%   |
| 40      | 7         | 0.25%   |
| 25      | 7         | 0.25%   |
| 54      | 6         | 0.21%   |
| 22      | 6         | 0.21%   |
| 7       | 5         | 0.18%   |
| 52      | 3         | 0.11%   |
| 46      | 3         | 0.11%   |
| 26      | 3         | 0.11%   |
| 8       | 3         | 0.11%   |
| 142     | 2         | 0.07%   |
| 38      | 2         | 0.07%   |
| 32      | 2         | 0.07%   |
| 65      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1773      | 62.58%  |
| 201-300        | 343       | 12.11%  |
| 501-600        | 241       | 8.51%   |
| 351-400        | 197       | 6.95%   |
| 401-500        | 114       | 4.02%   |
| Unknown        | 48        | 1.69%   |
| 701-800        | 29        | 1.02%   |
| 601-700        | 29        | 1.02%   |
| 1501-2000      | 20        | 0.71%   |
| 1001-1500      | 16        | 0.56%   |
| 801-900        | 11        | 0.39%   |
| 1-100          | 6         | 0.21%   |
| 101-200        | 3         | 0.11%   |
| More than 2000 | 2         | 0.07%   |
| 901-1000       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2057      | 81.79%  |
| 16/10   | 309       | 12.29%  |
| 3/2     | 31        | 1.23%   |
| Unknown | 28        | 1.11%   |
| 21/9    | 27        | 1.07%   |
| 5/4     | 26        | 1.03%   |
| 4/3     | 15        | 0.6%    |
| 0.62    | 12        | 0.48%   |
| 0.67    | 5         | 0.2%    |
| 1.00    | 2         | 0.08%   |
| 32/9    | 1         | 0.04%   |
| 1.03    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1418      | 49.72%  |
| 81-90          | 395       | 13.85%  |
| 201-250        | 208       | 7.29%   |
| 71-80          | 157       | 5.5%    |
| 121-130        | 114       | 4%      |
| 301-350        | 81        | 2.84%   |
| 61-70          | 53        | 1.86%   |
| 351-500        | 50        | 1.75%   |
| 151-200        | 49        | 1.72%   |
| Unknown        | 48        | 1.68%   |
| 51-60          | 45        | 1.58%   |
| 41-50          | 45        | 1.58%   |
| 131-140        | 35        | 1.23%   |
| More than 1000 | 34        | 1.19%   |
| 251-300        | 31        | 1.09%   |
| 141-150        | 27        | 0.95%   |
| 111-120        | 19        | 0.67%   |
| 501-1000       | 17        | 0.6%    |
| 91-100         | 17        | 0.6%    |
| 1-40           | 9         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1004      | 35.96%  |
| 101-120       | 933       | 33.42%  |
| 51-100        | 544       | 19.48%  |
| 161-240       | 173       | 6.2%    |
| More than 240 | 54        | 1.93%   |
| Unknown       | 48        | 1.72%   |
| 1-50          | 36        | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2051      | 78.95%  |
| 2     | 406       | 15.63%  |
| 0     | 86        | 3.31%   |
| 3     | 51        | 1.96%   |
| 4     | 4         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1419      | 34.55%  |
| Intel                                  | 1195      | 29.1%   |
| Qualcomm Atheros                       | 664       | 16.17%  |
| Broadcom                               | 310       | 7.55%   |
| Broadcom Limited                       | 72        | 1.75%   |
| Marvell Technology Group               | 66        | 1.61%   |
| Ralink                                 | 44        | 1.07%   |
| TP-Link                                | 42        | 1.02%   |
| Ralink Technology                      | 34        | 0.83%   |
| MediaTek                               | 34        | 0.83%   |
| Nvidia                                 | 19        | 0.46%   |
| Samsung Electronics                    | 18        | 0.44%   |
| ASIX Electronics                       | 16        | 0.39%   |
| Xiaomi                                 | 15        | 0.37%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.32%   |
| Hewlett-Packard                        | 12        | 0.29%   |
| JMicron Technology                     | 11        | 0.27%   |
| Ericsson Business Mobile Networks      | 11        | 0.27%   |
| Dell                                   | 11        | 0.27%   |
| Sierra Wireless                        | 10        | 0.24%   |
| Qualcomm Atheros Communications        | 9         | 0.22%   |
| Qualcomm                               | 9         | 0.22%   |
| Lenovo                                 | 9         | 0.22%   |
| DisplayLink                            | 8         | 0.19%   |
| D-Link                                 | 5         | 0.12%   |
| VIA Technologies                       | 4         | 0.1%    |
| LSI                                    | 4         | 0.1%    |
| Huawei Technologies                    | 4         | 0.1%    |
| Attansic Technology                    | 4         | 0.1%    |
| ASUSTek Computer                       | 4         | 0.1%    |
| Toshiba                                | 3         | 0.07%   |
| Edimax Technology                      | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Fibocom                                | 2         | 0.05%   |
| Arduino SA                             | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Sitecom Europe                         | 1         | 0.02%   |
| OPPO Electronics                       | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 819       | 16.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 258       | 5.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 112       | 2.32%   |
| Intel Wi-Fi 6 AX200                                                     | 106       | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 101       | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 98        | 2.03%   |
| Intel Wireless 8265 / 8275                                              | 96        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 94        | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 91        | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 90        | 1.86%   |
| Intel Wi-Fi 6 AX201                                                     | 90        | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 77        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 75        | 1.55%   |
| Intel Wireless 7265                                                     | 70        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.26%   |
| Intel Wireless 7260                                                     | 59        | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 57        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 57        | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 53        | 1.1%    |
| Intel Wireless 3165                                                     | 51        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 46        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 46        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 0.91%   |
| Intel WiFi Link 5100                                                    | 40        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 34        | 0.7%    |
| Intel Wireless 8260                                                     | 33        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 33        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 33        | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 33        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 32        | 0.66%   |
| Intel Wireless 3160                                                     | 32        | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 28        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 27        | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 0.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 27        | 0.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 26        | 0.54%   |
| Intel Centrino Advanced-N 6200                                          | 25        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1151      | 43.65%  |
| Qualcomm Atheros                  | 559       | 21.2%   |
| Realtek Semiconductor             | 473       | 17.94%  |
| Broadcom                          | 206       | 7.81%   |
| Broadcom Limited                  | 50        | 1.9%    |
| Ralink                            | 44        | 1.67%   |
| Ralink Technology                 | 34        | 1.29%   |
| MediaTek                          | 34        | 1.29%   |
| TP-Link                           | 27        | 1.02%   |
| Sierra Wireless                   | 10        | 0.38%   |
| Qualcomm Atheros Communications   | 9         | 0.34%   |
| Dell                              | 6         | 0.23%   |
| D-Link                            | 5         | 0.19%   |
| Qualcomm                          | 4         | 0.15%   |
| Hewlett-Packard                   | 4         | 0.15%   |
| ASUSTek Computer                  | 4         | 0.15%   |
| Ericsson Business Mobile Networks | 3         | 0.11%   |
| Edimax Technology                 | 3         | 0.11%   |
| Fibocom                           | 2         | 0.08%   |
| Accton Technology                 | 2         | 0.08%   |
| Sitecom Europe                    | 1         | 0.04%   |
| NetGear                           | 1         | 0.04%   |
| Linksys                           | 1         | 0.04%   |
| Gemtek                            | 1         | 0.04%   |
| D-Link System                     | 1         | 0.04%   |
| Belkin Components                 | 1         | 0.04%   |
| AirTies Wireless Networks         | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 106       | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 101       | 3.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 98        | 3.69%   |
| Intel Wireless 8265 / 8275                                              | 96        | 3.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 94        | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 91        | 3.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 90        | 3.39%   |
| Intel Wi-Fi 6 AX201                                                     | 90        | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 77        | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 75        | 2.83%   |
| Intel Wireless 7265                                                     | 70        | 2.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 2.3%    |
| Intel Wireless 7260                                                     | 59        | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 57        | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 57        | 2.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 2.04%   |
| Intel Wireless 3165                                                     | 51        | 1.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 46        | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 46        | 1.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 1.66%   |
| Intel WiFi Link 5100                                                    | 40        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 40        | 1.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 34        | 1.28%   |
| Intel Wireless 8260                                                     | 33        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 33        | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 33        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 32        | 1.21%   |
| Intel Wireless 3160                                                     | 32        | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 28        | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 27        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 26        | 0.98%   |
| Intel Centrino Advanced-N 6200                                          | 25        | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 24        | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 24        | 0.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 23        | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 21        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 20        | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 17        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1221      | 57.81%  |
| Intel                                  | 326       | 15.44%  |
| Qualcomm Atheros                       | 178       | 8.43%   |
| Broadcom                               | 141       | 6.68%   |
| Marvell Technology Group               | 66        | 3.13%   |
| Broadcom Limited                       | 24        | 1.14%   |
| Nvidia                                 | 19        | 0.9%    |
| Samsung Electronics                    | 18        | 0.85%   |
| ASIX Electronics                       | 16        | 0.76%   |
| Xiaomi                                 | 15        | 0.71%   |
| TP-Link                                | 15        | 0.71%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.62%   |
| JMicron Technology                     | 11        | 0.52%   |
| Lenovo                                 | 9         | 0.43%   |
| DisplayLink                            | 8         | 0.38%   |
| Qualcomm                               | 5         | 0.24%   |
| VIA Technologies                       | 4         | 0.19%   |
| LSI                                    | 4         | 0.19%   |
| Hewlett-Packard                        | 4         | 0.19%   |
| Attansic Technology                    | 4         | 0.19%   |
| Google                                 | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| Huawei Technologies                    | 1         | 0.05%   |
| Davicom Semiconductor                  | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| ADMtek                                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 819       | 38.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 258       | 12.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 112       | 5.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 53        | 2.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 33        | 1.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 28        | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 27        | 1.26%   |
| Intel 82577LM Gigabit Network Connection                                       | 24        | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 23        | 1.07%   |
| Intel Ethernet Connection I218-LM                                              | 22        | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 20        | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                          | 18        | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                          | 18        | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 16        | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 16        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                           | 16        | 0.75%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 15        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 15        | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 15        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 15        | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 15        | 0.7%    |
| Nvidia MCP79 Ethernet                                                          | 14        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                                          | 14        | 0.65%   |
| Intel 82567LM Gigabit Network Connection                                       | 14        | 0.65%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 14        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 14        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 13        | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 12        | 0.56%   |
| Intel 82579V Gigabit Network Connection                                        | 12        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 11        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 11        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 11        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 11        | 0.51%   |
| Intel Ethernet Connection I219-V                                               | 11        | 0.51%   |
| Intel Ethernet Connection I219-LM                                              | 11        | 0.51%   |
| Intel Ethernet Connection I217-LM                                              | 11        | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 11        | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 10        | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 10        | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 10        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2488      | 54.3%   |
| Ethernet | 2054      | 44.83%  |
| Modem    | 39        | 0.85%   |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2030      | 75.46%  |
| Ethernet | 660       | 24.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1861      | 73.24%  |
| 1     | 617       | 24.28%  |
| 0     | 51        | 2.01%   |
| 3     | 11        | 0.43%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2464      | 96.51%  |
| Yes  | 89        | 3.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 862       | 45.63%  |
| Realtek Semiconductor           | 240       | 12.71%  |
| IMC Networks                    | 140       | 7.41%   |
| Qualcomm Atheros Communications | 133       | 7.04%   |
| Broadcom                        | 87        | 4.61%   |
| Lite-On Technology              | 86        | 4.55%   |
| Foxconn / Hon Hai               | 77        | 4.08%   |
| Apple                           | 57        | 3.02%   |
| Toshiba                         | 35        | 1.85%   |
| Cambridge Silicon Radio         | 34        | 1.8%    |
| Realtek                         | 32        | 1.69%   |
| Dell                            | 25        | 1.32%   |
| Hewlett-Packard                 | 22        | 1.16%   |
| Ralink                          | 17        | 0.9%    |
| ASUSTek Computer                | 13        | 0.69%   |
| Alps Electric                   | 13        | 0.69%   |
| Foxconn International           | 8         | 0.42%   |
| Ralink Technology               | 4         | 0.21%   |
| Askey Computer                  | 2         | 0.11%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 337       | 17.84%  |
| Intel Bluetooth Device                              | 186       | 9.85%   |
| Realtek Bluetooth Radio                             | 161       | 8.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 157       | 8.31%   |
| Intel AX200 Bluetooth                               | 104       | 5.51%   |
| IMC Networks Bluetooth Radio                        | 71        | 3.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 54        | 2.86%   |
| Realtek  Bluetooth 4.2 Adapter                      | 48        | 2.54%   |
| Lite-On Bluetooth Device                            | 45        | 2.38%   |
| IMC Networks Bluetooth Device                       | 38        | 2.01%   |
| Foxconn / Hon Hai Bluetooth Device                  | 36        | 1.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 34        | 1.8%    |
| Apple Bluetooth Host Controller                     | 34        | 1.8%    |
| Realtek Bluetooth Radio                             | 32        | 1.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 30        | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 1.48%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 1.16%   |
| Intel Wireless-AC 3168 Bluetooth                    | 19        | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.01%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.9%    |
| Intel AX210 Bluetooth                               | 17        | 0.9%    |
| IMC Networks Wireless_Device                        | 17        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 0.79%   |
| Apple Bluetooth USB Host Controller                 | 15        | 0.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 0.64%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.58%   |
| Toshiba Integrated Bluetooth HCI                    | 10        | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.53%   |
| Realtek RTL8821A Bluetooth                          | 9         | 0.48%   |
| Broadcom BCM2045 Bluetooth                          | 9         | 0.48%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.42%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.42%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.42%   |
| Foxconn / Hon Hai BCM20702A0                        | 8         | 0.42%   |
| Alps Electric BCM2046 Bluetooth Device              | 8         | 0.42%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2024      | 66.23%  |
| AMD                                  | 515       | 16.85%  |
| Nvidia                               | 347       | 11.35%  |
| C-Media Electronics                  | 22        | 0.72%   |
| Logitech                             | 16        | 0.52%   |
| Silicon Integrated Systems [SiS]     | 13        | 0.43%   |
| GN Netcom                            | 10        | 0.33%   |
| Lenovo                               | 9         | 0.29%   |
| Plantronics                          | 7         | 0.23%   |
| JMTek                                | 7         | 0.23%   |
| Realtek Semiconductor                | 6         | 0.2%    |
| VIA Technologies                     | 5         | 0.16%   |
| Texas Instruments                    | 5         | 0.16%   |
| Kingston Technology                  | 4         | 0.13%   |
| Generalplus Technology               | 4         | 0.13%   |
| Corsair                              | 4         | 0.13%   |
| SteelSeries ApS                      | 3         | 0.1%    |
| Sennheiser Communications            | 3         | 0.1%    |
| Hewlett-Packard                      | 3         | 0.1%    |
| Creative Technology                  | 3         | 0.1%    |
| BEHRINGER International              | 3         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| No brand                             | 2         | 0.07%   |
| Guillemot                            | 2         | 0.07%   |
| CMX Systems                          | 2         | 0.07%   |
| Blue Microphones                     | 2         | 0.07%   |
| ASUSTek Computer                     | 2         | 0.07%   |
| Apple                                | 2         | 0.07%   |
| Alesis                               | 2         | 0.07%   |
| Vestax                               | 1         | 0.03%   |
| Veho                                 | 1         | 0.03%   |
| Unknown (ABC)                        | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| ThrustMaster                         | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Signalpath International             | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| PreSonus Audio Electronics           | 1         | 0.03%   |
| Nordic Semiconductor ASA             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 272       | 7.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 239       | 6.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 148       | 4.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 134       | 3.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 129       | 3.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 126       | 3.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 121       | 3.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 118       | 3.2%    |
| Intel 8 Series HD Audio Controller                                                                | 118       | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 113       | 3.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 101       | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 92        | 2.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 90        | 2.44%   |
| Intel Broadwell-U Audio Controller                                                                | 82        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 82        | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 81        | 2.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 81        | 2.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 77        | 2.09%   |
| AMD FCH Azalia Controller                                                                         | 70        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 68        | 1.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 64        | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 61        | 1.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 58        | 1.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 56        | 1.52%   |
| AMD High Definition Audio Controller                                                              | 47        | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 46        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 46        | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 44        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 42        | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 39        | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 38        | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 35        | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 34        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 33        | 0.89%   |
| Intel CM238 HD Audio Controller                                                                   | 31        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 29        | 0.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 29        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 28        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 26        | 0.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 26        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 473       | 30.73%  |
| SK hynix                     | 329       | 21.38%  |
| Micron Technology            | 191       | 12.41%  |
| Kingston                     | 149       | 9.68%   |
| Unknown                      | 118       | 7.67%   |
| Crucial                      | 74        | 4.81%   |
| Ramaxel Technology           | 52        | 3.38%   |
| Elpida                       | 23        | 1.49%   |
| Unknown (ABCD)               | 22        | 1.43%   |
| A-DATA Technology            | 17        | 1.1%    |
| Nanya Technology             | 15        | 0.97%   |
| Corsair                      | 13        | 0.84%   |
| G.Skill                      | 11        | 0.71%   |
| Silicon Power                | 8         | 0.52%   |
| Transcend                    | 5         | 0.32%   |
| GOODRAM                      | 5         | 0.32%   |
| Unknown                      | 5         | 0.32%   |
| Wilk                         | 3         | 0.19%   |
| Apacer                       | 3         | 0.19%   |
| SHARETRONIC                  | 2         | 0.13%   |
| Patriot                      | 2         | 0.13%   |
| KomputerBay                  | 2         | 0.13%   |
| Avant                        | 2         | 0.13%   |
| Unifosa                      | 1         | 0.06%   |
| Toshiba                      | 1         | 0.06%   |
| Timetec                      | 1         | 0.06%   |
| Team                         | 1         | 0.06%   |
| Qimonda                      | 1         | 0.06%   |
| PNY                          | 1         | 0.06%   |
| Patriot Memory (PDP Systems) | 1         | 0.06%   |
| Netlist                      | 1         | 0.06%   |
| Netac                        | 1         | 0.06%   |
| Micron/Elpida                | 1         | 0.06%   |
| Kllisre                      | 1         | 0.06%   |
| Kembona                      | 1         | 0.06%   |
| CSX                          | 1         | 0.06%   |
| Atermiter                    | 1         | 0.06%   |
| ASint Technology             | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 28        | 1.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 1.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 21        | 1.31%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 1.12%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 18        | 1.12%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.99%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.99%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 15        | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 12        | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.75%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 12        | 0.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 11        | 0.68%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.62%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 10        | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.62%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 9         | 0.56%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 9         | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 9         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.56%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 8         | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.5%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.5%    |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 8         | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 631       | 48.43%  |
| DDR3    | 418       | 32.08%  |
| DDR2    | 77        | 5.91%   |
| LPDDR4  | 61        | 4.68%   |
| LPDDR3  | 47        | 3.61%   |
| SDRAM   | 28        | 2.15%   |
| DDR5    | 14        | 1.07%   |
| Unknown | 9         | 0.69%   |
| DDR     | 7         | 0.54%   |
| DRAM    | 6         | 0.46%   |
| LPDDR5  | 5         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1174      | 89.21%  |
| Row Of Chips | 126       | 9.57%   |
| DIMM         | 8         | 0.61%   |
| Chip         | 8         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 547       | 38.66%  |
| 4096  | 411       | 29.05%  |
| 16384 | 205       | 14.49%  |
| 2048  | 166       | 11.73%  |
| 1024  | 52        | 3.67%   |
| 32768 | 27        | 1.91%   |
| 512   | 4         | 0.28%   |
| 256   | 2         | 0.14%   |
| 3072  | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 290       | 20.66%  |
| 1600    | 280       | 19.94%  |
| 3200    | 256       | 18.23%  |
| 2400    | 99        | 7.05%   |
| 1334    | 69        | 4.91%   |
| 2133    | 67        | 4.77%   |
| 667     | 54        | 3.85%   |
| 1333    | 52        | 3.7%    |
| Unknown | 38        | 2.71%   |
| 8400    | 28        | 1.99%   |
| 4267    | 24        | 1.71%   |
| 1067    | 24        | 1.71%   |
| 3266    | 15        | 1.07%   |
| 1867    | 15        | 1.07%   |
| 4800    | 14        | 1%      |
| 800     | 14        | 1%      |
| 533     | 12        | 0.85%   |
| 4199    | 10        | 0.71%   |
| 2048    | 9         | 0.64%   |
| 6400    | 6         | 0.43%   |
| 4266    | 5         | 0.36%   |
| 1066    | 5         | 0.36%   |
| 975     | 5         | 0.36%   |
| 2933    | 2         | 0.14%   |
| 1639    | 2         | 0.14%   |
| 1200    | 2         | 0.14%   |
| 3733    | 1         | 0.07%   |
| 3000    | 1         | 0.07%   |
| 1866    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |
| 333     | 1         | 0.07%   |
| 266     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 11        | 50%     |
| Seiko Epson        | 4         | 18.18%  |
| Canon              | 4         | 18.18%  |
| Brother Industries | 3         | 13.64%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series        | 3         | 13.64%  |
| Seiko Epson XP-230 Series        | 1         | 4.55%   |
| Seiko Epson Printer              | 1         | 4.55%   |
| Seiko Epson L555 Series          | 1         | 4.55%   |
| Seiko Epson ET-2700 Series       | 1         | 4.55%   |
| HP PSC 1500 series               | 1         | 4.55%   |
| HP Printing Support              | 1         | 4.55%   |
| HP LaserJet Professional P 1102w | 1         | 4.55%   |
| HP LaserJet Pro M404-M405        | 1         | 4.55%   |
| HP LaserJet 1320                 | 1         | 4.55%   |
| HP LaserJet 1020                 | 1         | 4.55%   |
| HP LaserJet 1018                 | 1         | 4.55%   |
| HP LaserJet 1000                 | 1         | 4.55%   |
| HP DeskJet F300 series           | 1         | 4.55%   |
| HP DeskJet F2492 All-in-One      | 1         | 4.55%   |
| HP Deskjet 2050 J510             | 1         | 4.55%   |
| Canon TS3100 series              | 1         | 4.55%   |
| Brother MFC-J5330DW              | 1         | 4.55%   |
| Brother HL-2030 Laser Printer    | 1         | 4.55%   |
| Brother HL-1210W series          | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 4300c              | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 210       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 578       | 26.4%   |
| IMC Networks                           | 272       | 12.43%  |
| Acer                                   | 235       | 10.74%  |
| Realtek Semiconductor                  | 146       | 6.67%   |
| Microdia                               | 141       | 6.44%   |
| Suyin                                  | 115       | 5.25%   |
| Quanta                                 | 108       | 4.93%   |
| Sunplus Innovation Technology          | 90        | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 90        | 4.11%   |
| Syntek                                 | 66        | 3.02%   |
| Alcor Micro                            | 41        | 1.87%   |
| Lite-On Technology                     | 35        | 1.6%    |
| Apple                                  | 35        | 1.6%    |
| Luxvisions Innotech Limited            | 31        | 1.42%   |
| Ricoh                                  | 30        | 1.37%   |
| Silicon Motion                         | 19        | 0.87%   |
| Logitech                               | 19        | 0.87%   |
| Samsung Electronics                    | 11        | 0.5%    |
| Sonix Technology                       | 9         | 0.41%   |
| Importek                               | 9         | 0.41%   |
| Z-Star Microelectronics                | 8         | 0.37%   |
| Lenovo                                 | 8         | 0.37%   |
| ALi                                    | 8         | 0.37%   |
| icSpring                               | 7         | 0.32%   |
| GEMBIRD                                | 7         | 0.32%   |
| Sunplus Technology                     | 6         | 0.27%   |
| Primax Electronics                     | 6         | 0.27%   |
| Intel                                  | 6         | 0.27%   |
| KYE Systems (Mouse Systems)            | 5         | 0.23%   |
| OmniVision Technologies                | 4         | 0.18%   |
| Genesys Logic                          | 4         | 0.18%   |
| DigiTech                               | 4         | 0.18%   |
| ARC International                      | 4         | 0.18%   |
| Trust                                  | 3         | 0.14%   |
| Novatek Microelectronics               | 2         | 0.09%   |
| Microsoft                              | 2         | 0.09%   |
| Creative Technology                    | 2         | 0.09%   |
| 2M UVC CAMERA                          | 2         | 0.09%   |
| Xiaomi                                 | 1         | 0.05%   |
| WaveRider Communications               | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 72        | 3.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 66        | 3.01%   |
| Chicony HD Webcam                                       | 65        | 2.96%   |
| Chicony integrated camera                               | 58        | 2.64%   |
| Microdia Integrated_Webcam_HD                           | 54        | 2.46%   |
| Acer Integrated Camera                                  | 52        | 2.37%   |
| Acer HD Webcam                                          | 52        | 2.37%   |
| IMC Networks Integrated Camera                          | 40        | 1.82%   |
| Chicony USB2.0 VGA UVC WebCam                           | 40        | 1.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 31        | 1.41%   |
| Realtek Integrated_Webcam_HD                            | 30        | 1.37%   |
| Quanta HP TrueVision HD Camera                          | 29        | 1.32%   |
| Sunplus HD WebCam                                       | 26        | 1.18%   |
| Realtek USB Camera                                      | 26        | 1.18%   |
| Chicony EasyCamera                                      | 23        | 1.05%   |
| Chicony USB 2.0 Camera                                  | 22        | 1%      |
| Syntek Integrated Camera                                | 21        | 0.96%   |
| Acer Lenovo EasyCamera                                  | 20        | 0.91%   |
| Acer HD Camera                                          | 19        | 0.87%   |
| Acer EasyCamera                                         | 19        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                            | 18        | 0.82%   |
| Chicony HP Truevision HD                                | 18        | 0.82%   |
| Syntek Lenovo EasyCamera                                | 17        | 0.77%   |
| Syntek EasyCamera                                       | 17        | 0.77%   |
| Lite-On Integrated Camera                               | 17        | 0.77%   |
| Chicony VGA WebCam                                      | 17        | 0.77%   |
| Apple Built-in iSight                                   | 17        | 0.77%   |
| Realtek Lenovo EasyCamera                               | 16        | 0.73%   |
| Chicony TOSHIBA Web Camera - HD                         | 16        | 0.73%   |
| Chicony HP HD Camera                                    | 16        | 0.73%   |
| Quanta HP HD Camera                                     | 15        | 0.68%   |
| Microdia Integrated Webcam                              | 15        | 0.68%   |
| Chicony USB2.0 Camera                                   | 15        | 0.68%   |
| Chicony Integrated Camera (1280x720@30)                 | 15        | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.68%   |
| Alcor Micro Asus Integrated Webcam                      | 15        | 0.68%   |
| Microdia Webcam Vitade AF                               | 14        | 0.64%   |
| IMC Networks ov9734_azurewave_camera                    | 14        | 0.64%   |
| Chicony HP TrueVision HD Camera                         | 14        | 0.64%   |
| Acer BisonCam, NB Pro                                   | 14        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 95        | 27.7%   |
| Validity Sensors           | 83        | 24.2%   |
| Shenzhen Goodix Technology | 56        | 16.33%  |
| Elan Microelectronics      | 36        | 10.5%   |
| AuthenTec                  | 35        | 10.2%   |
| Upek                       | 23        | 6.71%   |
| LighTuning Technology      | 9         | 2.62%   |
| STMicroelectronics         | 6         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 44        | 12.83%  |
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 11.95%  |
| Elan ELAN:Fingerprint                                                      | 33        | 9.62%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 7.29%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 5.54%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 5.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 4.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 3.21%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 3.21%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.75%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.75%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.75%   |
| AuthenTec AES1600                                                          | 6         | 1.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.46%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.46%   |
| AuthenTec AES2810                                                          | 5         | 1.46%   |
| Validity Sensors VFS491                                                    | 4         | 1.17%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.17%   |
| Synaptics  WBDI                                                            | 4         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.17%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.87%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.87%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.87%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.87%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.58%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.58%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.58%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 53        | 34.64%  |
| Broadcom              | 50        | 32.68%  |
| O2 Micro              | 23        | 15.03%  |
| Lenovo                | 8         | 5.23%   |
| Upek                  | 4         | 2.61%   |
| C3PO                  | 4         | 2.61%   |
| Realtek Semiconductor | 3         | 1.96%   |
| Cherry                | 3         | 1.96%   |
| Gemalto (was Gemplus) | 2         | 1.31%   |
| In Focus Systems      | 1         | 0.65%   |
| Chicony Electronics   | 1         | 0.65%   |
| Advanced Card Systems | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 53        | 34.64%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 14.38%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 11.76%  |
| Broadcom 5880                                                                | 14        | 9.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.88%   |
| Broadcom 58200                                                               | 9         | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 5.23%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.61%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.96%   |
| Cherry SmartTerminal XX1X                                                    | 3         | 1.96%   |
| C3PO LTC31v2                                                                 | 3         | 1.96%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.31%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.65%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.65%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.65%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.65%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1685      | 64.66%  |
| 1     | 709       | 27.21%  |
| 2     | 179       | 6.87%   |
| 3     | 22        | 0.84%   |
| 4     | 7         | 0.27%   |
| 5     | 3         | 0.12%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 335       | 29.54%  |
| Graphics card            | 282       | 24.87%  |
| Net/wireless             | 146       | 12.87%  |
| Chipcard                 | 134       | 11.82%  |
| Multimedia controller    | 67        | 5.91%   |
| Camera                   | 39        | 3.44%   |
| Bluetooth                | 26        | 2.29%   |
| Storage                  | 22        | 1.94%   |
| Communication controller | 22        | 1.94%   |
| Card reader              | 16        | 1.41%   |
| Sound                    | 11        | 0.97%   |
| Net/ethernet             | 11        | 0.97%   |
| Flash memory             | 10        | 0.88%   |
| Modem                    | 8         | 0.71%   |
| Dvb card                 | 3         | 0.26%   |
| Network                  | 2         | 0.18%   |


Linux in Portugal - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

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

Total: 1514

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| LNV           | L40-70                      | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| HP            | 250 G3                      | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | Notebook                    | [02ceb78a4f](https://linux-hardware.org/?probe=02ceb78a4f) | Aug 07, 2023 |
| Medion        | M14L-256                    | [7d0a8921dc](https://linux-hardware.org/?probe=7d0a8921dc) | Aug 07, 2023 |
| Apple         | MacBook7,1                  | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Teclast       | F7S                         | [a844443394](https://linux-hardware.org/?probe=a844443394) | Aug 06, 2023 |
| Unknown       | Unknown                     | [9431f6f4e8](https://linux-hardware.org/?probe=9431f6f4e8) | Aug 06, 2023 |
| Teclast       | F7S                         | [71ab18cda5](https://linux-hardware.org/?probe=71ab18cda5) | Aug 05, 2023 |
| HUAWEI        | RLEF-XX                     | [5b0c2b27e7](https://linux-hardware.org/?probe=5b0c2b27e7) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [2825bbd67b](https://linux-hardware.org/?probe=2825bbd67b) | Aug 04, 2023 |
| ASUSTek       | UX430UNR                    | [89c8324528](https://linux-hardware.org/?probe=89c8324528) | Aug 01, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| Lenovo        | G50-45 80E3                 | [002504b8be](https://linux-hardware.org/?probe=002504b8be) | Jul 29, 2023 |
| HP            | Laptop 15-fc0xxx            | [30dabbbc28](https://linux-hardware.org/?probe=30dabbbc28) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| MSI           | Summit E16Flip A12UCT       | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7d2f78f0d3](https://linux-hardware.org/?probe=7d2f78f0d3) | Jul 15, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [20e49aa241](https://linux-hardware.org/?probe=20e49aa241) | Jul 14, 2023 |
| HP            | Pavilion dv3                | [94eeea2364](https://linux-hardware.org/?probe=94eeea2364) | Jul 12, 2023 |
| HP            | EliteBook 645 14 inch G9... | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Dell          | Latitude E5500              | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [50f23f3476](https://linux-hardware.org/?probe=50f23f3476) | Jul 09, 2023 |
| Dell          | XPS 13 9350                 | [9fc07d1102](https://linux-hardware.org/?probe=9fc07d1102) | Jul 08, 2023 |
| HP            | 350 G1                      | [d965c2785d](https://linux-hardware.org/?probe=d965c2785d) | Jul 04, 2023 |
| HP            | 350 G1                      | [bb742c9ffb](https://linux-hardware.org/?probe=bb742c9ffb) | Jul 04, 2023 |
| Acer          | Aspire 5737Z                | [842aa57faf](https://linux-hardware.org/?probe=842aa57faf) | Jun 30, 2023 |
| ASUSTek       | K56CB                       | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| MSI           | PS63 Modern 8SC             | [dcbb8108cf](https://linux-hardware.org/?probe=dcbb8108cf) | Jun 29, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Toshiba       | Satellite X200              | [4a3e7008cf](https://linux-hardware.org/?probe=4a3e7008cf) | Jun 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c05a780b64](https://linux-hardware.org/?probe=c05a780b64) | Jun 27, 2023 |
| Gigabyte      | AERO 15 KD                  | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | XPS 9315                    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| HP            | EliteBook 840 G5            | [4ad837baa7](https://linux-hardware.org/?probe=4ad837baa7) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4b866ca19f](https://linux-hardware.org/?probe=4b866ca19f) | Jun 22, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [22c2768f76](https://linux-hardware.org/?probe=22c2768f76) | Jun 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2f19a23a54](https://linux-hardware.org/?probe=2f19a23a54) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | [3d8b5e9564](https://linux-hardware.org/?probe=3d8b5e9564) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | [fb8da18b42](https://linux-hardware.org/?probe=fb8da18b42) | Jun 17, 2023 |
| Dell          | Latitude E5400              | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| Toshiba       | Satellite X200              | [d57a63387d](https://linux-hardware.org/?probe=d57a63387d) | Jun 15, 2023 |
| Toshiba       | Satellite L650              | [d92c0dea02](https://linux-hardware.org/?probe=d92c0dea02) | Jun 14, 2023 |
| Sony          | SVF1521J7EW                 | [2d04d992c2](https://linux-hardware.org/?probe=2d04d992c2) | Jun 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Chuwi         | GemiBook Pro                | [83adb0e53a](https://linux-hardware.org/?probe=83adb0e53a) | Jun 07, 2023 |
| Lenovo        | ThinkPad T440p              | [d46387134e](https://linux-hardware.org/?probe=d46387134e) | Jun 07, 2023 |
| Chuwi         | GemiBook Pro                | [1378fdec29](https://linux-hardware.org/?probe=1378fdec29) | Jun 07, 2023 |
| Lenovo        | ThinkPad T440p              | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| ASUSTek       | N56VB                       | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [6964a1da79](https://linux-hardware.org/?probe=6964a1da79) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Dell          | Latitude 5491               | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [109dbbfff0](https://linux-hardware.org/?probe=109dbbfff0) | Jun 02, 2023 |
| HP            | Unknown                     | [626075d6f2](https://linux-hardware.org/?probe=626075d6f2) | Jun 02, 2023 |
| HP            | Unknown                     | [2289bb8d24](https://linux-hardware.org/?probe=2289bb8d24) | Jun 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [302ae0e2dc](https://linux-hardware.org/?probe=302ae0e2dc) | Jun 02, 2023 |
| Chuwi         | GemiBook Pro                | [f17ebfac4b](https://linux-hardware.org/?probe=f17ebfac4b) | May 31, 2023 |
| HP            | Unknown                     | [3eb658702b](https://linux-hardware.org/?probe=3eb658702b) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [93ac1fb021](https://linux-hardware.org/?probe=93ac1fb021) | May 31, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [5881fb6ae2](https://linux-hardware.org/?probe=5881fb6ae2) | May 30, 2023 |
| HP            | Unknown                     | [2007104aeb](https://linux-hardware.org/?probe=2007104aeb) | May 30, 2023 |
| Lenovo        | ThinkPad E490 20N8000RPG    | [73b8bfb3a5](https://linux-hardware.org/?probe=73b8bfb3a5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Chuwi         | GemiBook Pro                | [5684d2005d](https://linux-hardware.org/?probe=5684d2005d) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| HP            | 15                          | [f5373f2397](https://linux-hardware.org/?probe=f5373f2397) | May 27, 2023 |
| HP            | 15                          | [f30c3b3a95](https://linux-hardware.org/?probe=f30c3b3a95) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| Sony          | VGN-FZ31Z                   | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Chuwi         | GemiBook Pro                | [ac87b1945b](https://linux-hardware.org/?probe=ac87b1945b) | May 26, 2023 |
| ASUSTek       | GL702ZC                     | [c60d7fabbb](https://linux-hardware.org/?probe=c60d7fabbb) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [b5a283de1d](https://linux-hardware.org/?probe=b5a283de1d) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [0a65452634](https://linux-hardware.org/?probe=0a65452634) | May 24, 2023 |
| ASUSTek       | GL702ZC                     | [9764417bf8](https://linux-hardware.org/?probe=9764417bf8) | May 24, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [a11fdd0361](https://linux-hardware.org/?probe=a11fdd0361) | May 23, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Acer          | Nitro AN515-52              | [f250413f11](https://linux-hardware.org/?probe=f250413f11) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| HP            | Unknown                     | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| HP            | Pavilion Notebook           | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| Acer          | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| HP            | Pavilion Notebook           | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| HUAWEI        | KLVL-WXXW                   | [72b5dfc390](https://linux-hardware.org/?probe=72b5dfc390) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [d7e4640b82](https://linux-hardware.org/?probe=d7e4640b82) | May 15, 2023 |
| ASUSTek       | X541UJ                      | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| ASUSTek       | N56VB                       | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Valve         | Jupiter                     | [9a9b88a86c](https://linux-hardware.org/?probe=9a9b88a86c) | May 14, 2023 |
| Apple         | MacBookPro11,2              | [a2199ee2c6](https://linux-hardware.org/?probe=a2199ee2c6) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| HP            | G62                         | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Dell          | Latitude 5420               | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| Sony          | VGN-FZ31Z                   | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| Lenovo        | G50-70 20351                | [70c3231200](https://linux-hardware.org/?probe=70c3231200) | May 07, 2023 |
| Notebook      | N141CU                      | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| Acer          | Aspire E5-523G              | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [678b4ca4ed](https://linux-hardware.org/?probe=678b4ca4ed) | May 06, 2023 |
| Valve         | Jupiter                     | [04f1f6146c](https://linux-hardware.org/?probe=04f1f6146c) | May 04, 2023 |
| Dell          | Precision 5540              | [3139d97ce0](https://linux-hardware.org/?probe=3139d97ce0) | May 04, 2023 |
| Toshiba       | PORTEGE Z830                | [a8cc4a63c2](https://linux-hardware.org/?probe=a8cc4a63c2) | May 03, 2023 |
| HP            | Unknown                     | [4d0dc62d87](https://linux-hardware.org/?probe=4d0dc62d87) | May 03, 2023 |
| HP            | Unknown                     | [95bbd82535](https://linux-hardware.org/?probe=95bbd82535) | May 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3e8baa565](https://linux-hardware.org/?probe=f3e8baa565) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | [168396ff77](https://linux-hardware.org/?probe=168396ff77) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | [b7ca4beb49](https://linux-hardware.org/?probe=b7ca4beb49) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| ASUSTek       | X542URR                     | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Dell          | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 850 G5            | [ba9bbe1e70](https://linux-hardware.org/?probe=ba9bbe1e70) | Apr 21, 2023 |
| Dell          | Precision 5540              | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [b4c6c1198f](https://linux-hardware.org/?probe=b4c6c1198f) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [b054f2bcd1](https://linux-hardware.org/?probe=b054f2bcd1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [69f8d7dfdf](https://linux-hardware.org/?probe=69f8d7dfdf) | Apr 11, 2023 |
| Chuwi         | GemiBook Pro                | [e0f6223c25](https://linux-hardware.org/?probe=e0f6223c25) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | [cb009d5401](https://linux-hardware.org/?probe=cb009d5401) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | [617f2a18bb](https://linux-hardware.org/?probe=617f2a18bb) | Apr 09, 2023 |
| Chuwi         | GemiBook Pro                | [5ff7c0183d](https://linux-hardware.org/?probe=5ff7c0183d) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E751               | [0bdc444de8](https://linux-hardware.org/?probe=0bdc444de8) | Apr 05, 2023 |
| Dell          | Latitude 5430               | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f13da06079](https://linux-hardware.org/?probe=f13da06079) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [48370f2817](https://linux-hardware.org/?probe=48370f2817) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| ASUSTek       | X202EV                      | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | GF65 Thin 9SD               | [ea69b96e55](https://linux-hardware.org/?probe=ea69b96e55) | Mar 09, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude E5570              | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| MSI           | GF72 8RD                    | [54eb266d2a](https://linux-hardware.org/?probe=54eb266d2a) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [26b308e28a](https://linux-hardware.org/?probe=26b308e28a) | Mar 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [73c765dbe2](https://linux-hardware.org/?probe=73c765dbe2) | Mar 01, 2023 |
| Lenovo        | ThinkPad T480 20L6SEH700    | [4a187e016b](https://linux-hardware.org/?probe=4a187e016b) | Feb 27, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7b59cbd067](https://linux-hardware.org/?probe=7b59cbd067) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d99e163be6](https://linux-hardware.org/?probe=d99e163be6) | Feb 24, 2023 |
| HP            | mt40                        | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| MSI           | GF72 8RD                    | [cf6dad63da](https://linux-hardware.org/?probe=cf6dad63da) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| HUAWEI        | BOHB-WAX9                   | [387aa81d4c](https://linux-hardware.org/?probe=387aa81d4c) | Feb 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [ebaa8145e1](https://linux-hardware.org/?probe=ebaa8145e1) | Feb 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [bb1c4209c7](https://linux-hardware.org/?probe=bb1c4209c7) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [ef69c22820](https://linux-hardware.org/?probe=ef69c22820) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [4e6c625797](https://linux-hardware.org/?probe=4e6c625797) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Toshiba       | Satellite L500              | [da3617cc40](https://linux-hardware.org/?probe=da3617cc40) | Feb 14, 2023 |
| Gigabyte      | P65                         | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | P65                         | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [b6b590fcdf](https://linux-hardware.org/?probe=b6b590fcdf) | Feb 11, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| HP            | ProBook 640 G1              | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Acer          | Aspire S7-391               | [3777a7d1e9](https://linux-hardware.org/?probe=3777a7d1e9) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Acer          | Aspire V3-572G              | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Dell          | Precision 7550              | [9608ff008d](https://linux-hardware.org/?probe=9608ff008d) | Feb 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| INSYS         | GW1-W149                    | [5a4337006d](https://linux-hardware.org/?probe=5a4337006d) | Jan 28, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| HP            | ProBook 640 G2              | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [a9567dc72b](https://linux-hardware.org/?probe=a9567dc72b) | Jan 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| ASUSTek       | UX360CA                     | [98fa78d117](https://linux-hardware.org/?probe=98fa78d117) | Jan 22, 2023 |
| Acer          | Aspire E1-522               | [ad5202642a](https://linux-hardware.org/?probe=ad5202642a) | Jan 22, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| Apple         | MacBookPro6,2               | [95074766b9](https://linux-hardware.org/?probe=95074766b9) | Jan 18, 2023 |
| Acer          | Predator PH315-51           | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| Acer          | Aspire V5-122               | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Aspire 5742G                | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| Unknown       | Unknown                     | [ce97b4a08f](https://linux-hardware.org/?probe=ce97b4a08f) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| HP            | Pavilion dv6                | [9f0fb0adf5](https://linux-hardware.org/?probe=9f0fb0adf5) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [113a2a45b2](https://linux-hardware.org/?probe=113a2a45b2) | Jan 01, 2023 |
| Toshiba       | Satellite L775-12V          | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Dell          | XPS 13 9370                 | [982f470134](https://linux-hardware.org/?probe=982f470134) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Dell          | Inspiron N5050              | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Thomson       | PT-NEO14A.2WH32             | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Sony          | VGN-FZ31Z                   | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [8008043900](https://linux-hardware.org/?probe=8008043900) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Acer          | Aspire A315-55G             | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| HP            | Pavilion dv6                | [8a940a493b](https://linux-hardware.org/?probe=8a940a493b) | Dec 03, 2022 |
| MSI           | GF72 8RD                    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| Acer          | Nitro AN515-58              | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| MSI           | GF72 8RD                    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| ASUSTek       | F7SR                        | [ecdba533ea](https://linux-hardware.org/?probe=ecdba533ea) | Nov 25, 2022 |
| ASUSTek       | F7SR                        | [8102d8b361](https://linux-hardware.org/?probe=8102d8b361) | Nov 25, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [2de63dfd54](https://linux-hardware.org/?probe=2de63dfd54) | Nov 23, 2022 |
| HUAWEI        | BOD-WXX9                    | [814f45a510](https://linux-hardware.org/?probe=814f45a510) | Nov 23, 2022 |
| Apple         | MacBookAir5,1               | [2ded48104d](https://linux-hardware.org/?probe=2ded48104d) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [02c6e2e360](https://linux-hardware.org/?probe=02c6e2e360) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [d4c27f1388](https://linux-hardware.org/?probe=d4c27f1388) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [0401b9e939](https://linux-hardware.org/?probe=0401b9e939) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| ASUSTek       | G752VS                      | [364d6d09ab](https://linux-hardware.org/?probe=364d6d09ab) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c54708e797](https://linux-hardware.org/?probe=c54708e797) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [e54df5cb0d](https://linux-hardware.org/?probe=e54df5cb0d) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Packard Be... | EasyNote LV11HC             | [244d508935](https://linux-hardware.org/?probe=244d508935) | Nov 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [c1f18206f4](https://linux-hardware.org/?probe=c1f18206f4) | Nov 11, 2022 |
| eMachines     | G525                        | [38b8684942](https://linux-hardware.org/?probe=38b8684942) | Nov 10, 2022 |
| ASUSTek       | N61Vg                       | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Dell          | Latitude E6510              | [befb811cfe](https://linux-hardware.org/?probe=befb811cfe) | Nov 05, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| ASUSTek       | N61Vg                       | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| Dell          | Latitude E6510              | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Acer          | Aspire ES1-131              | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| Dell          | Latitude 7320               | [f249267def](https://linux-hardware.org/?probe=f249267def) | Oct 26, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [8ebb941ac6](https://linux-hardware.org/?probe=8ebb941ac6) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Toshiba       | NB300                       | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| Apple         | MacBookPro10,1              | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| ASUSTek       | X541UV                      | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| HP            | EliteBook 840 G2            | [d83c027361](https://linux-hardware.org/?probe=d83c027361) | Oct 12, 2022 |
| ASUSTek       | N53SV                       | [2460d79ba8](https://linux-hardware.org/?probe=2460d79ba8) | Oct 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [184ecb5e76](https://linux-hardware.org/?probe=184ecb5e76) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [a3d3100ffa](https://linux-hardware.org/?probe=a3d3100ffa) | Oct 05, 2022 |
| Acer          | Aspire ES1-520              | [b50cfdccab](https://linux-hardware.org/?probe=b50cfdccab) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| HP            | ENVY 15                     | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d9a196cd8e](https://linux-hardware.org/?probe=d9a196cd8e) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| GIADA         | ChiefRiver Platform         | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [2f1fe986d8](https://linux-hardware.org/?probe=2f1fe986d8) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Toshiba       | Satellite P845T             | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [dd6d053ae2](https://linux-hardware.org/?probe=dd6d053ae2) | Sep 17, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| ASUSTek       | X555LJ                      | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| HP            | Pavilion g6                 | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| Sony          | VGN-FZ31Z                   | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a74d79fc0b](https://linux-hardware.org/?probe=a74d79fc0b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| Toshiba       | Satellite A300              | [f90886ae85](https://linux-hardware.org/?probe=f90886ae85) | Aug 30, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [73db272ecb](https://linux-hardware.org/?probe=73db272ecb) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| HP            | Laptop 15s-fq2xxx           | [8ffebf0c43](https://linux-hardware.org/?probe=8ffebf0c43) | Aug 26, 2022 |
| ASUSTek       | N61Vg                       | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| MSI           | Modern 14 A10RB             | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| Apple         | MacBookAir6,1               | [154468415c](https://linux-hardware.org/?probe=154468415c) | Aug 05, 2022 |
| Apple         | MacBookAir6,1               | [6f355de994](https://linux-hardware.org/?probe=6f355de994) | Aug 04, 2022 |
| Toshiba       | Satellite U840              | [5ebf9417bf](https://linux-hardware.org/?probe=5ebf9417bf) | Aug 04, 2022 |
| MSI           | Modern 14 A10RB             | [abf1fcf08b](https://linux-hardware.org/?probe=abf1fcf08b) | Aug 02, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [c6ce2d4317](https://linux-hardware.org/?probe=c6ce2d4317) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [eca5fa0c39](https://linux-hardware.org/?probe=eca5fa0c39) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Toshiba       | Satellite U840              | [c3f00f5b90](https://linux-hardware.org/?probe=c3f00f5b90) | Jul 29, 2022 |
| ASUSTek       | N53SN                       | [2e35ef4a8a](https://linux-hardware.org/?probe=2e35ef4a8a) | Jul 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e95cafce19](https://linux-hardware.org/?probe=e95cafce19) | Jul 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [ae16c8863a](https://linux-hardware.org/?probe=ae16c8863a) | Jul 25, 2022 |
| ASUSTek       | X540LJ                      | [264bb2f2a1](https://linux-hardware.org/?probe=264bb2f2a1) | Jul 23, 2022 |
| ASUSTek       | X540LJ                      | [fc5c252e6e](https://linux-hardware.org/?probe=fc5c252e6e) | Jul 23, 2022 |
| Acer          | Aspire A515-45              | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| Dell          | XPS 15 7590                 | [528f562110](https://linux-hardware.org/?probe=528f562110) | Jul 18, 2022 |
| Packard Be... | EasyNote LV11HC             | [c0693d5f9a](https://linux-hardware.org/?probe=c0693d5f9a) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Sony          | VPCEB3L1E                   | [310a2ada05](https://linux-hardware.org/?probe=310a2ada05) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [247411abde](https://linux-hardware.org/?probe=247411abde) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [9af59fca26](https://linux-hardware.org/?probe=9af59fca26) | Jul 08, 2022 |
| ASUSTek       | X540LJ                      | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Sony          | VGN-FZ31Z                   | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Acer          | Aspire A515-54G             | [c0975c6877](https://linux-hardware.org/?probe=c0975c6877) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire A515-54G             | [92d695d6be](https://linux-hardware.org/?probe=92d695d6be) | Jul 02, 2022 |
| HP            | EliteBook 840 G1            | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [17cb04c5f5](https://linux-hardware.org/?probe=17cb04c5f5) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Sony          | VPCEH2J1E                   | [7dde3ae196](https://linux-hardware.org/?probe=7dde3ae196) | Jun 23, 2022 |
| HP            | EliteBook 820 G1            | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| Toshiba       | NB305                       | [1280ac15ba](https://linux-hardware.org/?probe=1280ac15ba) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | [d9b85c0e15](https://linux-hardware.org/?probe=d9b85c0e15) | Jun 16, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [4b1946451e](https://linux-hardware.org/?probe=4b1946451e) | Jun 15, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| Sony          | VGN-FZ31Z                   | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Dell          | Latitude E6400              | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | Compaq nx7300 (RU464EA#A... | [a44ec57985](https://linux-hardware.org/?probe=a44ec57985) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [029a55ffb4](https://linux-hardware.org/?probe=029a55ffb4) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| Lenovo        | ThinkPad T530 2394C98       | [b5aebb2490](https://linux-hardware.org/?probe=b5aebb2490) | May 30, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [f47dbc0616](https://linux-hardware.org/?probe=f47dbc0616) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Acer          | Swift SF314-54              | [eb522816a1](https://linux-hardware.org/?probe=eb522816a1) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [533beb13eb](https://linux-hardware.org/?probe=533beb13eb) | May 26, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| HP            | EliteBook 8540w             | [2f973c22ec](https://linux-hardware.org/?probe=2f973c22ec) | May 19, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| Apple         | MacBookAir7,2               | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Notebook      | NB50TJ1_TK1                 | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Lenovo        | ThinkPad X61 7673AQ5        | [42a17c86f4](https://linux-hardware.org/?probe=42a17c86f4) | May 13, 2022 |
| MSI           | GT72VR 6RD                  | [c4cf6c9cd0](https://linux-hardware.org/?probe=c4cf6c9cd0) | May 12, 2022 |
| MSI           | Modern 15 A10RAS            | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion g6                 | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [d24187e845](https://linux-hardware.org/?probe=d24187e845) | May 05, 2022 |
| HP            | ProBook 640 G2              | [50ccff3e1a](https://linux-hardware.org/?probe=50ccff3e1a) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| HP            | EliteBook 840 G5            | [47aaf6f556](https://linux-hardware.org/?probe=47aaf6f556) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| Sony          | VGN-FZ31Z                   | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| Lenovo        | G50-45 80E3                 | [910267bbd5](https://linux-hardware.org/?probe=910267bbd5) | Apr 28, 2022 |
| Lenovo        | G50-45 80E3                 | [22dd67107b](https://linux-hardware.org/?probe=22dd67107b) | Apr 28, 2022 |
| HP            | Laptop 15s-fq2xxx           | [91c7a6b5a0](https://linux-hardware.org/?probe=91c7a6b5a0) | Apr 27, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [710ddc650e](https://linux-hardware.org/?probe=710ddc650e) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Apple         | MacBookPro7,1               | [2641eee3f1](https://linux-hardware.org/?probe=2641eee3f1) | Apr 21, 2022 |
| ASUSTek       | X102BA                      | [00fbb5cbff](https://linux-hardware.org/?probe=00fbb5cbff) | Apr 20, 2022 |
| Lenovo        | ThinkPad L390 20NR001EPG    | [d83b89a414](https://linux-hardware.org/?probe=d83b89a414) | Apr 20, 2022 |
| HP            | Pavilion g6                 | [0c4c081e71](https://linux-hardware.org/?probe=0c4c081e71) | Apr 17, 2022 |
| Toshiba       | Satellite L775-151          | [957020b872](https://linux-hardware.org/?probe=957020b872) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | [706f14a3e6](https://linux-hardware.org/?probe=706f14a3e6) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | [a9407bd227](https://linux-hardware.org/?probe=a9407bd227) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | [7403ce7189](https://linux-hardware.org/?probe=7403ce7189) | Apr 16, 2022 |
| Toshiba       | Satellite L300              | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Toshiba       | Satellite P70-B             | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [fba984b898](https://linux-hardware.org/?probe=fba984b898) | Apr 11, 2022 |
| Positivo      | H14BU08                     | [11014257c0](https://linux-hardware.org/?probe=11014257c0) | Apr 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4ca643452e](https://linux-hardware.org/?probe=4ca643452e) | Apr 10, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8adf631258](https://linux-hardware.org/?probe=8adf631258) | Apr 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [00c3a80eb1](https://linux-hardware.org/?probe=00c3a80eb1) | Apr 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ec5daa2c06](https://linux-hardware.org/?probe=ec5daa2c06) | Apr 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| ASUSTek       | T100TA                      | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| ASUSTek       | X555LJ                      | [f9bbaea819](https://linux-hardware.org/?probe=f9bbaea819) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | [944f40aa28](https://linux-hardware.org/?probe=944f40aa28) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| HP            | Pavilion g6                 | [5dce001675](https://linux-hardware.org/?probe=5dce001675) | Mar 31, 2022 |
| MSI           | Modern 14 B11M              | [3cdc036c09](https://linux-hardware.org/?probe=3cdc036c09) | Mar 30, 2022 |
| Toshiba       | Satellite C660              | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK S752               | [73c18f75a9](https://linux-hardware.org/?probe=73c18f75a9) | Mar 29, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [41870b3fdb](https://linux-hardware.org/?probe=41870b3fdb) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fc92c7a9d2](https://linux-hardware.org/?probe=fc92c7a9d2) | Mar 28, 2022 |
| ASUSTek       | GL552VW                     | [7e8bfac4b7](https://linux-hardware.org/?probe=7e8bfac4b7) | Mar 27, 2022 |
| MSI           | GL65 Leopard 10SFK          | [96afe8ccf1](https://linux-hardware.org/?probe=96afe8ccf1) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | [a2921a6b4c](https://linux-hardware.org/?probe=a2921a6b4c) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | [ca5720c46b](https://linux-hardware.org/?probe=ca5720c46b) | Mar 25, 2022 |
| Toshiba       | Satellite P50-B-10V         | [1f6acfd782](https://linux-hardware.org/?probe=1f6acfd782) | Mar 24, 2022 |
| ASUSTek       | X510UNR                     | [ab3b8653a6](https://linux-hardware.org/?probe=ab3b8653a6) | Mar 23, 2022 |
| Apple         | MacBookAir3,1               | [482fbd3456](https://linux-hardware.org/?probe=482fbd3456) | Mar 21, 2022 |
| HP            | ProBook 640 G2              | [17ceb0fd9f](https://linux-hardware.org/?probe=17ceb0fd9f) | Mar 19, 2022 |
| ASUSTek       | X541UV                      | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| MSI           | Stealth GS66 12UGS          | [882be4cd35](https://linux-hardware.org/?probe=882be4cd35) | Mar 19, 2022 |
| HP            | ProBook 640 G2              | [9024337e9f](https://linux-hardware.org/?probe=9024337e9f) | Mar 19, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [5b345c55f7](https://linux-hardware.org/?probe=5b345c55f7) | Mar 16, 2022 |
| HP            | 250 G8 Notebook PC          | [90bbda2f8c](https://linux-hardware.org/?probe=90bbda2f8c) | Mar 16, 2022 |
| Acer          | Nitro AN515-54              | [1fea8c1b2b](https://linux-hardware.org/?probe=1fea8c1b2b) | Mar 16, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [fabbaeb1bb](https://linux-hardware.org/?probe=fabbaeb1bb) | Mar 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [3aded823d8](https://linux-hardware.org/?probe=3aded823d8) | Mar 13, 2022 |
| ASUSTek       | ZenBook UX431FA             | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8469a31d58](https://linux-hardware.org/?probe=8469a31d58) | Mar 10, 2022 |
| Sony          | VGN-FZ31Z                   | [17e3cb9771](https://linux-hardware.org/?probe=17e3cb9771) | Mar 10, 2022 |
| ASUSTek       | X541UV                      | [aef8901d13](https://linux-hardware.org/?probe=aef8901d13) | Mar 08, 2022 |
| ASUSTek       | X541UV                      | [6bed69bcdb](https://linux-hardware.org/?probe=6bed69bcdb) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Acer          | Aspire E5-551G              | [18bc15734f](https://linux-hardware.org/?probe=18bc15734f) | Mar 07, 2022 |
| ASUSTek       | X541UV                      | [a90d26bc2d](https://linux-hardware.org/?probe=a90d26bc2d) | Mar 06, 2022 |
| Lenovo        | ThinkPad W541 20EGS03100    | [f7b51cf262](https://linux-hardware.org/?probe=f7b51cf262) | Mar 05, 2022 |
| ASUSTek       | X541UV                      | [b5678eb9d3](https://linux-hardware.org/?probe=b5678eb9d3) | Mar 05, 2022 |
| Apple         | MacBookPro8,3               | [87a5df55b8](https://linux-hardware.org/?probe=87a5df55b8) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c1b8c2903d](https://linux-hardware.org/?probe=c1b8c2903d) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | [67241eca45](https://linux-hardware.org/?probe=67241eca45) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | [06455796f9](https://linux-hardware.org/?probe=06455796f9) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | [01b50ec980](https://linux-hardware.org/?probe=01b50ec980) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | [1d156021e3](https://linux-hardware.org/?probe=1d156021e3) | Feb 26, 2022 |
| Sony          | VGN-FZ31Z                   | [b223305dc1](https://linux-hardware.org/?probe=b223305dc1) | Feb 26, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Positivo      | H14BU08                     | [b3cb8e0d72](https://linux-hardware.org/?probe=b3cb8e0d72) | Feb 25, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e72b93aadf](https://linux-hardware.org/?probe=e72b93aadf) | Feb 24, 2022 |
| Apple         | MacBookPro12,1              | [e9d9cfb3e9](https://linux-hardware.org/?probe=e9d9cfb3e9) | Feb 24, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | [20b0cf0db9](https://linux-hardware.org/?probe=20b0cf0db9) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [48d36e9bae](https://linux-hardware.org/?probe=48d36e9bae) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [60adc82fb8](https://linux-hardware.org/?probe=60adc82fb8) | Feb 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cf3e28fb31](https://linux-hardware.org/?probe=cf3e28fb31) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| SLIMBOOK      | TITAN                       | [2a35f863c2](https://linux-hardware.org/?probe=2a35f863c2) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [013349e12a](https://linux-hardware.org/?probe=013349e12a) | Feb 19, 2022 |
| HP            | EliteBook 840 G6            | [b6f947ed63](https://linux-hardware.org/?probe=b6f947ed63) | Feb 18, 2022 |
| Dell          | Latitude E6440              | [1d4bac917c](https://linux-hardware.org/?probe=1d4bac917c) | Feb 18, 2022 |
| ASUSTek       | T100TA                      | [9f0a454d8b](https://linux-hardware.org/?probe=9f0a454d8b) | Feb 18, 2022 |
| ASUSTek       | X555LJ                      | [c2f63ae6d7](https://linux-hardware.org/?probe=c2f63ae6d7) | Feb 14, 2022 |
| Acer          | Aspire 5715Z                | [cdd4414bbd](https://linux-hardware.org/?probe=cdd4414bbd) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| ASUSTek       | X541UV                      | [fb81da9fa5](https://linux-hardware.org/?probe=fb81da9fa5) | Feb 13, 2022 |
| Dell          | Precision 3561              | [23c3392c57](https://linux-hardware.org/?probe=23c3392c57) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6c64279dbc](https://linux-hardware.org/?probe=6c64279dbc) | Feb 12, 2022 |
| ASUSTek       | K50IJ                       | [0dd30d1e7e](https://linux-hardware.org/?probe=0dd30d1e7e) | Feb 11, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| HP            | Compaq Presario CQ60        | [f5d9f92aad](https://linux-hardware.org/?probe=f5d9f92aad) | Feb 09, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6bee100b0a](https://linux-hardware.org/?probe=6bee100b0a) | Feb 06, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [a554a842f7](https://linux-hardware.org/?probe=a554a842f7) | Feb 05, 2022 |
| Dell          | Latitude D630               | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [722271e199](https://linux-hardware.org/?probe=722271e199) | Feb 04, 2022 |
| HP            | Pavilion Notebook           | [62cf8cdd3c](https://linux-hardware.org/?probe=62cf8cdd3c) | Feb 02, 2022 |
| Dell          | Latitude D630               | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| Sony          | VGN-FZ31Z                   | [c3e03d2551](https://linux-hardware.org/?probe=c3e03d2551) | Feb 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [e0c36731ca](https://linux-hardware.org/?probe=e0c36731ca) | Jan 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [b4f3d4f1ee](https://linux-hardware.org/?probe=b4f3d4f1ee) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [77d230b476](https://linux-hardware.org/?probe=77d230b476) | Jan 29, 2022 |
| Acer          | Aspire E5-551G              | [435c894ed4](https://linux-hardware.org/?probe=435c894ed4) | Jan 29, 2022 |
| Toshiba       | Satellite C660              | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| ASUSTek       | N56VZ                       | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| Apple         | MacBookPro9,2               | [90249388ff](https://linux-hardware.org/?probe=90249388ff) | Jan 22, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6fd36db1e0](https://linux-hardware.org/?probe=6fd36db1e0) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Sony          | VGN-FZ31Z                   | [c7f9080e23](https://linux-hardware.org/?probe=c7f9080e23) | Jan 18, 2022 |
| Acer          | Aspire ES1-512              | [ca83027c67](https://linux-hardware.org/?probe=ca83027c67) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b27ed63a97](https://linux-hardware.org/?probe=b27ed63a97) | Jan 16, 2022 |
| Toshiba       | Satellite C660              | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a8ff8d111b](https://linux-hardware.org/?probe=a8ff8d111b) | Jan 11, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [5ba5bfc822](https://linux-hardware.org/?probe=5ba5bfc822) | Jan 11, 2022 |
| HP            | Laptop 15s-fq2xxx           | [468890e10d](https://linux-hardware.org/?probe=468890e10d) | Jan 08, 2022 |
| Sony          | VGN-FZ31Z                   | [7587e6c439](https://linux-hardware.org/?probe=7587e6c439) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [a3194a0ed3](https://linux-hardware.org/?probe=a3194a0ed3) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a140e77bfe](https://linux-hardware.org/?probe=a140e77bfe) | Jan 05, 2022 |
| Toshiba       | Satellite L50D-B            | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| HP            | ProBook 4530s               | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| MSI           | Modern 14 A10RB             | [83285ade95](https://linux-hardware.org/?probe=83285ade95) | Jan 02, 2022 |
| MSI           | Modern 14 A10RB             | [602fe88681](https://linux-hardware.org/?probe=602fe88681) | Jan 02, 2022 |
| Timi          | TM1701                      | [594f40016d](https://linux-hardware.org/?probe=594f40016d) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Dell          | Latitude D420               | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| Sony          | VGN-FZ31Z                   | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | [6f891ac715](https://linux-hardware.org/?probe=6f891ac715) | Dec 29, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [d988f944f8](https://linux-hardware.org/?probe=d988f944f8) | Dec 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1daccedded](https://linux-hardware.org/?probe=1daccedded) | Dec 26, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [fe1f7f03e2](https://linux-hardware.org/?probe=fe1f7f03e2) | Dec 21, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [40282bb1fd](https://linux-hardware.org/?probe=40282bb1fd) | Dec 21, 2021 |
| Acer          | Aspire ES1-520              | [7a43d12de6](https://linux-hardware.org/?probe=7a43d12de6) | Dec 20, 2021 |
| ASUSTek       | T100HAN                     | [ad0dc6b737](https://linux-hardware.org/?probe=ad0dc6b737) | Dec 17, 2021 |
| ASUSTek       | T100HAN                     | [67b8998643](https://linux-hardware.org/?probe=67b8998643) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [f9a4ac885d](https://linux-hardware.org/?probe=f9a4ac885d) | Dec 17, 2021 |
| MSI           | Alpha 15 A4DEK              | [0ecac9e450](https://linux-hardware.org/?probe=0ecac9e450) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| MSI           | Alpha 15 A4DEK              | [4b7a0b485e](https://linux-hardware.org/?probe=4b7a0b485e) | Dec 15, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Sony          | VGN-SZ2HP_B                 | [a5d51adfab](https://linux-hardware.org/?probe=a5d51adfab) | Dec 13, 2021 |
| Lenovo        | Z51-70 80K6                 | [3faa0a2aad](https://linux-hardware.org/?probe=3faa0a2aad) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [11fb7ea1d7](https://linux-hardware.org/?probe=11fb7ea1d7) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [23579d8b3a](https://linux-hardware.org/?probe=23579d8b3a) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [66796a4303](https://linux-hardware.org/?probe=66796a4303) | Dec 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d9d5bfe12](https://linux-hardware.org/?probe=1d9d5bfe12) | Dec 05, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [aa4d4e3b08](https://linux-hardware.org/?probe=aa4d4e3b08) | Dec 04, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Sony          | VGN-FZ31Z                   | [8e4401834b](https://linux-hardware.org/?probe=8e4401834b) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Packard Be... | EasyNote_MX37-V-101PT       | [6f8e7042c4](https://linux-hardware.org/?probe=6f8e7042c4) | Nov 30, 2021 |
| Acer          | Aspire A315-57G             | [cfc036a421](https://linux-hardware.org/?probe=cfc036a421) | Nov 29, 2021 |
| HP            | OMEN by Laptop              | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Acer          | Aspire E5-521               | [48d70742bb](https://linux-hardware.org/?probe=48d70742bb) | Nov 28, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [1a717e5780](https://linux-hardware.org/?probe=1a717e5780) | Nov 28, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| HP            | Pavilion 15                 | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| HP            | 15 TS                       | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| Clevo         | M7X0SU                      | [a9638079c6](https://linux-hardware.org/?probe=a9638079c6) | Nov 20, 2021 |
| ASUSTek       | UX303LAB                    | [21a3bdf255](https://linux-hardware.org/?probe=21a3bdf255) | Nov 19, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [8fc5db0cd9](https://linux-hardware.org/?probe=8fc5db0cd9) | Nov 17, 2021 |
| Sony          | VGN-FZ31Z                   | [2c4fd499c5](https://linux-hardware.org/?probe=2c4fd499c5) | Nov 17, 2021 |
| HP            | Pavilion dv6                | [3f54f48e23](https://linux-hardware.org/?probe=3f54f48e23) | Nov 17, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [5f28060674](https://linux-hardware.org/?probe=5f28060674) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [72e7bebf84](https://linux-hardware.org/?probe=72e7bebf84) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [39d8ea222a](https://linux-hardware.org/?probe=39d8ea222a) | Nov 16, 2021 |
| HUAWEI        | WRT-WX9                     | [6c0ee3ae74](https://linux-hardware.org/?probe=6c0ee3ae74) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [be61c60b41](https://linux-hardware.org/?probe=be61c60b41) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [9fa65491aa](https://linux-hardware.org/?probe=9fa65491aa) | Nov 12, 2021 |
| ASUSTek       | X202EV                      | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| Sony          | VGN-FZ31Z                   | [fe8ba3f801](https://linux-hardware.org/?probe=fe8ba3f801) | Nov 11, 2021 |
| ASUSTek       | T102HA                      | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| Lenovo        | ThinkPad T420 4177Q5U       | [02ce053478](https://linux-hardware.org/?probe=02ce053478) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [c13d42cb63](https://linux-hardware.org/?probe=c13d42cb63) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [8403f5c97f](https://linux-hardware.org/?probe=8403f5c97f) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | G62                         | [a4a0360f3a](https://linux-hardware.org/?probe=a4a0360f3a) | Nov 06, 2021 |
| HP            | G62                         | [cd87bfa19b](https://linux-hardware.org/?probe=cd87bfa19b) | Nov 06, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [87daccdc88](https://linux-hardware.org/?probe=87daccdc88) | Nov 05, 2021 |
| HP            | OMEN by Laptop              | [0b933dd493](https://linux-hardware.org/?probe=0b933dd493) | Nov 03, 2021 |
| Toshiba       | Satellite C660              | [c22b81abd4](https://linux-hardware.org/?probe=c22b81abd4) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [bbe04676c1](https://linux-hardware.org/?probe=bbe04676c1) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [09eba8bb5f](https://linux-hardware.org/?probe=09eba8bb5f) | Nov 02, 2021 |
| Standard      | Unknown                     | [3cccd4bf9f](https://linux-hardware.org/?probe=3cccd4bf9f) | Nov 02, 2021 |
| HP            | ProBook 445 G7              | [ca8418c85b](https://linux-hardware.org/?probe=ca8418c85b) | Nov 02, 2021 |
| Acer          | Aspire E1-570G              | [9c6c7691c9](https://linux-hardware.org/?probe=9c6c7691c9) | Nov 02, 2021 |
| Acer          | Aspire 4732Z                | [7095848f26](https://linux-hardware.org/?probe=7095848f26) | Oct 31, 2021 |
| Acer          | Aspire 4732Z                | [ce23f8d9f9](https://linux-hardware.org/?probe=ce23f8d9f9) | Oct 30, 2021 |
| Standard      | Unknown                     | [1bf7e2da2f](https://linux-hardware.org/?probe=1bf7e2da2f) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [9276790a36](https://linux-hardware.org/?probe=9276790a36) | Oct 28, 2021 |
| Acer          | Aspire 5732Z                | [9d4f7a1a4b](https://linux-hardware.org/?probe=9d4f7a1a4b) | Oct 27, 2021 |
| ASUSTek       | X453MA                      | [4a70424b2f](https://linux-hardware.org/?probe=4a70424b2f) | Oct 27, 2021 |
| ASUSTek       | X540YA                      | [9b382500c5](https://linux-hardware.org/?probe=9b382500c5) | Oct 27, 2021 |
| Dell          | Latitude E5400              | [7049bbe182](https://linux-hardware.org/?probe=7049bbe182) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4826046b43](https://linux-hardware.org/?probe=4826046b43) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | [b3e2853259](https://linux-hardware.org/?probe=b3e2853259) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | [5af2c96114](https://linux-hardware.org/?probe=5af2c96114) | Oct 24, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| HP            | Notebook                    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| ASUSTek       | X555LD                      | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Lenovo        | ThinkPad T480 20L6S7PE06    | [28857899a2](https://linux-hardware.org/?probe=28857899a2) | Oct 20, 2021 |
| HP            | Compaq Presario CQ60        | [0b02aa22d4](https://linux-hardware.org/?probe=0b02aa22d4) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Toshiba       | Satellite C660              | [c70057c643](https://linux-hardware.org/?probe=c70057c643) | Oct 16, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [6360789a1c](https://linux-hardware.org/?probe=6360789a1c) | Oct 14, 2021 |
| eMachines     | E520 V1.06                  | [97c667e3c0](https://linux-hardware.org/?probe=97c667e3c0) | Oct 14, 2021 |
| HP            | EliteBook 840 G3            | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| HP            | Pavilion g6                 | [5eba384acd](https://linux-hardware.org/?probe=5eba384acd) | Oct 11, 2021 |
| HP            | Notebook                    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [77a6cb9eba](https://linux-hardware.org/?probe=77a6cb9eba) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [99c08de77b](https://linux-hardware.org/?probe=99c08de77b) | Oct 07, 2021 |
| HP            | G62                         | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| Dell          | XPS 13 7390                 | [843d9a14d4](https://linux-hardware.org/?probe=843d9a14d4) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | [b1996e39c6](https://linux-hardware.org/?probe=b1996e39c6) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | [47def5d058](https://linux-hardware.org/?probe=47def5d058) | Oct 05, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96cf9ba56a](https://linux-hardware.org/?probe=96cf9ba56a) | Sep 30, 2021 |
| ASUSTek       | X453MA                      | [782dfc1a5f](https://linux-hardware.org/?probe=782dfc1a5f) | Sep 30, 2021 |
| Toshiba       | Satellite L500              | [07116867d0](https://linux-hardware.org/?probe=07116867d0) | Sep 30, 2021 |
| Unknown       | Unknown                     | [1466ee93ee](https://linux-hardware.org/?probe=1466ee93ee) | Sep 29, 2021 |
| SLIMBOOK      | TITAN                       | [985d394a66](https://linux-hardware.org/?probe=985d394a66) | Sep 29, 2021 |
| HP            | Pavilion dv6                | [0a3653d139](https://linux-hardware.org/?probe=0a3653d139) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| HP            | Pavilion dv6                | [a5de874a12](https://linux-hardware.org/?probe=a5de874a12) | Sep 26, 2021 |
| Dell          | Latitude 5400               | [c94a87ddcd](https://linux-hardware.org/?probe=c94a87ddcd) | Sep 26, 2021 |
| Fujitsu       | LIFEBOOK AH552/SL           | [adefc47ea8](https://linux-hardware.org/?probe=adefc47ea8) | Sep 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| HP            | Laptop 15-bs0xx             | [6a1f29d17c](https://linux-hardware.org/?probe=6a1f29d17c) | Sep 22, 2021 |
| Dynabook      | PORTEGE X50-G               | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [8a14f4f8ce](https://linux-hardware.org/?probe=8a14f4f8ce) | Sep 20, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| Sony          | VGN-FZ31Z                   | [134fab4631](https://linux-hardware.org/?probe=134fab4631) | Sep 17, 2021 |
| Sony          | VGN-FZ31Z                   | [78a5f6cc5b](https://linux-hardware.org/?probe=78a5f6cc5b) | Sep 16, 2021 |
| Sony          | VGN-FZ31Z                   | [fd9704ad22](https://linux-hardware.org/?probe=fd9704ad22) | Sep 16, 2021 |
| ASUSTek       | F5SL                        | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Sony          | VGN-FZ21M                   | [f68a8cedaa](https://linux-hardware.org/?probe=f68a8cedaa) | Sep 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [232a307a5b](https://linux-hardware.org/?probe=232a307a5b) | Sep 14, 2021 |
| Acer          | Aspire ES1-520              | [4b4f263238](https://linux-hardware.org/?probe=4b4f263238) | Sep 14, 2021 |
| Intel         | powered classmate PC        | [15cb9c7764](https://linux-hardware.org/?probe=15cb9c7764) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [bfe6584c68](https://linux-hardware.org/?probe=bfe6584c68) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [e82ca3db5b](https://linux-hardware.org/?probe=e82ca3db5b) | Sep 12, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c50b07bfbc](https://linux-hardware.org/?probe=c50b07bfbc) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [24053a2921](https://linux-hardware.org/?probe=24053a2921) | Sep 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [b34fb7492d](https://linux-hardware.org/?probe=b34fb7492d) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e65bcd50d4](https://linux-hardware.org/?probe=e65bcd50d4) | Sep 05, 2021 |
| ASUSTek       | K53SV                       | [f617f97f20](https://linux-hardware.org/?probe=f617f97f20) | Sep 03, 2021 |
| Dell          | XPS 13 7390                 | [be1de37337](https://linux-hardware.org/?probe=be1de37337) | Sep 03, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [62e286b6bc](https://linux-hardware.org/?probe=62e286b6bc) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [84ed2a684d](https://linux-hardware.org/?probe=84ed2a684d) | Aug 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6d630f76dc](https://linux-hardware.org/?probe=6d630f76dc) | Aug 30, 2021 |
| Apple         | MacBookAir3,1               | [c431035e14](https://linux-hardware.org/?probe=c431035e14) | Aug 28, 2021 |
| HP            | EliteBook 820 G1            | [fcfdefc5ce](https://linux-hardware.org/?probe=fcfdefc5ce) | Aug 24, 2021 |
| Acer          | Aspire one 1-431            | [1d73bf7163](https://linux-hardware.org/?probe=1d73bf7163) | Aug 23, 2021 |
| HP            | Compaq Presario CQ50        | [afde6653db](https://linux-hardware.org/?probe=afde6653db) | Aug 20, 2021 |
| ASUSTek       | K52Je                       | [d35de28c56](https://linux-hardware.org/?probe=d35de28c56) | Aug 17, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [c2dee4fe1c](https://linux-hardware.org/?probe=c2dee4fe1c) | Aug 14, 2021 |
| HP            | Compaq Presario CQ71        | [c1e4d1748b](https://linux-hardware.org/?probe=c1e4d1748b) | Aug 14, 2021 |
| ASUSTek       | K52Je                       | [ae9629c543](https://linux-hardware.org/?probe=ae9629c543) | Aug 13, 2021 |
| Teclast       | TbooK 11                    | [d045383640](https://linux-hardware.org/?probe=d045383640) | Aug 12, 2021 |
| Teclast       | TbooK 11                    | [f3e17cb791](https://linux-hardware.org/?probe=f3e17cb791) | Aug 12, 2021 |
| ASUSTek       | X541UV                      | [3f45acb762](https://linux-hardware.org/?probe=3f45acb762) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3fb07ec1ab](https://linux-hardware.org/?probe=3fb07ec1ab) | Aug 11, 2021 |
| MSI           | Alpha 15 A4DEK              | [f8bd1ccc54](https://linux-hardware.org/?probe=f8bd1ccc54) | Aug 09, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| MSI           | Alpha 15 A4DEK              | [77c994366c](https://linux-hardware.org/?probe=77c994366c) | Aug 04, 2021 |
| Apple         | MacBookPro8,1               | [ea96dd2fc0](https://linux-hardware.org/?probe=ea96dd2fc0) | Aug 03, 2021 |
| Acer          | Extensa 5635ZG              | [7b18fd92ec](https://linux-hardware.org/?probe=7b18fd92ec) | Aug 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [dde43dfc5f](https://linux-hardware.org/?probe=dde43dfc5f) | Jul 31, 2021 |
| Acer          | Extensa 5635ZG              | [920920b284](https://linux-hardware.org/?probe=920920b284) | Jul 30, 2021 |
| HP            | EliteBook 840 G1            | [a4d0bd11cf](https://linux-hardware.org/?probe=a4d0bd11cf) | Jul 30, 2021 |
| Packard Be... | EasyNote MB65               | [f659f0645c](https://linux-hardware.org/?probe=f659f0645c) | Jul 28, 2021 |
| Toshiba       | Satellite L50-B             | [0e3d86e5fc](https://linux-hardware.org/?probe=0e3d86e5fc) | Jul 28, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [e877303c3f](https://linux-hardware.org/?probe=e877303c3f) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| ASUSTek       | X550DP                      | [fab8695920](https://linux-hardware.org/?probe=fab8695920) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [a2ba4d937e](https://linux-hardware.org/?probe=a2ba4d937e) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N3S27C00    | [f4f26a9357](https://linux-hardware.org/?probe=f4f26a9357) | Jul 24, 2021 |
| Sony          | VGN-AW21Z_B                 | [16afdefee9](https://linux-hardware.org/?probe=16afdefee9) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [ad8fb39682](https://linux-hardware.org/?probe=ad8fb39682) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | [996bc7336f](https://linux-hardware.org/?probe=996bc7336f) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | [84d70d9bde](https://linux-hardware.org/?probe=84d70d9bde) | Jul 23, 2021 |
| Toshiba       | Satellite M70               | [ffe4b92da3](https://linux-hardware.org/?probe=ffe4b92da3) | Jul 21, 2021 |
| Toshiba       | Satellite C50-B             | [288b6b0769](https://linux-hardware.org/?probe=288b6b0769) | Jul 16, 2021 |
| Toshiba       | Satellite P50-C             | [3b8ead252b](https://linux-hardware.org/?probe=3b8ead252b) | Jul 15, 2021 |
| HP            | Compaq Presario CQ71        | [d26cb48393](https://linux-hardware.org/?probe=d26cb48393) | Jul 14, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [9d1dfce344](https://linux-hardware.org/?probe=9d1dfce344) | Jul 13, 2021 |
| ASUSTek       | T100HAN                     | [9d9f33c5e5](https://linux-hardware.org/?probe=9d9f33c5e5) | Jul 12, 2021 |
| Acer          | NC-V3-575G-58LU             | [da6da7fbd6](https://linux-hardware.org/?probe=da6da7fbd6) | Jul 11, 2021 |
| ASUSTek       | G50V                        | [ec1ddd4644](https://linux-hardware.org/?probe=ec1ddd4644) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| Dell          | Latitude D530               | [d48cd58890](https://linux-hardware.org/?probe=d48cd58890) | Jul 09, 2021 |
| Dell          | Precision M4600             | [388aad414f](https://linux-hardware.org/?probe=388aad414f) | Jul 08, 2021 |
| Dell          | Latitude D530               | [21ad721b61](https://linux-hardware.org/?probe=21ad721b61) | Jul 07, 2021 |
| SLIMBOOK      | TITAN                       | [59233d0bff](https://linux-hardware.org/?probe=59233d0bff) | Jul 07, 2021 |
| Acer          | Aspire 5738                 | [77c0819e0f](https://linux-hardware.org/?probe=77c0819e0f) | Jul 07, 2021 |
| Toshiba       | Satellite C50-B             | [0bdc8750c3](https://linux-hardware.org/?probe=0bdc8750c3) | Jul 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0e79f21646](https://linux-hardware.org/?probe=0e79f21646) | Jul 05, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d6ef1b054b](https://linux-hardware.org/?probe=d6ef1b054b) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3430744d8](https://linux-hardware.org/?probe=f3430744d8) | Jun 24, 2021 |
| HP            | ENVY 17                     | [c6b33cf692](https://linux-hardware.org/?probe=c6b33cf692) | Jun 22, 2021 |
| HP            | EliteBook 820 G1            | [46e46cdce1](https://linux-hardware.org/?probe=46e46cdce1) | Jun 20, 2021 |
| Dell          | XPS 13 9305                 | [02ee8d11bc](https://linux-hardware.org/?probe=02ee8d11bc) | Jun 19, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Dell          | XPS 13 9305                 | [d1799a89c4](https://linux-hardware.org/?probe=d1799a89c4) | Jun 17, 2021 |
| Dell          | Latitude E6520              | [718e90b724](https://linux-hardware.org/?probe=718e90b724) | Jun 17, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [b796c5a183](https://linux-hardware.org/?probe=b796c5a183) | Jun 16, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| SLIMBOOK      | PROX15-INTEL                | [f471ae0176](https://linux-hardware.org/?probe=f471ae0176) | Jun 15, 2021 |
| ASUSTek       | K73SV                       | [228feaed8e](https://linux-hardware.org/?probe=228feaed8e) | Jun 12, 2021 |
| Google        | Coral                       | [f6cf3ed923](https://linux-hardware.org/?probe=f6cf3ed923) | Jun 11, 2021 |
| HP            | Slate 2                     | [0d820f363e](https://linux-hardware.org/?probe=0d820f363e) | Jun 10, 2021 |
| HP            | Slate 2                     | [ecb6d7d96f](https://linux-hardware.org/?probe=ecb6d7d96f) | Jun 10, 2021 |
| Acer          | Extensa 5635ZG              | [540d6fca8e](https://linux-hardware.org/?probe=540d6fca8e) | Jun 07, 2021 |
| Acer          | Aspire E5-523G              | [b092f36afc](https://linux-hardware.org/?probe=b092f36afc) | Jun 06, 2021 |
| HP            | ProBook 4520s               | [87f9426157](https://linux-hardware.org/?probe=87f9426157) | Jun 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [25a53bf5a0](https://linux-hardware.org/?probe=25a53bf5a0) | Jun 05, 2021 |
| Dell          | Precision M4600             | [b1bc313622](https://linux-hardware.org/?probe=b1bc313622) | Jun 04, 2021 |
| ASUSTek       | T100HAN                     | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| Toshiba       | Satellite C660D             | [39a33d288a](https://linux-hardware.org/?probe=39a33d288a) | Jun 03, 2021 |
| HP            | ProBook 450 G6              | [af16143ad8](https://linux-hardware.org/?probe=af16143ad8) | Jun 03, 2021 |
| Toshiba       | PORTEGE Z930                | [4a95259edd](https://linux-hardware.org/?probe=4a95259edd) | Jun 03, 2021 |
| Acer          | Aspire A315-41              | [15de6a42cc](https://linux-hardware.org/?probe=15de6a42cc) | Jun 01, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [0540d35606](https://linux-hardware.org/?probe=0540d35606) | May 31, 2021 |
| ASUSTek       | T100HAN                     | [ca42a42366](https://linux-hardware.org/?probe=ca42a42366) | May 30, 2021 |
| Acer          | Aspire ES1-572              | [c16c3f3c20](https://linux-hardware.org/?probe=c16c3f3c20) | May 29, 2021 |
| Samsung       | 700T                        | [374154a439](https://linux-hardware.org/?probe=374154a439) | May 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [430907546b](https://linux-hardware.org/?probe=430907546b) | May 29, 2021 |
| HP            | Pavilion g6                 | [03f3d2f19b](https://linux-hardware.org/?probe=03f3d2f19b) | May 27, 2021 |
| ASUSTek       | X555LD                      | [a0ab13de0b](https://linux-hardware.org/?probe=a0ab13de0b) | May 26, 2021 |
| ASUSTek       | T100HAN                     | [20badd4bf8](https://linux-hardware.org/?probe=20badd4bf8) | May 24, 2021 |
| HUAWEI        | WRT-WX9                     | [8865e5f33f](https://linux-hardware.org/?probe=8865e5f33f) | May 21, 2021 |
| ASUSTek       | X540YA                      | [c7d85ee10a](https://linux-hardware.org/?probe=c7d85ee10a) | May 21, 2021 |
| Toshiba       | PORTEGE Z930                | [e006b8bf83](https://linux-hardware.org/?probe=e006b8bf83) | May 18, 2021 |
| ASUSTek       | X541UJ                      | [0fc9152ae2](https://linux-hardware.org/?probe=0fc9152ae2) | May 16, 2021 |
| Acer          | Aspire E5-411               | [e9004a67e9](https://linux-hardware.org/?probe=e9004a67e9) | May 16, 2021 |
| HP            | EliteBook Folio 1040 G1     | [1e47d123cc](https://linux-hardware.org/?probe=1e47d123cc) | May 15, 2021 |
| ASUSTek       | T100HAN                     | [7195f02080](https://linux-hardware.org/?probe=7195f02080) | May 13, 2021 |
| ASUSTek       | 1215N                       | [2e4383bd79](https://linux-hardware.org/?probe=2e4383bd79) | May 13, 2021 |
| Acer          | Aspire 5750                 | [51386797f0](https://linux-hardware.org/?probe=51386797f0) | May 11, 2021 |
| HP            | Laptop 17-ak0xx             | [b2207b19c0](https://linux-hardware.org/?probe=b2207b19c0) | May 09, 2021 |
| INSYS         | CD9-G148                    | [162b7d2dd4](https://linux-hardware.org/?probe=162b7d2dd4) | May 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [34b008d2a3](https://linux-hardware.org/?probe=34b008d2a3) | May 06, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [8edf563281](https://linux-hardware.org/?probe=8edf563281) | May 03, 2021 |
| eMachines     | eME728                      | [9c098c150f](https://linux-hardware.org/?probe=9c098c150f) | May 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [8956498c75](https://linux-hardware.org/?probe=8956498c75) | Apr 29, 2021 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [b3a280cc6b](https://linux-hardware.org/?probe=b3a280cc6b) | Apr 29, 2021 |
| Positivo      | H14BU08                     | [0074b53665](https://linux-hardware.org/?probe=0074b53665) | Apr 28, 2021 |
| ASUSTek       | K73SV                       | [d810797575](https://linux-hardware.org/?probe=d810797575) | Apr 28, 2021 |
| ASUSTek       | K73SV                       | [b70e4fe78b](https://linux-hardware.org/?probe=b70e4fe78b) | Apr 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bf2ec3a69c](https://linux-hardware.org/?probe=bf2ec3a69c) | Apr 26, 2021 |
| ASUSTek       | X555LJ                      | [3febe6795e](https://linux-hardware.org/?probe=3febe6795e) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [0bcc333251](https://linux-hardware.org/?probe=0bcc333251) | Apr 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [508213fd9c](https://linux-hardware.org/?probe=508213fd9c) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | [f82c8e8839](https://linux-hardware.org/?probe=f82c8e8839) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | [bcca68ee1a](https://linux-hardware.org/?probe=bcca68ee1a) | Apr 25, 2021 |
| HP            | Laptop 15-gw0xxx            | [bbb889a0ca](https://linux-hardware.org/?probe=bbb889a0ca) | Apr 25, 2021 |
| ASUSTek       | T100HAN                     | [a8ff3e1736](https://linux-hardware.org/?probe=a8ff3e1736) | Apr 22, 2021 |
| ASUSTek       | T100HAN                     | [2c4f2ffa49](https://linux-hardware.org/?probe=2c4f2ffa49) | Apr 20, 2021 |
| Dell          | XPS 13 7390                 | [b1801d62cb](https://linux-hardware.org/?probe=b1801d62cb) | Apr 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a008c4e692](https://linux-hardware.org/?probe=a008c4e692) | Apr 19, 2021 |
| ASUSTek       | T100HAN                     | [5ff0bb6a88](https://linux-hardware.org/?probe=5ff0bb6a88) | Apr 18, 2021 |
| Toshiba       | Satellite L50D-B            | [4b47248331](https://linux-hardware.org/?probe=4b47248331) | Apr 18, 2021 |
| Toshiba       | Satellite L50D-B            | [2df86fbb1c](https://linux-hardware.org/?probe=2df86fbb1c) | Apr 18, 2021 |
| Sony          | VGN-FZ140N                  | [b46e85cdb2](https://linux-hardware.org/?probe=b46e85cdb2) | Apr 17, 2021 |
| HP            | Pavilion dv6                | [cc367d13cf](https://linux-hardware.org/?probe=cc367d13cf) | Apr 16, 2021 |
| HP            | Pavilion dv6                | [d5b4576543](https://linux-hardware.org/?probe=d5b4576543) | Apr 16, 2021 |
| Lenovo        | B50-10 80QR                 | [a5d4730bbe](https://linux-hardware.org/?probe=a5d4730bbe) | Apr 16, 2021 |
| HP            | Pavilion dv6                | [10a2c15ac0](https://linux-hardware.org/?probe=10a2c15ac0) | Apr 12, 2021 |
| Dell          | XPS 13 7390                 | [2c074aa232](https://linux-hardware.org/?probe=2c074aa232) | Apr 12, 2021 |
| Toshiba       | Satellite L40               | [0f6ed90100](https://linux-hardware.org/?probe=0f6ed90100) | Apr 11, 2021 |
| HP            | Pavilion dv6                | [5c83ad0f56](https://linux-hardware.org/?probe=5c83ad0f56) | Apr 10, 2021 |
| Toshiba       | Satellite L650              | [5652130b72](https://linux-hardware.org/?probe=5652130b72) | Apr 09, 2021 |
| Acer          | Aspire A515-51G             | [0af274abed](https://linux-hardware.org/?probe=0af274abed) | Apr 03, 2021 |
| Acer          | Aspire A515-51G             | [21263e72df](https://linux-hardware.org/?probe=21263e72df) | Apr 03, 2021 |
| eMachines     | eME728                      | [1db163e222](https://linux-hardware.org/?probe=1db163e222) | Apr 02, 2021 |
| Dell          | Latitude E5410              | [5d8f94313f](https://linux-hardware.org/?probe=5d8f94313f) | Apr 02, 2021 |
| Acer          | Aspire A315-41              | [2ba4e8be53](https://linux-hardware.org/?probe=2ba4e8be53) | Apr 02, 2021 |
| Phoenix/Si... | M7X0SU                      | [44b42fe693](https://linux-hardware.org/?probe=44b42fe693) | Apr 02, 2021 |
| HP            | Pavilion dv6                | [9d7000a50b](https://linux-hardware.org/?probe=9d7000a50b) | Mar 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [859d3df16d](https://linux-hardware.org/?probe=859d3df16d) | Mar 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [8d09fd5fad](https://linux-hardware.org/?probe=8d09fd5fad) | Mar 29, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [417973ae47](https://linux-hardware.org/?probe=417973ae47) | Mar 27, 2021 |
| Lenovo        | ThinkPad X390 20Q1S17H02    | [8a1509f6f9](https://linux-hardware.org/?probe=8a1509f6f9) | Mar 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [804865062f](https://linux-hardware.org/?probe=804865062f) | Mar 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [186f54f898](https://linux-hardware.org/?probe=186f54f898) | Mar 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [36ba280ff4](https://linux-hardware.org/?probe=36ba280ff4) | Mar 20, 2021 |
| HP            | Compaq Presario CQ60        | [29b5b3b3c4](https://linux-hardware.org/?probe=29b5b3b3c4) | Mar 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcb52364ec](https://linux-hardware.org/?probe=bcb52364ec) | Mar 18, 2021 |
| ASUSTek       | T100HAN                     | [4d004db7b4](https://linux-hardware.org/?probe=4d004db7b4) | Mar 17, 2021 |
| ASUSTek       | T100HAN                     | [375e68fd9f](https://linux-hardware.org/?probe=375e68fd9f) | Mar 17, 2021 |
| Toshiba       | Satellite T110              | [e974c29a53](https://linux-hardware.org/?probe=e974c29a53) | Mar 17, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1WS0... | [616d32ae4b](https://linux-hardware.org/?probe=616d32ae4b) | Mar 16, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1WS0... | [67f54ece11](https://linux-hardware.org/?probe=67f54ece11) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [bcdd60dc85](https://linux-hardware.org/?probe=bcdd60dc85) | Mar 14, 2021 |
| Lenovo        | ThinkPad R400 7443E1G       | [10584ae27b](https://linux-hardware.org/?probe=10584ae27b) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [14d6107700](https://linux-hardware.org/?probe=14d6107700) | Mar 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [3043c4c8ed](https://linux-hardware.org/?probe=3043c4c8ed) | Mar 13, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [edbe4b927f](https://linux-hardware.org/?probe=edbe4b927f) | Mar 12, 2021 |
| MSI           | Prestige 15 A10SC           | [6bcf98bb2b](https://linux-hardware.org/?probe=6bcf98bb2b) | Mar 10, 2021 |
| Alienware     | 17 R3                       | [8582334b5a](https://linux-hardware.org/?probe=8582334b5a) | Mar 10, 2021 |
| HP            | G62                         | [2be248991e](https://linux-hardware.org/?probe=2be248991e) | Mar 08, 2021 |
| Acer          | Aspire E5-521               | [d2ee782761](https://linux-hardware.org/?probe=d2ee782761) | Mar 07, 2021 |
| HP            | G62                         | [4d4a5d0369](https://linux-hardware.org/?probe=4d4a5d0369) | Mar 07, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [0f1bf2c9c8](https://linux-hardware.org/?probe=0f1bf2c9c8) | Mar 06, 2021 |
| Acer          | Aspire 5551G                | [eb7deed365](https://linux-hardware.org/?probe=eb7deed365) | Mar 05, 2021 |
| ASUSTek       | X102BA                      | [5b648fcc6b](https://linux-hardware.org/?probe=5b648fcc6b) | Mar 04, 2021 |
| Lenovo        | ThinkPad SL500 27466CS      | [f2d482cf8d](https://linux-hardware.org/?probe=f2d482cf8d) | Mar 02, 2021 |
| HP            | Pavilion x2 Detachable      | [9eb3ae4c15](https://linux-hardware.org/?probe=9eb3ae4c15) | Feb 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [83587f3565](https://linux-hardware.org/?probe=83587f3565) | Feb 25, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [c584e27b6c](https://linux-hardware.org/?probe=c584e27b6c) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | [7a2466e991](https://linux-hardware.org/?probe=7a2466e991) | Feb 25, 2021 |
| Acer          | Aspire E5-573G              | [55a00ca46d](https://linux-hardware.org/?probe=55a00ca46d) | Feb 24, 2021 |
| Sony          | 91                          | [adfdcf1669](https://linux-hardware.org/?probe=adfdcf1669) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | [86f60bbc44](https://linux-hardware.org/?probe=86f60bbc44) | Feb 23, 2021 |
| HP            | Laptop 15-da0xxx            | [6a9341e4ab](https://linux-hardware.org/?probe=6a9341e4ab) | Feb 22, 2021 |
| Acer          | Aspire ES1-512              | [cfc54d6468](https://linux-hardware.org/?probe=cfc54d6468) | Feb 21, 2021 |
| Acer          | Aspire E5-521G              | [7b0155df52](https://linux-hardware.org/?probe=7b0155df52) | Feb 20, 2021 |
| Apple         | MacBookPro9,2               | [022bccde17](https://linux-hardware.org/?probe=022bccde17) | Feb 19, 2021 |
| HP            | G62                         | [bf7d5b9736](https://linux-hardware.org/?probe=bf7d5b9736) | Feb 19, 2021 |
| Sony          | SVE1512C6EW                 | [477d0e5a6d](https://linux-hardware.org/?probe=477d0e5a6d) | Feb 17, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [2e3039e232](https://linux-hardware.org/?probe=2e3039e232) | Feb 15, 2021 |
| ASUSTek       | X555LD                      | [78355d7193](https://linux-hardware.org/?probe=78355d7193) | Feb 14, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [ba8153abd8](https://linux-hardware.org/?probe=ba8153abd8) | Feb 14, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [3cc715f92a](https://linux-hardware.org/?probe=3cc715f92a) | Feb 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [c097a16392](https://linux-hardware.org/?probe=c097a16392) | Feb 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [252b674af4](https://linux-hardware.org/?probe=252b674af4) | Feb 14, 2021 |
| Acer          | Aspire 5732Z                | [a72e26c3bd](https://linux-hardware.org/?probe=a72e26c3bd) | Feb 14, 2021 |
| HP            | G62                         | [3acbc7c7e3](https://linux-hardware.org/?probe=3acbc7c7e3) | Feb 13, 2021 |
| MSI           | GS65 Stealth Thin 8RE       | [d948546be2](https://linux-hardware.org/?probe=d948546be2) | Feb 13, 2021 |
| MSI           | GS65 Stealth Thin 8RE       | [63e4ddb6a6](https://linux-hardware.org/?probe=63e4ddb6a6) | Feb 13, 2021 |
| HP            | Pavilion Notebook           | [fcc62099b2](https://linux-hardware.org/?probe=fcc62099b2) | Feb 13, 2021 |
| Toshiba       | Satellite M50D-A            | [248337d69a](https://linux-hardware.org/?probe=248337d69a) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [922c8b7dfd](https://linux-hardware.org/?probe=922c8b7dfd) | Feb 11, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [e2f6310b33](https://linux-hardware.org/?probe=e2f6310b33) | Feb 11, 2021 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [57f509711d](https://linux-hardware.org/?probe=57f509711d) | Feb 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [1ddd62bb74](https://linux-hardware.org/?probe=1ddd62bb74) | Feb 10, 2021 |
| HP            | Compaq Presario CQ61        | [88bc30b5c4](https://linux-hardware.org/?probe=88bc30b5c4) | Feb 07, 2021 |
| HP            | Pavilion dv5                | [25a5b76a4b](https://linux-hardware.org/?probe=25a5b76a4b) | Feb 07, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b94aa04034](https://linux-hardware.org/?probe=b94aa04034) | Feb 06, 2021 |
| ASUSTek       | E203NAS                     | [a97e612dd4](https://linux-hardware.org/?probe=a97e612dd4) | Feb 05, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [33311133f5](https://linux-hardware.org/?probe=33311133f5) | Feb 03, 2021 |
| HP            | G62                         | [af6f8ed7d3](https://linux-hardware.org/?probe=af6f8ed7d3) | Feb 01, 2021 |
| Notebook      | N2x0WU                      | [fad3702ef5](https://linux-hardware.org/?probe=fad3702ef5) | Feb 01, 2021 |
| HP            | Compaq Presario CQ50        | [98a871c74d](https://linux-hardware.org/?probe=98a871c74d) | Feb 01, 2021 |
| HP            | ProBook 6550b               | [b41bf411ae](https://linux-hardware.org/?probe=b41bf411ae) | Jan 31, 2021 |
| Toshiba       | Satellite C50D-B            | [5b1624d2fa](https://linux-hardware.org/?probe=5b1624d2fa) | Jan 31, 2021 |
| ASUSTek       | S400CA                      | [9749eb6d22](https://linux-hardware.org/?probe=9749eb6d22) | Jan 31, 2021 |
| Acer          | Aspire E1-570G              | [19e6d6afd7](https://linux-hardware.org/?probe=19e6d6afd7) | Jan 28, 2021 |
| HP            | ProBook 6550b               | [90cc726402](https://linux-hardware.org/?probe=90cc726402) | Jan 27, 2021 |
| Acer          | Aspire E1-570G              | [f8f4880823](https://linux-hardware.org/?probe=f8f4880823) | Jan 26, 2021 |
| Clevo         | W760T/M740T/M760T           | [4b75664c6f](https://linux-hardware.org/?probe=4b75664c6f) | Jan 25, 2021 |
| MSI           | GF75 Thin 10SCSR            | [7a6ed88f27](https://linux-hardware.org/?probe=7a6ed88f27) | Jan 24, 2021 |
| MSI           | GF75 Thin 10SCSR            | [f04b769e0d](https://linux-hardware.org/?probe=f04b769e0d) | Jan 24, 2021 |
| ASUSTek       | X541UVK                     | [bb710f7faa](https://linux-hardware.org/?probe=bb710f7faa) | Jan 23, 2021 |
| ASUSTek       | X541UVK                     | [541bbe8e75](https://linux-hardware.org/?probe=541bbe8e75) | Jan 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [6eb0721a80](https://linux-hardware.org/?probe=6eb0721a80) | Jan 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF07    | [fab6e1d3ad](https://linux-hardware.org/?probe=fab6e1d3ad) | Jan 21, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF07    | [5311f338e0](https://linux-hardware.org/?probe=5311f338e0) | Jan 21, 2021 |
| Acer          | Aspire E5-521               | [50ee0ac068](https://linux-hardware.org/?probe=50ee0ac068) | Jan 20, 2021 |
| ASUSTek       | N56VZ                       | [039ce9b983](https://linux-hardware.org/?probe=039ce9b983) | Jan 19, 2021 |
| HP            | ProBook 6475b               | [82693f57b0](https://linux-hardware.org/?probe=82693f57b0) | Jan 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [313cc475fc](https://linux-hardware.org/?probe=313cc475fc) | Jan 11, 2021 |
| Notebook      | NV4XMZ                      | [130719e683](https://linux-hardware.org/?probe=130719e683) | Jan 09, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [ffeb181a7f](https://linux-hardware.org/?probe=ffeb181a7f) | Jan 08, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [5b2eb10b23](https://linux-hardware.org/?probe=5b2eb10b23) | Jan 08, 2021 |
| Lenovo        | ThinkPad T480 20L6SEH700    | [cce564cea6](https://linux-hardware.org/?probe=cce564cea6) | Jan 07, 2021 |
| HP            | Compaq Presario CQ61        | [87076627c9](https://linux-hardware.org/?probe=87076627c9) | Jan 04, 2021 |
| HP            | ProBook 6475b               | [31a4449ada](https://linux-hardware.org/?probe=31a4449ada) | Dec 30, 2020 |
| HP            | EliteBook 745 G6            | [abbb1bd093](https://linux-hardware.org/?probe=abbb1bd093) | Dec 28, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [a37f3f2e39](https://linux-hardware.org/?probe=a37f3f2e39) | Dec 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7deeb9d310](https://linux-hardware.org/?probe=7deeb9d310) | Dec 28, 2020 |
| Toshiba       | Satellite Pro L770-14H      | [82de56046c](https://linux-hardware.org/?probe=82de56046c) | Dec 27, 2020 |
| Acer          | Aspire 5715Z                | [8e6e0fd1c6](https://linux-hardware.org/?probe=8e6e0fd1c6) | Dec 24, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [0405731f25](https://linux-hardware.org/?probe=0405731f25) | Dec 23, 2020 |
| Toshiba       | Satellite P70-B             | [ec3a105576](https://linux-hardware.org/?probe=ec3a105576) | Dec 23, 2020 |
| Chuwi         | AeroBook                    | [94ca964c09](https://linux-hardware.org/?probe=94ca964c09) | Dec 21, 2020 |
| Chuwi         | AeroBook                    | [2639bb9e02](https://linux-hardware.org/?probe=2639bb9e02) | Dec 20, 2020 |
| Acer          | Aspire E1-570G              | [54c4be3905](https://linux-hardware.org/?probe=54c4be3905) | Dec 19, 2020 |
| HP            | HDX18                       | [933b4f749c](https://linux-hardware.org/?probe=933b4f749c) | Dec 18, 2020 |
| Lenovo        | ThinkPad X201 3680U18       | [ad31517eff](https://linux-hardware.org/?probe=ad31517eff) | Dec 18, 2020 |
| HP            | ProBook 6475b               | [c00a760aca](https://linux-hardware.org/?probe=c00a760aca) | Dec 18, 2020 |
| ASUSTek       | M51Vr                       | [a389e8ebce](https://linux-hardware.org/?probe=a389e8ebce) | Dec 18, 2020 |
| Toshiba       | TECRA R840                  | [731c5ca5c0](https://linux-hardware.org/?probe=731c5ca5c0) | Dec 16, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [ea3546c2f4](https://linux-hardware.org/?probe=ea3546c2f4) | Dec 16, 2020 |
| HP            | OMEN by Laptop 15-dc0xxx    | [3da605fec6](https://linux-hardware.org/?probe=3da605fec6) | Dec 14, 2020 |
| Samsung       | 530U4E/540U4E               | [415b67ede5](https://linux-hardware.org/?probe=415b67ede5) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| HP            | ProBook 6475b               | [e9ec659df5](https://linux-hardware.org/?probe=e9ec659df5) | Dec 07, 2020 |
| PC Special... | GK5NR0O                     | [1dfbed1284](https://linux-hardware.org/?probe=1dfbed1284) | Dec 05, 2020 |
| Acer          | Aspire ES1-512              | [575ce0ade3](https://linux-hardware.org/?probe=575ce0ade3) | Dec 04, 2020 |
| HP            | EliteBook 2560p             | [704777ce16](https://linux-hardware.org/?probe=704777ce16) | Dec 03, 2020 |
| Fujitsu       | STYLISTIC Q704              | [caa54ddfda](https://linux-hardware.org/?probe=caa54ddfda) | Dec 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [bb94d818b6](https://linux-hardware.org/?probe=bb94d818b6) | Nov 27, 2020 |
| HP            | OMEN by Laptop              | [0aa60b7f1f](https://linux-hardware.org/?probe=0aa60b7f1f) | Nov 27, 2020 |
| HP            | Laptop 15s-eq0xxx           | [4932c526f1](https://linux-hardware.org/?probe=4932c526f1) | Nov 26, 2020 |
| HUAWEI        | WRT-WX9                     | [a247637afb](https://linux-hardware.org/?probe=a247637afb) | Nov 23, 2020 |
| Toshiba       | Satellite L40               | [6dcbbd7118](https://linux-hardware.org/?probe=6dcbbd7118) | Nov 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [19118ea389](https://linux-hardware.org/?probe=19118ea389) | Nov 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [0429ace281](https://linux-hardware.org/?probe=0429ace281) | Nov 21, 2020 |
| ASUSTek       | X540LJ                      | [57ffeceb02](https://linux-hardware.org/?probe=57ffeceb02) | Nov 21, 2020 |
| Lenovo        | ThinkPad T430 2349V4B       | [989a5dd973](https://linux-hardware.org/?probe=989a5dd973) | Nov 20, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 137       | 12.45%  |
| Ubuntu 18.04                 | 87        | 7.91%   |
| Ubuntu 22.04                 | 59        | 5.36%   |
| OpenMandriva 4.3             | 32        | 2.91%   |
| Zorin 16                     | 24        | 2.18%   |
| Zorin 15                     | 24        | 2.18%   |
| Pop!_OS 22.04                | 24        | 2.18%   |
| OpenMandriva 4.2             | 21        | 1.91%   |
| Debian 11                    | 21        | 1.91%   |
| Arch Rolling                 | 20        | 1.82%   |
| KDE neon 20.04               | 19        | 1.73%   |
| Pop!_OS 20.04                | 18        | 1.64%   |
| Linux Mint 20.3              | 18        | 1.64%   |
| Debian 10                    | 17        | 1.55%   |
| Fedora 34                    | 16        | 1.45%   |
| Ubuntu 19.10                 | 14        | 1.27%   |
| Linux Mint 20.1              | 14        | 1.27%   |
| Pop!_OS 21.04                | 13        | 1.18%   |
| Manjaro                      | 13        | 1.18%   |
| Linux Mint 19.3              | 13        | 1.18%   |
| Arch                         | 13        | 1.18%   |
| Xubuntu 20.04                | 12        | 1.09%   |
| Ubuntu 21.10                 | 12        | 1.09%   |
| Ubuntu 19.04                 | 12        | 1.09%   |
| Pop!_OS 20.10                | 12        | 1.09%   |
| OpenMandriva 4.50            | 12        | 1.09%   |
| Fedora 38                    | 12        | 1.09%   |
| Fedora 36                    | 12        | 1.09%   |
| Linux Mint 20                | 11        | 1%      |
| Fedora 33                    | 11        | 1%      |
| Xubuntu 18.04                | 10        | 0.91%   |
| OpenMandriva 23.01           | 10        | 0.91%   |
| Linux Mint 21                | 10        | 0.91%   |
| Fedora 37                    | 10        | 0.91%   |
| Ubuntu 20.10                 | 9         | 0.82%   |
| Pop!_OS 21.10                | 9         | 0.82%   |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 0.82%   |
| Linux Mint 21.1              | 9         | 0.82%   |
| Linux Mint 19.1              | 9         | 0.82%   |
| Fedora 35                    | 8         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 338       | 32.28%  |
| Linux Mint       | 92        | 8.79%   |
| OpenMandriva     | 77        | 7.35%   |
| Pop!_OS          | 75        | 7.16%   |
| Fedora           | 70        | 6.69%   |
| Zorin            | 48        | 4.58%   |
| Debian           | 45        | 4.3%    |
| Manjaro          | 34        | 3.25%   |
| Arch             | 34        | 3.25%   |
| KDE neon         | 32        | 3.06%   |
| Endless          | 32        | 3.06%   |
| Xubuntu          | 24        | 2.29%   |
| Elementary       | 15        | 1.43%   |
| Kubuntu          | 14        | 1.34%   |
| ROSA             | 12        | 1.15%   |
| openSUSE         | 12        | 1.15%   |
| ArcoLinux        | 7         | 0.67%   |
| Ubuntu Unity     | 6         | 0.57%   |
| Ubuntu MATE      | 5         | 0.48%   |
| Slackware        | 5         | 0.48%   |
| Nobara           | 5         | 0.48%   |
| Lubuntu          | 5         | 0.48%   |
| LMDE             | 5         | 0.48%   |
| Gentoo           | 5         | 0.48%   |
| Kali             | 4         | 0.38%   |
| EndeavourOS      | 4         | 0.38%   |
| Clear Linux      | 4         | 0.38%   |
| Ubuntu Budgie    | 3         | 0.29%   |
| MX               | 3         | 0.29%   |
| Devuan           | 3         | 0.29%   |
| TUXEDO OS        | 2         | 0.19%   |
| SteamOS          | 2         | 0.19%   |
| Peppermint       | 2         | 0.19%   |
| Parrot           | 2         | 0.19%   |
| org.kde.Platform | 2         | 0.19%   |
| Artix            | 2         | 0.19%   |
| Xero             | 1         | 0.1%    |
| UbuntuDDE        | 1         | 0.1%    |
| RHEL             | 1         | 0.1%    |
| Reborn OS        | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 25        | 2.09%   |
| 5.4.0-42-generic         | 24        | 2.01%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.67%   |
| 5.15.0-56-generic        | 13        | 1.09%   |
| 5.3.0-46-generic         | 12        | 1%      |
| 5.14.14-desktop-1omv4050 | 12        | 1%      |
| 5.4.0-29-generic         | 11        | 0.92%   |
| 5.15.0-52-generic        | 11        | 0.92%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.84%   |
| 5.4.0-58-generic         | 10        | 0.84%   |
| 5.4.0-52-generic         | 10        | 0.84%   |
| 5.15.0-48-generic        | 10        | 0.84%   |
| 5.15.0-46-generic        | 10        | 0.84%   |
| 5.11.0-38-generic        | 10        | 0.84%   |
| 6.2.6-76060206-generic   | 9         | 0.75%   |
| 5.3.0-28-generic         | 9         | 0.75%   |
| 5.15.0-41-generic        | 9         | 0.75%   |
| 4.18.0-15-generic        | 9         | 0.75%   |
| 5.4.0-7634-generic       | 8         | 0.67%   |
| 5.4.0-26-generic         | 8         | 0.67%   |
| 5.0.0-25-generic         | 8         | 0.67%   |
| 5.4.0-31-generic         | 7         | 0.59%   |
| 5.19.0-76051900-generic  | 7         | 0.59%   |
| 5.15.0-58-generic        | 7         | 0.59%   |
| 5.13.0-39-generic        | 7         | 0.59%   |
| 5.11.0-43-generic        | 7         | 0.59%   |
| 5.0.0-37-generic         | 7         | 0.59%   |
| 4.18.0-25-generic        | 7         | 0.59%   |
| 4.15.0-46-generic        | 7         | 0.59%   |
| 6.2.6-desktop-1omv2390   | 6         | 0.5%    |
| 5.8.0-63-generic         | 6         | 0.5%    |
| 5.4.0-91-generic         | 6         | 0.5%    |
| 5.4.0-65-generic         | 6         | 0.5%    |
| 5.3.0-40-generic         | 6         | 0.5%    |
| 5.19.0-41-generic        | 6         | 0.5%    |
| 5.11.0-7620-generic      | 6         | 0.5%    |
| 5.10.0-21-amd64          | 6         | 0.5%    |
| 6.2.0-20-generic         | 5         | 0.42%   |
| 5.8.0-7642-generic       | 5         | 0.42%   |
| 5.8.0-55-generic         | 5         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 186       | 16.46%  |
| 5.15.0  | 86        | 7.61%   |
| 4.15.0  | 67        | 5.93%   |
| 5.8.0   | 63        | 5.58%   |
| 5.11.0  | 60        | 5.31%   |
| 5.3.0   | 55        | 4.87%   |
| 5.13.0  | 49        | 4.34%   |
| 5.19.0  | 43        | 3.81%   |
| 5.0.0   | 38        | 3.36%   |
| 4.18.0  | 34        | 3.01%   |
| 5.10.0  | 28        | 2.48%   |
| 5.16.7  | 25        | 2.21%   |
| 5.10.14 | 21        | 1.86%   |
| 4.19.0  | 17        | 1.5%    |
| 6.2.6   | 15        | 1.33%   |
| 6.1.1   | 12        | 1.06%   |
| 5.14.14 | 12        | 1.06%   |
| 6.2.0   | 11        | 0.97%   |
| 6.1.0   | 7         | 0.62%   |
| 6.2.14  | 5         | 0.44%   |
| 4.4.0   | 5         | 0.44%   |
| 6.3.8   | 4         | 0.35%   |
| 6.2.15  | 4         | 0.35%   |
| 6.0.12  | 4         | 0.35%   |
| 6.0.0   | 4         | 0.35%   |
| 5.6.0   | 4         | 0.35%   |
| 5.14.0  | 4         | 0.35%   |
| 5.11.12 | 4         | 0.35%   |
| 6.3.2   | 3         | 0.27%   |
| 6.1.12  | 3         | 0.27%   |
| 5.9.0   | 3         | 0.27%   |
| 5.8.16  | 3         | 0.27%   |
| 5.7.9   | 3         | 0.27%   |
| 5.19.5  | 3         | 0.27%   |
| 5.16.15 | 3         | 0.27%   |
| 5.16.11 | 3         | 0.27%   |
| 5.16.0  | 3         | 0.27%   |
| 5.15.15 | 3         | 0.27%   |
| 5.15.11 | 3         | 0.27%   |
| 5.14.16 | 3         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 196       | 17.48%  |
| 5.15    | 113       | 10.08%  |
| 5.8     | 77        | 6.87%   |
| 5.11    | 68        | 6.07%   |
| 4.15    | 67        | 5.98%   |
| 5.10    | 64        | 5.71%   |
| 5.3     | 58        | 5.17%   |
| 5.19    | 55        | 4.91%   |
| 5.13    | 54        | 4.82%   |
| 5.16    | 43        | 3.84%   |
| 6.2     | 41        | 3.66%   |
| 5.0     | 39        | 3.48%   |
| 6.1     | 36        | 3.21%   |
| 4.18    | 35        | 3.12%   |
| 5.14    | 25        | 2.23%   |
| 4.19    | 20        | 1.78%   |
| 6.0     | 19        | 1.69%   |
| 6.3     | 18        | 1.61%   |
| 5.12    | 16        | 1.43%   |
| 4.9     | 12        | 1.07%   |
| 5.9     | 10        | 0.89%   |
| 5.7     | 10        | 0.89%   |
| 5.6     | 10        | 0.89%   |
| 5.17    | 10        | 0.89%   |
| 5.5     | 6         | 0.54%   |
| 5.18    | 6         | 0.54%   |
| 4.4     | 5         | 0.45%   |
| 6.4     | 2         | 0.18%   |
| 5.2     | 2         | 0.18%   |
| 4.12    | 1         | 0.09%   |
| 4.1     | 1         | 0.09%   |
| 3.10    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 964       | 95.35%  |
| i686   | 47        | 4.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 484       | 45.75%  |
| KDE5             | 175       | 16.54%  |
| Unknown          | 138       | 13.04%  |
| XFCE             | 74        | 6.99%   |
| X-Cinnamon       | 72        | 6.81%   |
| MATE             | 19        | 1.8%    |
| KDE              | 18        | 1.7%    |
| Pantheon         | 13        | 1.23%   |
| i3               | 10        | 0.95%   |
| Cinnamon         | 10        | 0.95%   |
| KDE4             | 9         | 0.85%   |
| Unity            | 7         | 0.66%   |
| Budgie           | 7         | 0.66%   |
| LXQt             | 5         | 0.47%   |
| LXDE             | 4         | 0.38%   |
| Deepin           | 3         | 0.28%   |
| GNOME Flashback  | 2         | 0.19%   |
| DWM              | 2         | 0.19%   |
| awesome          | 2         | 0.19%   |
| Openbox          | 1         | 0.09%   |
| lightdm-xsession | 1         | 0.09%   |
| fluxbox          | 1         | 0.09%   |
| Cutefish         | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 806       | 77.8%   |
| Wayland | 162       | 15.64%  |
| Unknown | 66        | 6.37%   |
| Tty     | 2         | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 569       | 54.29%  |
| SDDM    | 141       | 13.45%  |
| GDM3    | 114       | 10.88%  |
| GDM     | 104       | 9.92%   |
| LightDM | 78        | 7.44%   |
| TDM     | 28        | 2.67%   |
| KDM     | 9         | 0.86%   |
| XDM     | 3         | 0.29%   |
| SLiM    | 1         | 0.1%    |
| GREETD  | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_PT   | 408       | 39.27%  |
| en_US   | 378       | 36.38%  |
| Unknown | 134       | 12.9%   |
| en_GB   | 61        | 5.87%   |
| pt_BR   | 19        | 1.83%   |
| C       | 16        | 1.54%   |
| fr_FR   | 4         | 0.38%   |
| en_IE   | 4         | 0.38%   |
| de_DE   | 4         | 0.38%   |
| ru_RU   | 2         | 0.19%   |
| POSIX   | 2         | 0.19%   |
| it_IT   | 2         | 0.19%   |
| es_ES   | 2         | 0.19%   |
| sk_SK   | 1         | 0.1%    |
| en_IN   | 1         | 0.1%    |
| Default | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 531       | 51.21%  |
| EFI  | 506       | 48.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 798       | 77.55%  |
| Btrfs    | 88        | 8.55%   |
| Overlay  | 63        | 6.12%   |
| Unknown  | 44        | 4.28%   |
| Tmpfs    | 15        | 1.46%   |
| Zfs      | 7         | 0.68%   |
| Xfs      | 7         | 0.68%   |
| Ext2     | 4         | 0.39%   |
| Ext3     | 2         | 0.19%   |
| Reiserfs | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 602       | 58.39%  |
| GPT     | 342       | 33.17%  |
| MBR     | 87        | 8.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 915       | 89.53%  |
| Yes       | 107       | 10.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 736       | 71.73%  |
| Yes       | 290       | 28.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 188       | 18.61%  |
| Hewlett-Packard     | 188       | 18.61%  |
| ASUSTek Computer    | 176       | 17.43%  |
| Acer                | 101       | 10%     |
| Toshiba             | 80        | 7.92%   |
| Dell                | 57        | 5.64%   |
| Sony                | 44        | 4.36%   |
| Apple               | 26        | 2.57%   |
| MSI                 | 25        | 2.48%   |
| HUAWEI              | 22        | 2.18%   |
| Samsung Electronics | 14        | 1.39%   |
| Notebook            | 9         | 0.89%   |
| TUXEDO              | 6         | 0.59%   |
| Packard Bell        | 6         | 0.59%   |
| Fujitsu             | 6         | 0.59%   |
| Chuwi               | 5         | 0.5%    |
| Unknown             | 4         | 0.4%    |
| Teclast             | 3         | 0.3%    |
| Phoenix/SiS         | 3         | 0.3%    |
| LG Electronics      | 3         | 0.3%    |
| Intel               | 3         | 0.3%    |
| Gigabyte Technology | 3         | 0.3%    |
| eMachines           | 3         | 0.3%    |
| Clevo               | 3         | 0.3%    |
| Valve               | 2         | 0.2%    |
| SLIMBOOK            | 2         | 0.2%    |
| Positivo            | 2         | 0.2%    |
| OBSIDIAN-PC         | 2         | 0.2%    |
| INSYS               | 2         | 0.2%    |
| Fujitsu Siemens     | 2         | 0.2%    |
| Alienware           | 2         | 0.2%    |
| Timi                | 1         | 0.1%    |
| Thomson             | 1         | 0.1%    |
| System76            | 1         | 0.1%    |
| Standard            | 1         | 0.1%    |
| Schenker            | 1         | 0.1%    |
| Qilive              | 1         | 0.1%    |
| Purism              | 1         | 0.1%    |
| PC Specialist       | 1         | 0.1%    |
| Medion              | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Sony VGN-FZ31Z                         | 21        | 2.08%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 14        | 1.39%   |
| Toshiba Satellite C660                 | 8         | 0.79%   |
| HP Pavilion g6                         | 8         | 0.79%   |
| HP Pavilion dv6                        | 8         | 0.79%   |
| HP G62                                 | 8         | 0.79%   |
| Unknown                                | 8         | 0.79%   |
| Lenovo Legion 5 15ACH6H 82JU           | 7         | 0.69%   |
| HP Notebook                            | 7         | 0.69%   |
| Toshiba Satellite L650                 | 6         | 0.59%   |
| HP Pavilion Notebook                   | 5         | 0.5%    |
| ASUS X555LJ                            | 5         | 0.5%    |
| ASUS X555LD                            | 5         | 0.5%    |
| ASUS X541UV                            | 5         | 0.5%    |
| Acer Extensa 5620                      | 5         | 0.5%    |
| Toshiba Satellite L500                 | 4         | 0.4%    |
| Toshiba Satellite L40                  | 4         | 0.4%    |
| Toshiba Satellite A200                 | 4         | 0.4%    |
| Lenovo Y520-15IKBN 80WK                | 4         | 0.4%    |
| Lenovo IdeaPad 320-15AST 80XV          | 4         | 0.4%    |
| Lenovo G50-45 80E3                     | 4         | 0.4%    |
| HUAWEI NBLK-WAX9X                      | 4         | 0.4%    |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 4         | 0.4%    |
| HP OMEN by Laptop 15-dc0xxx            | 4         | 0.4%    |
| HP Compaq Presario CQ60                | 4         | 0.4%    |
| ASUS X541UJ                            | 4         | 0.4%    |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 4         | 0.4%    |
| ASUS VivoBook 15_ASUS Laptop X507LA    | 4         | 0.4%    |
| Acer Extensa 5635ZG                    | 4         | 0.4%    |
| Acer Aspire ES1-520                    | 4         | 0.4%    |
| Acer Aspire E5-551G                    | 4         | 0.4%    |
| Toshiba Satellite L50D-B               | 3         | 0.3%    |
| MSI Modern 14 A10RB                    | 3         | 0.3%    |
| Lenovo Legion 5 15ARH05 82B5           | 3         | 0.3%    |
| Intel powered classmate PC             | 3         | 0.3%    |
| HUAWEI WRT-WX9                         | 3         | 0.3%    |
| HP Pavilion 15                         | 3         | 0.3%    |
| HP OMEN by Laptop                      | 3         | 0.3%    |
| HP EliteBook 840 G3                    | 3         | 0.3%    |
| HP Compaq Presario CQ61                | 3         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 90        | 8.91%   |
| Acer Aspire           | 80        | 7.92%   |
| Toshiba Satellite     | 69        | 6.83%   |
| HP Pavilion           | 57        | 5.64%   |
| Lenovo IdeaPad        | 55        | 5.45%   |
| ASUS VivoBook         | 35        | 3.47%   |
| HP EliteBook          | 28        | 2.77%   |
| Dell Latitude         | 27        | 2.67%   |
| Sony VGN-FZ31Z        | 21        | 2.08%   |
| Lenovo Legion         | 18        | 1.78%   |
| HP Compaq             | 17        | 1.68%   |
| HP ProBook            | 15        | 1.49%   |
| HP Laptop             | 14        | 1.39%   |
| Dell XPS              | 14        | 1.39%   |
| HP OMEN               | 10        | 0.99%   |
| Dell Inspiron         | 10        | 0.99%   |
| ASUS ZenBook          | 10        | 0.99%   |
| Acer Extensa          | 9         | 0.89%   |
| HP G62                | 8         | 0.79%   |
| ASUS ROG              | 8         | 0.79%   |
| Unknown               | 8         | 0.79%   |
| HP Notebook           | 7         | 0.69%   |
| HP ENVY               | 7         | 0.69%   |
| Packard Bell EasyNote | 6         | 0.59%   |
| MSI Modern            | 6         | 0.59%   |
| ASUS TUF              | 6         | 0.59%   |
| Acer Nitro            | 6         | 0.59%   |
| Fujitsu LIFEBOOK      | 5         | 0.5%    |
| Dell Precision        | 5         | 0.5%    |
| ASUS X555LJ           | 5         | 0.5%    |
| ASUS X555LD           | 5         | 0.5%    |
| ASUS X541UV           | 5         | 0.5%    |
| Toshiba PORTEGE       | 4         | 0.4%    |
| Lenovo Yoga           | 4         | 0.4%    |
| Lenovo Y520-15IKBN    | 4         | 0.4%    |
| Lenovo G50-45         | 4         | 0.4%    |
| HUAWEI NBLK-WAX9X     | 4         | 0.4%    |
| HP Stream             | 4         | 0.4%    |
| HP 15                 | 4         | 0.4%    |
| ASUS X541UJ           | 4         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 97        | 9.6%    |
| 2019    | 91        | 9.01%   |
| 2018    | 82        | 8.12%   |
| 2010    | 80        | 7.92%   |
| 2015    | 65        | 6.44%   |
| 2013    | 65        | 6.44%   |
| 2014    | 62        | 6.14%   |
| 2021    | 60        | 5.94%   |
| 2007    | 59        | 5.84%   |
| 2008    | 54        | 5.35%   |
| 2016    | 53        | 5.25%   |
| 2017    | 51        | 5.05%   |
| 2011    | 50        | 4.95%   |
| 2012    | 46        | 4.55%   |
| 2009    | 45        | 4.46%   |
| 2022    | 29        | 2.87%   |
| 2006    | 10        | 0.99%   |
| 2005    | 7         | 0.69%   |
| 2023    | 2         | 0.2%    |
| Unknown | 2         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1010      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 925       | 89.89%  |
| Enabled  | 104       | 10.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1006      | 99.6%   |
| Yes  | 4         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 279       | 27.38%  |
| 4.01-8.0    | 262       | 25.71%  |
| 8.01-16.0   | 161       | 15.8%   |
| 16.01-24.0  | 138       | 13.54%  |
| 32.01-64.0  | 70        | 6.87%   |
| 1.01-2.0    | 66        | 6.48%   |
| 2.01-3.0    | 18        | 1.77%   |
| 0.51-1.0    | 11        | 1.08%   |
| 64.01-256.0 | 8         | 0.79%   |
| 24.01-32.0  | 6         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 418       | 37.62%  |
| 2.01-3.0   | 247       | 22.23%  |
| 4.01-8.0   | 166       | 14.94%  |
| 3.01-4.0   | 137       | 12.33%  |
| 0.51-1.0   | 86        | 7.74%   |
| 8.01-16.0  | 42        | 3.78%   |
| 16.01-24.0 | 7         | 0.63%   |
| 0.01-0.5   | 7         | 0.63%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 764       | 74.25%  |
| 2      | 223       | 21.67%  |
| 3      | 28        | 2.72%   |
| 0      | 10        | 0.97%   |
| 4      | 3         | 0.29%   |
| 5      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 649       | 64.19%  |
| Yes       | 362       | 35.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 837       | 82.38%  |
| No        | 179       | 17.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 987       | 97.72%  |
| No        | 23        | 2.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 737       | 72.25%  |
| No        | 283       | 27.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Portugal | 1010      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lisbon                  | 245       | 22.69%  |
| Porto                   | 101       | 9.35%   |
| Funchal                 | 31        | 2.87%   |
| Vila Nova de Gaia       | 30        | 2.78%   |
| Amadora                 | 26        | 2.41%   |
| Aveiro                  | 18        | 1.67%   |
| Braga                   | 17        | 1.57%   |
| Coimbra                 | 16        | 1.48%   |
| Setúbal                | 15        | 1.39%   |
| Cascais                 | 15        | 1.39%   |
| Loures                  | 14        | 1.3%    |
| Guimaraes               | 13        | 1.2%    |
| Leiria                  | 12        | 1.11%   |
| Faro                    | 12        | 1.11%   |
| Bragança               | 11        | 1.02%   |
| Almada                  | 11        | 1.02%   |
| Sintra                  | 9         | 0.83%   |
| Mem Martins             | 9         | 0.83%   |
| Santarém               | 8         | 0.74%   |
| Póvoa de Varzim        | 8         | 0.74%   |
| Feira                   | 8         | 0.74%   |
| Alverca do Ribatejo     | 8         | 0.74%   |
| Viana do Castelo        | 7         | 0.65%   |
| Santo Tirso             | 7         | 0.65%   |
| Odivelas                | 7         | 0.65%   |
| Carnaxide               | 7         | 0.65%   |
| Barreiro                | 7         | 0.65%   |
| Barcelos                | 7         | 0.65%   |
| Viseu                   | 6         | 0.56%   |
| Portimao                | 6         | 0.56%   |
| Matosinhos Municipality | 6         | 0.56%   |
| Maia                    | 6         | 0.56%   |
| Evora                   | 6         | 0.56%   |
| Cacem                   | 6         | 0.56%   |
| Águeda Municipality    | 6         | 0.56%   |
| Vila Nova de Famalicao  | 5         | 0.46%   |
| Vila do Conde           | 5         | 0.46%   |
| Torres Vedras           | 5         | 0.46%   |
| Seixal                  | 5         | 0.46%   |
| Lagos                   | 5         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 185       | 239    | 15.05%  |
| WDC                         | 127       | 168    | 10.33%  |
| Toshiba                     | 127       | 148    | 10.33%  |
| Seagate                     | 122       | 149    | 9.93%   |
| Kingston                    | 95        | 110    | 7.73%   |
| Unknown                     | 73        | 105    | 5.94%   |
| Sandisk                     | 71        | 85     | 5.78%   |
| Crucial                     | 48        | 60     | 3.91%   |
| Hitachi                     | 41        | 44     | 3.34%   |
| HGST                        | 41        | 51     | 3.34%   |
| SK hynix                    | 34        | 39     | 2.77%   |
| Intel                       | 34        | 56     | 2.77%   |
| Micron Technology           | 30        | 35     | 2.44%   |
| Fujitsu                     | 18        | 19     | 1.46%   |
| KIOXIA                      | 16        | 25     | 1.3%    |
| Apple                       | 11        | 11     | 0.9%    |
| GOODRAM                     | 9         | 9      | 0.73%   |
| S3+                         | 8         | 19     | 0.65%   |
| JMicron Technology          | 8         | 8      | 0.65%   |
| China                       | 8         | 10     | 0.65%   |
| A-DATA Technology           | 7         | 7      | 0.57%   |
| LITEON                      | 6         | 7      | 0.49%   |
| Kingston Technology Company | 6         | 6      | 0.49%   |
| Transcend                   | 5         | 6      | 0.41%   |
| Silicon Motion              | 5         | 7      | 0.41%   |
| Phison Electronics          | 5         | 5      | 0.41%   |
| Emtec                       | 5         | 6      | 0.41%   |
| PNY                         | 4         | 5      | 0.33%   |
| Phison                      | 4         | 4      | 0.33%   |
| KIOXIA-EXCERIA              | 4         | 4      | 0.33%   |
| BlueRay                     | 4         | 5      | 0.33%   |
| Unknown                     | 4         | 4      | 0.33%   |
| USB                         | 3         | 3      | 0.24%   |
| Team                        | 3         | 4      | 0.24%   |
| OCZ                         | 3         | 3      | 0.24%   |
| Netac                       | 3         | 3      | 0.24%   |
| Micron/Crucial Technology   | 3         | 6      | 0.24%   |
| Maxtor                      | 3         | 10     | 0.24%   |
| Union Memory (Shenzhen)     | 2         | 5      | 0.16%   |
| UMIS                        | 2         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 19        | 1.49%   |
| HGST HTS721010A9E630 1TB                            | 18        | 1.42%   |
| Toshiba MQ01ABD100 1TB                              | 17        | 1.34%   |
| Unknown MMC Card  32GB                              | 15        | 1.18%   |
| Seagate ST500LT012-1DG142 500GB                     | 15        | 1.18%   |
| Kingston SA400S37120G 120GB SSD                     | 15        | 1.18%   |
| Unknown MMC64G  64GB                                | 14        | 1.1%    |
| Crucial CT240M500SSD1 240GB                         | 14        | 1.1%    |
| Unknown MMC Card  64GB                              | 13        | 1.02%   |
| Toshiba MQ01ABF050 500GB                            | 13        | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB                      | 13        | 1.02%   |
| Kingston SV300S37A120G 120GB SSD                    | 12        | 0.94%   |
| SanDisk NVMe SSD Drive 512GB                        | 11        | 0.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 11        | 0.87%   |
| Kingston SA400S37240G 240GB SSD                     | 10        | 0.79%   |
| Seagate ST9500325AS 500GB                           | 9         | 0.71%   |
| Samsung SSD 850 EVO 500GB                           | 9         | 0.71%   |
| Samsung NVMe SSD Drive 512GB                        | 8         | 0.63%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 7         | 0.55%   |
| Toshiba TR200 240GB SSD                             | 7         | 0.55%   |
| Toshiba MQ04ABF100 1TB                              | 7         | 0.55%   |
| SanDisk NVMe SSD Drive 256GB                        | 7         | 0.55%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.55%   |
| Samsung NVMe SSD Drive 256GB                        | 7         | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 7         | 0.55%   |
| Kingston NVMe SSD Drive 512GB                       | 7         | 0.55%   |
| HGST HTS541010A9E680 1TB                            | 7         | 0.55%   |
| Crucial CT240BX500SSD1 240GB                        | 7         | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 6         | 0.47%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 6         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 6         | 0.47%   |
| Unknown MMC Card  128GB                             | 6         | 0.47%   |
| SK hynix NVMe SSD Drive 512GB                       | 6         | 0.47%   |
| SK hynix NVMe SSD Drive 256GB                       | 6         | 0.47%   |
| SanDisk NVMe SSD Drive 1024GB                       | 6         | 0.47%   |
| Samsung SSD 860 QVO 1TB                             | 6         | 0.47%   |
| Samsung NVMe SSD Drive 1024GB                       | 6         | 0.47%   |
| Micron NVMe SSD Drive 512GB                         | 6         | 0.47%   |
| Unknown MMC Card  16GB                              | 5         | 0.39%   |
| Seagate ST9320325AS 320GB                           | 5         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 121       | 144    | 29.23%  |
| Toshiba             | 87        | 106    | 21.01%  |
| WDC                 | 86        | 102    | 20.77%  |
| Hitachi             | 41        | 44     | 9.9%    |
| HGST                | 41        | 51     | 9.9%    |
| Fujitsu             | 18        | 19     | 4.35%   |
| Samsung Electronics | 12        | 12     | 2.9%    |
| JMicron Technology  | 5         | 5      | 1.21%   |
| USB3.0              | 1         | 1      | 0.24%   |
| Intenso             | 1         | 1      | 0.24%   |
| ASMedia             | 1         | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 76        | 94     | 19.24%  |
| Kingston            | 75        | 88     | 18.99%  |
| Crucial             | 47        | 58     | 11.9%   |
| SanDisk             | 28        | 34     | 7.09%   |
| Toshiba             | 20        | 22     | 5.06%   |
| WDC                 | 16        | 18     | 4.05%   |
| Apple               | 10        | 10     | 2.53%   |
| Intel               | 9         | 13     | 2.28%   |
| GOODRAM             | 9         | 9      | 2.28%   |
| S3+                 | 8         | 19     | 2.03%   |
| Micron Technology   | 8         | 12     | 2.03%   |
| China               | 8         | 10     | 2.03%   |
| SK hynix            | 7         | 7      | 1.77%   |
| A-DATA Technology   | 7         | 7      | 1.77%   |
| Transcend           | 5         | 6      | 1.27%   |
| Emtec               | 5         | 6      | 1.27%   |
| LITEON              | 4         | 5      | 1.01%   |
| KIOXIA-EXCERIA      | 4         | 4      | 1.01%   |
| BlueRay             | 4         | 5      | 1.01%   |
| USB                 | 3         | 3      | 0.76%   |
| Team                | 3         | 4      | 0.76%   |
| PNY                 | 3         | 4      | 0.76%   |
| OCZ                 | 3         | 3      | 0.76%   |
| Netac               | 3         | 3      | 0.76%   |
| Maxtor              | 3         | 10     | 0.76%   |
| TCSUNBOW            | 2         | 2      | 0.51%   |
| Seagate             | 2         | 4      | 0.51%   |
| Plextor             | 2         | 2      | 0.51%   |
| KingDian            | 2         | 2      | 0.51%   |
| Hewlett-Packard     | 2         | 2      | 0.51%   |
| Unknown             | 2         | 2      | 0.51%   |
| VNYEZ               | 1         | 1      | 0.25%   |
| Verbatim            | 1         | 1      | 0.25%   |
| Vaseky              | 1         | 1      | 0.25%   |
| Teclast             | 1         | 1      | 0.25%   |
| TEAM T25            | 1         | 1      | 0.25%   |
| OSC                 | 1         | 1      | 0.25%   |
| LITEONIT            | 1         | 1      | 0.25%   |
| Lexar               | 1         | 1      | 0.25%   |
| KingSpec            | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 406       | 486    | 34.47%  |
| SSD     | 368       | 483    | 31.24%  |
| NVMe    | 319       | 449    | 27.08%  |
| MMC     | 72        | 106    | 6.11%   |
| Unknown | 13        | 14     | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 695       | 944    | 62.11%  |
| NVMe | 319       | 448    | 28.51%  |
| MMC  | 72        | 106    | 6.43%   |
| SAS  | 33        | 40     | 2.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 550       | 720    | 73.53%  |
| 0.51-1.0   | 185       | 234    | 24.73%  |
| 1.01-2.0   | 12        | 14     | 1.6%    |
| 4.01-10.0  | 1         | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 315       | 29.89%  |
| 251-500        | 272       | 25.81%  |
| 501-1000       | 139       | 13.19%  |
| 51-100         | 86        | 8.16%   |
| 1-20           | 76        | 7.21%   |
| 1001-2000      | 59        | 5.6%    |
| 21-50          | 48        | 4.55%   |
| Unknown        | 26        | 2.47%   |
| More than 3000 | 19        | 1.8%    |
| 2001-3000      | 14        | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 447       | 40.93%  |
| 21-50          | 227       | 20.79%  |
| 101-250        | 140       | 12.82%  |
| 51-100         | 120       | 10.99%  |
| 251-500        | 73        | 6.68%   |
| 501-1000       | 30        | 2.75%   |
| Unknown        | 26        | 2.38%   |
| 1001-2000      | 21        | 1.92%   |
| More than 3000 | 6         | 0.55%   |
| 2001-3000      | 2         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Crucial CT240M500SSD1 240GB           | 14        | 15     | 18.92%  |
| Kingston SV300S37A120G 120GB SSD      | 6         | 6      | 8.11%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 2.7%    |
| Kingston SV300S37A240G 240GB SSD      | 2         | 2      | 2.7%    |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 2.7%    |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 2.7%    |
| China G521N256GB SSD                  | 2         | 3      | 2.7%    |
| WDC WD7500BPVX-60JC3T0 752GB          | 1         | 1      | 1.35%   |
| WDC WD5000BPVT-80HXZT1 500GB          | 1         | 1      | 1.35%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 1.35%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 1.35%   |
| WDC WD10JPVT-22A1YT0 1TB              | 1         | 1      | 1.35%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 1.35%   |
| VNYEZ SSD MSATA 128GB                 | 1         | 1      | 1.35%   |
| USB 3.1 1TB                           | 1         | 1      | 1.35%   |
| Toshiba Q300. 240GB SSD               | 1         | 1      | 1.35%   |
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 1.35%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.35%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.35%   |
| Toshiba MK7575GSX 752GB               | 1         | 1      | 1.35%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 1.35%   |
| Toshiba MK3276GSX 320GB               | 1         | 1      | 1.35%   |
| Toshiba MK2561GSYN 250GB              | 1         | 1      | 1.35%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 1         | 1      | 1.35%   |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1         | 1      | 1.35%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 1.35%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.35%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.35%   |
| Seagate ST9160310AS 160GB             | 1         | 2      | 1.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.35%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.35%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 1.35%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.35%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 1.35%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 1.35%   |
| Samsung Electronics HM320JI 320GB     | 1         | 1      | 1.35%   |
| Samsung Electronics HM251HI 250GB     | 1         | 1      | 1.35%   |
| Kingston SUV400S37240G 240GB SSD      | 1         | 1      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 14        | 15     | 18.92%  |
| Seagate             | 13        | 14     | 17.57%  |
| Kingston            | 9         | 9      | 12.16%  |
| Hitachi             | 9         | 9      | 12.16%  |
| Toshiba             | 8         | 8      | 10.81%  |
| WDC                 | 6         | 6      | 8.11%   |
| Samsung Electronics | 3         | 3      | 4.05%   |
| HGST                | 3         | 3      | 4.05%   |
| SK hynix            | 2         | 2      | 2.7%    |
| China               | 2         | 3      | 2.7%    |
| VNYEZ               | 1         | 1      | 1.35%   |
| USB                 | 1         | 1      | 1.35%   |
| SanDisk             | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| A-DATA Technology   | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 31.71%  |
| Hitachi             | 9         | 9      | 21.95%  |
| Toshiba             | 7         | 7      | 17.07%  |
| WDC                 | 6         | 6      | 14.63%  |
| HGST                | 3         | 3      | 7.32%   |
| Samsung Electronics | 2         | 2      | 4.88%   |
| Fujitsu             | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 42     | 55.41%  |
| SSD  | 33        | 35     | 44.59%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010B7E610 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 666       | 1014   | 63.25%  |
| Works    | 313       | 446    | 29.72%  |
| Malfunc  | 73        | 77     | 6.93%   |
| Failed   | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 679       | 59.15%  |
| AMD                              | 124       | 10.8%   |
| Samsung Electronics              | 106       | 9.23%   |
| SanDisk                          | 62        | 5.4%    |
| SK hynix                         | 25        | 2.18%   |
| Kingston Technology Company      | 25        | 2.18%   |
| Toshiba America Info Systems     | 22        | 1.92%   |
| Micron Technology                | 22        | 1.92%   |
| KIOXIA                           | 14        | 1.22%   |
| Nvidia                           | 13        | 1.13%   |
| Silicon Integrated Systems [SiS] | 12        | 1.05%   |
| Phison Electronics               | 10        | 0.87%   |
| Union Memory (Shenzhen)          | 6         | 0.52%   |
| Silicon Motion                   | 5         | 0.44%   |
| Micron/Crucial Technology        | 5         | 0.44%   |
| Lite-On Technology               | 5         | 0.44%   |
| JMicron Technology               | 4         | 0.35%   |
| Solid State Storage Technology   | 2         | 0.17%   |
| Lenovo                           | 2         | 0.17%   |
| Silicon Image                    | 1         | 0.09%   |
| Realtek Semiconductor            | 1         | 0.09%   |
| Marvell Technology Group         | 1         | 0.09%   |
| Enmotus                          | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 116       | 9.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 71        | 5.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 62        | 4.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 57        | 4.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 56        | 4.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 54        | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 53        | 4.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 49        | 3.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 45        | 3.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 44        | 3.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 2.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 25        | 1.97%   |
| Samsung NVMe SSD Controller 980                                                | 24        | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 24        | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller                            | 22        | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21        | 1.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 19        | 1.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 15        | 1.18%   |
| Intel SSD 660P Series                                                          | 15        | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 1.02%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 12        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 12        | 0.94%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 11        | 0.87%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 11        | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 11        | 0.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 10        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 10        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 0.71%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 9         | 0.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 9         | 0.71%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 8         | 0.63%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 8         | 0.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 8         | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 7         | 0.55%   |
| Phison PS5013 E13 NVMe Controller                                              | 7         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 705       | 58.17%  |
| NVMe | 320       | 26.4%   |
| IDE  | 121       | 9.98%   |
| RAID | 66        | 5.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 822       | 81.39%  |
| AMD    | 188       | 18.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 25        | 2.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 20        | 1.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 1.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.39%   |
| AMD 3020e with Radeon Graphics                | 14        | 1.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.29%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 1.19%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 11        | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 1.09%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 1.09%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.99%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 10        | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.89%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 9         | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.89%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.89%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 8         | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.79%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 8         | 0.79%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.79%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 0.79%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 7         | 0.69%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 7         | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.69%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 7         | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 247       | 24.46%  |
| Intel Core i5           | 194       | 19.21%  |
| Intel Core 2 Duo        | 83        | 8.22%   |
| Other                   | 79        | 7.82%   |
| Intel Core i3           | 67        | 6.63%   |
| AMD Ryzen 7             | 48        | 4.75%   |
| Intel Celeron           | 44        | 4.36%   |
| AMD Ryzen 5             | 39        | 3.86%   |
| Intel Atom              | 32        | 3.17%   |
| Intel Pentium Dual-Core | 25        | 2.48%   |
| Intel Pentium Dual      | 23        | 2.28%   |
| Intel Pentium           | 15        | 1.49%   |
| AMD A4                  | 14        | 1.39%   |
| Intel Genuine           | 13        | 1.29%   |
| AMD A8                  | 11        | 1.09%   |
| AMD A6                  | 11        | 1.09%   |
| Intel Core 2            | 9         | 0.89%   |
| AMD E2                  | 8         | 0.79%   |
| AMD Ryzen 9             | 7         | 0.69%   |
| AMD Ryzen 3             | 6         | 0.59%   |
| Intel Pentium M         | 5         | 0.5%    |
| AMD A10                 | 4         | 0.4%    |
| AMD E                   | 3         | 0.3%    |
| AMD Athlon              | 3         | 0.3%    |
| Intel Core m3           | 2         | 0.2%    |
| Intel Celeron M         | 2         | 0.2%    |
| AMD Ryzen 7 PRO         | 2         | 0.2%    |
| AMD Mobile Sempron      | 2         | 0.2%    |
| AMD E1                  | 2         | 0.2%    |
| Intel Core m7           | 1         | 0.1%    |
| Intel Core i9           | 1         | 0.1%    |
| Intel Celeron Dual-Core | 1         | 0.1%    |
| AMD Turion 64 X2 Mobile | 1         | 0.1%    |
| AMD Turion              | 1         | 0.1%    |
| AMD Ryzen 5 PRO         | 1         | 0.1%    |
| AMD Quad-Core           | 1         | 0.1%    |
| AMD Phenom II           | 1         | 0.1%    |
| AMD FX                  | 1         | 0.1%    |
| AMD Athlon 64 X2        | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 518       | 51.29%  |
| 4      | 325       | 32.18%  |
| 6      | 66        | 6.53%   |
| 8      | 54        | 5.35%   |
| 1      | 29        | 2.87%   |
| 10     | 7         | 0.69%   |
| 12     | 5         | 0.5%    |
| 14     | 4         | 0.4%    |
| 16     | 1         | 0.1%    |
| 3      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1010      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 682       | 67.52%  |
| 1      | 328       | 32.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 963       | 94.97%  |
| Unknown        | 29        | 2.86%   |
| 32-bit         | 19        | 1.87%   |
| 64-bit         | 3         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 274       | 26.17%  |
| 0x306a9    | 51        | 4.87%   |
| 0x206a7    | 48        | 4.58%   |
| 0x1067a    | 43        | 4.11%   |
| 0x806ec    | 37        | 3.53%   |
| 0x10676    | 35        | 3.34%   |
| 0x806ea    | 33        | 3.15%   |
| 0x906ea    | 30        | 2.87%   |
| 0x6fd      | 30        | 2.87%   |
| 0x806c1    | 27        | 2.58%   |
| 0x40651    | 24        | 2.29%   |
| 0x306d4    | 21        | 2.01%   |
| 0x20655    | 21        | 2.01%   |
| 0x406e3    | 18        | 1.72%   |
| 0x806eb    | 16        | 1.53%   |
| 0x20652    | 16        | 1.53%   |
| 0x806e9    | 15        | 1.43%   |
| 0x306c3    | 14        | 1.34%   |
| 0x08200103 | 14        | 1.34%   |
| 0x506e3    | 13        | 1.24%   |
| 0x30678    | 13        | 1.24%   |
| 0x08108109 | 13        | 1.24%   |
| 0xa0652    | 11        | 1.05%   |
| 0x0a50000c | 11        | 1.05%   |
| 0x406c3    | 10        | 0.96%   |
| 0x07030105 | 10        | 0.96%   |
| 0x406c4    | 8         | 0.76%   |
| 0x106ca    | 8         | 0.76%   |
| 0x08108102 | 8         | 0.76%   |
| 0x906e9    | 7         | 0.67%   |
| 0x906a3    | 7         | 0.67%   |
| 0x6f6      | 7         | 0.67%   |
| 0x106e5    | 7         | 0.67%   |
| 0x08600103 | 7         | 0.67%   |
| 0x706e5    | 6         | 0.57%   |
| 0x6d8      | 6         | 0.57%   |
| 0x08600104 | 6         | 0.57%   |
| 0x0700010f | 6         | 0.57%   |
| 0x06006704 | 6         | 0.57%   |
| 0x08608103 | 5         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 175       | 17.31%  |
| Penryn           | 95        | 9.4%    |
| IvyBridge        | 70        | 6.92%   |
| SandyBridge      | 62        | 6.13%   |
| Haswell          | 61        | 6.03%   |
| Core             | 56        | 5.54%   |
| Westmere         | 50        | 4.95%   |
| Skylake          | 48        | 4.75%   |
| Silvermont       | 44        | 4.35%   |
| TigerLake        | 38        | 3.76%   |
| Broadwell        | 30        | 2.97%   |
| Zen 3            | 29        | 2.87%   |
| Zen+             | 26        | 2.57%   |
| Zen 2            | 25        | 2.47%   |
| Zen              | 23        | 2.27%   |
| Unknown          | 23        | 2.27%   |
| Puma             | 20        | 1.98%   |
| CometLake        | 16        | 1.58%   |
| Bonnell          | 15        | 1.48%   |
| Excavator        | 14        | 1.38%   |
| P6               | 13        | 1.29%   |
| Alderlake Hybrid | 12        | 1.19%   |
| Jaguar           | 11        | 1.09%   |
| Nehalem          | 9         | 0.89%   |
| IceLake          | 9         | 0.89%   |
| Goldmont plus    | 6         | 0.59%   |
| Steamroller      | 5         | 0.49%   |
| Bobcat           | 5         | 0.49%   |
| K8 Hammer        | 4         | 0.4%    |
| K8 & K10 hybrid  | 4         | 0.4%    |
| Goldmont         | 4         | 0.4%    |
| Tremont          | 3         | 0.3%    |
| Piledriver       | 3         | 0.3%    |
| K10 Llano        | 2         | 0.2%    |
| K10              | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 664       | 49.96%  |
| Nvidia                           | 379       | 28.52%  |
| AMD                              | 277       | 20.84%  |
| Silicon Integrated Systems [SiS] | 9         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 5.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 3.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 40        | 2.89%   |
| Intel UHD Graphics 620                                                                   | 38        | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 35        | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 34        | 2.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 2.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 2.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 2.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 1.95%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 24        | 1.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 24        | 1.73%   |
| AMD Renoir                                                                               | 22        | 1.59%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 21        | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20        | 1.44%   |
| Intel HD Graphics 620                                                                    | 19        | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 1.37%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 19        | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 1.01%   |
| Nvidia GP108M [GeForce MX150]                                                            | 14        | 1.01%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 1.01%   |
| Intel HD Graphics 530                                                                    | 14        | 1.01%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 14        | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.94%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 12        | 0.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.87%   |
| Nvidia GP108M [GeForce MX250]                                                            | 11        | 0.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 0.79%   |
| Intel HD Graphics 630                                                                    | 11        | 0.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 10        | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.72%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 10        | 0.72%   |
| AMD Lucienne                                                                             | 10        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 377       | 37.25%  |
| Intel + Nvidia | 240       | 23.72%  |
| 1 x AMD        | 177       | 17.49%  |
| 1 x Nvidia     | 107       | 10.57%  |
| Intel + AMD    | 47        | 4.64%   |
| AMD + Nvidia   | 32        | 3.16%   |
| 2 x AMD        | 22        | 2.17%   |
| 1 x SiS        | 9         | 0.89%   |
| 2 x Intel      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 822       | 80.04%  |
| Proprietary | 166       | 16.16%  |
| Unknown     | 39        | 3.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 576       | 55.54%  |
| 0.01-0.5   | 178       | 17.16%  |
| 1.01-2.0   | 133       | 12.83%  |
| 0.51-1.0   | 72        | 6.94%   |
| 3.01-4.0   | 48        | 4.63%   |
| 5.01-6.0   | 20        | 1.93%   |
| 7.01-8.0   | 7         | 0.68%   |
| 2.01-3.0   | 2         | 0.19%   |
| 8.01-16.0  | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 215       | 19.85%  |
| Chimei Innolux          | 158       | 14.59%  |
| LG Display              | 131       | 12.1%   |
| BOE                     | 126       | 11.63%  |
| Samsung Electronics     | 103       | 9.51%   |
| Goldstar                | 38        | 3.51%   |
| Chi Mei Optoelectronics | 31        | 2.86%   |
| Apple                   | 25        | 2.31%   |
| LG Philips              | 24        | 2.22%   |
| Lenovo                  | 21        | 1.94%   |
| Dell                    | 20        | 1.85%   |
| PANDA                   | 19        | 1.75%   |
| Ancor Communications    | 19        | 1.75%   |
| Hewlett-Packard         | 18        | 1.66%   |
| Sharp                   | 17        | 1.57%   |
| AOC                     | 13        | 1.2%    |
| Philips                 | 9         | 0.83%   |
| BenQ                    | 8         | 0.74%   |
| CPT                     | 7         | 0.65%   |
| Sony                    | 6         | 0.55%   |
| Seiko/Epson             | 6         | 0.55%   |
| InfoVision              | 6         | 0.55%   |
| MSI                     | 5         | 0.46%   |
| Acer                    | 5         | 0.46%   |
| ViewSonic               | 4         | 0.37%   |
| HannStar                | 4         | 0.37%   |
| ASUSTek Computer        | 4         | 0.37%   |
| Toshiba                 | 3         | 0.28%   |
| LGD                     | 3         | 0.28%   |
| LG Electronics          | 3         | 0.28%   |
| CSO                     | 3         | 0.28%   |
| Valve                   | 2         | 0.18%   |
| Unknown                 | 2         | 0.18%   |
| Panasonic               | 2         | 0.18%   |
| HUAWEI                  | 2         | 0.18%   |
| CVT                     | 2         | 0.18%   |
| ZTR                     | 1         | 0.09%   |
| STA                     | 1         | 0.09%   |
| RTK                     | 1         | 0.09%   |
| Plain Tree Systems      | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 1.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 1%      |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.91%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 10        | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 8         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 7         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 6         | 0.54%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 6         | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.45%   |
| LG Philips LCD Monitor LPLDD00 1280x800 331x207mm 15.4-inch              | 5         | 0.45%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 5         | 0.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 5         | 0.45%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.45%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 5         | 0.45%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.45%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 4         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 4         | 0.36%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 4         | 0.36%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.36%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.36%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 4         | 0.36%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 4         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.36%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 376       | 37.3%   |
| 1366x768 (WXGA)    | 360       | 35.71%  |
| 1280x800 (WXGA)    | 60        | 5.95%   |
| 3840x2160 (4K)     | 30        | 2.98%   |
| 1600x900 (HD+)     | 30        | 2.98%   |
| 1440x900 (WXGA+)   | 19        | 1.88%   |
| 2560x1440 (QHD)    | 18        | 1.79%   |
| 1680x1050 (WSXGA+) | 13        | 1.29%   |
| 1280x1024 (SXGA)   | 12        | 1.19%   |
| 2560x1080          | 10        | 0.99%   |
| 1920x1200 (WUXGA)  | 10        | 0.99%   |
| 2160x1440          | 8         | 0.79%   |
| 2560x1600          | 6         | 0.6%    |
| 1360x768           | 6         | 0.6%    |
| 1024x600           | 6         | 0.6%    |
| 3440x1440          | 5         | 0.5%    |
| 2880x1800          | 5         | 0.5%    |
| 1024x768 (XGA)     | 5         | 0.5%    |
| 3840x2400          | 4         | 0.4%    |
| Unknown            | 4         | 0.4%    |
| 3200x1800 (QHD+)   | 3         | 0.3%    |
| 800x1280           | 2         | 0.2%    |
| 2288x1287          | 2         | 0.2%    |
| 1400x1050          | 2         | 0.2%    |
| 640x480            | 1         | 0.1%    |
| 3840x1600          | 1         | 0.1%    |
| 3840x1100          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 3520x1080          | 1         | 0.1%    |
| 3280x1080          | 1         | 0.1%    |
| 3000x2000          | 1         | 0.1%    |
| 2880x1620          | 1         | 0.1%    |
| 2726x768           | 1         | 0.1%    |
| 2240x1400          | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1600x1200          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 506       | 46.64%  |
| 13      | 130       | 11.98%  |
| 14      | 129       | 11.89%  |
| 17      | 54        | 4.98%   |
| 24      | 38        | 3.5%    |
| 21      | 33        | 3.04%   |
| 23      | 25        | 2.3%    |
| 27      | 24        | 2.21%   |
| Unknown | 24        | 2.21%   |
| 12      | 20        | 1.84%   |
| 11      | 16        | 1.47%   |
| 34      | 14        | 1.29%   |
| 16      | 12        | 1.11%   |
| 10      | 9         | 0.83%   |
| 31      | 8         | 0.74%   |
| 22      | 8         | 0.74%   |
| 19      | 7         | 0.65%   |
| 40      | 4         | 0.37%   |
| 84      | 3         | 0.28%   |
| 28      | 3         | 0.28%   |
| 20      | 3         | 0.28%   |
| 18      | 3         | 0.28%   |
| 72      | 2         | 0.18%   |
| 26      | 2         | 0.18%   |
| 25      | 2         | 0.18%   |
| 7       | 2         | 0.18%   |
| 60      | 1         | 0.09%   |
| 54      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 8       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 701       | 65.64%  |
| 201-300     | 106       | 9.93%   |
| 501-600     | 81        | 7.58%   |
| 351-400     | 61        | 5.71%   |
| 401-500     | 52        | 4.87%   |
| Unknown     | 24        | 2.25%   |
| 701-800     | 14        | 1.31%   |
| 601-700     | 14        | 1.31%   |
| 801-900     | 5         | 0.47%   |
| 1501-2000   | 5         | 0.47%   |
| 1001-1500   | 2         | 0.19%   |
| 1-100       | 2         | 0.19%   |
| 101-200     | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 766       | 79.79%  |
| 16/10   | 121       | 12.6%   |
| Unknown | 22        | 2.29%   |
| 21/9    | 16        | 1.67%   |
| 3/2     | 12        | 1.25%   |
| 5/4     | 11        | 1.15%   |
| 4/3     | 9         | 0.94%   |
| 0.67    | 2         | 0.21%   |
| 3.40    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 505       | 46.63%  |
| 81-90          | 211       | 19.48%  |
| 201-250        | 85        | 7.85%   |
| 71-80          | 46        | 4.25%   |
| 121-130        | 35        | 3.23%   |
| 301-350        | 25        | 2.31%   |
| Unknown        | 24        | 2.22%   |
| 351-500        | 22        | 2.03%   |
| 61-70          | 20        | 1.85%   |
| 151-200        | 19        | 1.75%   |
| 51-60          | 17        | 1.57%   |
| 251-300        | 13        | 1.2%    |
| 141-150        | 12        | 1.11%   |
| 111-120        | 10        | 0.92%   |
| 41-50          | 9         | 0.83%   |
| 131-140        | 9         | 0.83%   |
| More than 1000 | 7         | 0.65%   |
| 501-1000       | 6         | 0.55%   |
| 91-100         | 5         | 0.46%   |
| 1-40           | 3         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 376       | 35.51%  |
| 121-160       | 369       | 34.84%  |
| 51-100        | 208       | 19.64%  |
| 161-240       | 56        | 5.29%   |
| Unknown       | 24        | 2.27%   |
| More than 240 | 21        | 1.98%   |
| 1-50          | 5         | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 805       | 77.63%  |
| 2     | 160       | 15.43%  |
| 0     | 49        | 4.73%   |
| 3     | 20        | 1.93%   |
| 4     | 3         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 528       | 32.65%  |
| Intel                             | 462       | 28.57%  |
| Qualcomm Atheros                  | 275       | 17.01%  |
| Broadcom                          | 122       | 7.54%   |
| Marvell Technology Group          | 45        | 2.78%   |
| TP-Link                           | 31        | 1.92%   |
| MediaTek                          | 21        | 1.3%    |
| Broadcom Limited                  | 20        | 1.24%   |
| Ralink                            | 15        | 0.93%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.74%   |
| Nvidia                            | 9         | 0.56%   |
| Ralink Technology                 | 6         | 0.37%   |
| ASIX Electronics                  | 6         | 0.37%   |
| Sierra Wireless                   | 4         | 0.25%   |
| Lenovo                            | 4         | 0.25%   |
| JMicron Technology                | 4         | 0.25%   |
| Ericsson Business Mobile Networks | 4         | 0.25%   |
| DisplayLink                       | 4         | 0.25%   |
| D-Link                            | 4         | 0.25%   |
| Attansic Technology               | 4         | 0.25%   |
| ASUSTek Computer                  | 4         | 0.25%   |
| Qualcomm Atheros Communications   | 3         | 0.19%   |
| ICS Advent                        | 3         | 0.19%   |
| Huawei Technologies               | 3         | 0.19%   |
| Hewlett-Packard                   | 3         | 0.19%   |
| Samsung Electronics               | 2         | 0.12%   |
| Fibocom                           | 2         | 0.12%   |
| Dell                              | 2         | 0.12%   |
| Xiaomi                            | 1         | 0.06%   |
| TRENDnet                          | 1         | 0.06%   |
| Toshiba                           | 1         | 0.06%   |
| T & A Mobile Phones               | 1         | 0.06%   |
| SparkFun                          | 1         | 0.06%   |
| Qualcomm                          | 1         | 0.06%   |
| Microsoft                         | 1         | 0.06%   |
| Micro Star International          | 1         | 0.06%   |
| LSI                               | 1         | 0.06%   |
| GrupoPIE PORTUGAL                 | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |
| Belkin Components                 | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 321       | 16.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 117       | 6.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 2.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 48        | 2.51%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 38        | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 32        | 1.68%   |
| Intel Wireless 8265 / 8275                                              | 32        | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 30        | 1.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 1.47%   |
| Intel Wi-Fi 6 AX201                                                     | 27        | 1.41%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                    | 26        | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 25        | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 24        | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 23        | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 23        | 1.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 22        | 1.15%   |
| Intel Wireless 7260                                                     | 22        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.1%    |
| Intel Wireless 7265                                                     | 21        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 21        | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 18        | 0.94%   |
| Intel Wireless 8260                                                     | 18        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 17        | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 14        | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 0.63%   |
| Intel Wireless 3165                                                     | 12        | 0.63%   |
| Intel WiFi Link 5100                                                    | 12        | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 11        | 0.58%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 0.58%   |
| Intel Wireless 3160                                                     | 11        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 447       | 43.36%  |
| Qualcomm Atheros                | 241       | 23.38%  |
| Realtek Semiconductor           | 158       | 15.32%  |
| Broadcom                        | 99        | 9.6%    |
| MediaTek                        | 20        | 1.94%   |
| Ralink                          | 15        | 1.45%   |
| Broadcom Limited                | 12        | 1.16%   |
| TP-Link                         | 10        | 0.97%   |
| Ralink Technology               | 6         | 0.58%   |
| Sierra Wireless                 | 4         | 0.39%   |
| D-Link                          | 4         | 0.39%   |
| ASUSTek Computer                | 4         | 0.39%   |
| Qualcomm Atheros Communications | 3         | 0.29%   |
| Fibocom                         | 2         | 0.19%   |
| Dell                            | 2         | 0.19%   |
| TRENDnet                        | 1         | 0.1%    |
| Micro Star International        | 1         | 0.1%    |
| D-Link System                   | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 5.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 48        | 4.66%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 3.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 38        | 3.69%   |
| Intel Wireless 8265 / 8275                                              | 32        | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 30        | 2.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 2.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 2.72%   |
| Intel Wi-Fi 6 AX201                                                     | 27        | 2.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 25        | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 2.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 24        | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 23        | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 23        | 2.23%   |
| Intel Wireless 7260                                                     | 22        | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 2.04%   |
| Intel Wireless 7265                                                     | 21        | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 1.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 18        | 1.75%   |
| Intel Wireless 8260                                                     | 18        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 17        | 1.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 14        | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 1.16%   |
| Intel Wireless 3165                                                     | 12        | 1.16%   |
| Intel WiFi Link 5100                                                    | 12        | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 1.07%   |
| Intel Wireless 3160                                                     | 11        | 1.07%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.97%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.87%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 9         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 483       | 56.29%  |
| Intel                            | 137       | 15.97%  |
| Qualcomm Atheros                 | 65        | 7.58%   |
| Marvell Technology Group         | 45        | 5.24%   |
| Broadcom                         | 39        | 4.55%   |
| TP-Link                          | 22        | 2.56%   |
| Silicon Integrated Systems [SiS] | 12        | 1.4%    |
| Nvidia                           | 9         | 1.05%   |
| Broadcom Limited                 | 8         | 0.93%   |
| ASIX Electronics                 | 6         | 0.7%    |
| Lenovo                           | 4         | 0.47%   |
| JMicron Technology               | 4         | 0.47%   |
| DisplayLink                      | 4         | 0.47%   |
| Attansic Technology              | 4         | 0.47%   |
| ICS Advent                       | 3         | 0.35%   |
| Huawei Technologies              | 2         | 0.23%   |
| Hewlett-Packard                  | 2         | 0.23%   |
| Xiaomi                           | 1         | 0.12%   |
| T & A Mobile Phones              | 1         | 0.12%   |
| Samsung Electronics              | 1         | 0.12%   |
| Qualcomm                         | 1         | 0.12%   |
| Microsoft                        | 1         | 0.12%   |
| MediaTek                         | 1         | 0.12%   |
| LSI                              | 1         | 0.12%   |
| Archos                           | 1         | 0.12%   |
| Allwinner Technology             | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 321       | 37.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 117       | 13.57%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 32        | 3.71%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 26        | 3.02%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 22        | 2.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21        | 2.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 11        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 9         | 1.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 9         | 1.04%   |
| Intel Ethernet Connection I218-LM                                              | 9         | 1.04%   |
| Intel 82579V Gigabit Network Connection                                        | 9         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                                           | 8         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.81%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 7         | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.7%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.7%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.7%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.7%    |
| Intel Ethernet Connection I219-LM                                              | 6         | 0.7%    |
| Intel Ethernet Connection I217-LM                                              | 6         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                                          | 4         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 0.46%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 0.46%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 0.46%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 4         | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 4         | 0.46%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 4         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 987       | 53.64%  |
| Ethernet | 836       | 45.43%  |
| Modem    | 15        | 0.82%   |
| Unknown  | 2         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 789       | 73.53%  |
| Ethernet | 283       | 26.37%  |
| Modem    | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 747       | 73.89%  |
| 1     | 245       | 24.23%  |
| 0     | 17        | 1.68%   |
| 3     | 2         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 754       | 72.92%  |
| Yes  | 280       | 27.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 312       | 42.16%  |
| Realtek Semiconductor           | 83        | 11.22%  |
| Qualcomm Atheros Communications | 57        | 7.7%    |
| IMC Networks                    | 57        | 7.7%    |
| Foxconn / Hon Hai               | 44        | 5.95%   |
| Lite-On Technology              | 41        | 5.54%   |
| Broadcom                        | 35        | 4.73%   |
| Apple                           | 25        | 3.38%   |
| Toshiba                         | 19        | 2.57%   |
| Hewlett-Packard                 | 15        | 2.03%   |
| ASUSTek Computer                | 12        | 1.62%   |
| Realtek                         | 10        | 1.35%   |
| Dell                            | 9         | 1.22%   |
| Ralink                          | 8         | 1.08%   |
| Cambridge Silicon Radio         | 4         | 0.54%   |
| Alps Electric                   | 4         | 0.54%   |
| Ralink Technology               | 2         | 0.27%   |
| MediaTek                        | 1         | 0.14%   |
| Foxconn International           | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 116       | 15.68%  |
| Realtek Bluetooth Radio                                                             | 61        | 8.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 57        | 7.7%    |
| Intel AX201 Bluetooth                                                               | 57        | 7.7%    |
| Intel AX200 Bluetooth                                                               | 40        | 5.41%   |
| IMC Networks Bluetooth Device                                                       | 29        | 3.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 20        | 2.7%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 2.16%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 2.03%   |
| IMC Networks Bluetooth Radio                                                        | 15        | 2.03%   |
| Apple Bluetooth Host Controller                                                     | 14        | 1.89%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 1.76%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 1.49%   |
| Realtek 802.11ac WLAN Adapter                                                       | 10        | 1.35%   |
| Lite-On Bluetooth Device                                                            | 10        | 1.35%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.22%   |
| Intel Bluetooth Device                                                              | 9         | 1.22%   |
| Apple Bluetooth USB Host Controller                                                 | 9         | 1.22%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.95%   |
| IMC Networks Wireless_Device                                                        | 7         | 0.95%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 7         | 0.95%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 6         | 0.81%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.81%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.68%   |
| Toshiba Askey Bluetooth Module                                                      | 5         | 0.68%   |
| Lite-On BCM43142A0                                                                  | 5         | 0.68%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 5         | 0.68%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.54%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 4         | 0.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 0.54%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 4         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 785       | 62.35%  |
| AMD                              | 231       | 18.35%  |
| Nvidia                           | 156       | 12.39%  |
| Silicon Integrated Systems [SiS] | 12        | 0.95%   |
| Realtek Semiconductor            | 7         | 0.56%   |
| GN Netcom                        | 7         | 0.56%   |
| C-Media Electronics              | 7         | 0.56%   |
| Plantronics                      | 6         | 0.48%   |
| Lenovo                           | 4         | 0.32%   |
| Hewlett-Packard                  | 4         | 0.32%   |
| Creative Technology              | 4         | 0.32%   |
| Texas Instruments                | 3         | 0.24%   |
| Razer USA                        | 3         | 0.24%   |
| JMTek                            | 3         | 0.24%   |
| Sony                             | 2         | 0.16%   |
| Logitech                         | 2         | 0.16%   |
| Kingston Technology              | 2         | 0.16%   |
| Generalplus Technology           | 2         | 0.16%   |
| DSEA A/S                         | 2         | 0.16%   |
| XMOS                             | 1         | 0.08%   |
| Trust                            | 1         | 0.08%   |
| Micro Star International         | 1         | 0.08%   |
| JBL                              | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |
| GYROCOM C&C                      | 1         | 0.08%   |
| Guillemot                        | 1         | 0.08%   |
| ESS Technology                   | 1         | 0.08%   |
| EGO SYStems                      | 1         | 0.08%   |
| Dell                             | 1         | 0.08%   |
| Corsair                          | 1         | 0.08%   |
| Conexant Systems                 | 1         | 0.08%   |
| Conexant                         | 1         | 0.08%   |
| CMX Systems                      | 1         | 0.08%   |
| BEHRINGER International          | 1         | 0.08%   |
| ASUSTek Computer                 | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 110       | 7.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 87        | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 76        | 5.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 66        | 4.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 59        | 3.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 56        | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 56        | 3.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 3.07%   |
| AMD FCH Azalia Controller                                                                         | 43        | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 40        | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 40        | 2.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 38        | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 38        | 2.54%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 2.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 36        | 2.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 34        | 2.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 33        | 2.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 30        | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 30        | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 29        | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 20        | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 1.2%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 17        | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 16        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 14        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 0.87%   |
| AMD High Definition Audio Controller                                                              | 12        | 0.8%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 11        | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 0.73%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 11        | 0.73%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 11        | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 10        | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 174       | 30.85%  |
| SK hynix            | 127       | 22.52%  |
| Unknown             | 70        | 12.41%  |
| Micron Technology   | 57        | 10.11%  |
| Kingston            | 49        | 8.69%   |
| Ramaxel Technology  | 15        | 2.66%   |
| Crucial             | 12        | 2.13%   |
| G.Skill             | 9         | 1.6%    |
| Elpida              | 9         | 1.6%    |
| A-DATA Technology   | 8         | 1.42%   |
| Corsair             | 7         | 1.24%   |
| Team                | 4         | 0.71%   |
| Unknown             | 4         | 0.71%   |
| Transcend           | 3         | 0.53%   |
| Nanya Technology    | 3         | 0.53%   |
| Unknown (ABCD)      | 2         | 0.35%   |
| Unigen              | 1         | 0.18%   |
| Toshiba             | 1         | 0.18%   |
| Teikon              | 1         | 0.18%   |
| PUSKILL             | 1         | 0.18%   |
| Netlist             | 1         | 0.18%   |
| GOODRAM             | 1         | 0.18%   |
| Goldkey             | 1         | 0.18%   |
| Essencore Limited   | 1         | 0.18%   |
| ASint Technology    | 1         | 0.18%   |
| Apacer              | 1         | 0.18%   |
| 48spaces            | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 24        | 4.07%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 16        | 2.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 2.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 9         | 1.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 1.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.19%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 7         | 1.19%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 5         | 0.85%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.85%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 5         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 4         | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.68%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.68%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.68%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.68%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 4         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.68%   |
| Unknown                                                          | 4         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.51%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 3         | 0.51%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.51%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.51%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.51%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 234       | 48.55%  |
| DDR3    | 136       | 28.22%  |
| DDR2    | 51        | 10.58%  |
| LPDDR4  | 19        | 3.94%   |
| LPDDR3  | 17        | 3.53%   |
| SDRAM   | 11        | 2.28%   |
| LPDDR5  | 5         | 1.04%   |
| DDR5    | 4         | 0.83%   |
| DDR     | 3         | 0.62%   |
| Unknown | 2         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 413       | 85.86%  |
| Row Of Chips | 63        | 13.1%   |
| DIMM         | 2         | 0.42%   |
| Chip         | 2         | 0.42%   |
| Unknown      | 1         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 174       | 33.4%   |
| 4096    | 145       | 27.83%  |
| 2048    | 83        | 15.93%  |
| 16384   | 81        | 15.55%  |
| 1024    | 19        | 3.65%   |
| 32768   | 14        | 2.69%   |
| 512     | 4         | 0.77%   |
| Unknown | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 111       | 21.64%  |
| 1600    | 89        | 17.35%  |
| 3200    | 88        | 17.15%  |
| Unknown | 43        | 8.38%   |
| 2400    | 31        | 6.04%   |
| 2133    | 27        | 5.26%   |
| 1334    | 21        | 4.09%   |
| 667     | 15        | 2.92%   |
| 1333    | 14        | 2.73%   |
| 8400    | 10        | 1.95%   |
| 4267    | 9         | 1.75%   |
| 1067    | 7         | 1.36%   |
| 4199    | 6         | 1.17%   |
| 3266    | 6         | 1.17%   |
| 6400    | 5         | 0.97%   |
| 1867    | 5         | 0.97%   |
| 800     | 5         | 0.97%   |
| 4800    | 4         | 0.78%   |
| 1066    | 3         | 0.58%   |
| 533     | 3         | 0.58%   |
| 2933    | 2         | 0.39%   |
| 2048    | 2         | 0.39%   |
| 1866    | 2         | 0.39%   |
| 4266    | 1         | 0.19%   |
| 3733    | 1         | 0.19%   |
| 3000    | 1         | 0.19%   |
| 1200    | 1         | 0.19%   |
| 975     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 4         | 50%     |
| STMicroelectronics     | 1         | 12.5%   |
| Seiko Epson            | 1         | 12.5%   |
| Samsung Electronics    | 1         | 12.5%   |
| Panasonic (Matsushita) | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 12.5%   |
| Seiko Epson AcuLaser C1700                                | 1         | 12.5%   |
| Samsung ML-1640 Series Laser Printer                      | 1         | 12.5%   |
| Panasonic (Matsushita) KX-FLB851SP                        | 1         | 12.5%   |
| HP OfficeJet 3830 series                                  | 1         | 12.5%   |
| HP DeskJet F4100 Printer series                           | 1         | 12.5%   |
| HP Deskjet 3050A                                          | 1         | 12.5%   |
| HP DeskJet 2130 series                                    | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems BearPaw 2448 CU Pro | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 245       | 27.34%  |
| IMC Networks                           | 118       | 13.17%  |
| Realtek Semiconductor                  | 73        | 8.15%   |
| Suyin                                  | 49        | 5.47%   |
| Bison Electronics                      | 48        | 5.36%   |
| Quanta                                 | 41        | 4.58%   |
| Microdia                               | 40        | 4.46%   |
| Ricoh                                  | 32        | 3.57%   |
| Sunplus Innovation Technology          | 31        | 3.46%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 3.35%   |
| Syntek                                 | 27        | 3.01%   |
| Lite-On Technology                     | 27        | 3.01%   |
| Apple                                  | 21        | 2.34%   |
| Acer                                   | 17        | 1.9%    |
| Luxvisions Innotech Limited            | 15        | 1.67%   |
| Silicon Motion                         | 10        | 1.12%   |
| Alcor Micro                            | 9         | 1%      |
| Importek                               | 8         | 0.89%   |
| Lenovo                                 | 7         | 0.78%   |
| Z-Star Microelectronics                | 6         | 0.67%   |
| Logitech                               | 5         | 0.56%   |
| Generalplus Technology                 | 4         | 0.45%   |
| Sonix Technology                       | 3         | 0.33%   |
| Samsung Electronics                    | 3         | 0.33%   |
| ALi                                    | 3         | 0.33%   |
| WaveRider Communications               | 2         | 0.22%   |
| SunplusIT                              | 2         | 0.22%   |
| Primax Electronics                     | 2         | 0.22%   |
| Microsoft                              | 2         | 0.22%   |
| MacroSilicon                           | 2         | 0.22%   |
| DigiTech                               | 2         | 0.22%   |
| Creative Technology                    | 2         | 0.22%   |
| Y Media                                | 1         | 0.11%   |
| Trust                                  | 1         | 0.11%   |
| OmniVision Technologies                | 1         | 0.11%   |
| Mustek Systems                         | 1         | 0.11%   |
| lihappe8                               | 1         | 0.11%   |
| kingcome                               | 1         | 0.11%   |
| Intel                                  | 1         | 0.11%   |
| Genesys Logic                          | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 35        | 3.89%   |
| Chicony Integrated Camera                           | 33        | 3.67%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 22        | 2.44%   |
| IMC Networks Integrated Camera                      | 22        | 2.44%   |
| Chicony HD WebCam                                   | 22        | 2.44%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 2%      |
| Chicony USB2.0 VGA UVC WebCam                       | 17        | 1.89%   |
| Realtek EasyCamera                                  | 14        | 1.56%   |
| Chicony USB 2.0 Camera                              | 14        | 1.56%   |
| Microdia Integrated_Webcam_HD                       | 13        | 1.44%   |
| Chicony CNF9055 Toshiba Webcam                      | 13        | 1.44%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 12        | 1.33%   |
| Realtek USB Camera                                  | 12        | 1.33%   |
| Chicony TOSHIBA Web Camera - HD                     | 11        | 1.22%   |
| Syntek Integrated Camera                            | 10        | 1.11%   |
| IMC Networks HD Camera                              | 10        | 1.11%   |
| Bison Integrated Camera                             | 10        | 1.11%   |
| Realtek Integrated_Webcam_HD                        | 9         | 1%      |
| Chicony HP Truevision HD                            | 9         | 1%      |
| Suyin USB 2.0 Camera                                | 8         | 0.89%   |
| Sunplus HD WebCam                                   | 8         | 0.89%   |
| Quanta HP Wide Vision HD Camera                     | 8         | 0.89%   |
| Lite-On Integrated Camera                           | 8         | 0.89%   |
| Chicony HP HD Camera                                | 8         | 0.89%   |
| Realtek HD WebCam                                   | 7         | 0.78%   |
| Realtek 2SF022                                      | 7         | 0.78%   |
| Quanta HP TrueVision HD Camera                      | 7         | 0.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 7         | 0.78%   |
| IMC Networks ov9734_azurewave_camera                | 7         | 0.78%   |
| Chicony VGA Webcam                                  | 7         | 0.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 7         | 0.78%   |
| Syntek EasyCamera                                   | 6         | 0.67%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.67%   |
| Chicony USB2.0 HD UVC WebCam                        | 6         | 0.67%   |
| Chicony USB2.0 Camera                               | 6         | 0.67%   |
| Sunplus Asus Webcam                                 | 5         | 0.56%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.56%   |
| Quanta VGA WebCam                                   | 5         | 0.56%   |
| Microdia USB 2.0 Camera                             | 5         | 0.56%   |
| Microdia Sonix USB 2.0 Camera                       | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 47        | 32.41%  |
| Validity Sensors                   | 46        | 31.72%  |
| Shenzhen Goodix Technology         | 21        | 14.48%  |
| AuthenTec                          | 9         | 6.21%   |
| Elan Microelectronics              | 7         | 4.83%   |
| Upek                               | 6         | 4.14%   |
| LighTuning Technology              | 5         | 3.45%   |
| STMicroelectronics                 | 3         | 2.07%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 11.03%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 5.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 4.14%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 3.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 3.45%   |
| Synaptics UWP WBDI Device                                                  | 5         | 3.45%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 3.45%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 2.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.76%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.76%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 2.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.76%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.07%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.07%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.07%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.07%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.07%   |
| AuthenTec AES2810                                                          | 3         | 2.07%   |
| AuthenTec AES1600                                                          | 3         | 2.07%   |
| Validity Sensors VFS491                                                    | 2         | 1.38%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.38%   |
| Synaptics WBDI                                                             | 2         | 1.38%   |
| Synaptics UWP WBDI                                                         | 2         | 1.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.38%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.38%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.38%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.38%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.69%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.69%   |
| Synaptics WBDI Device                                                      | 1         | 0.69%   |
| Synaptics  WBDI                                                            | 1         | 0.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 24        | 37.5%   |
| Broadcom              | 19        | 29.69%  |
| O2 Micro              | 6         | 9.38%   |
| Gemalto (was Gemplus) | 5         | 7.81%   |
| Lenovo                | 3         | 4.69%   |
| SCM Microsystems      | 2         | 3.13%   |
| Yubico.com            | 1         | 1.56%   |
| Upek                  | 1         | 1.56%   |
| Realtek Semiconductor | 1         | 1.56%   |
| Cherry                | 1         | 1.56%   |
| Advanced Card Systems | 1         | 1.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 10.94%  |
| Broadcom 58200                                                               | 7         | 10.94%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 7.81%   |
| Broadcom 5880                                                                | 4         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 4.69%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 3.13%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 3.13%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.56%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.56%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.56%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 649       | 62.28%  |
| 1     | 303       | 29.08%  |
| 2     | 69        | 6.62%   |
| 3     | 16        | 1.54%   |
| 4     | 4         | 0.38%   |
| 5     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 144       | 30%     |
| Graphics card            | 126       | 26.25%  |
| Net/wireless             | 58        | 12.08%  |
| Chipcard                 | 50        | 10.42%  |
| Multimedia controller    | 40        | 8.33%   |
| Camera                   | 14        | 2.92%   |
| Bluetooth                | 12        | 2.5%    |
| Card reader              | 10        | 2.08%   |
| Storage                  | 7         | 1.46%   |
| Communication controller | 6         | 1.25%   |
| Modem                    | 4         | 0.83%   |
| Flash memory             | 4         | 0.83%   |
| Network                  | 2         | 0.42%   |
| Net/ethernet             | 2         | 0.42%   |
| Sound                    | 1         | 0.21%   |


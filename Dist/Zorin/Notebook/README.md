Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 4727

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Venue 11 Pro 5130           | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| Dell          | Latitude E7450              | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| Dell          | Latitude E6520              | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Sony          | SVS15116GAB                 | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | ENVY 17                     | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| HP            | ENVY 17                     | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| HP            | 250 G7 Notebook PC          | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| Acer          | Aspire 5738                 | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| Dell          | Precision 7530              | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| Dell          | Latitude 5490               | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| HP            | Pavilion g7                 | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| HP            | Compaq Presario CQ60        | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| HP            | 250 G8 Notebook PC          | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Alienware     | M14xR2                      | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dell          | Precision 5530              | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Medion        | E4251 MD61435               | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Dell          | G3 3579                     | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Acer          | Aspire ES1-521              | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| HP            | Pavilion dv6                | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| HP            | 470 17 inch G9              | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| HP            | Notebook                    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Dell          | XPS 13 9360                 | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| HP            | 250 G7 Notebook PC          | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Apple         | MacBook4,1                  | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| ASUSTek       | K54C                        | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Lenovo        | V110-14IAP 80TF             | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Dell          | Inspiron 5559               | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| HP            | Laptop 14-dq1xxx            | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [b1efa66e79](https://linux-hardware.org/?probe=b1efa66e79) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| TERRA         | TERRAPC                     | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| HP            | Notebook                    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Dell          | Latitude E5470              | [ca95c6f5bc](https://linux-hardware.org/?probe=ca95c6f5bc) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | 15                          | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| OEM           | Unknown                     | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Positivo      | Mobile                      | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| Dell          | Precision M4700             | [3680e0f79f](https://linux-hardware.org/?probe=3680e0f79f) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | EliteBook 8560p             | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Haier         | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| eMachines     | eMD728                      | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| HP            | Pavilion g7                 | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| IPASON        | P3                          | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Sony          | SVF14214CXW                 | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| ASUSTek       | G50VT                       | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Google        | Lars                        | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| Apple         | MacBookAir4,1               | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| HP            | Pavilion g6                 | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| Dell          | Latitude E7450              | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookAir7,2               | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| Framework     | Laptop                      | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| Dell          | XPS 17 9700                 | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Samsung       | N150/N210/N220              | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Apple         | MacBookPro10,1              | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Acer          | Aspire E5-574               | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Dell          | Latitude 3340               | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Chuwi         | GemiBook XPro               | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Aspire E1-570               | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Dell          | Precision M2800             | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| Apple         | MacBookPro10,1              | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | OMEN by Laptop              | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| ASUSTek       | GL702VI                     | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Acer          | Aspire E5-574               | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| HP            | 655                         | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| Dell          | Inspiron 3501               | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| HP            | ProBook 6570b               | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Unknown       | X133                        | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| HP            | EliteBook 8470p             | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Unknown       | E450                        | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | XPS 15 9560                 | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Acer          | Aspire E1-570               | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Acer          | Aspire V5-531               | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| Dell          | Latitude E6540              | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| ASUSTek       | K53U                        | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Dell          | Vostro 1510                 | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Acer          | AOHAPPY                     | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| HP            | Laptop 14-em0xxx            | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Acer          | AOHAPPY                     | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Acer          | Aspire E5-574               | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| Dell          | Vostro 3580                 | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| Positivo      | Q4128C-S                    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Inspiron 1545               | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Apple         | MacBookPro14,2              | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| HP            | ProBook 4540s               | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| HP            | Notebook                    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Google        | Cyan                        | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| Dell          | Latitude E6430              | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| HP            | kip                         | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Dell          | Precision M4500             | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | Latitude E5510              | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| HP            | 255 G5                      | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |
| Dell          | Inspiron 3721               | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Dell          | Latitude E7240              | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Dell          | Inspiron 5405               | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Google        | Kip                         | [84b79bf446](https://linux-hardware.org/?probe=84b79bf446) | Mar 19, 2023 |
| Google        | Kip                         | [4e63ea7ac8](https://linux-hardware.org/?probe=4e63ea7ac8) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| ASUSTek       | G53SX                       | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| Google        | Celes                       | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| HP            | Pavilion 15                 | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Dell          | Latitude E5470              | [86adaddcae](https://linux-hardware.org/?probe=86adaddcae) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Dell          | Latitude E5470              | [e7e23885b7](https://linux-hardware.org/?probe=e7e23885b7) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | Latitude 3180               | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Multilaser    | PC130                       | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| ASUSTek       | K50IJ                       | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Google        | Candy                       | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Timi          | TM1701                      | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Dell          | Inspiron N5010              | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| HP            | ENVY 17                     | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| Dell          | Inspiron 3793               | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| HP            | Pavilion dv7                | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| DERE          | V14                         | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | ENVY 17                     | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Multilaser    | PC130                       | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| HP            | ENVY 17                     | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| Dell          | Latitude E6400              | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| Acer          | TravelMate P253             | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| Acer          | Predator G3-571             | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Positivo      | Smash2                      | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| HP            | Pavilion dv7                | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 1991      | 63.83%  |
| Zorin 15 | 1014      | 32.51%  |
| Zorin 12 | 114       | 3.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 3108      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 133       | 3.73%   |
| 5.11.0-38-generic | 101       | 2.83%   |
| 5.11.0-27-generic | 94        | 2.64%   |
| 5.15.0-52-generic | 93        | 2.61%   |
| 5.15.0-58-generic | 90        | 2.52%   |
| 5.15.0-46-generic | 88        | 2.47%   |
| 5.13.0-30-generic | 74        | 2.08%   |
| 5.3.0-40-generic  | 67        | 1.88%   |
| 5.11.0-37-generic | 67        | 1.88%   |
| 5.11.0-40-generic | 65        | 1.82%   |
| 5.15.0-69-generic | 63        | 1.77%   |
| 5.15.0-67-generic | 63        | 1.77%   |
| 5.11.0-41-generic | 63        | 1.77%   |
| 5.4.0-42-generic  | 61        | 1.71%   |
| 5.15.0-78-generic | 61        | 1.71%   |
| 5.13.0-39-generic | 60        | 1.68%   |
| 5.11.0-34-generic | 57        | 1.6%    |
| 5.15.0-60-generic | 56        | 1.57%   |
| 5.11.0-43-generic | 56        | 1.57%   |
| 5.15.0-76-generic | 55        | 1.54%   |
| 5.3.0-46-generic  | 53        | 1.49%   |
| 5.15.0-71-generic | 53        | 1.49%   |
| 5.15.0-48-generic | 51        | 1.43%   |
| 5.13.0-44-generic | 48        | 1.35%   |
| 5.3.0-51-generic  | 47        | 1.32%   |
| 5.0.0-37-generic  | 47        | 1.32%   |
| 5.13.0-40-generic | 46        | 1.29%   |
| 5.15.0-53-generic | 43        | 1.21%   |
| 5.15.0-84-generic | 41        | 1.15%   |
| 5.15.0-86-generic | 40        | 1.12%   |
| 5.13.0-35-generic | 40        | 1.12%   |
| 5.4.0-47-generic  | 38        | 1.07%   |
| 5.3.0-53-generic  | 37        | 1.04%   |
| 5.13.0-28-generic | 37        | 1.04%   |
| 5.3.0-42-generic  | 36        | 1.01%   |
| 5.4.0-45-generic  | 35        | 0.98%   |
| 5.15.0-41-generic | 35        | 0.98%   |
| 5.15.0-79-generic | 34        | 0.95%   |
| 5.15.0-73-generic | 34        | 0.95%   |
| 5.4.0-58-generic  | 32        | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 1062      | 32.8%   |
| 5.4.0   | 592       | 18.28%  |
| 5.11.0  | 550       | 16.99%  |
| 5.13.0  | 406       | 12.54%  |
| 5.3.0   | 312       | 9.64%   |
| 4.15.0  | 110       | 3.4%    |
| 5.0.0   | 89        | 2.75%   |
| 4.18.0  | 45        | 1.39%   |
| 5.8.0   | 23        | 0.71%   |
| 5.14.0  | 8         | 0.25%   |
| 4.4.0   | 4         | 0.12%   |
| 6.3.13  | 2         | 0.06%   |
| 5.6.0   | 2         | 0.06%   |
| 5.19.0  | 2         | 0.06%   |
| 5.18.15 | 2         | 0.06%   |
| 5.16.0  | 2         | 0.06%   |
| 5.10.0  | 2         | 0.06%   |
| 6.3.2   | 1         | 0.03%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.16  | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.1.22  | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.9.12  | 1         | 0.03%   |
| 5.9.0   | 1         | 0.03%   |
| 5.7.1   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.4.1   | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.12 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.13.18 | 1         | 0.03%   |
| 5.10.35 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 1064      | 32.86%  |
| 5.4     | 594       | 18.34%  |
| 5.11    | 550       | 16.99%  |
| 5.13    | 407       | 12.57%  |
| 5.3     | 312       | 9.64%   |
| 4.15    | 110       | 3.4%    |
| 5.0     | 89        | 2.75%   |
| 4.18    | 45        | 1.39%   |
| 5.8     | 23        | 0.71%   |
| 5.14    | 8         | 0.25%   |
| 5.19    | 6         | 0.19%   |
| 6.3     | 4         | 0.12%   |
| 5.10    | 4         | 0.12%   |
| 4.4     | 4         | 0.12%   |
| 6.0     | 3         | 0.09%   |
| 5.18    | 3         | 0.09%   |
| 5.16    | 3         | 0.09%   |
| 6.2     | 2         | 0.06%   |
| 5.9     | 2         | 0.06%   |
| 5.6     | 2         | 0.06%   |
| 6.1     | 1         | 0.03%   |
| 5.7     | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2830      | 90.97%  |
| i686   | 281       | 9.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 2211      | 70.32%  |
| XFCE       | 738       | 23.47%  |
| Unknown    | 172       | 5.47%   |
| X-Cinnamon | 7         | 0.22%   |
| Unity      | 3         | 0.1%    |
| KDE5       | 3         | 0.1%    |
| KDE        | 3         | 0.1%    |
| i3         | 2         | 0.06%   |
| Budgie     | 2         | 0.06%   |
| LXQt       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| Cinnamon   | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2970      | 94.65%  |
| Unknown | 107       | 3.41%   |
| Wayland | 60        | 1.91%   |
| Tty     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2442      | 77.38%  |
| GDM     | 258       | 8.17%   |
| GDM3    | 248       | 7.86%   |
| LightDM | 199       | 6.31%   |
| TDM     | 6         | 0.19%   |
| SDDM    | 2         | 0.06%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1097      | 35%     |
| de_DE   | 241       | 7.69%   |
| pt_BR   | 197       | 6.29%   |
| en_GB   | 181       | 5.78%   |
| Unknown | 127       | 4.05%   |
| it_IT   | 120       | 3.83%   |
| fr_FR   | 106       | 3.38%   |
| es_ES   | 104       | 3.32%   |
| en_IN   | 99        | 3.16%   |
| en_CA   | 90        | 2.87%   |
| pl_PL   | 77        | 2.46%   |
| en_AU   | 48        | 1.53%   |
| nl_NL   | 45        | 1.44%   |
| es_MX   | 44        | 1.4%    |
| pt_PT   | 43        | 1.37%   |
| ru_RU   | 38        | 1.21%   |
| cs_CZ   | 37        | 1.18%   |
| es_AR   | 31        | 0.99%   |
| en_ZA   | 31        | 0.99%   |
| tr_TR   | 24        | 0.77%   |
| sv_SE   | 24        | 0.77%   |
| C       | 20        | 0.64%   |
| es_CL   | 19        | 0.61%   |
| en_NZ   | 18        | 0.57%   |
| de_AT   | 18        | 0.57%   |
| hu_HU   | 16        | 0.51%   |
| de_CH   | 15        | 0.48%   |
| nl_BE   | 13        | 0.41%   |
| ja_JP   | 13        | 0.41%   |
| fr_BE   | 13        | 0.41%   |
| fr_CA   | 12        | 0.38%   |
| el_GR   | 11        | 0.35%   |
| es_CO   | 10        | 0.32%   |
| en_PH   | 9         | 0.29%   |
| da_DK   | 9         | 0.29%   |
| ro_RO   | 8         | 0.26%   |
| es_PE   | 8         | 0.26%   |
| ru_UA   | 7         | 0.22%   |
| hr_HR   | 7         | 0.22%   |
| sk_SK   | 6         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1594      | 50.62%  |
| EFI  | 1555      | 49.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2888      | 92.21%  |
| Tmpfs   | 69        | 2.2%    |
| Overlay | 69        | 2.2%    |
| Zfs     | 33        | 1.05%   |
| Btrfs   | 27        | 0.86%   |
| Ext2    | 22        | 0.7%    |
| Unknown | 17        | 0.54%   |
| Xfs     | 4         | 0.13%   |
| Ext3    | 3         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2670      | 84.84%  |
| GPT     | 363       | 11.53%  |
| MBR     | 114       | 3.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2970      | 94.92%  |
| Yes       | 159       | 5.08%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2632      | 84.22%  |
| Yes       | 493       | 15.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 701       | 22.55%  |
| Lenovo              | 495       | 15.93%  |
| Dell                | 478       | 15.38%  |
| ASUSTek Computer    | 297       | 9.56%   |
| Acer                | 251       | 8.08%   |
| Toshiba             | 162       | 5.21%   |
| Apple               | 90        | 2.9%    |
| Samsung Electronics | 60        | 1.93%   |
| Sony                | 55        | 1.77%   |
| MSI                 | 46        | 1.48%   |
| Google              | 32        | 1.03%   |
| Unknown             | 30        | 0.97%   |
| Packard Bell        | 29        | 0.93%   |
| Positivo            | 23        | 0.74%   |
| HUAWEI              | 22        | 0.71%   |
| Fujitsu Siemens     | 20        | 0.64%   |
| Fujitsu             | 18        | 0.58%   |
| Medion              | 17        | 0.55%   |
| Notebook            | 13        | 0.42%   |
| Alienware           | 13        | 0.42%   |
| Chuwi               | 10        | 0.32%   |
| Panasonic           | 9         | 0.29%   |
| AMI                 | 9         | 0.29%   |
| Multilaser          | 8         | 0.26%   |
| Gateway             | 8         | 0.26%   |
| eMachines           | 8         | 0.26%   |
| Itautec             | 7         | 0.23%   |
| Semp Toshiba        | 6         | 0.19%   |
| LG Electronics      | 6         | 0.19%   |
| Insyde              | 6         | 0.19%   |
| GPU Company         | 6         | 0.19%   |
| Digibras            | 6         | 0.19%   |
| Thomson             | 5         | 0.16%   |
| NEC Computers       | 5         | 0.16%   |
| Intel               | 5         | 0.16%   |
| Ematic              | 5         | 0.16%   |
| Clevo               | 5         | 0.16%   |
| TrekStor            | 4         | 0.13%   |
| Razer               | 4         | 0.13%   |
| Quanta              | 4         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Unknown                   | 59        | 1.9%    |
| HP Notebook               | 31        | 1%      |
| HP Pavilion Notebook      | 17        | 0.55%   |
| HP Pavilion dv6           | 17        | 0.55%   |
| HP 15                     | 17        | 0.55%   |
| HP Pavilion dv7           | 14        | 0.45%   |
| HP Pavilion 15            | 13        | 0.42%   |
| Toshiba Satellite C660    | 10        | 0.32%   |
| Dell Latitude E6400       | 10        | 0.32%   |
| Dell Latitude D630        | 10        | 0.32%   |
| Dell Inspiron 1545        | 10        | 0.32%   |
| HP Pavilion g7            | 9         | 0.29%   |
| HP Pavilion g6            | 9         | 0.29%   |
| Apple MacBookPro8,1       | 9         | 0.29%   |
| HP Laptop 15-bw0xx        | 8         | 0.26%   |
| Dell Latitude E6540       | 8         | 0.26%   |
| Dell Inspiron 15-3567     | 8         | 0.26%   |
| HP Pavilion dv6700        | 7         | 0.23%   |
| HP EliteBook 8460p        | 7         | 0.23%   |
| HP EliteBook 840 G1       | 7         | 0.23%   |
| Dell Latitude E6410       | 7         | 0.23%   |
| Dell Inspiron 3521        | 7         | 0.23%   |
| Dell Inspiron 1525        | 7         | 0.23%   |
| Apple MacBookPro12,1      | 7         | 0.23%   |
| Apple MacBookPro11,1      | 7         | 0.23%   |
| Toshiba Satellite A100    | 6         | 0.19%   |
| HP ProBook 640 G1         | 6         | 0.19%   |
| HP ProBook 4540s          | 6         | 0.19%   |
| HP Pavilion 17            | 6         | 0.19%   |
| HP Laptop 15-db0xxx       | 6         | 0.19%   |
| HP Compaq Presario CQ60   | 6         | 0.19%   |
| Dell Latitude E6520       | 6         | 0.19%   |
| Dell Latitude E6430       | 6         | 0.19%   |
| Dell Latitude E5470       | 6         | 0.19%   |
| Dell Inspiron 7520        | 6         | 0.19%   |
| Positivo Mobile           | 5         | 0.16%   |
| Itautec Infoway           | 5         | 0.16%   |
| HUAWEI BOHK-WAX9X         | 5         | 0.16%   |
| HP Stream Notebook        | 5         | 0.16%   |
| HP Stream Laptop 14-ax0XX | 5         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 208       | 6.69%   |
| HP Pavilion           | 177       | 5.69%   |
| Dell Latitude         | 177       | 5.69%   |
| Acer Aspire           | 177       | 5.69%   |
| Dell Inspiron         | 174       | 5.6%    |
| Lenovo IdeaPad        | 153       | 4.92%   |
| Toshiba Satellite     | 138       | 4.44%   |
| HP EliteBook          | 90        | 2.9%    |
| HP ProBook            | 75        | 2.41%   |
| HP Laptop             | 66        | 2.12%   |
| Unknown               | 59        | 1.9%    |
| HP Compaq             | 54        | 1.74%   |
| ASUS VivoBook         | 42        | 1.35%   |
| Dell Vostro           | 36        | 1.16%   |
| HP Notebook           | 31        | 1%      |
| Packard Bell EasyNote | 27        | 0.87%   |
| Dell XPS              | 26        | 0.84%   |
| HP ENVY               | 24        | 0.77%   |
| HP Stream             | 23        | 0.74%   |
| Dell Precision        | 22        | 0.71%   |
| HP 15                 | 19        | 0.61%   |
| ASUS ZenBook          | 19        | 0.61%   |
| ASUS ROG              | 17        | 0.55%   |
| HP Presario           | 16        | 0.51%   |
| Lenovo Yoga           | 15        | 0.48%   |
| HP 255                | 14        | 0.45%   |
| HP OMEN               | 13        | 0.42%   |
| Apple MacBookPro8     | 13        | 0.42%   |
| HP ZBook              | 12        | 0.39%   |
| Fujitsu LIFEBOOK      | 12        | 0.39%   |
| Dell Studio           | 12        | 0.39%   |
| Apple MacBookPro11    | 12        | 0.39%   |
| Acer TravelMate       | 12        | 0.39%   |
| Lenovo Legion         | 11        | 0.35%   |
| Fujitsu Siemens AMILO | 11        | 0.35%   |
| Dell System           | 10        | 0.32%   |
| ASUS ASUS             | 10        | 0.32%   |
| Toshiba PORTEGE       | 9         | 0.29%   |
| Apple MacBookPro5     | 9         | 0.29%   |
| Acer Swift            | 9         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 277       | 8.91%   |
| 2012    | 261       | 8.4%    |
| 2013    | 251       | 8.08%   |
| 2010    | 219       | 7.05%   |
| 2008    | 208       | 6.69%   |
| 2018    | 198       | 6.37%   |
| 2014    | 193       | 6.21%   |
| 2019    | 185       | 5.95%   |
| 2017    | 181       | 5.82%   |
| 2021    | 175       | 5.63%   |
| 2015    | 170       | 5.47%   |
| 2020    | 158       | 5.08%   |
| 2016    | 158       | 5.08%   |
| 2007    | 149       | 4.79%   |
| 2009    | 147       | 4.73%   |
| 2006    | 56        | 1.8%    |
| 2022    | 53        | 1.71%   |
| 2005    | 37        | 1.19%   |
| 2023    | 23        | 0.74%   |
| Unknown | 6         | 0.19%   |
| 2003    | 2         | 0.06%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3108      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2745      | 87.7%   |
| Enabled  | 385       | 12.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3071      | 98.81%  |
| Yes  | 37        | 1.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 910       | 29.03%  |
| 4.01-8.0    | 899       | 28.68%  |
| 8.01-16.0   | 381       | 12.15%  |
| 1.01-2.0    | 332       | 10.59%  |
| 16.01-24.0  | 305       | 9.73%   |
| 2.01-3.0    | 115       | 3.67%   |
| 32.01-64.0  | 92        | 2.93%   |
| 0.51-1.0    | 72        | 2.3%    |
| 64.01-256.0 | 15        | 0.48%   |
| 24.01-32.0  | 14        | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1425      | 42.36%  |
| 2.01-3.0   | 955       | 28.39%  |
| 3.01-4.0   | 379       | 11.27%  |
| 0.51-1.0   | 282       | 8.38%   |
| 4.01-8.0   | 259       | 7.7%    |
| 8.01-16.0  | 34        | 1.01%   |
| 0.01-0.5   | 25        | 0.74%   |
| 24.01-32.0 | 3         | 0.09%   |
| 16.01-24.0 | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2421      | 76.64%  |
| 2      | 648       | 20.51%  |
| 3      | 65        | 2.06%   |
| 0      | 12        | 0.38%   |
| 4      | 8         | 0.25%   |
| 5      | 3         | 0.09%   |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1639      | 52.5%   |
| Yes       | 1483      | 47.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2548      | 81.77%  |
| No        | 568       | 18.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3009      | 96.72%  |
| No        | 102       | 3.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2042      | 64.99%  |
| No        | 1100      | 35.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 627       | 20.08%  |
| Germany      | 283       | 9.06%   |
| Brazil       | 227       | 7.27%   |
| UK           | 173       | 5.54%   |
| Italy        | 126       | 4.04%   |
| Canada       | 116       | 3.72%   |
| Spain        | 109       | 3.49%   |
| India        | 106       | 3.4%    |
| France       | 103       | 3.3%    |
| Netherlands  | 83        | 2.66%   |
| Poland       | 74        | 2.37%   |
| Mexico       | 68        | 2.18%   |
| Australia    | 54        | 1.73%   |
| Portugal     | 50        | 1.6%    |
| Sweden       | 42        | 1.35%   |
| Czechia      | 42        | 1.35%   |
| Russia       | 40        | 1.28%   |
| Argentina    | 40        | 1.28%   |
| Belgium      | 38        | 1.22%   |
| South Africa | 37        | 1.19%   |
| Austria      | 36        | 1.15%   |
| Romania      | 34        | 1.09%   |
| Turkey       | 33        | 1.06%   |
| Switzerland  | 32        | 1.02%   |
| Indonesia    | 30        | 0.96%   |
| Greece       | 25        | 0.8%    |
| New Zealand  | 21        | 0.67%   |
| Japan        | 21        | 0.67%   |
| Norway       | 19        | 0.61%   |
| Hungary      | 19        | 0.61%   |
| Chile        | 19        | 0.61%   |
| Colombia     | 18        | 0.58%   |
| Serbia       | 17        | 0.54%   |
| Egypt        | 17        | 0.54%   |
| Bulgaria     | 15        | 0.48%   |
| Ireland      | 13        | 0.42%   |
| Denmark      | 13        | 0.42%   |
| Ukraine      | 12        | 0.38%   |
| Philippines  | 12        | 0.38%   |
| Slovakia     | 11        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 24        | 0.73%   |
| Vienna         | 21        | 0.64%   |
| Berlin         | 21        | 0.64%   |
| Sydney         | 19        | 0.58%   |
| Madrid         | 19        | 0.58%   |
| Munich         | 17        | 0.52%   |
| Rome           | 16        | 0.49%   |
| Milan          | 15        | 0.46%   |
| Johannesburg   | 15        | 0.46%   |
| Hamburg        | 14        | 0.43%   |
| Athens         | 14        | 0.43%   |
| Paris          | 13        | 0.4%    |
| New York       | 13        | 0.4%    |
| Montreal       | 13        | 0.4%    |
| Mexico City    | 13        | 0.4%    |
| Istanbul       | 13        | 0.4%    |
| Amsterdam      | 13        | 0.4%    |
| Rio de Janeiro | 12        | 0.37%   |
| Jakarta        | 12        | 0.37%   |
| Auckland       | 12        | 0.37%   |
| Toronto        | 11        | 0.34%   |
| Prague         | 11        | 0.34%   |
| Moscow         | 11        | 0.34%   |
| Dallas         | 11        | 0.34%   |
| Cairo          | 11        | 0.34%   |
| Warsaw         | 10        | 0.31%   |
| Stuttgart      | 10        | 0.31%   |
| Stockholm      | 10        | 0.31%   |
| Seattle        | 10        | 0.31%   |
| Denver         | 10        | 0.31%   |
| Delhi          | 10        | 0.31%   |
| Buenos Aires   | 10        | 0.31%   |
| Bucharest      | 10        | 0.31%   |
| Bengaluru      | 10        | 0.31%   |
| Belgrade       | 10        | 0.31%   |
| Nairobi        | 9         | 0.28%   |
| Melbourne      | 9         | 0.28%   |
| Krakow         | 9         | 0.28%   |
| Kolkata        | 9         | 0.28%   |
| Barcelona      | 9         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 456       | 558    | 12.56%  |
| WDC                 | 437       | 534    | 12.03%  |
| Samsung Electronics | 413       | 557    | 11.37%  |
| Toshiba             | 365       | 419    | 10.05%  |
| Unknown             | 315       | 430    | 8.67%   |
| SanDisk             | 213       | 255    | 5.86%   |
| Hitachi             | 173       | 202    | 4.76%   |
| Kingston            | 164       | 200    | 4.52%   |
| Crucial             | 118       | 143    | 3.25%   |
| HGST                | 107       | 130    | 2.95%   |
| Intel               | 91        | 113    | 2.51%   |
| SK hynix            | 83        | 97     | 2.29%   |
| Micron Technology   | 66        | 79     | 1.82%   |
| A-DATA Technology   | 45        | 51     | 1.24%   |
| Fujitsu             | 44        | 47     | 1.21%   |
| China               | 44        | 55     | 1.21%   |
| Apple               | 40        | 46     | 1.1%    |
| KIOXIA              | 28        | 33     | 0.77%   |
| Intenso             | 27        | 28     | 0.74%   |
| PNY                 | 21        | 25     | 0.58%   |
| SPCC                | 20        | 26     | 0.55%   |
| Unknown             | 19        | 21     | 0.52%   |
| Phison              | 17        | 20     | 0.47%   |
| Netac               | 17        | 17     | 0.47%   |
| LITEONIT            | 17        | 20     | 0.47%   |
| LITEON              | 17        | 21     | 0.47%   |
| Patriot             | 16        | 20     | 0.44%   |
| Transcend           | 15        | 20     | 0.41%   |
| GOODRAM             | 13        | 14     | 0.36%   |
| Team                | 12        | 13     | 0.33%   |
| JMicron Technology  | 10        | 11     | 0.28%   |
| Silicon Motion      | 9         | 9      | 0.25%   |
| OCZ                 | 9         | 10     | 0.25%   |
| SABRENT             | 8         | 9      | 0.22%   |
| Hewlett-Packard     | 7         | 7      | 0.19%   |
| Phison Electronics  | 6         | 6      | 0.17%   |
| ASMT                | 6         | 6      | 0.17%   |
| Plextor             | 5         | 5      | 0.14%   |
| Lite-On             | 5         | 7      | 0.14%   |
| KingSpec            | 5         | 5      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                            | 113       | 3%      |
| Unknown MMC Card  64GB                            | 82        | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB                    | 50        | 1.33%   |
| Toshiba MQ01ABF050 500GB                          | 49        | 1.3%    |
| Toshiba MQ01ABD100 1TB                            | 42        | 1.11%   |
| Seagate ST500LT012-1DG142 500GB                   | 39        | 1.03%   |
| Kingston SA400S37240G 240GB SSD                   | 39        | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 35        | 0.93%   |
| Unknown MMC Card  128GB                           | 33        | 0.88%   |
| Toshiba MQ04ABF100 1TB                            | 33        | 0.88%   |
| Seagate ST9500325AS 500GB                         | 28        | 0.74%   |
| Kingston SA400S37480G 480GB SSD                   | 28        | 0.74%   |
| Unknown MMC Card  16GB                            | 27        | 0.72%   |
| Samsung NVMe SSD Drive 512GB                      | 24        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                   | 23        | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 21        | 0.56%   |
| Crucial CT240BX500SSD1 240GB                      | 21        | 0.56%   |
| SanDisk NVMe SSD Drive 256GB                      | 20        | 0.53%   |
| HGST HTS725050A7E630 500GB                        | 20        | 0.53%   |
| HGST HTS721010A9E630 1TB                          | 20        | 0.53%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 19        | 0.5%    |
| Unknown                                           | 19        | 0.5%    |
| HGST HTS541010A9E680 1TB                          | 18        | 0.48%   |
| Samsung SSD 850 EVO 500GB                         | 17        | 0.45%   |
| Intel NVMe SSD Drive 512GB                        | 17        | 0.45%   |
| Hitachi HTS545032B9A300 320GB                     | 17        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                      | 17        | 0.45%   |
| Seagate Expansion 1TB                             | 16        | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                      | 16        | 0.42%   |
| HGST HTS545050A7E680 500GB                        | 16        | 0.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 15        | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB                          | 14        | 0.37%   |
| Samsung SSD 860 EVO 500GB                         | 14        | 0.37%   |
| Unknown SD/MMC/MS PRO 16GB                        | 13        | 0.34%   |
| Samsung SSD 860 EVO 250GB                         | 13        | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 12        | 0.32%   |
| Samsung HM160HI 160GB                             | 12        | 0.32%   |
| HGST HTS545050A7E380 500GB                        | 12        | 0.32%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 11        | 0.29%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 11        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 450       | 548    | 29.43%  |
| WDC                 | 372       | 445    | 24.33%  |
| Toshiba             | 305       | 345    | 19.95%  |
| Hitachi             | 173       | 202    | 11.31%  |
| HGST                | 107       | 130    | 7%      |
| Samsung Electronics | 47        | 52     | 3.07%   |
| Fujitsu             | 44        | 47     | 2.88%   |
| Unknown             | 13        | 19     | 0.85%   |
| Apple               | 5         | 5      | 0.33%   |
| IBM/Hitachi         | 4         | 5      | 0.26%   |
| JMicron Technology  | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.07%   |
| SSK                 | 1         | 1      | 0.07%   |
| SABRENT             | 1         | 1      | 0.07%   |
| Pioneer             | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 223       | 308    | 18.8%   |
| Kingston            | 144       | 177    | 12.14%  |
| SanDisk             | 120       | 145    | 10.12%  |
| Crucial             | 116       | 139    | 9.78%   |
| WDC                 | 48        | 64     | 4.05%   |
| China               | 43        | 54     | 3.63%   |
| Intel               | 41        | 47     | 3.46%   |
| A-DATA Technology   | 38        | 44     | 3.2%    |
| Toshiba             | 33        | 37     | 2.78%   |
| SK hynix            | 30        | 34     | 2.53%   |
| Apple               | 30        | 34     | 2.53%   |
| Micron Technology   | 29        | 34     | 2.45%   |
| PNY                 | 21        | 25     | 1.77%   |
| SPCC                | 19        | 25     | 1.6%    |
| Intenso             | 19        | 19     | 1.6%    |
| Netac               | 17        | 17     | 1.43%   |
| LITEONIT            | 17        | 20     | 1.43%   |
| LITEON              | 17        | 21     | 1.43%   |
| Patriot             | 16        | 20     | 1.35%   |
| Transcend           | 15        | 20     | 1.26%   |
| Team                | 12        | 13     | 1.01%   |
| GOODRAM             | 12        | 13     | 1.01%   |
| OCZ                 | 9         | 10     | 0.76%   |
| SABRENT             | 7         | 8      | 0.59%   |
| ASMT                | 6         | 6      | 0.51%   |
| Unknown             | 6         | 8      | 0.51%   |
| Plextor             | 5         | 5      | 0.42%   |
| KingSpec            | 5         | 5      | 0.42%   |
| Hewlett-Packard     | 5         | 5      | 0.42%   |
| Phison              | 4         | 5      | 0.34%   |
| Apacer              | 4         | 4      | 0.34%   |
| Verbatim            | 3         | 3      | 0.25%   |
| Mushkin             | 3         | 3      | 0.25%   |
| Lexar               | 3         | 3      | 0.25%   |
| BHT                 | 3         | 4      | 0.25%   |
| Vaseky              | 2         | 3      | 0.17%   |
| TO Exter            | 2         | 3      | 0.17%   |
| Teclast             | 2         | 2      | 0.17%   |
| TCSUNBOW            | 2         | 2      | 0.17%   |
| Leven               | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1497      | 1807   | 42.48%  |
| SSD     | 1128      | 1449   | 32.01%  |
| NVMe    | 528       | 688    | 14.98%  |
| MMC     | 318       | 429    | 9.02%   |
| Unknown | 53        | 58     | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2459      | 3178   | 72.3%   |
| NVMe | 522       | 680    | 15.35%  |
| MMC  | 318       | 429    | 9.35%   |
| SAS  | 102       | 144    | 3%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1938      | 2418   | 74.54%  |
| 0.51-1.0   | 602       | 755    | 23.15%  |
| 1.01-2.0   | 48        | 64     | 1.85%   |
| 3.01-4.0   | 5         | 8      | 0.19%   |
| 4.01-10.0  | 4         | 8      | 0.15%   |
| 2.01-3.0   | 3         | 3      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1140      | 35.64%  |
| 251-500        | 816       | 25.51%  |
| 501-1000       | 397       | 12.41%  |
| 51-100         | 353       | 11.03%  |
| 21-50          | 211       | 6.6%    |
| 1001-2000      | 101       | 3.16%   |
| 1-20           | 99        | 3.09%   |
| Unknown        | 31        | 0.97%   |
| More than 3000 | 28        | 0.88%   |
| 2001-3000      | 23        | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1630      | 48.95%  |
| 21-50          | 817       | 24.53%  |
| 51-100         | 346       | 10.39%  |
| 101-250        | 293       | 8.8%    |
| 251-500        | 128       | 3.84%   |
| 501-1000       | 52        | 1.56%   |
| Unknown        | 31        | 0.93%   |
| 1001-2000      | 17        | 0.51%   |
| More than 3000 | 11        | 0.33%   |
| 2001-3000      | 5         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 3         | 3      | 4.23%   |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 4.23%   |
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 2.82%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 2.82%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 2.82%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 2.82%   |
| Seagate ST1000LM048-2E7172 1TB                   | 2         | 2      | 2.82%   |
| Seagate ST1000LM035-1RK172 1TB                   | 2         | 2      | 2.82%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 2.82%   |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 2.82%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.41%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.41%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.41%   |
| WDC WD3200BPVT-55ZEST0 320GB                     | 1         | 1      | 1.41%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.41%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.41%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.41%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.41%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.41%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.41%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.41%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.41%   |
| Toshiba MK5061GSY 500GB                          | 1         | 1      | 1.41%   |
| Toshiba MK2046GSX 200GB                          | 1         | 1      | 1.41%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.41%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.41%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 1.41%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.41%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.41%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.41%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.41%   |
| Seagate ST9160314AS 160GB                        | 1         | 1      | 1.41%   |
| Seagate ST9120822AS 120GB                        | 1         | 1      | 1.41%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.41%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.41%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.41%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.41%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 1.41%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 23     | 32.39%  |
| Toshiba             | 11        | 11     | 15.49%  |
| WDC                 | 8         | 8      | 11.27%  |
| HGST                | 7         | 8      | 9.86%   |
| Hitachi             | 5         | 5      | 7.04%   |
| Samsung Electronics | 4         | 4      | 5.63%   |
| Kingston            | 3         | 3      | 4.23%   |
| SK hynix            | 2         | 2      | 2.82%   |
| Teclast             | 1         | 1      | 1.41%   |
| POLION              | 1         | 1      | 1.41%   |
| Micron Technology   | 1         | 1      | 1.41%   |
| LITEONIT            | 1         | 1      | 1.41%   |
| Intel               | 1         | 1      | 1.41%   |
| Hewlett-Packard     | 1         | 1      | 1.41%   |
| Drevo               | 1         | 1      | 1.41%   |
| Unknown             | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 23     | 42.59%  |
| Toshiba             | 9         | 9      | 16.67%  |
| WDC                 | 8         | 8      | 14.81%  |
| HGST                | 7         | 8      | 12.96%  |
| Hitachi             | 5         | 5      | 9.26%   |
| Samsung Electronics | 2         | 2      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 55     | 76.06%  |
| SSD  | 15        | 15     | 21.13%  |
| NVMe | 2         | 2      | 2.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2804      | 4007   | 88.59%  |
| Works    | 288       | 349    | 9.1%    |
| Malfunc  | 70        | 72     | 2.21%   |
| Failed   | 2         | 2      | 0.06%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2261      | 68.7%   |
| AMD                              | 393       | 11.94%  |
| Samsung Electronics              | 176       | 5.35%   |
| SanDisk                          | 100       | 3.04%   |
| Nvidia                           | 51        | 1.55%   |
| SK hynix                         | 50        | 1.52%   |
| Micron Technology                | 38        | 1.15%   |
| Silicon Integrated Systems [SiS] | 31        | 0.94%   |
| Toshiba America Info Systems     | 29        | 0.88%   |
| KIOXIA                           | 28        | 0.85%   |
| Kingston Technology Company      | 24        | 0.73%   |
| Phison Electronics               | 19        | 0.58%   |
| VIA Technologies                 | 12        | 0.36%   |
| Silicon Motion                   | 12        | 0.36%   |
| ADATA Technology                 | 10        | 0.3%    |
| Micron/Crucial Technology        | 7         | 0.21%   |
| Marvell Technology Group         | 6         | 0.18%   |
| Union Memory (Shenzhen)          | 5         | 0.15%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.15%   |
| Lite-On Technology               | 5         | 0.15%   |
| JMicron Technology               | 5         | 0.15%   |
| Realtek Semiconductor            | 4         | 0.12%   |
| ASMedia Technology               | 4         | 0.12%   |
| Apple                            | 4         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Solid State Storage Technology   | 2         | 0.06%   |
| Silicon Image                    | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 300       | 8.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 252       | 6.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 220       | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 202       | 5.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 179       | 4.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 163       | 4.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 124       | 3.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 122       | 3.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 103       | 2.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 103       | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 82        | 2.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 69        | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 66        | 1.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 58        | 1.58%   |
| Intel Volume Management Device NVMe RAID Controller                              | 57        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 54        | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 53        | 1.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 52        | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 51        | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 47        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 45        | 1.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 41        | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 39        | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 38        | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 37        | 1.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 35        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 32        | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                              | 31        | 0.84%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 30        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 27        | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 25        | 0.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 24        | 0.65%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 24        | 0.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 24        | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 24        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 23        | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                            | 23        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 21        | 0.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 21        | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 19        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2253      | 64.61%  |
| NVMe | 523       | 15%     |
| IDE  | 464       | 13.31%  |
| RAID | 247       | 7.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2611      | 84.01%  |
| AMD          | 496       | 15.96%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 39        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 36        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 35        | 1.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 32        | 1.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 31        | 1%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.9%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 28        | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 27        | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 0.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 26        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 26        | 0.84%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 22        | 0.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.71%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 22        | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.71%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 22        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 21        | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 20        | 0.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 20        | 0.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 20        | 0.64%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 20        | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 19        | 0.61%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.61%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 19        | 0.61%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 19        | 0.61%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.61%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.61%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.58%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 18        | 0.58%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 18        | 0.58%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 17        | 0.55%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 17        | 0.55%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 17        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 664       | 21.34%  |
| Intel Core i7           | 466       | 14.98%  |
| Intel Core i3           | 304       | 9.77%   |
| Intel Celeron           | 273       | 8.78%   |
| Intel Core 2 Duo        | 255       | 8.2%    |
| Intel Atom              | 170       | 5.46%   |
| Other                   | 133       | 4.28%   |
| Intel Pentium           | 103       | 3.31%   |
| AMD Ryzen 5             | 78        | 2.51%   |
| AMD Ryzen 7             | 54        | 1.74%   |
| AMD A6                  | 51        | 1.64%   |
| Intel Pentium Dual-Core | 45        | 1.45%   |
| Intel Genuine           | 42        | 1.35%   |
| AMD A4                  | 41        | 1.32%   |
| Intel Pentium Dual      | 33        | 1.06%   |
| Intel Core 2            | 27        | 0.87%   |
| Intel Pentium M         | 26        | 0.84%   |
| AMD A8                  | 26        | 0.84%   |
| AMD Ryzen 3             | 25        | 0.8%    |
| AMD A10                 | 25        | 0.8%    |
| Intel Celeron M         | 24        | 0.77%   |
| AMD E1                  | 22        | 0.71%   |
| AMD E                   | 20        | 0.64%   |
| AMD Turion 64 X2 Mobile | 17        | 0.55%   |
| Intel Core M            | 12        | 0.39%   |
| Intel Pentium Silver    | 11        | 0.35%   |
| AMD Ryzen 9             | 11        | 0.35%   |
| Intel Celeron Dual-Core | 10        | 0.32%   |
| AMD Turion 64 Mobile    | 9         | 0.29%   |
| AMD E2                  | 9         | 0.29%   |
| AMD Athlon II           | 9         | 0.29%   |
| AMD Athlon 64 X2        | 9         | 0.29%   |
| Intel Core Duo          | 8         | 0.26%   |
| AMD Sempron             | 7         | 0.23%   |
| AMD Mobile Sempron      | 7         | 0.23%   |
| AMD Athlon              | 7         | 0.23%   |
| AMD C-50                | 6         | 0.19%   |
| AMD Athlon X2           | 6         | 0.19%   |
| Intel Core m5           | 5         | 0.16%   |
| AMD Ryzen 7 PRO         | 5         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1957      | 62.91%  |
| 4      | 773       | 24.85%  |
| 1      | 188       | 6.04%   |
| 6      | 93        | 2.99%   |
| 8      | 75        | 2.41%   |
| 10     | 10        | 0.32%   |
| 14     | 5         | 0.16%   |
| 12     | 4         | 0.13%   |
| 16     | 3         | 0.1%    |
| 3      | 2         | 0.06%   |
| 24     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3108      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1829      | 58.85%  |
| 1      | 1279      | 41.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2988      | 96.11%  |
| 32-bit         | 119       | 3.83%   |
| Unknown        | 2         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 270       | 8.57%   |
| Unknown    | 262       | 8.31%   |
| 0x306a9    | 228       | 7.23%   |
| 0x1067a    | 167       | 5.3%    |
| 0x40651    | 138       | 4.38%   |
| 0x20655    | 110       | 3.49%   |
| 0x406e3    | 106       | 3.36%   |
| 0x306d4    | 102       | 3.24%   |
| 0x6fd      | 92        | 2.92%   |
| 0x30678    | 89        | 2.82%   |
| 0x306c3    | 83        | 2.63%   |
| 0x806e9    | 81        | 2.57%   |
| 0x806ea    | 73        | 2.32%   |
| 0x806c1    | 70        | 2.22%   |
| 0x406c4    | 68        | 2.16%   |
| 0x806ec    | 61        | 1.94%   |
| 0x10676    | 54        | 1.71%   |
| 0x906ea    | 45        | 1.43%   |
| 0x706a8    | 43        | 1.36%   |
| 0x506c9    | 42        | 1.33%   |
| 0x406c3    | 42        | 1.33%   |
| 0x20652    | 41        | 1.3%    |
| 0x706e5    | 40        | 1.27%   |
| 0x906e9    | 38        | 1.21%   |
| 0x106ca    | 35        | 1.11%   |
| 0x08108109 | 34        | 1.08%   |
| 0x06006705 | 34        | 1.08%   |
| 0x6e8      | 30        | 0.95%   |
| 0x6d8      | 30        | 0.95%   |
| 0x07030105 | 26        | 0.82%   |
| 0x05000119 | 26        | 0.82%   |
| 0x0700010f | 25        | 0.79%   |
| 0x6f6      | 24        | 0.76%   |
| 0x106c2    | 24        | 0.76%   |
| 0x08108102 | 24        | 0.76%   |
| 0x706a1    | 22        | 0.7%    |
| 0x6fb      | 22        | 0.7%    |
| 0x0a50000c | 22        | 0.7%    |
| 0x06001119 | 22        | 0.7%    |
| 0xa0652    | 20        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 346       | 11.13%  |
| SandyBridge      | 276       | 8.88%   |
| IvyBridge        | 239       | 7.69%   |
| Haswell          | 239       | 7.69%   |
| Penryn           | 233       | 7.5%    |
| Silvermont       | 230       | 7.4%    |
| Core             | 185       | 5.95%   |
| Westmere         | 158       | 5.08%   |
| Skylake          | 129       | 4.15%   |
| Broadwell        | 102       | 3.28%   |
| P6               | 84        | 2.7%    |
| TigerLake        | 80        | 2.57%   |
| Bonnell          | 70        | 2.25%   |
| Goldmont plus    | 68        | 2.19%   |
| Excavator        | 63        | 2.03%   |
| Zen+             | 61        | 1.96%   |
| IceLake          | 52        | 1.67%   |
| K8 Hammer        | 48        | 1.54%   |
| Goldmont         | 44        | 1.42%   |
| Puma             | 42        | 1.35%   |
| Unknown          | 42        | 1.35%   |
| Bobcat           | 39        | 1.25%   |
| Zen 2            | 38        | 1.22%   |
| Zen 3            | 36        | 1.16%   |
| Jaguar           | 32        | 1.03%   |
| Piledriver       | 27        | 0.87%   |
| CometLake        | 25        | 0.8%    |
| K10              | 22        | 0.71%   |
| K10 Llano        | 20        | 0.64%   |
| Alderlake Hybrid | 18        | 0.58%   |
| K8 & K10 hybrid  | 17        | 0.55%   |
| Zen              | 15        | 0.48%   |
| Nehalem          | 11        | 0.35%   |
| Tremont          | 7         | 0.23%   |
| Steamroller      | 6         | 0.19%   |
| NetBurst         | 4         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2285      | 62.43%  |
| AMD                              | 689       | 18.83%  |
| Nvidia                           | 647       | 17.68%  |
| Silicon Integrated Systems [SiS] | 28        | 0.77%   |
| VIA Technologies                 | 11        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 247       | 6.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 227       | 5.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 144       | 3.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 142       | 3.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 118       | 3.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 116       | 2.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 114       | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 98        | 2.53%   |
| Intel HD Graphics 620                                                                    | 86        | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 81        | 2.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 81        | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 81        | 2.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 75        | 1.94%   |
| Intel UHD Graphics 620                                                                   | 72        | 1.86%   |
| Intel HD Graphics 5500                                                                   | 72        | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 62        | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 62        | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 60        | 1.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 50        | 1.29%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 1.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 47        | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 1.11%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 38        | 0.98%   |
| Intel HD Graphics 630                                                                    | 36        | 0.93%   |
| Intel HD Graphics 500                                                                    | 36        | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 36        | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 31        | 0.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 30        | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 29        | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 28        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 27        | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 27        | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 27        | 0.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 25        | 0.65%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 24        | 0.62%   |
| AMD Lucienne                                                                             | 22        | 0.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 0.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1768      | 56.79%  |
| 1 x AMD        | 479       | 15.39%  |
| Intel + Nvidia | 389       | 12.5%   |
| 1 x Nvidia     | 212       | 6.81%   |
| Intel + AMD    | 122       | 3.92%   |
| 2 x AMD        | 49        | 1.57%   |
| AMD + Nvidia   | 40        | 1.28%   |
| 1 x SiS        | 28        | 0.9%    |
| 1 x VIA        | 11        | 0.35%   |
| Other          | 8         | 0.26%   |
| 2 x Nvidia     | 7         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2703      | 86.58%  |
| Proprietary | 314       | 10.06%  |
| Unknown     | 105       | 3.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2072      | 65.8%   |
| 0.01-0.5   | 491       | 15.59%  |
| 1.01-2.0   | 262       | 8.32%   |
| 0.51-1.0   | 188       | 5.97%   |
| 3.01-4.0   | 85        | 2.7%    |
| 5.01-6.0   | 20        | 0.64%   |
| 7.01-8.0   | 17        | 0.54%   |
| 2.01-3.0   | 12        | 0.38%   |
| 8.01-16.0  | 2         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 613       | 19.44%  |
| LG Display              | 445       | 14.11%  |
| Samsung Electronics     | 420       | 13.32%  |
| Chimei Innolux          | 404       | 12.81%  |
| BOE                     | 384       | 12.18%  |
| Chi Mei Optoelectronics | 120       | 3.8%    |
| Apple                   | 91        | 2.89%   |
| LG Philips              | 78        | 2.47%   |
| Lenovo                  | 54        | 1.71%   |
| Sharp                   | 51        | 1.62%   |
| Goldstar                | 46        | 1.46%   |
| Dell                    | 43        | 1.36%   |
| InfoVision              | 36        | 1.14%   |
| PANDA                   | 31        | 0.98%   |
| CPT                     | 22        | 0.7%    |
| Hewlett-Packard         | 20        | 0.63%   |
| HannStar                | 18        | 0.57%   |
| Toshiba                 | 17        | 0.54%   |
| Sony                    | 15        | 0.48%   |
| Acer                    | 15        | 0.48%   |
| Philips                 | 12        | 0.38%   |
| BenQ                    | 12        | 0.38%   |
| Quanta Display          | 11        | 0.35%   |
| Vizio                   | 10        | 0.32%   |
| LGD                     | 10        | 0.32%   |
| InnoLux Display         | 10        | 0.32%   |
| AOC                     | 10        | 0.32%   |
| Seiko/Epson             | 9         | 0.29%   |
| Panasonic               | 8         | 0.25%   |
| Ancor Communications    | 8         | 0.25%   |
| Eizo                    | 7         | 0.22%   |
| ASUSTek Computer        | 6         | 0.19%   |
| SLD                     | 5         | 0.16%   |
| Iiyama                  | 5         | 0.16%   |
| BOE Technology Group    | 5         | 0.16%   |
| Unknown                 | 5         | 0.16%   |
| ViewSonic               | 4         | 0.13%   |
| Unknown                 | 4         | 0.13%   |
| KDC                     | 4         | 0.13%   |
| IBM                     | 4         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 35        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 25        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 22        | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 20        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 19        | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.57%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 17        | 0.53%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.5%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 16        | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.47%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 15        | 0.47%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 14        | 0.44%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 14        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.41%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 12        | 0.38%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 12        | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.38%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 11        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 11        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 11        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 11        | 0.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.28%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.28%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.28%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.28%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 9         | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 8         | 0.25%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 8         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 8         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 8         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1279      | 41.63%  |
| 1920x1080 (FHD)    | 874       | 28.45%  |
| 1280x800 (WXGA)    | 243       | 7.91%   |
| 1600x900 (HD+)     | 200       | 6.51%   |
| 1440x900 (WXGA+)   | 84        | 2.73%   |
| 3840x2160 (4K)     | 62        | 2.02%   |
| 1024x600           | 47        | 1.53%   |
| 1920x1200 (WUXGA)  | 33        | 1.07%   |
| 1680x1050 (WSXGA+) | 32        | 1.04%   |
| 2560x1600          | 28        | 0.91%   |
| 2560x1440 (QHD)    | 23        | 0.75%   |
| 1360x768           | 14        | 0.46%   |
| 1280x1024 (SXGA)   | 14        | 0.46%   |
| 2880x1800          | 12        | 0.39%   |
| 2560x1080          | 11        | 0.36%   |
| 2160x1440          | 11        | 0.36%   |
| 3200x1800 (QHD+)   | 10        | 0.33%   |
| 1024x768 (XGA)     | 10        | 0.33%   |
| Unknown            | 9         | 0.29%   |
| 2256x1504          | 8         | 0.26%   |
| 1280x768           | 8         | 0.26%   |
| 1920x540           | 6         | 0.2%    |
| 3840x2400          | 5         | 0.16%   |
| 3440x1440          | 5         | 0.16%   |
| 3840x1080          | 4         | 0.13%   |
| 1680x945           | 4         | 0.13%   |
| 1400x1050          | 4         | 0.13%   |
| 1920x515           | 3         | 0.1%    |
| 1024x576           | 3         | 0.1%    |
| 5760x1080          | 2         | 0.07%   |
| 3600x1080          | 2         | 0.07%   |
| 2880x1920          | 2         | 0.07%   |
| 2880x1620          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 2240x1400          | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 5760x2160          | 1         | 0.03%   |
| 4480x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1373      | 43.59%  |
| 13      | 432       | 13.71%  |
| 14      | 374       | 11.87%  |
| 17      | 259       | 8.22%   |
| 11      | 117       | 3.71%   |
| 12      | 87        | 2.76%   |
| Unknown | 72        | 2.29%   |
| 10      | 59        | 1.87%   |
| 24      | 51        | 1.62%   |
| 27      | 47        | 1.49%   |
| 23      | 33        | 1.05%   |
| 18      | 31        | 0.98%   |
| 21      | 30        | 0.95%   |
| 16      | 26        | 0.83%   |
| 31      | 23        | 0.73%   |
| 34      | 19        | 0.6%    |
| 19      | 15        | 0.48%   |
| 20      | 12        | 0.38%   |
| 22      | 11        | 0.35%   |
| 54      | 10        | 0.32%   |
| 72      | 9         | 0.29%   |
| 40      | 7         | 0.22%   |
| 84      | 6         | 0.19%   |
| 8       | 5         | 0.16%   |
| 32      | 4         | 0.13%   |
| 25      | 4         | 0.13%   |
| 74      | 3         | 0.1%    |
| 52      | 3         | 0.1%    |
| 49      | 3         | 0.1%    |
| 26      | 3         | 0.1%    |
| 58      | 2         | 0.06%   |
| 48      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 37      | 2         | 0.06%   |
| 36      | 2         | 0.06%   |
| 29      | 2         | 0.06%   |
| 86      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |
| 59      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1958      | 62.36%  |
| 201-300     | 450       | 14.33%  |
| 351-400     | 315       | 10.03%  |
| 501-600     | 129       | 4.11%   |
| 401-500     | 97        | 3.09%   |
| Unknown     | 72        | 2.29%   |
| 601-700     | 30        | 0.96%   |
| 1001-1500   | 27        | 0.86%   |
| 701-800     | 26        | 0.83%   |
| 1501-2000   | 18        | 0.57%   |
| 801-900     | 10        | 0.32%   |
| 101-200     | 5         | 0.16%   |
| 901-1000    | 3         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2356      | 80.68%  |
| 16/10   | 426       | 14.59%  |
| Unknown | 54        | 1.85%   |
| 3/2     | 26        | 0.89%   |
| 4/3     | 19        | 0.65%   |
| 21/9    | 17        | 0.58%   |
| 5/4     | 13        | 0.45%   |
| 32/9    | 3         | 0.1%    |
| 3.73    | 3         | 0.1%    |
| 0.62    | 2         | 0.07%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1372      | 43.61%  |
| 81-90          | 674       | 21.42%  |
| 121-130        | 193       | 6.13%   |
| 71-80          | 126       | 4.01%   |
| 51-60          | 117       | 3.72%   |
| 201-250        | 104       | 3.31%   |
| 61-70          | 85        | 2.7%    |
| Unknown        | 72        | 2.29%   |
| 41-50          | 59        | 1.88%   |
| 131-140        | 59        | 1.88%   |
| 301-350        | 49        | 1.56%   |
| 351-500        | 47        | 1.49%   |
| More than 1000 | 42        | 1.34%   |
| 151-200        | 40        | 1.27%   |
| 141-150        | 39        | 1.24%   |
| 501-1000       | 20        | 0.64%   |
| 111-120        | 17        | 0.54%   |
| 251-300        | 13        | 0.41%   |
| 91-100         | 13        | 0.41%   |
| 1-40           | 5         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1343      | 43.31%  |
| 121-160       | 926       | 29.86%  |
| 51-100        | 522       | 16.83%  |
| 161-240       | 147       | 4.74%   |
| Unknown       | 72        | 2.32%   |
| 1-50          | 46        | 1.48%   |
| More than 240 | 45        | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2701      | 85.39%  |
| 2     | 329       | 10.4%   |
| 0     | 109       | 3.45%   |
| 3     | 21        | 0.66%   |
| 4     | 2         | 0.06%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1565      | 31.06%  |
| Intel                             | 1315      | 26.1%   |
| Qualcomm Atheros                  | 839       | 16.65%  |
| Broadcom                          | 498       | 9.88%   |
| Broadcom Limited                  | 162       | 3.22%   |
| Marvell Technology Group          | 94        | 1.87%   |
| Ralink                            | 63        | 1.25%   |
| Nvidia                            | 45        | 0.89%   |
| TP-Link                           | 36        | 0.71%   |
| MediaTek                          | 35        | 0.69%   |
| Silicon Integrated Systems [SiS]  | 29        | 0.58%   |
| Dell                              | 29        | 0.58%   |
| Ralink Technology                 | 27        | 0.54%   |
| ASIX Electronics                  | 27        | 0.54%   |
| JMicron Technology                | 26        | 0.52%   |
| Samsung Electronics               | 25        | 0.5%    |
| Xiaomi                            | 16        | 0.32%   |
| Sierra Wireless                   | 16        | 0.32%   |
| Hewlett-Packard                   | 15        | 0.3%    |
| Huawei Technologies               | 12        | 0.24%   |
| DisplayLink                       | 12        | 0.24%   |
| Qualcomm Atheros Communications   | 11        | 0.22%   |
| VIA Technologies                  | 10        | 0.2%    |
| Ericsson Business Mobile Networks | 10        | 0.2%    |
| OPPO Electronics                  | 9         | 0.18%   |
| NetGear                           | 9         | 0.18%   |
| ASUSTek Computer                  | 9         | 0.18%   |
| Edimax Technology                 | 8         | 0.16%   |
| AMD                               | 8         | 0.16%   |
| Qualcomm                          | 6         | 0.12%   |
| Motorola PCS                      | 6         | 0.12%   |
| Attansic Technology               | 6         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| Google                            | 4         | 0.08%   |
| D-Link System                     | 4         | 0.08%   |
| D-Link                            | 4         | 0.08%   |
| T & A Mobile Phones               | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| Belkin Components                 | 3         | 0.06%   |
| ZyDAS                             | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 787       | 13.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 427       | 7.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 147       | 2.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 137       | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 125       | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 118       | 1.97%   |
| Intel Wireless 7260                                                     | 114       | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 111       | 1.85%   |
| Intel Wireless 7265                                                     | 82        | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 81        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 79        | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 79        | 1.32%   |
| Intel Wireless 8265 / 8275                                              | 76        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 71        | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.02%   |
| Intel Wireless 8260                                                     | 59        | 0.99%   |
| Intel Wireless 3165                                                     | 58        | 0.97%   |
| Intel Wi-Fi 6 AX200                                                     | 58        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 54        | 0.9%    |
| Intel WiFi Link 5100                                                    | 52        | 0.87%   |
| Intel Wi-Fi 6 AX201                                                     | 52        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 51        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 47        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 43        | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 37        | 0.62%   |
| Intel Wireless 3160                                                     | 36        | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 36        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.6%    |
| Intel Ethernet Connection I217-LM                                       | 35        | 0.58%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 34        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 34        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                                | 34        | 0.57%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                | 33        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1228      | 38.11%  |
| Qualcomm Atheros                | 711       | 22.07%  |
| Realtek Semiconductor           | 542       | 16.82%  |
| Broadcom                        | 383       | 11.89%  |
| Broadcom Limited                | 112       | 3.48%   |
| Ralink                          | 63        | 1.96%   |
| MediaTek                        | 28        | 0.87%   |
| TP-Link                         | 27        | 0.84%   |
| Ralink Technology               | 27        | 0.84%   |
| Sierra Wireless                 | 16        | 0.5%    |
| Dell                            | 16        | 0.5%    |
| Qualcomm Atheros Communications | 11        | 0.34%   |
| NetGear                         | 9         | 0.28%   |
| Edimax Technology               | 8         | 0.25%   |
| ASUSTek Computer                | 8         | 0.25%   |
| D-Link System                   | 4         | 0.12%   |
| D-Link                          | 4         | 0.12%   |
| Linksys                         | 3         | 0.09%   |
| Hewlett-Packard                 | 3         | 0.09%   |
| Belkin Components               | 3         | 0.09%   |
| ZyDAS                           | 2         | 0.06%   |
| Micro Star International        | 2         | 0.06%   |
| ZyXEL Communications            | 1         | 0.03%   |
| Xiaomi                          | 1         | 0.03%   |
| TRENDnet                        | 1         | 0.03%   |
| Tenda                           | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Qualcomm                        | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Mercucys                        | 1         | 0.03%   |
| Lite-On Technology              | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| Fibocom                         | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 147       | 4.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 137       | 4.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 118       | 3.63%   |
| Intel Wireless 7260                                                     | 114       | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 111       | 3.41%   |
| Intel Wireless 7265                                                     | 82        | 2.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 81        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 79        | 2.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 79        | 2.43%   |
| Intel Wireless 8265 / 8275                                              | 76        | 2.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 71        | 2.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 67        | 2.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 64        | 1.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 61        | 1.88%   |
| Intel Wireless 8260                                                     | 59        | 1.81%   |
| Intel Wireless 3165                                                     | 58        | 1.78%   |
| Intel Wi-Fi 6 AX200                                                     | 58        | 1.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 54        | 1.66%   |
| Intel WiFi Link 5100                                                    | 52        | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 52        | 1.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 52        | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 47        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 43        | 1.32%   |
| Intel Wireless 3160                                                     | 36        | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.11%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 34        | 1.05%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 30        | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 30        | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 28        | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 26        | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 26        | 0.8%    |
| Intel Centrino Advanced-N 6235                                          | 26        | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 25        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 25        | 0.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 24        | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 24        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1329      | 50.47%  |
| Intel                                  | 503       | 19.1%   |
| Qualcomm Atheros                       | 216       | 8.2%    |
| Broadcom                               | 175       | 6.65%   |
| Marvell Technology Group               | 94        | 3.57%   |
| Broadcom Limited                       | 55        | 2.09%   |
| Nvidia                                 | 45        | 1.71%   |
| Silicon Integrated Systems [SiS]       | 27        | 1.03%   |
| ASIX Electronics                       | 27        | 1.03%   |
| JMicron Technology                     | 26        | 0.99%   |
| Samsung Electronics                    | 25        | 0.95%   |
| Xiaomi                                 | 15        | 0.57%   |
| DisplayLink                            | 12        | 0.46%   |
| VIA Technologies                       | 10        | 0.38%   |
| TP-Link                                | 9         | 0.34%   |
| OPPO Electronics                       | 9         | 0.34%   |
| Huawei Technologies                    | 9         | 0.34%   |
| MediaTek                               | 6         | 0.23%   |
| Attansic Technology                    | 6         | 0.23%   |
| Qualcomm                               | 5         | 0.19%   |
| Motorola PCS                           | 5         | 0.19%   |
| Google                                 | 4         | 0.15%   |
| Hewlett-Packard                        | 3         | 0.11%   |
| T & A Mobile Phones                    | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| Davicom Semiconductor                  | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Novatel Wireless                       | 1         | 0.04%   |
| Motorola BCS                           | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| GoPro                                  | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 787       | 29.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 427       | 16.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 125       | 4.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 51        | 1.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 1.4%    |
| Intel Ethernet Connection I218-LM                                 | 36        | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 35        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 1.29%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 1.29%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 1.25%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 1.13%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 30        | 1.13%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 26        | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 25        | 0.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 24        | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.83%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 21        | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.76%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 20        | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 17        | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 17        | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 17        | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 17        | 0.64%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 17        | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.57%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 15        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.53%   |
| Nvidia MCP67 Ethernet                                             | 14        | 0.53%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.53%   |
| Intel PRO/100 VE Network Connection                               | 13        | 0.49%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 12        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3008      | 53.3%   |
| Ethernet | 2541      | 45.03%  |
| Modem    | 89        | 1.58%   |
| Unknown  | 5         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2527      | 78.5%   |
| Ethernet | 691       | 21.47%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2339      | 75.16%  |
| 1     | 632       | 20.31%  |
| 0     | 126       | 4.05%   |
| 3     | 15        | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2441      | 77.37%  |
| Yes  | 714       | 22.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 773       | 37.43%  |
| Qualcomm Atheros Communications | 251       | 12.15%  |
| Realtek Semiconductor           | 236       | 11.43%  |
| Broadcom                        | 163       | 7.89%   |
| IMC Networks                    | 90        | 4.36%   |
| Apple                           | 81        | 3.92%   |
| Foxconn / Hon Hai               | 75        | 3.63%   |
| Lite-On Technology              | 73        | 3.54%   |
| Dell                            | 69        | 3.34%   |
| Hewlett-Packard                 | 66        | 3.2%    |
| Toshiba                         | 40        | 1.94%   |
| Cambridge Silicon Radio         | 30        | 1.45%   |
| Ralink                          | 26        | 1.26%   |
| ASUSTek Computer                | 17        | 0.82%   |
| Realtek                         | 16        | 0.77%   |
| Alps Electric                   | 15        | 0.73%   |
| Foxconn International           | 12        | 0.58%   |
| Ralink Technology               | 6         | 0.29%   |
| Askey Computer                  | 6         | 0.29%   |
| Taiyo Yuden                     | 4         | 0.19%   |
| Dynex                           | 3         | 0.15%   |
| Chicony Electronics             | 3         | 0.15%   |
| Qcom                            | 2         | 0.1%    |
| MediaTek                        | 2         | 0.1%    |
| Integrated System Solution      | 2         | 0.1%    |
| TP-Link                         | 1         | 0.05%   |
| Conwise Technology              | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 402       | 19.44%  |
| Realtek Bluetooth Radio                             | 149       | 7.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 109       | 5.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 99        | 4.79%   |
| Intel AX201 Bluetooth                               | 96        | 4.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 68        | 3.29%   |
| Intel AX200 Bluetooth                               | 56        | 2.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 46        | 2.22%   |
| Apple Bluetooth Host Controller                     | 46        | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 1.93%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 39        | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 36        | 1.74%   |
| IMC Networks Bluetooth Device                       | 33        | 1.6%    |
| Intel Bluetooth Device                              | 32        | 1.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30        | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 27        | 1.31%   |
| Ralink RT3290 Bluetooth                             | 26        | 1.26%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 1.26%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 24        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 1.11%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.06%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 1.02%   |
| Dell DW375 Bluetooth Module                         | 20        | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 0.92%   |
| Intel AX210 Bluetooth                               | 18        | 0.87%   |
| Realtek Bluetooth Radio                             | 16        | 0.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 0.73%   |
| Apple Bluetooth USB Host Controller                 | 15        | 0.73%   |
| IMC Networks Wireless_Device                        | 14        | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 14        | 0.68%   |
| Toshiba Bluetooth Device                            | 13        | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.58%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.58%   |
| Apple Bluetooth HCI                                 | 12        | 0.58%   |
| Dell Wireless 370 Bluetooth Mini-card               | 11        | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2450      | 70.1%   |
| AMD                                  | 551       | 15.77%  |
| Nvidia                               | 357       | 10.21%  |
| Silicon Integrated Systems [SiS]     | 31        | 0.89%   |
| VIA Technologies                     | 11        | 0.31%   |
| C-Media Electronics                  | 11        | 0.31%   |
| Generalplus Technology               | 8         | 0.23%   |
| Tenx Technology                      | 6         | 0.17%   |
| Realtek Semiconductor                | 5         | 0.14%   |
| Texas Instruments                    | 4         | 0.11%   |
| Plantronics                          | 4         | 0.11%   |
| Logitech                             | 4         | 0.11%   |
| Lenovo                               | 4         | 0.11%   |
| Creative Technology                  | 4         | 0.11%   |
| SteelSeries ApS                      | 3         | 0.09%   |
| PreSonus Audio Electronics           | 3         | 0.09%   |
| JMTek                                | 3         | 0.09%   |
| GN Netcom                            | 3         | 0.09%   |
| Yamaha                               | 2         | 0.06%   |
| Hewlett-Packard                      | 2         | 0.06%   |
| Focusrite-Novation                   | 2         | 0.06%   |
| DCMT Technology                      | 2         | 0.06%   |
| Corsair                              | 2         | 0.06%   |
| ZOOM                                 | 1         | 0.03%   |
| XMOS                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Syntek                               | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Sennheiser Communications            | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| Roland                               | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| OPPO Electronics                     | 1         | 0.03%   |
| M-Audio                              | 1         | 0.03%   |
| Kingston Technology                  | 1         | 0.03%   |
| FiiO Electronics Technology          | 1         | 0.03%   |
| DSEA A/S                             | 1         | 0.03%   |
| Dell                                 | 1         | 0.03%   |
| Conexant Systems                     | 1         | 0.03%   |
| CMX Systems                          | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 288       | 6.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 284       | 6.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 226       | 5.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 201       | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 176       | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 169       | 4%      |
| Intel 8 Series HD Audio Controller                                                                | 144       | 3.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 142       | 3.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 140       | 3.31%   |
| AMD FCH Azalia Controller                                                                         | 138       | 3.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 130       | 3.08%   |
| Intel Broadwell-U Audio Controller                                                                | 102       | 2.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 101       | 2.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 95        | 2.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 88        | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 80        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 78        | 1.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 78        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 77        | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 72        | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 69        | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 68        | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 61        | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 54        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 53        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 51        | 1.21%   |
| AMD High Definition Audio Controller                                                              | 49        | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 47        | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 44        | 1.04%   |
| Intel CM238 HD Audio Controller                                                                   | 42        | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 40        | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 35        | 0.83%   |
| AMD Wrestler HDMI Audio                                                                           | 32        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 30        | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 27        | 0.64%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 26        | 0.62%   |
| Nvidia High Definition Audio Controller                                                           | 24        | 0.57%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 24        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 23        | 0.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 196       | 25.39%  |
| SK hynix               | 185       | 23.96%  |
| Micron Technology      | 87        | 11.27%  |
| Unknown                | 73        | 9.46%   |
| Kingston               | 54        | 6.99%   |
| Crucial                | 23        | 2.98%   |
| Unknown (ABCD)         | 21        | 2.72%   |
| Elpida                 | 16        | 2.07%   |
| Ramaxel Technology     | 15        | 1.94%   |
| Nanya Technology       | 15        | 1.94%   |
| A-DATA Technology      | 15        | 1.94%   |
| Smart                  | 10        | 1.3%    |
| Corsair                | 5         | 0.65%   |
| Qimonda                | 4         | 0.52%   |
| Timetec                | 3         | 0.39%   |
| Team                   | 3         | 0.39%   |
| Unknown                | 3         | 0.39%   |
| Transcend              | 2         | 0.26%   |
| Teikon                 | 2         | 0.26%   |
| Smart Brazil           | 2         | 0.26%   |
| SHARETRONIC            | 2         | 0.26%   |
| Patriot                | 2         | 0.26%   |
| High Bridge            | 2         | 0.26%   |
| G.Skill                | 2         | 0.26%   |
| ff                     | 2         | 0.26%   |
| fef5                   | 2         | 0.26%   |
| 4ea5                   | 2         | 0.26%   |
| Walton Chaintech       | 1         | 0.13%   |
| Unknown (08B5)         | 1         | 0.13%   |
| Unknown (07F7)         | 1         | 0.13%   |
| Unknown (000080B30080) | 1         | 0.13%   |
| Toshiba                | 1         | 0.13%   |
| Strontium              | 1         | 0.13%   |
| Silicon Power          | 1         | 0.13%   |
| PUSKILL                | 1         | 0.13%   |
| ProMos/Mosel Vitelic   | 1         | 0.13%   |
| pqi                    | 1         | 0.13%   |
| PNY                    | 1         | 0.13%   |
| Netlist                | 1         | 0.13%   |
| Nayna                  | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 2.2%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.1%    |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 9         | 1.1%    |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 8         | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.85%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 6         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.73%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.73%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.73%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 5         | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.61%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 5         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 4         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.49%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.49%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 252       | 38.53%  |
| DDR4    | 221       | 33.79%  |
| DDR2    | 70        | 10.7%   |
| LPDDR4  | 41        | 6.27%   |
| SDRAM   | 24        | 3.67%   |
| LPDDR3  | 22        | 3.36%   |
| DRAM    | 6         | 0.92%   |
| Unknown | 6         | 0.92%   |
| DDR     | 5         | 0.76%   |
| LPDDR5  | 4         | 0.61%   |
| DDR5    | 3         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 563       | 86.88%  |
| Row Of Chips | 55        | 8.49%   |
| DIMM         | 13        | 2.01%   |
| Chip         | 9         | 1.39%   |
| Unknown      | 8         | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 234       | 31.71%  |
| 4096  | 227       | 30.76%  |
| 2048  | 151       | 20.46%  |
| 16384 | 54        | 7.32%   |
| 1024  | 51        | 6.91%   |
| 512   | 12        | 1.63%   |
| 32768 | 7         | 0.95%   |
| 256   | 2         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 169       | 23.84%  |
| 2667    | 107       | 15.09%  |
| 3200    | 85        | 11.99%  |
| 2400    | 59        | 8.32%   |
| 1334    | 40        | 5.64%   |
| 667     | 38        | 5.36%   |
| 2133    | 29        | 4.09%   |
| 1333    | 28        | 3.95%   |
| Unknown | 27        | 3.81%   |
| 1066    | 15        | 2.12%   |
| 800     | 13        | 1.83%   |
| 4267    | 11        | 1.55%   |
| 975     | 11        | 1.55%   |
| 4199    | 10        | 1.41%   |
| 2048    | 10        | 1.41%   |
| 533     | 10        | 1.41%   |
| 3266    | 9         | 1.27%   |
| 1867    | 8         | 1.13%   |
| 1067    | 7         | 0.99%   |
| 6400    | 5         | 0.71%   |
| 8400    | 4         | 0.56%   |
| 4800    | 3         | 0.42%   |
| 400     | 3         | 0.42%   |
| 3733    | 2         | 0.28%   |
| 5600    | 1         | 0.14%   |
| 4266    | 1         | 0.14%   |
| 2933    | 1         | 0.14%   |
| 1866    | 1         | 0.14%   |
| 1639    | 1         | 0.14%   |
| 666     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 38.71%  |
| Seiko Epson           | 6         | 19.35%  |
| Canon                 | 6         | 19.35%  |
| Samsung Electronics   | 2         | 6.45%   |
| Brother Industries    | 2         | 6.45%   |
| Zebra                 | 1         | 3.23%   |
| STMicroelectronics    | 1         | 3.23%   |
| Lexmark International | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series                                 | 2         | 6.45%   |
| HP DeskJet 1110 series                                    | 2         | 6.45%   |
| Zebra ZP 450 Printer                                      | 1         | 3.23%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.23%   |
| Seiko Epson XP-235 Series                                 | 1         | 3.23%   |
| Seiko Epson WF-2010 Series                                | 1         | 3.23%   |
| Seiko Epson Printer                                       | 1         | 3.23%   |
| Seiko Epson L3110 Series                                  | 1         | 3.23%   |
| Seiko Epson ET-2810 Series                                | 1         | 3.23%   |
| Seiko Epson AcuLaser C1700                                | 1         | 3.23%   |
| Samsung M2020 Series                                      | 1         | 3.23%   |
| Samsung CLX-3300 Series                                   | 1         | 3.23%   |
| Lexmark International 2400 series                         | 1         | 3.23%   |
| HP Laserjet P1505                                         | 1         | 3.23%   |
| HP LaserJet P1102                                         | 1         | 3.23%   |
| HP LaserJet 1200                                          | 1         | 3.23%   |
| HP LaserJet 1020                                          | 1         | 3.23%   |
| HP LaserJet 1000                                          | 1         | 3.23%   |
| HP DeskJet 2700 series                                    | 1         | 3.23%   |
| HP DeskJet 2300 series                                    | 1         | 3.23%   |
| HP Deskjet 1510                                           | 1         | 3.23%   |
| Canon TS3100 series                                       | 1         | 3.23%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.23%   |
| Canon PIXMA MX340                                         | 1         | 3.23%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.23%   |
| Canon PIXMA MG3000 series                                 | 1         | 3.23%   |
| Canon MG2100 series                                       | 1         | 3.23%   |
| Brother MFC-L2730DW series                                | 1         | 3.23%   |
| Brother DCP-T300                                          | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 40%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 200                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 637       | 25.25%  |
| Microdia                               | 237       | 9.39%   |
| Realtek Semiconductor                  | 206       | 8.16%   |
| IMC Networks                           | 198       | 7.85%   |
| Bison Electronics                      | 142       | 5.63%   |
| Sunplus Innovation Technology          | 141       | 5.59%   |
| Suyin                                  | 129       | 5.11%   |
| Cheng Uei Precision Industry (Foxlink) | 115       | 4.56%   |
| Quanta                                 | 106       | 4.2%    |
| Apple                                  | 71        | 2.81%   |
| Syntek                                 | 66        | 2.62%   |
| Silicon Motion                         | 56        | 2.22%   |
| Alcor Micro                            | 48        | 1.9%    |
| Lite-On Technology                     | 46        | 1.82%   |
| Acer                                   | 41        | 1.63%   |
| Ricoh                                  | 33        | 1.31%   |
| Luxvisions Innotech Limited            | 23        | 0.91%   |
| Logitech                               | 20        | 0.79%   |
| ALi                                    | 19        | 0.75%   |
| Importek                               | 17        | 0.67%   |
| Samsung Electronics                    | 16        | 0.63%   |
| Primax Electronics                     | 15        | 0.59%   |
| icSpring                               | 14        | 0.55%   |
| Z-Star Microelectronics                | 13        | 0.52%   |
| Sonix Technology                       | 12        | 0.48%   |
| Lenovo                                 | 11        | 0.44%   |
| OmniVision Technologies                | 10        | 0.4%    |
| GEMBIRD                                | 9         | 0.36%   |
| SunplusIT                              | 7         | 0.28%   |
| Genesys Logic                          | 6         | 0.24%   |
| Y Media                                | 5         | 0.2%    |
| Sunplus Technology                     | 4         | 0.16%   |
| Microsoft                              | 4         | 0.16%   |
| Intel                                  | 4         | 0.16%   |
| Generalplus Technology                 | 3         | 0.12%   |
| ARC International                      | 3         | 0.12%   |
| YGTek                                  | 2         | 0.08%   |
| Tripath Technology                     | 2         | 0.08%   |
| LG Electronics                         | 2         | 0.08%   |
| KYE Systems (Mouse Systems)            | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 86        | 3.4%    |
| Microdia Integrated_Webcam_HD                    | 49        | 1.94%   |
| IMC Networks USB2.0 HD UVC WebCam                | 46        | 1.82%   |
| Chicony HD Webcam                                | 41        | 1.62%   |
| Realtek Integrated_Webcam_HD                     | 39        | 1.54%   |
| Microdia Integrated Webcam                       | 36        | 1.42%   |
| Chicony HP Truevision HD                         | 36        | 1.42%   |
| Syntek Integrated Camera                         | 32        | 1.26%   |
| Chicony TOSHIBA Web Camera - HD                  | 31        | 1.23%   |
| Bison Lenovo EasyCamera                          | 31        | 1.23%   |
| IMC Networks Integrated Camera                   | 30        | 1.19%   |
| Bison Integrated Camera                          | 29        | 1.15%   |
| Sunplus Integrated_Webcam_HD                     | 28        | 1.11%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 27        | 1.07%   |
| Chicony USB 2.0 Camera                           | 25        | 0.99%   |
| Chicony HP TrueVision HD Camera                  | 25        | 0.99%   |
| Sunplus HD WebCam                                | 24        | 0.95%   |
| Realtek Integrated Webcam                        | 22        | 0.87%   |
| Chicony EasyCamera                               | 22        | 0.87%   |
| Chicony Lenovo EasyCamera                        | 21        | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 21        | 0.83%   |
| Chicony VGA Webcam                               | 20        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 20        | 0.79%   |
| Alcor Micro USB 2.0 Camera                       | 20        | 0.79%   |
| Chicony USB2.0 VGA UVC WebCam                    | 19        | 0.75%   |
| Apple FaceTime HD Camera                         | 19        | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 18        | 0.71%   |
| Realtek USB Camera                               | 18        | 0.71%   |
| Chicony HP HD Webcam                             | 18        | 0.71%   |
| Suyin HP Truevision HD                           | 17        | 0.67%   |
| Quanta HP Webcam                                 | 17        | 0.67%   |
| Lite-On HP HD Camera                             | 17        | 0.67%   |
| Chicony HP Webcam                                | 17        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)          | 16        | 0.63%   |
| Quanta HP TrueVision HD Camera                   | 16        | 0.63%   |
| Chicony CNF9055 Toshiba Webcam                   | 16        | 0.63%   |
| Apple Built-in iSight                            | 16        | 0.63%   |
| ALi Gateway Webcam                               | 16        | 0.63%   |
| Realtek HP Truevision HD                         | 15        | 0.59%   |
| Microdia Sonix USB 2.0 Camera                    | 15        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 202       | 46.76%  |
| AuthenTec                          | 63        | 14.58%  |
| Shenzhen Goodix Technology         | 43        | 9.95%   |
| Synaptics                          | 36        | 8.33%   |
| Upek                               | 35        | 8.1%    |
| Elan Microelectronics              | 21        | 4.86%   |
| STMicroelectronics                 | 19        | 4.4%    |
| LighTuning Technology              | 8         | 1.85%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.69%   |
| Samsung Electronics                | 1         | 0.23%   |
| Focal-systems.Corp                 | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 9.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 7.64%   |
| Shenzhen Goodix  Fingerprint Device                                        | 31        | 7.18%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 5.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 4.86%   |
| Validity Sensors VFS491                                                    | 20        | 4.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 4.4%    |
| STMicroelectronics Fingerprint Reader                                      | 19        | 4.4%    |
| Validity Sensors Fingerprint scanner                                       | 18        | 4.17%   |
| AuthenTec AES2810                                                          | 18        | 4.17%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.78%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 2.31%   |
| AuthenTec AES1600                                                          | 10        | 2.31%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.08%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 1.85%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.62%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.39%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 1.16%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.16%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 1.16%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.93%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.69%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.69%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.69%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.46%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.46%   |
| Synaptics WBDI                                                             | 2         | 0.46%   |
| Synaptics  WBDI                                                            | 2         | 0.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.46%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 104       | 54.45%  |
| Alcor Micro                       | 33        | 17.28%  |
| O2 Micro                          | 27        | 14.14%  |
| Lenovo                            | 9         | 4.71%   |
| Upek                              | 8         | 4.19%   |
| Yubico.com                        | 2         | 1.05%   |
| VASCO Data Security International | 2         | 1.05%   |
| SCM Microsystems                  | 2         | 1.05%   |
| Realtek Semiconductor             | 2         | 1.05%   |
| OmniKey                           | 1         | 0.52%   |
| Fujitsu Siemens Computers         | 1         | 0.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 24.48%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 32        | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 13.54%  |
| Broadcom 5880                                                                | 26        | 13.54%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 11.46%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 4.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.6%    |
| Broadcom 58200                                                               | 4         | 2.08%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.04%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1.04%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.04%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.04%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.04%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.52%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.52%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2011      | 63.68%  |
| 1     | 897       | 28.4%   |
| 2     | 218       | 6.9%    |
| 3     | 28        | 0.89%   |
| 4     | 3         | 0.09%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 425       | 30.77%  |
| Graphics card            | 298       | 21.58%  |
| Chipcard                 | 182       | 13.18%  |
| Net/wireless             | 168       | 12.17%  |
| Multimedia controller    | 107       | 7.75%   |
| Storage                  | 45        | 3.26%   |
| Modem                    | 38        | 2.75%   |
| Bluetooth                | 34        | 2.46%   |
| Sound                    | 16        | 1.16%   |
| Communication controller | 15        | 1.09%   |
| Camera                   | 14        | 1.01%   |
| Flash memory             | 13        | 0.94%   |
| Net/ethernet             | 8         | 0.58%   |
| Card reader              | 6         | 0.43%   |
| Network                  | 4         | 0.29%   |
| Storage/nvme             | 2         | 0.14%   |
| Storage/ide              | 2         | 0.14%   |
| Dvb card                 | 2         | 0.14%   |
| Unclassified device      | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |


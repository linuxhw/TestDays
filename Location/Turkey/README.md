Linux in Turkey - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Turkey.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Turkey/Desktop/README.md) and [notebooks](/Location/Turkey/Notebook/README.md).

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

Total: 2400

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c68576fce8](https://linux-hardware.org/?probe=c68576fce8) | Apr 30, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1c67ba3f8a](https://linux-hardware.org/?probe=1c67ba3f8a) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Monster       | TULPAR T5 V21.7             | Notebook    | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [8c4ba894b4](https://linux-hardware.org/?probe=8c4ba894b4) | Apr 28, 2023 |
| Supermicro    | X12SPL-F                    | Server      | [8382988ca9](https://linux-hardware.org/?probe=8382988ca9) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | Notebook    | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | Desktop     | [8cbd1dce35](https://linux-hardware.org/?probe=8cbd1dce35) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | Desktop     | [ef0df72346](https://linux-hardware.org/?probe=ef0df72346) | Apr 26, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [f9671dc0a4](https://linux-hardware.org/?probe=f9671dc0a4) | Apr 26, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [2b0ee4d542](https://linux-hardware.org/?probe=2b0ee4d542) | Apr 26, 2023 |
| HP            | 240 G8                      | Notebook    | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | Notebook    | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| HP            | ProBook 4540s               | Notebook    | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [bb1a40d839](https://linux-hardware.org/?probe=bb1a40d839) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8b18bb529f](https://linux-hardware.org/?probe=8b18bb529f) | Apr 21, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [6d24ab2a04](https://linux-hardware.org/?probe=6d24ab2a04) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [43fc15779a](https://linux-hardware.org/?probe=43fc15779a) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| Lenovo        | Unknown                     | Notebook    | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| Biostar       | G31D-M7                     | Desktop     | [bb518a8623](https://linux-hardware.org/?probe=bb518a8623) | Apr 14, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [6e07b5d9d1](https://linux-hardware.org/?probe=6e07b5d9d1) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [a23067158f](https://linux-hardware.org/?probe=a23067158f) | Apr 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [62dd8e069f](https://linux-hardware.org/?probe=62dd8e069f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [cc0b87e611](https://linux-hardware.org/?probe=cc0b87e611) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| Sony          | VPCEB3J1E                   | Notebook    | [1405405cbb](https://linux-hardware.org/?probe=1405405cbb) | Apr 11, 2023 |
| HP            | 18E6                        | Desktop     | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2a108e9eed](https://linux-hardware.org/?probe=2a108e9eed) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [396850fd22](https://linux-hardware.org/?probe=396850fd22) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [5d0731fb7a](https://linux-hardware.org/?probe=5d0731fb7a) | Apr 05, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| Acer          | Aspire 5220                 | Notebook    | [d22076fd54](https://linux-hardware.org/?probe=d22076fd54) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b55be43d4c](https://linux-hardware.org/?probe=b55be43d4c) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [78bda6a16c](https://linux-hardware.org/?probe=78bda6a16c) | Apr 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [38dc8922e4](https://linux-hardware.org/?probe=38dc8922e4) | Apr 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [804bf25c27](https://linux-hardware.org/?probe=804bf25c27) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [d527726a1c](https://linux-hardware.org/?probe=d527726a1c) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [282031e979](https://linux-hardware.org/?probe=282031e979) | Mar 30, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [920f4a2dc2](https://linux-hardware.org/?probe=920f4a2dc2) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [31a96824ea](https://linux-hardware.org/?probe=31a96824ea) | Mar 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| Pegatron      | IPMIP-H55-GEN               | Desktop     | [7dcf9e9b51](https://linux-hardware.org/?probe=7dcf9e9b51) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| ASUSTek       | E502NA                      | Notebook    | [a116400859](https://linux-hardware.org/?probe=a116400859) | Mar 27, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [d7b97732fa](https://linux-hardware.org/?probe=d7b97732fa) | Mar 26, 2023 |
| Monster       | TULPAR T7 V19.5             | Notebook    | [4a4933c183](https://linux-hardware.org/?probe=4a4933c183) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| Dell          | Vostro 5581                 | Notebook    | [d2ebb46bea](https://linux-hardware.org/?probe=d2ebb46bea) | Mar 25, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| HP            | Pavilion dv6                | Notebook    | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [de7c54aec1](https://linux-hardware.org/?probe=de7c54aec1) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [fdea1b7da5](https://linux-hardware.org/?probe=fdea1b7da5) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [0634ed91ba](https://linux-hardware.org/?probe=0634ed91ba) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [ad5218c0bf](https://linux-hardware.org/?probe=ad5218c0bf) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [32ba732ef0](https://linux-hardware.org/?probe=32ba732ef0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| Lenovo        | Flex 2-15                   | Notebook    | [6bea7b508e](https://linux-hardware.org/?probe=6bea7b508e) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [66f69d578c](https://linux-hardware.org/?probe=66f69d578c) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Toshiba       | Satellite C55-A-1K4         | Notebook    | [3ba10eda08](https://linux-hardware.org/?probe=3ba10eda08) | Mar 11, 2023 |
| MSI           | Alpha 15 A3DC               | Notebook    | [feabd7f5bf](https://linux-hardware.org/?probe=feabd7f5bf) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [44db3bc5ec](https://linux-hardware.org/?probe=44db3bc5ec) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [96e374345a](https://linux-hardware.org/?probe=96e374345a) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b5f8598cfd](https://linux-hardware.org/?probe=b5f8598cfd) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [e55325be18](https://linux-hardware.org/?probe=e55325be18) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [39805e4790](https://linux-hardware.org/?probe=39805e4790) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [d12e99f5d2](https://linux-hardware.org/?probe=d12e99f5d2) | Mar 09, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| Sony          | SVD11225CXB                 | Notebook    | [b5b755e185](https://linux-hardware.org/?probe=b5b755e185) | Mar 07, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [8961f32cc5](https://linux-hardware.org/?probe=8961f32cc5) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [d1a37d82cb](https://linux-hardware.org/?probe=d1a37d82cb) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [80ee932665](https://linux-hardware.org/?probe=80ee932665) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [c112aacdb6](https://linux-hardware.org/?probe=c112aacdb6) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [ccd91fb0c7](https://linux-hardware.org/?probe=ccd91fb0c7) | Mar 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1ccfddfbc0](https://linux-hardware.org/?probe=1ccfddfbc0) | Mar 04, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | Notebook    | [4cb64cfa8f](https://linux-hardware.org/?probe=4cb64cfa8f) | Mar 03, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [e230d5c136](https://linux-hardware.org/?probe=e230d5c136) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | Notebook    | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e0864b4a50](https://linux-hardware.org/?probe=e0864b4a50) | Mar 02, 2023 |
| HP            | 15                          | Notebook    | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [0242801bbc](https://linux-hardware.org/?probe=0242801bbc) | Mar 01, 2023 |
| Unknown       | Unknown                     | Phone       | [a9c7699598](https://linux-hardware.org/?probe=a9c7699598) | Feb 28, 2023 |
| ASUSTek       | X55A                        | Notebook    | [1429627725](https://linux-hardware.org/?probe=1429627725) | Feb 28, 2023 |
| Alienware     | 15 R2                       | Notebook    | [5e29609544](https://linux-hardware.org/?probe=5e29609544) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | Notebook    | [68a816d082](https://linux-hardware.org/?probe=68a816d082) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | Notebook    | [bbb8c4e905](https://linux-hardware.org/?probe=bbb8c4e905) | Feb 28, 2023 |
| Casper        | H510 001 G10a               | Desktop     | [95a9cfbf0b](https://linux-hardware.org/?probe=95a9cfbf0b) | Feb 27, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [72034abe27](https://linux-hardware.org/?probe=72034abe27) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7ff7ca240](https://linux-hardware.org/?probe=c7ff7ca240) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [246492391c](https://linux-hardware.org/?probe=246492391c) | Feb 23, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [29673d3e8f](https://linux-hardware.org/?probe=29673d3e8f) | Feb 22, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [be36fee6eb](https://linux-hardware.org/?probe=be36fee6eb) | Feb 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [40468a72ce](https://linux-hardware.org/?probe=40468a72ce) | Feb 20, 2023 |
| ASUSTek       | V161GAR                     | All in one  | [e8277425a5](https://linux-hardware.org/?probe=e8277425a5) | Feb 20, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [c124cec382](https://linux-hardware.org/?probe=c124cec382) | Feb 19, 2023 |
| Sony          | VPCCB16FG                   | Notebook    | [0a6224bcc3](https://linux-hardware.org/?probe=0a6224bcc3) | Feb 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [3543a34ca0](https://linux-hardware.org/?probe=3543a34ca0) | Feb 19, 2023 |
| HP            | Notebook                    | Notebook    | [2d03543f4c](https://linux-hardware.org/?probe=2d03543f4c) | Feb 18, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [75db698bfd](https://linux-hardware.org/?probe=75db698bfd) | Feb 18, 2023 |
| Casper        | H510 001 G10a               | Desktop     | [56402bade6](https://linux-hardware.org/?probe=56402bade6) | Feb 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [02d91d3f00](https://linux-hardware.org/?probe=02d91d3f00) | Feb 17, 2023 |
| Lenovo        | ThinkPad X220 4291ZD8       | Notebook    | [9dbad47bf0](https://linux-hardware.org/?probe=9dbad47bf0) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | Notebook    | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [514bbe20b5](https://linux-hardware.org/?probe=514bbe20b5) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ef50e45214](https://linux-hardware.org/?probe=ef50e45214) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Pegatron      | H36ST                       | Notebook    | [2b0e74ca00](https://linux-hardware.org/?probe=2b0e74ca00) | Feb 13, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a384bb740c](https://linux-hardware.org/?probe=a384bb740c) | Feb 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [18cd6aad2c](https://linux-hardware.org/?probe=18cd6aad2c) | Feb 11, 2023 |
| HP            | 15                          | Notebook    | [162c6f9186](https://linux-hardware.org/?probe=162c6f9186) | Feb 11, 2023 |
| Lenovo        | ThinkPad X280 20KES2WC06    | Notebook    | [794dcaf42d](https://linux-hardware.org/?probe=794dcaf42d) | Feb 11, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [ea2304bdfe](https://linux-hardware.org/?probe=ea2304bdfe) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a410a7b784](https://linux-hardware.org/?probe=a410a7b784) | Feb 09, 2023 |
| Timi          | TM1701                      | Notebook    | [b3015735e6](https://linux-hardware.org/?probe=b3015735e6) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| Sony          | VPCEH1M1E                   | Notebook    | [43f51d50c1](https://linux-hardware.org/?probe=43f51d50c1) | Feb 09, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1d05e35623](https://linux-hardware.org/?probe=1d05e35623) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [ffce390164](https://linux-hardware.org/?probe=ffce390164) | Feb 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [7fd90f29c1](https://linux-hardware.org/?probe=7fd90f29c1) | Feb 08, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e1fc422565](https://linux-hardware.org/?probe=e1fc422565) | Feb 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [234f1c81c2](https://linux-hardware.org/?probe=234f1c81c2) | Feb 07, 2023 |
| Packard Be... | SJV50MV                     | Notebook    | [930ac749ca](https://linux-hardware.org/?probe=930ac749ca) | Feb 07, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [f632cba0a7](https://linux-hardware.org/?probe=f632cba0a7) | Feb 07, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [295fd70d70](https://linux-hardware.org/?probe=295fd70d70) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [5b16a4a572](https://linux-hardware.org/?probe=5b16a4a572) | Feb 05, 2023 |
| Packard Be... | SJV50MV                     | Notebook    | [ff862a12ae](https://linux-hardware.org/?probe=ff862a12ae) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.3             | Notebook    | [82f58f57c0](https://linux-hardware.org/?probe=82f58f57c0) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.1             | Notebook    | [b224ac6a46](https://linux-hardware.org/?probe=b224ac6a46) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [d839e9036f](https://linux-hardware.org/?probe=d839e9036f) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [ed1785494a](https://linux-hardware.org/?probe=ed1785494a) | Feb 02, 2023 |
| HP            | Notebook                    | Notebook    | [82068da14b](https://linux-hardware.org/?probe=82068da14b) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [2d4aa2e1a0](https://linux-hardware.org/?probe=2d4aa2e1a0) | Feb 01, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [52ffe609b8](https://linux-hardware.org/?probe=52ffe609b8) | Jan 31, 2023 |
| Dell          | Latitude E6530              | Notebook    | [140543c98c](https://linux-hardware.org/?probe=140543c98c) | Jan 31, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [3be362b4aa](https://linux-hardware.org/?probe=3be362b4aa) | Jan 31, 2023 |
| Sony          | VPCCB16FG                   | Notebook    | [837588c9eb](https://linux-hardware.org/?probe=837588c9eb) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Sony          | VPCCB16FG                   | Notebook    | [7307480466](https://linux-hardware.org/?probe=7307480466) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [d4a5012f93](https://linux-hardware.org/?probe=d4a5012f93) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [e789456756](https://linux-hardware.org/?probe=e789456756) | Jan 28, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [cba2528a29](https://linux-hardware.org/?probe=cba2528a29) | Jan 28, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [0cda1a95a2](https://linux-hardware.org/?probe=0cda1a95a2) | Jan 28, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| HP            | ProBook 6460b               | Notebook    | [81a1748477](https://linux-hardware.org/?probe=81a1748477) | Jan 25, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [c66369d864](https://linux-hardware.org/?probe=c66369d864) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [a7219ed5ef](https://linux-hardware.org/?probe=a7219ed5ef) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b37f2fcaba](https://linux-hardware.org/?probe=b37f2fcaba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [0e29c1dd04](https://linux-hardware.org/?probe=0e29c1dd04) | Jan 22, 2023 |
| MSI           | H510M PRO                   | Desktop     | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [395d565464](https://linux-hardware.org/?probe=395d565464) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [fcce46f618](https://linux-hardware.org/?probe=fcce46f618) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [f79928ed4d](https://linux-hardware.org/?probe=f79928ed4d) | Jan 21, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [54cf7414fd](https://linux-hardware.org/?probe=54cf7414fd) | Jan 20, 2023 |
| Lenovo        | 3132 NOK                    | Desktop     | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d828f8f4a8](https://linux-hardware.org/?probe=d828f8f4a8) | Jan 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [282b1007ac](https://linux-hardware.org/?probe=282b1007ac) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8c8cf26214](https://linux-hardware.org/?probe=8c8cf26214) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | ThinkPad SL500 2746A18      | Notebook    | [5535380e6c](https://linux-hardware.org/?probe=5535380e6c) | Jan 16, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [b5b29198b0](https://linux-hardware.org/?probe=b5b29198b0) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [0a323f0cb8](https://linux-hardware.org/?probe=0a323f0cb8) | Jan 15, 2023 |
| Monster       | TULPAR T5 V19.2             | Notebook    | [46bd0385fa](https://linux-hardware.org/?probe=46bd0385fa) | Jan 15, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [6ff8ef1eb3](https://linux-hardware.org/?probe=6ff8ef1eb3) | Jan 15, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [4332a351bf](https://linux-hardware.org/?probe=4332a351bf) | Jan 13, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [fc41631096](https://linux-hardware.org/?probe=fc41631096) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [14d0dddfc9](https://linux-hardware.org/?probe=14d0dddfc9) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [eb61471644](https://linux-hardware.org/?probe=eb61471644) | Jan 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2a71b87b09](https://linux-hardware.org/?probe=2a71b87b09) | Jan 11, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [46dfb4ddef](https://linux-hardware.org/?probe=46dfb4ddef) | Jan 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [93ffaa0920](https://linux-hardware.org/?probe=93ffaa0920) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [010a4fc9bd](https://linux-hardware.org/?probe=010a4fc9bd) | Jan 10, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [401e0c3743](https://linux-hardware.org/?probe=401e0c3743) | Jan 10, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [179af39858](https://linux-hardware.org/?probe=179af39858) | Jan 08, 2023 |
| ODM           | MS-16K2                     | Notebook    | [f9a7d267e5](https://linux-hardware.org/?probe=f9a7d267e5) | Jan 08, 2023 |
| MSI           | GF63 8RC                    | Notebook    | [9222c5a0a6](https://linux-hardware.org/?probe=9222c5a0a6) | Jan 08, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [fba9812651](https://linux-hardware.org/?probe=fba9812651) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ef45fa4056](https://linux-hardware.org/?probe=ef45fa4056) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [36c97306ae](https://linux-hardware.org/?probe=36c97306ae) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [0ee14d767d](https://linux-hardware.org/?probe=0ee14d767d) | Jan 06, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [c7d37a7616](https://linux-hardware.org/?probe=c7d37a7616) | Jan 04, 2023 |
| Monster       | Huma H5 V3.2                | Notebook    | [cab22e2b7b](https://linux-hardware.org/?probe=cab22e2b7b) | Jan 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [113d6b92d1](https://linux-hardware.org/?probe=113d6b92d1) | Jan 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [7783f397ec](https://linux-hardware.org/?probe=7783f397ec) | Jan 03, 2023 |
| MSI           | 880GMA-E45                  | Desktop     | [f55d2f2c90](https://linux-hardware.org/?probe=f55d2f2c90) | Jan 03, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [b1d353931a](https://linux-hardware.org/?probe=b1d353931a) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [20e752831c](https://linux-hardware.org/?probe=20e752831c) | Jan 01, 2023 |
| Dell          | G3 3500                     | Notebook    | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [021903d3d7](https://linux-hardware.org/?probe=021903d3d7) | Dec 25, 2022 |
| Dell          | Latitude 5521               | Notebook    | [32d3e87886](https://linux-hardware.org/?probe=32d3e87886) | Dec 25, 2022 |
| Hometech      | Alfa 420C                   | Notebook    | [9dcf2c28b3](https://linux-hardware.org/?probe=9dcf2c28b3) | Dec 23, 2022 |
| Hometech      | Alfa 420C                   | Notebook    | [5a4f33dd7b](https://linux-hardware.org/?probe=5a4f33dd7b) | Dec 22, 2022 |
| Monster       | ABRA A5 V18.1               | Notebook    | [d151d1eb82](https://linux-hardware.org/?probe=d151d1eb82) | Dec 21, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [12bb45433d](https://linux-hardware.org/?probe=12bb45433d) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4906017260](https://linux-hardware.org/?probe=4906017260) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [085b8c23b4](https://linux-hardware.org/?probe=085b8c23b4) | Dec 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [87d3186549](https://linux-hardware.org/?probe=87d3186549) | Dec 20, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [d79e681980](https://linux-hardware.org/?probe=d79e681980) | Dec 19, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [72bfd0a0f6](https://linux-hardware.org/?probe=72bfd0a0f6) | Dec 19, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [7d5ca26325](https://linux-hardware.org/?probe=7d5ca26325) | Dec 19, 2022 |
| Dell          | Latitude 5521               | Notebook    | [3d3be9c8e9](https://linux-hardware.org/?probe=3d3be9c8e9) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| Pegatron      | H36FF                       | Notebook    | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [2a39f517ef](https://linux-hardware.org/?probe=2a39f517ef) | Dec 18, 2022 |
| Pegatron      | H36FF                       | Notebook    | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [58eac3b208](https://linux-hardware.org/?probe=58eac3b208) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [8641a184ad](https://linux-hardware.org/?probe=8641a184ad) | Dec 17, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Lenovo        | Flex 2-15                   | Notebook    | [38670ac27c](https://linux-hardware.org/?probe=38670ac27c) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Pegatron      | IPXSB-H61                   | Desktop     | [84c0b45a3b](https://linux-hardware.org/?probe=84c0b45a3b) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [e4f2e85204](https://linux-hardware.org/?probe=e4f2e85204) | Dec 14, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6dec5de4a9](https://linux-hardware.org/?probe=6dec5de4a9) | Dec 13, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b822420d6d](https://linux-hardware.org/?probe=b822420d6d) | Dec 09, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [9ba738605c](https://linux-hardware.org/?probe=9ba738605c) | Dec 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [bb540dbfb1](https://linux-hardware.org/?probe=bb540dbfb1) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2a7f909902](https://linux-hardware.org/?probe=2a7f909902) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [92f4bd5ee1](https://linux-hardware.org/?probe=92f4bd5ee1) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f8e78fbf31](https://linux-hardware.org/?probe=f8e78fbf31) | Dec 06, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [ab7d61cced](https://linux-hardware.org/?probe=ab7d61cced) | Dec 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cf810b2e09](https://linux-hardware.org/?probe=cf810b2e09) | Dec 04, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [50bcdd33eb](https://linux-hardware.org/?probe=50bcdd33eb) | Dec 04, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [02f4319195](https://linux-hardware.org/?probe=02f4319195) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [77ad02b5bd](https://linux-hardware.org/?probe=77ad02b5bd) | Nov 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [291b53ea79](https://linux-hardware.org/?probe=291b53ea79) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [ceda4dbb46](https://linux-hardware.org/?probe=ceda4dbb46) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | Notebook    | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [a116300d12](https://linux-hardware.org/?probe=a116300d12) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [a30ad69ac2](https://linux-hardware.org/?probe=a30ad69ac2) | Nov 27, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [408158ed97](https://linux-hardware.org/?probe=408158ed97) | Nov 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [dce27f6d43](https://linux-hardware.org/?probe=dce27f6d43) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [ef46869de3](https://linux-hardware.org/?probe=ef46869de3) | Nov 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4246d4813a](https://linux-hardware.org/?probe=4246d4813a) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [76f6ba932f](https://linux-hardware.org/?probe=76f6ba932f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [6d87497f34](https://linux-hardware.org/?probe=6d87497f34) | Nov 23, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [f02593fc75](https://linux-hardware.org/?probe=f02593fc75) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [5f040880ce](https://linux-hardware.org/?probe=5f040880ce) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Acer          | TravelMate 5360             | Notebook    | [c2dfb8625b](https://linux-hardware.org/?probe=c2dfb8625b) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [af679e6195](https://linux-hardware.org/?probe=af679e6195) | Nov 17, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d3d2afd2c3](https://linux-hardware.org/?probe=d3d2afd2c3) | Nov 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [450e658685](https://linux-hardware.org/?probe=450e658685) | Nov 16, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [15087fec90](https://linux-hardware.org/?probe=15087fec90) | Nov 16, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [9a588b78c3](https://linux-hardware.org/?probe=9a588b78c3) | Nov 16, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [930beb6857](https://linux-hardware.org/?probe=930beb6857) | Nov 16, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [70071adfb0](https://linux-hardware.org/?probe=70071adfb0) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [ca24381492](https://linux-hardware.org/?probe=ca24381492) | Nov 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [1cb724a4d5](https://linux-hardware.org/?probe=1cb724a4d5) | Nov 15, 2022 |
| MSI           | Z97I GAMING AC              | Desktop     | [b0a5c0251f](https://linux-hardware.org/?probe=b0a5c0251f) | Nov 15, 2022 |
| Pegatron      | IPXSB-H61                   | Desktop     | [9de70711ef](https://linux-hardware.org/?probe=9de70711ef) | Nov 15, 2022 |
| HP            | 530                         | Notebook    | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [700e2ffc46](https://linux-hardware.org/?probe=700e2ffc46) | Nov 15, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b966d9e8c9](https://linux-hardware.org/?probe=b966d9e8c9) | Nov 13, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| Monster       | ABRA A5 V15.6               | Notebook    | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [741209999d](https://linux-hardware.org/?probe=741209999d) | Nov 10, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [02944a1b38](https://linux-hardware.org/?probe=02944a1b38) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5a5633f611](https://linux-hardware.org/?probe=5a5633f611) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| Monster       | TULPAR T7 V21.7             | Notebook    | [1106dc2d92](https://linux-hardware.org/?probe=1106dc2d92) | Nov 07, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [dc90947100](https://linux-hardware.org/?probe=dc90947100) | Nov 07, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [32bb86a1e6](https://linux-hardware.org/?probe=32bb86a1e6) | Nov 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [c91e77c03a](https://linux-hardware.org/?probe=c91e77c03a) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [8c532d2ad0](https://linux-hardware.org/?probe=8c532d2ad0) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [faf3c3a1ae](https://linux-hardware.org/?probe=faf3c3a1ae) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | Notebook    | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | Notebook    | [80dbecb998](https://linux-hardware.org/?probe=80dbecb998) | Nov 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | Pavilion 15                 | Notebook    | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [c2d1799732](https://linux-hardware.org/?probe=c2d1799732) | Oct 29, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [2ca56cb740](https://linux-hardware.org/?probe=2ca56cb740) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [b086433e61](https://linux-hardware.org/?probe=b086433e61) | Oct 26, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0X000      | Tablet      | [f17ef87aca](https://linux-hardware.org/?probe=f17ef87aca) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [06a31b0132](https://linux-hardware.org/?probe=06a31b0132) | Oct 24, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [5d01101cee](https://linux-hardware.org/?probe=5d01101cee) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| Monster       | ABRA A5 V15.2               | Notebook    | [cb1a5559dc](https://linux-hardware.org/?probe=cb1a5559dc) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [9dffa26de0](https://linux-hardware.org/?probe=9dffa26de0) | Oct 20, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| Monster       | TULPAR T5 V21.6             | Notebook    | [eaeb6f6610](https://linux-hardware.org/?probe=eaeb6f6610) | Oct 17, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [210d7fdd5d](https://linux-hardware.org/?probe=210d7fdd5d) | Oct 17, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [f7e44be1b5](https://linux-hardware.org/?probe=f7e44be1b5) | Oct 17, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [cf556bb7f7](https://linux-hardware.org/?probe=cf556bb7f7) | Oct 16, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a8a52af0f4](https://linux-hardware.org/?probe=a8a52af0f4) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| Pegatron      | 2A84h                       | Desktop     | [5b46511238](https://linux-hardware.org/?probe=5b46511238) | Oct 15, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [adbd1fa089](https://linux-hardware.org/?probe=adbd1fa089) | Oct 14, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [b8ba7e41c8](https://linux-hardware.org/?probe=b8ba7e41c8) | Oct 14, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [c0fefb30fe](https://linux-hardware.org/?probe=c0fefb30fe) | Oct 12, 2022 |
| Intel         | DH87RL AAG74240-400         | Desktop     | [82d2063927](https://linux-hardware.org/?probe=82d2063927) | Oct 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bf2c25a350](https://linux-hardware.org/?probe=bf2c25a350) | Oct 12, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| ASUSTek       | Vivobook Slate T3300KA_T... | Tablet      | [cf1735bf9e](https://linux-hardware.org/?probe=cf1735bf9e) | Oct 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [09225a1f01](https://linux-hardware.org/?probe=09225a1f01) | Oct 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [a2979dfe6d](https://linux-hardware.org/?probe=a2979dfe6d) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e9928bbd81](https://linux-hardware.org/?probe=e9928bbd81) | Oct 10, 2022 |
| HP            | 81C5 MVB                    | Desktop     | [1f08f2d239](https://linux-hardware.org/?probe=1f08f2d239) | Oct 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [582de9d5d6](https://linux-hardware.org/?probe=582de9d5d6) | Oct 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f1b7cbae01](https://linux-hardware.org/?probe=f1b7cbae01) | Oct 09, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [92998a2fa1](https://linux-hardware.org/?probe=92998a2fa1) | Oct 07, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [3f310e92ed](https://linux-hardware.org/?probe=3f310e92ed) | Oct 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [87936d87c6](https://linux-hardware.org/?probe=87936d87c6) | Oct 06, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2109e3f7b1](https://linux-hardware.org/?probe=2109e3f7b1) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | Notebook    | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [5794de3528](https://linux-hardware.org/?probe=5794de3528) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | Desktop     | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [ed89b0d272](https://linux-hardware.org/?probe=ed89b0d272) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| MSI           | H110M GAMING                | Desktop     | [379aaceaab](https://linux-hardware.org/?probe=379aaceaab) | Oct 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [bd8ce563ff](https://linux-hardware.org/?probe=bd8ce563ff) | Oct 03, 2022 |
| MSI           | A75A-G35                    | Desktop     | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Casper        | C15B                        | Desktop     | [be4c7469a6](https://linux-hardware.org/?probe=be4c7469a6) | Oct 01, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [c6e67f7643](https://linux-hardware.org/?probe=c6e67f7643) | Oct 01, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5f1d0e6142](https://linux-hardware.org/?probe=5f1d0e6142) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [70a80b4201](https://linux-hardware.org/?probe=70a80b4201) | Sep 30, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [f0d1b90e89](https://linux-hardware.org/?probe=f0d1b90e89) | Sep 29, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [36ff9b8bcb](https://linux-hardware.org/?probe=36ff9b8bcb) | Sep 29, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [2e6164b675](https://linux-hardware.org/?probe=2e6164b675) | Sep 28, 2022 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [04589a6a6c](https://linux-hardware.org/?probe=04589a6a6c) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [98742c4135](https://linux-hardware.org/?probe=98742c4135) | Sep 27, 2022 |
| MSI           | B560M PRO                   | Desktop     | [5949440926](https://linux-hardware.org/?probe=5949440926) | Sep 26, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Dell          | Precision 7550              | Notebook    | [347372a20a](https://linux-hardware.org/?probe=347372a20a) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [23f17e2f91](https://linux-hardware.org/?probe=23f17e2f91) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [d401319e57](https://linux-hardware.org/?probe=d401319e57) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| HP            | EliteBook 1040 G4           | Notebook    | [9b4136a781](https://linux-hardware.org/?probe=9b4136a781) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [5ae6fea41e](https://linux-hardware.org/?probe=5ae6fea41e) | Sep 13, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [788cf883c5](https://linux-hardware.org/?probe=788cf883c5) | Sep 10, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [ce084887f1](https://linux-hardware.org/?probe=ce084887f1) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [2f23958df0](https://linux-hardware.org/?probe=2f23958df0) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [be18103b06](https://linux-hardware.org/?probe=be18103b06) | Sep 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [57235f1260](https://linux-hardware.org/?probe=57235f1260) | Sep 05, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [7d505ec2d3](https://linux-hardware.org/?probe=7d505ec2d3) | Sep 05, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | Notebook    | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [7a5978071e](https://linux-hardware.org/?probe=7a5978071e) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [6462d2370f](https://linux-hardware.org/?probe=6462d2370f) | Aug 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [eb79e6b28e](https://linux-hardware.org/?probe=eb79e6b28e) | Aug 31, 2022 |
| HUAWEI        | CREF-XX                     | Notebook    | [4ea2674cd8](https://linux-hardware.org/?probe=4ea2674cd8) | Aug 31, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [05c3d5d7b7](https://linux-hardware.org/?probe=05c3d5d7b7) | Aug 30, 2022 |
| Monster       | Huma H5 V3.2                | Notebook    | [ea050f24db](https://linux-hardware.org/?probe=ea050f24db) | Aug 29, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1337a4c8e9](https://linux-hardware.org/?probe=1337a4c8e9) | Aug 28, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [41459260b8](https://linux-hardware.org/?probe=41459260b8) | Aug 27, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [e05d9e51d5](https://linux-hardware.org/?probe=e05d9e51d5) | Aug 27, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [11867009b0](https://linux-hardware.org/?probe=11867009b0) | Aug 26, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [909b7dcd37](https://linux-hardware.org/?probe=909b7dcd37) | Aug 26, 2022 |
| Acer          | TravelMate 5742G            | Notebook    | [37418dc2c7](https://linux-hardware.org/?probe=37418dc2c7) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| Timi          | TM1701                      | Notebook    | [4591dee526](https://linux-hardware.org/?probe=4591dee526) | Aug 21, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [e762245df3](https://linux-hardware.org/?probe=e762245df3) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | Notebook    | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1f85d6a1b9](https://linux-hardware.org/?probe=1f85d6a1b9) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ccea67d380](https://linux-hardware.org/?probe=ccea67d380) | Aug 19, 2022 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [9d599f3d84](https://linux-hardware.org/?probe=9d599f3d84) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| Dell          | Latitude 3510               | Notebook    | [97e3f5102d](https://linux-hardware.org/?probe=97e3f5102d) | Aug 15, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [c0c3232fad](https://linux-hardware.org/?probe=c0c3232fad) | Aug 15, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [76550f7aef](https://linux-hardware.org/?probe=76550f7aef) | Aug 15, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [dd375c139f](https://linux-hardware.org/?probe=dd375c139f) | Aug 14, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7cd120b2e1](https://linux-hardware.org/?probe=7cd120b2e1) | Aug 14, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [20746ad23d](https://linux-hardware.org/?probe=20746ad23d) | Aug 09, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [db33232b90](https://linux-hardware.org/?probe=db33232b90) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [f0c5f6a834](https://linux-hardware.org/?probe=f0c5f6a834) | Aug 07, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ba034abead](https://linux-hardware.org/?probe=ba034abead) | Aug 07, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | Desktop     | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Monster       | ABRA A5 V13.1               | Notebook    | [557923ae7f](https://linux-hardware.org/?probe=557923ae7f) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [55af061736](https://linux-hardware.org/?probe=55af061736) | Aug 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [705f31df94](https://linux-hardware.org/?probe=705f31df94) | Aug 05, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [9edf66f0ec](https://linux-hardware.org/?probe=9edf66f0ec) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [06852d59ac](https://linux-hardware.org/?probe=06852d59ac) | Aug 04, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [057187b6c9](https://linux-hardware.org/?probe=057187b6c9) | Aug 04, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | Notebook    | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| Sony          | SVE1113M1EW                 | Notebook    | [7a18b67232](https://linux-hardware.org/?probe=7a18b67232) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [110c94eb72](https://linux-hardware.org/?probe=110c94eb72) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | Notebook    | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | Notebook    | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| HP            | 81C6 MVB 0C                 | Server      | [7f5bd87d2e](https://linux-hardware.org/?probe=7f5bd87d2e) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [ef6984a3a9](https://linux-hardware.org/?probe=ef6984a3a9) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | Notebook    | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Acer          | Veriton ES2740G V:1.0       | Desktop     | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| Monster       | ABRA A5 V16.6               | Notebook    | [d26a2b3f0a](https://linux-hardware.org/?probe=d26a2b3f0a) | Jul 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8bf5cae166](https://linux-hardware.org/?probe=8bf5cae166) | Jul 23, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | Notebook    | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ARCELIK       | 1S7-GNB1586B1I5             | Notebook    | [e9a81688b3](https://linux-hardware.org/?probe=e9a81688b3) | Jul 20, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [f74458bf19](https://linux-hardware.org/?probe=f74458bf19) | Jul 19, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [720cc9c1ce](https://linux-hardware.org/?probe=720cc9c1ce) | Jul 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [b85c907afc](https://linux-hardware.org/?probe=b85c907afc) | Jul 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [5528f26010](https://linux-hardware.org/?probe=5528f26010) | Jul 19, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2ddc53797a](https://linux-hardware.org/?probe=2ddc53797a) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Pegatron      | D15K                        | Notebook    | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| ASUSTek       | X553SA                      | Notebook    | [f28ef11fe2](https://linux-hardware.org/?probe=f28ef11fe2) | Jul 15, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [2ba7d6af57](https://linux-hardware.org/?probe=2ba7d6af57) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [d25b4ecc69](https://linux-hardware.org/?probe=d25b4ecc69) | Jul 11, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [9d74a4a9cb](https://linux-hardware.org/?probe=9d74a4a9cb) | Jul 10, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [09bdb4be6a](https://linux-hardware.org/?probe=09bdb4be6a) | Jul 08, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f4d2c6bb1e](https://linux-hardware.org/?probe=f4d2c6bb1e) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| Pegatron      | H36FF                       | Notebook    | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [825362cafe](https://linux-hardware.org/?probe=825362cafe) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f852861149](https://linux-hardware.org/?probe=f852861149) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6b942bfd10](https://linux-hardware.org/?probe=6b942bfd10) | Jul 05, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [ab366fcbe6](https://linux-hardware.org/?probe=ab366fcbe6) | Jul 05, 2022 |
| HP            | 83EE                        | Desktop     | [a49f00b158](https://linux-hardware.org/?probe=a49f00b158) | Jul 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [cea4b92a7d](https://linux-hardware.org/?probe=cea4b92a7d) | Jul 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [0ffa87cfad](https://linux-hardware.org/?probe=0ffa87cfad) | Jul 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| HP            | 84DE                        | All in one  | [8af29f9d6c](https://linux-hardware.org/?probe=8af29f9d6c) | Jul 04, 2022 |
| ASUSTek       | X553SA                      | Notebook    | [e3cd0aa8d4](https://linux-hardware.org/?probe=e3cd0aa8d4) | Jul 02, 2022 |
| Gigabyte      | EP45-DS3                    | Desktop     | [bc316ca4cb](https://linux-hardware.org/?probe=bc316ca4cb) | Jul 02, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [63da8fa3b9](https://linux-hardware.org/?probe=63da8fa3b9) | Jul 02, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [d352a1c731](https://linux-hardware.org/?probe=d352a1c731) | Jul 02, 2022 |
| ASUSTek       | H61M-PRO                    | Desktop     | [48464c0df0](https://linux-hardware.org/?probe=48464c0df0) | Jun 30, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | 340S G7                     | Notebook    | [6695a6a5ed](https://linux-hardware.org/?probe=6695a6a5ed) | Jun 28, 2022 |
| HP            | 84DE                        | All in one  | [edb267564a](https://linux-hardware.org/?probe=edb267564a) | Jun 27, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d306afd176](https://linux-hardware.org/?probe=d306afd176) | Jun 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f3742fcee5](https://linux-hardware.org/?probe=f3742fcee5) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [1860dff362](https://linux-hardware.org/?probe=1860dff362) | Jun 23, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [6e34269277](https://linux-hardware.org/?probe=6e34269277) | Jun 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8a530af324](https://linux-hardware.org/?probe=8a530af324) | Jun 21, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d4896fb036](https://linux-hardware.org/?probe=d4896fb036) | Jun 21, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Alienware     | m17 R3                      | Notebook    | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [f2b6d46056](https://linux-hardware.org/?probe=f2b6d46056) | Jun 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [afc1d78a8f](https://linux-hardware.org/?probe=afc1d78a8f) | Jun 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [14500170b0](https://linux-hardware.org/?probe=14500170b0) | Jun 16, 2022 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [e808d94139](https://linux-hardware.org/?probe=e808d94139) | Jun 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| Dell          | Precision 7550              | Notebook    | [bffea13d72](https://linux-hardware.org/?probe=bffea13d72) | Jun 14, 2022 |
| Monster       | HUMA H5 V2.2                | Notebook    | [062a54a327](https://linux-hardware.org/?probe=062a54a327) | Jun 13, 2022 |
| ASUSTek       | P5G41T-M                    | Desktop     | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f58bb7a98a](https://linux-hardware.org/?probe=f58bb7a98a) | Jun 11, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [7e45eef7ba](https://linux-hardware.org/?probe=7e45eef7ba) | Jun 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [4ce4c3ad20](https://linux-hardware.org/?probe=4ce4c3ad20) | Jun 08, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [8fcf9a9913](https://linux-hardware.org/?probe=8fcf9a9913) | Jun 07, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b48f5d554f](https://linux-hardware.org/?probe=b48f5d554f) | Jun 05, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [d7001b6ceb](https://linux-hardware.org/?probe=d7001b6ceb) | Jun 05, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [5ecae1ce0d](https://linux-hardware.org/?probe=5ecae1ce0d) | Jun 04, 2022 |
| Acer          | Swift SF314-41G             | Notebook    | [aad6ae85d1](https://linux-hardware.org/?probe=aad6ae85d1) | Jun 04, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [76e1b187df](https://linux-hardware.org/?probe=76e1b187df) | Jun 04, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [5593b63d10](https://linux-hardware.org/?probe=5593b63d10) | Jun 04, 2022 |
| Acer          | AO722                       | Notebook    | [73850c23ac](https://linux-hardware.org/?probe=73850c23ac) | Jun 02, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [eca3bd70a8](https://linux-hardware.org/?probe=eca3bd70a8) | Jun 02, 2022 |
| Monster       | ABRA A5 V15.8               | Notebook    | [a284d50bb9](https://linux-hardware.org/?probe=a284d50bb9) | Jun 01, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [dedf695fc6](https://linux-hardware.org/?probe=dedf695fc6) | May 31, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [cf41cc78f7](https://linux-hardware.org/?probe=cf41cc78f7) | May 30, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [a1e7cf7158](https://linux-hardware.org/?probe=a1e7cf7158) | May 30, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [4d4ea4beec](https://linux-hardware.org/?probe=4d4ea4beec) | May 30, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| Lenovo        | 30C7 SDK0J40688 WIN 3424... | Desktop     | [93ffb95e1a](https://linux-hardware.org/?probe=93ffb95e1a) | May 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| HP            | 250 G3                      | Notebook    | [bddc428262](https://linux-hardware.org/?probe=bddc428262) | May 28, 2022 |
| HP            | 250 G3                      | Notebook    | [911bf39209](https://linux-hardware.org/?probe=911bf39209) | May 28, 2022 |
| ECS           | G31T-M7                     | Desktop     | [706532d328](https://linux-hardware.org/?probe=706532d328) | May 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3980ea8269](https://linux-hardware.org/?probe=3980ea8269) | May 27, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [c7e011235c](https://linux-hardware.org/?probe=c7e011235c) | May 26, 2022 |
| Hometech      | Alfa 430C                   | Notebook    | [4f0e4e240d](https://linux-hardware.org/?probe=4f0e4e240d) | May 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2b5ef1dbe5](https://linux-hardware.org/?probe=2b5ef1dbe5) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | Notebook    | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | Notebook    | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [21c0d575b0](https://linux-hardware.org/?probe=21c0d575b0) | May 23, 2022 |
| Toshiba       | Satellite A100              | Notebook    | [a789d51565](https://linux-hardware.org/?probe=a789d51565) | May 23, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [a97b4f8a75](https://linux-hardware.org/?probe=a97b4f8a75) | May 22, 2022 |
| MSI           | MS-7360                     | Desktop     | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [6098005a1a](https://linux-hardware.org/?probe=6098005a1a) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [aac14b5554](https://linux-hardware.org/?probe=aac14b5554) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [6763ad45ce](https://linux-hardware.org/?probe=6763ad45ce) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [8e4aca2b1f](https://linux-hardware.org/?probe=8e4aca2b1f) | May 19, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [4d38806404](https://linux-hardware.org/?probe=4d38806404) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [9c3b90c60d](https://linux-hardware.org/?probe=9c3b90c60d) | May 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [76c661d512](https://linux-hardware.org/?probe=76c661d512) | May 18, 2022 |
| Sony          | SVS1512U1RW                 | Notebook    | [491818d2e0](https://linux-hardware.org/?probe=491818d2e0) | May 18, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Clevo         | M540SS                      | Notebook    | [9860619027](https://linux-hardware.org/?probe=9860619027) | May 15, 2022 |
| Clevo         | M540SS                      | Notebook    | [e2fa8573fb](https://linux-hardware.org/?probe=e2fa8573fb) | May 15, 2022 |
| ECS           | G41T-R3                     | Desktop     | [ed8d019c1e](https://linux-hardware.org/?probe=ed8d019c1e) | May 14, 2022 |
| ECS           | G41T-R3                     | Desktop     | [1bf10674d0](https://linux-hardware.org/?probe=1bf10674d0) | May 14, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | Notebook    | [0a28329f7a](https://linux-hardware.org/?probe=0a28329f7a) | May 12, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [ea8ce36bef](https://linux-hardware.org/?probe=ea8ce36bef) | May 12, 2022 |
| HP            | Pavilion dv6                | Notebook    | [9e5da14b9f](https://linux-hardware.org/?probe=9e5da14b9f) | May 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [c378efbd3d](https://linux-hardware.org/?probe=c378efbd3d) | May 11, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [0e3079b5a1](https://linux-hardware.org/?probe=0e3079b5a1) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [65e46938b9](https://linux-hardware.org/?probe=65e46938b9) | May 10, 2022 |
| Acer          | AO722                       | Notebook    | [645156f92d](https://linux-hardware.org/?probe=645156f92d) | May 10, 2022 |
| Monster       | HUMA H4 V3.1                | Notebook    | [38372af132](https://linux-hardware.org/?probe=38372af132) | May 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [267b134fdd](https://linux-hardware.org/?probe=267b134fdd) | May 09, 2022 |
| ASUSTek       | P5Q SE/R                    | Desktop     | [c99b0a0683](https://linux-hardware.org/?probe=c99b0a0683) | May 08, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [78b977ea42](https://linux-hardware.org/?probe=78b977ea42) | May 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8c1fedaa4b](https://linux-hardware.org/?probe=8c1fedaa4b) | May 06, 2022 |
| Vestel        | V Note 1341                 | Notebook    | [d5a260dc00](https://linux-hardware.org/?probe=d5a260dc00) | May 05, 2022 |
| MSI           | Prestige 15 A12UC           | Notebook    | [2b86e2ca60](https://linux-hardware.org/?probe=2b86e2ca60) | May 04, 2022 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [7b293f80bc](https://linux-hardware.org/?probe=7b293f80bc) | May 03, 2022 |
| HP            | 158Ch                       | Mini pc     | [241022b1d0](https://linux-hardware.org/?probe=241022b1d0) | May 01, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| ASUSTek       | X550VC                      | Notebook    | [16223d208e](https://linux-hardware.org/?probe=16223d208e) | Apr 30, 2022 |
| Dell          | Latitude 7390               | Notebook    | [bbf3908118](https://linux-hardware.org/?probe=bbf3908118) | Apr 30, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [d1e0096b2d](https://linux-hardware.org/?probe=d1e0096b2d) | Apr 29, 2022 |
| HP            | ProBook 4510s               | Notebook    | [d020eac67a](https://linux-hardware.org/?probe=d020eac67a) | Apr 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [17a853c8ff](https://linux-hardware.org/?probe=17a853c8ff) | Apr 27, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [f09766a481](https://linux-hardware.org/?probe=f09766a481) | Apr 27, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Desktop     | [d74b2d8bb3](https://linux-hardware.org/?probe=d74b2d8bb3) | Apr 26, 2022 |
| Lenovo        | ThinkPad E15 20RDS03500     | Notebook    | [6aa4c36808](https://linux-hardware.org/?probe=6aa4c36808) | Apr 26, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [5275d17d40](https://linux-hardware.org/?probe=5275d17d40) | Apr 24, 2022 |
| Acer          | Aspire A515-56G             | Notebook    | [492dd679be](https://linux-hardware.org/?probe=492dd679be) | Apr 24, 2022 |
| Acer          | Aspire A515-56G             | Notebook    | [5fc4dbeaad](https://linux-hardware.org/?probe=5fc4dbeaad) | Apr 24, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Desktop     | [0d4977ae14](https://linux-hardware.org/?probe=0d4977ae14) | Apr 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [a76e953825](https://linux-hardware.org/?probe=a76e953825) | Apr 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce3b387afa](https://linux-hardware.org/?probe=ce3b387afa) | Apr 21, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [68a04098ec](https://linux-hardware.org/?probe=68a04098ec) | Apr 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [8cbc7d1caf](https://linux-hardware.org/?probe=8cbc7d1caf) | Apr 20, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [85f9b41fe4](https://linux-hardware.org/?probe=85f9b41fe4) | Apr 19, 2022 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [f940c46866](https://linux-hardware.org/?probe=f940c46866) | Apr 17, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [49c981ee41](https://linux-hardware.org/?probe=49c981ee41) | Apr 17, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [c394557d17](https://linux-hardware.org/?probe=c394557d17) | Apr 16, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [427335d90c](https://linux-hardware.org/?probe=427335d90c) | Apr 16, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [dc9ac2e9b6](https://linux-hardware.org/?probe=dc9ac2e9b6) | Apr 15, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b40d10cb81](https://linux-hardware.org/?probe=b40d10cb81) | Apr 14, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [5064c36f02](https://linux-hardware.org/?probe=5064c36f02) | Apr 14, 2022 |
| Monster       | ABRA A5 V15.8               | Notebook    | [28f1e82585](https://linux-hardware.org/?probe=28f1e82585) | Apr 13, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [a4b25c87fa](https://linux-hardware.org/?probe=a4b25c87fa) | Apr 13, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [2366b7b28d](https://linux-hardware.org/?probe=2366b7b28d) | Apr 12, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [b6c1c28521](https://linux-hardware.org/?probe=b6c1c28521) | Apr 11, 2022 |
| Sony          | SVF1521GSTB                 | Notebook    | [5537b2189d](https://linux-hardware.org/?probe=5537b2189d) | Apr 10, 2022 |
| MSI           | MS-7360                     | Desktop     | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2fa2ca8320](https://linux-hardware.org/?probe=2fa2ca8320) | Apr 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b86cec3f38](https://linux-hardware.org/?probe=b86cec3f38) | Apr 10, 2022 |
| Monster       | ABRA A5 V12.1               | Notebook    | [4b45daf3b2](https://linux-hardware.org/?probe=4b45daf3b2) | Apr 10, 2022 |
| ASUSTek       | H61M-PRO                    | Desktop     | [c89c043120](https://linux-hardware.org/?probe=c89c043120) | Apr 10, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [acff685c08](https://linux-hardware.org/?probe=acff685c08) | Apr 09, 2022 |
| Dell          | Latitude E5440              | Notebook    | [18290ab7b0](https://linux-hardware.org/?probe=18290ab7b0) | Apr 08, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [9dfd75a7dd](https://linux-hardware.org/?probe=9dfd75a7dd) | Apr 07, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [0dbc471fee](https://linux-hardware.org/?probe=0dbc471fee) | Apr 07, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [645adad8a7](https://linux-hardware.org/?probe=645adad8a7) | Apr 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| Dell          | G3 3579                     | Notebook    | [9994b24cef](https://linux-hardware.org/?probe=9994b24cef) | Apr 06, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [96372fecb5](https://linux-hardware.org/?probe=96372fecb5) | Apr 05, 2022 |
| HP            | Victus by Laptop 16         | Notebook    | [62650f5d20](https://linux-hardware.org/?probe=62650f5d20) | Apr 04, 2022 |
| ASUSTek       | H61M-D                      | Desktop     | [b9c2af0976](https://linux-hardware.org/?probe=b9c2af0976) | Apr 03, 2022 |
| MSI           | GS75 Stealth 9SF            | Notebook    | [048bb1c397](https://linux-hardware.org/?probe=048bb1c397) | Apr 03, 2022 |
| ASUSTek       | B560M-P                     | Desktop     | [d696143851](https://linux-hardware.org/?probe=d696143851) | Apr 03, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [ea091854ed](https://linux-hardware.org/?probe=ea091854ed) | Apr 01, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [ae491737c7](https://linux-hardware.org/?probe=ae491737c7) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [6096184486](https://linux-hardware.org/?probe=6096184486) | Mar 31, 2022 |
| Intel         | Unknown                     | Desktop     | [4689fbf7e1](https://linux-hardware.org/?probe=4689fbf7e1) | Mar 31, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [d42d4a24cd](https://linux-hardware.org/?probe=d42d4a24cd) | Mar 30, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [17f97e88c0](https://linux-hardware.org/?probe=17f97e88c0) | Mar 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [1c58a58ead](https://linux-hardware.org/?probe=1c58a58ead) | Mar 29, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [656413f7e6](https://linux-hardware.org/?probe=656413f7e6) | Mar 28, 2022 |
| LG Electro... | P1-JSUVT                    | Notebook    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [a3ecefa43f](https://linux-hardware.org/?probe=a3ecefa43f) | Mar 26, 2022 |
| ASUSTek       | X542UR                      | Notebook    | [4d4477bd16](https://linux-hardware.org/?probe=4d4477bd16) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS09Y19    | Notebook    | [2602549f95](https://linux-hardware.org/?probe=2602549f95) | Mar 25, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [a56ed819d1](https://linux-hardware.org/?probe=a56ed819d1) | Mar 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [46344218a6](https://linux-hardware.org/?probe=46344218a6) | Mar 22, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [8883dc7315](https://linux-hardware.org/?probe=8883dc7315) | Mar 22, 2022 |
| MSI           | MS-7360                     | Desktop     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [c294e20164](https://linux-hardware.org/?probe=c294e20164) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [5b9b7903ad](https://linux-hardware.org/?probe=5b9b7903ad) | Mar 21, 2022 |
| Casper        | EXCALIBUR G900              | Notebook    | [d4902562f0](https://linux-hardware.org/?probe=d4902562f0) | Mar 21, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [39746d7497](https://linux-hardware.org/?probe=39746d7497) | Mar 20, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6da9c9f35d](https://linux-hardware.org/?probe=6da9c9f35d) | Mar 19, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0fe350f296](https://linux-hardware.org/?probe=0fe350f296) | Mar 19, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [6d64c8e4de](https://linux-hardware.org/?probe=6d64c8e4de) | Mar 19, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [ad3e8cb6c8](https://linux-hardware.org/?probe=ad3e8cb6c8) | Mar 19, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [9ad3eef70b](https://linux-hardware.org/?probe=9ad3eef70b) | Mar 19, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d1f5b906e4](https://linux-hardware.org/?probe=d1f5b906e4) | Mar 19, 2022 |
| MSI           | MS-7360                     | Desktop     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d943b94c21](https://linux-hardware.org/?probe=d943b94c21) | Mar 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [591f5cdcc0](https://linux-hardware.org/?probe=591f5cdcc0) | Mar 18, 2022 |
| HP            | Pavilion g6                 | Notebook    | [67e332bb9f](https://linux-hardware.org/?probe=67e332bb9f) | Mar 18, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [962a1f764e](https://linux-hardware.org/?probe=962a1f764e) | Mar 18, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [0cd9c29dd0](https://linux-hardware.org/?probe=0cd9c29dd0) | Mar 18, 2022 |
| HP            | Victus by Laptop 16         | Notebook    | [cbf47a2c89](https://linux-hardware.org/?probe=cbf47a2c89) | Mar 18, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [b8fa124867](https://linux-hardware.org/?probe=b8fa124867) | Mar 17, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [421906c2ff](https://linux-hardware.org/?probe=421906c2ff) | Mar 17, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | Notebook    | [1ac160aea7](https://linux-hardware.org/?probe=1ac160aea7) | Mar 15, 2022 |
| Insyde        | i101c                       | Notebook    | [1d1171c005](https://linux-hardware.org/?probe=1d1171c005) | Mar 15, 2022 |
| ASUSTek       | GL502VSK                    | Notebook    | [f9f75e4f3d](https://linux-hardware.org/?probe=f9f75e4f3d) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [9b2f013b90](https://linux-hardware.org/?probe=9b2f013b90) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [c24379e7da](https://linux-hardware.org/?probe=c24379e7da) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [09d876ab23](https://linux-hardware.org/?probe=09d876ab23) | Mar 11, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [e0e30a9273](https://linux-hardware.org/?probe=e0e30a9273) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [160a8dd021](https://linux-hardware.org/?probe=160a8dd021) | Mar 10, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [b5a2bf57eb](https://linux-hardware.org/?probe=b5a2bf57eb) | Mar 09, 2022 |
| Acer          | AO722                       | Notebook    | [fc0bccc42d](https://linux-hardware.org/?probe=fc0bccc42d) | Mar 09, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [3e6993a459](https://linux-hardware.org/?probe=3e6993a459) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [2b8b852d07](https://linux-hardware.org/?probe=2b8b852d07) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| HP            | Notebook                    | Notebook    | [a15666c682](https://linux-hardware.org/?probe=a15666c682) | Mar 07, 2022 |
| HP            | Notebook                    | Notebook    | [85eb96edd4](https://linux-hardware.org/?probe=85eb96edd4) | Mar 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [0456c09970](https://linux-hardware.org/?probe=0456c09970) | Mar 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [d3b3f1e5d2](https://linux-hardware.org/?probe=d3b3f1e5d2) | Mar 05, 2022 |
| Fujitsu Si... | D2598-A1 S26361-D2598-A1    | Desktop     | [b003806a72](https://linux-hardware.org/?probe=b003806a72) | Mar 05, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [71481e0139](https://linux-hardware.org/?probe=71481e0139) | Mar 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d09a669d80](https://linux-hardware.org/?probe=d09a669d80) | Mar 03, 2022 |
| Clevo         | E512xQ/E4129                | Notebook    | [7aff97f14f](https://linux-hardware.org/?probe=7aff97f14f) | Mar 02, 2022 |
| MSI           | A58M-E33                    | Desktop     | [58f83fb7fc](https://linux-hardware.org/?probe=58f83fb7fc) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [65a9b832d2](https://linux-hardware.org/?probe=65a9b832d2) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [738744d850](https://linux-hardware.org/?probe=738744d850) | Mar 01, 2022 |
| Clevo         | M540SS                      | Notebook    | [50fafbe5e8](https://linux-hardware.org/?probe=50fafbe5e8) | Mar 01, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [f62c829839](https://linux-hardware.org/?probe=f62c829839) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60d1c44981](https://linux-hardware.org/?probe=60d1c44981) | Feb 28, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [9c482a1888](https://linux-hardware.org/?probe=9c482a1888) | Feb 28, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [fdbadf4dcb](https://linux-hardware.org/?probe=fdbadf4dcb) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9e496b4990](https://linux-hardware.org/?probe=9e496b4990) | Feb 27, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [101d5588d2](https://linux-hardware.org/?probe=101d5588d2) | Feb 26, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [a24f9785ac](https://linux-hardware.org/?probe=a24f9785ac) | Feb 25, 2022 |
| Monster       | ABRA A5 V16.6               | Notebook    | [61707e5a4b](https://linux-hardware.org/?probe=61707e5a4b) | Feb 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [baa1d24da5](https://linux-hardware.org/?probe=baa1d24da5) | Feb 24, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [399a541ed9](https://linux-hardware.org/?probe=399a541ed9) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c8723d2dd9](https://linux-hardware.org/?probe=c8723d2dd9) | Feb 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [45529bb469](https://linux-hardware.org/?probe=45529bb469) | Feb 21, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [ebca133032](https://linux-hardware.org/?probe=ebca133032) | Feb 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d894476c06](https://linux-hardware.org/?probe=d894476c06) | Feb 21, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [3a8cec53c9](https://linux-hardware.org/?probe=3a8cec53c9) | Feb 20, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [cd97a5dfb4](https://linux-hardware.org/?probe=cd97a5dfb4) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| HP            | Pavilion g6                 | Notebook    | [298655060c](https://linux-hardware.org/?probe=298655060c) | Feb 18, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [f988c3bfdc](https://linux-hardware.org/?probe=f988c3bfdc) | Feb 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [c4b7901caa](https://linux-hardware.org/?probe=c4b7901caa) | Feb 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [5650039a15](https://linux-hardware.org/?probe=5650039a15) | Feb 18, 2022 |
| ASUSTek       | X55A                        | Notebook    | [1ed422d0e2](https://linux-hardware.org/?probe=1ed422d0e2) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [1fa5e259f5](https://linux-hardware.org/?probe=1fa5e259f5) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [92ccebcc90](https://linux-hardware.org/?probe=92ccebcc90) | Feb 16, 2022 |
| Apple         | MacBookPro16,3              | Notebook    | [ee62794632](https://linux-hardware.org/?probe=ee62794632) | Feb 16, 2022 |
| Apple         | MacBookPro16,3              | Notebook    | [a651af2ee1](https://linux-hardware.org/?probe=a651af2ee1) | Feb 15, 2022 |
| HP            | 0B54h D                     | Desktop     | [5081de1d10](https://linux-hardware.org/?probe=5081de1d10) | Feb 14, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [e9f4a5b4a8](https://linux-hardware.org/?probe=e9f4a5b4a8) | Feb 14, 2022 |
| Sony          | SVF1521QSTB                 | Notebook    | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| Gigabyte      | AB350M-D3V-CF               | Desktop     | [8d0cd32859](https://linux-hardware.org/?probe=8d0cd32859) | Feb 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [2289e255e7](https://linux-hardware.org/?probe=2289e255e7) | Feb 13, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [3bbcbc62f5](https://linux-hardware.org/?probe=3bbcbc62f5) | Feb 13, 2022 |
| ASUSTek       | ZenBook UX334FLC_UX334FL    | Notebook    | [d74ad9fc94](https://linux-hardware.org/?probe=d74ad9fc94) | Feb 13, 2022 |
| MSI           | PL62 7RC                    | Notebook    | [1cba3daad7](https://linux-hardware.org/?probe=1cba3daad7) | Feb 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [daa58b3386](https://linux-hardware.org/?probe=daa58b3386) | Feb 12, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [a87e7380d9](https://linux-hardware.org/?probe=a87e7380d9) | Feb 12, 2022 |
| Foxconn       | A88GMV                      | Desktop     | [a1004894e9](https://linux-hardware.org/?probe=a1004894e9) | Feb 11, 2022 |
| HP            | 1998                        | Desktop     | [800ceec2ea](https://linux-hardware.org/?probe=800ceec2ea) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| HP            | ProBook 4510s               | Notebook    | [1ec304f4f6](https://linux-hardware.org/?probe=1ec304f4f6) | Feb 10, 2022 |
| Sony          | SVE1711V1EB                 | Notebook    | [28da9a136f](https://linux-hardware.org/?probe=28da9a136f) | Feb 10, 2022 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [30b9a925de](https://linux-hardware.org/?probe=30b9a925de) | Feb 10, 2022 |
| Sony          | SVE1711V1EB                 | Notebook    | [ce823abe6e](https://linux-hardware.org/?probe=ce823abe6e) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Acer          | VAG70_HC                    | Notebook    | [89df31dc20](https://linux-hardware.org/?probe=89df31dc20) | Feb 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c3bda85409](https://linux-hardware.org/?probe=c3bda85409) | Feb 09, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5de6e1ed8f](https://linux-hardware.org/?probe=5de6e1ed8f) | Feb 08, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [84a6cc3fad](https://linux-hardware.org/?probe=84a6cc3fad) | Feb 08, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [1308425490](https://linux-hardware.org/?probe=1308425490) | Feb 08, 2022 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [277f7ae4fd](https://linux-hardware.org/?probe=277f7ae4fd) | Feb 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [b4cfe297d4](https://linux-hardware.org/?probe=b4cfe297d4) | Feb 08, 2022 |
| Lenovo        | ThinkPad X230 23257R2       | Notebook    | [4fa07e0a61](https://linux-hardware.org/?probe=4fa07e0a61) | Feb 08, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [370a0709e9](https://linux-hardware.org/?probe=370a0709e9) | Feb 07, 2022 |
| ECS           | H55H-M                      | Desktop     | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [837b0e80ef](https://linux-hardware.org/?probe=837b0e80ef) | Feb 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [aec471416a](https://linux-hardware.org/?probe=aec471416a) | Feb 07, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [0892485b4b](https://linux-hardware.org/?probe=0892485b4b) | Feb 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9efa6de9c0](https://linux-hardware.org/?probe=9efa6de9c0) | Feb 07, 2022 |
| Lenovo        | 317C SDK0J40688 WIN 3424... | Desktop     | [f6174ebd67](https://linux-hardware.org/?probe=f6174ebd67) | Feb 06, 2022 |
| HP            | Notebook                    | Notebook    | [69071da574](https://linux-hardware.org/?probe=69071da574) | Feb 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [8d1fa47bb0](https://linux-hardware.org/?probe=8d1fa47bb0) | Feb 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [4b20e9f979](https://linux-hardware.org/?probe=4b20e9f979) | Feb 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [2c3e69a6d2](https://linux-hardware.org/?probe=2c3e69a6d2) | Feb 04, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [cbb1e33af4](https://linux-hardware.org/?probe=cbb1e33af4) | Feb 03, 2022 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [23c8c7962a](https://linux-hardware.org/?probe=23c8c7962a) | Feb 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [3fde135a0c](https://linux-hardware.org/?probe=3fde135a0c) | Feb 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [28c4fcaddd](https://linux-hardware.org/?probe=28c4fcaddd) | Feb 03, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [4c9a0cdddb](https://linux-hardware.org/?probe=4c9a0cdddb) | Feb 03, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [dfa7d6bf8c](https://linux-hardware.org/?probe=dfa7d6bf8c) | Feb 03, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [9ab100b85c](https://linux-hardware.org/?probe=9ab100b85c) | Feb 02, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [e14121100b](https://linux-hardware.org/?probe=e14121100b) | Feb 02, 2022 |
| Insyde        | i101c                       | Notebook    | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [bdb825e963](https://linux-hardware.org/?probe=bdb825e963) | Feb 02, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [b12edb18d5](https://linux-hardware.org/?probe=b12edb18d5) | Feb 01, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [051abf292f](https://linux-hardware.org/?probe=051abf292f) | Jan 30, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [4d4ffcb92f](https://linux-hardware.org/?probe=4d4ffcb92f) | Jan 30, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| HP            | Pavilion g7                 | Notebook    | [02214b67ab](https://linux-hardware.org/?probe=02214b67ab) | Jan 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [0316d10862](https://linux-hardware.org/?probe=0316d10862) | Jan 29, 2022 |
| ASUSTek       | TAICHI21                    | Notebook    | [ccc3361d04](https://linux-hardware.org/?probe=ccc3361d04) | Jan 28, 2022 |
| Unknown       | ASUS Google Nexus 7 (Pro... | Notebook    | [b51e5807f8](https://linux-hardware.org/?probe=b51e5807f8) | Jan 28, 2022 |
| HP            | Pavilion g7                 | Notebook    | [64f1eb2dbe](https://linux-hardware.org/?probe=64f1eb2dbe) | Jan 28, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [5d7886a578](https://linux-hardware.org/?probe=5d7886a578) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | Notebook    | [6b9b9f727e](https://linux-hardware.org/?probe=6b9b9f727e) | Jan 28, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [069306fc04](https://linux-hardware.org/?probe=069306fc04) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [89bbc4800a](https://linux-hardware.org/?probe=89bbc4800a) | Jan 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [08deab0e09](https://linux-hardware.org/?probe=08deab0e09) | Jan 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [a6d89f6ae1](https://linux-hardware.org/?probe=a6d89f6ae1) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [87c1802929](https://linux-hardware.org/?probe=87c1802929) | Jan 19, 2022 |
| HP            | Notebook                    | Notebook    | [782c51f796](https://linux-hardware.org/?probe=782c51f796) | Jan 17, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [f02e2c390e](https://linux-hardware.org/?probe=f02e2c390e) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ef86d029ff](https://linux-hardware.org/?probe=ef86d029ff) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [7345361fc2](https://linux-hardware.org/?probe=7345361fc2) | Jan 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f87a30cc1b](https://linux-hardware.org/?probe=f87a30cc1b) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7e3aee849](https://linux-hardware.org/?probe=a7e3aee849) | Jan 15, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6e363cb43c](https://linux-hardware.org/?probe=6e363cb43c) | Jan 15, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [96b0a9dbdc](https://linux-hardware.org/?probe=96b0a9dbdc) | Jan 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a9f451830b](https://linux-hardware.org/?probe=a9f451830b) | Jan 14, 2022 |
| Intel         | H55                         | Desktop     | [e774b0ecac](https://linux-hardware.org/?probe=e774b0ecac) | Jan 12, 2022 |
| Intel         | H55                         | Desktop     | [6528de9981](https://linux-hardware.org/?probe=6528de9981) | Jan 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13ba6fba7f](https://linux-hardware.org/?probe=13ba6fba7f) | Jan 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [51586040b8](https://linux-hardware.org/?probe=51586040b8) | Jan 08, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [5cd2548a30](https://linux-hardware.org/?probe=5cd2548a30) | Jan 07, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [5e77633e52](https://linux-hardware.org/?probe=5e77633e52) | Jan 07, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [74b342a9fe](https://linux-hardware.org/?probe=74b342a9fe) | Jan 07, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [ed7ca5bcb0](https://linux-hardware.org/?probe=ed7ca5bcb0) | Jan 07, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8a3b6c72a9](https://linux-hardware.org/?probe=8a3b6c72a9) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cafe68988e](https://linux-hardware.org/?probe=cafe68988e) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Turkey/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 231       | 13.25%  |
| Ubuntu 18.04        | 168       | 9.64%   |
| Ubuntu 22.04        | 95        | 5.45%   |
| OpenMandriva 4.3    | 43        | 2.47%   |
| Arch Rolling        | 42        | 2.41%   |
| Debian 11           | 36        | 2.07%   |
| Fedora 37           | 35        | 2.01%   |
| Fedora 36           | 34        | 1.95%   |
| Arch                | 33        | 1.89%   |
| Manjaro             | 27        | 1.55%   |
| ArcoLinux Rolling   | 27        | 1.55%   |
| Zorin 16            | 26        | 1.49%   |
| Fedora 33           | 26        | 1.49%   |
| KDE neon 20.04      | 25        | 1.43%   |
| Fedora 35           | 22        | 1.26%   |
| Linux Mint 20.3     | 21        | 1.2%    |
| OpenMandriva 23.01  | 20        | 1.15%   |
| Linux Mint 20.1     | 19        | 1.09%   |
| Ubuntu 21.10        | 18        | 1.03%   |
| Linux Mint 20       | 18        | 1.03%   |
| Pop!_OS 22.04       | 17        | 0.98%   |
| Linux Mint 21       | 17        | 0.98%   |
| Elementary 6.1      | 17        | 0.98%   |
| ROSA R10            | 16        | 0.92%   |
| Fedora 34           | 16        | 0.92%   |
| Linux Mint 21.1     | 15        | 0.86%   |
| EndeavourOS Rolling | 15        | 0.86%   |
| Linux Mint 20.2     | 14        | 0.8%    |
| Ubuntu 22.10        | 13        | 0.75%   |
| Ubuntu 20.10        | 13        | 0.75%   |
| Zorin 15            | 12        | 0.69%   |
| Ubuntu 21.04        | 12        | 0.69%   |
| Pop!_OS 21.10       | 12        | 0.69%   |
| Pop!_OS 20.04       | 12        | 0.69%   |
| Debian 10           | 12        | 0.69%   |
| Ubuntu Unity 16.04  | 11        | 0.63%   |
| Ubuntu 19.10        | 11        | 0.63%   |
| Ubuntu 19.04        | 11        | 0.63%   |
| Ubuntu 16.04        | 11        | 0.63%   |
| OpenMandriva 4.2    | 11        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 579       | 34.67%  |
| Fedora        | 135       | 8.08%   |
| Linux Mint    | 121       | 7.25%   |
| OpenMandriva  | 88        | 5.27%   |
| Arch          | 73        | 4.37%   |
| Debian        | 60        | 3.59%   |
| Manjaro       | 59        | 3.53%   |
| Pop!_OS       | 52        | 3.11%   |
| Pardus        | 50        | 2.99%   |
| Zorin         | 39        | 2.34%   |
| KDE neon      | 39        | 2.34%   |
| ROSA          | 32        | 1.92%   |
| Kubuntu       | 30        | 1.8%    |
| ArcoLinux     | 30        | 1.8%    |
| Elementary    | 28        | 1.68%   |
| Endless       | 27        | 1.62%   |
| Xubuntu       | 23        | 1.38%   |
| Kali          | 23        | 1.38%   |
| Lubuntu       | 16        | 0.96%   |
| EndeavourOS   | 16        | 0.96%   |
| openSUSE      | 14        | 0.84%   |
| Ubuntu Unity  | 13        | 0.78%   |
| Ubuntu MATE   | 12        | 0.72%   |
| Gentoo        | 9         | 0.54%   |
| Clear Linux   | 8         | 0.48%   |
| LMDE          | 7         | 0.42%   |
| Artix         | 6         | 0.36%   |
| MX            | 5         | 0.3%    |
| Garuda Linux  | 5         | 0.3%    |
| CentOS        | 5         | 0.3%    |
| Parrot        | 4         | 0.24%   |
| Deepin        | 4         | 0.24%   |
| BlackPanther  | 4         | 0.24%   |
| Void Linux    | 3         | 0.18%   |
| Ubuntu Budgie | 3         | 0.18%   |
| SteamOS       | 3         | 0.18%   |
| Solus         | 3         | 0.18%   |
| Nobara        | 3         | 0.18%   |
| Linux Lite    | 3         | 0.18%   |
| Xero          | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 41        | 2.19%   |
| 5.4.0-42-generic         | 25        | 1.33%   |
| 5.4.0-58-generic         | 22        | 1.17%   |
| 6.1.1-desktop-1omv2290   | 20        | 1.07%   |
| 5.15.0-56-generic        | 20        | 1.07%   |
| 5.15.0-58-generic        | 18        | 0.96%   |
| 5.0.0-37-generic         | 15        | 0.8%    |
| 5.4.0-48-generic         | 14        | 0.75%   |
| 5.4.0-26-generic         | 14        | 0.75%   |
| 5.15.0-52-generic        | 14        | 0.75%   |
| 4.18.0-15-generic        | 14        | 0.75%   |
| 5.3.0-40-generic         | 13        | 0.69%   |
| 5.15.0-48-generic        | 13        | 0.69%   |
| 5.10.0-21-amd64          | 13        | 0.69%   |
| 5.19.0-32-generic        | 12        | 0.64%   |
| 5.15.0-43-generic        | 12        | 0.64%   |
| 5.8.0-43-generic         | 11        | 0.59%   |
| 5.8.0-14-generic         | 11        | 0.59%   |
| 5.3.0-46-generic         | 11        | 0.59%   |
| 5.15.0-46-generic        | 11        | 0.59%   |
| 5.11.0-27-generic        | 11        | 0.59%   |
| 5.10.14-desktop-1omv4002 | 11        | 0.59%   |
| 5.4.0-37-generic         | 10        | 0.53%   |
| 5.4.0-29-generic         | 10        | 0.53%   |
| 5.15.0-27-generic        | 10        | 0.53%   |
| 5.13.0-39-generic        | 10        | 0.53%   |
| 5.13.0-30-generic        | 10        | 0.53%   |
| 5.8.0-48-generic         | 9         | 0.48%   |
| 5.4.0-74-generic         | 9         | 0.48%   |
| 5.4.0-73-generic         | 9         | 0.48%   |
| 5.4.0-47-generic         | 9         | 0.48%   |
| 5.4.0-33-generic         | 9         | 0.48%   |
| 5.3.0-42-generic         | 9         | 0.48%   |
| 5.3.0-28-generic         | 9         | 0.48%   |
| 5.15.0-53-generic        | 9         | 0.48%   |
| 5.13.0-28-generic        | 9         | 0.48%   |
| 5.8.0-63-generic         | 8         | 0.43%   |
| 5.8.0-44-generic         | 8         | 0.43%   |
| 5.4.0-65-generic         | 8         | 0.43%   |
| 5.4.0-56-generic         | 8         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 280       | 15.57%  |
| 5.15.0  | 156       | 8.68%   |
| 5.8.0   | 94        | 5.23%   |
| 5.10.0  | 86        | 4.78%   |
| 4.15.0  | 86        | 4.78%   |
| 5.11.0  | 85        | 4.73%   |
| 5.13.0  | 75        | 4.17%   |
| 5.3.0   | 65        | 3.62%   |
| 5.0.0   | 57        | 3.17%   |
| 4.18.0  | 46        | 2.56%   |
| 5.19.0  | 45        | 2.5%    |
| 5.16.7  | 43        | 2.39%   |
| 4.19.0  | 28        | 1.56%   |
| 6.1.1   | 24        | 1.33%   |
| 5.10.14 | 12        | 0.67%   |
| 6.0.12  | 11        | 0.61%   |
| 5.17.5  | 11        | 0.61%   |
| 6.2.6   | 10        | 0.56%   |
| 4.9.60  | 10        | 0.56%   |
| 5.6.0   | 9         | 0.5%    |
| 5.17.1  | 7         | 0.39%   |
| 5.14.0  | 7         | 0.39%   |
| 5.11.11 | 7         | 0.39%   |
| 6.2.10  | 6         | 0.33%   |
| 6.2.0   | 6         | 0.33%   |
| 6.2.8   | 5         | 0.28%   |
| 6.0.9   | 5         | 0.28%   |
| 6.0.8   | 5         | 0.28%   |
| 6.0.2   | 5         | 0.28%   |
| 6.0.0   | 5         | 0.28%   |
| 5.9.16  | 5         | 0.28%   |
| 5.7.0   | 5         | 0.28%   |
| 5.19.5  | 5         | 0.28%   |
| 5.18.13 | 5         | 0.28%   |
| 5.18.0  | 5         | 0.28%   |
| 5.16.16 | 5         | 0.28%   |
| 5.11.10 | 5         | 0.28%   |
| 4.9.124 | 5         | 0.28%   |
| 4.4.0   | 5         | 0.28%   |
| 6.2.7   | 4         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 297       | 16.79%  |
| 5.15    | 217       | 12.27%  |
| 5.10    | 133       | 7.52%   |
| 5.11    | 116       | 6.56%   |
| 5.8     | 111       | 6.27%   |
| 5.13    | 87        | 4.92%   |
| 4.15    | 86        | 4.86%   |
| 5.16    | 77        | 4.35%   |
| 5.3     | 76        | 4.3%    |
| 5.19    | 67        | 3.79%   |
| 5.0     | 59        | 3.34%   |
| 6.1     | 57        | 3.22%   |
| 6.0     | 49        | 2.77%   |
| 4.18    | 49        | 2.77%   |
| 6.2     | 43        | 2.43%   |
| 5.18    | 33        | 1.87%   |
| 5.17    | 32        | 1.81%   |
| 4.19    | 30        | 1.7%    |
| 5.9     | 29        | 1.64%   |
| 4.9     | 23        | 1.3%    |
| 5.14    | 19        | 1.07%   |
| 5.6     | 17        | 0.96%   |
| 5.7     | 16        | 0.9%    |
| 5.12    | 16        | 0.9%    |
| 5.5     | 5         | 0.28%   |
| 4.4     | 5         | 0.28%   |
| 5.2     | 4         | 0.23%   |
| 5.1     | 4         | 0.23%   |
| 4.1     | 3         | 0.17%   |
| 4.13    | 2         | 0.11%   |
| 4.10    | 2         | 0.11%   |
| 6.0.5   | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |
| 4.12    | 1         | 0.06%   |
| 3.4     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1533      | 96.54%  |
| i686    | 44        | 2.77%   |
| aarch64 | 6         | 0.38%   |
| armv7l  | 5         | 0.31%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 749       | 45.07%  |
| KDE5            | 251       | 15.1%   |
| Unknown         | 214       | 12.88%  |
| XFCE            | 164       | 9.87%   |
| X-Cinnamon      | 78        | 4.69%   |
| KDE             | 38        | 2.29%   |
| MATE            | 33        | 1.99%   |
| Pantheon        | 27        | 1.62%   |
| KDE4            | 17        | 1.02%   |
| Cinnamon        | 17        | 1.02%   |
| LXQt            | 15        | 0.9%    |
| Unity           | 13        | 0.78%   |
| LXDE            | 9         | 0.54%   |
| i3              | 8         | 0.48%   |
| Deepin          | 5         | 0.3%    |
| Budgie          | 4         | 0.24%   |
| Trinity         | 3         | 0.18%   |
| sway            | 3         | 0.18%   |
| openbox         | 2         | 0.12%   |
| Hyprland        | 2         | 0.12%   |
| DWM             | 2         | 0.12%   |
| bspwm           | 2         | 0.12%   |
| xmonad          | 1         | 0.06%   |
| qtile           | 1         | 0.06%   |
| GNOME Flashback | 1         | 0.06%   |
| GNOME Classic   | 1         | 0.06%   |
| default         | 1         | 0.06%   |
| awesome         | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1257      | 76.88%  |
| Wayland | 261       | 15.96%  |
| Unknown | 87        | 5.32%   |
| Tty     | 30        | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 833       | 49.97%  |
| SDDM    | 223       | 13.38%  |
| GDM     | 214       | 12.84%  |
| GDM3    | 171       | 10.26%  |
| LightDM | 141       | 8.46%   |
| TDM     | 61        | 3.66%   |
| KDM     | 17        | 1.02%   |
| XDM     | 2         | 0.12%   |
| SLiM    | 2         | 0.12%   |
| LXDM    | 2         | 0.12%   |
| Ly      | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 711       | 43.86%  |
| tr_TR       | 609       | 37.57%  |
| Unknown     | 194       | 11.97%  |
| en_GB       | 40        | 2.47%   |
| C           | 24        | 1.48%   |
| ru_RU       | 15        | 0.93%   |
| de_DE       | 5         | 0.31%   |
| POSIX       | 3         | 0.19%   |
| ar_EG       | 2         | 0.12%   |
| zh_CN       | 1         | 0.06%   |
| tr_TR.UTF8  | 1         | 0.06%   |
| tr_CY       | 1         | 0.06%   |
| ru_UA       | 1         | 0.06%   |
| nl_BE       | 1         | 0.06%   |
| fr_FR       | 1         | 0.06%   |
| fa_IR       | 1         | 0.06%   |
| es_ES       | 1         | 0.06%   |
| en_US.UTF8  | 1         | 0.06%   |
| en_US-UTF-8 | 1         | 0.06%   |
| en_NZ       | 1         | 0.06%   |
| en_IE       | 1         | 0.06%   |
| en_GB.UTF8  | 1         | 0.06%   |
| en_DK       | 1         | 0.06%   |
| en_CA       | 1         | 0.06%   |
| en_AU       | 1         | 0.06%   |
| en_150      | 1         | 0.06%   |
| de_AT       | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 848       | 52.25%  |
| BIOS | 775       | 47.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1250      | 76.5%   |
| Btrfs   | 168       | 10.28%  |
| Overlay | 108       | 6.61%   |
| Unknown | 59        | 3.61%   |
| Xfs     | 15        | 0.92%   |
| Ext2    | 14        | 0.86%   |
| Zfs     | 10        | 0.61%   |
| Tmpfs   | 5         | 0.31%   |
| Ext3    | 2         | 0.12%   |
| Aufs    | 2         | 0.12%   |
| F2fs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 894       | 54.71%  |
| GPT     | 578       | 35.37%  |
| MBR     | 162       | 9.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1383      | 85.74%  |
| Yes       | 230       | 14.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1069      | 65.46%  |
| Yes       | 564       | 34.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 277       | 17.45%  |
| Lenovo                  | 245       | 15.44%  |
| Hewlett-Packard         | 213       | 13.42%  |
| Dell                    | 118       | 7.44%   |
| MSI                     | 106       | 6.68%   |
| Acer                    | 93        | 5.86%   |
| Gigabyte Technology     | 90        | 5.67%   |
| Toshiba                 | 51        | 3.21%   |
| Monster                 | 51        | 3.21%   |
| HUAWEI                  | 36        | 2.27%   |
| Apple                   | 36        | 2.27%   |
| Samsung Electronics     | 30        | 1.89%   |
| Sony                    | 27        | 1.7%    |
| Casper                  | 27        | 1.7%    |
| Unknown                 | 21        | 1.32%   |
| Pegatron                | 16        | 1.01%   |
| Packard Bell            | 14        | 0.88%   |
| Intel                   | 14        | 0.88%   |
| ASRock                  | 12        | 0.76%   |
| Clevo                   | 11        | 0.69%   |
| Hometech                | 9         | 0.57%   |
| Foxconn                 | 8         | 0.5%    |
| ECS                     | 7         | 0.44%   |
| ARCELIK                 | 5         | 0.32%   |
| Vestel                  | 4         | 0.25%   |
| Raspberry Pi Foundation | 4         | 0.25%   |
| Fujitsu                 | 4         | 0.25%   |
| Alienware               | 4         | 0.25%   |
| Notebook                | 3         | 0.19%   |
| Huanan                  | 3         | 0.19%   |
| Fujitsu Siemens         | 3         | 0.19%   |
| AMI                     | 3         | 0.19%   |
| Valve                   | 2         | 0.13%   |
| Quanta                  | 2         | 0.13%   |
| Nvidia                  | 2         | 0.13%   |
| LG Electronics          | 2         | 0.13%   |
| Insyde                  | 2         | 0.13%   |
| HONOR                   | 2         | 0.13%   |
| Biostar                 | 2         | 0.13%   |
| Zillion                 | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 28        | 1.76%   |
| HP Pavilion g6                       | 17        | 1.07%   |
| Casper NIRVANA NOTEBOOK              | 10        | 0.63%   |
| ASUS All Series                      | 9         | 0.57%   |
| HP Pavilion dv6                      | 8         | 0.5%    |
| HP Notebook                          | 8         | 0.5%    |
| HP Pavilion 15                       | 7         | 0.44%   |
| HP 15                                | 7         | 0.44%   |
| Gigabyte B450M S2H                   | 7         | 0.44%   |
| ASUS X550VX                          | 7         | 0.44%   |
| Lenovo V15 G2 ALC 82KD               | 5         | 0.32%   |
| HUAWEI NBLK-WAX9X                    | 5         | 0.32%   |
| HUAWEI KLVL-WXX9                     | 5         | 0.32%   |
| HUAWEI BOHK-WAX9X                    | 5         | 0.32%   |
| HUAWEI BOD-WXX9                      | 5         | 0.32%   |
| HP Pavilion Notebook                 | 5         | 0.32%   |
| Gigabyte G31M-ES2L                   | 5         | 0.32%   |
| Gigabyte A320M-S2H                   | 5         | 0.32%   |
| ASUS X555UB                          | 5         | 0.32%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 5         | 0.32%   |
| ASUS N550JV                          | 5         | 0.32%   |
| Acer Aspire 5750G                    | 5         | 0.32%   |
| Toshiba Satellite L655               | 4         | 0.25%   |
| MSI MS-7A34                          | 4         | 0.25%   |
| MSI MS-7817                          | 4         | 0.25%   |
| MSI MS-7693                          | 4         | 0.25%   |
| Lenovo Legion Y530-15ICH 81FV        | 4         | 0.25%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 4         | 0.25%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 4         | 0.25%   |
| HP Pavilion Gaming Laptop 15-cx0xxx  | 4         | 0.25%   |
| HP ElitePad 1000 G2                  | 4         | 0.25%   |
| HP 250 G3                            | 4         | 0.25%   |
| Gigabyte G41M-ES2L                   | 4         | 0.25%   |
| Dell Inspiron MM061                  | 4         | 0.25%   |
| Dell Inspiron 7577                   | 4         | 0.25%   |
| Dell Inspiron 3580                   | 4         | 0.25%   |
| Dell Inspiron 3542                   | 4         | 0.25%   |
| Dell G3 3500                         | 4         | 0.25%   |
| Casper CASPER NIRVANA NOTEBOOK       | 4         | 0.25%   |
| ASUS X556UQK                         | 4         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 86        | 5.42%   |
| HP Pavilion           | 62        | 3.91%   |
| Dell Inspiron         | 54        | 3.4%    |
| Lenovo IdeaPad        | 53        | 3.34%   |
| Acer Aspire           | 53        | 3.34%   |
| Toshiba Satellite     | 47        | 2.96%   |
| Unknown               | 28        | 1.76%   |
| Monster ABRA          | 26        | 1.64%   |
| HP Laptop             | 24        | 1.51%   |
| Dell Latitude         | 24        | 1.51%   |
| ASUS PRIME            | 21        | 1.32%   |
| ASUS VivoBook         | 20        | 1.26%   |
| HP ProBook            | 19        | 1.2%    |
| HP EliteBook          | 19        | 1.2%    |
| ASUS ROG              | 19        | 1.2%    |
| Monster TULPAR        | 16        | 1.01%   |
| ASUS TUF              | 16        | 1.01%   |
| Casper NIRVANA        | 15        | 0.95%   |
| Dell Vostro           | 14        | 0.88%   |
| Packard Bell EasyNote | 13        | 0.82%   |
| Lenovo Yoga           | 13        | 0.82%   |
| HP 250                | 13        | 0.82%   |
| Acer Nitro            | 13        | 0.82%   |
| Lenovo Legion         | 11        | 0.69%   |
| Gigabyte B450M        | 11        | 0.69%   |
| Acer Swift            | 10        | 0.63%   |
| ASUS All              | 9         | 0.57%   |
| Monster HUMA          | 8         | 0.5%    |
| Lenovo ThinkBook      | 8         | 0.5%    |
| HP Notebook           | 8         | 0.5%    |
| Dell Precision        | 8         | 0.5%    |
| HP ENVY               | 7         | 0.44%   |
| HP Compaq             | 7         | 0.44%   |
| HP 15                 | 7         | 0.44%   |
| Dell G3               | 7         | 0.44%   |
| ASUS X550VX           | 7         | 0.44%   |
| Lenovo ThinkCentre    | 6         | 0.38%   |
| Dell XPS              | 6         | 0.38%   |
| ASUS ASUS             | 6         | 0.38%   |
| Lenovo V15            | 5         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 165       | 10.4%   |
| 2018    | 157       | 9.89%   |
| 2019    | 152       | 9.58%   |
| 2017    | 128       | 8.07%   |
| 2011    | 117       | 7.37%   |
| 2012    | 107       | 6.74%   |
| 2013    | 102       | 6.43%   |
| 2010    | 98        | 6.18%   |
| 2021    | 90        | 5.67%   |
| 2016    | 90        | 5.67%   |
| 2015    | 88        | 5.55%   |
| 2014    | 81        | 5.1%    |
| 2009    | 58        | 3.65%   |
| 2008    | 52        | 3.28%   |
| 2022    | 34        | 2.14%   |
| 2007    | 31        | 1.95%   |
| 2006    | 17        | 1.07%   |
| Unknown | 11        | 0.69%   |
| 2005    | 5         | 0.32%   |
| 2023    | 2         | 0.13%   |
| 2004    | 1         | 0.06%   |
| 2003    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1115      | 70.26%  |
| Desktop        | 390       | 24.57%  |
| Convertible    | 24        | 1.51%   |
| All in one     | 19        | 1.2%    |
| Mini pc        | 13        | 0.82%   |
| Tablet         | 12        | 0.76%   |
| System on chip | 7         | 0.44%   |
| Server         | 5         | 0.32%   |
| Phone          | 2         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1494      | 92.91%  |
| Enabled  | 114       | 7.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1585      | 99.87%  |
| Yes  | 2         | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 402       | 25.05%  |
| 3.01-4.0        | 325       | 20.25%  |
| 16.01-24.0      | 312       | 19.44%  |
| 8.01-16.0       | 291       | 18.13%  |
| 1.01-2.0        | 98        | 6.11%   |
| 32.01-64.0      | 91        | 5.67%   |
| 2.01-3.0        | 33        | 2.06%   |
| 64.01-256.0     | 20        | 1.25%   |
| 24.01-32.0      | 19        | 1.18%   |
| 0.51-1.0        | 13        | 0.81%   |
| More than 256.0 | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 605       | 34.28%  |
| 2.01-3.0   | 464       | 26.29%  |
| 3.01-4.0   | 269       | 15.24%  |
| 4.01-8.0   | 243       | 13.77%  |
| 0.51-1.0   | 101       | 5.72%   |
| 8.01-16.0  | 56        | 3.17%   |
| 0.01-0.5   | 17        | 0.96%   |
| 16.01-24.0 | 6         | 0.34%   |
| 24.01-32.0 | 2         | 0.11%   |
| 32.01-64.0 | 1         | 0.06%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1019      | 62.78%  |
| 2      | 448       | 27.6%   |
| 3      | 93        | 5.73%   |
| 4      | 30        | 1.85%   |
| 5      | 13        | 0.8%    |
| 0      | 11        | 0.68%   |
| 7      | 6         | 0.37%   |
| 6      | 3         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1047      | 65.32%  |
| Yes       | 556       | 34.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1377      | 86.49%  |
| No        | 215       | 13.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1313      | 82.47%  |
| No        | 279       | 17.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1070      | 66.58%  |
| No        | 537       | 33.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 1587      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Istanbul            | 610       | 36.22%  |
| Ankara              | 232       | 13.78%  |
| Izmir               | 161       | 9.56%   |
| Antalya             | 82        | 4.87%   |
| Bursa               | 77        | 4.57%   |
| Adana               | 29        | 1.72%   |
| Konya               | 27        | 1.6%    |
| İzmit              | 24        | 1.43%   |
| Balıkesir          | 20        | 1.19%   |
| Kayseri             | 19        | 1.13%   |
| Gaziantep           | 19        | 1.13%   |
| Denizli             | 16        | 0.95%   |
| Kosekoy             | 15        | 0.89%   |
| Antakya             | 14        | 0.83%   |
| Mersin              | 13        | 0.77%   |
| Aydin               | 13        | 0.77%   |
| Samsun              | 12        | 0.71%   |
| Tekirdağ           | 11        | 0.65%   |
| Mugla               | 11        | 0.65%   |
| Ordu                | 8         | 0.48%   |
| Magnesia ad Sipylum | 8         | 0.48%   |
| Kırklareli         | 8         | 0.48%   |
| Yalova              | 7         | 0.42%   |
| Kartal              | 7         | 0.42%   |
| Adapazarı          | 7         | 0.42%   |
| Trabzon             | 6         | 0.36%   |
| Sisli               | 6         | 0.36%   |
| Malatya             | 6         | 0.36%   |
| Eskişehir          | 6         | 0.36%   |
| Zonguldak           | 5         | 0.3%    |
| Osmaniye            | 5         | 0.3%    |
| OEdemis             | 5         | 0.3%    |
| Erzurum             | 5         | 0.3%    |
| Diyarbakır         | 5         | 0.3%    |
| Çorum              | 5         | 0.3%    |
| Çanakkale          | 5         | 0.3%    |
| Batman              | 5         | 0.3%    |
| Van                 | 4         | 0.24%   |
| Ulus                | 4         | 0.24%   |
| Sanliurfa           | 4         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 329       | 464    | 14.69%  |
| Seagate                     | 313       | 388    | 13.97%  |
| WDC                         | 303       | 426    | 13.53%  |
| SanDisk                     | 201       | 238    | 8.97%   |
| Toshiba                     | 191       | 219    | 8.53%   |
| Kingston                    | 124       | 167    | 5.54%   |
| Unknown                     | 83        | 100    | 3.71%   |
| HGST                        | 60        | 68     | 2.68%   |
| Hitachi                     | 59        | 65     | 2.63%   |
| SK hynix                    | 53        | 64     | 2.37%   |
| Micron Technology           | 40        | 46     | 1.79%   |
| Intel                       | 38        | 49     | 1.7%    |
| Crucial                     | 37        | 46     | 1.65%   |
| A-DATA Technology           | 33        | 38     | 1.47%   |
| China                       | 32        | 37     | 1.43%   |
| Corsair                     | 23        | 30     | 1.03%   |
| Apple                       | 20        | 28     | 0.89%   |
| KIOXIA                      | 19        | 22     | 0.85%   |
| Phison                      | 18        | 18     | 0.8%    |
| KIOXIA-EXCERIA              | 15        | 17     | 0.67%   |
| Fujitsu                     | 13        | 13     | 0.58%   |
| HS-SSD-C100                 | 12        | 12     | 0.54%   |
| OCZ                         | 11        | 13     | 0.49%   |
| JAMESDONKEY                 | 10        | 10     | 0.45%   |
| Netac                       | 9         | 10     | 0.4%    |
| Lexar                       | 8         | 12     | 0.36%   |
| Team                        | 7         | 7      | 0.31%   |
| Silicon Motion              | 7         | 8      | 0.31%   |
| Phison Electronics          | 7         | 7      | 0.31%   |
| UMIS                        | 6         | 8      | 0.27%   |
| Realtek Semiconductor       | 6         | 7      | 0.27%   |
| Pioneer                     | 6         | 16     | 0.27%   |
| LITEON                      | 6         | 7      | 0.27%   |
| Kingston Technology Company | 6         | 6      | 0.27%   |
| KingSpec                    | 6         | 6      | 0.27%   |
| XPG                         | 5         | 7      | 0.22%   |
| Transcend                   | 5         | 5      | 0.22%   |
| Gigabyte Technology         | 5         | 10     | 0.22%   |
| ADATA Technology            | 5         | 7      | 0.22%   |
| Union Memory (Shenzhen)     | 4         | 6      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                  | 40        | 1.67%   |
| SanDisk SSD PLUS 240GB                            | 33        | 1.38%   |
| HGST HTS721010A9E630 1TB                          | 30        | 1.25%   |
| Unknown MMC Card  32GB                            | 21        | 0.88%   |
| Toshiba MQ04ABF100 1TB                            | 21        | 0.88%   |
| Toshiba MQ01ABD100 1TB                            | 21        | 0.88%   |
| Samsung NVMe SSD Drive 256GB                      | 18        | 0.75%   |
| Toshiba MQ01ABF050 500GB                          | 17        | 0.71%   |
| Samsung SSD 860 EVO 250GB                         | 16        | 0.67%   |
| Samsung NVMe SSD Drive 512GB                      | 15        | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 15        | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                   | 14        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                    | 14        | 0.58%   |
| SanDisk SSD PLUS 120GB                            | 14        | 0.58%   |
| Seagate ST500LT012-1DG142 500GB                   | 12        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 12        | 0.5%    |
| SanDisk NVMe SSD Drive 256GB                      | 12        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD                  | 12        | 0.5%    |
| Toshiba TR200 240GB SSD                           | 11        | 0.46%   |
| Seagate ST9500325AS 500GB                         | 11        | 0.46%   |
| Seagate ST1000LM049-2GH172 1TB                    | 11        | 0.46%   |
| Intel NVMe SSD Drive 512GB                        | 11        | 0.46%   |
| Toshiba MQ01ABD075 752GB                          | 10        | 0.42%   |
| Seagate ST1000DM003-1ER162 1TB                    | 10        | 0.42%   |
| Seagate Expansion 4TB                             | 10        | 0.42%   |
| Kingston SA400S37120G 120GB SSD                   | 10        | 0.42%   |
| HGST HTS541010A9E680 1TB                          | 10        | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 9         | 0.38%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 9         | 0.38%   |
| SanDisk SSD PLUS 480GB                            | 9         | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                      | 9         | 0.38%   |
| Samsung SSD 860 EVO 500GB                         | 9         | 0.38%   |
| A-DATA SU650 120GB SSD                            | 9         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 8         | 0.33%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 8         | 0.33%   |
| Unknown MMC Card  64GB                            | 8         | 0.33%   |
| Toshiba DT01ACA100 1TB                            | 8         | 0.33%   |
| SK hynix NVMe SSD Drive 512GB                     | 8         | 0.33%   |
| Seagate ST3500418AS 500GB                         | 8         | 0.33%   |
| Seagate ST1000LM048-2E7172 1TB                    | 8         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 307       | 378    | 33.52%  |
| WDC                 | 245       | 349    | 26.75%  |
| Toshiba             | 142       | 155    | 15.5%   |
| Samsung Electronics | 69        | 90     | 7.53%   |
| HGST                | 60        | 68     | 6.55%   |
| Hitachi             | 59        | 65     | 6.44%   |
| Fujitsu             | 13        | 13     | 1.42%   |
| Unknown             | 6         | 7      | 0.66%   |
| Maxtor              | 4         | 4      | 0.44%   |
| Apple               | 3         | 6      | 0.33%   |
| Pioneer             | 2         | 10     | 0.22%   |
| JMicron Technology  | 2         | 2      | 0.22%   |
| Intenso             | 1         | 1      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |
| China               | 1         | 1      | 0.11%   |
| 128MB               | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 143       | 172    | 20.06%  |
| Samsung Electronics | 125       | 165    | 17.53%  |
| Kingston            | 100       | 137    | 14.03%  |
| WDC                 | 38        | 44     | 5.33%   |
| Crucial             | 30        | 37     | 4.21%   |
| China               | 28        | 31     | 3.93%   |
| Toshiba             | 24        | 26     | 3.37%   |
| A-DATA Technology   | 23        | 26     | 3.23%   |
| Corsair             | 19        | 21     | 2.66%   |
| Micron Technology   | 16        | 19     | 2.24%   |
| KIOXIA-EXCERIA      | 12        | 14     | 1.68%   |
| SK hynix            | 11        | 14     | 1.54%   |
| OCZ                 | 11        | 13     | 1.54%   |
| Netac               | 9         | 10     | 1.26%   |
| JAMESDONKEY         | 9         | 9      | 1.26%   |
| Intel               | 9         | 15     | 1.26%   |
| Apple               | 9         | 10     | 1.26%   |
| Lexar               | 7         | 11     | 0.98%   |
| Team                | 6         | 6      | 0.84%   |
| Seagate             | 6         | 7      | 0.84%   |
| LITEON              | 6         | 7      | 0.84%   |
| KingSpec            | 6         | 6      | 0.84%   |
| Pioneer             | 4         | 6      | 0.56%   |
| LITEONIT            | 4         | 5      | 0.56%   |
| HS-SSD-C100         | 4         | 4      | 0.56%   |
| Hewlett-Packard     | 4         | 4      | 0.56%   |
| EZCOOL              | 4         | 5      | 0.56%   |
| Transcend           | 3         | 3      | 0.42%   |
| Patriot             | 3         | 4      | 0.42%   |
| GOODRAM             | 3         | 4      | 0.42%   |
| Gigabyte Technology | 3         | 7      | 0.42%   |
| 2.5"                | 3         | 3      | 0.42%   |
| TwinMOS             | 2         | 2      | 0.28%   |
| SPCC                | 2         | 2      | 0.28%   |
| KingFast            | 2         | 3      | 0.28%   |
| KingDian            | 2         | 2      | 0.28%   |
| JD                  | 2         | 2      | 0.28%   |
| Indilinx            | 2         | 4      | 0.28%   |
| Colorful            | 2         | 2      | 0.28%   |
| Apacer              | 2         | 2      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 815       | 1151   | 39.58%  |
| SSD     | 643       | 882    | 31.23%  |
| NVMe    | 490       | 667    | 23.8%   |
| MMC     | 77        | 94     | 3.74%   |
| Unknown | 34        | 43     | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1202      | 1998   | 65.75%  |
| NVMe | 490       | 665    | 26.81%  |
| MMC  | 77        | 94     | 4.21%   |
| SAS  | 59        | 80     | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 926       | 1349   | 64.39%  |
| 0.51-1.0   | 422       | 556    | 29.35%  |
| 1.01-2.0   | 48        | 71     | 3.34%   |
| 3.01-4.0   | 22        | 30     | 1.53%   |
| 4.01-10.0  | 9         | 11     | 0.63%   |
| 2.01-3.0   | 8         | 12     | 0.56%   |
| 10.01-20.0 | 3         | 4      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 519       | 30.62%  |
| 251-500        | 371       | 21.89%  |
| 501-1000       | 222       | 13.1%   |
| 51-100         | 136       | 8.02%   |
| 1-20           | 130       | 7.67%   |
| 1001-2000      | 118       | 6.96%   |
| 21-50          | 106       | 6.25%   |
| 2001-3000      | 35        | 2.06%   |
| More than 3000 | 34        | 2.01%   |
| Unknown        | 24        | 1.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 724       | 41.32%  |
| 21-50          | 336       | 19.18%  |
| 51-100         | 211       | 12.04%  |
| 101-250        | 197       | 11.24%  |
| 251-500        | 119       | 6.79%   |
| 501-1000       | 85        | 4.85%   |
| 1001-2000      | 32        | 1.83%   |
| Unknown        | 24        | 1.37%   |
| More than 3000 | 14        | 0.8%    |
| 2001-3000      | 10        | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB            | 5         | 5      | 2.98%   |
| Seagate ST500DM002-1BD142 500GB   | 5         | 5      | 2.98%   |
| Seagate ST500LT012-1DG142 500GB   | 4         | 6      | 2.38%   |
| HGST HTS721010A9E630 1TB          | 4         | 5      | 2.38%   |
| HGST HTS545050A7E680 500GB        | 4         | 4      | 2.38%   |
| Toshiba MQ01ABF050 500GB          | 3         | 4      | 1.79%   |
| Seagate ST1000LM035-1RK172 970GB  | 3         | 3      | 1.79%   |
| SanDisk SSD PLUS 240GB            | 3         | 3      | 1.79%   |
| Kingston SV300S37A120G 120GB SSD  | 3         | 4      | 1.79%   |
| Toshiba MQ02ABD100H 1TB           | 2         | 3      | 1.19%   |
| Toshiba MQ01ABD075 752GB          | 2         | 2      | 1.19%   |
| Toshiba MQ01ABD050 500GB          | 2         | 2      | 1.19%   |
| Toshiba DT01ACA050 500GB          | 2         | 2      | 1.19%   |
| Seagate ST9320325AS 320GB         | 2         | 2      | 1.19%   |
| Seagate ST3500630AS 500GB         | 2         | 2      | 1.19%   |
| Seagate ST1000LM014-SSHD-8GB      | 2         | 2      | 1.19%   |
| Samsung Electronics HD161HJ 160GB | 2         | 2      | 1.19%   |
| Kingston SVP200S37A120G 120GB SSD | 2         | 2      | 1.19%   |
| Kingston SUV400S37240G 240GB SSD  | 2         | 2      | 1.19%   |
| Indilinx IND-S325S120G 120GB SSD  | 2         | 4      | 1.19%   |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 1.19%   |
| Hitachi HTS543232A7A384 320GB     | 2         | 2      | 1.19%   |
| Fujitsu MHY2120BH 120GB           | 2         | 2      | 1.19%   |
| 2.5" SATA SSD 3TG6-P 480GB        | 2         | 2      | 1.19%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1         | 1      | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 0.6%    |
| WDC WD5000LPCX-60VHAT0 500GB      | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-60U6AA0 500GB      | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB       | 1         | 2      | 0.6%    |
| WDC WD400JB-00ENA0 40GB           | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-80JJ5T0 320GB      | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 0.6%    |
| WDC WD3200BEVT-60A23T0 320GB      | 1         | 1      | 0.6%    |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 0.6%    |
| WDC WD3200AAJS-00B4A0 320GB       | 1         | 1      | 0.6%    |
| WDC WD3200AACS-00M6B0 320GB       | 1         | 1      | 0.6%    |
| WDC WD30EZRX-00MMMB0 3TB          | 1         | 1      | 0.6%    |
| WDC WD2500JS-55NCB1 250GB         | 1         | 1      | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB          | 1         | 1      | 0.6%    |
| WDC WD10JPVT-75A1YT0 1TB          | 1         | 1      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 41     | 22.89%  |
| Toshiba             | 24        | 26     | 14.46%  |
| WDC                 | 17        | 22     | 10.24%  |
| Hitachi             | 15        | 15     | 9.04%   |
| Samsung Electronics | 13        | 17     | 7.83%   |
| HGST                | 12        | 13     | 7.23%   |
| Kingston            | 9         | 10     | 5.42%   |
| SanDisk             | 8         | 9      | 4.82%   |
| A-DATA Technology   | 8         | 8      | 4.82%   |
| Fujitsu             | 3         | 3      | 1.81%   |
| China               | 3         | 3      | 1.81%   |
| SK hynix            | 2         | 3      | 1.2%    |
| Maxtor              | 2         | 2      | 1.2%    |
| Indilinx            | 2         | 4      | 1.2%    |
| 2.5"                | 2         | 2      | 1.2%    |
| SSD-S400            | 1         | 1      | 0.6%    |
| OCZ                 | 1         | 2      | 0.6%    |
| LITEONIT            | 1         | 2      | 0.6%    |
| LITEON              | 1         | 1      | 0.6%    |
| JMicron Technology  | 1         | 1      | 0.6%    |
| JD                  | 1         | 1      | 0.6%    |
| Intel               | 1         | 1      | 0.6%    |
| Crucial             | 1         | 1      | 0.6%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 41     | 31.67%  |
| Toshiba             | 24        | 26     | 20%     |
| WDC                 | 16        | 21     | 13.33%  |
| Hitachi             | 15        | 15     | 12.5%   |
| HGST                | 12        | 13     | 10%     |
| Samsung Electronics | 10        | 12     | 8.33%   |
| Fujitsu             | 3         | 3      | 2.5%    |
| Maxtor              | 2         | 2      | 1.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 112       | 133    | 70.89%  |
| SSD     | 41        | 50     | 25.95%  |
| NVMe    | 4         | 4      | 2.53%   |
| Unknown | 1         | 1      | 0.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 33.33%  |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1012      | 1710   | 58.53%  |
| Works    | 560       | 936    | 32.39%  |
| Malfunc  | 154       | 188    | 8.91%   |
| Failed   | 3         | 3      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1083      | 56.47%  |
| AMD                              | 258       | 13.45%  |
| Samsung Electronics              | 165       | 8.6%    |
| SanDisk                          | 74        | 3.86%   |
| SK hynix                         | 40        | 2.09%   |
| Phison Electronics               | 32        | 1.67%   |
| Kingston Technology Company      | 30        | 1.56%   |
| KIOXIA                           | 26        | 1.36%   |
| Micron Technology                | 23        | 1.2%    |
| Nvidia                           | 22        | 1.15%   |
| Toshiba America Info Systems     | 21        | 1.09%   |
| JMicron Technology               | 17        | 0.89%   |
| Marvell Technology Group         | 16        | 0.83%   |
| ADATA Technology                 | 15        | 0.78%   |
| Union Memory (Shenzhen)          | 12        | 0.63%   |
| Silicon Motion                   | 12        | 0.63%   |
| Silicon Integrated Systems [SiS] | 12        | 0.63%   |
| Micron/Crucial Technology        | 11        | 0.57%   |
| ASMedia Technology               | 11        | 0.57%   |
| Realtek Semiconductor            | 10        | 0.52%   |
| Apple                            | 7         | 0.36%   |
| Yangtze Memory Technologies      | 4         | 0.21%   |
| VIA Technologies                 | 4         | 0.21%   |
| Lite-On Technology               | 3         | 0.16%   |
| Innodisk                         | 3         | 0.16%   |
| LSI Logic / Symbios Logic        | 2         | 0.1%    |
| ULi Electronics                  | 1         | 0.05%   |
| Transcend                        | 1         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.05%   |
| Promise Technology               | 1         | 0.05%   |
| OCZ Technology Group             | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 186       | 8.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 106       | 4.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 93        | 4.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 75        | 3.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 69        | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 60        | 2.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 48        | 2.2%    |
| Samsung NVMe SSD Controller 980                                                         | 45        | 2.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 45        | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 45        | 2.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 44        | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 44        | 2.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 40        | 1.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 40        | 1.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 35        | 1.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 35        | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 34        | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 34        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 27        | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26        | 1.19%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 24        | 1.1%    |
| Micron NVMe Storage Controller                                                          | 23        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 23        | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 23        | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 22        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 22        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 22        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 21        | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18        | 0.82%   |
| Phison PS5013 E13 NVMe Controller                                                       | 17        | 0.78%   |
| Intel SSD 660P Series                                                                   | 17        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 15        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 15        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 0.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 15        | 0.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 14        | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 14        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1160      | 59.49%  |
| NVMe | 492       | 25.23%  |
| IDE  | 212       | 10.87%  |
| RAID | 84        | 4.31%   |
| SCSI | 2         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1222      | 77%     |
| AMD          | 352       | 22.18%  |
| ARM          | 11        | 0.69%   |
| CentaurHauls | 2         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 1.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 1.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 1.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 1.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 1.32%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 20        | 1.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 18        | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 1.01%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 15        | 0.94%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 14        | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.82%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 13        | 0.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 12        | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 12        | 0.76%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 10        | 0.63%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 10        | 0.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 10        | 0.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 10        | 0.63%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 10        | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.57%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 9         | 0.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 0.57%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 9         | 0.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.5%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 8         | 0.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 8         | 0.5%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 8         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 389       | 24.5%   |
| Intel Core i7           | 323       | 20.34%  |
| AMD Ryzen 5             | 115       | 7.24%   |
| Intel Core i3           | 114       | 7.18%   |
| Other                   | 94        | 5.92%   |
| AMD Ryzen 7             | 67        | 4.22%   |
| Intel Core 2 Duo        | 65        | 4.09%   |
| Intel Celeron           | 65        | 4.09%   |
| Intel Pentium           | 37        | 2.33%   |
| Intel Atom              | 37        | 2.33%   |
| AMD Ryzen 3             | 23        | 1.45%   |
| Intel Xeon              | 21        | 1.32%   |
| Intel Pentium Dual-Core | 21        | 1.32%   |
| Intel Core 2 Quad       | 19        | 1.2%    |
| AMD FX                  | 19        | 1.2%    |
| Intel Pentium Dual      | 16        | 1.01%   |
| AMD A8                  | 16        | 1.01%   |
| Intel Core 2            | 14        | 0.88%   |
| AMD A10                 | 12        | 0.76%   |
| AMD A6                  | 7         | 0.44%   |
| AMD A4                  | 7         | 0.44%   |
| Intel Core i9           | 6         | 0.38%   |
| AMD Ryzen 7 PRO         | 6         | 0.38%   |
| AMD Ryzen 5 PRO         | 6         | 0.38%   |
| AMD Ryzen 9             | 5         | 0.31%   |
| AMD Phenom II X4        | 5         | 0.31%   |
| AMD Athlon 64 X2        | 5         | 0.31%   |
| Intel Pentium 4         | 4         | 0.25%   |
| Intel Genuine           | 4         | 0.25%   |
| AMD Athlon II X3        | 4         | 0.25%   |
| AMD Athlon II X2        | 4         | 0.25%   |
| AMD Athlon              | 4         | 0.25%   |
| AMD A12                 | 4         | 0.25%   |
| Intel Pentium Silver    | 3         | 0.19%   |
| AMD Phenom II X6        | 3         | 0.19%   |
| AMD Phenom              | 3         | 0.19%   |
| AMD E2                  | 3         | 0.19%   |
| AMD C-60                | 3         | 0.19%   |
| AMD Athlon II X4        | 3         | 0.19%   |
| Intel Xeon Silver       | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 694       | 43.7%   |
| 4      | 570       | 35.89%  |
| 6      | 173       | 10.89%  |
| 8      | 85        | 5.35%   |
| 1      | 30        | 1.89%   |
| 3      | 12        | 0.76%   |
| 14     | 9         | 0.57%   |
| 12     | 6         | 0.38%   |
| 10     | 5         | 0.31%   |
| 64     | 1         | 0.06%   |
| 24     | 1         | 0.06%   |
| 20     | 1         | 0.06%   |
| 16     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1582      | 99.68%  |
| 2      | 5         | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1113      | 70.13%  |
| 1      | 473       | 29.8%   |
| 8      | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1540      | 96.79%  |
| Unknown        | 37        | 2.33%   |
| 32-bit         | 13        | 0.82%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 362       | 22.07%  |
| 0x306a9    | 91        | 5.55%   |
| 0x206a7    | 90        | 5.49%   |
| 0x306c3    | 57        | 3.48%   |
| 0x906e9    | 51        | 3.11%   |
| 0x1067a    | 50        | 3.05%   |
| 0x906ea    | 40        | 2.44%   |
| 0x806ea    | 40        | 2.44%   |
| 0x40651    | 38        | 2.32%   |
| 0x806e9    | 36        | 2.2%    |
| 0x806ec    | 33        | 2.01%   |
| 0xa0652    | 32        | 1.95%   |
| 0x506e3    | 32        | 1.95%   |
| 0x306d4    | 32        | 1.95%   |
| 0x406e3    | 31        | 1.89%   |
| 0x20655    | 30        | 1.83%   |
| 0x806c1    | 29        | 1.77%   |
| 0x6fd      | 25        | 1.52%   |
| 0x08108109 | 23        | 1.4%    |
| 0x406c4    | 20        | 1.22%   |
| 0x30678    | 20        | 1.22%   |
| 0x08108102 | 20        | 1.22%   |
| 0x706e5    | 18        | 1.1%    |
| 0x20652    | 18        | 1.1%    |
| 0x08600106 | 18        | 1.1%    |
| 0x10676    | 17        | 1.04%   |
| 0x08608103 | 17        | 1.04%   |
| 0x08701021 | 13        | 0.79%   |
| 0x506c9    | 12        | 0.73%   |
| 0x06000852 | 12        | 0.73%   |
| 0x0a50000c | 11        | 0.67%   |
| 0x0800820d | 10        | 0.61%   |
| 0x08001138 | 10        | 0.61%   |
| 0x06006705 | 10        | 0.61%   |
| 0x6f6      | 9         | 0.55%   |
| 0x406c3    | 9         | 0.55%   |
| 0x08600103 | 9         | 0.55%   |
| 0x010000c8 | 9         | 0.55%   |
| 0x906a3    | 8         | 0.49%   |
| 0x806eb    | 8         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 270       | 17%     |
| Haswell          | 118       | 7.43%   |
| SandyBridge      | 115       | 7.24%   |
| IvyBridge        | 114       | 7.18%   |
| Penryn           | 86        | 5.42%   |
| Skylake          | 83        | 5.23%   |
| Zen 2            | 69        | 4.35%   |
| Zen+             | 67        | 4.22%   |
| Westmere         | 63        | 3.97%   |
| Silvermont       | 58        | 3.65%   |
| Unknown          | 58        | 3.65%   |
| Core             | 57        | 3.59%   |
| CometLake        | 50        | 3.15%   |
| Broadwell        | 43        | 2.71%   |
| TigerLake        | 42        | 2.64%   |
| Zen              | 36        | 2.27%   |
| IceLake          | 36        | 2.27%   |
| Zen 3            | 28        | 1.76%   |
| Piledriver       | 28        | 1.76%   |
| K10              | 26        | 1.64%   |
| Excavator        | 22        | 1.39%   |
| Puma             | 15        | 0.94%   |
| Goldmont         | 15        | 0.94%   |
| Goldmont plus    | 14        | 0.88%   |
| Nehalem          | 12        | 0.76%   |
| Bonnell          | 12        | 0.76%   |
| Bobcat           | 9         | 0.57%   |
| Alderlake Hybrid | 9         | 0.57%   |
| K8 Hammer        | 8         | 0.5%    |
| K10 Llano        | 6         | 0.38%   |
| P6               | 5         | 0.31%   |
| NetBurst         | 5         | 0.31%   |
| Steamroller      | 3         | 0.19%   |
| Bulldozer        | 3         | 0.19%   |
| Tremont          | 1         | 0.06%   |
| K6               | 1         | 0.06%   |
| Jaguar           | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 954       | 45.47%  |
| Nvidia                           | 608       | 28.98%  |
| AMD                              | 520       | 24.79%  |
| Silicon Integrated Systems [SiS] | 10        | 0.48%   |
| VIA Technologies                 | 3         | 0.14%   |
| Matrox Electronics Systems       | 2         | 0.1%    |
| ASPEED Technology                | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 88        | 4.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 81        | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 2.33%   |
| Intel HD Graphics 620                                                                    | 48        | 2.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 2.15%   |
| Intel UHD Graphics 620                                                                   | 43        | 1.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 1.97%   |
| AMD Renoir                                                                               | 43        | 1.97%   |
| Intel HD Graphics 630                                                                    | 39        | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 38        | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 38        | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 36        | 1.65%   |
| Intel HD Graphics 5500                                                                   | 35        | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 1.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 32        | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 32        | 1.46%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 31        | 1.42%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26        | 1.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 25        | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 1.1%    |
| Intel HD Graphics 530                                                                    | 24        | 1.1%    |
| AMD Lucienne                                                                             | 24        | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 0.91%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 20        | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 19        | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 18        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 18        | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18        | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 18        | 0.82%   |
| Nvidia GM108M [GeForce 840M]                                                             | 17        | 0.78%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 16        | 0.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 15        | 0.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 458       | 28.7%   |
| Intel + Nvidia | 368       | 23.06%  |
| 1 x AMD        | 324       | 20.3%   |
| 1 x Nvidia     | 216       | 13.53%  |
| Intel + AMD    | 114       | 7.14%   |
| 2 x AMD        | 58        | 3.63%   |
| AMD + Nvidia   | 25        | 1.57%   |
| Other          | 15        | 0.94%   |
| 1 x SiS        | 10        | 0.63%   |
| 1 x VIA        | 3         | 0.19%   |
| 1 x Matrox     | 2         | 0.13%   |
| 2 x Nvidia     | 1         | 0.06%   |
| 2 x Intel      | 1         | 0.06%   |
| 1 x ASPEED     | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1243      | 77.11%  |
| Proprietary | 309       | 19.17%  |
| Unknown     | 60        | 3.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 818       | 49.85%  |
| 1.01-2.0   | 256       | 15.6%   |
| 0.01-0.5   | 168       | 10.24%  |
| 0.51-1.0   | 167       | 10.18%  |
| 3.01-4.0   | 140       | 8.53%   |
| 5.01-6.0   | 44        | 2.68%   |
| 7.01-8.0   | 23        | 1.4%    |
| 8.01-16.0  | 13        | 0.79%   |
| 2.01-3.0   | 10        | 0.61%   |
| 4.01-5.0   | 1         | 0.06%   |
| 16.01-24.0 | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 243       | 14.79%  |
| LG Display              | 207       | 12.6%   |
| BOE                     | 195       | 11.87%  |
| Samsung Electronics     | 184       | 11.2%   |
| Chimei Innolux          | 155       | 9.43%   |
| Goldstar                | 56        | 3.41%   |
| Philips                 | 55        | 3.35%   |
| Dell                    | 37        | 2.25%   |
| AOC                     | 36        | 2.19%   |
| Ancor Communications    | 35        | 2.13%   |
| Apple                   | 34        | 2.07%   |
| Hewlett-Packard         | 33        | 2.01%   |
| Lenovo                  | 31        | 1.89%   |
| Chi Mei Optoelectronics | 31        | 1.89%   |
| Acer                    | 30        | 1.83%   |
| ViewSonic               | 26        | 1.58%   |
| PANDA                   | 24        | 1.46%   |
| ASUSTek Computer        | 21        | 1.28%   |
| Sharp                   | 20        | 1.22%   |
| BenQ                    | 18        | 1.1%    |
| LG Philips              | 11        | 0.67%   |
| MSI                     | 10        | 0.61%   |
| InfoVision              | 9         | 0.55%   |
| CPT                     | 9         | 0.55%   |
| Vestel Elektronik       | 7         | 0.43%   |
| Unknown                 | 7         | 0.43%   |
| Sony                    | 7         | 0.43%   |
| LG Electronics          | 7         | 0.43%   |
| LGD                     | 6         | 0.37%   |
| AGO                     | 6         | 0.37%   |
| SAC                     | 5         | 0.3%    |
| KTC                     | 5         | 0.3%    |
| HKC                     | 5         | 0.3%    |
| Unknown                 | 5         | 0.3%    |
| SANYO                   | 4         | 0.24%   |
| VIE                     | 3         | 0.18%   |
| RTK                     | 3         | 0.18%   |
| Plain Tree Systems      | 3         | 0.18%   |
| Mi                      | 3         | 0.18%   |
| HannStar                | 3         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 1.31%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 14        | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.83%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.77%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 13        | 0.77%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.71%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 11        | 0.65%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 11        | 0.65%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 10        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.48%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 8         | 0.48%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 8         | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.48%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 7         | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 7         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.42%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.42%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 6         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.36%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 6         | 0.36%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.36%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 6         | 0.36%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 6         | 0.36%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 6         | 0.36%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 6         | 0.36%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.36%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 6         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 5         | 0.3%    |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 5         | 0.3%    |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 5         | 0.3%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 5         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 5         | 0.3%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 5         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 726       | 46.21%  |
| 1366x768 (WXGA)    | 442       | 28.13%  |
| 3840x2160 (4K)     | 51        | 3.25%   |
| 2560x1440 (QHD)    | 40        | 2.55%   |
| 1280x800 (WXGA)    | 38        | 2.42%   |
| 1600x900 (HD+)     | 37        | 2.36%   |
| 1440x900 (WXGA+)   | 33        | 2.1%    |
| 1280x1024 (SXGA)   | 32        | 2.04%   |
| Unknown            | 24        | 1.53%   |
| 1680x1050 (WSXGA+) | 20        | 1.27%   |
| 1920x1200 (WUXGA)  | 19        | 1.21%   |
| 2160x1440          | 13        | 0.83%   |
| 2560x1600          | 12        | 0.76%   |
| 1360x768           | 10        | 0.64%   |
| 2560x1080          | 9         | 0.57%   |
| 1024x600           | 8         | 0.51%   |
| 3840x1080          | 7         | 0.45%   |
| 3440x1440          | 5         | 0.32%   |
| 3200x1800 (QHD+)   | 5         | 0.32%   |
| 2880x1800          | 5         | 0.32%   |
| 1920x540           | 4         | 0.25%   |
| 1680x945           | 3         | 0.19%   |
| 800x1280           | 2         | 0.13%   |
| 4480x1440          | 2         | 0.13%   |
| 3000x2000          | 2         | 0.13%   |
| 1024x768 (XGA)     | 2         | 0.13%   |
| 7920x1440          | 1         | 0.06%   |
| 6000x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 3840x2560          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3750x1280          | 1         | 0.06%   |
| 3360x1050          | 1         | 0.06%   |
| 3240x2160          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 3046x1050          | 1         | 0.06%   |
| 2880x1620          | 1         | 0.06%   |
| 2806x900           | 1         | 0.06%   |
| 2646x1024          | 1         | 0.06%   |
| 2520x1680          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 693       | 42.26%  |
| 13      | 148       | 9.02%   |
| 23      | 95        | 5.79%   |
| 21      | 87        | 5.3%    |
| 14      | 83        | 5.06%   |
| Unknown | 74        | 4.51%   |
| 17      | 68        | 4.15%   |
| 27      | 67        | 4.09%   |
| 24      | 60        | 3.66%   |
| 18      | 44        | 2.68%   |
| 19      | 30        | 1.83%   |
| 12      | 26        | 1.59%   |
| 11      | 21        | 1.28%   |
| 31      | 17        | 1.04%   |
| 20      | 17        | 1.04%   |
| 16      | 14        | 0.85%   |
| 10      | 14        | 0.85%   |
| 34      | 13        | 0.79%   |
| 22      | 10        | 0.61%   |
| 84      | 9         | 0.55%   |
| 72      | 7         | 0.43%   |
| 26      | 5         | 0.3%    |
| 40      | 4         | 0.24%   |
| 32      | 4         | 0.24%   |
| 46      | 3         | 0.18%   |
| 33      | 3         | 0.18%   |
| 29      | 3         | 0.18%   |
| 60      | 2         | 0.12%   |
| 57      | 2         | 0.12%   |
| 54      | 2         | 0.12%   |
| 47      | 2         | 0.12%   |
| 43      | 2         | 0.12%   |
| 36      | 2         | 0.12%   |
| 28      | 2         | 0.12%   |
| 7       | 2         | 0.12%   |
| 65      | 1         | 0.06%   |
| 64      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 25      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 851       | 52.34%  |
| 501-600     | 206       | 12.67%  |
| 401-500     | 187       | 11.5%   |
| 201-300     | 143       | 8.79%   |
| 351-400     | 75        | 4.61%   |
| Unknown     | 74        | 4.55%   |
| 601-700     | 29        | 1.78%   |
| 701-800     | 22        | 1.35%   |
| 1501-2000   | 16        | 0.98%   |
| 1001-1500   | 15        | 0.92%   |
| 801-900     | 4         | 0.25%   |
| 901-1000    | 2         | 0.12%   |
| 1-100       | 2         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1211      | 81.44%  |
| 16/10   | 128       | 8.61%   |
| Unknown | 66        | 4.44%   |
| 3/2     | 25        | 1.68%   |
| 5/4     | 24        | 1.61%   |
| 4/3     | 17        | 1.14%   |
| 21/9    | 13        | 0.87%   |
| 0.67    | 2         | 0.13%   |
| 6/5     | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 694       | 42.52%  |
| 201-250        | 219       | 13.42%  |
| 81-90          | 171       | 10.48%  |
| Unknown        | 74        | 4.53%   |
| 301-350        | 69        | 4.23%   |
| 151-200        | 69        | 4.23%   |
| 71-80          | 66        | 4.04%   |
| 141-150        | 56        | 3.43%   |
| 121-130        | 45        | 2.76%   |
| 351-500        | 42        | 2.57%   |
| More than 1000 | 26        | 1.59%   |
| 51-60          | 21        | 1.29%   |
| 61-70          | 20        | 1.23%   |
| 41-50          | 14        | 0.86%   |
| 251-300        | 14        | 0.86%   |
| 501-1000       | 13        | 0.8%    |
| 111-120        | 10        | 0.61%   |
| 91-100         | 4         | 0.25%   |
| 131-140        | 3         | 0.18%   |
| 1-40           | 2         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 510       | 31.68%  |
| 101-120       | 479       | 29.75%  |
| 51-100        | 413       | 25.65%  |
| 161-240       | 91        | 5.65%   |
| Unknown       | 74        | 4.6%    |
| 1-50          | 25        | 1.55%   |
| More than 240 | 18        | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1339      | 82.55%  |
| 2     | 201       | 12.39%  |
| 0     | 73        | 4.5%    |
| 3     | 9         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1022      | 40.81%  |
| Intel                                  | 613       | 24.48%  |
| Qualcomm Atheros                       | 350       | 13.98%  |
| Broadcom                               | 153       | 6.11%   |
| Ralink Technology                      | 58        | 2.32%   |
| Ralink                                 | 31        | 1.24%   |
| Broadcom Limited                       | 30        | 1.2%    |
| Marvell Technology Group               | 28        | 1.12%   |
| ASUSTek Computer                       | 20        | 0.8%    |
| TP-Link                                | 19        | 0.76%   |
| Qualcomm Atheros Communications        | 19        | 0.76%   |
| Nvidia                                 | 19        | 0.76%   |
| MediaTek                               | 19        | 0.76%   |
| Samsung Electronics                    | 16        | 0.64%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.52%   |
| Xiaomi                                 | 12        | 0.48%   |
| ASIX Electronics                       | 6         | 0.24%   |
| ZyXEL Communications                   | 5         | 0.2%    |
| Huawei Technologies                    | 5         | 0.2%    |
| Ericsson Business Mobile Networks      | 5         | 0.2%    |
| JMicron Technology                     | 4         | 0.16%   |
| Apple                                  | 4         | 0.16%   |
| Microchip Technology                   | 3         | 0.12%   |
| Aquantia                               | 3         | 0.12%   |
| Tenda                                  | 2         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.08%   |
| Sierra Wireless                        | 2         | 0.08%   |
| OPPO Electronics                       | 2         | 0.08%   |
| Motorola PCS                           | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| ICS Advent                             | 2         | 0.08%   |
| Dell                                   | 2         | 0.08%   |
| Attansic Technology                    | 2         | 0.08%   |
| Accton Technology                      | 2         | 0.08%   |
| Wilocity                               | 1         | 0.04%   |
| VIA Technologies                       | 1         | 0.04%   |
| ULi Electronics                        | 1         | 0.04%   |
| U-Blox                                 | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Standard Microsystems                  | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 710       | 24.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 162       | 5.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 64        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 62        | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 50        | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 50        | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 45        | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 45        | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 43        | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 40        | 1.4%    |
| Intel Wireless 7265                                               | 36        | 1.26%   |
| Intel Wi-Fi 6 AX201                                               | 36        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 35        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 30        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 29        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 28        | 0.98%   |
| Ralink MT7601U Wireless Adapter                                   | 27        | 0.94%   |
| Intel Wireless 8265 / 8275                                        | 27        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 24        | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 24        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 24        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                     | 23        | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 20        | 0.7%    |
| Intel Wireless 3165                                               | 20        | 0.7%    |
| Intel Wireless 7260                                               | 19        | 0.66%   |
| Intel Wireless 3160                                               | 18        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 0.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 16        | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 15        | 0.52%   |
| Intel Wireless 8260                                               | 15        | 0.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 14        | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                   | 14        | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 14        | 0.49%   |
| Intel I211 Gigabit Network Connection                             | 14        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 531       | 38.17%  |
| Realtek Semiconductor            | 270       | 19.41%  |
| Qualcomm Atheros                 | 267       | 19.19%  |
| Broadcom                         | 118       | 8.48%   |
| Ralink Technology                | 58        | 4.17%   |
| Ralink                           | 31        | 2.23%   |
| Broadcom Limited                 | 20        | 1.44%   |
| ASUSTek Computer                 | 20        | 1.44%   |
| Qualcomm Atheros Communications  | 19        | 1.37%   |
| MediaTek                         | 18        | 1.29%   |
| TP-Link                          | 17        | 1.22%   |
| ZyXEL Communications             | 5         | 0.36%   |
| Tenda                            | 2         | 0.14%   |
| Sierra Wireless                  | 2         | 0.14%   |
| Dell                             | 2         | 0.14%   |
| Accton Technology                | 2         | 0.14%   |
| Wilocity                         | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Marvell Technology Group         | 1         | 0.07%   |
| Linksys                          | 1         | 0.07%   |
| IMC Networks                     | 1         | 0.07%   |
| Fibocom                          | 1         | 0.07%   |
| Edimax Technology                | 1         | 0.07%   |
| Belkin Components                | 1         | 0.07%   |
| AirTies Wireless Networks        | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 64        | 4.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 62        | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 50        | 3.58%   |
| Intel Wi-Fi 6 AX200                                            | 50        | 3.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 45        | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 43        | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 40        | 2.87%   |
| Intel Wireless 7265                                            | 36        | 2.58%   |
| Intel Wi-Fi 6 AX201                                            | 36        | 2.58%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 35        | 2.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 30        | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 29        | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 28        | 2.01%   |
| Ralink MT7601U Wireless Adapter                                | 27        | 1.94%   |
| Intel Wireless 8265 / 8275                                     | 27        | 1.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 24        | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 24        | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 24        | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                  | 23        | 1.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 20        | 1.43%   |
| Intel Wireless 3165                                            | 20        | 1.43%   |
| Intel Wireless 7260                                            | 19        | 1.36%   |
| Intel Wireless 3160                                            | 18        | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 16        | 1.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15        | 1.08%   |
| Intel Wireless 8260                                            | 15        | 1.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 14        | 1%      |
| Qualcomm Atheros AR9271 802.11n                                | 14        | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 14        | 1%      |
| Intel Wireless-AC 9260                                         | 13        | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 12        | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 12        | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 0.86%   |
| Intel WiFi Link 5100                                           | 11        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 0.79%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 10        | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 10        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 935       | 65.89%  |
| Intel                                  | 169       | 11.91%  |
| Qualcomm Atheros                       | 124       | 8.74%   |
| Broadcom                               | 58        | 4.09%   |
| Marvell Technology Group               | 27        | 1.9%    |
| Nvidia                                 | 18        | 1.27%   |
| Xiaomi                                 | 12        | 0.85%   |
| Silicon Integrated Systems [SiS]       | 12        | 0.85%   |
| Broadcom Limited                       | 10        | 0.7%    |
| ASIX Electronics                       | 6         | 0.42%   |
| Samsung Electronics                    | 5         | 0.35%   |
| Huawei Technologies                    | 5         | 0.35%   |
| JMicron Technology                     | 4         | 0.28%   |
| Apple                                  | 4         | 0.28%   |
| Microchip Technology                   | 3         | 0.21%   |
| Aquantia                               | 3         | 0.21%   |
| TP-Link                                | 2         | 0.14%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.14%   |
| OPPO Electronics                       | 2         | 0.14%   |
| Motorola PCS                           | 2         | 0.14%   |
| ICS Advent                             | 2         | 0.14%   |
| Attansic Technology                    | 2         | 0.14%   |
| VIA Technologies                       | 1         | 0.07%   |
| ULi Electronics                        | 1         | 0.07%   |
| Standard Microsystems                  | 1         | 0.07%   |
| Qualcomm                               | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| Mellanox Technologies                  | 1         | 0.07%   |
| MediaTek                               | 1         | 0.07%   |
| LSI                                    | 1         | 0.07%   |
| Lenovo                                 | 1         | 0.07%   |
| Insyde Software                        | 1         | 0.07%   |
| HTC (High Tech Computer)               | 1         | 0.07%   |
| Davicom Semiconductor                  | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 710       | 49.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 162       | 11.26%  |
| Realtek RTL8125 2.5GbE Controller                                              | 24        | 1.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 22        | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21        | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 17        | 1.18%   |
| Intel Ethernet Connection (2) I219-V                                           | 17        | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 0.97%   |
| Intel I211 Gigabit Network Connection                                          | 14        | 0.97%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 12        | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 10        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 10        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 10        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 9         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 9         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 9         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 8         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 0.56%   |
| Intel 82579V Gigabit Network Connection                                        | 8         | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 8         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 7         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 0.49%   |
| Nvidia MCP61 Ethernet                                                          | 7         | 0.49%   |
| Intel I210 Gigabit Network Connection                                          | 7         | 0.49%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 0.49%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 7         | 0.49%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 5         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.35%   |
| Nvidia MCP79 Ethernet                                                          | 5         | 0.35%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.35%   |
| Huawei ATU-L21                                                                 | 5         | 0.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1372      | 50.55%  |
| WiFi     | 1313      | 48.38%  |
| Modem    | 25        | 0.92%   |
| Unknown  | 4         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1077      | 67.02%  |
| Ethernet | 529       | 32.92%  |
| Modem    | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 989       | 62.2%   |
| 1     | 544       | 34.21%  |
| 0     | 38        | 2.39%   |
| 3     | 13        | 0.82%   |
| 4     | 3         | 0.19%   |
| 16    | 1         | 0.06%   |
| 7     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1566      | 98.55%  |
| Yes  | 23        | 1.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 433       | 40.09%  |
| Realtek Semiconductor           | 123       | 11.39%  |
| Qualcomm Atheros Communications | 102       | 9.44%   |
| IMC Networks                    | 88        | 8.15%   |
| Cambridge Silicon Radio         | 62        | 5.74%   |
| Broadcom                        | 48        | 4.44%   |
| Lite-On Technology              | 38        | 3.52%   |
| Foxconn / Hon Hai               | 30        | 2.78%   |
| Apple                           | 27        | 2.5%    |
| Toshiba                         | 23        | 2.13%   |
| ASUSTek Computer                | 22        | 2.04%   |
| Realtek                         | 21        | 1.94%   |
| Ralink                          | 20        | 1.85%   |
| Hewlett-Packard                 | 11        | 1.02%   |
| Dell                            | 10        | 0.93%   |
| TP-Link                         | 5         | 0.46%   |
| MediaTek                        | 4         | 0.37%   |
| Ralink Technology               | 3         | 0.28%   |
| Foxconn International           | 3         | 0.28%   |
| Alps Electric                   | 3         | 0.28%   |
| Qcom                            | 1         | 0.09%   |
| Logitech                        | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| HTC (High Tech Computer)        | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 153       | 14.15%  |
| Intel AX201 Bluetooth                               | 90        | 8.33%   |
| Realtek Bluetooth Radio                             | 72        | 6.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 68        | 6.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 65        | 6.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 62        | 5.74%   |
| Intel AX200 Bluetooth                               | 49        | 4.53%   |
| IMC Networks Bluetooth Radio                        | 31        | 2.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 27        | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.31%   |
| Realtek 802.11ac WLAN Adapter                       | 21        | 1.94%   |
| Ralink RT3290 Bluetooth                             | 20        | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.57%   |
| IMC Networks Bluetooth Device                       | 17        | 1.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 14        | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1.3%    |
| Apple Bluetooth Host Controller                     | 14        | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 1.2%    |
| Lite-On Bluetooth Device                            | 13        | 1.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 12        | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 1.11%   |
| IMC Networks Bluetooth USB Host Controller          | 12        | 1.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 11        | 1.02%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 0.83%   |
| IMC Networks Bluetooth                              | 9         | 0.83%   |
| Apple Bluetooth USB Host Controller                 | 9         | 0.83%   |
| Realtek RTL8821A Bluetooth                          | 7         | 0.65%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.65%   |
| ASUS BT-253 Bluetooth Adapter                       | 7         | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.56%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 0.56%   |
| TP-Link UB500 Adapter                               | 5         | 0.46%   |
| Toshiba Askey Bluetooth Module                      | 5         | 0.46%   |
| Intel Bluetooth Device                              | 5         | 0.46%   |
| IMC Networks Wireless_Device                        | 5         | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.46%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1166      | 55.55%  |
| AMD                                             | 455       | 21.68%  |
| Nvidia                                          | 353       | 16.82%  |
| C-Media Electronics                             | 20        | 0.95%   |
| Silicon Integrated Systems [SiS]                | 12        | 0.57%   |
| Barco Display Systems                           | 8         | 0.38%   |
| Logitech                                        | 6         | 0.29%   |
| Generalplus Technology                          | 6         | 0.29%   |
| VIA Technologies                                | 5         | 0.24%   |
| Tenx Technology                                 | 5         | 0.24%   |
| Kingston Technology                             | 5         | 0.24%   |
| JMTek                                           | 5         | 0.24%   |
| Creative Labs                                   | 5         | 0.24%   |
| Apple                                           | 5         | 0.24%   |
| Yamaha                                          | 3         | 0.14%   |
| Texas Instruments                               | 3         | 0.14%   |
| SteelSeries ApS                                 | 2         | 0.1%    |
| Realtek Semiconductor                           | 2         | 0.1%    |
| M-Audio                                         | 2         | 0.1%    |
| LG Electronics                                  | 2         | 0.1%    |
| GYROCOM C&C                                     | 2         | 0.1%    |
| GN Netcom                                       | 2         | 0.1%    |
| Focusrite-Novation                              | 2         | 0.1%    |
| DSEA A/S                                        | 2         | 0.1%    |
| Creative Technology                             | 2         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.05%   |
| ULi Electronics                                 | 1         | 0.05%   |
| Trust                                           | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.05%   |
| RODE Microphones                                | 1         | 0.05%   |
| Native Instruments                              | 1         | 0.05%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.05%   |
| Hewlett-Packard                                 | 1         | 0.05%   |
| Google                                          | 1         | 0.05%   |
| Evolution Electronics                           | 1         | 0.05%   |
| Earth Computer Technologies                     | 1         | 0.05%   |
| DigiTech                                        | 1         | 0.05%   |
| CMX Systems                                     | 1         | 0.05%   |
| Bose                                            | 1         | 0.05%   |
| Blue Microphones                                | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 155       | 6.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 135       | 5.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 114       | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 108       | 4.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 80        | 3.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 69        | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 68        | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 61        | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 57        | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 55        | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 49        | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 48        | 1.92%   |
| Intel 8 Series HD Audio Controller                                                                | 48        | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 48        | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 46        | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 46        | 1.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 44        | 1.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 42        | 1.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 41        | 1.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 41        | 1.64%   |
| Intel Broadwell-U Audio Controller                                                                | 41        | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 40        | 1.6%    |
| AMD FCH Azalia Controller                                                                         | 40        | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 39        | 1.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 34        | 1.36%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 30        | 1.2%    |
| Intel CM238 HD Audio Controller                                                                   | 29        | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 29        | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 27        | 1.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 27        | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 1%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 25        | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 24        | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 22        | 0.88%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 21        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 20        | 0.8%    |
| Nvidia High Definition Audio Controller                                                           | 18        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 245       | 25.55%  |
| SK hynix            | 153       | 15.95%  |
| Kingston            | 133       | 13.87%  |
| Unknown             | 98        | 10.22%  |
| Micron Technology   | 95        | 9.91%   |
| Crucial             | 48        | 5.01%   |
| Corsair             | 33        | 3.44%   |
| G.Skill             | 27        | 2.82%   |
| A-DATA Technology   | 25        | 2.61%   |
| Ramaxel Technology  | 16        | 1.67%   |
| Nanya Technology    | 16        | 1.67%   |
| Elpida              | 10        | 1.04%   |
| Goldkey             | 7         | 0.73%   |
| Unknown             | 7         | 0.73%   |
| Team                | 5         | 0.52%   |
| Transcend           | 4         | 0.42%   |
| Timetec             | 4         | 0.42%   |
| Unknown (ABCD)      | 3         | 0.31%   |
| Neo Forza           | 3         | 0.31%   |
| Apacer              | 3         | 0.31%   |
| Avant               | 2         | 0.21%   |
| AMD                 | 2         | 0.21%   |
| Unknown (F288)      | 1         | 0.1%    |
| Unknown (0x4509)    | 1         | 0.1%    |
| Unknown (0x29E)     | 1         | 0.1%    |
| Unknown (0B38)      | 1         | 0.1%    |
| Unknown (07FB)      | 1         | 0.1%    |
| Unifosa             | 1         | 0.1%    |
| pqi                 | 1         | 0.1%    |
| Patriot             | 1         | 0.1%    |
| Lexar Co Limited    | 1         | 0.1%    |
| Kllisre             | 1         | 0.1%    |
| Innodisk            | 1         | 0.1%    |
| Hikvision           | 1         | 0.1%    |
| Golden Empire       | 1         | 0.1%    |
| Gold Key            | 1         | 0.1%    |
| ff                  | 1         | 0.1%    |
| ChangXin Memory     | 1         | 0.1%    |
| ASint Technology    | 1         | 0.1%    |
| A-DA                | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 13        | 1.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 13        | 1.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 12        | 1.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 11        | 1.07%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 11        | 1.07%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 10        | 0.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 10        | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 9         | 0.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 8         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 8         | 0.78%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 7         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 7         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 7         | 0.68%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 7         | 0.68%   |
| Unknown                                                      | 7         | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 6         | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 6         | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 6         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 6         | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.58%   |
| Crucial RAM CT8G4SFS8266.M8FD 8192MB SODIMM DDR4 2667MT/s    | 6         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 5         | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 5         | 0.49%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 5         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 5         | 0.49%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 5         | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 5         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 0.49%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 5         | 0.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 5         | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 5         | 0.49%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 5         | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 5         | 0.49%   |
| G.Skill RAM F4-3000C16-8GVRB 8GB DIMM DDR4 3200MT/s          | 5         | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 4         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 4         | 0.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 4         | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 4         | 0.39%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 4         | 0.39%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s     | 4         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 421       | 51.59%  |
| DDR3    | 261       | 31.99%  |
| DDR2    | 27        | 3.31%   |
| LPDDR4  | 26        | 3.19%   |
| Unknown | 25        | 3.06%   |
| SDRAM   | 23        | 2.82%   |
| LPDDR3  | 17        | 2.08%   |
| DDR5    | 5         | 0.61%   |
| DDR     | 5         | 0.61%   |
| DRAM    | 3         | 0.37%   |
| LPDDR5  | 2         | 0.25%   |
| EEPROM  | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 575       | 71.34%  |
| DIMM         | 168       | 20.84%  |
| Row Of Chips | 59        | 7.32%   |
| Chip         | 2         | 0.25%   |
| Unknown      | 2         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 367       | 40.91%  |
| 4096    | 256       | 28.54%  |
| 2048    | 112       | 12.49%  |
| 16384   | 102       | 11.37%  |
| 1024    | 29        | 3.23%   |
| 32768   | 23        | 2.56%   |
| 512     | 4         | 0.45%   |
| 65536   | 1         | 0.11%   |
| 256     | 1         | 0.11%   |
| 1       | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 170       | 19.41%  |
| 3200    | 160       | 18.26%  |
| 2667    | 156       | 17.81%  |
| 2400    | 77        | 8.79%   |
| 2133    | 42        | 4.79%   |
| 1333    | 42        | 4.79%   |
| 1334    | 34        | 3.88%   |
| Unknown | 28        | 3.2%    |
| 667     | 20        | 2.28%   |
| 800     | 16        | 1.83%   |
| 3600    | 14        | 1.6%    |
| 1067    | 14        | 1.6%    |
| 4199    | 12        | 1.37%   |
| 1867    | 11        | 1.26%   |
| 3000    | 10        | 1.14%   |
| 4267    | 7         | 0.8%    |
| 4266    | 6         | 0.68%   |
| 2800    | 6         | 0.68%   |
| 4800    | 5         | 0.57%   |
| 3400    | 5         | 0.57%   |
| 1066    | 5         | 0.57%   |
| 400     | 4         | 0.46%   |
| 8400    | 3         | 0.34%   |
| 6400    | 2         | 0.23%   |
| 3866    | 2         | 0.23%   |
| 3733    | 2         | 0.23%   |
| 3466    | 2         | 0.23%   |
| 3266    | 2         | 0.23%   |
| 2933    | 2         | 0.23%   |
| 2048    | 2         | 0.23%   |
| 1639    | 2         | 0.23%   |
| 533     | 2         | 0.23%   |
| 50410   | 1         | 0.11%   |
| 3800    | 1         | 0.11%   |
| 3151    | 1         | 0.11%   |
| 3100    | 1         | 0.11%   |
| 2733    | 1         | 0.11%   |
| 2666    | 1         | 0.11%   |
| 1866    | 1         | 0.11%   |
| 1400    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 34.29%  |
| Canon               | 10        | 28.57%  |
| Seiko Epson         | 6         | 17.14%  |
| Zebra               | 3         | 8.57%   |
| Samsung Electronics | 2         | 5.71%   |
| QinHeng Electronics | 1         | 2.86%   |
| Brother Industries  | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Zebra TLP2844                        | 2         | 5.56%   |
| Seiko Epson L3110 Series             | 2         | 5.56%   |
| HP Officejet 4500 G510g-m            | 2         | 5.56%   |
| HP LaserJet P2055 series             | 2         | 5.56%   |
| Canon LBP6030w/6018w                 | 2         | 5.56%   |
| Canon E410 series                    | 2         | 5.56%   |
| Zebra Zebra GC420d Label Printer     | 1         | 2.78%   |
| Seiko Epson L405 Series              | 1         | 2.78%   |
| Seiko Epson L3150 Series             | 1         | 2.78%   |
| Seiko Epson L210 Series              | 1         | 2.78%   |
| Seiko Epson FX-2190IIN               | 1         | 2.78%   |
| Samsung ML-216x Series Laser Printer | 1         | 2.78%   |
| Samsung M2020 Series                 | 1         | 2.78%   |
| QinHeng CH340S                       | 1         | 2.78%   |
| HP LaserJet P1102                    | 1         | 2.78%   |
| HP LaserJet M101-M106                | 1         | 2.78%   |
| HP LaserJet 1020                     | 1         | 2.78%   |
| HP LaserJet 1010                     | 1         | 2.78%   |
| HP DeskJet F2100 Printer series      | 1         | 2.78%   |
| HP DeskJet 3830 series               | 1         | 2.78%   |
| HP DeskJet 2620 All-in-One Printer   | 1         | 2.78%   |
| HP DeskJet 2130 series               | 1         | 2.78%   |
| HP Deskjet 1050 J410                 | 1         | 2.78%   |
| Canon PIXMA MX340                    | 1         | 2.78%   |
| Canon PIXMA MG3000 series            | 1         | 2.78%   |
| Canon LBP6000                        | 1         | 2.78%   |
| Canon G3020 series                   | 1         | 2.78%   |
| Canon G3010 series                   | 1         | 2.78%   |
| Canon E460 series                    | 1         | 2.78%   |
| Brother DCP-1510                     | 1         | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 50%     |
| Canon          | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 50%     |
| Canon CanoScan LiDE 210            | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 269       | 24.21%  |
| IMC Networks                           | 132       | 11.88%  |
| Realtek Semiconductor                  | 104       | 9.36%   |
| Microdia                               | 72        | 6.48%   |
| Cheng Uei Precision Industry (Foxlink) | 60        | 5.4%    |
| Acer                                   | 60        | 5.4%    |
| Quanta                                 | 53        | 4.77%   |
| Bison Electronics                      | 43        | 3.87%   |
| Sunplus Innovation Technology          | 40        | 3.6%    |
| Syntek                                 | 37        | 3.33%   |
| Suyin                                  | 32        | 2.88%   |
| Apple                                  | 30        | 2.7%    |
| Alcor Micro                            | 19        | 1.71%   |
| Silicon Motion                         | 17        | 1.53%   |
| Logitech                               | 17        | 1.53%   |
| Lite-On Technology                     | 17        | 1.53%   |
| Z-Star Microelectronics                | 14        | 1.26%   |
| Ricoh                                  | 12        | 1.08%   |
| Luxvisions Innotech Limited            | 11        | 0.99%   |
| Samsung Electronics                    | 8         | 0.72%   |
| Importek                               | 8         | 0.72%   |
| ALi                                    | 7         | 0.63%   |
| Novatek Microelectronics               | 3         | 0.27%   |
| LG Electronics                         | 3         | 0.27%   |
| Genesys Logic                          | 3         | 0.27%   |
| Arkmicro Technologies                  | 3         | 0.27%   |
| SunplusIT                              | 2         | 0.18%   |
| Sunplus Technology                     | 2         | 0.18%   |
| Sonix Technology                       | 2         | 0.18%   |
| Primax Electronics                     | 2         | 0.18%   |
| Microsoft                              | 2         | 0.18%   |
| MacroSilicon                           | 2         | 0.18%   |
| Lenovo                                 | 2         | 0.18%   |
| Jieli Technology                       | 2         | 0.18%   |
| HYGD-220628-A                          | 2         | 0.18%   |
| Generalplus Technology                 | 2         | 0.18%   |
| GEMBIRD                                | 2         | 0.18%   |
| Foxconn / Hon Hai                      | 2         | 0.18%   |
| DigiTech                               | 2         | 0.18%   |
| Philips (or NXP)                       | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                             | 42        | 3.77%   |
| Microdia Integrated_Webcam_HD                                 | 33        | 2.96%   |
| Chicony Integrated Camera                                     | 33        | 2.96%   |
| IMC Networks Integrated Camera                                | 31        | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 27        | 2.42%   |
| Realtek Integrated_Webcam_HD                                  | 26        | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 23        | 2.06%   |
| Syntek Integrated Camera                                      | 21        | 1.88%   |
| Acer Integrated Camera                                        | 19        | 1.7%    |
| Chicony USB2.0 VGA UVC WebCam                                 | 16        | 1.43%   |
| Chicony USB2.0 HD UVC WebCam                                  | 15        | 1.35%   |
| Realtek USB2.0 VGA UVC WebCam                                 | 13        | 1.17%   |
| Chicony USB 2.0 Camera                                        | 12        | 1.08%   |
| Chicony USB2.0 Camera                                         | 11        | 0.99%   |
| Chicony TOSHIBA Web Camera - HD                               | 11        | 0.99%   |
| Chicony HP HD Camera                                          | 11        | 0.99%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                               | 11        | 0.99%   |
| IMC Networks HD Camera                                        | 10        | 0.9%    |
| Chicony Lenovo EasyCamera                                     | 10        | 0.9%    |
| Bison HD Webcam                                               | 10        | 0.9%    |
| Acer BisonCam, NB Pro                                         | 10        | 0.9%    |
| Quanta HD User Facing                                         | 9         | 0.81%   |
| Lite-On Integrated Camera                                     | 9         | 0.81%   |
| IMC Networks ov9734_azurewave_camera                          | 9         | 0.81%   |
| Chicony HP Webcam                                             | 9         | 0.81%   |
| Chicony EasyCamera                                            | 9         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera              | 9         | 0.81%   |
| Syntek EasyCamera                                             | 8         | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 8         | 0.72%   |
| Realtek USB Camera                                            | 8         | 0.72%   |
| Quanta ov9734_techfront_camera                                | 8         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD       | 8         | 0.72%   |
| Sunplus Integrated_Webcam_HD                                  | 7         | 0.63%   |
| Sunplus Asus Webcam                                           | 7         | 0.63%   |
| Quanta HP TrueVision HD Camera                                | 7         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 7         | 0.63%   |
| Bison SunplusIT Integrated Camera                             | 7         | 0.63%   |
| Apple FaceTime HD Camera (Built-in)                           | 7         | 0.63%   |
| Acer Lenovo EasyCamera                                        | 7         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam                                  | 6         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 58        | 35.15%  |
| Synaptics                  | 37        | 22.42%  |
| Validity Sensors           | 35        | 21.21%  |
| LighTuning Technology      | 14        | 8.48%   |
| Upek                       | 8         | 4.85%   |
| AuthenTec                  | 8         | 4.85%   |
| Elan Microelectronics      | 5         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 42        | 25.45%  |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 4.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 4.85%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 3.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 3.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 3.03%   |
| Synaptics  WBDI                                                            | 5         | 3.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.03%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.42%   |
| Synaptics WBDI                                                             | 4         | 2.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.42%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 2.42%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.82%   |
| Synaptics UWP WBDI                                                         | 3         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.82%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.82%   |
| AuthenTec AES1600                                                          | 3         | 1.82%   |
| Validity Sensors VFS491                                                    | 2         | 1.21%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.21%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.21%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.21%   |
| AuthenTec AES2810                                                          | 2         | 1.21%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.61%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.61%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.61%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 14        | 35%     |
| Alcor Micro           | 13        | 32.5%   |
| Advanced Card Systems | 6         | 15%     |
| Upek                  | 2         | 5%      |
| O2 Micro              | 2         | 5%      |
| Gemalto (was Gemplus) | 2         | 5%      |
| Lenovo                | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 32.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 15%     |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 12.5%   |
| Broadcom 58200                                                               | 3         | 7.5%    |
| Advanced Card Systems ACR39U                                                 | 3         | 7.5%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5%      |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 5%      |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1131      | 69.73%  |
| 1     | 392       | 24.17%  |
| 2     | 82        | 5.06%   |
| 3     | 11        | 0.68%   |
| 4     | 3         | 0.18%   |
| 6     | 2         | 0.12%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 171       | 29.13%  |
| Fingerprint reader       | 165       | 28.11%  |
| Net/wireless             | 55        | 9.37%   |
| Multimedia controller    | 35        | 5.96%   |
| Chipcard                 | 33        | 5.62%   |
| Camera                   | 30        | 5.11%   |
| Bluetooth                | 29        | 4.94%   |
| Communication controller | 24        | 4.09%   |
| Net/ethernet             | 11        | 1.87%   |
| Sound                    | 9         | 1.53%   |
| Storage                  | 8         | 1.36%   |
| Network                  | 5         | 0.85%   |
| Unassigned class         | 4         | 0.68%   |
| Flash memory             | 2         | 0.34%   |
| Card reader              | 2         | 0.34%   |
| Wireless                 | 1         | 0.17%   |
| Storage/raid             | 1         | 0.17%   |
| Storage/ide              | 1         | 0.17%   |
| Modem                    | 1         | 0.17%   |


Elementary 5.1.7 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Elementary 5.1.7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_5.1.7/Desktop/README.md) and [notebooks](/Dist/Elementary_5.1.7/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 317

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv5                | Notebook    | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [4b7e610e25](https://linux-hardware.org/?probe=4b7e610e25) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| Dell          | 0GM819                      | Desktop     | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| ASUSTek       | P5KPL-VM/S                  | Desktop     | [66223d6ef0](https://linux-hardware.org/?probe=66223d6ef0) | May 25, 2022 |
| ASUSTek       | P5KPL-VM/S                  | Desktop     | [d44e9d6290](https://linux-hardware.org/?probe=d44e9d6290) | May 25, 2022 |
| HP            | ZBook 15                    | Notebook    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d7223d4b03](https://linux-hardware.org/?probe=d7223d4b03) | May 05, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| Dell          | Latitude 3550               | Notebook    | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| Panasonic     | CF-31SBLJGDM                | Notebook    | [60a1068658](https://linux-hardware.org/?probe=60a1068658) | Apr 13, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| HP            | 18E7                        | Desktop     | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| Dell          | Latitude 3550               | Notebook    | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | Notebook    | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
| Dell          | 0HMX8D A01                  | Desktop     | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [e0c07cf9d2](https://linux-hardware.org/?probe=e0c07cf9d2) | Feb 20, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [85d07f0cc8](https://linux-hardware.org/?probe=85d07f0cc8) | Feb 03, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f3e2292b52](https://linux-hardware.org/?probe=f3e2292b52) | Feb 03, 2022 |
| Panasonic     | CF-31SBLJGDM                | Notebook    | [488b80a942](https://linux-hardware.org/?probe=488b80a942) | Feb 03, 2022 |
| HP            | Pavilion dv5                | Notebook    | [62a18fa26b](https://linux-hardware.org/?probe=62a18fa26b) | Jan 26, 2022 |
| Dell          | Latitude 5420               | Notebook    | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [d74dcddae6](https://linux-hardware.org/?probe=d74dcddae6) | Jan 13, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [afe25bb395](https://linux-hardware.org/?probe=afe25bb395) | Jan 10, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | Notebook    | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fa46d4f41a](https://linux-hardware.org/?probe=fa46d4f41a) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [22fb358e03](https://linux-hardware.org/?probe=22fb358e03) | Dec 28, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [82483b42e2](https://linux-hardware.org/?probe=82483b42e2) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [197a4e0280](https://linux-hardware.org/?probe=197a4e0280) | Dec 21, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| HP            | Pavilion dv7                | Notebook    | [073367afb1](https://linux-hardware.org/?probe=073367afb1) | Nov 25, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| HP            | Laptop 17-by3xxx            | Notebook    | [beba4da01c](https://linux-hardware.org/?probe=beba4da01c) | Nov 09, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| ASUSTek       | K75VJ                       | Notebook    | [9c0bccf601](https://linux-hardware.org/?probe=9c0bccf601) | Nov 01, 2021 |
| Dell          | 0KFKMF A00                  | All in one  | [81af87f00c](https://linux-hardware.org/?probe=81af87f00c) | Oct 29, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [73615204f8](https://linux-hardware.org/?probe=73615204f8) | Sep 23, 2021 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| Lenovo        | Flex 6-11IGM 81A7           | Convertible | [17e78af479](https://linux-hardware.org/?probe=17e78af479) | Sep 14, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [e872ba288e](https://linux-hardware.org/?probe=e872ba288e) | Sep 12, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [9460412d4d](https://linux-hardware.org/?probe=9460412d4d) | Sep 04, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [cf69bd4423](https://linux-hardware.org/?probe=cf69bd4423) | Aug 31, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [8c61841633](https://linux-hardware.org/?probe=8c61841633) | Aug 30, 2021 |
| HP            | Laptop 17-by3xxx            | Notebook    | [84aa134848](https://linux-hardware.org/?probe=84aa134848) | Aug 25, 2021 |
| HP            | Laptop 17-by3xxx            | Notebook    | [674068cb21](https://linux-hardware.org/?probe=674068cb21) | Aug 19, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Acer          | Aspire 3810TZ               | Notebook    | [6b7176e5ed](https://linux-hardware.org/?probe=6b7176e5ed) | Aug 10, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [caa41076f3](https://linux-hardware.org/?probe=caa41076f3) | Aug 07, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [53c721a204](https://linux-hardware.org/?probe=53c721a204) | Aug 01, 2021 |
| Acer          | Aspire XC-603G              | Desktop     | [8a37f28ecc](https://linux-hardware.org/?probe=8a37f28ecc) | Jul 31, 2021 |
| Lenovo        | ThinkPad P50 20ENA00PLM     | Notebook    | [3b6f4346e5](https://linux-hardware.org/?probe=3b6f4346e5) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | Notebook    | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [75ff3dac2c](https://linux-hardware.org/?probe=75ff3dac2c) | Jul 28, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4a7e9569e4](https://linux-hardware.org/?probe=4a7e9569e4) | Jul 28, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| Dell          | 0KFKMF A00                  | All in one  | [f09adc9f37](https://linux-hardware.org/?probe=f09adc9f37) | Jul 25, 2021 |
| Dell          | Vostro 3446                 | Notebook    | [566fe43065](https://linux-hardware.org/?probe=566fe43065) | Jul 25, 2021 |
| Dell          | Vostro 3446                 | Notebook    | [9a984d5856](https://linux-hardware.org/?probe=9a984d5856) | Jul 25, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [9951dfaa86](https://linux-hardware.org/?probe=9951dfaa86) | Jul 24, 2021 |
| Biostar       | H61MH                       | Desktop     | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | Desktop     | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| 3E            | Education PC by             | Tablet      | [4997e0ca93](https://linux-hardware.org/?probe=4997e0ca93) | Jul 14, 2021 |
| 3E            | Education PC by             | Tablet      | [9719e5e012](https://linux-hardware.org/?probe=9719e5e012) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [9e27318e84](https://linux-hardware.org/?probe=9e27318e84) | Jul 14, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [a01b8bbea0](https://linux-hardware.org/?probe=a01b8bbea0) | Jul 07, 2021 |
| Google        | Banjo                       | Notebook    | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| HP            | Pavilion 14                 | Notebook    | [01491528b1](https://linux-hardware.org/?probe=01491528b1) | Jun 28, 2021 |
| Acer          | Aspire E1-570G              | Notebook    | [e72de97e18](https://linux-hardware.org/?probe=e72de97e18) | Jun 25, 2021 |
| ASUSTek       | ZenBook UX481FA_UX481FA     | Notebook    | [675397a7db](https://linux-hardware.org/?probe=675397a7db) | Jun 19, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [82e660e88d](https://linux-hardware.org/?probe=82e660e88d) | Jun 12, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [e8589abc23](https://linux-hardware.org/?probe=e8589abc23) | Jun 10, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [b65c50aaf8](https://linux-hardware.org/?probe=b65c50aaf8) | Jun 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [6b941d232d](https://linux-hardware.org/?probe=6b941d232d) | Jun 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3f8470a641](https://linux-hardware.org/?probe=3f8470a641) | Jun 02, 2021 |
| Lenovo        | ThinkPad X240 20AMA0XK00    | Notebook    | [8b7ecca1b8](https://linux-hardware.org/?probe=8b7ecca1b8) | Jun 02, 2021 |
| HP            | Presario CQ56               | Notebook    | [70a720b401](https://linux-hardware.org/?probe=70a720b401) | May 31, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| HP            | Pavilion g7                 | Notebook    | [6607d7bfd4](https://linux-hardware.org/?probe=6607d7bfd4) | May 28, 2021 |
| HP            | Laptop 17-by3xxx            | Notebook    | [94e12db274](https://linux-hardware.org/?probe=94e12db274) | May 28, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [7bcdcd125f](https://linux-hardware.org/?probe=7bcdcd125f) | May 24, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [c812470c98](https://linux-hardware.org/?probe=c812470c98) | May 22, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [96c74bb052](https://linux-hardware.org/?probe=96c74bb052) | May 14, 2021 |
| Dell          | Latitude E6400              | Notebook    | [28c0f73a83](https://linux-hardware.org/?probe=28c0f73a83) | May 12, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [dd6a1734a8](https://linux-hardware.org/?probe=dd6a1734a8) | May 09, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | Notebook    | [dc9c7088dd](https://linux-hardware.org/?probe=dc9c7088dd) | May 08, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | Notebook    | [9cf4893825](https://linux-hardware.org/?probe=9cf4893825) | May 08, 2021 |
| Acer          | One S1003                   | Tablet      | [23e45b2b8e](https://linux-hardware.org/?probe=23e45b2b8e) | May 03, 2021 |
| Acer          | One S1003                   | Tablet      | [38a4af836c](https://linux-hardware.org/?probe=38a4af836c) | May 03, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [fdabc1d291](https://linux-hardware.org/?probe=fdabc1d291) | Apr 28, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [2e2cc93814](https://linux-hardware.org/?probe=2e2cc93814) | Apr 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b35c15fb6b](https://linux-hardware.org/?probe=b35c15fb6b) | Apr 25, 2021 |
| ASUSTek       | X205TAW                     | Notebook    | [91e8c10d9e](https://linux-hardware.org/?probe=91e8c10d9e) | Apr 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [1d52101f3a](https://linux-hardware.org/?probe=1d52101f3a) | Apr 23, 2021 |
| Positivo      | S14SL01                     | Notebook    | [f1cc01bb29](https://linux-hardware.org/?probe=f1cc01bb29) | Apr 22, 2021 |
| Lenovo        | ThinkPad T460 20FMS6C200    | Notebook    | [7f900f8923](https://linux-hardware.org/?probe=7f900f8923) | Apr 20, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [9065c52996](https://linux-hardware.org/?probe=9065c52996) | Apr 17, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [98d6e8f2d2](https://linux-hardware.org/?probe=98d6e8f2d2) | Apr 15, 2021 |
| Lenovo        | ThinkPad R61e/R61i 76508... | Notebook    | [e3b2bd3e3a](https://linux-hardware.org/?probe=e3b2bd3e3a) | Apr 14, 2021 |
| Dell          | Inspiron 5482               | Convertible | [c6692154a1](https://linux-hardware.org/?probe=c6692154a1) | Apr 14, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [09240a2a3f](https://linux-hardware.org/?probe=09240a2a3f) | Apr 13, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [542d0b7163](https://linux-hardware.org/?probe=542d0b7163) | Apr 13, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [9749184629](https://linux-hardware.org/?probe=9749184629) | Apr 12, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [7cd834c7b9](https://linux-hardware.org/?probe=7cd834c7b9) | Apr 11, 2021 |
| Positivo      | C14CR21                     | Notebook    | [b4ed03e23e](https://linux-hardware.org/?probe=b4ed03e23e) | Apr 11, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [304541ce36](https://linux-hardware.org/?probe=304541ce36) | Apr 08, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [90eb8e7cc2](https://linux-hardware.org/?probe=90eb8e7cc2) | Apr 08, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [47766de8d9](https://linux-hardware.org/?probe=47766de8d9) | Apr 07, 2021 |
| MSI           | H61M-P31                    | Desktop     | [867b109a0b](https://linux-hardware.org/?probe=867b109a0b) | Apr 07, 2021 |
| Lenovo        | ThinkPad W540 20BHS1MX00    | Notebook    | [47cc5eb719](https://linux-hardware.org/?probe=47cc5eb719) | Apr 07, 2021 |
| HP            | 843F                        | Desktop     | [d5b68ba3fb](https://linux-hardware.org/?probe=d5b68ba3fb) | Apr 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [e2bbdc0f8a](https://linux-hardware.org/?probe=e2bbdc0f8a) | Mar 26, 2021 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| Toshiba       | QOSMIO G55                  | Notebook    | [be88551910](https://linux-hardware.org/?probe=be88551910) | Mar 22, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [29ef42ccfc](https://linux-hardware.org/?probe=29ef42ccfc) | Mar 20, 2021 |
| Toshiba       | QOSMIO G55                  | Notebook    | [35fcfae27e](https://linux-hardware.org/?probe=35fcfae27e) | Mar 19, 2021 |
| HP            | 843F                        | Desktop     | [a4fc49c430](https://linux-hardware.org/?probe=a4fc49c430) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [0fadf2dbc1](https://linux-hardware.org/?probe=0fadf2dbc1) | Mar 08, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [9e67aa8a54](https://linux-hardware.org/?probe=9e67aa8a54) | Mar 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| HP            | Notebook                    | Notebook    | [201023370e](https://linux-hardware.org/?probe=201023370e) | Feb 28, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [686e15d925](https://linux-hardware.org/?probe=686e15d925) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | Notebook    | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Lenovo        | ThinkPad E14 20RBS6MD00     | Notebook    | [32fced07f8](https://linux-hardware.org/?probe=32fced07f8) | Feb 25, 2021 |
| Dell          | Vostro 14 5401              | Notebook    | [e6e3289d55](https://linux-hardware.org/?probe=e6e3289d55) | Feb 25, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| HP            | ProBook 5330m               | Notebook    | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Compaq        | Presario CQ-23              | Notebook    | [2266878950](https://linux-hardware.org/?probe=2266878950) | Feb 21, 2021 |
| Acer          | V5-131                      | Notebook    | [fb508c9cd9](https://linux-hardware.org/?probe=fb508c9cd9) | Feb 14, 2021 |
| Toshiba       | Satellite P750              | Notebook    | [65db006d0a](https://linux-hardware.org/?probe=65db006d0a) | Feb 12, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [268b9f895a](https://linux-hardware.org/?probe=268b9f895a) | Feb 10, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [6271486e7b](https://linux-hardware.org/?probe=6271486e7b) | Feb 10, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [bc4bed1cdf](https://linux-hardware.org/?probe=bc4bed1cdf) | Feb 10, 2021 |
| Compaq        | Presario CQ-23              | Notebook    | [0303913f3a](https://linux-hardware.org/?probe=0303913f3a) | Feb 10, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [a5a556b691](https://linux-hardware.org/?probe=a5a556b691) | Feb 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [878b85cbc6](https://linux-hardware.org/?probe=878b85cbc6) | Feb 06, 2021 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [f04da4053d](https://linux-hardware.org/?probe=f04da4053d) | Feb 05, 2021 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [c53cdbd363](https://linux-hardware.org/?probe=c53cdbd363) | Feb 05, 2021 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [9bccdfbc03](https://linux-hardware.org/?probe=9bccdfbc03) | Feb 05, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [8b201eef4f](https://linux-hardware.org/?probe=8b201eef4f) | Feb 05, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [69d8376e50](https://linux-hardware.org/?probe=69d8376e50) | Feb 03, 2021 |
| ASRock        | Z75 Pro3                    | Desktop     | [f2d919b5c5](https://linux-hardware.org/?probe=f2d919b5c5) | Feb 03, 2021 |
| Sony          | VPCF23JFX                   | Notebook    | [6fffecad4a](https://linux-hardware.org/?probe=6fffecad4a) | Feb 02, 2021 |
| Biostar       | Hi-Fi A70U3P                | Desktop     | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar       | Hi-Fi A70U3P                | Desktop     | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [2ee3bd8ca9](https://linux-hardware.org/?probe=2ee3bd8ca9) | Jan 30, 2021 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [4ce7ac1cce](https://linux-hardware.org/?probe=4ce7ac1cce) | Jan 30, 2021 |
| Acer          | AOD255E                     | Notebook    | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [c259d42e53](https://linux-hardware.org/?probe=c259d42e53) | Jan 16, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [d40272076d](https://linux-hardware.org/?probe=d40272076d) | Jan 13, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [d31c109973](https://linux-hardware.org/?probe=d31c109973) | Jan 13, 2021 |
| Dell          | G3 3579                     | Notebook    | [888385f26b](https://linux-hardware.org/?probe=888385f26b) | Jan 13, 2021 |
| Dell          | Latitude E6500              | Notebook    | [81ffedd992](https://linux-hardware.org/?probe=81ffedd992) | Jan 13, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [b4bd0c4eec](https://linux-hardware.org/?probe=b4bd0c4eec) | Jan 12, 2021 |
| EVGA          | 132-CK-NF79 2               | Desktop     | [44c54ae3df](https://linux-hardware.org/?probe=44c54ae3df) | Jan 09, 2021 |
| MSI           | P35 Platinum                | Desktop     | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [4a241f61c6](https://linux-hardware.org/?probe=4a241f61c6) | Jan 05, 2021 |
| HP            | Laptop 17-by3xxx            | Notebook    | [84272dcaa9](https://linux-hardware.org/?probe=84272dcaa9) | Jan 05, 2021 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [21c0963f18](https://linux-hardware.org/?probe=21c0963f18) | Jan 03, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [721dd0a694](https://linux-hardware.org/?probe=721dd0a694) | Jan 03, 2021 |
| Star Labs     | Lite                        | Notebook    | [02fa9d26a2](https://linux-hardware.org/?probe=02fa9d26a2) | Jan 03, 2021 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | Notebook    | [7f209f6d03](https://linux-hardware.org/?probe=7f209f6d03) | Dec 31, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [1830ce642b](https://linux-hardware.org/?probe=1830ce642b) | Dec 29, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [934454c9c1](https://linux-hardware.org/?probe=934454c9c1) | Dec 29, 2020 |
| ASUSTek       | M5A97                       | Desktop     | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| HP            | 18EA                        | Desktop     | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Lenovo        | ThinkPad T420 4236M37       | Notebook    | [da2b217109](https://linux-hardware.org/?probe=da2b217109) | Dec 27, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [8f63e2a0d9](https://linux-hardware.org/?probe=8f63e2a0d9) | Dec 25, 2020 |
| HP            | G42                         | Notebook    | [c2046377dc](https://linux-hardware.org/?probe=c2046377dc) | Dec 25, 2020 |
| Dell          | Latitude E6520              | Notebook    | [01048967fe](https://linux-hardware.org/?probe=01048967fe) | Dec 24, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [5e92b317ef](https://linux-hardware.org/?probe=5e92b317ef) | Dec 24, 2020 |
| Biostar       | TA785G3 HD                  | Desktop     | [ed91ded9e9](https://linux-hardware.org/?probe=ed91ded9e9) | Dec 23, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [861b40ea1d](https://linux-hardware.org/?probe=861b40ea1d) | Dec 21, 2020 |
| Dell          | 0GN723                      | Desktop     | [a952bf5fa6](https://linux-hardware.org/?probe=a952bf5fa6) | Dec 20, 2020 |
| Apple         | MacBook2,1                  | Notebook    | [1bae958a19](https://linux-hardware.org/?probe=1bae958a19) | Dec 17, 2020 |
| LG Electro... | R490-G.ARL5RE2              | Notebook    | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [ec54395d4b](https://linux-hardware.org/?probe=ec54395d4b) | Dec 15, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [344504a10b](https://linux-hardware.org/?probe=344504a10b) | Dec 15, 2020 |
| Chuwi         | LapBook Pro                 | Notebook    | [602060bbe9](https://linux-hardware.org/?probe=602060bbe9) | Dec 13, 2020 |
| HP            | Pavilion dv7                | Notebook    | [fee310f330](https://linux-hardware.org/?probe=fee310f330) | Dec 13, 2020 |
| Toshiba       | Satellite R630              | Notebook    | [816b966aa8](https://linux-hardware.org/?probe=816b966aa8) | Dec 11, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0e95ec9f75](https://linux-hardware.org/?probe=0e95ec9f75) | Dec 08, 2020 |
| Unknown       | 1.0                         | Notebook    | [05b0ad54c9](https://linux-hardware.org/?probe=05b0ad54c9) | Dec 07, 2020 |
| HP            | Pavilion dv7                | Notebook    | [332576610a](https://linux-hardware.org/?probe=332576610a) | Dec 06, 2020 |
| WeiBu         | rev1.0                      | All in one  | [ddf6e5a3f7](https://linux-hardware.org/?probe=ddf6e5a3f7) | Dec 05, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Acer          | Aspire E5-411               | Notebook    | [2513d28117](https://linux-hardware.org/?probe=2513d28117) | Dec 02, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [0ef0b89d48](https://linux-hardware.org/?probe=0ef0b89d48) | Dec 01, 2020 |
| HP            | 304Bh                       | Desktop     | [d30d065810](https://linux-hardware.org/?probe=d30d065810) | Nov 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [04def4b8c8](https://linux-hardware.org/?probe=04def4b8c8) | Nov 25, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [d7a6b8524d](https://linux-hardware.org/?probe=d7a6b8524d) | Nov 23, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [73a317dd32](https://linux-hardware.org/?probe=73a317dd32) | Nov 21, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [2a86994bf7](https://linux-hardware.org/?probe=2a86994bf7) | Nov 21, 2020 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [47c75561ac](https://linux-hardware.org/?probe=47c75561ac) | Nov 21, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [b0504dfd39](https://linux-hardware.org/?probe=b0504dfd39) | Nov 21, 2020 |
| ASUSTek       | U31SD                       | Notebook    | [0454faa58e](https://linux-hardware.org/?probe=0454faa58e) | Nov 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [10e9d31bdb](https://linux-hardware.org/?probe=10e9d31bdb) | Nov 20, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [d47493ecae](https://linux-hardware.org/?probe=d47493ecae) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [54fd3c5678](https://linux-hardware.org/?probe=54fd3c5678) | Nov 15, 2020 |
| HP            | Laptop 17-by3xxx            | Notebook    | [4b3fbfd552](https://linux-hardware.org/?probe=4b3fbfd552) | Nov 12, 2020 |
| Lenovo        | ThinkPad T480 20L50007RT    | Notebook    | [284c6ccc22](https://linux-hardware.org/?probe=284c6ccc22) | Nov 10, 2020 |
| Acer          | Aspire E5-475G              | Notebook    | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| Apple         | MacBookPro11,2              | Notebook    | [aaa025e278](https://linux-hardware.org/?probe=aaa025e278) | Nov 09, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [dec186ab5a](https://linux-hardware.org/?probe=dec186ab5a) | Nov 08, 2020 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b48bb4088](https://linux-hardware.org/?probe=3b48bb4088) | Nov 04, 2020 |
| Apple         | MacBookPro11,2              | Notebook    | [c9674438eb](https://linux-hardware.org/?probe=c9674438eb) | Nov 04, 2020 |
| Acer          | AOD255E                     | Notebook    | [b64297fa62](https://linux-hardware.org/?probe=b64297fa62) | Nov 04, 2020 |
| Acer          | AOD255E                     | Notebook    | [3ef6628882](https://linux-hardware.org/?probe=3ef6628882) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| eMachines     | EL1358G                     | Desktop     | [9aabea4465](https://linux-hardware.org/?probe=9aabea4465) | Oct 28, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [4b4e294b37](https://linux-hardware.org/?probe=4b4e294b37) | Oct 28, 2020 |
| Lenovo        | ThinkPad L480 20LSS0GL00    | Notebook    | [7401cec82c](https://linux-hardware.org/?probe=7401cec82c) | Oct 28, 2020 |
| Lenovo        | ThinkPad L480 20LSS0GL00    | Notebook    | [70d33d80bb](https://linux-hardware.org/?probe=70d33d80bb) | Oct 27, 2020 |
| Dell          | MXG061                      | Notebook    | [d3495d4c8b](https://linux-hardware.org/?probe=d3495d4c8b) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [565653d844](https://linux-hardware.org/?probe=565653d844) | Oct 21, 2020 |
| HP            | Laptop 17-by3xxx            | Notebook    | [2c0288dadd](https://linux-hardware.org/?probe=2c0288dadd) | Oct 20, 2020 |
| HP            | Laptop 17-by3xxx            | Notebook    | [72d9d5cf88](https://linux-hardware.org/?probe=72d9d5cf88) | Oct 20, 2020 |
| MSI           | P35 Platinum                | Desktop     | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [743c634d73](https://linux-hardware.org/?probe=743c634d73) | Oct 10, 2020 |
| HP            | 304Ah                       | Desktop     | [5143880fd9](https://linux-hardware.org/?probe=5143880fd9) | Oct 09, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [bdcba0b93e](https://linux-hardware.org/?probe=bdcba0b93e) | Oct 08, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [1779589a19](https://linux-hardware.org/?probe=1779589a19) | Oct 08, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ba00de031e](https://linux-hardware.org/?probe=ba00de031e) | Oct 05, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| Acer          | WMCP78M                     | Desktop     | [2510b2bc49](https://linux-hardware.org/?probe=2510b2bc49) | Oct 02, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| Intel         | DG41RQ AAE54511-204         | Desktop     | [651cef3c94](https://linux-hardware.org/?probe=651cef3c94) | Sep 29, 2020 |
| MSI           | FM2-A55M-E33                | Desktop     | [50d8cc3e2d](https://linux-hardware.org/?probe=50d8cc3e2d) | Sep 28, 2020 |
| Samsung       | 850XBD                      | Notebook    | [0f37b12bcf](https://linux-hardware.org/?probe=0f37b12bcf) | Sep 25, 2020 |
| Samsung       | 850XBD                      | Notebook    | [6d3aecebe1](https://linux-hardware.org/?probe=6d3aecebe1) | Sep 25, 2020 |
| Dell          | Latitude E5440              | Notebook    | [ce030d4ddf](https://linux-hardware.org/?probe=ce030d4ddf) | Sep 21, 2020 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [d8a5d97d41](https://linux-hardware.org/?probe=d8a5d97d41) | Sep 18, 2020 |
| Toshiba       | Satellite C55t-A            | Notebook    | [74cf1c0699](https://linux-hardware.org/?probe=74cf1c0699) | Sep 16, 2020 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [8eef95cd00](https://linux-hardware.org/?probe=8eef95cd00) | Sep 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [73576f6c41](https://linux-hardware.org/?probe=73576f6c41) | Sep 09, 2020 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [3b51467541](https://linux-hardware.org/?probe=3b51467541) | Sep 06, 2020 |
| HP            | ProBook 6460b               | Notebook    | [dd1da16f74](https://linux-hardware.org/?probe=dd1da16f74) | Sep 06, 2020 |
| Dell          | Inspiron 5565               | Notebook    | [61e0f4dfb2](https://linux-hardware.org/?probe=61e0f4dfb2) | Sep 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [e5e4260a64](https://linux-hardware.org/?probe=e5e4260a64) | Sep 04, 2020 |
| Lenovo        | ThinkPad T480 20L50018US    | Notebook    | [3e3f5cb909](https://linux-hardware.org/?probe=3e3f5cb909) | Sep 04, 2020 |
| Dell          | Latitude E5540              | Notebook    | [7f237410a4](https://linux-hardware.org/?probe=7f237410a4) | Sep 03, 2020 |
| ASUSTek       | X441BA                      | Notebook    | [e244d30598](https://linux-hardware.org/?probe=e244d30598) | Sep 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [51aa00a8f0](https://linux-hardware.org/?probe=51aa00a8f0) | Sep 03, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Acer          | Swift SF313-52              | Notebook    | [c03f9b4cc4](https://linux-hardware.org/?probe=c03f9b4cc4) | Aug 30, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [78ec970ee1](https://linux-hardware.org/?probe=78ec970ee1) | Aug 29, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| Dell          | Inspiron 3585               | Notebook    | [4c1c8da34d](https://linux-hardware.org/?probe=4c1c8da34d) | Aug 28, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [40f5f91c4e](https://linux-hardware.org/?probe=40f5f91c4e) | Aug 26, 2020 |
| Dell          | Latitude E6400              | Notebook    | [097649e115](https://linux-hardware.org/?probe=097649e115) | Aug 25, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [1e6aa82545](https://linux-hardware.org/?probe=1e6aa82545) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | Notebook    | [adcbc1af5f](https://linux-hardware.org/?probe=adcbc1af5f) | Aug 25, 2020 |
| Hampoo        | Cherry Trail CR             | Notebook    | [b2a99bdee8](https://linux-hardware.org/?probe=b2a99bdee8) | Aug 25, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [fbcb7cfb48](https://linux-hardware.org/?probe=fbcb7cfb48) | Aug 24, 2020 |
| HP            | 81B4                        | Desktop     | [6747078a67](https://linux-hardware.org/?probe=6747078a67) | Aug 24, 2020 |
| ASUSTek       | X501U                       | Notebook    | [11b77977b4](https://linux-hardware.org/?probe=11b77977b4) | Aug 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [4dc08dfc6f](https://linux-hardware.org/?probe=4dc08dfc6f) | Aug 22, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [caa355d2ed](https://linux-hardware.org/?probe=caa355d2ed) | Aug 21, 2020 |
| HP            | 250 G4                      | Notebook    | [24615bedce](https://linux-hardware.org/?probe=24615bedce) | Aug 19, 2020 |
| HP            | 81B4                        | Desktop     | [ff66e031e4](https://linux-hardware.org/?probe=ff66e031e4) | Aug 18, 2020 |
| HP            | 250 G4                      | Notebook    | [bdadaddd2d](https://linux-hardware.org/?probe=bdadaddd2d) | Aug 18, 2020 |
| Apple         | MacBook2,1                  | Notebook    | [86447b8ed9](https://linux-hardware.org/?probe=86447b8ed9) | Aug 17, 2020 |
| Apple         | MacBook2,1                  | Notebook    | [e623d56bad](https://linux-hardware.org/?probe=e623d56bad) | Aug 17, 2020 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [86ff4005e2](https://linux-hardware.org/?probe=86ff4005e2) | Aug 15, 2020 |
| Gigabyte      | AERO 15-WA                  | Notebook    | [1843d38083](https://linux-hardware.org/?probe=1843d38083) | Aug 10, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [8ae138eceb](https://linux-hardware.org/?probe=8ae138eceb) | Aug 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.4.0-42-generic      | 20        | 7.94%   |
| 5.4.0-65-generic      | 17        | 6.75%   |
| 5.4.0-58-generic      | 14        | 5.56%   |
| 5.4.0-48-generic      | 13        | 5.16%   |
| 5.4.0-52-generic      | 12        | 4.76%   |
| 5.4.0-80-generic      | 9         | 3.57%   |
| 5.4.0-56-generic      | 9         | 3.57%   |
| 5.4.0-54-generic      | 9         | 3.57%   |
| 5.4.0-73-generic      | 8         | 3.17%   |
| 5.4.0-72-generic      | 7         | 2.78%   |
| 5.4.0-47-generic      | 7         | 2.78%   |
| 5.4.0-70-generic      | 6         | 2.38%   |
| 5.4.0-66-generic      | 6         | 2.38%   |
| 5.4.0-81-generic      | 5         | 1.98%   |
| 5.4.0-60-generic      | 5         | 1.98%   |
| 5.4.0-90-generic      | 4         | 1.59%   |
| 5.4.0-77-generic      | 4         | 1.59%   |
| 5.4.0-74-generic      | 4         | 1.59%   |
| 5.4.0-67-generic      | 4         | 1.59%   |
| 5.4.0-53-generic      | 4         | 1.59%   |
| 4.15.0-128-generic    | 4         | 1.59%   |
| 4.15.0-112-generic    | 4         | 1.59%   |
| 5.4.0-71-generic      | 3         | 1.19%   |
| 5.4.0-64-generic      | 3         | 1.19%   |
| 5.4.0-45-generic      | 3         | 1.19%   |
| 5.4.0-96-generic      | 2         | 0.79%   |
| 5.4.0-92-generic      | 2         | 0.79%   |
| 5.4.0-91-generic      | 2         | 0.79%   |
| 5.4.0-62-generic      | 2         | 0.79%   |
| 5.4.0-59-generic      | 2         | 0.79%   |
| 5.4.0-51-generic      | 2         | 0.79%   |
| 5.4.0-124-generic     | 2         | 0.79%   |
| 5.4.0-120-generic     | 2         | 0.79%   |
| 5.4.0-109-generic     | 2         | 0.79%   |
| 5.4.0-107-generic     | 2         | 0.79%   |
| 5.4.0-100-generic     | 2         | 0.79%   |
| 5.3.0-62-generic      | 2         | 0.79%   |
| 5.10.0-051000-generic | 2         | 0.79%   |
| 4.15.0-162-generic    | 2         | 0.79%   |
| 4.15.0-161-generic    | 2         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 189       | 82.17%  |
| 4.15.0  | 20        | 8.7%    |
| 5.3.0   | 4         | 1.74%   |
| 5.10.0  | 3         | 1.3%    |
| 5.8.0   | 2         | 0.87%   |
| 5.9.1   | 1         | 0.43%   |
| 5.8.5   | 1         | 0.43%   |
| 5.8.13  | 1         | 0.43%   |
| 5.6.19  | 1         | 0.43%   |
| 5.4.78  | 1         | 0.43%   |
| 5.17.0  | 1         | 0.43%   |
| 5.15.5  | 1         | 0.43%   |
| 5.15.12 | 1         | 0.43%   |
| 5.14.9  | 1         | 0.43%   |
| 5.14.0  | 1         | 0.43%   |
| 5.10.4  | 1         | 0.43%   |
| 4.18.0  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 190       | 82.61%  |
| 4.15    | 20        | 8.7%    |
| 5.8     | 4         | 1.74%   |
| 5.3     | 4         | 1.74%   |
| 5.10    | 4         | 1.74%   |
| 5.15    | 2         | 0.87%   |
| 5.14    | 2         | 0.87%   |
| 5.9     | 1         | 0.43%   |
| 5.6     | 1         | 0.43%   |
| 5.17    | 1         | 0.43%   |
| 4.18    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 227       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 198       | 86.46%  |
| Unknown    | 26        | 11.35%  |
| X-Cinnamon | 2         | 0.87%   |
| Unity      | 1         | 0.44%   |
| GNOME      | 1         | 0.44%   |
| Budgie     | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 226       | 99.56%  |
| Unknown | 1         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 173       | 75.22%  |
| TDM     | 33        | 14.35%  |
| LightDM | 22        | 9.57%   |
| SDDM    | 1         | 0.43%   |
| GDM     | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 94        | 41.23%  |
| en_GB   | 17        | 7.46%   |
| pt_BR   | 10        | 4.39%   |
| es_ES   | 10        | 4.39%   |
| de_DE   | 9         | 3.95%   |
| ru_RU   | 8         | 3.51%   |
| pl_PL   | 8         | 3.51%   |
| en_IN   | 7         | 3.07%   |
| en_CA   | 7         | 3.07%   |
| en_AU   | 7         | 3.07%   |
| fr_FR   | 5         | 2.19%   |
| es_MX   | 5         | 2.19%   |
| it_IT   | 3         | 1.32%   |
| hu_HU   | 3         | 1.32%   |
| es_EC   | 3         | 1.32%   |
| en_ZA   | 3         | 1.32%   |
| hr_HR   | 2         | 0.88%   |
| en_PH   | 2         | 0.88%   |
| el_GR   | 2         | 0.88%   |
| de_AT   | 2         | 0.88%   |
| Unknown | 2         | 0.88%   |
| zh_TW   | 1         | 0.44%   |
| uk_UA   | 1         | 0.44%   |
| tr_TR   | 1         | 0.44%   |
| sv_SE   | 1         | 0.44%   |
| ru_UA   | 1         | 0.44%   |
| gl_ES   | 1         | 0.44%   |
| fr_CA   | 1         | 0.44%   |
| fr_BE   | 1         | 0.44%   |
| es_UY   | 1         | 0.44%   |
| es_US   | 1         | 0.44%   |
| es_SV   | 1         | 0.44%   |
| es_PE   | 1         | 0.44%   |
| es_PA   | 1         | 0.44%   |
| es_AR   | 1         | 0.44%   |
| en_IE   | 1         | 0.44%   |
| en_HK   | 1         | 0.44%   |
| de_IT   | 1         | 0.44%   |
| cs_CZ   | 1         | 0.44%   |
| ca_ES   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 120       | 52.63%  |
| EFI  | 108       | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 215       | 94.3%   |
| Btrfs   | 7         | 3.07%   |
| Overlay | 4         | 1.75%   |
| Xfs     | 1         | 0.44%   |
| Ext3    | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 185       | 81.14%  |
| GPT     | 31        | 13.6%   |
| MBR     | 12        | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 94.71%  |
| Yes       | 12        | 5.29%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 178       | 78.07%  |
| Yes       | 50        | 21.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 35        | 15.42%  |
| ASUSTek Computer    | 33        | 14.54%  |
| Lenovo              | 31        | 13.66%  |
| Dell                | 30        | 13.22%  |
| Acer                | 19        | 8.37%   |
| Apple               | 16        | 7.05%   |
| Gigabyte Technology | 15        | 6.61%   |
| Toshiba             | 8         | 3.52%   |
| MSI                 | 7         | 3.08%   |
| Samsung Electronics | 4         | 1.76%   |
| ASRock              | 4         | 1.76%   |
| Intel               | 3         | 1.32%   |
| Biostar             | 3         | 1.32%   |
| WeiBu               | 1         | 0.44%   |
| Star Labs           | 1         | 0.44%   |
| Sony                | 1         | 0.44%   |
| Positivo            | 1         | 0.44%   |
| Panasonic           | 1         | 0.44%   |
| LG Electronics      | 1         | 0.44%   |
| HUAWEI              | 1         | 0.44%   |
| Hampoo              | 1         | 0.44%   |
| Google              | 1         | 0.44%   |
| Fujitsu Siemens     | 1         | 0.44%   |
| Fujitsu             | 1         | 0.44%   |
| Foxconn             | 1         | 0.44%   |
| EVGA                | 1         | 0.44%   |
| eMachines           | 1         | 0.44%   |
| Compaq              | 1         | 0.44%   |
| Clevo               | 1         | 0.44%   |
| Chuwi               | 1         | 0.44%   |
| 3E                  | 1         | 0.44%   |
| Unknown             | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Apple MacBook2,1                               | 3         | 1.32%   |
| HP Pavilion dv7                                | 2         | 0.88%   |
| HP Laptop 17-by3xxx                            | 2         | 0.88%   |
| Dell Latitude E6400                            | 2         | 0.88%   |
| ASUS P8H61-M LX3 R2.0                          | 2         | 0.88%   |
| ASUS All Series                                | 2         | 0.88%   |
| Apple MacBookPro8,1                            | 2         | 0.88%   |
| Apple MacBook7,1                               | 2         | 0.88%   |
| Acer Aspire R3-131T                            | 2         | 0.88%   |
| Acer Aspire F5-573G                            | 2         | 0.88%   |
| Acer AOD255E                                   | 2         | 0.88%   |
| WeiBu Unity F24B                               | 1         | 0.44%   |
| Toshiba Satellite R630                         | 1         | 0.44%   |
| Toshiba Satellite P750                         | 1         | 0.44%   |
| Toshiba Satellite L855                         | 1         | 0.44%   |
| Toshiba Satellite L500                         | 1         | 0.44%   |
| Toshiba Satellite C870-1H2                     | 1         | 0.44%   |
| Toshiba Satellite C850D-119                    | 1         | 0.44%   |
| Toshiba Satellite C55t-A                       | 1         | 0.44%   |
| Toshiba QOSMIO G55                             | 1         | 0.44%   |
| Star Labs Lite                                 | 1         | 0.44%   |
| Sony VPCF23JFX                                 | 1         | 0.44%   |
| Samsung 850XBD                                 | 1         | 0.44%   |
| Samsung 530U3C/530U4C/532U3C                   | 1         | 0.44%   |
| Samsung 350V5C/351V5C/3540VC/3440VC            | 1         | 0.44%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 1         | 0.44%   |
| Positivo S14SL01                               | 1         | 0.44%   |
| Panasonic CF-31SBLJGDM                         | 1         | 0.44%   |
| MSI P35 Platinum(MS-7345)                      | 1         | 0.44%   |
| MSI MS-7C94                                    | 1         | 0.44%   |
| MSI MS-7C02                                    | 1         | 0.44%   |
| MSI MS-7A38                                    | 1         | 0.44%   |
| MSI MS-7788                                    | 1         | 0.44%   |
| MSI MS-7721                                    | 1         | 0.44%   |
| MSI GE60 2PE                                   | 1         | 0.44%   |
| LG R490-G.ARL5RE2                              | 1         | 0.44%   |
| Lenovo Yoga 710-14IKB 80V4                     | 1         | 0.44%   |
| Lenovo V15-IIL 82C5                            | 1         | 0.44%   |
| Lenovo V15-ADA 82C7                            | 1         | 0.44%   |
| Lenovo ThinkPad X240 20AMS0XP0S                | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 7.49%   |
| Acer Aspire            | 12        | 5.29%   |
| Dell Latitude          | 9         | 3.96%   |
| HP Pavilion            | 8         | 3.52%   |
| Dell Inspiron          | 8         | 3.52%   |
| Toshiba Satellite      | 7         | 3.08%   |
| Lenovo IdeaPad         | 5         | 2.2%    |
| HP ProBook             | 5         | 2.2%    |
| ASUS PRIME             | 5         | 2.2%    |
| HP EliteBook           | 4         | 1.76%   |
| Dell Vostro            | 4         | 1.76%   |
| HP 250                 | 3         | 1.32%   |
| Dell XPS               | 3         | 1.32%   |
| Dell OptiPlex          | 3         | 1.32%   |
| Apple MacBook2         | 3         | 1.32%   |
| Acer Swift             | 3         | 1.32%   |
| Lenovo ThinkCentre     | 2         | 0.88%   |
| HP Laptop              | 2         | 0.88%   |
| HP ENVY                | 2         | 0.88%   |
| HP Compaq              | 2         | 0.88%   |
| ASUS ZenBook           | 2         | 0.88%   |
| ASUS VivoBook          | 2         | 0.88%   |
| ASUS TUF               | 2         | 0.88%   |
| ASUS ROG               | 2         | 0.88%   |
| ASUS P8H61-M           | 2         | 0.88%   |
| ASUS All               | 2         | 0.88%   |
| Apple MacBookPro8      | 2         | 0.88%   |
| Apple MacBook7         | 2         | 0.88%   |
| Acer AOD255E           | 2         | 0.88%   |
| WeiBu Unity            | 1         | 0.44%   |
| Toshiba QOSMIO         | 1         | 0.44%   |
| Star Labs Lite         | 1         | 0.44%   |
| Sony VPCF23JFX         | 1         | 0.44%   |
| Samsung 850XBD         | 1         | 0.44%   |
| Samsung 530U3C         | 1         | 0.44%   |
| Samsung 350V5C         | 1         | 0.44%   |
| Samsung 300E5EV        | 1         | 0.44%   |
| Positivo S14SL01       | 1         | 0.44%   |
| Panasonic CF-31SBLJGDM | 1         | 0.44%   |
| MSI P35                | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 27        | 11.89%  |
| 2019 | 25        | 11.01%  |
| 2018 | 21        | 9.25%   |
| 2012 | 21        | 9.25%   |
| 2011 | 20        | 8.81%   |
| 2020 | 19        | 8.37%   |
| 2016 | 17        | 7.49%   |
| 2008 | 14        | 6.17%   |
| 2010 | 12        | 5.29%   |
| 2015 | 11        | 4.85%   |
| 2014 | 11        | 4.85%   |
| 2009 | 11        | 4.85%   |
| 2017 | 10        | 4.41%   |
| 2007 | 6         | 2.64%   |
| 2021 | 1         | 0.44%   |
| 2006 | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 146       | 64.32%  |
| Desktop     | 67        | 29.52%  |
| Convertible | 6         | 2.64%   |
| All in one  | 4         | 1.76%   |
| Tablet      | 2         | 0.88%   |
| Mini pc     | 2         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 223       | 98.24%  |
| Enabled  | 4         | 1.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 226       | 99.56%  |
| Yes  | 1         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 56        | 24.67%  |
| 8.01-16.0   | 54        | 23.79%  |
| 3.01-4.0    | 45        | 19.82%  |
| 16.01-24.0  | 37        | 16.3%   |
| 1.01-2.0    | 14        | 6.17%   |
| 32.01-64.0  | 11        | 4.85%   |
| 2.01-3.0    | 6         | 2.64%   |
| 0.51-1.0    | 2         | 0.88%   |
| 24.01-32.0  | 1         | 0.44%   |
| 64.01-256.0 | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 93        | 38.59%  |
| 2.01-3.0  | 63        | 26.14%  |
| 3.01-4.0  | 40        | 16.6%   |
| 4.01-8.0  | 33        | 13.69%  |
| 0.51-1.0  | 7         | 2.9%    |
| 8.01-16.0 | 5         | 2.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 141       | 61.57%  |
| 2      | 66        | 28.82%  |
| 3      | 7         | 3.06%   |
| 5      | 4         | 1.75%   |
| 4      | 4         | 1.75%   |
| 0      | 3         | 1.31%   |
| 7      | 2         | 0.87%   |
| 6      | 2         | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 60.43%  |
| Yes       | 91        | 39.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 84.58%  |
| No        | 35        | 15.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 84.21%  |
| No        | 36        | 15.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 65.79%  |
| No        | 78        | 34.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 27        | 11.89%  |
| UK           | 15        | 6.61%   |
| Brazil       | 15        | 6.61%   |
| Germany      | 14        | 6.17%   |
| Spain        | 12        | 5.29%   |
| Mexico       | 11        | 4.85%   |
| Poland       | 10        | 4.41%   |
| India        | 10        | 4.41%   |
| Canada       | 9         | 3.96%   |
| Russia       | 8         | 3.52%   |
| Indonesia    | 6         | 2.64%   |
| France       | 6         | 2.64%   |
| Australia    | 6         | 2.64%   |
| Ukraine      | 5         | 2.2%    |
| Italy        | 5         | 2.2%    |
| Turkey       | 4         | 1.76%   |
| Netherlands  | 4         | 1.76%   |
| Malaysia     | 4         | 1.76%   |
| Peru         | 3         | 1.32%   |
| Hungary      | 3         | 1.32%   |
| Hong Kong    | 3         | 1.32%   |
| Greece       | 3         | 1.32%   |
| Ecuador      | 3         | 1.32%   |
| Sweden       | 2         | 0.88%   |
| South Africa | 2         | 0.88%   |
| Philippines  | 2         | 0.88%   |
| Kenya        | 2         | 0.88%   |
| Ireland      | 2         | 0.88%   |
| Croatia      | 2         | 0.88%   |
| Austria      | 2         | 0.88%   |
| Argentina    | 2         | 0.88%   |
| Venezuela    | 1         | 0.44%   |
| Uruguay      | 1         | 0.44%   |
| UAE          | 1         | 0.44%   |
| Thailand     | 1         | 0.44%   |
| Tajikistan   | 1         | 0.44%   |
| Slovakia     | 1         | 0.44%   |
| Sint Maarten | 1         | 0.44%   |
| Saudi Arabia | 1         | 0.44%   |
| Romania      | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Warsaw               | 4         | 1.72%   |
| Fortaleza            | 4         | 1.72%   |
| Montreal             | 3         | 1.29%   |
| Hamburg              | 3         | 1.29%   |
| Berlin               | 3         | 1.29%   |
| Valencia             | 2         | 0.86%   |
| Tijuana              | 2         | 0.86%   |
| Rio de Janeiro       | 2         | 0.86%   |
| Quito                | 2         | 0.86%   |
| Perth                | 2         | 0.86%   |
| Novosibirsk          | 2         | 0.86%   |
| Nairobi              | 2         | 0.86%   |
| Milan                | 2         | 0.86%   |
| Mexico City          | 2         | 0.86%   |
| Melbourne            | 2         | 0.86%   |
| Lima                 | 2         | 0.86%   |
| Jaipur               | 2         | 0.86%   |
| Gilbert              | 2         | 0.86%   |
| Eskişehir           | 2         | 0.86%   |
| Córdoba             | 2         | 0.86%   |
| Central              | 2         | 0.86%   |
| Cape Town            | 2         | 0.86%   |
| Ames                 | 2         | 0.86%   |
| Zaragoza             | 1         | 0.43%   |
| Zagreb               | 1         | 0.43%   |
| York                 | 1         | 0.43%   |
| Yogyakarta           | 1         | 0.43%   |
| Wroclaw              | 1         | 0.43%   |
| Winhoring            | 1         | 0.43%   |
| Wellington           | 1         | 0.43%   |
| Villahermosa         | 1         | 0.43%   |
| Vigo                 | 1         | 0.43%   |
| Vienna               | 1         | 0.43%   |
| Vernon               | 1         | 0.43%   |
| Tseung Kwan O        | 1         | 0.43%   |
| Torun                | 1         | 0.43%   |
| Toronto              | 1         | 0.43%   |
| Tirupur              | 1         | 0.43%   |
| Theodore             | 1         | 0.43%   |
| Talavera de la Reina | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 56     | 13.87%  |
| WDC                 | 34        | 45     | 10.97%  |
| Samsung Electronics | 34        | 47     | 10.97%  |
| Toshiba             | 31        | 47     | 10%     |
| SanDisk             | 27        | 28     | 8.71%   |
| Kingston            | 26        | 36     | 8.39%   |
| Unknown             | 19        | 23     | 6.13%   |
| Crucial             | 19        | 23     | 6.13%   |
| Hitachi             | 13        | 14     | 4.19%   |
| Intel               | 10        | 12     | 3.23%   |
| HGST                | 10        | 12     | 3.23%   |
| Apple               | 4         | 4      | 1.29%   |
| A-DATA Technology   | 4         | 5      | 1.29%   |
| SK hynix            | 3         | 3      | 0.97%   |
| KIOXIA              | 3         | 8      | 0.97%   |
| Fujitsu             | 3         | 3      | 0.97%   |
| PNY                 | 2         | 2      | 0.65%   |
| Patriot             | 2         | 2      | 0.65%   |
| Micron Technology   | 2         | 3      | 0.65%   |
| WDC WDS             | 1         | 1      | 0.32%   |
| V-GeN               | 1         | 1      | 0.32%   |
| Transcend           | 1         | 1      | 0.32%   |
| TO Exter            | 1         | 1      | 0.32%   |
| Star                | 1         | 1      | 0.32%   |
| SPCC                | 1         | 1      | 0.32%   |
| Phison              | 1         | 1      | 0.32%   |
| OWC                 | 1         | 1      | 0.32%   |
| OCZ                 | 1         | 2      | 0.32%   |
| NGFF                | 1         | 1      | 0.32%   |
| LITEON              | 1         | 1      | 0.32%   |
| KingSpec            | 1         | 1      | 0.32%   |
| KingFast            | 1         | 1      | 0.32%   |
| JMicron Technology  | 1         | 1      | 0.32%   |
| Hewlett-Packard     | 1         | 1      | 0.32%   |
| GOODRAM             | 1         | 2      | 0.32%   |
| Gigabyte Technology | 1         | 1      | 0.32%   |
| GeIL                | 1         | 1      | 0.32%   |
| Emtec               | 1         | 1      | 0.32%   |
| China               | 1         | 1      | 0.32%   |
| ADATA Technology    | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 7         | 2.08%   |
| Unknown MMC Card  64GB             | 6         | 1.79%   |
| Toshiba MQ04ABF100 1TB             | 6         | 1.79%   |
| Samsung SSD 850 EVO 250GB          | 5         | 1.49%   |
| Samsung NVMe SSD Drive 512GB       | 5         | 1.49%   |
| Unknown MMC Card  32GB             | 4         | 1.19%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 1.19%   |
| SanDisk NVMe SSD Drive 256GB       | 4         | 1.19%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 1.19%   |
| Kingston SA400S37120G 120GB SSD    | 4         | 1.19%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 3         | 0.89%   |
| Toshiba NVMe SSD Drive 256GB       | 3         | 0.89%   |
| Toshiba DT01ACA100 1TB             | 3         | 0.89%   |
| SanDisk SSD PLUS 480GB             | 3         | 0.89%   |
| SanDisk NVMe SSD Drive 512GB       | 3         | 0.89%   |
| Samsung SSD 860 QVO 1TB            | 3         | 0.89%   |
| HGST HTS545050A7E680 500GB         | 3         | 0.89%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 0.89%   |
| Crucial CT120BX500SSD1 120GB       | 3         | 0.89%   |
| Crucial CT120BX300SSD1 120GB       | 3         | 0.89%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 0.6%    |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.6%    |
| Unknown MMC Card  16GB             | 2         | 0.6%    |
| Toshiba THNSNJ128GCSU 128GB SSD    | 2         | 0.6%    |
| Toshiba MQ01ABF050 500GB           | 2         | 0.6%    |
| Toshiba MQ01ABD100 1TB             | 2         | 0.6%    |
| Seagate ST500LM000-1EJ162 500GB    | 2         | 0.6%    |
| Seagate ST3500418AS 500GB          | 2         | 0.6%    |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB     | 2         | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB     | 2         | 0.6%    |
| Seagate Expansion 2TB              | 2         | 0.6%    |
| SanDisk SSD PLUS 240GB             | 2         | 0.6%    |
| Samsung SSD 970 EVO 500GB          | 2         | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 2         | 0.6%    |
| Samsung SSD 860 EVO 250GB          | 2         | 0.6%    |
| Samsung SSD 850 EVO 500GB          | 2         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 54     | 33.87%  |
| Toshiba             | 26        | 40     | 20.97%  |
| WDC                 | 22        | 33     | 17.74%  |
| Hitachi             | 13        | 14     | 10.48%  |
| HGST                | 10        | 12     | 8.06%   |
| Samsung Electronics | 5         | 7      | 4.03%   |
| Fujitsu             | 3         | 3      | 2.42%   |
| Apple               | 2         | 2      | 1.61%   |
| Unknown             | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 28     | 17.56%  |
| Kingston            | 23        | 27     | 17.56%  |
| SanDisk             | 19        | 20     | 14.5%   |
| Crucial             | 19        | 23     | 14.5%   |
| WDC                 | 10        | 10     | 7.63%   |
| Intel               | 6         | 6      | 4.58%   |
| A-DATA Technology   | 4         | 5      | 3.05%   |
| Toshiba             | 2         | 2      | 1.53%   |
| PNY                 | 2         | 2      | 1.53%   |
| Patriot             | 2         | 2      | 1.53%   |
| Apple               | 2         | 2      | 1.53%   |
| WDC WDS             | 1         | 1      | 0.76%   |
| V-GeN               | 1         | 1      | 0.76%   |
| Transcend           | 1         | 1      | 0.76%   |
| TO Exter            | 1         | 1      | 0.76%   |
| Star                | 1         | 1      | 0.76%   |
| SPCC                | 1         | 1      | 0.76%   |
| SK hynix            | 1         | 1      | 0.76%   |
| OWC                 | 1         | 1      | 0.76%   |
| OCZ                 | 1         | 2      | 0.76%   |
| NGFF                | 1         | 1      | 0.76%   |
| Micron Technology   | 1         | 2      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| Hewlett-Packard     | 1         | 1      | 0.76%   |
| GOODRAM             | 1         | 2      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| GeIL                | 1         | 1      | 0.76%   |
| Emtec               | 1         | 1      | 0.76%   |
| China               | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 111       | 149    | 39.36%  |
| HDD     | 109       | 166    | 38.65%  |
| NVMe    | 43        | 58     | 15.25%  |
| MMC     | 17        | 21     | 6.03%   |
| Unknown | 2         | 2      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 186       | 306    | 73.23%  |
| NVMe | 42        | 57     | 16.54%  |
| MMC  | 17        | 21     | 6.69%   |
| SAS  | 9         | 12     | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 149       | 211    | 66.52%  |
| 0.51-1.0   | 59        | 77     | 26.34%  |
| 1.01-2.0   | 11        | 18     | 4.91%   |
| 4.01-10.0  | 3         | 3      | 1.34%   |
| 2.01-3.0   | 2         | 6      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 78        | 33.62%  |
| 251-500        | 65        | 28.02%  |
| 501-1000       | 27        | 11.64%  |
| 51-100         | 18        | 7.76%   |
| 21-50          | 15        | 6.47%   |
| 1001-2000      | 11        | 4.74%   |
| More than 3000 | 7         | 3.02%   |
| 2001-3000      | 5         | 2.16%   |
| 1-20           | 5         | 2.16%   |
| Unknown        | 1         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 76        | 31.8%   |
| 21-50          | 59        | 24.69%  |
| 101-250        | 34        | 14.23%  |
| 51-100         | 34        | 14.23%  |
| 251-500        | 13        | 5.44%   |
| 501-1000       | 11        | 4.6%    |
| 1001-2000      | 5         | 2.09%   |
| More than 3000 | 3         | 1.26%   |
| 2001-3000      | 3         | 1.26%   |
| Unknown        | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 9.09%   |
| WDC WD5000AAKX-221CA1 500GB         | 1         | 1      | 9.09%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 9.09%   |
| Seagate ST3320613AS 320GB           | 1         | 1      | 9.09%   |
| Seagate ST2000DM006-2DM164 2TB      | 1         | 1      | 9.09%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 9.09%   |
| Samsung Electronics HD204UI 2TB     | 1         | 1      | 9.09%   |
| Kingston SA400S37120G 120GB SSD     | 1         | 1      | 9.09%   |
| HGST HUS724030ALA640 3TB            | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 9.09%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 27.27%  |
| HGST                | 3         | 3      | 27.27%  |
| WDC                 | 2         | 2      | 18.18%  |
| SanDisk             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| HGST                | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 81.82%  |
| SSD  | 2         | 2      | 18.18%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 186       | 320    | 78.48%  |
| Works    | 40        | 65     | 16.88%  |
| Malfunc  | 11        | 11     | 4.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 165       | 64.2%   |
| AMD                          | 33        | 12.84%  |
| Samsung Electronics          | 13        | 5.06%   |
| SanDisk                      | 10        | 3.89%   |
| Nvidia                       | 8         | 3.11%   |
| Toshiba America Info Systems | 5         | 1.95%   |
| Kingston Technology Company  | 5         | 1.95%   |
| KIOXIA                       | 3         | 1.17%   |
| JMicron Technology           | 3         | 1.17%   |
| ASMedia Technology           | 3         | 1.17%   |
| SK hynix                     | 2         | 0.78%   |
| ADATA Technology             | 2         | 0.78%   |
| Silicon Image                | 1         | 0.39%   |
| Seagate Technology           | 1         | 0.39%   |
| Phison Electronics           | 1         | 0.39%   |
| Micron Technology            | 1         | 0.39%   |
| Marvell Technology Group     | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24        | 8.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 18        | 6.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 5.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 4.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 4.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 3.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 2.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 2.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.37%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4         | 1.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 1.02%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 1.02%   |
| SanDisk PC SN520 NVMe SSD                                                               | 3         | 1.02%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 3         | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.02%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.02%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.68%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.68%   |
| Nvidia MCP89 SATA Controller                                                            | 2         | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 171       | 65.27%  |
| NVMe | 43        | 16.41%  |
| IDE  | 32        | 12.21%  |
| RAID | 16        | 6.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 188       | 82.82%  |
| AMD    | 39        | 17.18%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 2.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.76%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.32%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 3         | 1.32%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.32%   |
| Intel Core i5-3330S CPU @ 2.70GHz             | 3         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.32%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.32%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 2         | 0.88%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.88%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.88%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.88%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 2         | 0.88%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 2         | 0.88%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.88%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2         | 0.88%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.88%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.88%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.88%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.88%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 2         | 0.88%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 0.88%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 0.88%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 0.88%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.88%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 0.88%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.88%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 66        | 29.07%  |
| Intel Core i7                        | 42        | 18.5%   |
| Intel Core i3                        | 23        | 10.13%  |
| Intel Core 2 Duo                     | 14        | 6.17%   |
| Intel Celeron                        | 12        | 5.29%   |
| AMD Ryzen 5                          | 10        | 4.41%   |
| Intel Atom                           | 7         | 3.08%   |
| AMD Ryzen 7                          | 5         | 2.2%    |
| Other                                | 4         | 1.76%   |
| Intel Pentium Dual-Core              | 4         | 1.76%   |
| Intel Core 2 Quad                    | 4         | 1.76%   |
| Intel Core 2                         | 4         | 1.76%   |
| Intel Xeon                           | 3         | 1.32%   |
| Intel Pentium                        | 3         | 1.32%   |
| AMD Ryzen 3                          | 3         | 1.32%   |
| AMD Phenom II X4                     | 3         | 1.32%   |
| AMD A8                               | 3         | 1.32%   |
| AMD FX                               | 2         | 0.88%   |
| Intel Pentium Silver                 | 1         | 0.44%   |
| Intel Genuine                        | 1         | 0.44%   |
| Intel Core m3                        | 1         | 0.44%   |
| Intel Celeron Dual-Core              | 1         | 0.44%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.44%   |
| AMD Ryzen 9                          | 1         | 0.44%   |
| AMD Ryzen 5 PRO                      | 1         | 0.44%   |
| AMD Phenom                           | 1         | 0.44%   |
| AMD E1                               | 1         | 0.44%   |
| AMD C-60                             | 1         | 0.44%   |
| AMD Athlon II X4                     | 1         | 0.44%   |
| AMD Athlon II X3                     | 1         | 0.44%   |
| AMD A6                               | 1         | 0.44%   |
| AMD A4                               | 1         | 0.44%   |
| AMD A12                              | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 108       | 47.58%  |
| 4      | 94        | 41.41%  |
| 6      | 10        | 4.41%   |
| 8      | 5         | 2.2%    |
| 3      | 5         | 2.2%    |
| 1      | 4         | 1.76%   |
| 12     | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 226       | 99.56%  |
| 2      | 1         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 135       | 59.47%  |
| 1      | 92        | 40.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 227       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 13.54%  |
| 0x306a9    | 23        | 10.04%  |
| 0x206a7    | 19        | 8.3%    |
| 0x1067a    | 16        | 6.99%   |
| 0x306c3    | 12        | 5.24%   |
| 0x40651    | 9         | 3.93%   |
| 0x806ec    | 7         | 3.06%   |
| 0x806e9    | 6         | 2.62%   |
| 0x706e5    | 6         | 2.62%   |
| 0x906ea    | 5         | 2.18%   |
| 0x806ea    | 5         | 2.18%   |
| 0x6f6      | 5         | 2.18%   |
| 0x406e3    | 5         | 2.18%   |
| 0x30678    | 5         | 2.18%   |
| 0x08108109 | 5         | 2.18%   |
| 0x906eb    | 4         | 1.75%   |
| 0x506e3    | 4         | 1.75%   |
| 0x706a1    | 3         | 1.31%   |
| 0x406c3    | 3         | 1.31%   |
| 0x306d4    | 3         | 1.31%   |
| 0x906e9    | 2         | 0.87%   |
| 0x806eb    | 2         | 0.87%   |
| 0x806c1    | 2         | 0.87%   |
| 0x20655    | 2         | 0.87%   |
| 0x20652    | 2         | 0.87%   |
| 0x106e5    | 2         | 0.87%   |
| 0x106ca    | 2         | 0.87%   |
| 0x10676    | 2         | 0.87%   |
| 0x08701021 | 2         | 0.87%   |
| 0x08108102 | 2         | 0.87%   |
| 0x0810100b | 2         | 0.87%   |
| 0x06006705 | 2         | 0.87%   |
| 0x0600063e | 2         | 0.87%   |
| 0x05000119 | 2         | 0.87%   |
| 0x010000db | 2         | 0.87%   |
| 0x010000c8 | 2         | 0.87%   |
| 0x906ed    | 1         | 0.44%   |
| 0x906ec    | 1         | 0.44%   |
| 0x6fd      | 1         | 0.44%   |
| 0x6fb      | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 40        | 17.62%  |
| IvyBridge       | 25        | 11.01%  |
| Haswell         | 25        | 11.01%  |
| SandyBridge     | 22        | 9.69%   |
| Penryn          | 20        | 8.81%   |
| Silvermont      | 13        | 5.73%   |
| Skylake         | 10        | 4.41%   |
| Core            | 9         | 3.96%   |
| Zen+            | 8         | 3.52%   |
| IceLake         | 7         | 3.08%   |
| Zen 2           | 6         | 2.64%   |
| Zen             | 6         | 2.64%   |
| K10             | 6         | 2.64%   |
| Excavator       | 5         | 2.2%    |
| Westmere        | 4         | 1.76%   |
| Goldmont plus   | 4         | 1.76%   |
| Broadwell       | 3         | 1.32%   |
| TigerLake       | 2         | 0.88%   |
| Nehalem         | 2         | 0.88%   |
| Bulldozer       | 2         | 0.88%   |
| Bonnell         | 2         | 0.88%   |
| Bobcat          | 2         | 0.88%   |
| Steamroller     | 1         | 0.44%   |
| Puma            | 1         | 0.44%   |
| Piledriver      | 1         | 0.44%   |
| K8 & K10 hybrid | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 150       | 58.82%  |
| Nvidia | 55        | 21.57%  |
| AMD    | 50        | 19.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 6.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 5.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.17%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.65%   |
| Intel HD Graphics 620                                                                    | 7         | 2.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 2.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3         | 1.14%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 3         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.14%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.14%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.14%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.14%   |
| AMD Renoir                                                                               | 3         | 1.14%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.76%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.76%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.76%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.76%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.76%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.76%   |
| Intel HD Graphics 530                                                                    | 2         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 122       | 53.74%  |
| 1 x AMD        | 46        | 20.26%  |
| 1 x Nvidia     | 31        | 13.66%  |
| Intel + Nvidia | 23        | 10.13%  |
| 2 x AMD        | 2         | 0.88%   |
| Intel + AMD    | 2         | 0.88%   |
| 2 x Nvidia     | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 181       | 79.74%  |
| Proprietary | 38        | 16.74%  |
| Unknown     | 8         | 3.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 56.14%  |
| 1.01-2.0   | 37        | 16.23%  |
| 0.01-0.5   | 24        | 10.53%  |
| 0.51-1.0   | 16        | 7.02%   |
| 3.01-4.0   | 12        | 5.26%   |
| 7.01-8.0   | 8         | 3.51%   |
| 5.01-6.0   | 2         | 0.88%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 28        | 11.67%  |
| AU Optronics            | 27        | 11.25%  |
| BOE                     | 25        | 10.42%  |
| LG Display              | 24        | 10%     |
| Chimei Innolux          | 22        | 9.17%   |
| Dell                    | 17        | 7.08%   |
| Apple                   | 15        | 6.25%   |
| Goldstar                | 9         | 3.75%   |
| Chi Mei Optoelectronics | 6         | 2.5%    |
| AOC                     | 6         | 2.5%    |
| Acer                    | 6         | 2.5%    |
| Unknown                 | 5         | 2.08%   |
| Sharp                   | 5         | 2.08%   |
| Hewlett-Packard         | 5         | 2.08%   |
| Ancor Communications    | 5         | 2.08%   |
| BenQ                    | 4         | 1.67%   |
| ViewSonic               | 3         | 1.25%   |
| PANDA                   | 3         | 1.25%   |
| LG Electronics          | 3         | 1.25%   |
| Fujitsu Siemens         | 3         | 1.25%   |
| ___                     | 2         | 0.83%   |
| Lenovo                  | 2         | 0.83%   |
| Vizio                   | 1         | 0.42%   |
| Toshiba                 | 1         | 0.42%   |
| SAC                     | 1         | 0.42%   |
| Ruijiang                | 1         | 0.42%   |
| Philips                 | 1         | 0.42%   |
| PDA                     | 1         | 0.42%   |
| Panasonic               | 1         | 0.42%   |
| LG Philips              | 1         | 0.42%   |
| KIV                     | 1         | 0.42%   |
| InfoVision              | 1         | 0.42%   |
| Iiyama                  | 1         | 0.42%   |
| HPN                     | 1         | 0.42%   |
| HKC                     | 1         | 0.42%   |
| Haier                   | 1         | 0.42%   |
| Unknown                 | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                     | 3         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 1.22%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 3         | 1.22%   |
| ___ LCD TV ___0101 1366x768                                              | 2         | 0.82%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.82%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 0.82%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 2         | 0.82%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 0.82%   |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                      | 1         | 0.41%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch            | 1         | 0.41%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch            | 1         | 0.41%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch             | 1         | 0.41%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 1         | 0.41%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                       | 1         | 0.41%   |
| Unknown LCD Monitor Toshiba Internal LCD 1680x945                        | 1         | 0.41%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.41%   |
| Unknown LCD Monitor NCP 1920x1080                                        | 1         | 0.41%   |
| Toshiba TV TSB010B 1920x1080 926x523mm 41.9-inch                         | 1         | 0.41%   |
| Sharp LCD Monitor SHP14CB 1920x1200 288x180mm 13.4-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP13C1 1920x1200 366x229mm 17.0-inch                  | 1         | 0.41%   |
| Sharp HDMI SHP10A1 1360x768 700x390mm 31.5-inch                          | 1         | 0.41%   |
| Samsung Electronics U28E510 SAM0D63 1680x1050 610x350mm 27.7-inch        | 1         | 0.41%   |
| Samsung Electronics T27C370 SAM0ADE 1920x1080 598x336mm 27.0-inch        | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 459x296mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0560 1440x900 408x255mm 18.9-inch      | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 1         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch     | 1         | 0.41%   |
| Samsung Electronics LS32R75 SAM0F92 3840x2160 697x392mm 31.5-inch        | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch    | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 82        | 35.34%  |
| 1366x768 (WXGA)    | 59        | 25.43%  |
| 1600x900 (HD+)     | 17        | 7.33%   |
| 1280x800 (WXGA)    | 14        | 6.03%   |
| 3840x2160 (4K)     | 12        | 5.17%   |
| 2560x1440 (QHD)    | 5         | 2.16%   |
| 1680x1050 (WSXGA+) | 5         | 2.16%   |
| 1440x900 (WXGA+)   | 5         | 2.16%   |
| 1280x1024 (SXGA)   | 4         | 1.72%   |
| Unknown            | 4         | 1.72%   |
| 1920x1200 (WUXGA)  | 3         | 1.29%   |
| 1600x1200          | 3         | 1.29%   |
| 3440x1440          | 2         | 0.86%   |
| 2560x1600          | 2         | 0.86%   |
| 1024x600           | 2         | 0.86%   |
| 5120x1440          | 1         | 0.43%   |
| 3968x1280          | 1         | 0.43%   |
| 3840x1080          | 1         | 0.43%   |
| 3600x1080          | 1         | 0.43%   |
| 2880x1800          | 1         | 0.43%   |
| 2288x1287          | 1         | 0.43%   |
| 2256x1504          | 1         | 0.43%   |
| 2048x1152          | 1         | 0.43%   |
| 1920x515           | 1         | 0.43%   |
| 1920x1280          | 1         | 0.43%   |
| 1680x945           | 1         | 0.43%   |
| 1360x768           | 1         | 0.43%   |
| 1024x768 (XGA)     | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 49        | 20.33%  |
| 13      | 43        | 17.84%  |
| Unknown | 23        | 9.54%   |
| 14      | 19        | 7.88%   |
| 24      | 12        | 4.98%   |
| 17      | 12        | 4.98%   |
| 27      | 10        | 4.15%   |
| 19      | 10        | 4.15%   |
| 21      | 9         | 3.73%   |
| 23      | 8         | 3.32%   |
| 20      | 8         | 3.32%   |
| 11      | 7         | 2.9%    |
| 18      | 5         | 2.07%   |
| 84      | 3         | 1.24%   |
| 72      | 3         | 1.24%   |
| 31      | 3         | 1.24%   |
| 22      | 3         | 1.24%   |
| 10      | 3         | 1.24%   |
| 32      | 2         | 0.83%   |
| 29      | 2         | 0.83%   |
| 12      | 2         | 0.83%   |
| 57      | 1         | 0.41%   |
| 38      | 1         | 0.41%   |
| 34      | 1         | 0.41%   |
| 33      | 1         | 0.41%   |
| 16      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 39.48%  |
| 201-300     | 32        | 13.73%  |
| 401-500     | 28        | 12.02%  |
| 501-600     | 26        | 11.16%  |
| Unknown     | 23        | 9.87%   |
| 351-400     | 14        | 6.01%   |
| 601-700     | 6         | 2.58%   |
| 1501-2000   | 6         | 2.58%   |
| 701-800     | 4         | 1.72%   |
| 801-900     | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 152       | 70.7%   |
| 16/10   | 28        | 13.02%  |
| Unknown | 21        | 9.77%   |
| 5/4     | 5         | 2.33%   |
| 4/3     | 4         | 1.86%   |
| 3/2     | 3         | 1.4%    |
| 3.73    | 1         | 0.47%   |
| 21/9    | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 21.61%  |
| 101-110        | 50        | 21.19%  |
| 201-250        | 26        | 11.02%  |
| Unknown        | 23        | 9.75%   |
| 151-200        | 16        | 6.78%   |
| 71-80          | 11        | 4.66%   |
| 301-350        | 10        | 4.24%   |
| 351-500        | 9         | 3.81%   |
| 141-150        | 8         | 3.39%   |
| More than 1000 | 7         | 2.97%   |
| 51-60          | 7         | 2.97%   |
| 121-130        | 6         | 2.54%   |
| 41-50          | 3         | 1.27%   |
| 251-300        | 3         | 1.27%   |
| 131-140        | 3         | 1.27%   |
| 61-70          | 2         | 0.85%   |
| 501-1000       | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 82        | 36.12%  |
| 51-100        | 53        | 23.35%  |
| 121-160       | 51        | 22.47%  |
| Unknown       | 23        | 10.13%  |
| 161-240       | 11        | 4.85%   |
| 1-50          | 5         | 2.2%    |
| More than 240 | 2         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 186       | 80.52%  |
| 2     | 33        | 14.29%  |
| 0     | 8         | 3.46%   |
| 3     | 4         | 1.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 118       | 34.1%   |
| Intel                             | 101       | 29.19%  |
| Qualcomm Atheros                  | 50        | 14.45%  |
| Broadcom                          | 31        | 8.96%   |
| Nvidia                            | 8         | 2.31%   |
| TP-Link                           | 5         | 1.45%   |
| Marvell Technology Group          | 4         | 1.16%   |
| Broadcom Limited                  | 4         | 1.16%   |
| Ralink                            | 3         | 0.87%   |
| Samsung Electronics               | 2         | 0.58%   |
| Huawei Technologies               | 2         | 0.58%   |
| D-Link                            | 2         | 0.58%   |
| Xiaomi                            | 1         | 0.29%   |
| VIA Technologies                  | 1         | 0.29%   |
| Sierra Wireless                   | 1         | 0.29%   |
| Ralink Technology                 | 1         | 0.29%   |
| Qualcomm Atheros Communications   | 1         | 0.29%   |
| Qualcomm                          | 1         | 0.29%   |
| Microsoft                         | 1         | 0.29%   |
| LG Electronics                    | 1         | 0.29%   |
| Hewlett-Packard                   | 1         | 0.29%   |
| Google                            | 1         | 0.29%   |
| FIBOCOM                           | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| BUFFALO                           | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |
| Arduino SA                        | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 81        | 19.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 20        | 4.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 12        | 2.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 1.97%   |
| Intel Wireless 7260                                                                   | 8         | 1.97%   |
| Intel Wireless 8260                                                                   | 7         | 1.72%   |
| Intel Wi-Fi 6 AX200                                                                   | 7         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 1.47%   |
| Intel Ethernet Connection I218-LM                                                     | 5         | 1.23%   |
| Intel Centrino Advanced-N 6235                                                        | 5         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 4         | 0.98%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 0.98%   |
| Intel Wireless 7265                                                                   | 4         | 0.98%   |
| Intel I211 Gigabit Network Connection                                                 | 4         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                                  | 4         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 0.98%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 4         | 0.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 3         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 3         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 0.74%   |
| Realtek 802.11ac NIC                                                                  | 3         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 3         | 0.74%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 3         | 0.74%   |
| Nvidia MCP79 Ethernet                                                                 | 3         | 0.74%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 3         | 0.74%   |
| Intel Wireless 3165                                                                   | 3         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 0.74%   |
| Intel Ethernet Connection I219-LM                                                     | 3         | 0.74%   |
| Intel Ethernet Connection I217-LM                                                     | 3         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                                                  | 3         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                                  | 3         | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 3         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                                              | 3         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 3         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 37.81%  |
| Qualcomm Atheros                | 44        | 21.89%  |
| Realtek Semiconductor           | 34        | 16.92%  |
| Broadcom                        | 26        | 12.94%  |
| TP-Link                         | 5         | 2.49%   |
| Broadcom Limited                | 4         | 1.99%   |
| Ralink                          | 3         | 1.49%   |
| D-Link                          | 2         | 1%      |
| Sierra Wireless                 | 1         | 0.5%    |
| Ralink Technology               | 1         | 0.5%    |
| Qualcomm Atheros Communications | 1         | 0.5%    |
| Microsoft                       | 1         | 0.5%    |
| FIBOCOM                         | 1         | 0.5%    |
| D-Link System                   | 1         | 0.5%    |
| BUFFALO                         | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 4.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 3.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 3.96%   |
| Intel Wireless 7260                                                                   | 8         | 3.96%   |
| Intel Wireless 8260                                                                   | 7         | 3.47%   |
| Intel Wi-Fi 6 AX200                                                                   | 7         | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 2.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 2.97%   |
| Intel Centrino Advanced-N 6235                                                        | 5         | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 4         | 1.98%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.98%   |
| Intel Wireless 7265                                                                   | 4         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 1.98%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 4         | 1.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 3         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 3         | 1.49%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 1.49%   |
| Realtek 802.11ac NIC                                                                  | 3         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 1.49%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 3         | 1.49%   |
| Intel Wireless 3165                                                                   | 3         | 1.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 3         | 1.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 3         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 3         | 1.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 1.49%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 1.49%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 2         | 0.99%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 2         | 0.99%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 2         | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.99%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 2         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.99%   |
| Intel Wireless-AC 9260                                                                | 2         | 0.99%   |
| Intel Wireless 3160                                                                   | 2         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 52.5%   |
| Intel                    | 51        | 25.5%   |
| Qualcomm Atheros         | 11        | 5.5%    |
| Broadcom                 | 10        | 5%      |
| Nvidia                   | 8         | 4%      |
| Marvell Technology Group | 4         | 2%      |
| Samsung Electronics      | 2         | 1%      |
| Huawei Technologies      | 2         | 1%      |
| Xiaomi                   | 1         | 0.5%    |
| VIA Technologies         | 1         | 0.5%    |
| Qualcomm                 | 1         | 0.5%    |
| LG Electronics           | 1         | 0.5%    |
| Hewlett-Packard          | 1         | 0.5%    |
| Google                   | 1         | 0.5%    |
| ASIX Electronics         | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 39.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 9.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 5.91%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.46%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.97%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.48%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.48%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 1.48%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.48%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.48%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.48%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.99%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.99%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.49%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.49%   |
| Qualcomm Mobile Router                                            | 1         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.49%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.49%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.49%   |
| Nvidia MCP55 Ethernet                                             | 1         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.49%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 194       | 50%     |
| WiFi     | 192       | 49.48%  |
| Modem    | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 163       | 70.26%  |
| Ethernet | 69        | 29.74%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 136       | 59.65%  |
| 1     | 80        | 35.09%  |
| 0     | 6         | 2.63%   |
| 3     | 5         | 2.19%   |
| 4     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 200       | 88.11%  |
| Yes  | 27        | 11.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 38.71%  |
| Cambridge Silicon Radio         | 16        | 10.32%  |
| Apple                           | 16        | 10.32%  |
| Qualcomm Atheros Communications | 14        | 9.03%   |
| Realtek Semiconductor           | 12        | 7.74%   |
| Lite-On Technology              | 8         | 5.16%   |
| Broadcom                        | 8         | 5.16%   |
| Toshiba                         | 3         | 1.94%   |
| IMC Networks                    | 3         | 1.94%   |
| Hewlett-Packard                 | 3         | 1.94%   |
| Foxconn / Hon Hai               | 3         | 1.94%   |
| ASUSTek Computer                | 2         | 1.29%   |
| Taiyo Yuden                     | 1         | 0.65%   |
| Realtek                         | 1         | 0.65%   |
| Ralink                          | 1         | 0.65%   |
| Qcom                            | 1         | 0.65%   |
| Logitech                        | 1         | 0.65%   |
| Fujitsu                         | 1         | 0.65%   |
| Dell                            | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 25        | 16.13%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 10.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 5.16%   |
| Intel AX201 Bluetooth                               | 8         | 5.16%   |
| Apple Bluetooth Host Controller                     | 8         | 5.16%   |
| Intel AX200 Bluetooth                               | 7         | 4.52%   |
| Realtek Bluetooth Radio                             | 6         | 3.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 3.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.94%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.94%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.94%   |
| Apple Bluetooth HCI                                 | 3         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.29%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.29%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.29%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.29%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.29%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.65%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.65%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.65%   |
| Realtek Bluetooth Radio                             | 1         | 0.65%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.65%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.65%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.65%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.65%   |
| Lite-On Bluetooth Device                            | 1         | 0.65%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.65%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.65%   |
| IMC Networks Bluetooth Device                       | 1         | 0.65%   |
| IMC Networks BCM20702A0                             | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 177       | 60.82%  |
| AMD                        | 53        | 18.21%  |
| Nvidia                     | 41        | 14.09%  |
| C-Media Electronics        | 7         | 2.41%   |
| JMTek                      | 3         | 1.03%   |
| Generalplus Technology     | 3         | 1.03%   |
| YUAN High-Tech Development | 1         | 0.34%   |
| Texas Instruments          | 1         | 0.34%   |
| Native Instruments         | 1         | 0.34%   |
| Hewlett-Packard            | 1         | 0.34%   |
| Fortemedia                 | 1         | 0.34%   |
| Dell                       | 1         | 0.34%   |
| Astro Gaming               | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 6.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 6.63%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 6.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 4.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 3.17%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.59%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 2.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 2.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.73%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.15%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.15%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.86%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.86%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.86%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.86%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 21.88%  |
| SK hynix            | 24        | 18.75%  |
| Kingston            | 17        | 13.28%  |
| Unknown             | 15        | 11.72%  |
| Micron Technology   | 13        | 10.16%  |
| Crucial             | 7         | 5.47%   |
| Elpida              | 5         | 3.91%   |
| Corsair             | 3         | 2.34%   |
| Unknown (ABCD)      | 2         | 1.56%   |
| Ramaxel Technology  | 2         | 1.56%   |
| Patriot             | 2         | 1.56%   |
| Unknown (0x198)     | 1         | 0.78%   |
| Timetec             | 1         | 0.78%   |
| Smart               | 1         | 0.78%   |
| PNY                 | 1         | 0.78%   |
| Nanya Technology    | 1         | 0.78%   |
| Magnum Tech         | 1         | 0.78%   |
| G.Skill             | 1         | 0.78%   |
| Avant               | 1         | 0.78%   |
| Aeneon              | 1         | 0.78%   |
| A-DATA Technology   | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 2.94%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 1.47%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 2         | 1.47%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 2         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.47%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 1.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 1067MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.74%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.74%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 3733MT/s             | 1         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR3 667MT/s                    | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s     | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.74%   |
| Unknown (0x198) RAM Module 8GB SODIMM DDR3 1867MT/s              | 1         | 0.74%   |
| Timetec RAM SD4-2666 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.74%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 1         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.74%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 1         | 0.74%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.74%   |
| SK hynix RAM Module 1024MB SODIMM DDR2 800MT/s                   | 1         | 0.74%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.74%   |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s          | 1         | 0.74%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 52        | 49.06%  |
| DDR4    | 32        | 30.19%  |
| DDR2    | 12        | 11.32%  |
| LPDDR4  | 4         | 3.77%   |
| LPDDR3  | 3         | 2.83%   |
| Unknown | 2         | 1.89%   |
| SDRAM   | 1         | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 71.43%  |
| DIMM         | 24        | 22.86%  |
| Row Of Chips | 5         | 4.76%   |
| FB-DIMM      | 1         | 0.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 40        | 32.79%  |
| 8192  | 38        | 31.15%  |
| 2048  | 24        | 19.67%  |
| 16384 | 12        | 9.84%   |
| 1024  | 7         | 5.74%   |
| 32768 | 1         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 26        | 22.22%  |
| 2667  | 13        | 11.11%  |
| 1333  | 13        | 11.11%  |
| 667   | 10        | 8.55%   |
| 2400  | 8         | 6.84%   |
| 2133  | 8         | 6.84%   |
| 1334  | 8         | 6.84%   |
| 1067  | 5         | 4.27%   |
| 800   | 5         | 4.27%   |
| 3200  | 4         | 3.42%   |
| 1867  | 3         | 2.56%   |
| 3466  | 2         | 1.71%   |
| 1866  | 2         | 1.71%   |
| 4267  | 1         | 0.85%   |
| 4199  | 1         | 0.85%   |
| 3733  | 1         | 0.85%   |
| 3600  | 1         | 0.85%   |
| 3334  | 1         | 0.85%   |
| 2934  | 1         | 0.85%   |
| 2933  | 1         | 0.85%   |
| 1800  | 1         | 0.85%   |
| 1639  | 1         | 0.85%   |
| 1066  | 1         | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 62.5%   |
| Seiko Epson        | 1         | 12.5%   |
| Canon              | 1         | 12.5%   |
| Brother Industries | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-202 203 206 Series | 1         | 12.5%   |
| HP Printing Support               | 1         | 12.5%   |
| HP LaserJet Pro M202dw            | 1         | 12.5%   |
| HP LaserJet 1320                  | 1         | 12.5%   |
| HP Deskjet 2050 J510              | 1         | 12.5%   |
| HP Deskjet 1000 J110 series       | 1         | 12.5%   |
| Canon TR8500 series               | 1         | 12.5%   |
| Brother MFC-T910DW                | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 21.79%  |
| Realtek Semiconductor                  | 20        | 12.82%  |
| IMC Networks                           | 15        | 9.62%   |
| Apple                                  | 12        | 7.69%   |
| Sunplus Innovation Technology          | 10        | 6.41%   |
| Acer                                   | 9         | 5.77%   |
| Microdia                               | 8         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.85%   |
| Silicon Motion                         | 5         | 3.21%   |
| Quanta                                 | 5         | 3.21%   |
| Logitech                               | 5         | 3.21%   |
| Syntek                                 | 4         | 2.56%   |
| Suyin                                  | 3         | 1.92%   |
| Lite-On Technology                     | 3         | 1.92%   |
| Importek                               | 3         | 1.92%   |
| Samsung Electronics                    | 2         | 1.28%   |
| LG Electronics                         | 2         | 1.28%   |
| Alcor Micro                            | 2         | 1.28%   |
| Z-Star Microelectronics                | 1         | 0.64%   |
| Ricoh                                  | 1         | 0.64%   |
| Microsoft                              | 1         | 0.64%   |
| KYE Systems (Mouse Systems)            | 1         | 0.64%   |
| Jieli Technology                       | 1         | 0.64%   |
| Generalplus Technology                 | 1         | 0.64%   |
| Cubeternet                             | 1         | 0.64%   |
| ALi                                    | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                          | 10        | 6.41%   |
| Chicony Integrated Camera                             | 6         | 3.85%   |
| Chicony HD WebCam                                     | 6         | 3.85%   |
| Apple Built-in iSight                                 | 5         | 3.21%   |
| Logitech HD Pro Webcam C920                           | 4         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 4         | 2.56%   |
| IMC Networks Integrated Camera                        | 4         | 2.56%   |
| Sunplus HD WebCam                                     | 3         | 1.92%   |
| Realtek HD WebCam                                     | 3         | 1.92%   |
| Apple iPhone 5/5C/5S/6/SE                             | 3         | 1.92%   |
| Syntek Integrated Camera                              | 2         | 1.28%   |
| Syntek EasyCamera                                     | 2         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_HD                   | 2         | 1.28%   |
| Sunplus Integrated_Webcam_HD                          | 2         | 1.28%   |
| Samsung Galaxy series, misc. (MTP mode)               | 2         | 1.28%   |
| Realtek USB Camera                                    | 2         | 1.28%   |
| Quanta HP Webcam                                      | 2         | 1.28%   |
| Microdia Integrated_Webcam_HD                         | 2         | 1.28%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2         | 1.28%   |
| Importek TOSHIBA Web Camera - HD                      | 2         | 1.28%   |
| Chicony HP Wide Vision HD Camera                      | 2         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101  | 2         | 1.28%   |
| Apple FaceTime HD Camera                              | 2         | 1.28%   |
| Acer SunplusIT INC. Integrated Camera                 | 2         | 1.28%   |
| Acer BisonCam, NB Pro                                 | 2         | 1.28%   |
| Z-Star Venus USB2.0 Camera                            | 1         | 0.64%   |
| Suyin UVC HD Webcam                                   | 1         | 0.64%   |
| Suyin HP Truevision HD                                | 1         | 0.64%   |
| Suyin HD Video WebCam                                 | 1         | 0.64%   |
| Sunplus HP Universal Camera                           | 1         | 0.64%   |
| Sunplus Dell HD Webcam                                | 1         | 0.64%   |
| Sunplus Dell E5570 integrated webcam                  | 1         | 0.64%   |
| Silicon Motion WebCam SC-13HDL12131N                  | 1         | 0.64%   |
| Silicon Motion WebCam SC-10HDD12636N                  | 1         | 0.64%   |
| Silicon Motion Web Camera                             | 1         | 0.64%   |
| Silicon Motion Lenovo EasyCamera                      | 1         | 0.64%   |
| Silicon Motion HP Webcam-101 Integrated Camera        | 1         | 0.64%   |
| Ricoh USB2.0 Camera                                   | 1         | 0.64%   |
| Realtek USB2.0 HD UVC WebCam                          | 1         | 0.64%   |
| Realtek Integrated Webcam HD                          | 1         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 40.74%  |
| Synaptics                  | 8         | 29.63%  |
| Shenzhen Goodix Technology | 3         | 11.11%  |
| LighTuning Technology      | 3         | 11.11%  |
| Elan Microelectronics      | 2         | 7.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 7.41%   |
| Validity Sensors VFS491                                                    | 2         | 7.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 7.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 7.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 7.41%   |
| Elan ELAN:Fingerprint                                                      | 2         | 7.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 3.7%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.7%    |
| Unknown                                                                    | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 46.15%  |
| Alcor Micro | 3         | 23.08%  |
| O2 Micro    | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |
| Lenovo      | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 23.08%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 170       | 73.59%  |
| 1     | 50        | 21.65%  |
| 2     | 8         | 3.46%   |
| 3     | 3         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 26        | 34.67%  |
| Graphics card      | 15        | 20%     |
| Chipcard           | 13        | 17.33%  |
| Net/wireless       | 10        | 13.33%  |
| Camera             | 5         | 6.67%   |
| Storage            | 2         | 2.67%   |
| Network            | 1         | 1.33%   |
| Net/ethernet       | 1         | 1.33%   |
| Card reader        | 1         | 1.33%   |
| Bluetooth          | 1         | 1.33%   |


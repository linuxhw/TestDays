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

Total: 311

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.4.0-42-generic          | 20        | 8.06%   |
| 5.4.0-65-generic          | 17        | 6.85%   |
| 5.4.0-58-generic          | 14        | 5.65%   |
| 5.4.0-48-generic          | 13        | 5.24%   |
| 5.4.0-52-generic          | 12        | 4.84%   |
| 5.4.0-80-generic          | 9         | 3.63%   |
| 5.4.0-56-generic          | 9         | 3.63%   |
| 5.4.0-54-generic          | 9         | 3.63%   |
| 5.4.0-73-generic          | 8         | 3.23%   |
| 5.4.0-72-generic          | 7         | 2.82%   |
| 5.4.0-47-generic          | 7         | 2.82%   |
| 5.4.0-70-generic          | 6         | 2.42%   |
| 5.4.0-66-generic          | 6         | 2.42%   |
| 5.4.0-81-generic          | 5         | 2.02%   |
| 5.4.0-60-generic          | 5         | 2.02%   |
| 5.4.0-90-generic          | 4         | 1.61%   |
| 5.4.0-77-generic          | 4         | 1.61%   |
| 5.4.0-74-generic          | 4         | 1.61%   |
| 5.4.0-67-generic          | 4         | 1.61%   |
| 5.4.0-53-generic          | 4         | 1.61%   |
| 4.15.0-128-generic        | 4         | 1.61%   |
| 4.15.0-112-generic        | 4         | 1.61%   |
| 5.4.0-71-generic          | 3         | 1.21%   |
| 5.4.0-64-generic          | 3         | 1.21%   |
| 5.4.0-45-generic          | 3         | 1.21%   |
| 5.4.0-96-generic          | 2         | 0.81%   |
| 5.4.0-92-generic          | 2         | 0.81%   |
| 5.4.0-91-generic          | 2         | 0.81%   |
| 5.4.0-62-generic          | 2         | 0.81%   |
| 5.4.0-59-generic          | 2         | 0.81%   |
| 5.4.0-51-generic          | 2         | 0.81%   |
| 5.4.0-120-generic         | 2         | 0.81%   |
| 5.4.0-109-generic         | 2         | 0.81%   |
| 5.4.0-107-generic         | 2         | 0.81%   |
| 5.4.0-100-generic         | 2         | 0.81%   |
| 5.3.0-62-generic          | 2         | 0.81%   |
| 5.10.0-051000-generic     | 2         | 0.81%   |
| 4.15.0-162-generic        | 2         | 0.81%   |
| 4.15.0-161-generic        | 2         | 0.81%   |
| 4.15.0-140-generic        | 2         | 0.81%   |
| 5.9.1-050901-generic      | 1         | 0.4%    |
| 5.8.5-050805-generic      | 1         | 0.4%    |
| 5.8.13-050813-generic     | 1         | 0.4%    |
| 5.8.0-17.2-liquorix-amd64 | 1         | 0.4%    |
| 5.8.0-050800-generic      | 1         | 0.4%    |
| 5.6.19-050619-generic     | 1         | 0.4%    |
| 5.4.78-1203.4-MiDoX-EOS   | 1         | 0.4%    |
| 5.4.0-97-generic          | 1         | 0.4%    |
| 5.4.0-94-generic          | 1         | 0.4%    |
| 5.4.0-89-generic          | 1         | 0.4%    |
| 5.4.0-86-generic          | 1         | 0.4%    |
| 5.4.0-84-generic          | 1         | 0.4%    |
| 5.4.0-49-generic          | 1         | 0.4%    |
| 5.4.0-113-generic         | 1         | 0.4%    |
| 5.4.0-104-generic         | 1         | 0.4%    |
| 5.3.0-7648-generic        | 1         | 0.4%    |
| 5.3.0-51-generic          | 1         | 0.4%    |
| 5.17.0-051700-generic     | 1         | 0.4%    |
| 5.15.5-051505-generic     | 1         | 0.4%    |
| 5.15.12-051512-generic    | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 186       | 81.94%  |
| 4.15.0  | 20        | 8.81%   |
| 5.3.0   | 4         | 1.76%   |
| 5.10.0  | 3         | 1.32%   |
| 5.8.0   | 2         | 0.88%   |
| 5.9.1   | 1         | 0.44%   |
| 5.8.5   | 1         | 0.44%   |
| 5.8.13  | 1         | 0.44%   |
| 5.6.19  | 1         | 0.44%   |
| 5.4.78  | 1         | 0.44%   |
| 5.17.0  | 1         | 0.44%   |
| 5.15.5  | 1         | 0.44%   |
| 5.15.12 | 1         | 0.44%   |
| 5.14.9  | 1         | 0.44%   |
| 5.14.0  | 1         | 0.44%   |
| 5.10.4  | 1         | 0.44%   |
| 4.18.0  | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 187       | 82.38%  |
| 4.15    | 20        | 8.81%   |
| 5.8     | 4         | 1.76%   |
| 5.3     | 4         | 1.76%   |
| 5.10    | 4         | 1.76%   |
| 5.15    | 2         | 0.88%   |
| 5.14    | 2         | 0.88%   |
| 5.9     | 1         | 0.44%   |
| 5.6     | 1         | 0.44%   |
| 5.17    | 1         | 0.44%   |
| 4.18    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 224       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 195       | 86.28%  |
| Unknown    | 26        | 11.5%   |
| X-Cinnamon | 2         | 0.88%   |
| Unity      | 1         | 0.44%   |
| GNOME      | 1         | 0.44%   |
| Budgie     | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 223       | 99.55%  |
| Unknown | 1         | 0.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 171       | 75.33%  |
| TDM     | 33        | 14.54%  |
| LightDM | 21        | 9.25%   |
| SDDM    | 1         | 0.44%   |
| GDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 93        | 41.33%  |
| en_GB   | 16        | 7.11%   |
| pt_BR   | 10        | 4.44%   |
| es_ES   | 10        | 4.44%   |
| de_DE   | 9         | 4%      |
| ru_RU   | 8         | 3.56%   |
| pl_PL   | 8         | 3.56%   |
| en_IN   | 7         | 3.11%   |
| en_AU   | 7         | 3.11%   |
| en_CA   | 6         | 2.67%   |
| fr_FR   | 5         | 2.22%   |
| es_MX   | 5         | 2.22%   |
| it_IT   | 3         | 1.33%   |
| hu_HU   | 3         | 1.33%   |
| es_EC   | 3         | 1.33%   |
| en_ZA   | 3         | 1.33%   |
| hr_HR   | 2         | 0.89%   |
| en_PH   | 2         | 0.89%   |
| el_GR   | 2         | 0.89%   |
| de_AT   | 2         | 0.89%   |
| Unknown | 2         | 0.89%   |
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

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 118       | 52.44%  |
| EFI  | 107       | 47.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 212       | 94.22%  |
| Btrfs   | 7         | 3.11%   |
| Overlay | 4         | 1.78%   |
| Xfs     | 1         | 0.44%   |
| Ext3    | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 182       | 81.25%  |
| GPT     | 30        | 13.39%  |
| MBR     | 12        | 5.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 212       | 94.64%  |
| Yes       | 12        | 5.36%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 175       | 77.78%  |
| Yes       | 50        | 22.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 35        | 15.63%  |
| ASUSTek Computer    | 33        | 14.73%  |
| Lenovo              | 30        | 13.39%  |
| Dell                | 30        | 13.39%  |
| Acer                | 19        | 8.48%   |
| Apple               | 15        | 6.7%    |
| Gigabyte Technology | 14        | 6.25%   |
| Toshiba             | 8         | 3.57%   |
| MSI                 | 7         | 3.13%   |
| Samsung Electronics | 4         | 1.79%   |
| ASRock              | 4         | 1.79%   |
| Intel               | 3         | 1.34%   |
| Biostar             | 3         | 1.34%   |
| WeiBu               | 1         | 0.45%   |
| Star Labs           | 1         | 0.45%   |
| Sony                | 1         | 0.45%   |
| Positivo            | 1         | 0.45%   |
| Panasonic           | 1         | 0.45%   |
| LG Electronics      | 1         | 0.45%   |
| HUAWEI              | 1         | 0.45%   |
| Hampoo              | 1         | 0.45%   |
| Google              | 1         | 0.45%   |
| Fujitsu Siemens     | 1         | 0.45%   |
| Fujitsu             | 1         | 0.45%   |
| Foxconn             | 1         | 0.45%   |
| EVGA                | 1         | 0.45%   |
| eMachines           | 1         | 0.45%   |
| Compaq              | 1         | 0.45%   |
| Clevo               | 1         | 0.45%   |
| Chuwi               | 1         | 0.45%   |
| 3E                  | 1         | 0.45%   |
| Unknown             | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Apple MacBook2,1                               | 3         | 1.34%   |
| HP Pavilion dv7                                | 2         | 0.89%   |
| HP Laptop 17-by3xxx                            | 2         | 0.89%   |
| Dell Latitude E6400                            | 2         | 0.89%   |
| ASUS P8H61-M LX3 R2.0                          | 2         | 0.89%   |
| ASUS All Series                                | 2         | 0.89%   |
| Apple MacBook7,1                               | 2         | 0.89%   |
| Acer Aspire R3-131T                            | 2         | 0.89%   |
| Acer Aspire F5-573G                            | 2         | 0.89%   |
| Acer AOD255E                                   | 2         | 0.89%   |
| WeiBu Unity F24B                               | 1         | 0.45%   |
| Toshiba Satellite R630                         | 1         | 0.45%   |
| Toshiba Satellite P750                         | 1         | 0.45%   |
| Toshiba Satellite L855                         | 1         | 0.45%   |
| Toshiba Satellite L500                         | 1         | 0.45%   |
| Toshiba Satellite C870-1H2                     | 1         | 0.45%   |
| Toshiba Satellite C850D-119                    | 1         | 0.45%   |
| Toshiba Satellite C55t-A                       | 1         | 0.45%   |
| Toshiba QOSMIO G55                             | 1         | 0.45%   |
| Star Labs Lite                                 | 1         | 0.45%   |
| Sony VPCF23JFX                                 | 1         | 0.45%   |
| Samsung 850XBD                                 | 1         | 0.45%   |
| Samsung 530U3C/530U4C/532U3C                   | 1         | 0.45%   |
| Samsung 350V5C/351V5C/3540VC/3440VC            | 1         | 0.45%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 1         | 0.45%   |
| Positivo S14SL01                               | 1         | 0.45%   |
| Panasonic CF-31SBLJGDM                         | 1         | 0.45%   |
| MSI P35 Platinum(MS-7345)                      | 1         | 0.45%   |
| MSI MS-7C94                                    | 1         | 0.45%   |
| MSI MS-7C02                                    | 1         | 0.45%   |
| MSI MS-7A38                                    | 1         | 0.45%   |
| MSI MS-7788                                    | 1         | 0.45%   |
| MSI MS-7721                                    | 1         | 0.45%   |
| MSI GE60 2PE                                   | 1         | 0.45%   |
| LG R490-G.ARL5RE2                              | 1         | 0.45%   |
| Lenovo Yoga 710-14IKB 80V4                     | 1         | 0.45%   |
| Lenovo V15-IIL 82C5                            | 1         | 0.45%   |
| Lenovo V15-ADA 82C7                            | 1         | 0.45%   |
| Lenovo ThinkPad X240 20AMS0XP0S                | 1         | 0.45%   |
| Lenovo ThinkPad X240 20AMA0XK00                | 1         | 0.45%   |
| Lenovo ThinkPad X13 Gen 1 20UF0013US           | 1         | 0.45%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDS1WX00       | 1         | 0.45%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS03P00       | 1         | 0.45%   |
| Lenovo ThinkPad T530 2429JB5                   | 1         | 0.45%   |
| Lenovo ThinkPad T480 20L50018US                | 1         | 0.45%   |
| Lenovo ThinkPad T480 20L50007RT                | 1         | 0.45%   |
| Lenovo ThinkPad T460 20FMS6C200                | 1         | 0.45%   |
| Lenovo ThinkPad T440p 20AWS1HK0P               | 1         | 0.45%   |
| Lenovo ThinkPad T440 20B7S0JF0L                | 1         | 0.45%   |
| Lenovo ThinkPad T420 4236M37                   | 1         | 0.45%   |
| Lenovo ThinkPad R61e/R61i 76508TG              | 1         | 0.45%   |
| Lenovo ThinkPad P50 20ENA00PLM                 | 1         | 0.45%   |
| Lenovo ThinkPad L480 20LSS0GL00                | 1         | 0.45%   |
| Lenovo ThinkPad E580 20KSCTO1WW                | 1         | 0.45%   |
| Lenovo ThinkPad E14 20RBS6MD00                 | 1         | 0.45%   |
| Lenovo ThinkCentre M92p 3227D13                | 1         | 0.45%   |
| Lenovo IdeaPadFlex 14 20308                    | 1         | 0.45%   |
| Lenovo IdeaPad S145-15IKB 81XM                 | 1         | 0.45%   |
| Lenovo IdeaPad 330-15IKB 81DE                  | 1         | 0.45%   |
| Lenovo IdeaPad 330-14AST 81D5                  | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 7.59%   |
| Acer Aspire            | 12        | 5.36%   |
| Dell Latitude          | 9         | 4.02%   |
| HP Pavilion            | 8         | 3.57%   |
| Dell Inspiron          | 8         | 3.57%   |
| Toshiba Satellite      | 7         | 3.13%   |
| Lenovo IdeaPad         | 5         | 2.23%   |
| HP ProBook             | 5         | 2.23%   |
| ASUS PRIME             | 5         | 2.23%   |
| HP EliteBook           | 4         | 1.79%   |
| Dell Vostro            | 4         | 1.79%   |
| HP 250                 | 3         | 1.34%   |
| Dell XPS               | 3         | 1.34%   |
| Dell OptiPlex          | 3         | 1.34%   |
| Apple MacBook2         | 3         | 1.34%   |
| Acer Swift             | 3         | 1.34%   |
| HP Laptop              | 2         | 0.89%   |
| HP ENVY                | 2         | 0.89%   |
| HP Compaq              | 2         | 0.89%   |
| ASUS ZenBook           | 2         | 0.89%   |
| ASUS VivoBook          | 2         | 0.89%   |
| ASUS TUF               | 2         | 0.89%   |
| ASUS ROG               | 2         | 0.89%   |
| ASUS P8H61-M           | 2         | 0.89%   |
| ASUS All               | 2         | 0.89%   |
| Apple MacBook7         | 2         | 0.89%   |
| Acer AOD255E           | 2         | 0.89%   |
| WeiBu Unity            | 1         | 0.45%   |
| Toshiba QOSMIO         | 1         | 0.45%   |
| Star Labs Lite         | 1         | 0.45%   |
| Sony VPCF23JFX         | 1         | 0.45%   |
| Samsung 850XBD         | 1         | 0.45%   |
| Samsung 530U3C         | 1         | 0.45%   |
| Samsung 350V5C         | 1         | 0.45%   |
| Samsung 300E5EV        | 1         | 0.45%   |
| Positivo S14SL01       | 1         | 0.45%   |
| Panasonic CF-31SBLJGDM | 1         | 0.45%   |
| MSI P35                | 1         | 0.45%   |
| MSI MS-7C94            | 1         | 0.45%   |
| MSI MS-7C02            | 1         | 0.45%   |
| MSI MS-7A38            | 1         | 0.45%   |
| MSI MS-7788            | 1         | 0.45%   |
| MSI MS-7721            | 1         | 0.45%   |
| MSI GE60               | 1         | 0.45%   |
| LG R490-G.ARL5RE2      | 1         | 0.45%   |
| Lenovo Yoga            | 1         | 0.45%   |
| Lenovo V15-IIL         | 1         | 0.45%   |
| Lenovo V15-ADA         | 1         | 0.45%   |
| Lenovo ThinkCentre     | 1         | 0.45%   |
| Lenovo IdeaPadFlex     | 1         | 0.45%   |
| Lenovo G50-45          | 1         | 0.45%   |
| Lenovo Flex            | 1         | 0.45%   |
| Lenovo 3000            | 1         | 0.45%   |
| Intel NUC8i5BEH        | 1         | 0.45%   |
| Intel DG41RQ           | 1         | 0.45%   |
| Intel DG35EC           | 1         | 0.45%   |
| HUAWEI HLY-WX9XX       | 1         | 0.45%   |
| HP ZBook               | 1         | 0.45%   |
| HP Slim                | 1         | 0.45%   |
| HP ProOne              | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 25        | 11.16%  |
| 2013 | 25        | 11.16%  |
| 2018 | 21        | 9.38%   |
| 2012 | 21        | 9.38%   |
| 2020 | 19        | 8.48%   |
| 2011 | 19        | 8.48%   |
| 2016 | 17        | 7.59%   |
| 2008 | 14        | 6.25%   |
| 2010 | 12        | 5.36%   |
| 2015 | 11        | 4.91%   |
| 2014 | 11        | 4.91%   |
| 2009 | 11        | 4.91%   |
| 2017 | 10        | 4.46%   |
| 2007 | 6         | 2.68%   |
| 2021 | 1         | 0.45%   |
| 2006 | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 145       | 64.73%  |
| Desktop     | 65        | 29.02%  |
| Convertible | 6         | 2.68%   |
| All in one  | 4         | 1.79%   |
| Tablet      | 2         | 0.89%   |
| Mini pc     | 2         | 0.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 220       | 98.21%  |
| Enabled  | 4         | 1.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 223       | 99.55%  |
| Yes  | 1         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 55        | 24.55%  |
| 8.01-16.0   | 52        | 23.21%  |
| 3.01-4.0    | 45        | 20.09%  |
| 16.01-24.0  | 37        | 16.52%  |
| 1.01-2.0    | 14        | 6.25%   |
| 32.01-64.0  | 11        | 4.91%   |
| 2.01-3.0    | 6         | 2.68%   |
| 0.51-1.0    | 2         | 0.89%   |
| 24.01-32.0  | 1         | 0.45%   |
| 64.01-256.0 | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 91        | 38.4%   |
| 2.01-3.0  | 63        | 26.58%  |
| 3.01-4.0  | 39        | 16.46%  |
| 4.01-8.0  | 32        | 13.5%   |
| 0.51-1.0  | 7         | 2.95%   |
| 8.01-16.0 | 5         | 2.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 139       | 61.5%   |
| 2      | 65        | 28.76%  |
| 3      | 7         | 3.1%    |
| 5      | 4         | 1.77%   |
| 4      | 4         | 1.77%   |
| 0      | 3         | 1.33%   |
| 7      | 2         | 0.88%   |
| 6      | 2         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 61.23%  |
| Yes       | 88        | 38.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 84.38%  |
| No        | 35        | 15.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 84.89%  |
| No        | 34        | 15.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 65.78%  |
| No        | 77        | 34.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 27        | 12.05%  |
| UK           | 15        | 6.7%    |
| Brazil       | 15        | 6.7%    |
| Germany      | 14        | 6.25%   |
| Spain        | 12        | 5.36%   |
| Mexico       | 11        | 4.91%   |
| Poland       | 10        | 4.46%   |
| India        | 10        | 4.46%   |
| Russia       | 8         | 3.57%   |
| Canada       | 8         | 3.57%   |
| Indonesia    | 6         | 2.68%   |
| France       | 6         | 2.68%   |
| Australia    | 6         | 2.68%   |
| Ukraine      | 5         | 2.23%   |
| Italy        | 5         | 2.23%   |
| Turkey       | 4         | 1.79%   |
| Netherlands  | 4         | 1.79%   |
| Malaysia     | 4         | 1.79%   |
| Peru         | 3         | 1.34%   |
| Hungary      | 3         | 1.34%   |
| Hong Kong    | 3         | 1.34%   |
| Greece       | 3         | 1.34%   |
| Ecuador      | 3         | 1.34%   |
| Sweden       | 2         | 0.89%   |
| South Africa | 2         | 0.89%   |
| Philippines  | 2         | 0.89%   |
| Kenya        | 2         | 0.89%   |
| Ireland      | 2         | 0.89%   |
| Croatia      | 2         | 0.89%   |
| Austria      | 2         | 0.89%   |
| Argentina    | 2         | 0.89%   |
| Venezuela    | 1         | 0.45%   |
| Uruguay      | 1         | 0.45%   |
| UAE          | 1         | 0.45%   |
| Tajikistan   | 1         | 0.45%   |
| Slovakia     | 1         | 0.45%   |
| Sint Maarten | 1         | 0.45%   |
| Saudi Arabia | 1         | 0.45%   |
| Romania      | 1         | 0.45%   |
| Portugal     | 1         | 0.45%   |
| Panama       | 1         | 0.45%   |
| Nicaragua    | 1         | 0.45%   |
| New Zealand  | 1         | 0.45%   |
| Luxembourg   | 1         | 0.45%   |
| Latvia       | 1         | 0.45%   |
| Kosovo       | 1         | 0.45%   |
| Georgia      | 1         | 0.45%   |
| Eswatini     | 1         | 0.45%   |
| El Salvador  | 1         | 0.45%   |
| Czechia      | 1         | 0.45%   |
| Costa Rica   | 1         | 0.45%   |
| China        | 1         | 0.45%   |
| Belgium      | 1         | 0.45%   |
| Azerbaijan   | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Warsaw                  | 4         | 1.75%   |
| Fortaleza               | 4         | 1.75%   |
| Montreal                | 3         | 1.31%   |
| Hamburg                 | 3         | 1.31%   |
| Berlin                  | 3         | 1.31%   |
| Valencia                | 2         | 0.87%   |
| Tijuana                 | 2         | 0.87%   |
| Rio de Janeiro          | 2         | 0.87%   |
| Quito                   | 2         | 0.87%   |
| Perth                   | 2         | 0.87%   |
| Novosibirsk             | 2         | 0.87%   |
| Nairobi                 | 2         | 0.87%   |
| Milan                   | 2         | 0.87%   |
| Mexico City             | 2         | 0.87%   |
| Melbourne               | 2         | 0.87%   |
| Lima                    | 2         | 0.87%   |
| Jaipur                  | 2         | 0.87%   |
| Gilbert                 | 2         | 0.87%   |
| Eskişehir              | 2         | 0.87%   |
| Córdoba                | 2         | 0.87%   |
| Central                 | 2         | 0.87%   |
| Cape Town               | 2         | 0.87%   |
| Ames                    | 2         | 0.87%   |
| Zaragoza                | 1         | 0.44%   |
| Zagreb                  | 1         | 0.44%   |
| York                    | 1         | 0.44%   |
| Yogyakarta              | 1         | 0.44%   |
| Wroclaw                 | 1         | 0.44%   |
| Winhoring               | 1         | 0.44%   |
| Wellington              | 1         | 0.44%   |
| Villahermosa            | 1         | 0.44%   |
| Vigo                    | 1         | 0.44%   |
| Vienna                  | 1         | 0.44%   |
| Vernon                  | 1         | 0.44%   |
| Tseung Kwan O           | 1         | 0.44%   |
| Torun                   | 1         | 0.44%   |
| Tirupur                 | 1         | 0.44%   |
| Theodore                | 1         | 0.44%   |
| Talavera de la Reina    | 1         | 0.44%   |
| SГЈo Pedro            | 1         | 0.44%   |
| Surabaya                | 1         | 0.44%   |
| Sungai Petani           | 1         | 0.44%   |
| Stockton                | 1         | 0.44%   |
| Stavropol               | 1         | 0.44%   |
| Solna                   | 1         | 0.44%   |
| Simferopol              | 1         | 0.44%   |
| Shelekhov               | 1         | 0.44%   |
| Serres                  | 1         | 0.44%   |
| Seremban                | 1         | 0.44%   |
| Sao Luís               | 1         | 0.44%   |
| Sao José dos Campos    | 1         | 0.44%   |
| Santos                  | 1         | 0.44%   |
| Santo André            | 1         | 0.44%   |
| Santa Rosa              | 1         | 0.44%   |
| Santa Brigida           | 1         | 0.44%   |
| Sant Andreu de la Barca | 1         | 0.44%   |
| San Salvador            | 1         | 0.44%   |
| Samobor                 | 1         | 0.44%   |
| Rotterdam               | 1         | 0.44%   |
| Riyadh                  | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 55     | 13.73%  |
| Samsung Electronics | 34        | 46     | 11.11%  |
| WDC                 | 33        | 44     | 10.78%  |
| Toshiba             | 31        | 47     | 10.13%  |
| SanDisk             | 27        | 27     | 8.82%   |
| Kingston            | 25        | 35     | 8.17%   |
| Unknown             | 19        | 23     | 6.21%   |
| Crucial             | 19        | 22     | 6.21%   |
| Hitachi             | 13        | 14     | 4.25%   |
| Intel               | 10        | 12     | 3.27%   |
| HGST                | 10        | 12     | 3.27%   |
| Apple               | 4         | 4      | 1.31%   |
| A-DATA Technology   | 4         | 5      | 1.31%   |
| SK hynix            | 3         | 3      | 0.98%   |
| KIOXIA              | 3         | 8      | 0.98%   |
| Fujitsu             | 3         | 3      | 0.98%   |
| PNY                 | 2         | 2      | 0.65%   |
| Patriot             | 2         | 2      | 0.65%   |
| Micron Technology   | 2         | 3      | 0.65%   |
| WDC WDS             | 1         | 1      | 0.33%   |
| V-GeN               | 1         | 1      | 0.33%   |
| Transcend           | 1         | 1      | 0.33%   |
| TO Exter            | 1         | 1      | 0.33%   |
| Star                | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| Phison              | 1         | 1      | 0.33%   |
| OWC                 | 1         | 1      | 0.33%   |
| OCZ                 | 1         | 2      | 0.33%   |
| NGFF                | 1         | 1      | 0.33%   |
| LITEON              | 1         | 1      | 0.33%   |
| KingSpec            | 1         | 1      | 0.33%   |
| JMicron Technology  | 1         | 1      | 0.33%   |
| Hewlett-Packard     | 1         | 1      | 0.33%   |
| GOODRAM             | 1         | 2      | 0.33%   |
| Gigabyte Technology | 1         | 1      | 0.33%   |
| GeIL                | 1         | 1      | 0.33%   |
| EMTEC               | 1         | 1      | 0.33%   |
| China               | 1         | 1      | 0.33%   |
| ADATA Technology    | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD         | 7         | 2.11%   |
| Unknown MMC Card  64GB                  | 6         | 1.81%   |
| Toshiba MQ04ABF100 1TB                  | 6         | 1.81%   |
| Samsung SSD 850 EVO 250GB               | 5         | 1.51%   |
| Samsung NVMe SSD Drive 512GB            | 5         | 1.51%   |
| Unknown MMC Card  32GB                  | 4         | 1.2%    |
| Seagate ST500DM002-1BD142 500GB         | 4         | 1.2%    |
| SanDisk NVMe SSD Drive 256GB            | 4         | 1.2%    |
| Kingston SA400S37120G 120GB SSD         | 4         | 1.2%    |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 0.9%    |
| Toshiba NVMe SSD Drive 256GB            | 3         | 0.9%    |
| Toshiba DT01ACA100 1TB                  | 3         | 0.9%    |
| SanDisk SSD PLUS 480GB                  | 3         | 0.9%    |
| SanDisk NVMe SSD Drive 512GB            | 3         | 0.9%    |
| Samsung SSD 860 QVO 1TB                 | 3         | 0.9%    |
| Kingston SV300S37A120G 120GB SSD        | 3         | 0.9%    |
| HGST HTS545050A7E680 500GB              | 3         | 0.9%    |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.9%    |
| Crucial CT120BX500SSD1 120GB            | 3         | 0.9%    |
| Crucial CT120BX300SSD1 120GB            | 3         | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 0.6%    |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.6%    |
| Unknown MMC Card  16GB                  | 2         | 0.6%    |
| Toshiba THNSNJ128GCSU 128GB SSD         | 2         | 0.6%    |
| Toshiba MQ01ABF050 500GB                | 2         | 0.6%    |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.6%    |
| Seagate ST500LM000-1EJ162 500GB         | 2         | 0.6%    |
| Seagate ST3500418AS 500GB               | 2         | 0.6%    |
| Seagate ST320LT007-9ZV142 320GB         | 2         | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 0.6%    |
| Seagate Expansion 1TB                   | 2         | 0.6%    |
| SanDisk SSD PLUS 240GB                  | 2         | 0.6%    |
| Samsung SSD 970 EVO 500GB               | 2         | 0.6%    |
| Samsung SSD 860 EVO 500GB               | 2         | 0.6%    |
| Samsung SSD 860 EVO 250GB               | 2         | 0.6%    |
| Samsung SSD 850 EVO 500GB               | 2         | 0.6%    |
| Samsung SSD 840 EVO 500GB               | 2         | 0.6%    |
| Samsung NVMe SSD Drive 256GB            | 2         | 0.6%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 0.6%    |
| Hitachi HTS545025B9A300 250GB           | 2         | 0.6%    |
| HGST HTS725050A7E630 500GB              | 2         | 0.6%    |
| HGST HTS721010A9E630 1TB                | 2         | 0.6%    |
| HGST HTS541010A9E680 1TB                | 2         | 0.6%    |
| Crucial CT2000MX500SSD1 2TB             | 2         | 0.6%    |
| Crucial CT1000MX500SSD1 1TB             | 2         | 0.6%    |
| WDC WDS250G2B0B-00YS70 250GB SSD        | 1         | 0.3%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.3%    |
| WDC WDS100T1R0B-68A4Z0 1TB SSD          | 1         | 0.3%    |
| WDC WDS 500G2B0B-00YS70 500GB SSD       | 1         | 0.3%    |
| WDC WD6003FZBX-00K5WB0 6TB              | 1         | 0.3%    |
| WDC WD5000LUCT-63RC2Y0 500GB            | 1         | 0.3%    |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.3%    |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.3%    |
| WDC WD5000BPVT-75HXZT3 500GB            | 1         | 0.3%    |
| WDC WD5000AAKX-22ERMA0 500GB            | 1         | 0.3%    |
| WDC WD5000AAKX-221CA1 500GB             | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 53     | 33.61%  |
| Toshiba             | 26        | 40     | 21.31%  |
| WDC                 | 21        | 32     | 17.21%  |
| Hitachi             | 13        | 14     | 10.66%  |
| HGST                | 10        | 12     | 8.2%    |
| Samsung Electronics | 5         | 6      | 4.1%    |
| Fujitsu             | 3         | 3      | 2.46%   |
| Apple               | 2         | 2      | 1.64%   |
| Unknown             | 1         | 1      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 28     | 17.69%  |
| Kingston            | 22        | 26     | 16.92%  |
| SanDisk             | 19        | 19     | 14.62%  |
| Crucial             | 19        | 22     | 14.62%  |
| WDC                 | 10        | 10     | 7.69%   |
| Intel               | 6         | 6      | 4.62%   |
| A-DATA Technology   | 4         | 5      | 3.08%   |
| Toshiba             | 2         | 2      | 1.54%   |
| PNY                 | 2         | 2      | 1.54%   |
| Patriot             | 2         | 2      | 1.54%   |
| Apple               | 2         | 2      | 1.54%   |
| WDC WDS             | 1         | 1      | 0.77%   |
| V-GeN               | 1         | 1      | 0.77%   |
| Transcend           | 1         | 1      | 0.77%   |
| TO Exter            | 1         | 1      | 0.77%   |
| Star                | 1         | 1      | 0.77%   |
| SPCC                | 1         | 1      | 0.77%   |
| SK hynix            | 1         | 1      | 0.77%   |
| OWC                 | 1         | 1      | 0.77%   |
| OCZ                 | 1         | 2      | 0.77%   |
| NGFF                | 1         | 1      | 0.77%   |
| Micron Technology   | 1         | 2      | 0.77%   |
| LITEON              | 1         | 1      | 0.77%   |
| KingSpec            | 1         | 1      | 0.77%   |
| Hewlett-Packard     | 1         | 1      | 0.77%   |
| GOODRAM             | 1         | 2      | 0.77%   |
| Gigabyte Technology | 1         | 1      | 0.77%   |
| GeIL                | 1         | 1      | 0.77%   |
| EMTEC               | 1         | 1      | 0.77%   |
| China               | 1         | 1      | 0.77%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 110       | 146    | 39.57%  |
| HDD     | 107       | 163    | 38.49%  |
| NVMe    | 43        | 58     | 15.47%  |
| MMC     | 17        | 21     | 6.12%   |
| Unknown | 1         | 1      | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 183       | 299    | 72.91%  |
| NVMe | 42        | 57     | 16.73%  |
| MMC  | 17        | 21     | 6.77%   |
| SAS  | 9         | 12     | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 207    | 67.12%  |
| 0.51-1.0   | 59        | 79     | 26.94%  |
| 1.01-2.0   | 8         | 14     | 3.65%   |
| 4.01-10.0  | 3         | 3      | 1.37%   |
| 2.01-3.0   | 2         | 6      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 33.62%  |
| 251-500        | 64        | 27.95%  |
| 501-1000       | 27        | 11.79%  |
| 51-100         | 18        | 7.86%   |
| 21-50          | 15        | 6.55%   |
| 1001-2000      | 10        | 4.37%   |
| More than 3000 | 7         | 3.06%   |
| 2001-3000      | 5         | 2.18%   |
| 1-20           | 5         | 2.18%   |
| Unknown        | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 76        | 32.2%   |
| 21-50          | 58        | 24.58%  |
| 101-250        | 33        | 13.98%  |
| 51-100         | 33        | 13.98%  |
| 251-500        | 13        | 5.51%   |
| 501-1000       | 11        | 4.66%   |
| 1001-2000      | 5         | 2.12%   |
| More than 3000 | 3         | 1.27%   |
| 2001-3000      | 3         | 1.27%   |
| Unknown        | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| HGST                | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 183       | 313    | 78.21%  |
| Works    | 40        | 65     | 17.09%  |
| Malfunc  | 11        | 11     | 4.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 162       | 63.78%  |
| AMD                          | 33        | 12.99%  |
| Samsung Electronics          | 13        | 5.12%   |
| SanDisk                      | 10        | 3.94%   |
| Nvidia                       | 8         | 3.15%   |
| Toshiba America Info Systems | 5         | 1.97%   |
| Kingston Technology Company  | 5         | 1.97%   |
| KIOXIA                       | 3         | 1.18%   |
| JMicron Technology           | 3         | 1.18%   |
| ASMedia Technology           | 3         | 1.18%   |
| SK hynix                     | 2         | 0.79%   |
| ADATA Technology             | 2         | 0.79%   |
| Silicon Image                | 1         | 0.39%   |
| Seagate Technology           | 1         | 0.39%   |
| Phison Electronics           | 1         | 0.39%   |
| Micron Technology            | 1         | 0.39%   |
| Marvell Technology Group     | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24        | 8.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 18        | 6.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 5.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 4.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 3.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 2.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 2.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 2.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.38%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.38%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4         | 1.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 1.03%   |
| SanDisk PC SN520 NVMe SSD                                                               | 3         | 1.03%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 3         | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.03%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.69%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.69%   |
| Nvidia MCP89 SATA Controller                                                            | 2         | 0.69%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.69%   |
| JMicron JMB368 IDE controller                                                           | 2         | 0.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.69%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.69%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2         | 0.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 0.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 0.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 0.69%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.69%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.69%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 0.34%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.34%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1         | 0.34%   |
| Seagate FireCuda 510 SSD                                                                | 1         | 0.34%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.34%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 168       | 64.86%  |
| NVMe | 43        | 16.6%   |
| IDE  | 32        | 12.36%  |
| RAID | 16        | 6.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 185       | 82.59%  |
| AMD    | 39        | 17.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 2.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.79%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.34%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.34%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 1.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.34%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.34%   |
| Intel Core i5-3330S CPU @ 2.70GHz             | 3         | 1.34%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.34%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.34%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.34%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 2         | 0.89%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.89%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.89%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.89%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 2         | 0.89%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 2         | 0.89%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.89%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2         | 0.89%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.89%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.89%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.89%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.89%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 2         | 0.89%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 0.89%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 0.89%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 0.89%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.89%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 0.89%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.89%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.89%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.89%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.89%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.89%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.89%   |
| AMD FX-6100 Six-Core Processor                | 2         | 0.89%   |
| Intel Xeon CPU E31230 @ 3.20GHz               | 1         | 0.45%   |
| Intel Xeon CPU E31225 @ 3.10GHz               | 1         | 0.45%   |
| Intel Xeon CPU 5160 @ 3.00GHz                 | 1         | 0.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.45%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.45%   |
| Intel Pentium CPU G3258 @ 3.20GHz             | 1         | 0.45%   |
| Intel Genuine CPU U2700 @ 1.30GHz             | 1         | 0.45%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.45%   |
| Intel Core i7-9700KF CPU @ 3.60GHz            | 1         | 0.45%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.45%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.45%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.45%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.45%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 64        | 28.57%  |
| Intel Core i7                        | 41        | 18.3%   |
| Intel Core i3                        | 23        | 10.27%  |
| Intel Core 2 Duo                     | 14        | 6.25%   |
| Intel Celeron                        | 12        | 5.36%   |
| AMD Ryzen 5                          | 10        | 4.46%   |
| Intel Atom                           | 7         | 3.13%   |
| AMD Ryzen 7                          | 5         | 2.23%   |
| Other                                | 4         | 1.79%   |
| Intel Pentium Dual-Core              | 4         | 1.79%   |
| Intel Core 2 Quad                    | 4         | 1.79%   |
| Intel Core 2                         | 4         | 1.79%   |
| Intel Xeon                           | 3         | 1.34%   |
| Intel Pentium                        | 3         | 1.34%   |
| AMD Ryzen 3                          | 3         | 1.34%   |
| AMD Phenom II X4                     | 3         | 1.34%   |
| AMD A8                               | 3         | 1.34%   |
| AMD FX                               | 2         | 0.89%   |
| Intel Pentium Silver                 | 1         | 0.45%   |
| Intel Genuine                        | 1         | 0.45%   |
| Intel Core m3                        | 1         | 0.45%   |
| Intel Celeron Dual-Core              | 1         | 0.45%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.45%   |
| AMD Ryzen 9                          | 1         | 0.45%   |
| AMD Ryzen 5 PRO                      | 1         | 0.45%   |
| AMD Phenom                           | 1         | 0.45%   |
| AMD E1                               | 1         | 0.45%   |
| AMD C-60                             | 1         | 0.45%   |
| AMD Athlon II X4                     | 1         | 0.45%   |
| AMD Athlon II X3                     | 1         | 0.45%   |
| AMD A6                               | 1         | 0.45%   |
| AMD A4                               | 1         | 0.45%   |
| AMD A12                              | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 107       | 47.77%  |
| 4      | 92        | 41.07%  |
| 6      | 10        | 4.46%   |
| 8      | 5         | 2.23%   |
| 3      | 5         | 2.23%   |
| 1      | 4         | 1.79%   |
| 12     | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 223       | 99.55%  |
| 2      | 1         | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 133       | 59.38%  |
| 1      | 91        | 40.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 224       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 13.27%  |
| 0x306a9    | 22        | 9.73%   |
| 0x206a7    | 19        | 8.41%   |
| 0x1067a    | 16        | 7.08%   |
| 0x306c3    | 11        | 4.87%   |
| 0x40651    | 9         | 3.98%   |
| 0x806ec    | 7         | 3.1%    |
| 0x806e9    | 6         | 2.65%   |
| 0x706e5    | 6         | 2.65%   |
| 0x906ea    | 5         | 2.21%   |
| 0x806ea    | 5         | 2.21%   |
| 0x6f6      | 5         | 2.21%   |
| 0x406e3    | 5         | 2.21%   |
| 0x30678    | 5         | 2.21%   |
| 0x08108109 | 5         | 2.21%   |
| 0x906eb    | 4         | 1.77%   |
| 0x506e3    | 4         | 1.77%   |
| 0x706a1    | 3         | 1.33%   |
| 0x406c3    | 3         | 1.33%   |
| 0x306d4    | 3         | 1.33%   |
| 0x906e9    | 2         | 0.88%   |
| 0x806eb    | 2         | 0.88%   |
| 0x806c1    | 2         | 0.88%   |
| 0x20655    | 2         | 0.88%   |
| 0x20652    | 2         | 0.88%   |
| 0x106e5    | 2         | 0.88%   |
| 0x106ca    | 2         | 0.88%   |
| 0x10676    | 2         | 0.88%   |
| 0x08701021 | 2         | 0.88%   |
| 0x08108102 | 2         | 0.88%   |
| 0x0810100b | 2         | 0.88%   |
| 0x06006705 | 2         | 0.88%   |
| 0x0600063e | 2         | 0.88%   |
| 0x05000119 | 2         | 0.88%   |
| 0x010000db | 2         | 0.88%   |
| 0x010000c8 | 2         | 0.88%   |
| 0x906ed    | 1         | 0.44%   |
| 0x906ec    | 1         | 0.44%   |
| 0x6fd      | 1         | 0.44%   |
| 0x6fb      | 1         | 0.44%   |
| 0x406c4    | 1         | 0.44%   |
| 0x40661    | 1         | 0.44%   |
| 0x30673    | 1         | 0.44%   |
| 0x08701013 | 1         | 0.44%   |
| 0x08600106 | 1         | 0.44%   |
| 0x08600104 | 1         | 0.44%   |
| 0x08101016 | 1         | 0.44%   |
| 0x0800820d | 1         | 0.44%   |
| 0x08001137 | 1         | 0.44%   |
| 0x08001129 | 1         | 0.44%   |
| 0x07030105 | 1         | 0.44%   |
| 0x0600611a | 1         | 0.44%   |
| 0x06006118 | 1         | 0.44%   |
| 0x06003106 | 1         | 0.44%   |
| 0x06001119 | 1         | 0.44%   |
| 0x02000057 | 1         | 0.44%   |
| 0x01000083 | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 40        | 17.86%  |
| IvyBridge       | 24        | 10.71%  |
| Haswell         | 24        | 10.71%  |
| SandyBridge     | 21        | 9.38%   |
| Penryn          | 20        | 8.93%   |
| Silvermont      | 13        | 5.8%    |
| Skylake         | 10        | 4.46%   |
| Core            | 9         | 4.02%   |
| Zen+            | 8         | 3.57%   |
| IceLake         | 7         | 3.13%   |
| Zen 2           | 6         | 2.68%   |
| Zen             | 6         | 2.68%   |
| K10             | 6         | 2.68%   |
| Excavator       | 5         | 2.23%   |
| Westmere        | 4         | 1.79%   |
| Goldmont plus   | 4         | 1.79%   |
| Broadwell       | 3         | 1.34%   |
| TigerLake       | 2         | 0.89%   |
| Nehalem         | 2         | 0.89%   |
| Bulldozer       | 2         | 0.89%   |
| Bonnell         | 2         | 0.89%   |
| Bobcat          | 2         | 0.89%   |
| Steamroller     | 1         | 0.45%   |
| Puma            | 1         | 0.45%   |
| Piledriver      | 1         | 0.45%   |
| K8 & K10 hybrid | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 148       | 58.96%  |
| Nvidia | 53        | 21.12%  |
| AMD    | 50        | 19.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 6.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 5.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.23%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 3.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.69%   |
| Intel HD Graphics 620                                                                    | 7         | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 2.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3         | 1.15%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 3         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.15%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.15%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 1.15%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.15%   |
| AMD Renoir                                                                               | 3         | 1.15%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.77%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.77%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.77%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.77%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.77%   |
| Intel HD Graphics 530                                                                    | 2         | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.77%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.77%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.77%   |
| AMD RS880 [Radeon HD 4200]                                                               | 2         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.38%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.38%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1         | 0.38%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.38%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.38%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.38%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.38%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.38%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.38%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1         | 0.38%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.38%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.38%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.38%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 121       | 54.02%  |
| 1 x AMD        | 46        | 20.54%  |
| 1 x Nvidia     | 30        | 13.39%  |
| Intel + Nvidia | 22        | 9.82%   |
| 2 x AMD        | 2         | 0.89%   |
| Intel + AMD    | 2         | 0.89%   |
| 2 x Nvidia     | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 180       | 80.36%  |
| Proprietary | 36        | 16.07%  |
| Unknown     | 8         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 56.44%  |
| 1.01-2.0   | 36        | 16%     |
| 0.01-0.5   | 24        | 10.67%  |
| 0.51-1.0   | 16        | 7.11%   |
| 3.01-4.0   | 11        | 4.89%   |
| 7.01-8.0   | 8         | 3.56%   |
| 5.01-6.0   | 2         | 0.89%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 28        | 11.81%  |
| AU Optronics            | 27        | 11.39%  |
| BOE                     | 25        | 10.55%  |
| LG Display              | 24        | 10.13%  |
| Chimei Innolux          | 22        | 9.28%   |
| Dell                    | 17        | 7.17%   |
| Apple                   | 14        | 5.91%   |
| Goldstar                | 9         | 3.8%    |
| Chi Mei Optoelectronics | 6         | 2.53%   |
| AOC                     | 6         | 2.53%   |
| Unknown                 | 5         | 2.11%   |
| Sharp                   | 5         | 2.11%   |
| Hewlett-Packard         | 5         | 2.11%   |
| Ancor Communications    | 5         | 2.11%   |
| Acer                    | 5         | 2.11%   |
| BenQ                    | 4         | 1.69%   |
| ViewSonic               | 3         | 1.27%   |
| PANDA                   | 3         | 1.27%   |
| LG Electronics          | 3         | 1.27%   |
| Fujitsu Siemens         | 3         | 1.27%   |
| ___                     | 2         | 0.84%   |
| Lenovo                  | 2         | 0.84%   |
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
| Haier                   | 1         | 0.42%   |
| Unknown                 | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                     | 3         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 1.24%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 3         | 1.24%   |
| ___ LCD TV ___0101 1360x768                                              | 2         | 0.83%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 0.83%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.83%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.83%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 0.83%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 2         | 0.83%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                       | 1         | 0.41%   |
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
| Samsung Electronics U28E510 SAM0D63 3840x2160 607x345mm 27.5-inch        | 1         | 0.41%   |
| Samsung Electronics T27C370 SAM0ADE 1920x1080 598x336mm 27.0-inch        | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 459x296mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0560 1440x900 408x255mm 18.9-inch      | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 1         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch     | 1         | 0.41%   |
| Samsung Electronics LS32R75 SAM0F92 3840x2160 697x392mm 31.5-inch        | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                        | 1         | 0.41%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 0.41%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                    | 1         | 0.41%   |
| Ruijiang HDMI RJT003A 1920x1080 800x480mm 36.7-inch                      | 1         | 0.41%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 1         | 0.41%   |
| PDA P24FA2 PDA2380 1920x1080 409x230mm 18.5-inch                         | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 80        | 34.93%  |
| 1366x768 (WXGA)    | 59        | 25.76%  |
| 1600x900 (HD+)     | 17        | 7.42%   |
| 1280x800 (WXGA)    | 13        | 5.68%   |
| 3840x2160 (4K)     | 11        | 4.8%    |
| 2560x1440 (QHD)    | 6         | 2.62%   |
| 1680x1050 (WSXGA+) | 5         | 2.18%   |
| 1440x900 (WXGA+)   | 5         | 2.18%   |
| 1280x1024 (SXGA)   | 4         | 1.75%   |
| Unknown            | 4         | 1.75%   |
| 1920x1200 (WUXGA)  | 3         | 1.31%   |
| 1600x1200          | 3         | 1.31%   |
| 3440x1440          | 2         | 0.87%   |
| 2560x1600          | 2         | 0.87%   |
| 1024x600           | 2         | 0.87%   |
| 5120x1440          | 1         | 0.44%   |
| 3968x1280          | 1         | 0.44%   |
| 3840x1080          | 1         | 0.44%   |
| 3600x1080          | 1         | 0.44%   |
| 2880x1800          | 1         | 0.44%   |
| 2288x1287          | 1         | 0.44%   |
| 2256x1504          | 1         | 0.44%   |
| 2048x1152          | 1         | 0.44%   |
| 1920x515           | 1         | 0.44%   |
| 1920x1280          | 1         | 0.44%   |
| 1680x945           | 1         | 0.44%   |
| 1360x768           | 1         | 0.44%   |
| 1024x768 (XGA)     | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 49        | 20.59%  |
| 13      | 42        | 17.65%  |
| Unknown | 21        | 8.82%   |
| 14      | 19        | 7.98%   |
| 24      | 12        | 5.04%   |
| 17      | 12        | 5.04%   |
| 27      | 10        | 4.2%    |
| 19      | 10        | 4.2%    |
| 21      | 9         | 3.78%   |
| 23      | 8         | 3.36%   |
| 20      | 8         | 3.36%   |
| 11      | 7         | 2.94%   |
| 18      | 5         | 2.1%    |
| 84      | 3         | 1.26%   |
| 72      | 3         | 1.26%   |
| 31      | 3         | 1.26%   |
| 22      | 3         | 1.26%   |
| 10      | 3         | 1.26%   |
| 32      | 2         | 0.84%   |
| 29      | 2         | 0.84%   |
| 12      | 2         | 0.84%   |
| 57      | 1         | 0.42%   |
| 38      | 1         | 0.42%   |
| 34      | 1         | 0.42%   |
| 33      | 1         | 0.42%   |
| 16      | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 40%     |
| 201-300     | 31        | 13.48%  |
| 401-500     | 28        | 12.17%  |
| 501-600     | 26        | 11.3%   |
| Unknown     | 21        | 9.13%   |
| 351-400     | 14        | 6.09%   |
| 601-700     | 6         | 2.61%   |
| 1501-2000   | 6         | 2.61%   |
| 701-800     | 4         | 1.74%   |
| 801-900     | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 152       | 71.7%   |
| 16/10   | 27        | 12.74%  |
| Unknown | 19        | 8.96%   |
| 5/4     | 5         | 2.36%   |
| 4/3     | 4         | 1.89%   |
| 3/2     | 3         | 1.42%   |
| 3.73    | 1         | 0.47%   |
| 21/9    | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 50        | 21.46%  |
| 101-110        | 50        | 21.46%  |
| 201-250        | 26        | 11.16%  |
| Unknown        | 21        | 9.01%   |
| 151-200        | 16        | 6.87%   |
| 71-80          | 11        | 4.72%   |
| 301-350        | 10        | 4.29%   |
| 351-500        | 9         | 3.86%   |
| 141-150        | 8         | 3.43%   |
| More than 1000 | 7         | 3%      |
| 51-60          | 7         | 3%      |
| 121-130        | 6         | 2.58%   |
| 41-50          | 3         | 1.29%   |
| 251-300        | 3         | 1.29%   |
| 131-140        | 3         | 1.29%   |
| 61-70          | 2         | 0.86%   |
| 501-1000       | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 81        | 36.16%  |
| 51-100        | 53        | 23.66%  |
| 121-160       | 51        | 22.77%  |
| Unknown       | 21        | 9.38%   |
| 161-240       | 11        | 4.91%   |
| 1-50          | 5         | 2.23%   |
| More than 240 | 2         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 183       | 80.26%  |
| 2     | 33        | 14.47%  |
| 0     | 8         | 3.51%   |
| 3     | 4         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 117       | 34.11%  |
| Intel                             | 100       | 29.15%  |
| Qualcomm Atheros                  | 50        | 14.58%  |
| Broadcom                          | 30        | 8.75%   |
| Nvidia                            | 8         | 2.33%   |
| TP-Link                           | 5         | 1.46%   |
| Marvell Technology Group          | 4         | 1.17%   |
| Broadcom Limited                  | 4         | 1.17%   |
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
| Fibocom                           | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| BUFFALO                           | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |
| Arduino SA                        | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 80        | 19.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 20        | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 11        | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 1.99%   |
| Intel Wireless 7260                                                                   | 8         | 1.99%   |
| Intel Wireless 8260                                                                   | 7         | 1.74%   |
| Intel Wi-Fi 6 AX200                                                                   | 7         | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 1.49%   |
| Intel Ethernet Connection I218-LM                                                     | 5         | 1.24%   |
| Intel Centrino Advanced-N 6235                                                        | 5         | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 4         | 0.99%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 0.99%   |
| Intel Wireless 7265                                                                   | 4         | 0.99%   |
| Intel I211 Gigabit Network Connection                                                 | 4         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                                  | 4         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 0.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 4         | 0.99%   |
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
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 3         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 3         | 0.74%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                           | 2         | 0.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 2         | 0.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 2         | 0.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 2         | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 0.5%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 2         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 2         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.5%    |
| Nvidia MCP89 Ethernet                                                                 | 2         | 0.5%    |
| Intel Wireless-AC 9260                                                                | 2         | 0.5%    |
| Intel Wireless 3160                                                                   | 2         | 0.5%    |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 38%     |
| Qualcomm Atheros                | 44        | 22%     |
| Realtek Semiconductor           | 34        | 17%     |
| Broadcom                        | 25        | 12.5%   |
| TP-Link                         | 5         | 2.5%    |
| Broadcom Limited                | 4         | 2%      |
| Ralink                          | 3         | 1.5%    |
| D-Link                          | 2         | 1%      |
| Sierra Wireless                 | 1         | 0.5%    |
| Ralink Technology               | 1         | 0.5%    |
| Qualcomm Atheros Communications | 1         | 0.5%    |
| Microsoft                       | 1         | 0.5%    |
| Fibocom                         | 1         | 0.5%    |
| D-Link System                   | 1         | 0.5%    |
| BUFFALO                         | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 4.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 3.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 8         | 3.98%   |
| Intel Wireless 7260                                                                   | 8         | 3.98%   |
| Intel Wireless 8260                                                                   | 7         | 3.48%   |
| Intel Wi-Fi 6 AX200                                                                   | 7         | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 2.99%   |
| Intel Centrino Advanced-N 6235                                                        | 5         | 2.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 4         | 1.99%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.99%   |
| Intel Wireless 7265                                                                   | 4         | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 1.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 1.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 4         | 1.99%   |
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
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 2         | 1%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 2         | 1%      |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 2         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 1%      |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 2         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 1%      |
| Intel Wireless-AC 9260                                                                | 2         | 1%      |
| Intel Wireless 3160                                                                   | 2         | 1%      |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 2         | 1%      |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 2         | 1%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 2         | 1%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.5%    |
| TP-Link 802.11ac WLAN Adapter                                                         | 1         | 0.5%    |
| Sierra Wireless MC7700                                                                | 1         | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.5%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 0.5%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.5%    |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 0.5%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1         | 0.5%    |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 104       | 52.79%  |
| Intel                    | 50        | 25.38%  |
| Qualcomm Atheros         | 11        | 5.58%   |
| Broadcom                 | 9         | 4.57%   |
| Nvidia                   | 8         | 4.06%   |
| Marvell Technology Group | 4         | 2.03%   |
| Samsung Electronics      | 2         | 1.02%   |
| Huawei Technologies      | 2         | 1.02%   |
| Xiaomi                   | 1         | 0.51%   |
| VIA Technologies         | 1         | 0.51%   |
| Qualcomm                 | 1         | 0.51%   |
| LG Electronics           | 1         | 0.51%   |
| Hewlett-Packard          | 1         | 0.51%   |
| Google                   | 1         | 0.51%   |
| ASIX Electronics         | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5.5%    |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 4         | 2%      |
| Intel Ethernet Connection (2) I219-V                              | 4         | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.5%    |
| Nvidia MCP79 Ethernet                                             | 3         | 1.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 1.5%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.5%    |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.5%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.5%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1%      |
| Nvidia MCP89 Ethernet                                             | 2         | 1%      |
| Intel 82578DM Gigabit Network Connection                          | 2         | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.5%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.5%    |
| Qualcomm BENGAL-QRD _SN:C5464635                                  | 1         | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.5%    |
| Nvidia MCP77 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP55 Ethernet                                             | 1         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.5%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.5%    |
| Intel 82566DC Gigabit Network Connection                          | 1         | 0.5%    |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.5%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 0.5%    |
| Huawei LYA-L09                                                    | 1         | 0.5%    |
| Huawei E353/E3131                                                 | 1         | 0.5%    |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.5%    |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.5%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.5%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.5%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 49.74%  |
| Ethernet | 191       | 49.74%  |
| Modem    | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 70.74%  |
| Ethernet | 67        | 29.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 135       | 60%     |
| 1     | 78        | 34.67%  |
| 0     | 6         | 2.67%   |
| 3     | 5         | 2.22%   |
| 4     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 198       | 88.39%  |
| Yes  | 26        | 11.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 39.22%  |
| Cambridge Silicon Radio         | 15        | 9.8%    |
| Apple                           | 15        | 9.8%    |
| Qualcomm Atheros Communications | 14        | 9.15%   |
| Realtek Semiconductor           | 12        | 7.84%   |
| Lite-On Technology              | 8         | 5.23%   |
| Broadcom                        | 8         | 5.23%   |
| Toshiba                         | 3         | 1.96%   |
| IMC Networks                    | 3         | 1.96%   |
| Hewlett-Packard                 | 3         | 1.96%   |
| Foxconn / Hon Hai               | 3         | 1.96%   |
| ASUSTek Computer                | 2         | 1.31%   |
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

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 25        | 16.34%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 15        | 9.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 6.54%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 5.88%   |
| Intel AX201 Bluetooth                                                               | 8         | 5.23%   |
| Intel AX200 Bluetooth                                                               | 7         | 4.58%   |
| Apple Bluetooth Host Controller                                                     | 7         | 4.58%   |
| Realtek Bluetooth Radio                                                             | 6         | 3.92%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.27%   |
| Intel Bluetooth Device                                                              | 4         | 2.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.96%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.96%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.96%   |
| Apple Bluetooth HCI                                                                 | 3         | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.31%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.31%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.31%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.31%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.65%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.65%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.65%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.65%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.65%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.65%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.65%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.65%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.65%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.65%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.65%   |
| Fujitsu Bluetooth Device                                                            | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.65%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.65%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.65%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.65%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 174       | 60.84%  |
| AMD                        | 53        | 18.53%  |
| Nvidia                     | 39        | 13.64%  |
| C-Media Electronics        | 7         | 2.45%   |
| JMTek                      | 3         | 1.05%   |
| Generalplus Technology     | 3         | 1.05%   |
| YUAN High-Tech Development | 1         | 0.35%   |
| Texas Instruments          | 1         | 0.35%   |
| Native Instruments         | 1         | 0.35%   |
| Hewlett-Packard            | 1         | 0.35%   |
| Fortemedia                 | 1         | 0.35%   |
| Dell                       | 1         | 0.35%   |
| Astro Gaming               | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 6.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 6.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 6.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 4.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 3.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 2.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 2.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.76%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.17%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.17%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.88%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.88%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.88%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.88%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.88%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.59%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.59%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.59%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.59%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.59%   |
| YUAN High-Tech Development YUAN FM100                                                             | 1         | 0.29%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.29%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.29%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.29%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia MCP55 High Definition Audio                                                                | 1         | 0.29%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.29%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.29%   |
| Nvidia GM200 High Definition Audio                                                                | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


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

![Memory Model](./images/pie_chart/memory_model.svg)


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
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 1         | 0.74%   |
| Unknown (0x198) RAM Module 8GB SODIMM DDR3 1867MT/s              | 1         | 0.74%   |
| Timetec RAM SD4-2666 32GB SODIMM DDR4 2667MT/s                   | 1         | 0.74%   |
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
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.74%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.74%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.74%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.74%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.74%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 0.74%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 0.74%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 0.74%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 0.74%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


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

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 71.43%  |
| DIMM         | 24        | 22.86%  |
| Row Of Chips | 5         | 4.76%   |
| FB-DIMM      | 1         | 0.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 40        | 32.79%  |
| 8192  | 39        | 31.97%  |
| 2048  | 24        | 19.67%  |
| 16384 | 11        | 9.02%   |
| 1024  | 7         | 5.74%   |
| 32768 | 1         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


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

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 62.5%   |
| Seiko Epson        | 1         | 12.5%   |
| Canon              | 1         | 12.5%   |
| Brother Industries | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 21.94%  |
| Realtek Semiconductor                  | 20        | 12.9%   |
| IMC Networks                           | 15        | 9.68%   |
| Apple                                  | 11        | 7.1%    |
| Sunplus Innovation Technology          | 10        | 6.45%   |
| Acer                                   | 9         | 5.81%   |
| Microdia                               | 8         | 5.16%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.87%   |
| Silicon Motion                         | 5         | 3.23%   |
| Quanta                                 | 5         | 3.23%   |
| Logitech                               | 5         | 3.23%   |
| Syntek                                 | 4         | 2.58%   |
| Suyin                                  | 3         | 1.94%   |
| Lite-On Technology                     | 3         | 1.94%   |
| Importek                               | 3         | 1.94%   |
| Samsung Electronics                    | 2         | 1.29%   |
| LG Electronics                         | 2         | 1.29%   |
| Alcor Micro                            | 2         | 1.29%   |
| Z-Star Microelectronics                | 1         | 0.65%   |
| Ricoh                                  | 1         | 0.65%   |
| Microsoft                              | 1         | 0.65%   |
| KYE Systems (Mouse Systems)            | 1         | 0.65%   |
| Jieli Technology                       | 1         | 0.65%   |
| Generalplus Technology                 | 1         | 0.65%   |
| Cubeternet                             | 1         | 0.65%   |
| ALi                                    | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                          | 9         | 5.81%   |
| Chicony Integrated Camera                             | 6         | 3.87%   |
| Chicony HD WebCam                                     | 6         | 3.87%   |
| Apple Built-in iSight                                 | 5         | 3.23%   |
| Logitech HD Pro Webcam C920                           | 4         | 2.58%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 4         | 2.58%   |
| IMC Networks Integrated Camera                        | 4         | 2.58%   |
| Sunplus HD WebCam                                     | 3         | 1.94%   |
| Realtek HD WebCam                                     | 3         | 1.94%   |
| Apple iPhone 5/5C/5S/6/SE                             | 3         | 1.94%   |
| Syntek Integrated Camera                              | 2         | 1.29%   |
| Syntek EasyCamera                                     | 2         | 1.29%   |
| Sunplus Laptop_Integrated_Webcam_HD                   | 2         | 1.29%   |
| Sunplus Integrated_Webcam_HD                          | 2         | 1.29%   |
| Samsung Galaxy A5 (MTP)                               | 2         | 1.29%   |
| Realtek USB Camera                                    | 2         | 1.29%   |
| Quanta HP Webcam                                      | 2         | 1.29%   |
| Microdia Integrated_Webcam_HD                         | 2         | 1.29%   |
| Lite-On HP HD Camera                                  | 2         | 1.29%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2         | 1.29%   |
| Importek TOSHIBA Web Camera - HD                      | 2         | 1.29%   |
| Chicony HP Wide Vision HD Camera                      | 2         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101  | 2         | 1.29%   |
| Acer SunplusIT INC. Integrated Camera                 | 2         | 1.29%   |
| Acer BisonCam, NB Pro                                 | 2         | 1.29%   |
| Z-Star Venus USB2.0 Camera                            | 1         | 0.65%   |
| Suyin UVC HD Webcam                                   | 1         | 0.65%   |
| Suyin HP Truevision HD                                | 1         | 0.65%   |
| Suyin HD Video WebCam                                 | 1         | 0.65%   |
| Sunplus HP Universal Camera                           | 1         | 0.65%   |
| Sunplus Dell HD Webcam                                | 1         | 0.65%   |
| Sunplus Dell E5570 integrated webcam                  | 1         | 0.65%   |
| Silicon Motion WebCam SC-13HDL12131N                  | 1         | 0.65%   |
| Silicon Motion WebCam SC-10HDD12636N                  | 1         | 0.65%   |
| Silicon Motion Web Camera                             | 1         | 0.65%   |
| Silicon Motion Lenovo EasyCamera                      | 1         | 0.65%   |
| Silicon Motion HP Webcam-101 Integrated Camera        | 1         | 0.65%   |
| Ricoh USB2.0 Camera                                   | 1         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                          | 1         | 0.65%   |
| Realtek Integrated Webcam HD                          | 1         | 0.65%   |
| Realtek Integrated Webcam                             | 1         | 0.65%   |
| Realtek HP Webcam                                     | 1         | 0.65%   |
| Realtek HD Webcam - Realtek                           | 1         | 0.65%   |
| Realtek 2SF001                                        | 1         | 0.65%   |
| Quanta LG Webcam                                      | 1         | 0.65%   |
| Quanta HP Wide Vision HD Camera                       | 1         | 0.65%   |
| Quanta HP HD Camera                                   | 1         | 0.65%   |
| Microsoft LifeCam VX-2000                             | 1         | 0.65%   |
| Microdia WebCam SC-13HDL12639P                        | 1         | 0.65%   |
| Microdia USB 2.0 Camera                               | 1         | 0.65%   |
| Microdia Sonix USB 2.0 Camera                         | 1         | 0.65%   |
| Microdia Integrated Webcam                            | 1         | 0.65%   |
| Microdia HP Webcam                                    | 1         | 0.65%   |
| Microdia Amcrest AWC2198 USB Webcam                   | 1         | 0.65%   |
| Logitech Webcam C270                                  | 1         | 0.65%   |
| Lite-On Integrated Camera                             | 1         | 0.65%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera      | 1         | 0.65%   |
| Jieli USB PHY 2.0                                     | 1         | 0.65%   |
| Importek FJ Camera                                    | 1         | 0.65%   |
| IMC Networks UVC VGA Webcam                           | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 167       | 73.25%  |
| 1     | 50        | 21.93%  |
| 2     | 8         | 3.51%   |
| 3     | 3         | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


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


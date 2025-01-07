Linux in Vietnam - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Vietnam/Desktop/README.md) and [notebooks](/Location/Vietnam/Notebook/README.md).

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

Total: 1008

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Precision M4800             | Notebook    | [7c360180e7](https://linux-hardware.org/?probe=7c360180e7) | Jan 04, 2025 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [2a6b25b609](https://linux-hardware.org/?probe=2a6b25b609) | Jan 02, 2025 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [5029ac1a06](https://linux-hardware.org/?probe=5029ac1a06) | Jan 01, 2025 |
| Dell          | Precision M4800             | Notebook    | [4e3bd9cbb4](https://linux-hardware.org/?probe=4e3bd9cbb4) | Jan 01, 2025 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5f6888e1a9](https://linux-hardware.org/?probe=5f6888e1a9) | Dec 30, 2024 |
| HP            | 212B                        | Desktop     | [3ddbe304f3](https://linux-hardware.org/?probe=3ddbe304f3) | Dec 29, 2024 |
| HP            | 212B                        | Desktop     | [d64fe3acb0](https://linux-hardware.org/?probe=d64fe3acb0) | Dec 29, 2024 |
| Dell          | Precision 7540              | Notebook    | [314c747e45](https://linux-hardware.org/?probe=314c747e45) | Dec 28, 2024 |
| Dell          | Precision 7540              | Notebook    | [4535a9d79b](https://linux-hardware.org/?probe=4535a9d79b) | Dec 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0971785105](https://linux-hardware.org/?probe=0971785105) | Dec 26, 2024 |
| HP            | 805A                        | Desktop     | [d55f3bc8c3](https://linux-hardware.org/?probe=d55f3bc8c3) | Dec 26, 2024 |
| Dell          | Latitude E5550              | Notebook    | [2512980572](https://linux-hardware.org/?probe=2512980572) | Dec 25, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [c02f6f4421](https://linux-hardware.org/?probe=c02f6f4421) | Dec 23, 2024 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [467d5bf559](https://linux-hardware.org/?probe=467d5bf559) | Dec 22, 2024 |
| Dell          | Latitude 7390               | Notebook    | [d446a06dc6](https://linux-hardware.org/?probe=d446a06dc6) | Dec 18, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d76388f034](https://linux-hardware.org/?probe=d76388f034) | Dec 16, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [00eb10a377](https://linux-hardware.org/?probe=00eb10a377) | Dec 16, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | Notebook    | [063c4b21a8](https://linux-hardware.org/?probe=063c4b21a8) | Dec 16, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [5d556ab3f4](https://linux-hardware.org/?probe=5d556ab3f4) | Dec 16, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [eb47c05bbb](https://linux-hardware.org/?probe=eb47c05bbb) | Dec 15, 2024 |
| Dell          | Latitude 7390               | Notebook    | [7c762c0713](https://linux-hardware.org/?probe=7c762c0713) | Dec 13, 2024 |
| Acer          | Aspire TC-780               | Desktop     | [63e18470f5](https://linux-hardware.org/?probe=63e18470f5) | Dec 12, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [8638d65417](https://linux-hardware.org/?probe=8638d65417) | Dec 12, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [e39b84b016](https://linux-hardware.org/?probe=e39b84b016) | Dec 11, 2024 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [704c8bef39](https://linux-hardware.org/?probe=704c8bef39) | Dec 05, 2024 |
| Dell          | Inspiron 3443               | Notebook    | [73ce4e96f5](https://linux-hardware.org/?probe=73ce4e96f5) | Dec 01, 2024 |
| Dell          | Inspiron 3442               | Notebook    | [8354433195](https://linux-hardware.org/?probe=8354433195) | Dec 01, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [f3ade75c2d](https://linux-hardware.org/?probe=f3ade75c2d) | Nov 30, 2024 |
| Lenovo        | ThinkPad P53 20QN002LUS     | Notebook    | [c4bb47dc8d](https://linux-hardware.org/?probe=c4bb47dc8d) | Nov 30, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [f2e869dbea](https://linux-hardware.org/?probe=f2e869dbea) | Nov 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | Notebook    | [59205e96b5](https://linux-hardware.org/?probe=59205e96b5) | Nov 25, 2024 |
| Lenovo        | ThinkPad P50 20EQA0HFJP     | Notebook    | [c9a5d2852f](https://linux-hardware.org/?probe=c9a5d2852f) | Nov 25, 2024 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [75382d8ea9](https://linux-hardware.org/?probe=75382d8ea9) | Nov 22, 2024 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [96e07ce0c5](https://linux-hardware.org/?probe=96e07ce0c5) | Nov 19, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [05ecf2c89a](https://linux-hardware.org/?probe=05ecf2c89a) | Nov 17, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [48169a4553](https://linux-hardware.org/?probe=48169a4553) | Nov 17, 2024 |
| MSI           | B760M GAMING PLUS WIFI      | Desktop     | [2e86962422](https://linux-hardware.org/?probe=2e86962422) | Nov 14, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6adb8dd712](https://linux-hardware.org/?probe=6adb8dd712) | Nov 14, 2024 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [333961be54](https://linux-hardware.org/?probe=333961be54) | Nov 14, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [42c31d1a6b](https://linux-hardware.org/?probe=42c31d1a6b) | Nov 13, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [57bdc97b57](https://linux-hardware.org/?probe=57bdc97b57) | Nov 12, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [780ff233ce](https://linux-hardware.org/?probe=780ff233ce) | Nov 09, 2024 |
| Lenovo        | ThinkPad X230 23243MU       | Notebook    | [b9aa89f4af](https://linux-hardware.org/?probe=b9aa89f4af) | Nov 09, 2024 |
| Dell          | Vostro 3560                 | Notebook    | [b832b01843](https://linux-hardware.org/?probe=b832b01843) | Nov 07, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5d7f9f6298](https://linux-hardware.org/?probe=5d7f9f6298) | Nov 06, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [77f61a6e57](https://linux-hardware.org/?probe=77f61a6e57) | Nov 04, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [0e03e2a67c](https://linux-hardware.org/?probe=0e03e2a67c) | Nov 03, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [43e8b9cd73](https://linux-hardware.org/?probe=43e8b9cd73) | Oct 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [1d73e46912](https://linux-hardware.org/?probe=1d73e46912) | Oct 27, 2024 |
| Ugoos         | AM6 Plus                    | Soc         | [82aa145536](https://linux-hardware.org/?probe=82aa145536) | Oct 23, 2024 |
| Lenovo        | ThinkPad P50 20EQA0HFJP     | Notebook    | [de0dff32ba](https://linux-hardware.org/?probe=de0dff32ba) | Oct 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [0d286dd3ac](https://linux-hardware.org/?probe=0d286dd3ac) | Oct 22, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [758143fbc9](https://linux-hardware.org/?probe=758143fbc9) | Oct 21, 2024 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [998331b0b5](https://linux-hardware.org/?probe=998331b0b5) | Oct 16, 2024 |
| Unknown       | Oranth Tanix TX3 Mini       | Soc         | [93676b1ece](https://linux-hardware.org/?probe=93676b1ece) | Oct 16, 2024 |
| Gigabyte      | Z490 GAMING X AX            | Desktop     | [e726c70ed6](https://linux-hardware.org/?probe=e726c70ed6) | Oct 16, 2024 |
| Unknown       | Oranth Tanix TX3 Mini (D... | Soc         | [770d64f945](https://linux-hardware.org/?probe=770d64f945) | Oct 15, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [de44b9af7c](https://linux-hardware.org/?probe=de44b9af7c) | Oct 15, 2024 |
| MSI           | H310-F PRO                  | Desktop     | [96e06666bd](https://linux-hardware.org/?probe=96e06666bd) | Oct 15, 2024 |
| Unknown       | Oranth Tanix TX3 Mini       | Soc         | [cbd216c912](https://linux-hardware.org/?probe=cbd216c912) | Oct 13, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [bb0bf00fc4](https://linux-hardware.org/?probe=bb0bf00fc4) | Oct 12, 2024 |
| Dell          | Vostro 3578                 | Notebook    | [d523995b93](https://linux-hardware.org/?probe=d523995b93) | Oct 12, 2024 |
| Dell          | Latitude E5450              | Notebook    | [c7bea876cf](https://linux-hardware.org/?probe=c7bea876cf) | Oct 12, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [0df50eaff2](https://linux-hardware.org/?probe=0df50eaff2) | Oct 12, 2024 |
| HP            | 81C6 MVB 0C                 | Server      | [21781753fb](https://linux-hardware.org/?probe=21781753fb) | Oct 09, 2024 |
| Dell          | Precision 5530              | Notebook    | [19bfbd7cdb](https://linux-hardware.org/?probe=19bfbd7cdb) | Oct 09, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [78f8401511](https://linux-hardware.org/?probe=78f8401511) | Oct 07, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [53f89517eb](https://linux-hardware.org/?probe=53f89517eb) | Oct 06, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [b54ffcadc5](https://linux-hardware.org/?probe=b54ffcadc5) | Oct 06, 2024 |
| Intel         | JGINYUE X99 TITANIUM D4     | Desktop     | [aecb4037b0](https://linux-hardware.org/?probe=aecb4037b0) | Oct 05, 2024 |
| Intel         | X99                         | Desktop     | [68f2b63233](https://linux-hardware.org/?probe=68f2b63233) | Oct 04, 2024 |
| HP            | ProBook 440 G7              | Notebook    | [0b63cd25e3](https://linux-hardware.org/?probe=0b63cd25e3) | Sep 27, 2024 |
| Acer          | Aspire A715-41G             | Notebook    | [28630e6b4e](https://linux-hardware.org/?probe=28630e6b4e) | Sep 26, 2024 |
| Lenovo        | ThinkPad T460s 20F9003CU... | Notebook    | [839431acb4](https://linux-hardware.org/?probe=839431acb4) | Sep 23, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [ceef2c6eb0](https://linux-hardware.org/?probe=ceef2c6eb0) | Sep 21, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [7a41c29a03](https://linux-hardware.org/?probe=7a41c29a03) | Sep 21, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [8aa81f0f7f](https://linux-hardware.org/?probe=8aa81f0f7f) | Sep 21, 2024 |
| HP            | ZBook Power 16 inch G11 ... | Notebook    | [07a4fb8d0d](https://linux-hardware.org/?probe=07a4fb8d0d) | Sep 20, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [c4777b62e2](https://linux-hardware.org/?probe=c4777b62e2) | Sep 19, 2024 |
| Dell          | Latitude 7390               | Notebook    | [90063dd1b7](https://linux-hardware.org/?probe=90063dd1b7) | Sep 18, 2024 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [4b8c75fca8](https://linux-hardware.org/?probe=4b8c75fca8) | Sep 17, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [878fec3180](https://linux-hardware.org/?probe=878fec3180) | Sep 14, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [aa5be70d5f](https://linux-hardware.org/?probe=aa5be70d5f) | Sep 13, 2024 |
| Dell          | Latitude 7390               | Notebook    | [738fbe7846](https://linux-hardware.org/?probe=738fbe7846) | Sep 11, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [0b9b93c40f](https://linux-hardware.org/?probe=0b9b93c40f) | Sep 09, 2024 |
| Dell          | G5 5500                     | Notebook    | [047302a678](https://linux-hardware.org/?probe=047302a678) | Sep 08, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [41d8287678](https://linux-hardware.org/?probe=41d8287678) | Sep 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [2a1feab9bf](https://linux-hardware.org/?probe=2a1feab9bf) | Sep 08, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [7a1624219e](https://linux-hardware.org/?probe=7a1624219e) | Sep 07, 2024 |
| Dell          | Latitude E6420              | Notebook    | [31212512fd](https://linux-hardware.org/?probe=31212512fd) | Sep 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [acc91bcc92](https://linux-hardware.org/?probe=acc91bcc92) | Aug 30, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [c3e7f8694f](https://linux-hardware.org/?probe=c3e7f8694f) | Aug 28, 2024 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [ba17ccfdcf](https://linux-hardware.org/?probe=ba17ccfdcf) | Aug 27, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [6984d83894](https://linux-hardware.org/?probe=6984d83894) | Aug 27, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f8c21d6744](https://linux-hardware.org/?probe=f8c21d6744) | Aug 26, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [313fd9a175](https://linux-hardware.org/?probe=313fd9a175) | Aug 26, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [24e8669ec3](https://linux-hardware.org/?probe=24e8669ec3) | Aug 26, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [260ef44eec](https://linux-hardware.org/?probe=260ef44eec) | Aug 26, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9211ef9b2d](https://linux-hardware.org/?probe=9211ef9b2d) | Aug 26, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ff7e8dcdfe](https://linux-hardware.org/?probe=ff7e8dcdfe) | Aug 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [1bc687932f](https://linux-hardware.org/?probe=1bc687932f) | Aug 23, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7 82S0    | Notebook    | [d8dd107aff](https://linux-hardware.org/?probe=d8dd107aff) | Aug 22, 2024 |
| ASUSTek       | Z10PA-D8 Series             | Desktop     | [9d140d5c3a](https://linux-hardware.org/?probe=9d140d5c3a) | Aug 22, 2024 |
| CompuLab      | SBC-ATCFL                   | Mini pc     | [dd34549add](https://linux-hardware.org/?probe=dd34549add) | Aug 21, 2024 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [ada714905a](https://linux-hardware.org/?probe=ada714905a) | Aug 19, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [8728a5c10a](https://linux-hardware.org/?probe=8728a5c10a) | Aug 17, 2024 |
| ASUSTek       | NUC14SRB 60AS0050-MB4B11    | Mini pc     | [23d1ff7d6d](https://linux-hardware.org/?probe=23d1ff7d6d) | Aug 15, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [647b4d4e05](https://linux-hardware.org/?probe=647b4d4e05) | Aug 14, 2024 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [b15b7f542f](https://linux-hardware.org/?probe=b15b7f542f) | Aug 13, 2024 |
| Acer          | Aspire A715-72G             | Notebook    | [ee80d11d07](https://linux-hardware.org/?probe=ee80d11d07) | Aug 12, 2024 |
| Dell          | Latitude 7480               | Notebook    | [29eb3942e4](https://linux-hardware.org/?probe=29eb3942e4) | Aug 11, 2024 |
| ASRock        | B360M Pro4                  | Desktop     | [617db99564](https://linux-hardware.org/?probe=617db99564) | Aug 10, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [e1801d006d](https://linux-hardware.org/?probe=e1801d006d) | Aug 09, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [c118336b8d](https://linux-hardware.org/?probe=c118336b8d) | Aug 08, 2024 |
| ASUSTek       | X455LA                      | Notebook    | [37e0171c30](https://linux-hardware.org/?probe=37e0171c30) | Aug 07, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [ae01578889](https://linux-hardware.org/?probe=ae01578889) | Aug 06, 2024 |
| Chuwi         | CoreBook X                  | Notebook    | [bcdc21a44e](https://linux-hardware.org/?probe=bcdc21a44e) | Aug 05, 2024 |
| Acer          | Aspire TC-780               | Desktop     | [01c38d4980](https://linux-hardware.org/?probe=01c38d4980) | Aug 04, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [96287a3827](https://linux-hardware.org/?probe=96287a3827) | Aug 04, 2024 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [16f8415d51](https://linux-hardware.org/?probe=16f8415d51) | Aug 03, 2024 |
| Dell          | 0MG3PY A00                  | Desktop     | [558c13f467](https://linux-hardware.org/?probe=558c13f467) | Aug 01, 2024 |
| Unknown       | Oranth Tanix TX3 Mini       | Soc         | [425c8faf25](https://linux-hardware.org/?probe=425c8faf25) | Jul 30, 2024 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [d996c69b4e](https://linux-hardware.org/?probe=d996c69b4e) | Jul 30, 2024 |
| Dell          | 05XGC8 A00                  | Desktop     | [3ee39cf10c](https://linux-hardware.org/?probe=3ee39cf10c) | Jul 29, 2024 |
| Dell          | 05XGC8 A00                  | Desktop     | [6e047a60ce](https://linux-hardware.org/?probe=6e047a60ce) | Jul 29, 2024 |
| Dell          | Vostro 3578                 | Notebook    | [c7238c32a7](https://linux-hardware.org/?probe=c7238c32a7) | Jul 29, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [c59c94dc80](https://linux-hardware.org/?probe=c59c94dc80) | Jul 28, 2024 |
| Dell          | Vostro 5468                 | Notebook    | [6f51e95a13](https://linux-hardware.org/?probe=6f51e95a13) | Jul 26, 2024 |
| HP            | ProBook 440 G7              | Notebook    | [aafd504745](https://linux-hardware.org/?probe=aafd504745) | Jul 24, 2024 |
| Shenzhen M... | F7BSD                       | Mini pc     | [9a4f052566](https://linux-hardware.org/?probe=9a4f052566) | Jul 23, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [9d6e1306ec](https://linux-hardware.org/?probe=9d6e1306ec) | Jul 23, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [8786c187fc](https://linux-hardware.org/?probe=8786c187fc) | Jul 17, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d7fcdc7953](https://linux-hardware.org/?probe=d7fcdc7953) | Jul 16, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [1542766bdd](https://linux-hardware.org/?probe=1542766bdd) | Jul 15, 2024 |
| Dell          | Latitude 7390               | Notebook    | [ddb7685bf1](https://linux-hardware.org/?probe=ddb7685bf1) | Jul 12, 2024 |
| OrangePi      | NEO-01                      | Notebook    | [bf07a0e349](https://linux-hardware.org/?probe=bf07a0e349) | Jul 12, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [8cabf59fdb](https://linux-hardware.org/?probe=8cabf59fdb) | Jul 12, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [1c31a4cfc4](https://linux-hardware.org/?probe=1c31a4cfc4) | Jul 11, 2024 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [a7dd8bc9c0](https://linux-hardware.org/?probe=a7dd8bc9c0) | Jul 10, 2024 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [1102b424c6](https://linux-hardware.org/?probe=1102b424c6) | Jul 08, 2024 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [395d619b53](https://linux-hardware.org/?probe=395d619b53) | Jul 08, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [4dcce43f80](https://linux-hardware.org/?probe=4dcce43f80) | Jul 02, 2024 |
| MSI           | Creator M16 A12UC           | Notebook    | [4b9de6f7b6](https://linux-hardware.org/?probe=4b9de6f7b6) | Jun 30, 2024 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [d03de18ca4](https://linux-hardware.org/?probe=d03de18ca4) | Jun 28, 2024 |
| Gigabyte      | B75M-HD3                    | Desktop     | [9e9ebd16d8](https://linux-hardware.org/?probe=9e9ebd16d8) | Jun 25, 2024 |
| Gigabyte      | B75M-HD3                    | Desktop     | [2bd6383e6f](https://linux-hardware.org/?probe=2bd6383e6f) | Jun 25, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f9cbea829f](https://linux-hardware.org/?probe=f9cbea829f) | Jun 24, 2024 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [25535547a0](https://linux-hardware.org/?probe=25535547a0) | Jun 23, 2024 |
| OrangePi      | NEO-01                      | Notebook    | [da69fb6377](https://linux-hardware.org/?probe=da69fb6377) | Jun 23, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [49737ebb77](https://linux-hardware.org/?probe=49737ebb77) | Jun 22, 2024 |
| HP            | Pavilion dv7                | Notebook    | [d2bf7bbc79](https://linux-hardware.org/?probe=d2bf7bbc79) | Jun 21, 2024 |
| OrangePi      | NEO-01                      | Notebook    | [4341aee209](https://linux-hardware.org/?probe=4341aee209) | Jun 19, 2024 |
| Intel         | X99                         | Desktop     | [10c3f9bb20](https://linux-hardware.org/?probe=10c3f9bb20) | Jun 12, 2024 |
| Lenovo        | ThinkPad P50 20EQA0HFJP     | Notebook    | [25a9a5fbab](https://linux-hardware.org/?probe=25a9a5fbab) | Jun 11, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [9a70731554](https://linux-hardware.org/?probe=9a70731554) | Jun 10, 2024 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [f839c2d656](https://linux-hardware.org/?probe=f839c2d656) | Jun 08, 2024 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [c948245a1e](https://linux-hardware.org/?probe=c948245a1e) | Jun 08, 2024 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [56f86f1288](https://linux-hardware.org/?probe=56f86f1288) | Jun 08, 2024 |
| Sony          | SVE14132CVB                 | Notebook    | [1d1b0f6b07](https://linux-hardware.org/?probe=1d1b0f6b07) | Jun 07, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [a2da3535f1](https://linux-hardware.org/?probe=a2da3535f1) | Jun 06, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [d1313b1f24](https://linux-hardware.org/?probe=d1313b1f24) | Jun 06, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [2c5b454002](https://linux-hardware.org/?probe=2c5b454002) | Jun 04, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [b57a2d7747](https://linux-hardware.org/?probe=b57a2d7747) | Jun 04, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [860b682ea7](https://linux-hardware.org/?probe=860b682ea7) | Jun 03, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [b08f59e8eb](https://linux-hardware.org/?probe=b08f59e8eb) | Jun 02, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1e9b9b0333](https://linux-hardware.org/?probe=1e9b9b0333) | May 28, 2024 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [270ea43e27](https://linux-hardware.org/?probe=270ea43e27) | May 27, 2024 |
| MSI           | B150M MORTAR                | Desktop     | [384ea70cf9](https://linux-hardware.org/?probe=384ea70cf9) | May 27, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [868fba5b46](https://linux-hardware.org/?probe=868fba5b46) | May 27, 2024 |
| HP            | 86E9 A                      | Desktop     | [d9acdfe5be](https://linux-hardware.org/?probe=d9acdfe5be) | May 27, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [bcb50afa3b](https://linux-hardware.org/?probe=bcb50afa3b) | May 27, 2024 |
| Alienware     | M17xR4                      | Notebook    | [a5147b08e6](https://linux-hardware.org/?probe=a5147b08e6) | May 26, 2024 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [3f73958526](https://linux-hardware.org/?probe=3f73958526) | May 26, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2c36f9b7bf](https://linux-hardware.org/?probe=2c36f9b7bf) | May 26, 2024 |
| HP            | EliteBook 1030 G1           | Notebook    | [2dc4e838a9](https://linux-hardware.org/?probe=2dc4e838a9) | May 25, 2024 |
| HP            | 212B                        | Desktop     | [5ff9cbc231](https://linux-hardware.org/?probe=5ff9cbc231) | May 23, 2024 |
| HP            | 212B                        | Desktop     | [434d87ae89](https://linux-hardware.org/?probe=434d87ae89) | May 23, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [73f9290f9b](https://linux-hardware.org/?probe=73f9290f9b) | May 22, 2024 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [43fc99d75b](https://linux-hardware.org/?probe=43fc99d75b) | May 21, 2024 |
| MSI           | Katana GF76 12UE            | Notebook    | [c9597611ab](https://linux-hardware.org/?probe=c9597611ab) | May 19, 2024 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [dfcc1413eb](https://linux-hardware.org/?probe=dfcc1413eb) | May 19, 2024 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [bec9fb0dce](https://linux-hardware.org/?probe=bec9fb0dce) | May 17, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [829e0a0d70](https://linux-hardware.org/?probe=829e0a0d70) | May 16, 2024 |
| MSI           | Katana GF76 12UE            | Notebook    | [4ddec0f62b](https://linux-hardware.org/?probe=4ddec0f62b) | May 15, 2024 |
| Lenovo        | ThinkPad T470 20HD000VUS    | Notebook    | [1453bbda09](https://linux-hardware.org/?probe=1453bbda09) | May 15, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [15d30912cf](https://linux-hardware.org/?probe=15d30912cf) | May 13, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a5031a990b](https://linux-hardware.org/?probe=a5031a990b) | May 10, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1400CBA... | Notebook    | [3a81cd6b2e](https://linux-hardware.org/?probe=3a81cd6b2e) | May 09, 2024 |
| MASSCOM VI... | L133                        | Notebook    | [12b6c6b515](https://linux-hardware.org/?probe=12b6c6b515) | May 06, 2024 |
| Acer          | Aspire A715-41G             | Notebook    | [b24efb4449](https://linux-hardware.org/?probe=b24efb4449) | May 06, 2024 |
| Acer          | Aspire A715-41G             | Notebook    | [aa9c440102](https://linux-hardware.org/?probe=aa9c440102) | May 01, 2024 |
| Dell          | G7 7588                     | Notebook    | [9745a22fe0](https://linux-hardware.org/?probe=9745a22fe0) | Apr 28, 2024 |
| Dell          | Latitude E5450              | Notebook    | [575668e003](https://linux-hardware.org/?probe=575668e003) | Apr 26, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [3e1d481314](https://linux-hardware.org/?probe=3e1d481314) | Apr 26, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [81b0d669d9](https://linux-hardware.org/?probe=81b0d669d9) | Apr 26, 2024 |
| HP            | Compaq 6520s                | Notebook    | [235863713b](https://linux-hardware.org/?probe=235863713b) | Apr 25, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [cf3db9398d](https://linux-hardware.org/?probe=cf3db9398d) | Apr 22, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [6eeb53e317](https://linux-hardware.org/?probe=6eeb53e317) | Apr 22, 2024 |
| AZW           | MINI S 10                   | Desktop     | [ae2d077638](https://linux-hardware.org/?probe=ae2d077638) | Apr 22, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [50f7cbb79a](https://linux-hardware.org/?probe=50f7cbb79a) | Apr 19, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [09c22645d8](https://linux-hardware.org/?probe=09c22645d8) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [a2fb569143](https://linux-hardware.org/?probe=a2fb569143) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [b70a3e9c9f](https://linux-hardware.org/?probe=b70a3e9c9f) | Apr 19, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [5357679252](https://linux-hardware.org/?probe=5357679252) | Apr 18, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [13af7544f2](https://linux-hardware.org/?probe=13af7544f2) | Apr 17, 2024 |
| Dell          | G7 7588                     | Notebook    | [06f5f64e59](https://linux-hardware.org/?probe=06f5f64e59) | Apr 14, 2024 |
| Dell          | Latitude E5570              | Notebook    | [91db6ada79](https://linux-hardware.org/?probe=91db6ada79) | Apr 13, 2024 |
| Dell          | 0D28YY A03                  | Desktop     | [894b628494](https://linux-hardware.org/?probe=894b628494) | Apr 12, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [1c61456dc2](https://linux-hardware.org/?probe=1c61456dc2) | Apr 11, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [c595905fcb](https://linux-hardware.org/?probe=c595905fcb) | Apr 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [05372f86e5](https://linux-hardware.org/?probe=05372f86e5) | Apr 10, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8b430e632f](https://linux-hardware.org/?probe=8b430e632f) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [bf43ad7ffe](https://linux-hardware.org/?probe=bf43ad7ffe) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [25dc9ad19d](https://linux-hardware.org/?probe=25dc9ad19d) | Apr 08, 2024 |
| Dell          | G7 7588                     | Notebook    | [8753ea1302](https://linux-hardware.org/?probe=8753ea1302) | Apr 05, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [bbb0e8daf4](https://linux-hardware.org/?probe=bbb0e8daf4) | Apr 02, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [d60c1ed904](https://linux-hardware.org/?probe=d60c1ed904) | Apr 02, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [5d12c5c26e](https://linux-hardware.org/?probe=5d12c5c26e) | Mar 31, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [142a42435b](https://linux-hardware.org/?probe=142a42435b) | Mar 30, 2024 |
| Lenovo        | Legion Pro 5 16IRX9 83DF    | Notebook    | [5457b4ef4c](https://linux-hardware.org/?probe=5457b4ef4c) | Mar 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S0HG00    | Notebook    | [f80e544ce6](https://linux-hardware.org/?probe=f80e544ce6) | Mar 22, 2024 |
| BBEN          | Cherry Trail CR             | Mini pc     | [ee5a042182](https://linux-hardware.org/?probe=ee5a042182) | Mar 19, 2024 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [99e78f54fd](https://linux-hardware.org/?probe=99e78f54fd) | Mar 18, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a13b1aaa4d](https://linux-hardware.org/?probe=a13b1aaa4d) | Mar 18, 2024 |
| Lenovo        | XiaoXinPro 14 AHP9 83D3     | Notebook    | [468b8047e4](https://linux-hardware.org/?probe=468b8047e4) | Mar 15, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [af8cc61afe](https://linux-hardware.org/?probe=af8cc61afe) | Mar 14, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ba3ec85a8c](https://linux-hardware.org/?probe=ba3ec85a8c) | Mar 14, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [7cddb85911](https://linux-hardware.org/?probe=7cddb85911) | Mar 14, 2024 |
| Gigabyte      | G5 GD                       | Notebook    | [58ac2082b9](https://linux-hardware.org/?probe=58ac2082b9) | Mar 11, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [22f1633f40](https://linux-hardware.org/?probe=22f1633f40) | Mar 09, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [17ef9e97c9](https://linux-hardware.org/?probe=17ef9e97c9) | Mar 06, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [b68f17fbdf](https://linux-hardware.org/?probe=b68f17fbdf) | Mar 02, 2024 |
| MSI           | Modern 14 B11SBU            | Notebook    | [5a5e7d82d7](https://linux-hardware.org/?probe=5a5e7d82d7) | Feb 29, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [565e6c2d46](https://linux-hardware.org/?probe=565e6c2d46) | Feb 29, 2024 |
| Apple         | MacBookPro13,3              | Notebook    | [f6a0a37d75](https://linux-hardware.org/?probe=f6a0a37d75) | Feb 20, 2024 |
| Gigabyte      | G5 KD                       | Notebook    | [0743c222ba](https://linux-hardware.org/?probe=0743c222ba) | Feb 20, 2024 |
| ASUSTek       | PRIME H510M-F               | Desktop     | [21e4b5ffeb](https://linux-hardware.org/?probe=21e4b5ffeb) | Feb 20, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [ae67d4e82a](https://linux-hardware.org/?probe=ae67d4e82a) | Feb 19, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [ba02f5d2ae](https://linux-hardware.org/?probe=ba02f5d2ae) | Feb 18, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [efd4bd356f](https://linux-hardware.org/?probe=efd4bd356f) | Feb 17, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [111c375a02](https://linux-hardware.org/?probe=111c375a02) | Feb 17, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [2fc996bace](https://linux-hardware.org/?probe=2fc996bace) | Feb 17, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [5b9d9efd21](https://linux-hardware.org/?probe=5b9d9efd21) | Feb 17, 2024 |
| Dell          | Inspiron 3576               | Notebook    | [740a10ea1f](https://linux-hardware.org/?probe=740a10ea1f) | Feb 15, 2024 |
| OrangePi      | NEO-01                      | Notebook    | [9999d229d6](https://linux-hardware.org/?probe=9999d229d6) | Feb 09, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [8dbe3ddfaa](https://linux-hardware.org/?probe=8dbe3ddfaa) | Feb 08, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [0e9a586cf0](https://linux-hardware.org/?probe=0e9a586cf0) | Feb 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [5cbf6ef1b5](https://linux-hardware.org/?probe=5cbf6ef1b5) | Feb 06, 2024 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [33ad82eafa](https://linux-hardware.org/?probe=33ad82eafa) | Feb 05, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [e591b9e544](https://linux-hardware.org/?probe=e591b9e544) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6acefbaadc](https://linux-hardware.org/?probe=6acefbaadc) | Feb 01, 2024 |
| MSI           | Creator M16 A12UC           | Notebook    | [804a70b7f5](https://linux-hardware.org/?probe=804a70b7f5) | Jan 31, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [ed474939eb](https://linux-hardware.org/?probe=ed474939eb) | Jan 31, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [021f108e72](https://linux-hardware.org/?probe=021f108e72) | Jan 31, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ac9d05a0b5](https://linux-hardware.org/?probe=ac9d05a0b5) | Jan 30, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [61d19fb0bc](https://linux-hardware.org/?probe=61d19fb0bc) | Jan 29, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [41cff556c1](https://linux-hardware.org/?probe=41cff556c1) | Jan 29, 2024 |
| Google        | Elemi                       | Notebook    | [f767c4fdbb](https://linux-hardware.org/?probe=f767c4fdbb) | Jan 28, 2024 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [a2c3ceeb83](https://linux-hardware.org/?probe=a2c3ceeb83) | Jan 25, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0996781568](https://linux-hardware.org/?probe=0996781568) | Jan 21, 2024 |
| COM1          | NBINF-O5-4R7R6              | Notebook    | [95df5c3aa3](https://linux-hardware.org/?probe=95df5c3aa3) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1284a92c36](https://linux-hardware.org/?probe=1284a92c36) | Jan 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [052a070a11](https://linux-hardware.org/?probe=052a070a11) | Jan 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1291da44c0](https://linux-hardware.org/?probe=1291da44c0) | Jan 14, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a7a7b48aa9](https://linux-hardware.org/?probe=a7a7b48aa9) | Jan 13, 2024 |
| Supermicro    | X10DRL-i                    | Desktop     | [874482c96c](https://linux-hardware.org/?probe=874482c96c) | Jan 10, 2024 |
| Supermicro    | X10DRL-i                    | Desktop     | [d51207de50](https://linux-hardware.org/?probe=d51207de50) | Jan 09, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [bde414f757](https://linux-hardware.org/?probe=bde414f757) | Jan 09, 2024 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [f23bf42f04](https://linux-hardware.org/?probe=f23bf42f04) | Jan 08, 2024 |
| Google        | Jinlon                      | Notebook    | [1d3ce76cf8](https://linux-hardware.org/?probe=1d3ce76cf8) | Jan 08, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [cd2d137285](https://linux-hardware.org/?probe=cd2d137285) | Jan 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [3274a6e444](https://linux-hardware.org/?probe=3274a6e444) | Jan 05, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [764d37dd86](https://linux-hardware.org/?probe=764d37dd86) | Jan 05, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [4254a865ee](https://linux-hardware.org/?probe=4254a865ee) | Jan 04, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [04de30dc4d](https://linux-hardware.org/?probe=04de30dc4d) | Jan 03, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | Notebook    | [389ae3afc8](https://linux-hardware.org/?probe=389ae3afc8) | Jan 02, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [939fe5ab0c](https://linux-hardware.org/?probe=939fe5ab0c) | Jan 02, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [e0aa5cc2d1](https://linux-hardware.org/?probe=e0aa5cc2d1) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [a97c12a4c8](https://linux-hardware.org/?probe=a97c12a4c8) | Dec 28, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [555b9489dd](https://linux-hardware.org/?probe=555b9489dd) | Dec 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [27856e6bb2](https://linux-hardware.org/?probe=27856e6bb2) | Dec 27, 2023 |
| Supermicro    | X11DAi-N                    | Server      | [6e0a7e9f92](https://linux-hardware.org/?probe=6e0a7e9f92) | Dec 27, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [9440079733](https://linux-hardware.org/?probe=9440079733) | Dec 27, 2023 |
| HP            | 86E9 A                      | Desktop     | [e373d2be5d](https://linux-hardware.org/?probe=e373d2be5d) | Dec 27, 2023 |
| Supermicro    | X11DAi-N                    | Server      | [9a681db276](https://linux-hardware.org/?probe=9a681db276) | Dec 27, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c179cdb6dc](https://linux-hardware.org/?probe=c179cdb6dc) | Dec 27, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [c7a5f771ce](https://linux-hardware.org/?probe=c7a5f771ce) | Dec 26, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [23577ab5f1](https://linux-hardware.org/?probe=23577ab5f1) | Dec 26, 2023 |
| HP            | 86E9 A                      | Desktop     | [c13adc0c5e](https://linux-hardware.org/?probe=c13adc0c5e) | Dec 26, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [09813a10ac](https://linux-hardware.org/?probe=09813a10ac) | Dec 26, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [9eff3f535e](https://linux-hardware.org/?probe=9eff3f535e) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a4efec2a2c](https://linux-hardware.org/?probe=a4efec2a2c) | Dec 19, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [74cbcabaa1](https://linux-hardware.org/?probe=74cbcabaa1) | Dec 17, 2023 |
| AYANEO        | 2                           | Tablet      | [78a21ff7fb](https://linux-hardware.org/?probe=78a21ff7fb) | Dec 16, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| ASUSTek       | K45VD                       | Notebook    | [527a669776](https://linux-hardware.org/?probe=527a669776) | Dec 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5a7d45a007](https://linux-hardware.org/?probe=5a7d45a007) | Dec 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2d6eaf642b](https://linux-hardware.org/?probe=2d6eaf642b) | Dec 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [52374a1dea](https://linux-hardware.org/?probe=52374a1dea) | Dec 03, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [34df3b2497](https://linux-hardware.org/?probe=34df3b2497) | Dec 02, 2023 |
| Dell          | Inspiron 1440               | Notebook    | [08b87da5fd](https://linux-hardware.org/?probe=08b87da5fd) | Nov 30, 2023 |
| Dell          | Inspiron 1440               | Notebook    | [7c28444086](https://linux-hardware.org/?probe=7c28444086) | Nov 29, 2023 |
| Gigabyte      | H310M DS2                   | Desktop     | [14a8656c8b](https://linux-hardware.org/?probe=14a8656c8b) | Nov 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [30bce064eb](https://linux-hardware.org/?probe=30bce064eb) | Nov 27, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [42271c5724](https://linux-hardware.org/?probe=42271c5724) | Nov 26, 2023 |
| HP            | 212B                        | Desktop     | [90bc0d4d2d](https://linux-hardware.org/?probe=90bc0d4d2d) | Nov 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [95b888d2b1](https://linux-hardware.org/?probe=95b888d2b1) | Nov 24, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [dbbf51e4c5](https://linux-hardware.org/?probe=dbbf51e4c5) | Nov 18, 2023 |
| Samsung       | 730QDA                      | Convertible | [3167fd276f](https://linux-hardware.org/?probe=3167fd276f) | Nov 17, 2023 |
| Samsung       | 730QDA                      | Convertible | [33aae4cfd4](https://linux-hardware.org/?probe=33aae4cfd4) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [95a4f9ff42](https://linux-hardware.org/?probe=95a4f9ff42) | Nov 14, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| Google        | Phaser360                   | Notebook    | [dbd0db9b7e](https://linux-hardware.org/?probe=dbd0db9b7e) | Nov 05, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [21b415bccc](https://linux-hardware.org/?probe=21b415bccc) | Nov 05, 2023 |
| Intel         | X99                         | Desktop     | [cb3515efba](https://linux-hardware.org/?probe=cb3515efba) | Nov 03, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e87403e608](https://linux-hardware.org/?probe=e87403e608) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [3e5415671f](https://linux-hardware.org/?probe=3e5415671f) | Nov 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [64e3601d4c](https://linux-hardware.org/?probe=64e3601d4c) | Oct 29, 2023 |
| Dell          | Latitude E5450              | Notebook    | [aebf2cd9fb](https://linux-hardware.org/?probe=aebf2cd9fb) | Oct 29, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [dcd6988b7a](https://linux-hardware.org/?probe=dcd6988b7a) | Oct 28, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [681e404df8](https://linux-hardware.org/?probe=681e404df8) | Oct 28, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [9854f25018](https://linux-hardware.org/?probe=9854f25018) | Oct 26, 2023 |
| BBEN          | Cherry Trail CR             | Mini pc     | [a37982a5e5](https://linux-hardware.org/?probe=a37982a5e5) | Oct 25, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [824215ab50](https://linux-hardware.org/?probe=824215ab50) | Oct 25, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8764daeeab](https://linux-hardware.org/?probe=8764daeeab) | Oct 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f06b99b2e](https://linux-hardware.org/?probe=4f06b99b2e) | Oct 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [62ca63bc89](https://linux-hardware.org/?probe=62ca63bc89) | Oct 23, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2b88710042](https://linux-hardware.org/?probe=2b88710042) | Oct 22, 2023 |
| Dell          | Latitude E6440              | Notebook    | [9db156fcaf](https://linux-hardware.org/?probe=9db156fcaf) | Oct 22, 2023 |
| HP            | Compaq 6520s                | Notebook    | [d010b05039](https://linux-hardware.org/?probe=d010b05039) | Oct 22, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [f77f7c8a16](https://linux-hardware.org/?probe=f77f7c8a16) | Oct 22, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a7f899353b](https://linux-hardware.org/?probe=a7f899353b) | Oct 21, 2023 |
| HP            | 15                          | Notebook    | [c85c40dbc8](https://linux-hardware.org/?probe=c85c40dbc8) | Oct 21, 2023 |
| HP            | 15                          | Notebook    | [95e8953601](https://linux-hardware.org/?probe=95e8953601) | Oct 21, 2023 |
| MSI           | Crosshair 15 B12UEZ         | Notebook    | [746189a3d8](https://linux-hardware.org/?probe=746189a3d8) | Oct 20, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [0875e69e22](https://linux-hardware.org/?probe=0875e69e22) | Oct 17, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9240952796](https://linux-hardware.org/?probe=9240952796) | Oct 16, 2023 |
| Dell          | Latitude 7330               | Notebook    | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| HP            | Notebook                    | Notebook    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29c7192a14](https://linux-hardware.org/?probe=29c7192a14) | Oct 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08bbfa9e1](https://linux-hardware.org/?probe=a08bbfa9e1) | Oct 07, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [171a2ad768](https://linux-hardware.org/?probe=171a2ad768) | Oct 04, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [63aededb0c](https://linux-hardware.org/?probe=63aededb0c) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [805cef3023](https://linux-hardware.org/?probe=805cef3023) | Oct 03, 2023 |
| Dell          | Inspiron 5583               | Notebook    | [c16bd909f3](https://linux-hardware.org/?probe=c16bd909f3) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | Notebook    | [11d6cad851](https://linux-hardware.org/?probe=11d6cad851) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | Notebook    | [84a0c8ea9b](https://linux-hardware.org/?probe=84a0c8ea9b) | Oct 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [76401b3ca2](https://linux-hardware.org/?probe=76401b3ca2) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [3e29eb1d63](https://linux-hardware.org/?probe=3e29eb1d63) | Sep 26, 2023 |
| ASRock        | A320M-HDV                   | Desktop     | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [b063bf9f1e](https://linux-hardware.org/?probe=b063bf9f1e) | Sep 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Dell          | Precision 7520              | Notebook    | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [4bf05e9eae](https://linux-hardware.org/?probe=4bf05e9eae) | Sep 17, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [b7c1a0a0a0](https://linux-hardware.org/?probe=b7c1a0a0a0) | Sep 16, 2023 |
| ASUSTek       | UX305FA                     | Notebook    | [e4ade39a1c](https://linux-hardware.org/?probe=e4ade39a1c) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [d1d5edf95c](https://linux-hardware.org/?probe=d1d5edf95c) | Sep 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [75ca1d0c52](https://linux-hardware.org/?probe=75ca1d0c52) | Sep 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [043d6c8d65](https://linux-hardware.org/?probe=043d6c8d65) | Sep 08, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [155023d91f](https://linux-hardware.org/?probe=155023d91f) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| ASUSTek       | EX-H110M-V3                 | Desktop     | [c38af5d04d](https://linux-hardware.org/?probe=c38af5d04d) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | Desktop     | [e2b97e4436](https://linux-hardware.org/?probe=e2b97e4436) | Aug 31, 2023 |
| Dell          | Vostro 1450                 | Notebook    | [1aad0f5aa3](https://linux-hardware.org/?probe=1aad0f5aa3) | Aug 26, 2023 |
| GuoGuang      | IC2M1028N                   | Desktop     | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Dell          | Latitude 7480               | Notebook    | [50bcada7d4](https://linux-hardware.org/?probe=50bcada7d4) | Aug 23, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [e00521ec88](https://linux-hardware.org/?probe=e00521ec88) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [882234a7b8](https://linux-hardware.org/?probe=882234a7b8) | Aug 22, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| HP            | 2000                        | Notebook    | [650a9a885c](https://linux-hardware.org/?probe=650a9a885c) | Aug 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [f52ceb7ab6](https://linux-hardware.org/?probe=f52ceb7ab6) | Aug 15, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| Acer          | Aspire V5-471G              | Notebook    | [1955354749](https://linux-hardware.org/?probe=1955354749) | Aug 11, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [b065632006](https://linux-hardware.org/?probe=b065632006) | Aug 08, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Dell          | System XPS L322X            | Notebook    | [dbe168d1a1](https://linux-hardware.org/?probe=dbe168d1a1) | Aug 02, 2023 |
| Alienware     | 13 R3                       | Notebook    | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [ece0a7a538](https://linux-hardware.org/?probe=ece0a7a538) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | Notebook    | [298fe52a60](https://linux-hardware.org/?probe=298fe52a60) | Jul 25, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [ae23c3b0d3](https://linux-hardware.org/?probe=ae23c3b0d3) | Jul 24, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | Notebook    | [4ec1a5c6fe](https://linux-hardware.org/?probe=4ec1a5c6fe) | Jul 22, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [fe9e1671cc](https://linux-hardware.org/?probe=fe9e1671cc) | Jul 20, 2023 |
| Dell          | Latitude 5580               | Notebook    | [6efcf73621](https://linux-hardware.org/?probe=6efcf73621) | Jul 19, 2023 |
| Dell          | Latitude 5580               | Notebook    | [16f62b67d3](https://linux-hardware.org/?probe=16f62b67d3) | Jul 17, 2023 |
| itel Mobil... | SPIRIT 1                    | Notebook    | [36c3d3f6a8](https://linux-hardware.org/?probe=36c3d3f6a8) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [d8310de68b](https://linux-hardware.org/?probe=d8310de68b) | Jul 12, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [851a3a00cf](https://linux-hardware.org/?probe=851a3a00cf) | Jul 05, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [0ffe35561e](https://linux-hardware.org/?probe=0ffe35561e) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7aaa5d2eec](https://linux-hardware.org/?probe=7aaa5d2eec) | Jul 03, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [2cd1962ee4](https://linux-hardware.org/?probe=2cd1962ee4) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef49f25cf8](https://linux-hardware.org/?probe=ef49f25cf8) | Jun 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6cc649e9ba](https://linux-hardware.org/?probe=6cc649e9ba) | Jun 29, 2023 |
| Lenovo        | ThinkPad T15g Gen1 20URC... | Notebook    | [e4c7449911](https://linux-hardware.org/?probe=e4c7449911) | Jun 27, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8454119675](https://linux-hardware.org/?probe=8454119675) | Jun 22, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ebedbde736](https://linux-hardware.org/?probe=ebedbde736) | Jun 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2754ddde7f](https://linux-hardware.org/?probe=2754ddde7f) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [d704e4a5d3](https://linux-hardware.org/?probe=d704e4a5d3) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bf2fc7d3b7](https://linux-hardware.org/?probe=bf2fc7d3b7) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [1b491bcfeb](https://linux-hardware.org/?probe=1b491bcfeb) | Jun 07, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [f1060e2b5d](https://linux-hardware.org/?probe=f1060e2b5d) | Jun 07, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [da21766a5c](https://linux-hardware.org/?probe=da21766a5c) | Jun 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | Notebook    | [8c16cec2e8](https://linux-hardware.org/?probe=8c16cec2e8) | Jun 01, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [d0a6a8e29e](https://linux-hardware.org/?probe=d0a6a8e29e) | May 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9c98caaf4](https://linux-hardware.org/?probe=b9c98caaf4) | May 13, 2023 |
| Dell          | G15 5520                    | Notebook    | [81024f3df4](https://linux-hardware.org/?probe=81024f3df4) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Supermicro    | X8DTL                       | Server      | [4d6836803f](https://linux-hardware.org/?probe=4d6836803f) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [7a7021d420](https://linux-hardware.org/?probe=7a7021d420) | May 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [ed0486cda1](https://linux-hardware.org/?probe=ed0486cda1) | May 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [e26aee893f](https://linux-hardware.org/?probe=e26aee893f) | May 01, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [21d008c7d8](https://linux-hardware.org/?probe=21d008c7d8) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [49557b8214](https://linux-hardware.org/?probe=49557b8214) | Apr 29, 2023 |
| Dell          | Latitude 7390               | Notebook    | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [b53354af62](https://linux-hardware.org/?probe=b53354af62) | Apr 25, 2023 |
| Intel         | H81                         | Desktop     | [fbc2766f35](https://linux-hardware.org/?probe=fbc2766f35) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [af72838c03](https://linux-hardware.org/?probe=af72838c03) | Apr 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85fa6bf3d5](https://linux-hardware.org/?probe=85fa6bf3d5) | Apr 21, 2023 |
| HP            | 1825                        | Desktop     | [e586a2657b](https://linux-hardware.org/?probe=e586a2657b) | Apr 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [82931a3c45](https://linux-hardware.org/?probe=82931a3c45) | Apr 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [ae048d3165](https://linux-hardware.org/?probe=ae048d3165) | Apr 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [c67c78ba10](https://linux-hardware.org/?probe=c67c78ba10) | Apr 11, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c56952417d](https://linux-hardware.org/?probe=c56952417d) | Apr 11, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [b67954cc59](https://linux-hardware.org/?probe=b67954cc59) | Apr 10, 2023 |
| Dell          | Latitude E6440              | Notebook    | [8153a28710](https://linux-hardware.org/?probe=8153a28710) | Apr 09, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [320195c782](https://linux-hardware.org/?probe=320195c782) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [3d59062866](https://linux-hardware.org/?probe=3d59062866) | Apr 06, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [81400b8912](https://linux-hardware.org/?probe=81400b8912) | Apr 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ea39081b01](https://linux-hardware.org/?probe=ea39081b01) | Apr 01, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e09dc41124](https://linux-hardware.org/?probe=e09dc41124) | Mar 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Dell          | Latitude 7290               | Notebook    | [576b8aa32a](https://linux-hardware.org/?probe=576b8aa32a) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [315750ea63](https://linux-hardware.org/?probe=315750ea63) | Mar 11, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [c45a0f2220](https://linux-hardware.org/?probe=c45a0f2220) | Mar 11, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [3cec8a7abc](https://linux-hardware.org/?probe=3cec8a7abc) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [219f16372b](https://linux-hardware.org/?probe=219f16372b) | Mar 03, 2023 |
| Samsung       | 930XDA                      | Notebook    | [684b448b3a](https://linux-hardware.org/?probe=684b448b3a) | Mar 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [4ead3fc236](https://linux-hardware.org/?probe=4ead3fc236) | Mar 03, 2023 |
| Dell          | Latitude 3400               | Notebook    | [2936e7f368](https://linux-hardware.org/?probe=2936e7f368) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [373f4f8123](https://linux-hardware.org/?probe=373f4f8123) | Feb 27, 2023 |
| Dell          | Precision M4600             | Notebook    | [901a8de667](https://linux-hardware.org/?probe=901a8de667) | Feb 24, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5fb951a350](https://linux-hardware.org/?probe=5fb951a350) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| Dell          | Precision M4600             | Notebook    | [2bdbf753b0](https://linux-hardware.org/?probe=2bdbf753b0) | Feb 21, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [12bb4f91ae](https://linux-hardware.org/?probe=12bb4f91ae) | Feb 20, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [a4404180b7](https://linux-hardware.org/?probe=a4404180b7) | Feb 20, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [420ccdfca6](https://linux-hardware.org/?probe=420ccdfca6) | Feb 07, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [cfcea0a331](https://linux-hardware.org/?probe=cfcea0a331) | Feb 05, 2023 |
| MSI           | Modern 14 B11SBU            | Notebook    | [50538fe8fd](https://linux-hardware.org/?probe=50538fe8fd) | Feb 05, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [8da4ffdd5c](https://linux-hardware.org/?probe=8da4ffdd5c) | Feb 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a7eba3e52d](https://linux-hardware.org/?probe=a7eba3e52d) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S3PV00    | Notebook    | [08f4e80cb9](https://linux-hardware.org/?probe=08f4e80cb9) | Feb 02, 2023 |
| HP            | 81B4                        | Desktop     | [01229ad5ec](https://linux-hardware.org/?probe=01229ad5ec) | Jan 29, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [b7971f413f](https://linux-hardware.org/?probe=b7971f413f) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0015U... | Notebook    | [1ece644fe1](https://linux-hardware.org/?probe=1ece644fe1) | Jan 04, 2023 |
| Dell          | Precision 3560              | Notebook    | [8cb8a3f5cf](https://linux-hardware.org/?probe=8cb8a3f5cf) | Jan 04, 2023 |
| Anbernic      | Win600                      | Notebook    | [db576ded28](https://linux-hardware.org/?probe=db576ded28) | Dec 29, 2022 |
| HP            | 158A                        | Desktop     | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c82ebf8b80](https://linux-hardware.org/?probe=c82ebf8b80) | Dec 26, 2022 |
| Anbernic      | Win600                      | Notebook    | [f7759a13d8](https://linux-hardware.org/?probe=f7759a13d8) | Dec 25, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b6ac9ce59](https://linux-hardware.org/?probe=3b6ac9ce59) | Dec 19, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470s 20HF0015U... | Notebook    | [3fd30db5e1](https://linux-hardware.org/?probe=3fd30db5e1) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [f82368713d](https://linux-hardware.org/?probe=f82368713d) | Dec 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [66635e6315](https://linux-hardware.org/?probe=66635e6315) | Dec 16, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| HP            | 350 G1                      | Notebook    | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Dell          | Latitude 7390               | Notebook    | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [324b5a49e4](https://linux-hardware.org/?probe=324b5a49e4) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [33113bb27d](https://linux-hardware.org/?probe=33113bb27d) | Nov 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [b19387a8f3](https://linux-hardware.org/?probe=b19387a8f3) | Nov 16, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [91268b9919](https://linux-hardware.org/?probe=91268b9919) | Nov 16, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [4adf740f59](https://linux-hardware.org/?probe=4adf740f59) | Nov 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [4b0ce24e6e](https://linux-hardware.org/?probe=4b0ce24e6e) | Nov 11, 2022 |
| Google        | Drallion                    | Notebook    | [7cb5922896](https://linux-hardware.org/?probe=7cb5922896) | Nov 10, 2022 |
| Dell          | G15 5511                    | Notebook    | [8a3246caed](https://linux-hardware.org/?probe=8a3246caed) | Nov 10, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [86f71fb0e6](https://linux-hardware.org/?probe=86f71fb0e6) | Nov 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| HP            | 212B                        | Desktop     | [adf4c58f4c](https://linux-hardware.org/?probe=adf4c58f4c) | Oct 22, 2022 |
| Gigabyte      | B360M DS3H                  | Desktop     | [ca57bb441c](https://linux-hardware.org/?probe=ca57bb441c) | Oct 18, 2022 |
| HP            | 158A                        | Desktop     | [6b1d53174a](https://linux-hardware.org/?probe=6b1d53174a) | Oct 12, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4... | Desktop     | [080242408d](https://linux-hardware.org/?probe=080242408d) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [1bff176b39](https://linux-hardware.org/?probe=1bff176b39) | Oct 05, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [403aa5af3e](https://linux-hardware.org/?probe=403aa5af3e) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | 158A                        | Desktop     | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Lenovo        | ThinkPad T450s 20BX005GU... | Notebook    | [5c41d03119](https://linux-hardware.org/?probe=5c41d03119) | Sep 15, 2022 |
| Intel         | S1200SP H57533-350          | Server      | [6e17cb41c9](https://linux-hardware.org/?probe=6e17cb41c9) | Sep 15, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [c07c5b31f6](https://linux-hardware.org/?probe=c07c5b31f6) | Sep 13, 2022 |
| HP            | Elite x2 1013 G3            | Tablet      | [25b64af3e9](https://linux-hardware.org/?probe=25b64af3e9) | Sep 13, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [7e840fc9d0](https://linux-hardware.org/?probe=7e840fc9d0) | Sep 12, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [4b728bc447](https://linux-hardware.org/?probe=4b728bc447) | Sep 12, 2022 |
| Dell          | 0VNM11 A00                  | Desktop     | [9ae0ae5ac4](https://linux-hardware.org/?probe=9ae0ae5ac4) | Sep 10, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [ecc2f4c975](https://linux-hardware.org/?probe=ecc2f4c975) | Sep 06, 2022 |
| MSI           | H410M PRO                   | Desktop     | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| HP            | 18E7                        | Desktop     | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [46c6096b6e](https://linux-hardware.org/?probe=46c6096b6e) | Aug 23, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [a3d9fca7aa](https://linux-hardware.org/?probe=a3d9fca7aa) | Aug 16, 2022 |
| HP            | 2AE2                        | Desktop     | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | Notebook    | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QM00     | Notebook    | [9779cc7396](https://linux-hardware.org/?probe=9779cc7396) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| ASUSTek       | K55A                        | Notebook    | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Dell          | G3 3500                     | Notebook    | [69f594bb80](https://linux-hardware.org/?probe=69f594bb80) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Toshiba       | dynabook Satellite B35/R    | Notebook    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| HP            | 8455                        | Desktop     | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| TENKU         | SB14                        | Notebook    | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6eb841aab1](https://linux-hardware.org/?probe=6eb841aab1) | Jun 21, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [58b312c382](https://linux-hardware.org/?probe=58b312c382) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [a8c7fc9c3a](https://linux-hardware.org/?probe=a8c7fc9c3a) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [63bc3a2ce5](https://linux-hardware.org/?probe=63bc3a2ce5) | May 27, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [09ba129a3b](https://linux-hardware.org/?probe=09ba129a3b) | May 25, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [9df127ec26](https://linux-hardware.org/?probe=9df127ec26) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [25b52955ee](https://linux-hardware.org/?probe=25b52955ee) | Apr 29, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [7499dbd303](https://linux-hardware.org/?probe=7499dbd303) | Apr 15, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [7bb124e322](https://linux-hardware.org/?probe=7bb124e322) | Apr 06, 2022 |
| Dell          | System Vostro 3450          | Notebook    | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [5dcc8e2cee](https://linux-hardware.org/?probe=5dcc8e2cee) | Mar 14, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [b20d7593ce](https://linux-hardware.org/?probe=b20d7593ce) | Mar 09, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| Dell          | System XPS L702X            | Notebook    | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [64f5921b5b](https://linux-hardware.org/?probe=64f5921b5b) | Feb 13, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [4834a3fe2e](https://linux-hardware.org/?probe=4834a3fe2e) | Feb 09, 2022 |
| Dell          | G3 3500                     | Notebook    | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [a95dfa8bc8](https://linux-hardware.org/?probe=a95dfa8bc8) | Jan 26, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | Notebook    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [5588a84fcf](https://linux-hardware.org/?probe=5588a84fcf) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [3b97b65258](https://linux-hardware.org/?probe=3b97b65258) | Jan 08, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [be7876abf4](https://linux-hardware.org/?probe=be7876abf4) | Jan 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [48cfc7d185](https://linux-hardware.org/?probe=48cfc7d185) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [cee5f081e3](https://linux-hardware.org/?probe=cee5f081e3) | Dec 19, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [297d964b96](https://linux-hardware.org/?probe=297d964b96) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [bd72de2067](https://linux-hardware.org/?probe=bd72de2067) | Dec 12, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [21d85302a2](https://linux-hardware.org/?probe=21d85302a2) | Dec 05, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [70c63b2fb6](https://linux-hardware.org/?probe=70c63b2fb6) | Dec 02, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [c5d4bf5c62](https://linux-hardware.org/?probe=c5d4bf5c62) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Timi          | A35S                        | Notebook    | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [fa62ac7a45](https://linux-hardware.org/?probe=fa62ac7a45) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [17781cb457](https://linux-hardware.org/?probe=17781cb457) | Nov 20, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [f4a646d1f8](https://linux-hardware.org/?probe=f4a646d1f8) | Nov 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [5471ce2e2f](https://linux-hardware.org/?probe=5471ce2e2f) | Nov 16, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a471ac5d59](https://linux-hardware.org/?probe=a471ac5d59) | Nov 07, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Dell          | Precision 7510              | Notebook    | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [370ad865cf](https://linux-hardware.org/?probe=370ad865cf) | Oct 31, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [f316c0a82e](https://linux-hardware.org/?probe=f316c0a82e) | Oct 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| Gigabyte      | EP43T-S3L                   | Desktop     | [8a1adefcb3](https://linux-hardware.org/?probe=8a1adefcb3) | Oct 20, 2021 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [603ccdfb84](https://linux-hardware.org/?probe=603ccdfb84) | Oct 19, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [7459a9ed47](https://linux-hardware.org/?probe=7459a9ed47) | Oct 18, 2021 |
| Dell          | Precision 7510              | Notebook    | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| HP            | Notebook                    | Notebook    | [6ac2c09585](https://linux-hardware.org/?probe=6ac2c09585) | Oct 09, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [c9fd6887d4](https://linux-hardware.org/?probe=c9fd6887d4) | Oct 06, 2021 |
| Acer          | Predator PH315-51           | Notebook    | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b1fb3d4e88](https://linux-hardware.org/?probe=b1fb3d4e88) | Oct 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fe4153e816](https://linux-hardware.org/?probe=fe4153e816) | Oct 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8b3b2655bb](https://linux-hardware.org/?probe=8b3b2655bb) | Oct 03, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [d8cde7951e](https://linux-hardware.org/?probe=d8cde7951e) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Dell          | Latitude 3520               | Notebook    | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| HP            | 15                          | Notebook    | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Sony          | SVE14A15FGW                 | Notebook    | [f1049f7db1](https://linux-hardware.org/?probe=f1049f7db1) | Sep 21, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | GF62 7RD                    | Notebook    | [5a35b145a9](https://linux-hardware.org/?probe=5a35b145a9) | Aug 19, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [df3d4bfff1](https://linux-hardware.org/?probe=df3d4bfff1) | Aug 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [dde539e1b1](https://linux-hardware.org/?probe=dde539e1b1) | Aug 18, 2021 |
| HP            | ProBook 4430s               | Notebook    | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f77c5c4c48](https://linux-hardware.org/?probe=f77c5c4c48) | Aug 10, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [886b00678b](https://linux-hardware.org/?probe=886b00678b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [57bf64ac4b](https://linux-hardware.org/?probe=57bf64ac4b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [76e0c19c46](https://linux-hardware.org/?probe=76e0c19c46) | Aug 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ce35fd4a1a](https://linux-hardware.org/?probe=ce35fd4a1a) | Jul 23, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [e6cb486cfd](https://linux-hardware.org/?probe=e6cb486cfd) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [58ad5d25b9](https://linux-hardware.org/?probe=58ad5d25b9) | Jul 07, 2021 |
| Dell          | Latitude E6410              | Notebook    | [9a4002aa3d](https://linux-hardware.org/?probe=9a4002aa3d) | Jul 07, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [894db66628](https://linux-hardware.org/?probe=894db66628) | Jul 05, 2021 |
| HP            | Compaq 510                  | Notebook    | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| Colorful T... | C.A68M-BTC YV14             | Desktop     | [9b6c7d9e82](https://linux-hardware.org/?probe=9b6c7d9e82) | Jun 23, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [85b912e99c](https://linux-hardware.org/?probe=85b912e99c) | Jun 22, 2021 |
| Huanan        | X79 249PC V2.1              | Desktop     | [b6fd95e48e](https://linux-hardware.org/?probe=b6fd95e48e) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [ac56c24f68](https://linux-hardware.org/?probe=ac56c24f68) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [4527ee70c7](https://linux-hardware.org/?probe=4527ee70c7) | Jun 13, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [ea30bb632e](https://linux-hardware.org/?probe=ea30bb632e) | Jun 10, 2021 |
| Lenovo        | ThinkPad L520 5015A76       | Notebook    | [84b62cbde9](https://linux-hardware.org/?probe=84b62cbde9) | Jun 10, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [851f20cb74](https://linux-hardware.org/?probe=851f20cb74) | Jun 09, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [428cb5bb99](https://linux-hardware.org/?probe=428cb5bb99) | Jun 05, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [de3596a9a3](https://linux-hardware.org/?probe=de3596a9a3) | Jun 05, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [38acf36fce](https://linux-hardware.org/?probe=38acf36fce) | Jun 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [4401c591ee](https://linux-hardware.org/?probe=4401c591ee) | Jun 01, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [f1d33c68f6](https://linux-hardware.org/?probe=f1d33c68f6) | Jun 01, 2021 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [8995f3c1ad](https://linux-hardware.org/?probe=8995f3c1ad) | Jun 01, 2021 |
| Lenovo        | Z40-70 20366                | Notebook    | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | Notebook    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [b70a62225d](https://linux-hardware.org/?probe=b70a62225d) | May 22, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [ddfb904938](https://linux-hardware.org/?probe=ddfb904938) | May 19, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [35324d2388](https://linux-hardware.org/?probe=35324d2388) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2ce7106efb](https://linux-hardware.org/?probe=2ce7106efb) | May 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [c84fc5c646](https://linux-hardware.org/?probe=c84fc5c646) | May 12, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [ef73590627](https://linux-hardware.org/?probe=ef73590627) | May 09, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [63effde8c3](https://linux-hardware.org/?probe=63effde8c3) | May 08, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [99ac06d5e2](https://linux-hardware.org/?probe=99ac06d5e2) | May 08, 2021 |
| Acer          | Predator G9-793             | Notebook    | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [2fabbbebb9](https://linux-hardware.org/?probe=2fabbbebb9) | Apr 29, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [23cc5c25c3](https://linux-hardware.org/?probe=23cc5c25c3) | Apr 29, 2021 |
| HP            | Pavilion 15                 | Notebook    | [1ddb966308](https://linux-hardware.org/?probe=1ddb966308) | Apr 28, 2021 |
| Sony          | VPCCW13FX                   | Notebook    | [82e9a1f82a](https://linux-hardware.org/?probe=82e9a1f82a) | Apr 25, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [599315872a](https://linux-hardware.org/?probe=599315872a) | Apr 24, 2021 |
| Dell          | Precision 3520              | Notebook    | [fc2d295c0e](https://linux-hardware.org/?probe=fc2d295c0e) | Apr 24, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [76defcf2f7](https://linux-hardware.org/?probe=76defcf2f7) | Apr 22, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e55472cf5f](https://linux-hardware.org/?probe=e55472cf5f) | Apr 18, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [007ae7cca0](https://linux-hardware.org/?probe=007ae7cca0) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [abf17f0c92](https://linux-hardware.org/?probe=abf17f0c92) | Apr 17, 2021 |
| HP            | Unknown                     | Notebook    | [2465109965](https://linux-hardware.org/?probe=2465109965) | Apr 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [698d0ca8cc](https://linux-hardware.org/?probe=698d0ca8cc) | Apr 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [d5d191947e](https://linux-hardware.org/?probe=d5d191947e) | Apr 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [07fd740efe](https://linux-hardware.org/?probe=07fd740efe) | Apr 06, 2021 |
| Chuwi         | LapBook SE                  | Notebook    | [0e9a03cc48](https://linux-hardware.org/?probe=0e9a03cc48) | Apr 06, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [d20d2b755f](https://linux-hardware.org/?probe=d20d2b755f) | Apr 04, 2021 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [cdfb323202](https://linux-hardware.org/?probe=cdfb323202) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [b9324b1b4d](https://linux-hardware.org/?probe=b9324b1b4d) | Apr 04, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| MSI           | GS40 6QE Phantom            | Notebook    | [adbf080ab7](https://linux-hardware.org/?probe=adbf080ab7) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [43f33bc8e0](https://linux-hardware.org/?probe=43f33bc8e0) | Mar 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [c377f57ac8](https://linux-hardware.org/?probe=c377f57ac8) | Mar 21, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| Dell          | 04Y8V0 A02                  | Desktop     | [241289046a](https://linux-hardware.org/?probe=241289046a) | Mar 16, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [5bada8b921](https://linux-hardware.org/?probe=5bada8b921) | Mar 13, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [a8e1128b26](https://linux-hardware.org/?probe=a8e1128b26) | Mar 13, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [d56654c11c](https://linux-hardware.org/?probe=d56654c11c) | Mar 12, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [d1bd158872](https://linux-hardware.org/?probe=d1bd158872) | Mar 10, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| ASUSTek       | X202E                       | Notebook    | [cc089d4ddb](https://linux-hardware.org/?probe=cc089d4ddb) | Mar 08, 2021 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [3acc3e5a05](https://linux-hardware.org/?probe=3acc3e5a05) | Mar 06, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [647b5fbb43](https://linux-hardware.org/?probe=647b5fbb43) | Mar 06, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [9e8527b842](https://linux-hardware.org/?probe=9e8527b842) | Mar 05, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [96fd52e1f2](https://linux-hardware.org/?probe=96fd52e1f2) | Mar 02, 2021 |
| Acer          | Aspire A515-53              | Notebook    | [637c3ebf75](https://linux-hardware.org/?probe=637c3ebf75) | Feb 28, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [05ad71d3d8](https://linux-hardware.org/?probe=05ad71d3d8) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [90ae93da93](https://linux-hardware.org/?probe=90ae93da93) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [4a441fe0c9](https://linux-hardware.org/?probe=4a441fe0c9) | Feb 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [bfb791c2fb](https://linux-hardware.org/?probe=bfb791c2fb) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [bb980a20ea](https://linux-hardware.org/?probe=bb980a20ea) | Feb 18, 2021 |
| ASUSTek       | EB1036                      | Desktop     | [d77c773bc7](https://linux-hardware.org/?probe=d77c773bc7) | Feb 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0c70deaac1](https://linux-hardware.org/?probe=0c70deaac1) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0441228ba8](https://linux-hardware.org/?probe=0441228ba8) | Feb 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [94b0fc1fc8](https://linux-hardware.org/?probe=94b0fc1fc8) | Feb 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [b2b00b4390](https://linux-hardware.org/?probe=b2b00b4390) | Jan 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [d7f2ee4a81](https://linux-hardware.org/?probe=d7f2ee4a81) | Jan 25, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [568c3e9797](https://linux-hardware.org/?probe=568c3e9797) | Jan 21, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [82f5ebd486](https://linux-hardware.org/?probe=82f5ebd486) | Jan 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [e9acf54209](https://linux-hardware.org/?probe=e9acf54209) | Jan 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [d462b4ca25](https://linux-hardware.org/?probe=d462b4ca25) | Jan 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [8ae2ef5b3b](https://linux-hardware.org/?probe=8ae2ef5b3b) | Jan 07, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [4a11009c6f](https://linux-hardware.org/?probe=4a11009c6f) | Jan 06, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [cf3d073aae](https://linux-hardware.org/?probe=cf3d073aae) | Jan 06, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [8b549321e4](https://linux-hardware.org/?probe=8b549321e4) | Dec 31, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [540115f336](https://linux-hardware.org/?probe=540115f336) | Dec 28, 2020 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [2e581b986a](https://linux-hardware.org/?probe=2e581b986a) | Dec 28, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [cd0b939f13](https://linux-hardware.org/?probe=cd0b939f13) | Dec 27, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [6eaddc8157](https://linux-hardware.org/?probe=6eaddc8157) | Dec 21, 2020 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [fb16534a29](https://linux-hardware.org/?probe=fb16534a29) | Dec 17, 2020 |
| Sony          | VGN-NW270F                  | Notebook    | [d8989e5c40](https://linux-hardware.org/?probe=d8989e5c40) | Dec 16, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [e880800d6f](https://linux-hardware.org/?probe=e880800d6f) | Dec 13, 2020 |
| Dell          | G3 3579                     | Notebook    | [99724b8bd6](https://linux-hardware.org/?probe=99724b8bd6) | Dec 12, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
| HP            | 158A                        | Desktop     | [9c309002d1](https://linux-hardware.org/?probe=9c309002d1) | Dec 10, 2020 |
| Acer          | Predator PH315-51           | Notebook    | [c9539f5932](https://linux-hardware.org/?probe=c9539f5932) | Dec 09, 2020 |
| HP            | 2B2C                        | Desktop     | [ffd83f6d60](https://linux-hardware.org/?probe=ffd83f6d60) | Dec 08, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [ea2bf23a76](https://linux-hardware.org/?probe=ea2bf23a76) | Dec 03, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [2a4ce919e5](https://linux-hardware.org/?probe=2a4ce919e5) | Dec 03, 2020 |
| Acer          | Aspire V5-431P              | Notebook    | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| HP            | 158A                        | Desktop     | [eaab601c40](https://linux-hardware.org/?probe=eaab601c40) | Dec 02, 2020 |
| HP            | 158A                        | Desktop     | [64320f7764](https://linux-hardware.org/?probe=64320f7764) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [4e39668b71](https://linux-hardware.org/?probe=4e39668b71) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [dbff453f7e](https://linux-hardware.org/?probe=dbff453f7e) | Dec 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [80f3a03fc2](https://linux-hardware.org/?probe=80f3a03fc2) | Nov 22, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [471b375bb8](https://linux-hardware.org/?probe=471b375bb8) | Nov 22, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [7fb140838e](https://linux-hardware.org/?probe=7fb140838e) | Nov 12, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ac263c6ad6](https://linux-hardware.org/?probe=ac263c6ad6) | Nov 10, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [3b2d445938](https://linux-hardware.org/?probe=3b2d445938) | Nov 07, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f2a745943a](https://linux-hardware.org/?probe=f2a745943a) | Nov 04, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [bfa10fd887](https://linux-hardware.org/?probe=bfa10fd887) | Nov 04, 2020 |
| Dell          | Latitude 7490               | Notebook    | [8f0ec25c05](https://linux-hardware.org/?probe=8f0ec25c05) | Oct 29, 2020 |
| Dell          | Latitude E6530              | Notebook    | [1a16aeb4dd](https://linux-hardware.org/?probe=1a16aeb4dd) | Oct 28, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [318f172f36](https://linux-hardware.org/?probe=318f172f36) | Oct 27, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [070dae158a](https://linux-hardware.org/?probe=070dae158a) | Oct 24, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [fa061b6d7e](https://linux-hardware.org/?probe=fa061b6d7e) | Oct 13, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [dc9b667685](https://linux-hardware.org/?probe=dc9b667685) | Oct 13, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [bcc1019568](https://linux-hardware.org/?probe=bcc1019568) | Oct 07, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [125dd87b84](https://linux-hardware.org/?probe=125dd87b84) | Oct 03, 2020 |
| Dell          | 0215PR A02                  | Desktop     | [a37475889b](https://linux-hardware.org/?probe=a37475889b) | Oct 03, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Lenovo        | ThinkPad T420 4236C95       | Notebook    | [8cf52f76c0](https://linux-hardware.org/?probe=8cf52f76c0) | Oct 02, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6753d2054d](https://linux-hardware.org/?probe=6753d2054d) | Oct 01, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6c568247ff](https://linux-hardware.org/?probe=6c568247ff) | Oct 01, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [15bcec7549](https://linux-hardware.org/?probe=15bcec7549) | Sep 28, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [5ff5b89d5e](https://linux-hardware.org/?probe=5ff5b89d5e) | Sep 22, 2020 |
| Koloe         | X58                         | Desktop     | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [55e8990643](https://linux-hardware.org/?probe=55e8990643) | Sep 17, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [3a8b43fc2f](https://linux-hardware.org/?probe=3a8b43fc2f) | Sep 16, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [8adea7b2b3](https://linux-hardware.org/?probe=8adea7b2b3) | Sep 15, 2020 |
| Dell          | Vostro 1450                 | Notebook    | [444ddb1aa9](https://linux-hardware.org/?probe=444ddb1aa9) | Sep 15, 2020 |
| Dell          | Precision 3520              | Notebook    | [e8f520c4fa](https://linux-hardware.org/?probe=e8f520c4fa) | Sep 09, 2020 |
| MASSCOM VI... | L133                        | Notebook    | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [11a8a7e166](https://linux-hardware.org/?probe=11a8a7e166) | Sep 07, 2020 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [42cdde5346](https://linux-hardware.org/?probe=42cdde5346) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [6b4eeecb26](https://linux-hardware.org/?probe=6b4eeecb26) | Sep 04, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [190c1e6486](https://linux-hardware.org/?probe=190c1e6486) | Aug 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [a9ced30680](https://linux-hardware.org/?probe=a9ced30680) | Aug 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [17c4f51c75](https://linux-hardware.org/?probe=17c4f51c75) | Aug 29, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [08d8dc8d6e](https://linux-hardware.org/?probe=08d8dc8d6e) | Aug 28, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [889530c9b1](https://linux-hardware.org/?probe=889530c9b1) | Aug 28, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | Notebook    | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [01f13cc1c7](https://linux-hardware.org/?probe=01f13cc1c7) | Aug 25, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [dc862d439b](https://linux-hardware.org/?probe=dc862d439b) | Aug 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ff005e6d9](https://linux-hardware.org/?probe=4ff005e6d9) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20L9001MUS    | Notebook    | [92c940e8c2](https://linux-hardware.org/?probe=92c940e8c2) | Aug 21, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [e7702e2ce8](https://linux-hardware.org/?probe=e7702e2ce8) | Aug 20, 2020 |
| Dell          | G3 3579                     | Notebook    | [8e341b94ae](https://linux-hardware.org/?probe=8e341b94ae) | Aug 18, 2020 |
| Dell          | G3 3579                     | Notebook    | [9a1078144d](https://linux-hardware.org/?probe=9a1078144d) | Aug 18, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [d9fe6d88cd](https://linux-hardware.org/?probe=d9fe6d88cd) | Aug 14, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [52f08d8242](https://linux-hardware.org/?probe=52f08d8242) | Aug 12, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | Notebook    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [a58d188243](https://linux-hardware.org/?probe=a58d188243) | Jul 19, 2020 |
| HP            | 2B2C                        | Desktop     | [ed031034e8](https://linux-hardware.org/?probe=ed031034e8) | Jul 18, 2020 |
| HP            | 2B2C                        | Desktop     | [dd85e7a5e1](https://linux-hardware.org/?probe=dd85e7a5e1) | Jul 18, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ab4eff4438](https://linux-hardware.org/?probe=ab4eff4438) | Jul 16, 2020 |
| Dell          | Latitude E5470              | Notebook    | [777b8955c3](https://linux-hardware.org/?probe=777b8955c3) | Jul 12, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [d0dff5e971](https://linux-hardware.org/?probe=d0dff5e971) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [7300218f1f](https://linux-hardware.org/?probe=7300218f1f) | Jul 09, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [4f8fb0d621](https://linux-hardware.org/?probe=4f8fb0d621) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [dba2423eba](https://linux-hardware.org/?probe=dba2423eba) | Jul 08, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [601726ae15](https://linux-hardware.org/?probe=601726ae15) | Jul 01, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [4e1f771d23](https://linux-hardware.org/?probe=4e1f771d23) | Jun 29, 2020 |
| Dell          | Vostro 3460                 | Notebook    | [2338ae0fde](https://linux-hardware.org/?probe=2338ae0fde) | Jun 28, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [a3b890c7f1](https://linux-hardware.org/?probe=a3b890c7f1) | Jun 26, 2020 |
| ASUSTek       | A68HM-K                     | Desktop     | [7fc608d8c2](https://linux-hardware.org/?probe=7fc608d8c2) | Jun 21, 2020 |
| HP            | ZBook 17 G2                 | Notebook    | [467e55d0db](https://linux-hardware.org/?probe=467e55d0db) | Jun 20, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [f223bc5b5e](https://linux-hardware.org/?probe=f223bc5b5e) | Jun 19, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [27d008955f](https://linux-hardware.org/?probe=27d008955f) | Jun 19, 2020 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [ce4a203e0f](https://linux-hardware.org/?probe=ce4a203e0f) | Jun 19, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [652d0e5648](https://linux-hardware.org/?probe=652d0e5648) | Jun 18, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [3b5f86f3d4](https://linux-hardware.org/?probe=3b5f86f3d4) | Jun 18, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [60a6140ac2](https://linux-hardware.org/?probe=60a6140ac2) | Jun 14, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [ac70aa8a8d](https://linux-hardware.org/?probe=ac70aa8a8d) | Jun 14, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [faca1b4063](https://linux-hardware.org/?probe=faca1b4063) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | Notebook    | [91a0ff7707](https://linux-hardware.org/?probe=91a0ff7707) | Jun 10, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [7b0270fb87](https://linux-hardware.org/?probe=7b0270fb87) | Jun 04, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [be05348be2](https://linux-hardware.org/?probe=be05348be2) | May 29, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [945550a204](https://linux-hardware.org/?probe=945550a204) | May 29, 2020 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [b0f5fc9b10](https://linux-hardware.org/?probe=b0f5fc9b10) | May 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [26b5908778](https://linux-hardware.org/?probe=26b5908778) | May 20, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [849bf107d8](https://linux-hardware.org/?probe=849bf107d8) | May 18, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [5a938c4186](https://linux-hardware.org/?probe=5a938c4186) | May 17, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [f400730782](https://linux-hardware.org/?probe=f400730782) | May 15, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [ffb18f222a](https://linux-hardware.org/?probe=ffb18f222a) | May 15, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [272430b55d](https://linux-hardware.org/?probe=272430b55d) | May 12, 2020 |
| Toshiba       | PORTEGE T110                | Notebook    | [8c8ec8db54](https://linux-hardware.org/?probe=8c8ec8db54) | May 10, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [7e7b980d96](https://linux-hardware.org/?probe=7e7b980d96) | May 09, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [a4ec49073e](https://linux-hardware.org/?probe=a4ec49073e) | May 02, 2020 |
| ASRock        | AOD790GX/128M               | Desktop     | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [3edae78003](https://linux-hardware.org/?probe=3edae78003) | Apr 28, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [8e17ac8b14](https://linux-hardware.org/?probe=8e17ac8b14) | Apr 27, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1aa80c5f94](https://linux-hardware.org/?probe=1aa80c5f94) | Apr 26, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [a41dc8c7b3](https://linux-hardware.org/?probe=a41dc8c7b3) | Apr 24, 2020 |
| Dell          | Vostro 3478                 | Notebook    | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [985dd25740](https://linux-hardware.org/?probe=985dd25740) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [8b6c1d10a4](https://linux-hardware.org/?probe=8b6c1d10a4) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [9cb006b675](https://linux-hardware.org/?probe=9cb006b675) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [e670bd004a](https://linux-hardware.org/?probe=e670bd004a) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [ed1d4fbd62](https://linux-hardware.org/?probe=ed1d4fbd62) | Apr 19, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [45b9a81a90](https://linux-hardware.org/?probe=45b9a81a90) | Apr 08, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Dell          | Precision 5530              | Notebook    | [805db6810c](https://linux-hardware.org/?probe=805db6810c) | Mar 31, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [6093f50362](https://linux-hardware.org/?probe=6093f50362) | Mar 30, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [1238bea224](https://linux-hardware.org/?probe=1238bea224) | Mar 21, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [72a39494c1](https://linux-hardware.org/?probe=72a39494c1) | Mar 18, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [7dddec34d1](https://linux-hardware.org/?probe=7dddec34d1) | Mar 02, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [49d0f0d68c](https://linux-hardware.org/?probe=49d0f0d68c) | Mar 01, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [359532fc26](https://linux-hardware.org/?probe=359532fc26) | Mar 01, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f1e468eec0](https://linux-hardware.org/?probe=f1e468eec0) | Feb 29, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [3740504388](https://linux-hardware.org/?probe=3740504388) | Feb 28, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [284484a6b6](https://linux-hardware.org/?probe=284484a6b6) | Feb 15, 2020 |
| Koompi        | Unknown                     | Notebook    | [46e5e1375d](https://linux-hardware.org/?probe=46e5e1375d) | Feb 12, 2020 |
| Shuttle       | FS81                        | Desktop     | [93c00d64e6](https://linux-hardware.org/?probe=93c00d64e6) | Feb 07, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [6eae1d7ba9](https://linux-hardware.org/?probe=6eae1d7ba9) | Feb 01, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [b7087b6ba5](https://linux-hardware.org/?probe=b7087b6ba5) | Jan 31, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [e3cbb2da5f](https://linux-hardware.org/?probe=e3cbb2da5f) | Jan 24, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [46c0e495c1](https://linux-hardware.org/?probe=46c0e495c1) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b2bc63b818](https://linux-hardware.org/?probe=b2bc63b818) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4ea2e33944](https://linux-hardware.org/?probe=4ea2e33944) | Jan 07, 2020 |
| AMI           | Cherry Trail FFD            | Notebook    | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| ASUSTek       | P9X79 WS                    | Desktop     | [7a8ccfd558](https://linux-hardware.org/?probe=7a8ccfd558) | Nov 21, 2019 |
| Jumper        | EZpad                       | Notebook    | [6dfb4e2274](https://linux-hardware.org/?probe=6dfb4e2274) | Oct 31, 2019 |
| Dell          | System Vostro 3450          | Notebook    | [2017fd9a25](https://linux-hardware.org/?probe=2017fd9a25) | Oct 29, 2019 |
| Dell          | System Vostro 3450          | Notebook    | [90391fe6fe](https://linux-hardware.org/?probe=90391fe6fe) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | Notebook    | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| Dell          | 0CU409                      | Desktop     | [a5aabfdba4](https://linux-hardware.org/?probe=a5aabfdba4) | Sep 09, 2019 |
| Dell          | 0CU409                      | Desktop     | [8efe3a4b92](https://linux-hardware.org/?probe=8efe3a4b92) | Sep 08, 2019 |
| Dell          | Inspiron 3421               | Notebook    | [46a7955491](https://linux-hardware.org/?probe=46a7955491) | Sep 04, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| Gigabyte      | B360 M AORUS PRO-CF         | Desktop     | [657b0b4115](https://linux-hardware.org/?probe=657b0b4115) | Aug 28, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [f9ed638fe3](https://linux-hardware.org/?probe=f9ed638fe3) | Aug 27, 2019 |
| Dell          | System Inspiron N4110       | Notebook    | [1923c8603b](https://linux-hardware.org/?probe=1923c8603b) | Aug 13, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [6a22791c51](https://linux-hardware.org/?probe=6a22791c51) | Aug 02, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [9394c6057f](https://linux-hardware.org/?probe=9394c6057f) | Aug 01, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [6cf789df63](https://linux-hardware.org/?probe=6cf789df63) | Jul 26, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [a6040fd25f](https://linux-hardware.org/?probe=a6040fd25f) | Jul 21, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [e4ad262a5d](https://linux-hardware.org/?probe=e4ad262a5d) | Jul 18, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [c52b084692](https://linux-hardware.org/?probe=c52b084692) | Jul 08, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [06efccb71d](https://linux-hardware.org/?probe=06efccb71d) | Jul 07, 2019 |
| Wistron       | JIH55Y                      | Desktop     | [75d7b2909e](https://linux-hardware.org/?probe=75d7b2909e) | Jul 07, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [ab1717a7d5](https://linux-hardware.org/?probe=ab1717a7d5) | Jul 05, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [32eed13a8c](https://linux-hardware.org/?probe=32eed13a8c) | Jul 05, 2019 |
| Dell          | Inspiron 3537               | Notebook    | [96b08c73b2](https://linux-hardware.org/?probe=96b08c73b2) | Jul 03, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [9662a59bb6](https://linux-hardware.org/?probe=9662a59bb6) | Jun 19, 2019 |
| ASUSTek       | K46CM                       | Notebook    | [f695a76e03](https://linux-hardware.org/?probe=f695a76e03) | Jun 16, 2019 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [e3cbad71df](https://linux-hardware.org/?probe=e3cbad71df) | Jun 06, 2019 |
| Dell          | Precision M4800             | Notebook    | [87cd78dbb8](https://linux-hardware.org/?probe=87cd78dbb8) | Jun 06, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [2b022f3e6e](https://linux-hardware.org/?probe=2b022f3e6e) | Jun 06, 2019 |
| HP            | Unknown                     | Notebook    | [5a84e64836](https://linux-hardware.org/?probe=5a84e64836) | Jun 05, 2019 |
| Lenovo        | Unknown                     | Notebook    | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | Notebook    | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [0142c9d319](https://linux-hardware.org/?probe=0142c9d319) | May 08, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [eab65462c8](https://linux-hardware.org/?probe=eab65462c8) | May 08, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [11b1a757e3](https://linux-hardware.org/?probe=11b1a757e3) | May 07, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [48a1bab21b](https://linux-hardware.org/?probe=48a1bab21b) | May 06, 2019 |
| Dell          | Inspiron 3420               | Notebook    | [97669e6bac](https://linux-hardware.org/?probe=97669e6bac) | Apr 28, 2019 |
| Lenovo        | ThinkPad X240 20AMA01LVA    | Notebook    | [60e3dddb8e](https://linux-hardware.org/?probe=60e3dddb8e) | Apr 18, 2019 |
| Lenovo        | ThinkPad X230 2325VEN       | Notebook    | [7de9f34ff3](https://linux-hardware.org/?probe=7de9f34ff3) | Apr 08, 2019 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [f98ce96fd7](https://linux-hardware.org/?probe=f98ce96fd7) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [3b2f20eb21](https://linux-hardware.org/?probe=3b2f20eb21) | Dec 14, 2018 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [eb181d9db4](https://linux-hardware.org/?probe=eb181d9db4) | Nov 17, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [6c2f44420a](https://linux-hardware.org/?probe=6c2f44420a) | Nov 09, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [795142797e](https://linux-hardware.org/?probe=795142797e) | Nov 09, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [0befde2891](https://linux-hardware.org/?probe=0befde2891) | Oct 29, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [6d5cda0177](https://linux-hardware.org/?probe=6d5cda0177) | Oct 29, 2018 |
| ASUSTek       | FX503VM                     | Notebook    | [c3eafeed41](https://linux-hardware.org/?probe=c3eafeed41) | May 23, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [b73b24ff47](https://linux-hardware.org/?probe=b73b24ff47) | May 16, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [4ced3a8a3c](https://linux-hardware.org/?probe=4ced3a8a3c) | Feb 04, 2018 |
| HP            | Notebook                    | Notebook    | [8f94426008](https://linux-hardware.org/?probe=8f94426008) | Dec 21, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [96a6c5cbab](https://linux-hardware.org/?probe=96a6c5cbab) | Dec 17, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [f59b817feb](https://linux-hardware.org/?probe=f59b817feb) | Dec 12, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Vietnam/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 96        | 12.96%  |
| Ubuntu 22.04                 | 58        | 7.83%   |
| Arch Rolling                 | 54        | 7.29%   |
| Ubuntu 18.04                 | 36        | 4.86%   |
| Debian 12                    | 23        | 3.1%    |
| Ubuntu 24.04                 | 19        | 2.56%   |
| Pop!_OS 22.04                | 17        | 2.29%   |
| Arch                         | 17        | 2.29%   |
| ArcoLinux Rolling            | 16        | 2.16%   |
| Fedora 40                    | 15        | 2.02%   |
| Fedora 37                    | 12        | 1.62%   |
| Manjaro                      | 11        | 1.48%   |
| Fedora 38                    | 11        | 1.48%   |
| EndeavourOS Rolling          | 9         | 1.21%   |
| Ubuntu 23.10                 | 8         | 1.08%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 1.08%   |
| Debian 10                    | 8         | 1.08%   |
| Zorin 16                     | 7         | 0.94%   |
| Pop!_OS 20.04                | 7         | 0.94%   |
| Debian 11                    | 7         | 0.94%   |
| Xero Rolling                 | 6         | 0.81%   |
| Ubuntu 21.04                 | 6         | 0.81%   |
| OpenMandriva 23.03           | 6         | 0.81%   |
| Linux Mint 21.2              | 6         | 0.81%   |
| KDE neon 20.04               | 6         | 0.81%   |
| Fedora 39                    | 6         | 0.81%   |
| Ubuntu 21.10                 | 5         | 0.67%   |
| Ubuntu 19.10                 | 5         | 0.67%   |
| Ubuntu 16.04                 | 5         | 0.67%   |
| OpenMandriva 4.2             | 5         | 0.67%   |
| Manjaro 20.2                 | 5         | 0.67%   |
| Linux Mint 22                | 5         | 0.67%   |
| Fedora 41                    | 5         | 0.67%   |
| Ubuntu Unity 16.04           | 4         | 0.54%   |
| Ubuntu 23.04                 | 4         | 0.54%   |
| Ubuntu 20.10                 | 4         | 0.54%   |
| Ubuntu 19.04                 | 4         | 0.54%   |
| Pop!_OS 21.04                | 4         | 0.54%   |
| Pop!_OS 20.10                | 4         | 0.54%   |
| OpenMandriva 4.3             | 4         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 247       | 34.4%   |
| Arch         | 71        | 9.89%   |
| Fedora       | 59        | 8.22%   |
| Debian       | 39        | 5.43%   |
| Pop!_OS      | 34        | 4.74%   |
| Linux Mint   | 33        | 4.6%    |
| OpenMandriva | 28        | 3.9%    |
| Manjaro      | 26        | 3.62%   |
| ArcoLinux    | 17        | 2.37%   |
| openSUSE     | 14        | 1.95%   |
| Zorin        | 12        | 1.67%   |
| Kubuntu      | 11        | 1.53%   |
| KDE neon     | 9         | 1.25%   |
| EndeavourOS  | 9         | 1.25%   |
| Ubuntu Unity | 8         | 1.11%   |
| Kali         | 8         | 1.11%   |
| Endless      | 7         | 0.97%   |
| Elementary   | 7         | 0.97%   |
| Xubuntu      | 6         | 0.84%   |
| Xero         | 6         | 0.84%   |
| NixOS        | 5         | 0.7%    |
| Lubuntu      | 5         | 0.7%    |
| Gentoo       | 5         | 0.7%    |
| Clear Linux  | 5         | 0.7%    |
| ChimeraOS    | 4         | 0.56%   |
| Ubuntu MATE  | 3         | 0.42%   |
| SteamOS      | 3         | 0.42%   |
| Nobara       | 3         | 0.42%   |
| Garuda Linux | 3         | 0.42%   |
| CentOS       | 3         | 0.42%   |
| Void Linux   | 2         | 0.28%   |
| ROSA         | 2         | 0.28%   |
| Parrot       | 2         | 0.28%   |
| Oracle Linux | 2         | 0.28%   |
| MX           | 2         | 0.28%   |
| LMDE         | 2         | 0.28%   |
| CachyOS      | 2         | 0.28%   |
| Artix        | 2         | 0.28%   |
| Ultramarine  | 1         | 0.14%   |
| Solus        | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 9         | 1.11%   |
| 6.8.0-31-generic         | 8         | 0.99%   |
| 5.4.0-37-generic         | 8         | 0.99%   |
| 6.8.0-40-generic         | 7         | 0.86%   |
| 5.4.0-52-generic         | 7         | 0.86%   |
| 5.4.0-48-generic         | 7         | 0.86%   |
| 6.2.6-desktop-1omv2390   | 6         | 0.74%   |
| 5.4.0-58-generic         | 6         | 0.74%   |
| 5.4.0-40-generic         | 6         | 0.74%   |
| 6.9.3-76060903-generic   | 5         | 0.62%   |
| 6.5.8-arch1-1            | 5         | 0.62%   |
| 6.2.0-34-generic         | 5         | 0.62%   |
| 5.8.0-55-generic         | 5         | 0.62%   |
| 5.8.0-53-generic         | 5         | 0.62%   |
| 5.15.0-91-generic        | 5         | 0.62%   |
| 5.15.0-56-generic        | 5         | 0.62%   |
| 5.15.0-52-generic        | 5         | 0.62%   |
| 5.11.0-41-generic        | 5         | 0.62%   |
| 5.11.0-38-generic        | 5         | 0.62%   |
| 5.11.0-37-generic        | 5         | 0.62%   |
| 5.10.14-desktop-1omv4002 | 5         | 0.62%   |
| 6.9.3-arch1-1            | 4         | 0.49%   |
| 6.8.0-45-generic         | 4         | 0.49%   |
| 6.5.0-15-generic         | 4         | 0.49%   |
| 6.5.0-14-generic         | 4         | 0.49%   |
| 6.2.9-300.fc38.x86_64    | 4         | 0.49%   |
| 6.2.0-36-generic         | 4         | 0.49%   |
| 6.1.0-18-amd64           | 4         | 0.49%   |
| 5.8.0-7642-generic       | 4         | 0.49%   |
| 5.8.0-50-generic         | 4         | 0.49%   |
| 5.8.0-43-generic         | 4         | 0.49%   |
| 5.4.0-47-generic         | 4         | 0.49%   |
| 5.4.0-26-generic         | 4         | 0.49%   |
| 5.15.0-48-generic        | 4         | 0.49%   |
| 5.15.0-47-generic        | 4         | 0.49%   |
| 5.0.0-23-generic         | 4         | 0.49%   |
| 4.10.0-28-generic        | 4         | 0.49%   |
| 6.8.1-arch1-1            | 3         | 0.37%   |
| 6.8.0-39-generic         | 3         | 0.37%   |
| 6.5.0-35-generic         | 3         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 76        | 9.86%   |
| 5.15.0  | 62        | 8.04%   |
| 5.8.0   | 37        | 4.8%    |
| 5.11.0  | 31        | 4.02%   |
| 6.8.0   | 26        | 3.37%   |
| 6.5.0   | 24        | 3.11%   |
| 6.2.0   | 24        | 3.11%   |
| 6.1.0   | 21        | 2.72%   |
| 5.13.0  | 15        | 1.95%   |
| 4.15.0  | 15        | 1.95%   |
| 5.19.0  | 14        | 1.82%   |
| 5.0.0   | 13        | 1.69%   |
| 5.3.0   | 12        | 1.56%   |
| 6.9.3   | 11        | 1.43%   |
| 5.10.0  | 10        | 1.3%    |
| 6.2.6   | 9         | 1.17%   |
| 4.18.0  | 9         | 1.17%   |
| 6.2.9   | 8         | 1.04%   |
| 4.19.0  | 6         | 0.78%   |
| 6.5.8   | 5         | 0.65%   |
| 6.5.6   | 5         | 0.65%   |
| 6.5.5   | 5         | 0.65%   |
| 6.4.0   | 5         | 0.65%   |
| 5.10.14 | 5         | 0.65%   |
| 4.10.0  | 5         | 0.65%   |
| 6.9.12  | 4         | 0.52%   |
| 6.3.9   | 4         | 0.52%   |
| 6.3.5   | 4         | 0.52%   |
| 6.12.1  | 4         | 0.52%   |
| 6.11.8  | 4         | 0.52%   |
| 6.11.4  | 4         | 0.52%   |
| 5.16.7  | 4         | 0.52%   |
| 6.9.7   | 3         | 0.39%   |
| 6.8.9   | 3         | 0.39%   |
| 6.8.4   | 3         | 0.39%   |
| 6.8.1   | 3         | 0.39%   |
| 6.7.4   | 3         | 0.39%   |
| 6.6.9   | 3         | 0.39%   |
| 6.6.56  | 3         | 0.39%   |
| 6.4.11  | 3         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 85        | 11.24%  |
| 5.15    | 77        | 10.19%  |
| 6.2     | 49        | 6.48%   |
| 6.5     | 46        | 6.08%   |
| 6.1     | 46        | 6.08%   |
| 6.8     | 44        | 5.82%   |
| 5.8     | 40        | 5.29%   |
| 5.11    | 33        | 4.37%   |
| 6.6     | 29        | 3.84%   |
| 6.9     | 23        | 3.04%   |
| 5.19    | 23        | 3.04%   |
| 5.10    | 23        | 3.04%   |
| 5.13    | 21        | 2.78%   |
| 6.4     | 17        | 2.25%   |
| 5.0     | 16        | 2.12%   |
| 4.15    | 16        | 2.12%   |
| 6.11    | 14        | 1.85%   |
| 6.10    | 13        | 1.72%   |
| 6.0     | 13        | 1.72%   |
| 5.3     | 12        | 1.59%   |
| 6.7     | 11        | 1.46%   |
| 6.3     | 11        | 1.46%   |
| 5.9     | 11        | 1.46%   |
| 5.18    | 9         | 1.19%   |
| 5.16    | 9         | 1.19%   |
| 5.12    | 9         | 1.19%   |
| 4.18    | 9         | 1.19%   |
| 6.12    | 8         | 1.06%   |
| 5.14    | 8         | 1.06%   |
| 4.19    | 8         | 1.06%   |
| 5.17    | 5         | 0.66%   |
| 4.10    | 5         | 0.66%   |
| 5.7     | 3         | 0.4%    |
| 5.6     | 2         | 0.26%   |
| 5.5     | 2         | 0.26%   |
| 4.13    | 2         | 0.26%   |
| 4.4     | 1         | 0.13%   |
| 4.12    | 1         | 0.13%   |
| 4.1     | 1         | 0.13%   |
| 3.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 681       | 98.84%  |
| aarch64 | 6         | 0.87%   |
| i686    | 2         | 0.29%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 344       | 47.71%  |
| KDE5             | 96        | 13.31%  |
| Unknown          | 91        | 12.62%  |
| XFCE             | 48        | 6.66%   |
| X-Cinnamon       | 28        | 3.88%   |
| KDE6             | 19        | 2.64%   |
| KDE              | 18        | 2.5%    |
| MATE             | 10        | 1.39%   |
| Hyprland         | 9         | 1.25%   |
| Unity            | 8         | 1.11%   |
| LXQt             | 8         | 1.11%   |
| Pantheon         | 7         | 0.97%   |
| i3               | 6         | 0.83%   |
| Cinnamon         | 4         | 0.55%   |
| bspwm            | 3         | 0.42%   |
| sway             | 2         | 0.28%   |
| Openbox          | 2         | 0.28%   |
| LXDE             | 2         | 0.28%   |
| KDE4             | 2         | 0.28%   |
| Deepin           | 2         | 0.28%   |
| Budgie           | 2         | 0.28%   |
| awesome          | 2         | 0.28%   |
| X-Generic        | 1         | 0.14%   |
| qtile            | 1         | 0.14%   |
| none+awesome     | 1         | 0.14%   |
| lightdm-xsession | 1         | 0.14%   |
| LeftWM           | 1         | 0.14%   |
| gamescope        | 1         | 0.14%   |
| fluxbox          | 1         | 0.14%   |
| dwm              | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 461       | 64.03%  |
| Wayland | 190       | 26.39%  |
| Unknown | 44        | 6.11%   |
| Tty     | 25        | 3.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 306       | 42.5%   |
| SDDM                  | 110       | 15.28%  |
| GDM                   | 100       | 13.89%  |
| GDM3                  | 98        | 13.61%  |
| LightDM               | 79        | 10.97%  |
| TDM                   | 16        | 2.22%   |
| XDM                   | 3         | 0.42%   |
| SLiM                  | 2         | 0.28%   |
| LY-DM                 | 2         | 0.28%   |
| GREETD                | 2         | 0.28%   |
| KDM                   | 1         | 0.14%   |
| DISPLAY-MANAGER-START | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 541       | 77.95%  |
| Unknown     | 65        | 9.37%   |
| vi_VN       | 37        | 5.33%   |
| C           | 21        | 3.03%   |
| en_GB       | 9         | 1.3%    |
| ru_RU       | 6         | 0.86%   |
| en_AU       | 4         | 0.58%   |
| en_CA       | 2         | 0.29%   |
| POSIX       | 1         | 0.14%   |
| ko_KR       | 1         | 0.14%   |
| ja_JP       | 1         | 0.14%   |
| fr_FR       | 1         | 0.14%   |
| es_ES       | 1         | 0.14%   |
| en_US.UTF=8 | 1         | 0.14%   |
| en_BW       | 1         | 0.14%   |
| de_DE       | 1         | 0.14%   |
| de          | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 452       | 63.93%  |
| BIOS | 255       | 36.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 501       | 70.96%  |
| Btrfs    | 102       | 14.45%  |
| Overlay  | 41        | 5.81%   |
| Tmpfs    | 29        | 4.11%   |
| Unknown  | 14        | 1.98%   |
| Zfs      | 9         | 1.27%   |
| Xfs      | 6         | 0.85%   |
| F2fs     | 2         | 0.28%   |
| Reiserfs | 1         | 0.14%   |
| Ext3     | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 385       | 54.92%  |
| Unknown | 270       | 38.52%  |
| MBR     | 46        | 6.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 602       | 85.39%  |
| Yes       | 103       | 14.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 414       | 58.31%  |
| Yes       | 296       | 41.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell                                 | 131       | 19.01%  |
| ASUSTek Computer                     | 118       | 17.13%  |
| Lenovo                               | 108       | 15.67%  |
| Hewlett-Packard                      | 80        | 11.61%  |
| Gigabyte Technology                  | 53        | 7.69%   |
| MSI                                  | 46        | 6.68%   |
| Acer                                 | 37        | 5.37%   |
| Apple                                | 14        | 2.03%   |
| Intel                                | 8         | 1.16%   |
| HUAWEI                               | 7         | 1.02%   |
| ASRock                               | 7         | 1.02%   |
| Sony                                 | 6         | 0.87%   |
| Samsung Electronics                  | 6         | 0.87%   |
| Toshiba                              | 5         | 0.73%   |
| Unknown                              | 5         | 0.73%   |
| Supermicro                           | 4         | 0.58%   |
| Google                               | 4         | 0.58%   |
| Chuwi                                | 4         | 0.58%   |
| ZOTAC                                | 3         | 0.44%   |
| GuoGuang                             | 3         | 0.44%   |
| Wistron                              | 2         | 0.29%   |
| Timi                                 | 2         | 0.29%   |
| Raspberry Pi Foundation              | 2         | 0.29%   |
| OrangePi                             | 2         | 0.29%   |
| MASSCOM VIETNAM                      | 2         | 0.29%   |
| LG Electronics                       | 2         | 0.29%   |
| Foxconn                              | 2         | 0.29%   |
| Alienware                            | 2         | 0.29%   |
| Valve                                | 1         | 0.15%   |
| Ugoos                                | 1         | 0.15%   |
| TENKU                                | 1         | 0.15%   |
| T-bao                                | 1         | 0.15%   |
| Shuttle                              | 1         | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.15%   |
| Shenzhen Amediatech Technology       | 1         | 0.15%   |
| Panasonic                            | 1         | 0.15%   |
| ONE-NETBOOK TECHNOLOGY               | 1         | 0.15%   |
| Microsoft                            | 1         | 0.15%   |
| Koompi                               | 1         | 0.15%   |
| Koloe                                | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 11        | 1.6%    |
| ASUS All Series                      | 7         | 1.02%   |
| Gigabyte H61M-DS2                    | 6         | 0.87%   |
| MSI MS-7B89                          | 4         | 0.58%   |
| Lenovo ThinkPad E14 20RAS0KX00       | 4         | 0.58%   |
| Lenovo Legion 5 15ARH05 82B5         | 4         | 0.58%   |
| Dell Vostro 3578                     | 4         | 0.58%   |
| Dell Inspiron 3537                   | 4         | 0.58%   |
| Apple MacBookPro12,1                 | 4         | 0.58%   |
| MSI MS-7B98                          | 3         | 0.44%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2  | 3         | 0.44%   |
| Intel X99                            | 3         | 0.44%   |
| HUAWEI BOM-WXX9                      | 3         | 0.44%   |
| HP Notebook                          | 3         | 0.44%   |
| Dell Vostro 15-3568                  | 3         | 0.44%   |
| ASUS X411UA                          | 3         | 0.44%   |
| Acer Nitro AN515-57                  | 3         | 0.44%   |
| Toshiba Satellite L840               | 2         | 0.29%   |
| Supermicro SYS-7039A-I               | 2         | 0.29%   |
| OrangePi NEO-01                      | 2         | 0.29%   |
| MSI MS-7C89                          | 2         | 0.29%   |
| MSI MS-7823                          | 2         | 0.29%   |
| MSI Modern 15 A5M                    | 2         | 0.29%   |
| MSI Modern 14 B5M                    | 2         | 0.29%   |
| MSI GF63 8RD                         | 2         | 0.29%   |
| MASSCOM VIETNAM L133                 | 2         | 0.29%   |
| Lenovo Yoga 14sACH 2021 82MS         | 2         | 0.29%   |
| Lenovo ThinkPad W530 2447EJ9         | 2         | 0.29%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0     | 2         | 0.29%   |
| Lenovo Legion 5 15ACH6H 82JU         | 2         | 0.29%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4 | 2         | 0.29%   |
| Lenovo IdeaPad 5 15ITL05 82FG        | 2         | 0.29%   |
| Lenovo IdeaPad 5 14ITL05 82FE        | 2         | 0.29%   |
| HUAWEI KLVL-WXXW                     | 2         | 0.29%   |
| HP Z440 Workstation                  | 2         | 0.29%   |
| HP Victus by Laptop 16-e0xxx         | 2         | 0.29%   |
| HP ProBook 450 G1                    | 2         | 0.29%   |
| HP ProBook 440 G7                    | 2         | 0.29%   |
| HP Laptop 15s-du1xxx                 | 2         | 0.29%   |
| HP Laptop 14-bs0xx                   | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 50        | 7.26%   |
| Dell Latitude      | 31        | 4.5%    |
| Dell Inspiron      | 29        | 4.21%   |
| Dell Vostro        | 24        | 3.48%   |
| ASUS ROG           | 23        | 3.34%   |
| Lenovo IdeaPad     | 22        | 3.19%   |
| Acer Aspire        | 21        | 3.05%   |
| HP EliteBook       | 18        | 2.61%   |
| ASUS VivoBook      | 14        | 2.03%   |
| Dell Precision     | 13        | 1.89%   |
| Lenovo Legion      | 12        | 1.74%   |
| ASUS PRIME         | 12        | 1.74%   |
| ASUS ASUS          | 12        | 1.74%   |
| Dell OptiPlex      | 11        | 1.6%    |
| Unknown            | 11        | 1.6%    |
| HP ProBook         | 10        | 1.45%   |
| Acer Nitro         | 10        | 1.45%   |
| Lenovo ThinkBook   | 9         | 1.31%   |
| Dell XPS           | 9         | 1.31%   |
| HP Laptop          | 8         | 1.16%   |
| Gigabyte H61M-DS2  | 7         | 1.02%   |
| ASUS All           | 7         | 1.02%   |
| MSI Modern         | 5         | 0.73%   |
| HP ZBook           | 5         | 0.73%   |
| HP Pavilion        | 5         | 0.73%   |
| Dell System        | 5         | 0.73%   |
| ASUS TUF           | 5         | 0.73%   |
| MSI MS-7B89        | 4         | 0.58%   |
| MSI GF63           | 4         | 0.58%   |
| Dell G3            | 4         | 0.58%   |
| Apple MacBookPro12 | 4         | 0.58%   |
| Toshiba Satellite  | 3         | 0.44%   |
| MSI MS-7B98        | 3         | 0.44%   |
| Lenovo Yoga        | 3         | 0.44%   |
| Lenovo ThinkCentre | 3         | 0.44%   |
| Intel X99          | 3         | 0.44%   |
| HUAWEI BOM-WXX9    | 3         | 0.44%   |
| HP Notebook        | 3         | 0.44%   |
| HP Compaq          | 3         | 0.44%   |
| ASUS X411UA        | 3         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 92        | 13.35%  |
| 2021    | 73        | 10.6%   |
| 2020    | 65        | 9.43%   |
| 2019    | 56        | 8.13%   |
| 2012    | 49        | 7.11%   |
| 2013    | 46        | 6.68%   |
| 2014    | 43        | 6.24%   |
| 2017    | 39        | 5.66%   |
| 2022    | 38        | 5.52%   |
| 2016    | 37        | 5.37%   |
| 2015    | 35        | 5.08%   |
| 2023    | 33        | 4.79%   |
| 2011    | 28        | 4.06%   |
| 2010    | 14        | 2.03%   |
| 2009    | 14        | 2.03%   |
| 2024    | 9         | 1.31%   |
| 2008    | 7         | 1.02%   |
| Unknown | 6         | 0.87%   |
| 2007    | 4         | 0.58%   |
| 2006    | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 469       | 68.07%  |
| Desktop        | 181       | 26.27%  |
| Convertible    | 9         | 1.31%   |
| Tablet         | 8         | 1.16%   |
| Mini pc        | 8         | 1.16%   |
| System on chip | 6         | 0.87%   |
| Server         | 6         | 0.87%   |
| All in one     | 2         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 640       | 92.09%  |
| Enabled  | 55        | 7.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 685       | 99.42%  |
| Yes  | 4         | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 166       | 23.71%  |
| 16.01-24.0  | 161       | 23%     |
| 8.01-16.0   | 132       | 18.86%  |
| 3.01-4.0    | 91        | 13%     |
| 32.01-64.0  | 84        | 12%     |
| 24.01-32.0  | 27        | 3.86%   |
| 1.01-2.0    | 19        | 2.71%   |
| 64.01-256.0 | 14        | 2%      |
| 2.01-3.0    | 4         | 0.57%   |
| 0.51-1.0    | 2         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 231       | 30.28%  |
| 4.01-8.0   | 168       | 22.02%  |
| 1.01-2.0   | 148       | 19.4%   |
| 3.01-4.0   | 128       | 16.78%  |
| 8.01-16.0  | 48        | 6.29%   |
| 0.51-1.0   | 18        | 2.36%   |
| 16.01-24.0 | 11        | 1.44%   |
| 0.01-0.5   | 6         | 0.79%   |
| 24.01-32.0 | 4         | 0.52%   |
| 32.01-64.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 406       | 57.43%  |
| 2      | 227       | 32.11%  |
| 3      | 54        | 7.64%   |
| 4      | 12        | 1.7%    |
| 5      | 3         | 0.42%   |
| 0      | 3         | 0.42%   |
| 9      | 1         | 0.14%   |
| 6      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 582       | 84.35%  |
| Yes       | 108       | 15.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 571       | 82.16%  |
| No        | 124       | 17.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 573       | 82.68%  |
| No        | 120       | 17.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 509       | 73.34%  |
| No        | 185       | 26.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Vietnam | 689       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Ho Chi Minh City | 317       | 44.09%  |
| Hanoi            | 230       | 31.99%  |
| Da Nang          | 24        | 3.34%   |
| Can Tho          | 11        | 1.53%   |
| Bien Hoa         | 9         | 1.25%   |
| Bac Giang        | 7         | 0.97%   |
| Nha Trang        | 6         | 0.83%   |
| Vũng Tàu       | 5         | 0.7%    |
| Tay Ninh         | 5         | 0.7%    |
| Đông Hà       | 4         | 0.56%   |
| Thai Nguyen      | 4         | 0.56%   |
| Nam Định      | 4         | 0.56%   |
| Huế            | 4         | 0.56%   |
| Bến Tre        | 4         | 0.56%   |
| Vinh             | 3         | 0.42%   |
| Tua Chua         | 3         | 0.42%   |
| Thuan An         | 3         | 0.42%   |
| Thu Duc          | 3         | 0.42%   |
| Thon Dien Ha     | 3         | 0.42%   |
| Quảng Ngai     | 3         | 0.42%   |
| Nga Bay          | 3         | 0.42%   |
| Hung Yen         | 3         | 0.42%   |
| Hai Duong        | 3         | 0.42%   |
| Dien Ban         | 3         | 0.42%   |
| Buon Ma Thuot    | 3         | 0.42%   |
| Vinh Phuc        | 2         | 0.28%   |
| Viet Tri         | 2         | 0.28%   |
| Tra Vinh         | 2         | 0.28%   |
| Tinh Binh Duong  | 2         | 0.28%   |
| Thanh Hóa       | 2         | 0.28%   |
| Tan An           | 2         | 0.28%   |
| Haiphong         | 2         | 0.28%   |
| Binh Hoa         | 2         | 0.28%   |
| Binh Duong       | 2         | 0.28%   |
| Bao Loc          | 2         | 0.28%   |
| Xom My Tho       | 1         | 0.14%   |
| Vinh Yen         | 1         | 0.14%   |
| Vi Thanh         | 1         | 0.14%   |
| Tinh Quang Binh  | 1         | 0.14%   |
| Tinh GJong Nai   | 1         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 163       | 222    | 15.98%  |
| WDC                         | 141       | 188    | 13.82%  |
| Seagate                     | 86        | 102    | 8.43%   |
| Toshiba                     | 57        | 78     | 5.59%   |
| SK hynix                    | 48        | 57     | 4.71%   |
| Kingston                    | 48        | 70     | 4.71%   |
| Sandisk                     | 42        | 55     | 4.12%   |
| Micron Technology           | 41        | 46     | 4.02%   |
| Unknown                     | 37        | 45     | 3.63%   |
| Intel                       | 34        | 37     | 3.33%   |
| HGST                        | 31        | 33     | 3.04%   |
| Hitachi                     | 20        | 26     | 1.96%   |
| Crucial                     | 19        | 22     | 1.86%   |
| KIOXIA                      | 13        | 17     | 1.27%   |
| Plextor                     | 12        | 12     | 1.18%   |
| Apple                       | 11        | 14     | 1.08%   |
| Lexar                       | 10        | 10     | 0.98%   |
| OSCOO                       | 8         | 9      | 0.78%   |
| MAXIO Technology (Hangzhou) | 8         | 8      | 0.78%   |
| KingSpec                    | 8         | 12     | 0.78%   |
| China                       | 8         | 9      | 0.78%   |
| Transcend                   | 7         | 9      | 0.69%   |
| Colorful                    | 7         | 9      | 0.69%   |
| TO Exter                    | 6         | 9      | 0.59%   |
| Phison Electronics          | 6         | 6      | 0.59%   |
| Kingmax                     | 6         | 7      | 0.59%   |
| Unknown                     | 6         | 7      | 0.59%   |
| Silicon Motion              | 5         | 8      | 0.49%   |
| Netac                       | 5         | 6      | 0.49%   |
| Kingston Technology Company | 5         | 7      | 0.49%   |
| Gigabyte Technology         | 5         | 5      | 0.49%   |
| XSTAR                       | 4         | 5      | 0.39%   |
| SPCC                        | 4         | 4      | 0.39%   |
| LITEON                      | 4         | 4      | 0.39%   |
| JMicron Technology          | 4         | 4      | 0.39%   |
| A-DATA Technology           | 4         | 4      | 0.39%   |
| Realtek Semiconductor       | 3         | 4      | 0.29%   |
| Phison                      | 3         | 4      | 0.29%   |
| OCZ                         | 3         | 3      | 0.29%   |
| Fujitsu                     | 3         | 4      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 18        | 1.67%   |
| HGST HTS721010A9E630 1TB                             | 12        | 1.12%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 11        | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB                       | 11        | 1.02%   |
| Samsung SSD 860 EVO 250GB                            | 11        | 1.02%   |
| Kingston SA400S37240G 240GB SSD                      | 10        | 0.93%   |
| Samsung SSD 980 1TB                                  | 9         | 0.84%   |
| Unknown MMC Card  32GB                               | 8         | 0.74%   |
| Toshiba MQ01ABF050 500GB                             | 8         | 0.74%   |
| Samsung SSD 860 EVO 500GB                            | 8         | 0.74%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 7         | 0.65%   |
| Samsung SSD 870 EVO 500GB                            | 7         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 7         | 0.65%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 7         | 0.65%   |
| Kingston SA400S37120G 120GB SSD                      | 7         | 0.65%   |
| HGST HTS545050A7E680 500GB                           | 7         | 0.65%   |
| Crucial CT240BX500SSD1 240GB                         | 7         | 0.65%   |
| WDC WD5000AAKX-00ERMA0 500GB                         | 6         | 0.56%   |
| Toshiba MQ04ABF100 1TB                               | 6         | 0.56%   |
| TO Exter nal USB 3.0 1024GB                          | 6         | 0.56%   |
| Samsung NVMe SSD Drive 512GB                         | 6         | 0.56%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 6         | 0.56%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 6         | 0.56%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 6         | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                            | 6         | 0.56%   |
| Unknown                                              | 6         | 0.56%   |
| Unknown SD/MMC/MS PRO 128GB                          | 5         | 0.47%   |
| Samsung SSD 980 500GB                                | 5         | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 5         | 0.47%   |
| Lexar 128GB SSD                                      | 5         | 0.47%   |
| Kingston SA400S37480G 480GB SSD                      | 5         | 0.47%   |
| XSTAR SSD 128GB                                      | 4         | 0.37%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 4         | 0.37%   |
| WDC WD5000LPLX-60ZNTT1 500GB                         | 4         | 0.37%   |
| WDC WD2500AAKX-00ERMA0 250GB                         | 4         | 0.37%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.37%   |
| SK hynix NVMe SSD Drive 256GB                        | 4         | 0.37%   |
| Seagate ST9500325AS 500GB                            | 4         | 0.37%   |
| Seagate ST500LT012-1DG142 500GB                      | 4         | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                      | 4         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 100       | 138    | 34.13%  |
| Seagate  | 86        | 101    | 29.35%  |
| Toshiba  | 39        | 50     | 13.31%  |
| HGST     | 31        | 33     | 10.58%  |
| Hitachi  | 20        | 26     | 6.83%   |
| TO Exter | 6         | 9      | 2.05%   |
| Unknown  | 5         | 6      | 1.71%   |
| Fujitsu  | 3         | 4      | 1.02%   |
| External | 2         | 2      | 0.68%   |
| CSD      | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 78     | 17.48%  |
| Kingston            | 31        | 48     | 9.51%   |
| WDC                 | 25        | 25     | 7.67%   |
| SanDisk             | 18        | 23     | 5.52%   |
| Crucial             | 18        | 19     | 5.52%   |
| Intel               | 13        | 14     | 3.99%   |
| Plextor             | 12        | 12     | 3.68%   |
| Lexar               | 10        | 10     | 3.07%   |
| Apple               | 9         | 12     | 2.76%   |
| KingSpec            | 8         | 12     | 2.45%   |
| China               | 8         | 9      | 2.45%   |
| Transcend           | 7         | 9      | 2.15%   |
| OSCOO               | 7         | 7      | 2.15%   |
| Colorful            | 7         | 9      | 2.15%   |
| Toshiba             | 6         | 8      | 1.84%   |
| SK hynix            | 6         | 6      | 1.84%   |
| Netac               | 5         | 6      | 1.53%   |
| Micron Technology   | 5         | 5      | 1.53%   |
| Kingmax             | 5         | 5      | 1.53%   |
| XSTAR               | 4         | 5      | 1.23%   |
| LITEON              | 4         | 4      | 1.23%   |
| Gigabyte Technology | 4         | 4      | 1.23%   |
| SPCC                | 3         | 3      | 0.92%   |
| FORESEE             | 3         | 3      | 0.92%   |
| Apacer              | 3         | 3      | 0.92%   |
| ZOTAC               | 2         | 2      | 0.61%   |
| OCZ                 | 2         | 2      | 0.61%   |
| Maxtor              | 2         | 4      | 0.61%   |
| LITEONIT            | 2         | 2      | 0.61%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.61%   |
| KingDian            | 2         | 3      | 0.61%   |
| Hikvision           | 2         | 2      | 0.61%   |
| AGI                 | 2         | 2      | 0.61%   |
| A-DATA Technology   | 2         | 2      | 0.61%   |
| W800S               | 1         | 1      | 0.31%   |
| VSP-128G            | 1         | 1      | 0.31%   |
| VSP                 | 1         | 1      | 0.31%   |
| Vaseky              | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |
| Team                | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 335       | 457    | 36.14%  |
| SSD     | 287       | 393    | 30.96%  |
| HDD     | 254       | 370    | 27.4%   |
| MMC     | 31        | 39     | 3.34%   |
| Unknown | 20        | 20     | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 418       | 742    | 51.04%  |
| NVMe | 335       | 454    | 40.9%   |
| SAS  | 35        | 44     | 4.27%   |
| MMC  | 31        | 39     | 3.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 361       | 536    | 68.37%  |
| 0.51-1.0   | 125       | 163    | 23.67%  |
| 1.01-2.0   | 26        | 37     | 4.92%   |
| 3.01-4.0   | 7         | 9      | 1.33%   |
| 4.01-10.0  | 7         | 16     | 1.33%   |
| 2.01-3.0   | 2         | 2      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 225       | 30.57%  |
| 251-500        | 175       | 23.78%  |
| 501-1000       | 89        | 12.09%  |
| 51-100         | 54        | 7.34%   |
| 1001-2000      | 43        | 5.84%   |
| 1-20           | 40        | 5.43%   |
| Unknown        | 38        | 5.16%   |
| 21-50          | 35        | 4.76%   |
| More than 3000 | 20        | 2.72%   |
| 2001-3000      | 17        | 2.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 274       | 36.63%  |
| 21-50          | 135       | 18.05%  |
| 101-250        | 101       | 13.5%   |
| 51-100         | 88        | 11.76%  |
| 251-500        | 56        | 7.49%   |
| Unknown        | 38        | 5.08%   |
| 501-1000       | 33        | 4.41%   |
| 1001-2000      | 11        | 1.47%   |
| More than 3000 | 7         | 0.94%   |
| 2001-3000      | 5         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD             | 3         | 3      | 4.17%   |
| HGST HTS545050A7E680 500GB                   | 3         | 4      | 4.17%   |
| WDC WD3200AAKX-001CA0 320GB                  | 2         | 2      | 2.78%   |
| Seagate ST9320325AS 320GB                    | 2         | 3      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 2.78%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 3      | 2.78%   |
| HGST HTS725050A7E630 500GB                   | 2         | 2      | 2.78%   |
| WDC WD60PURZ-85ZUFY1 6TB                     | 1         | 3      | 1.39%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.39%   |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 1.39%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 1      | 1.39%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.39%   |
| WDC WD3200AAJS-00L7A0 320GB                  | 1         | 1      | 1.39%   |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 1.39%   |
| WDC WD2500BEVT-75ZCT2 250GB                  | 1         | 1      | 1.39%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 1.39%   |
| WDC WD10EZRX-00A3KB0 1TB                     | 1         | 2      | 1.39%   |
| WDC WD10EARS-00Y5B1 1TB                      | 1         | 1      | 1.39%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1         | 1      | 1.39%   |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 1.39%   |
| Transcend TS256GSSD230S 256GB                | 1         | 1      | 1.39%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 1.39%   |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 1.39%   |
| Toshiba MK3275GSX 320GB                      | 1         | 1      | 1.39%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 1.39%   |
| Toshiba HDWK105 500GB                        | 1         | 1      | 1.39%   |
| SPCC Solid State Disk 128GB                  | 1         | 1      | 1.39%   |
| SK hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 1.39%   |
| SK hynix BC711 HFM256GD3JX013N 256GB         | 1         | 1      | 1.39%   |
| Seagate ST9640423AS 640GB                    | 1         | 1      | 1.39%   |
| Seagate ST9320320AS 320GB                    | 1         | 1      | 1.39%   |
| Seagate ST9250410AS 250GB                    | 1         | 1      | 1.39%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.39%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 1.39%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.39%   |
| Seagate ST2000NM0011 2TB                     | 1         | 1      | 1.39%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 1.39%   |
| Samsung Electronics SSD 980 1TB              | 1         | 2      | 1.39%   |
| Samsung Electronics SSD 870 EVO 1TB          | 1         | 1      | 1.39%   |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 20     | 23.61%  |
| Seagate             | 12        | 13     | 16.67%  |
| HGST                | 9         | 10     | 12.5%   |
| Hitachi             | 8         | 10     | 11.11%  |
| Toshiba             | 5         | 5      | 6.94%   |
| Samsung Electronics | 3         | 4      | 4.17%   |
| Kingston            | 3         | 7      | 4.17%   |
| SK hynix            | 2         | 2      | 2.78%   |
| Unknown             | 1         | 1      | 1.39%   |
| Transcend           | 1         | 1      | 1.39%   |
| SPCC                | 1         | 1      | 1.39%   |
| LITEON              | 1         | 1      | 1.39%   |
| Kingmax             | 1         | 1      | 1.39%   |
| KingFast            | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| GOLDTECH            | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |
| CSD                 | 1         | 1      | 1.39%   |
| Crucial             | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| AGI                 | 1         | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 17     | 28%     |
| Seagate | 12        | 13     | 24%     |
| HGST    | 9         | 10     | 18%     |
| Hitachi | 8         | 10     | 16%     |
| Toshiba | 5         | 5      | 10%     |
| Fujitsu | 1         | 1      | 2%      |
| CSD     | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 57     | 70%     |
| SSD  | 18        | 23     | 25.71%  |
| NVMe | 3         | 4      | 4.29%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB        | 1         | 1      | 50%     |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 354       | 612    | 45.85%  |
| Detected | 351       | 581    | 45.47%  |
| Malfunc  | 65        | 84     | 8.42%   |
| Failed   | 2         | 2      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 482       | 52.79%  |
| Samsung Electronics            | 123       | 13.47%  |
| AMD                            | 70        | 7.67%   |
| SanDisk                        | 44        | 4.82%   |
| SK hynix                       | 42        | 4.6%    |
| Micron Technology              | 36        | 3.94%   |
| Kingston Technology Company    | 21        | 2.3%    |
| Toshiba America Info Systems   | 15        | 1.64%   |
| Phison Electronics             | 13        | 1.42%   |
| KIOXIA                         | 13        | 1.42%   |
| Silicon Motion                 | 9         | 0.99%   |
| MAXIO Technology (Hangzhou)    | 9         | 0.99%   |
| Solid State Storage Technology | 5         | 0.55%   |
| Micron/Crucial Technology      | 4         | 0.44%   |
| ASMedia Technology             | 4         | 0.44%   |
| ADATA Technology               | 4         | 0.44%   |
| Realtek Semiconductor          | 3         | 0.33%   |
| Marvell Technology Group       | 3         | 0.33%   |
| Union Memory (Shenzhen)        | 2         | 0.22%   |
| Lite-On Technology             | 2         | 0.22%   |
| Lenovo                         | 2         | 0.22%   |
| Shenzhen Longsys Electronics   | 1         | 0.11%   |
| OCZ Technology Group           | 1         | 0.11%   |
| O2 Micro                       | 1         | 0.11%   |
| LSI Logic / Symbios Logic      | 1         | 0.11%   |
| JMicron Technology             | 1         | 0.11%   |
| Hosin Global Electronics       | 1         | 0.11%   |
| Broadcom / LSI                 | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 61        | 6.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 44        | 4.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 43        | 4.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41        | 4.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 38        | 3.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31        | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 24        | 2.41%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 20        | 2.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 19        | 1.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19        | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 19        | 1.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 18        | 1.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 18        | 1.81%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 17        | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 17        | 1.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 1.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 15        | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15        | 1.51%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15        | 1.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 12        | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 12        | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 11        | 1.1%    |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 1.1%    |
| SK hynix BC501 NVMe Solid State Drive                                                   | 10        | 1%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 9         | 0.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 9         | 0.9%    |
| Intel SATA Controller [RAID Mode]                                                       | 9         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 0.9%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 8         | 0.8%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 8         | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 0.8%    |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 8         | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 7         | 0.7%    |
| Micron 3400 NVMe SSD [Hendrix]                                                          | 7         | 0.7%    |
| Micron 2210 NVMe SSD [Cobain]                                                           | 7         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 474       | 52.15%  |
| NVMe | 336       | 36.96%  |
| RAID | 63        | 6.93%   |
| IDE  | 35        | 3.85%   |
| SAS  | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 554       | 80.41%  |
| AMD    | 129       | 18.72%  |
| ARM    | 6         | 0.87%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 19        | 2.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 13        | 1.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 1.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 10        | 1.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 9         | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 9         | 1.3%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 1.3%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 8         | 1.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 8         | 1.16%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 7         | 1.01%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 7         | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 1.01%   |
| Intel 12th Gen Core i7-12700H           | 7         | 1.01%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 7         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 6         | 0.87%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 6         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 6         | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 0.87%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz | 6         | 0.87%   |
| ARM Processor                           | 6         | 0.87%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 6         | 0.87%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 5         | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 0.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 5         | 0.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 5         | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 5         | 0.72%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 5         | 0.72%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 4         | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 0.58%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 4         | 0.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 4         | 0.58%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 4         | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 4         | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 0.58%   |
| Intel Core i3-7100 CPU @ 3.90GHz        | 4         | 0.58%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 4         | 0.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 4         | 0.58%   |
| Intel 12th Gen Core i5-12400F           | 4         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 192       | 27.87%  |
| Intel Core i7           | 114       | 16.55%  |
| Other                   | 83        | 12.05%  |
| Intel Core i3           | 69        | 10.01%  |
| AMD Ryzen 5             | 52        | 7.55%   |
| AMD Ryzen 7             | 45        | 6.53%   |
| Intel Celeron           | 23        | 3.34%   |
| Intel Xeon              | 21        | 3.05%   |
| Intel Core 2 Duo        | 16        | 2.32%   |
| Intel Atom              | 9         | 1.31%   |
| Intel Pentium           | 8         | 1.16%   |
| Intel Core i9           | 7         | 1.02%   |
| AMD Ryzen 9             | 7         | 1.02%   |
| AMD Ryzen 3             | 6         | 0.87%   |
| AMD Ryzen 7 PRO         | 5         | 0.73%   |
| Intel Xeon Silver       | 3         | 0.44%   |
| Intel Genuine           | 3         | 0.44%   |
| Intel Core              | 3         | 0.44%   |
| AMD Ryzen 5 PRO         | 3         | 0.44%   |
| AMD A10                 | 3         | 0.44%   |
| Intel Pentium Silver    | 2         | 0.29%   |
| Intel Pentium Gold      | 2         | 0.29%   |
| Intel Core M            | 2         | 0.29%   |
| AMD Athlon              | 2         | 0.29%   |
| AMD A8                  | 2         | 0.29%   |
| Intel Pentium Dual-Core | 1         | 0.15%   |
| Intel Pentium Dual      | 1         | 0.15%   |
| Intel Core m7           | 1         | 0.15%   |
| Intel Core 2 Quad       | 1         | 0.15%   |
| AMD Phenom II X4        | 1         | 0.15%   |
| AMD E                   | 1         | 0.15%   |
| AMD Athlon II X2        | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 232       | 33.57%  |
| 2       | 231       | 33.43%  |
| 6       | 99        | 14.33%  |
| 8       | 67        | 9.7%    |
| 14      | 14        | 2.03%   |
| 12      | 13        | 1.88%   |
| 10      | 13        | 1.88%   |
| 16      | 8         | 1.16%   |
| Unknown | 4         | 0.58%   |
| 24      | 3         | 0.43%   |
| 1       | 3         | 0.43%   |
| 36      | 1         | 0.14%   |
| 28      | 1         | 0.14%   |
| 20      | 1         | 0.14%   |
| 11      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 678       | 98.26%  |
| 2       | 7         | 1.01%   |
| Unknown | 4         | 0.58%   |
| 11      | 1         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 551       | 79.62%  |
| 1       | 137       | 19.8%   |
| Unknown | 4         | 0.58%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 682       | 98.84%  |
| Unknown        | 7         | 1.01%   |
| 64-bit         | 1         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 308       | 43.02%  |
| 0x306a9    | 37        | 5.17%   |
| 0x806ea    | 27        | 3.77%   |
| 0x206a7    | 22        | 3.07%   |
| 0x306c3    | 19        | 2.65%   |
| 0x906ea    | 18        | 2.51%   |
| 0x806ec    | 17        | 2.37%   |
| 0x40651    | 17        | 2.37%   |
| 0x806c1    | 16        | 2.23%   |
| 0x806e9    | 15        | 2.09%   |
| 0x306d4    | 14        | 1.96%   |
| 0x906e9    | 12        | 1.68%   |
| 0x1067a    | 11        | 1.54%   |
| 0x08600106 | 10        | 1.4%    |
| 0x506e3    | 9         | 1.26%   |
| 0x406e3    | 8         | 1.12%   |
| 0x0a50000d | 8         | 1.12%   |
| 0x0a50000c | 8         | 1.12%   |
| 0x08608103 | 8         | 1.12%   |
| 0xa0652    | 5         | 0.7%    |
| 0x906ed    | 5         | 0.7%    |
| 0x906a3    | 5         | 0.7%    |
| 0x806d1    | 5         | 0.7%    |
| 0x6fd      | 5         | 0.7%    |
| 0x20655    | 5         | 0.7%    |
| 0x0a404102 | 5         | 0.7%    |
| 0xa0653    | 4         | 0.56%   |
| 0x706e5    | 4         | 0.56%   |
| 0x706a1    | 4         | 0.56%   |
| 0x406c4    | 4         | 0.56%   |
| 0x08600104 | 4         | 0.56%   |
| 0x08108109 | 4         | 0.56%   |
| 0x08108102 | 4         | 0.56%   |
| 0x906eb    | 3         | 0.42%   |
| 0x906c0    | 3         | 0.42%   |
| 0x206d7    | 3         | 0.42%   |
| 0x0a201016 | 3         | 0.42%   |
| 0x08600103 | 3         | 0.42%   |
| 0x0810100b | 3         | 0.42%   |
| 0x90675    | 2         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 153       | 22.21%  |
| Haswell           | 65        | 9.43%   |
| Unknown           | 63        | 9.14%   |
| IvyBridge         | 57        | 8.27%   |
| Skylake           | 41        | 5.95%   |
| Zen 3             | 35        | 5.08%   |
| SandyBridge       | 33        | 4.79%   |
| Broadwell         | 30        | 4.35%   |
| Zen 2             | 29        | 4.21%   |
| TigerLake         | 26        | 3.77%   |
| Alderlake Hybrid  | 26        | 3.77%   |
| CometLake         | 20        | 2.9%    |
| Zen+              | 15        | 2.18%   |
| Penryn            | 15        | 2.18%   |
| Icelake           | 14        | 2.03%   |
| Silvermont        | 12        | 1.74%   |
| Westmere          | 10        | 1.45%   |
| Goldmont plus     | 8         | 1.16%   |
| Core              | 7         | 1.02%   |
| Zen               | 6         | 0.87%   |
| Bonnell           | 5         | 0.73%   |
| Tremont           | 3         | 0.44%   |
| Steamroller       | 3         | 0.44%   |
| Nehalem           | 2         | 0.29%   |
| Meteorlake Hybrid | 2         | 0.29%   |
| K10               | 2         | 0.29%   |
| Gracemont         | 2         | 0.29%   |
| Goldmont          | 2         | 0.29%   |
| Puma              | 1         | 0.15%   |
| Piledriver        | 1         | 0.15%   |
| Bobcat            | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 458       | 51.63%  |
| Nvidia                     | 261       | 29.43%  |
| AMD                        | 165       | 18.6%   |
| ASPEED Technology          | 2         | 0.23%   |
| Matrox Electronics Systems | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 37        | 4.11%   |
| Intel UHD Graphics 620                                                                   | 34        | 3.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 2.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 2.66%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 24        | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 2.33%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 19        | 2.11%   |
| Intel HD Graphics 620                                                                    | 18        | 2%      |
| Intel HD Graphics 5500                                                                   | 18        | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 1.55%   |
| Intel HD Graphics 630                                                                    | 14        | 1.55%   |
| Intel HD Graphics 530                                                                    | 14        | 1.55%   |
| AMD Lucienne                                                                             | 14        | 1.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 1.44%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 11        | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.22%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 11        | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 9         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1%      |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.89%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 8         | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.78%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 7         | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.67%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 6         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 295       | 42.63%  |
| Intel + Nvidia  | 132       | 19.08%  |
| 1 x AMD         | 100       | 14.45%  |
| 1 x Nvidia      | 89        | 12.86%  |
| AMD + Nvidia    | 35        | 5.06%   |
| Intel + AMD     | 26        | 3.76%   |
| Other           | 7         | 1.01%   |
| 2 x AMD         | 4         | 0.58%   |
| Nvidia + ASPEED | 2         | 0.29%   |
| 3 x Nvidia      | 1         | 0.14%   |
| 1 x Matrox      | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 499       | 70.98%  |
| Proprietary | 180       | 25.6%   |
| Unknown     | 24        | 3.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 447       | 62.96%  |
| 1.01-2.0   | 72        | 10.14%  |
| 3.01-4.0   | 57        | 8.03%   |
| 0.01-0.5   | 48        | 6.76%   |
| 0.51-1.0   | 30        | 4.23%   |
| 7.01-8.0   | 19        | 2.68%   |
| 8.01-16.0  | 16        | 2.25%   |
| 5.01-6.0   | 15        | 2.11%   |
| 2.01-3.0   | 4         | 0.56%   |
| 4.01-5.0   | 1         | 0.14%   |
| 16.01-24.0 | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 108       | 14.44%  |
| Chimei Innolux          | 89        | 11.9%   |
| AU Optronics            | 87        | 11.63%  |
| Samsung Electronics     | 75        | 10.03%  |
| Dell                    | 73        | 9.76%   |
| LG Display              | 63        | 8.42%   |
| Goldstar                | 34        | 4.55%   |
| Sharp                   | 17        | 2.27%   |
| PANDA                   | 17        | 2.27%   |
| ViewSonic               | 15        | 2.01%   |
| Hewlett-Packard         | 13        | 1.74%   |
| Apple                   | 13        | 1.74%   |
| AOC                     | 11        | 1.47%   |
| ASUSTek Computer        | 9         | 1.2%    |
| Lenovo                  | 8         | 1.07%   |
| InfoVision              | 7         | 0.94%   |
| Chi Mei Optoelectronics | 7         | 0.94%   |
| Acer                    | 7         | 0.94%   |
| CSO                     | 6         | 0.8%    |
| Mi                      | 5         | 0.67%   |
| LGD                     | 5         | 0.67%   |
| Gigabyte Technology     | 5         | 0.67%   |
| Ancor Communications    | 5         | 0.67%   |
| TMX                     | 4         | 0.53%   |
| RTK                     | 4         | 0.53%   |
| MSI                     | 4         | 0.53%   |
| BenQ                    | 4         | 0.53%   |
| Sony                    | 3         | 0.4%    |
| Panasonic               | 3         | 0.4%    |
| HKC                     | 3         | 0.4%    |
| Unknown                 | 3         | 0.4%    |
| Unknown                 | 2         | 0.27%   |
| Philips                 | 2         | 0.27%   |
| MStar                   | 2         | 0.27%   |
| LG Electronics          | 2         | 0.27%   |
| Fujitsu                 | 2         | 0.27%   |
| FPT                     | 2         | 0.27%   |
| XYM                     | 1         | 0.13%   |
| VSP                     | 1         | 0.13%   |
| VIE                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 10        | 1.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 1.06%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 7         | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.93%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6         | 0.79%   |
| LGD LCD Monitor 1920x1080                                             | 5         | 0.66%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.66%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 0.53%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.53%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 4         | 0.53%   |
| Dell SE198WFP DELF004 1440x900 408x255mm 18.9-inch                    | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.53%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.53%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 3         | 0.4%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.4%    |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch   | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.4%    |
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                     | 3         | 0.4%    |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 3         | 0.4%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 3         | 0.4%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 0.4%    |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                     | 3         | 0.4%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.4%    |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch      | 3         | 0.4%    |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.4%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.4%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.4%    |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 3         | 0.4%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.4%    |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 3         | 0.4%    |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 3         | 0.4%    |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 3         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 359       | 51.14%  |
| 1366x768 (WXGA)    | 128       | 18.23%  |
| 2560x1440 (QHD)    | 40        | 5.7%    |
| 3840x2160 (4K)     | 32        | 4.56%   |
| 1920x1200 (WUXGA)  | 20        | 2.85%   |
| 1600x900 (HD+)     | 19        | 2.71%   |
| 2560x1600          | 17        | 2.42%   |
| 2880x1800          | 14        | 1.99%   |
| 1280x1024 (SXGA)   | 13        | 1.85%   |
| 1440x900 (WXGA+)   | 11        | 1.57%   |
| 1280x800 (WXGA)    | 8         | 1.14%   |
| Unknown            | 6         | 0.85%   |
| 3440x1440          | 5         | 0.71%   |
| 2160x1440          | 5         | 0.71%   |
| 2560x1080          | 4         | 0.57%   |
| 3200x1800 (QHD+)   | 2         | 0.28%   |
| 2288x1287          | 2         | 0.28%   |
| 1920x1280          | 2         | 0.28%   |
| 800x1280           | 1         | 0.14%   |
| 3840x2400          | 1         | 0.14%   |
| 3840x1080          | 1         | 0.14%   |
| 3456x2160          | 1         | 0.14%   |
| 3286x1080          | 1         | 0.14%   |
| 3200x2000          | 1         | 0.14%   |
| 3000x2000          | 1         | 0.14%   |
| 2880x1920          | 1         | 0.14%   |
| 2240x1400          | 1         | 0.14%   |
| 2048x1536          | 1         | 0.14%   |
| 1680x1050 (WSXGA+) | 1         | 0.14%   |
| 1600x2560          | 1         | 0.14%   |
| 1360x768           | 1         | 0.14%   |
| 1200x1920          | 1         | 0.14%   |
| 1024x600           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 204       | 27.35%  |
| 14      | 106       | 14.21%  |
| 13      | 96        | 12.87%  |
| 24      | 43        | 5.76%   |
| 27      | 41        | 5.5%    |
| 21      | 40        | 5.36%   |
| 23      | 36        | 4.83%   |
| Unknown | 33        | 4.42%   |
| 17      | 22        | 2.95%   |
| 31      | 16        | 2.14%   |
| 16      | 15        | 2.01%   |
| 19      | 14        | 1.88%   |
| 18      | 14        | 1.88%   |
| 12      | 13        | 1.74%   |
| 20      | 8         | 1.07%   |
| 34      | 7         | 0.94%   |
| 11      | 6         | 0.8%    |
| 25      | 5         | 0.67%   |
| 84      | 4         | 0.54%   |
| 54      | 3         | 0.4%    |
| 142     | 2         | 0.27%   |
| 57      | 2         | 0.27%   |
| 40      | 2         | 0.27%   |
| 28      | 2         | 0.27%   |
| 7       | 2         | 0.27%   |
| 86      | 1         | 0.13%   |
| 72      | 1         | 0.13%   |
| 55      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 44      | 1         | 0.13%   |
| 43      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |
| 10      | 1         | 0.13%   |
| 9       | 1         | 0.13%   |
| 8       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 381       | 51.63%  |
| 501-600        | 118       | 15.99%  |
| 401-500        | 72        | 9.76%   |
| 201-300        | 62        | 8.4%    |
| Unknown        | 33        | 4.47%   |
| 351-400        | 22        | 2.98%   |
| 601-700        | 19        | 2.57%   |
| 701-800        | 8         | 1.08%   |
| 1501-2000      | 6         | 0.81%   |
| 1001-1500      | 6         | 0.81%   |
| 801-900        | 3         | 0.41%   |
| 101-200        | 3         | 0.41%   |
| More than 2000 | 2         | 0.27%   |
| 901-1000       | 2         | 0.27%   |
| 1-100          | 1         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 526       | 78.86%  |
| 16/10   | 70        | 10.49%  |
| Unknown | 31        | 4.65%   |
| 3/2     | 11        | 1.65%   |
| 5/4     | 10        | 1.5%    |
| 21/9    | 9         | 1.35%   |
| 4/3     | 3         | 0.45%   |
| 1.00    | 2         | 0.3%    |
| 0.56    | 2         | 0.3%    |
| 0.67    | 1         | 0.15%   |
| 0.62    | 1         | 0.15%   |
| 0.58    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 202       | 27.11%  |
| 81-90          | 172       | 23.09%  |
| 201-250        | 97        | 13.02%  |
| 301-350        | 41        | 5.5%    |
| 151-200        | 34        | 4.56%   |
| Unknown        | 33        | 4.43%   |
| 71-80          | 30        | 4.03%   |
| 351-500        | 23        | 3.09%   |
| 141-150        | 20        | 2.68%   |
| 251-300        | 17        | 2.28%   |
| 111-120        | 16        | 2.15%   |
| More than 1000 | 15        | 2.01%   |
| 121-130        | 14        | 1.88%   |
| 61-70          | 12        | 1.61%   |
| 51-60          | 6         | 0.81%   |
| 501-1000       | 5         | 0.67%   |
| 1-40           | 3         | 0.4%    |
| 41-50          | 2         | 0.27%   |
| 91-100         | 2         | 0.27%   |
| 131-140        | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 260       | 35.57%  |
| 101-120       | 172       | 23.53%  |
| 51-100        | 164       | 22.44%  |
| 161-240       | 66        | 9.03%   |
| Unknown       | 33        | 4.51%   |
| More than 240 | 24        | 3.28%   |
| 1-50          | 12        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 576       | 81.13%  |
| 2     | 94        | 13.24%  |
| 0     | 34        | 4.79%   |
| 3     | 5         | 0.7%    |
| 5     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 397       | 37.88%  |
| Intel                                  | 369       | 35.21%  |
| Qualcomm Atheros                       | 94        | 8.97%   |
| Broadcom                               | 47        | 4.48%   |
| MediaTek                               | 38        | 3.63%   |
| Broadcom Limited                       | 17        | 1.62%   |
| TP-Link                                | 12        | 1.15%   |
| ASIX Electronics                       | 12        | 1.15%   |
| Ralink Technology                      | 11        | 1.05%   |
| Samsung Electronics                    | 9         | 0.86%   |
| Marvell Technology Group               | 6         | 0.57%   |
| Xiaomi                                 | 5         | 0.48%   |
| Ralink                                 | 4         | 0.38%   |
| Hewlett-Packard                        | 3         | 0.29%   |
| D-Link                                 | 3         | 0.29%   |
| Microsoft                              | 2         | 0.19%   |
| DisplayLink                            | 2         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Sierra Wireless                        | 1         | 0.1%    |
| SEGGER                                 | 1         | 0.1%    |
| Research In Motion                     | 1         | 0.1%    |
| Qualcomm Atheros Communications        | 1         | 0.1%    |
| Qualcomm                               | 1         | 0.1%    |
| Novatel Wireless                       | 1         | 0.1%    |
| ICS Advent                             | 1         | 0.1%    |
| Huawei Technologies                    | 1         | 0.1%    |
| Foxconn / Hon Hai                      | 1         | 0.1%    |
| Ericsson Business Mobile Networks      | 1         | 0.1%    |
| Edimax Technology                      | 1         | 0.1%    |
| Dell                                   | 1         | 0.1%    |
| ASUSTek Computer                       | 1         | 0.1%    |
| Arduino SA                             | 1         | 0.1%    |
| Aquantia                               | 1         | 0.1%    |
| Unknown                                | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 275       | 22.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 3.26%   |
| Intel Wi-Fi 6 AX200                                                    | 31        | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 2.2%    |
| Intel Wireless 8265 / 8275                                             | 26        | 2.12%   |
| Intel Wireless 3165                                                    | 23        | 1.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 22        | 1.79%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 22        | 1.79%   |
| Intel Wi-Fi 6 AX201                                                    | 22        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 18        | 1.47%   |
| Intel Wireless 7265                                                    | 17        | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 16        | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 15        | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 15        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                          | 15        | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 14        | 1.14%   |
| Intel Wireless 7260                                                    | 14        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 14        | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 13        | 1.06%   |
| Intel Wireless 8260                                                    | 13        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 12        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                   | 12        | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 11        | 0.9%    |
| Realtek Killer E2600 GbE Controller                                    | 11        | 0.9%    |
| Intel Ethernet Connection I217-LM                                      | 11        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 11        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 10        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 10        | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 8         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 8         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                         | 8         | 0.65%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 8         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 299       | 50.59%  |
| Realtek Semiconductor           | 85        | 14.38%  |
| Qualcomm Atheros                | 79        | 13.37%  |
| Broadcom                        | 40        | 6.77%   |
| MediaTek                        | 34        | 5.75%   |
| Broadcom Limited                | 17        | 2.88%   |
| TP-Link                         | 12        | 2.03%   |
| Ralink Technology               | 11        | 1.86%   |
| Ralink                          | 4         | 0.68%   |
| D-Link                          | 3         | 0.51%   |
| Xiaomi                          | 1         | 0.17%   |
| Sierra Wireless                 | 1         | 0.17%   |
| Qualcomm Atheros Communications | 1         | 0.17%   |
| Marvell Technology Group        | 1         | 0.17%   |
| Edimax Technology               | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |
| ASUSTek Computer                | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 31        | 5.2%    |
| Intel Wireless 8265 / 8275                                     | 26        | 4.36%   |
| Intel Wireless 3165                                            | 23        | 3.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 3.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 22        | 3.69%   |
| Intel Wi-Fi 6 AX201                                            | 22        | 3.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 3.02%   |
| Intel Wireless 7265                                            | 17        | 2.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 2.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 2.52%   |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 2.35%   |
| Intel Wireless 7260                                            | 14        | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 2.18%   |
| Intel Wireless 8260                                            | 13        | 2.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 2.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 12        | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 1.34%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.34%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 8         | 1.34%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7         | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 6         | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 1.01%   |
| Realtek 802.11ac NIC                                           | 6         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.01%   |
| Intel Wireless 3160                                            | 6         | 1.01%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 6         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 1.01%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 6         | 1.01%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 363       | 60%     |
| Intel                                  | 163       | 26.94%  |
| Qualcomm Atheros                       | 23        | 3.8%    |
| ASIX Electronics                       | 12        | 1.98%   |
| Broadcom                               | 9         | 1.49%   |
| Samsung Electronics                    | 7         | 1.16%   |
| MediaTek                               | 6         | 0.99%   |
| Marvell Technology Group               | 5         | 0.83%   |
| Xiaomi                                 | 4         | 0.66%   |
| Microsoft                              | 2         | 0.33%   |
| Hewlett-Packard                        | 2         | 0.33%   |
| DisplayLink                            | 2         | 0.33%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.17%   |
| Research In Motion                     | 1         | 0.17%   |
| Qualcomm                               | 1         | 0.17%   |
| ICS Advent                             | 1         | 0.17%   |
| Huawei Technologies                    | 1         | 0.17%   |
| Foxconn / Hon Hai                      | 1         | 0.17%   |
| Aquantia                               | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 275       | 44.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 6.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27        | 4.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 2.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 15        | 2.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 2.41%   |
| Intel Ethernet Connection (7) I219-V                                   | 12        | 1.93%   |
| Realtek Killer E2600 GbE Controller                                    | 11        | 1.77%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 1.77%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 1.44%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 1.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 1.12%   |
| Intel I210 Gigabit Network Connection                                  | 7         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 6         | 0.96%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 0.96%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 0.8%    |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.8%    |
| Intel Ethernet Connection (5) I219-LM                                  | 5         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.64%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.48%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 3         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.48%   |
| Intel Ethernet Connection X722 for 1GbE                                | 3         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.48%   |
| Intel Ethernet Connection (14) I219-V                                  | 3         | 0.48%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.48%   |
| ASIX AX88772A Fast Ethernet                                            | 3         | 0.48%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 572       | 49.7%   |
| Ethernet | 571       | 49.61%  |
| Modem    | 7         | 0.61%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 480       | 67.42%  |
| Ethernet | 231       | 32.44%  |
| Modem    | 1         | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 409       | 59.02%  |
| 1     | 259       | 37.37%  |
| 3     | 15        | 2.16%   |
| 0     | 8         | 1.15%   |
| 4     | 2         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 494       | 69.87%  |
| Yes  | 213       | 30.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 263       | 51.27%  |
| Realtek Semiconductor           | 47        | 9.16%   |
| Qualcomm Atheros Communications | 43        | 8.38%   |
| IMC Networks                    | 27        | 5.26%   |
| Broadcom                        | 27        | 5.26%   |
| Cambridge Silicon Radio         | 21        | 4.09%   |
| Lite-On Technology              | 20        | 3.9%    |
| Foxconn / Hon Hai               | 20        | 3.9%    |
| Apple                           | 14        | 2.73%   |
| Realtek                         | 5         | 0.97%   |
| MediaTek                        | 5         | 0.97%   |
| Dell                            | 5         | 0.97%   |
| Hewlett-Packard                 | 4         | 0.78%   |
| TP-Link                         | 3         | 0.58%   |
| Ralink                          | 2         | 0.39%   |
| Toshiba                         | 1         | 0.19%   |
| Opticis                         | 1         | 0.19%   |
| Marvell Semiconductor           | 1         | 0.19%   |
| Foxconn International           | 1         | 0.19%   |
| Conwise Technology              | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |
| Alps Electric                   | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 91        | 17.64%  |
| Intel AX201 Bluetooth                               | 60        | 11.63%  |
| Realtek Bluetooth Radio                             | 32        | 6.2%    |
| Intel AX200 Bluetooth                               | 31        | 6.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 5.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 4.65%   |
| Intel AX210 Bluetooth                               | 22        | 4.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 4.07%   |
| Intel AX211 Bluetooth                               | 17        | 3.29%   |
| IMC Networks Wireless_Device                        | 14        | 2.71%   |
| Apple Bluetooth Host Controller                     | 10        | 1.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 1.55%   |
| IMC Networks Bluetooth Radio                        | 7         | 1.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.16%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 1.16%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 1.16%   |
| Realtek Bluetooth Radio                             | 5         | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 0.97%   |
| MediaTek Wireless_Device                            | 5         | 0.97%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 5         | 0.97%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.78%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.78%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 3         | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.58%   |
| Lite-On Wireless_Device                             | 3         | 0.58%   |
| Lite-On Bluetooth Radio                             | 3         | 0.58%   |
| Lite-On Bluetooth Device                            | 3         | 0.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.58%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.58%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 0.58%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.39%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 545       | 56.95%  |
| Nvidia                    | 191       | 19.96%  |
| AMD                       | 152       | 15.88%  |
| Generalplus Technology    | 9         | 0.94%   |
| C-Media Electronics       | 8         | 0.84%   |
| Realtek Semiconductor     | 4         | 0.42%   |
| Logitech                  | 4         | 0.42%   |
| Texas Instruments         | 3         | 0.31%   |
| JMTek                     | 3         | 0.31%   |
| Creative Labs             | 3         | 0.31%   |
| Audient                   | 3         | 0.31%   |
| ASUSTek Computer          | 3         | 0.31%   |
| Shenzhen Rapoo Technology | 2         | 0.21%   |
| Kingston Technology       | 2         | 0.21%   |
| FIFINE Microphones        | 2         | 0.21%   |
| Elgato Systems            | 2         | 0.21%   |
| Apple                     | 2         | 0.21%   |
| Walmart                   | 1         | 0.1%    |
| USB2.0                    | 1         | 0.1%    |
| Plantronics               | 1         | 0.1%    |
| OPPO Electronics          | 1         | 0.1%    |
| Nordic Semiconductor ASA  | 1         | 0.1%    |
| Microsoft                 | 1         | 0.1%    |
| Micro Star International  | 1         | 0.1%    |
| Jieli Technology          | 1         | 0.1%    |
| GYROCOM C&C               | 1         | 0.1%    |
| GN Netcom                 | 1         | 0.1%    |
| EDFIER                    | 1         | 0.1%    |
| Creative Technology       | 1         | 0.1%    |
| Corsair                   | 1         | 0.1%    |
| Conexant Systems          | 1         | 0.1%    |
| AudioQuest                | 1         | 0.1%    |
| Audeze                    | 1         | 0.1%    |
| AGPTek                    | 1         | 0.1%    |
| - KTMicro -               | 1         | 0.1%    |
| Unknown                   | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 95        | 8.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 71        | 6.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 57        | 5.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49        | 4.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 40        | 3.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 38        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 37        | 3.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 26        | 2.29%   |
| Intel Broadwell-U Audio Controller                                         | 25        | 2.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 24        | 2.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 24        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23        | 2.03%   |
| Intel Haswell-ULT HD Audio Controller                                      | 23        | 2.03%   |
| Intel 8 Series HD Audio Controller                                         | 23        | 2.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 21        | 1.85%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20        | 1.77%   |
| Nvidia GA107 High Definition Audio Controller                              | 18        | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1.5%    |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 1.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 1.5%    |
| Intel 200 Series PCH HD Audio                                              | 15        | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.24%   |
| Nvidia TU116 High Definition Audio Controller                              | 13        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12        | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 1.06%   |
| Intel CM238 HD Audio Controller                                            | 12        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10        | 0.88%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 0.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 0.79%   |
| Generalplus Technology USB Audio Device                                    | 9         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 134       | 24.5%   |
| SK hynix                                | 96        | 17.55%  |
| Kingston                                | 91        | 16.64%  |
| Micron Technology                       | 72        | 13.16%  |
| G.Skill                                 | 30        | 5.48%   |
| Corsair                                 | 22        | 4.02%   |
| Unknown                                 | 18        | 3.29%   |
| Crucial                                 | 17        | 3.11%   |
| A-DATA Technology                       | 12        | 2.19%   |
| Ramaxel Technology                      | 10        | 1.83%   |
| Kingmax                                 | 10        | 1.83%   |
| Team                                    | 5         | 0.91%   |
| Elpida                                  | 4         | 0.73%   |
| Apacer                                  | 4         | 0.73%   |
| Unknown                                 | 4         | 0.73%   |
| Kingmax Semiconductor                   | 3         | 0.55%   |
| Nanya Technology                        | 2         | 0.37%   |
| Unknown (ABCD)                          | 1         | 0.18%   |
| Unknown (8A02)                          | 1         | 0.18%   |
| Unknown (7FE0)                          | 1         | 0.18%   |
| Silicon Power Computer & Communications | 1         | 0.18%   |
| PUSKILL                                 | 1         | 0.18%   |
| PNY                                     | 1         | 0.18%   |
| Pioneer                                 | 1         | 0.18%   |
| Patriot                                 | 1         | 0.18%   |
| Lexar Co Limited                        | 1         | 0.18%   |
| KingFast                                | 1         | 0.18%   |
| ChangXin Memory                         | 1         | 0.18%   |
| AVEXIR                                  | 1         | 0.18%   |
| ASint Technology                        | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 7         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 7         | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 6         | 1.01%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s     | 6         | 1.01%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 6         | 1.01%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 0.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 0.84%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 5         | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 5         | 0.84%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 5         | 0.84%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 5         | 0.84%   |
| Kingston RAM 9905700-122.A00G 16GB SODIMM DDR4 3200MT/s      | 5         | 0.84%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3200MT/s         | 5         | 0.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 4         | 0.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 4         | 0.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 0.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 4         | 0.67%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.67%   |
| G.Skill RAM F4-3200C22-8GRS 8GB SODIMM DDR4 3200MT/s         | 4         | 0.67%   |
| Unknown                                                      | 4         | 0.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 3         | 0.51%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 3         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 0.51%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 3         | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 0.51%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 0.51%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 3         | 0.51%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 3         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 3         | 0.51%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 3         | 0.51%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s        | 3         | 0.51%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 2         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 262       | 59.55%  |
| DDR3    | 110       | 25%     |
| DDR5    | 20        | 4.55%   |
| LPDDR4  | 16        | 3.64%   |
| LPDDR5  | 11        | 2.5%    |
| LPDDR3  | 10        | 2.27%   |
| DDR2    | 5         | 1.14%   |
| DRAM    | 2         | 0.45%   |
| Unknown | 2         | 0.45%   |
| SDRAM   | 1         | 0.23%   |
| DDR     | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 284       | 64.55%  |
| DIMM         | 116       | 26.36%  |
| Row Of Chips | 39        | 8.86%   |
| Unknown      | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 212       | 43.98%  |
| 4096  | 121       | 25.1%   |
| 16384 | 100       | 20.75%  |
| 2048  | 23        | 4.77%   |
| 32768 | 18        | 3.73%   |
| 1024  | 8         | 1.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 125       | 25.46%  |
| 2667    | 86        | 17.52%  |
| 1600    | 83        | 16.9%   |
| 2400    | 43        | 8.76%   |
| 1333    | 19        | 3.87%   |
| 2133    | 16        | 3.26%   |
| 5600    | 9         | 1.83%   |
| 6400    | 7         | 1.43%   |
| 4800    | 7         | 1.43%   |
| 3600    | 7         | 1.43%   |
| 1867    | 7         | 1.43%   |
| 1334    | 7         | 1.43%   |
| 4267    | 6         | 1.22%   |
| 3733    | 5         | 1.02%   |
| 7500    | 4         | 0.81%   |
| 3000    | 4         | 0.81%   |
| 2666    | 4         | 0.81%   |
| 800     | 4         | 0.81%   |
| 8400    | 3         | 0.61%   |
| 3666    | 3         | 0.61%   |
| 3466    | 3         | 0.61%   |
| 3266    | 3         | 0.61%   |
| 2933    | 3         | 0.61%   |
| 1067    | 3         | 0.61%   |
| 1066    | 3         | 0.61%   |
| Unknown | 3         | 0.61%   |
| 5200    | 2         | 0.41%   |
| 3400    | 2         | 0.41%   |
| 2800    | 2         | 0.41%   |
| 2448    | 2         | 0.41%   |
| 1866    | 2         | 0.41%   |
| 667     | 2         | 0.41%   |
| 7467    | 1         | 0.2%    |
| 7000    | 1         | 0.2%    |
| 4266    | 1         | 0.2%    |
| 4199    | 1         | 0.2%    |
| 3334    | 1         | 0.2%    |
| 3007    | 1         | 0.2%    |
| 2734    | 1         | 0.2%    |
| 1800    | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 22.22%  |
| Brother Industries    | 2         | 22.22%  |
| Seiko Epson           | 1         | 11.11%  |
| Ricoh                 | 1         | 11.11%  |
| MIIIW                 | 1         | 11.11%  |
| Intermec Technologies | 1         | 11.11%  |
| Canon                 | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson L3110 Series   | 1         | 11.11%  |
| Ricoh Printing Support     | 1         | 11.11%  |
| MIIIW MW Keyboard Air Mini | 1         | 11.11%  |
| Intermec PC43t             | 1         | 11.11%  |
| HP LaserJet P3010 Series   | 1         | 11.11%  |
| HP LaserJet P1102          | 1         | 11.11%  |
| Canon LBP6030/6030B/6018L  | 1         | 11.11%  |
| Brother HL-L2360D series   | 1         | 11.11%  |
| Brother HL-L2320D series   | 1         | 11.11%  |

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
| Chicony Electronics                    | 86        | 18.9%   |
| IMC Networks                           | 59        | 12.97%  |
| Microdia                               | 56        | 12.31%  |
| Realtek Semiconductor                  | 38        | 8.35%   |
| Sunplus Innovation Technology          | 36        | 7.91%   |
| Quanta                                 | 28        | 6.15%   |
| Bison Electronics                      | 27        | 5.93%   |
| Syntek                                 | 16        | 3.52%   |
| Luxvisions Innotech Limited            | 16        | 3.52%   |
| Logitech                               | 12        | 2.64%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 2.64%   |
| Apple                                  | 10        | 2.2%    |
| Lite-On Technology                     | 9         | 1.98%   |
| Suyin                                  | 7         | 1.54%   |
| Acer                                   | 7         | 1.54%   |
| Sonix Technology                       | 6         | 1.32%   |
| Samsung Electronics                    | 4         | 0.88%   |
| Ricoh                                  | 4         | 0.88%   |
| Alcor Micro                            | 3         | 0.66%   |
| SN0002                                 | 2         | 0.44%   |
| Silicon Motion                         | 2         | 0.44%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.44%   |
| Denron                                 | 2         | 0.44%   |
| vivo                                   | 1         | 0.22%   |
| Shinetech                              | 1         | 0.22%   |
| Linux Foundation                       | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |
| KYE Systems (Mouse Systems)            | 1         | 0.22%   |
| Intel                                  | 1         | 0.22%   |
| IDS Imaging Development Systems        | 1         | 0.22%   |
| Hewlett-Packard                        | 1         | 0.22%   |
| Aveo Technology                        | 1         | 0.22%   |
| Alpha Imaging Technology               | 1         | 0.22%   |
| ALi                                    | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                     | 28        | 6.11%   |
| Chicony Integrated Camera                         | 28        | 6.11%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 22        | 4.8%    |
| Sunplus Integrated_Webcam_HD                      | 19        | 4.15%   |
| Realtek Integrated_Webcam_HD                      | 14        | 3.06%   |
| IMC Networks Integrated Camera                    | 14        | 3.06%   |
| Syntek Integrated Camera                          | 11        | 2.4%    |
| Bison HD Webcam                                   | 10        | 2.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 8         | 1.75%   |
| Chicony HD Webcam                                 | 8         | 1.75%   |
| Quanta HD User Facing                             | 7         | 1.53%   |
| Microdia Laptop_Integrated_Webcam_HD              | 7         | 1.53%   |
| Luxvisions Innotech Limited Integrated Camera     | 7         | 1.53%   |
| Chicony HP HD Camera                              | 7         | 1.53%   |
| Microdia Integrated Webcam                        | 6         | 1.31%   |
| Chicony HP TrueVision HD Camera                   | 6         | 1.31%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 6         | 1.31%   |
| Sonix USB2.0 HD UVC WebCam                        | 5         | 1.09%   |
| Realtek Integrated Webcam                         | 5         | 1.09%   |
| Logitech Webcam C270                              | 5         | 1.09%   |
| Bison SunplusIT Integrated Camera                 | 5         | 1.09%   |
| Bison Integrated Camera                           | 5         | 1.09%   |
| Acer Integrated Camera                            | 5         | 1.09%   |
| Samsung Galaxy series, misc. (MTP mode)           | 4         | 0.87%   |
| Realtek USB Camera                                | 4         | 0.87%   |
| Realtek Integrated Webcam HD                      | 4         | 0.87%   |
| Quanta HP TrueVision HD Camera                    | 4         | 0.87%   |
| Lite-On Integrated Camera                         | 4         | 0.87%   |
| Chicony HD User Facing                            | 4         | 0.87%   |
| Bison ThinkPad Integrated Camera                  | 4         | 0.87%   |
| Syntek Lenovo EasyCamera                          | 3         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 3         | 0.66%   |
| Quanta VGA WebCam                                 | 3         | 0.66%   |
| Quanta ov9734_techfront_camera                    | 3         | 0.66%   |
| Quanta HP HD Camera                               | 3         | 0.66%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 3         | 0.66%   |
| Luxvisions Innotech Limited HP 5MP Camera         | 3         | 0.66%   |
| IMC Networks VGA UVC WebCam                       | 3         | 0.66%   |
| IMC Networks USB2.0 UVC HD Webcam                 | 3         | 0.66%   |
| Chicony Integrated HP HD Webcam                   | 3         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 45.26%  |
| Shenzhen Goodix Technology | 22        | 23.16%  |
| Synaptics                  | 20        | 21.05%  |
| Samsung Electronics        | 3         | 3.16%   |
| Elan Microelectronics      | 3         | 3.16%   |
| LighTuning Technology      | 2         | 2.11%   |
| Upek                       | 1         | 1.05%   |
| STMicroelectronics         | 1         | 1.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 16.84%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 9.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 7.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 6.32%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 6.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 6         | 6.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 5.26%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 4.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.21%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 4.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.16%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 3.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.11%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.11%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.05%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.05%   |
| Synaptics UWP WBDI                                                         | 1         | 1.05%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.05%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.05%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.05%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.05%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 1.05%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 22        | 75.86%  |
| Alcor Micro | 4         | 13.79%  |
| Upek        | 1         | 3.45%   |
| OmniKey     | 1         | 3.45%   |
| Lenovo      | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 31.03%  |
| Broadcom 5880                                                                | 8         | 27.59%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 13.79%  |
| Broadcom 58200                                                               | 3         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.45%   |
| OmniKey CardMan 4321                                                         | 1         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 470       | 66.1%   |
| 1     | 197       | 27.71%  |
| 2     | 34        | 4.78%   |
| 3     | 7         | 0.98%   |
| 4     | 2         | 0.28%   |
| 5     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 93        | 32.98%  |
| Graphics card            | 62        | 21.99%  |
| Chipcard                 | 28        | 9.93%   |
| Net/wireless             | 24        | 8.51%   |
| Multimedia controller    | 21        | 7.45%   |
| Communication controller | 13        | 4.61%   |
| Camera                   | 12        | 4.26%   |
| Unassigned class         | 11        | 3.9%    |
| Net/ethernet             | 6         | 2.13%   |
| Bluetooth                | 6         | 2.13%   |
| Storage                  | 3         | 1.06%   |
| Card reader              | 2         | 0.71%   |
| Sound                    | 1         | 0.35%   |


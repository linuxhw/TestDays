Linux in Estonia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Estonia/Desktop/README.md) and [notebooks](/Location/Estonia/Notebook/README.md).

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

Total: 498

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ed0902f81c](https://linux-hardware.org/?probe=ed0902f81c) | May 08, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [2dee9df53a](https://linux-hardware.org/?probe=2dee9df53a) | May 02, 2024 |
| Dell          | Latitude 3300               | Notebook    | [639fb8097f](https://linux-hardware.org/?probe=639fb8097f) | May 02, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [eefd534cd5](https://linux-hardware.org/?probe=eefd534cd5) | May 01, 2024 |
| Acer          | Extensa 5620                | Notebook    | [4150199b68](https://linux-hardware.org/?probe=4150199b68) | Apr 29, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [fad4840965](https://linux-hardware.org/?probe=fad4840965) | Apr 26, 2024 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [01d705d92b](https://linux-hardware.org/?probe=01d705d92b) | Apr 25, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Gigabyte      | H81M-S                      | Desktop     | [d18c354852](https://linux-hardware.org/?probe=d18c354852) | Mar 31, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | Notebook    | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d13f0a354c](https://linux-hardware.org/?probe=d13f0a354c) | Mar 21, 2024 |
| Dell          | Inspiron 5558               | Notebook    | [2202cb6328](https://linux-hardware.org/?probe=2202cb6328) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| HP            | 650                         | Notebook    | [d58bfc527e](https://linux-hardware.org/?probe=d58bfc527e) | Mar 17, 2024 |
| ASRock        | H310M-HDV                   | Desktop     | [4e2f714f49](https://linux-hardware.org/?probe=4e2f714f49) | Mar 16, 2024 |
| ASRock        | H310M-HDV                   | Desktop     | [8d62cae785](https://linux-hardware.org/?probe=8d62cae785) | Mar 15, 2024 |
| MSI           | B85M-G43                    | Desktop     | [c1b1061c0d](https://linux-hardware.org/?probe=c1b1061c0d) | Mar 14, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [8c9bcaf098](https://linux-hardware.org/?probe=8c9bcaf098) | Mar 14, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [16dee4c095](https://linux-hardware.org/?probe=16dee4c095) | Mar 13, 2024 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | Notebook    | [d3de9797e5](https://linux-hardware.org/?probe=d3de9797e5) | Mar 07, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | Notebook    | [48c9ed444c](https://linux-hardware.org/?probe=48c9ed444c) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | Notebook    | [a8c23be08a](https://linux-hardware.org/?probe=a8c23be08a) | Mar 05, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66295fb0e8](https://linux-hardware.org/?probe=66295fb0e8) | Mar 04, 2024 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [9dbfe4a6eb](https://linux-hardware.org/?probe=9dbfe4a6eb) | Mar 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7c8e1659f2](https://linux-hardware.org/?probe=7c8e1659f2) | Feb 24, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [b1c2e786ed](https://linux-hardware.org/?probe=b1c2e786ed) | Feb 17, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0ea90e3ee0](https://linux-hardware.org/?probe=0ea90e3ee0) | Feb 17, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [50746a2234](https://linux-hardware.org/?probe=50746a2234) | Feb 09, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [779b399243](https://linux-hardware.org/?probe=779b399243) | Feb 09, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [07deb1efe3](https://linux-hardware.org/?probe=07deb1efe3) | Feb 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Dell          | Latitude 7490               | Notebook    | [d2085f3674](https://linux-hardware.org/?probe=d2085f3674) | Jan 24, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [ab07a9741b](https://linux-hardware.org/?probe=ab07a9741b) | Jan 13, 2024 |
| MSI           | Pulse GL66 11UDK            | Notebook    | [fdb748bed5](https://linux-hardware.org/?probe=fdb748bed5) | Jan 13, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [7536a68c05](https://linux-hardware.org/?probe=7536a68c05) | Jan 06, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [8991ffeadc](https://linux-hardware.org/?probe=8991ffeadc) | Jan 04, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [0863d91cdc](https://linux-hardware.org/?probe=0863d91cdc) | Dec 25, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c1069bda0b](https://linux-hardware.org/?probe=c1069bda0b) | Dec 23, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e222a97c0b](https://linux-hardware.org/?probe=e222a97c0b) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9c4f708056](https://linux-hardware.org/?probe=9c4f708056) | Dec 10, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [62734db5de](https://linux-hardware.org/?probe=62734db5de) | Dec 10, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [be768fb273](https://linux-hardware.org/?probe=be768fb273) | Dec 06, 2023 |
| HP            | 8619                        | Desktop     | [a33e273f33](https://linux-hardware.org/?probe=a33e273f33) | Dec 04, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [bb0ded92ef](https://linux-hardware.org/?probe=bb0ded92ef) | Dec 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [a1ab0858a6](https://linux-hardware.org/?probe=a1ab0858a6) | Dec 01, 2023 |
| HP            | ProBook 4530s               | Notebook    | [5743a3e441](https://linux-hardware.org/?probe=5743a3e441) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| Dell          | Precision M4600             | Notebook    | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| Dell          | Precision M4600             | Notebook    | [af124219eb](https://linux-hardware.org/?probe=af124219eb) | Nov 18, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [84650e7d6f](https://linux-hardware.org/?probe=84650e7d6f) | Nov 15, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [be33944c69](https://linux-hardware.org/?probe=be33944c69) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| ECS           | H61H2-M12                   | Desktop     | [885cbf522c](https://linux-hardware.org/?probe=885cbf522c) | Oct 28, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [235eadfef8](https://linux-hardware.org/?probe=235eadfef8) | Oct 18, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [42b86ea4ec](https://linux-hardware.org/?probe=42b86ea4ec) | Oct 18, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [506accae39](https://linux-hardware.org/?probe=506accae39) | Oct 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | Notebook    | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [9044f3b345](https://linux-hardware.org/?probe=9044f3b345) | Sep 12, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | Notebook    | [3d7ba31c2a](https://linux-hardware.org/?probe=3d7ba31c2a) | Aug 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | Notebook    | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | Notebook    | [cb5346a558](https://linux-hardware.org/?probe=cb5346a558) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | Notebook    | [4bfb2c68ca](https://linux-hardware.org/?probe=4bfb2c68ca) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d78e4ab87d](https://linux-hardware.org/?probe=d78e4ab87d) | Aug 08, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Intel         | powered classmate PC        | Notebook    | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | Desktop     | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | Notebook    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| Notebook      | N150SD/N155SD               | Notebook    | [55f219bc3f](https://linux-hardware.org/?probe=55f219bc3f) | May 11, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fdaef83d1e](https://linux-hardware.org/?probe=fdaef83d1e) | Apr 23, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| HP            | 304Ah                       | Desktop     | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6694c9279d](https://linux-hardware.org/?probe=6694c9279d) | Mar 31, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [b06257fd9c](https://linux-hardware.org/?probe=b06257fd9c) | Mar 28, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [3a0d77d195](https://linux-hardware.org/?probe=3a0d77d195) | Mar 28, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | 304Ah                       | Desktop     | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | Notebook    | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [396ad2d6aa](https://linux-hardware.org/?probe=396ad2d6aa) | Mar 04, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [07d496ada9](https://linux-hardware.org/?probe=07d496ada9) | Feb 04, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [146f307b8e](https://linux-hardware.org/?probe=146f307b8e) | Jan 10, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [efa2d6986f](https://linux-hardware.org/?probe=efa2d6986f) | Dec 28, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70436ae3c3](https://linux-hardware.org/?probe=70436ae3c3) | Dec 15, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4c5bac90eb](https://linux-hardware.org/?probe=4c5bac90eb) | Dec 15, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [2ace77f72c](https://linux-hardware.org/?probe=2ace77f72c) | Dec 14, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [0b91c8c70f](https://linux-hardware.org/?probe=0b91c8c70f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | Notebook    | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [8eb1316a14](https://linux-hardware.org/?probe=8eb1316a14) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [81374a561c](https://linux-hardware.org/?probe=81374a561c) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d88d101a3c](https://linux-hardware.org/?probe=d88d101a3c) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5405caf9dc](https://linux-hardware.org/?probe=5405caf9dc) | Oct 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26d539c606](https://linux-hardware.org/?probe=26d539c606) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASRock        | B460 Steel Legend           | Desktop     | [ca98840e23](https://linux-hardware.org/?probe=ca98840e23) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a1b08d912](https://linux-hardware.org/?probe=7a1b08d912) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3f808f36a0](https://linux-hardware.org/?probe=3f808f36a0) | Oct 13, 2022 |
| Unknown       | Seagate Personal Cloud (... | Desktop     | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| Dell          | Latitude 7390               | Notebook    | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8c56960243](https://linux-hardware.org/?probe=8c56960243) | Aug 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [5dae076f42](https://linux-hardware.org/?probe=5dae076f42) | Jul 27, 2022 |
| ECS           | G41T-M7                     | Desktop     | [a531a754a8](https://linux-hardware.org/?probe=a531a754a8) | Jul 23, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | 3646h                       | Desktop     | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [cdb4149eba](https://linux-hardware.org/?probe=cdb4149eba) | Jun 27, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [a068a18649](https://linux-hardware.org/?probe=a068a18649) | Jun 08, 2022 |
| Dell          | 088DT1 A00                  | Desktop     | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| HP            | Presario CQ57               | Notebook    | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Gigabyte      | H55M-S2                     | Desktop     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| Dell          | Latitude 5520               | Notebook    | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Lenovo        | ThinkCentre M58 7360WQK     | Desktop     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | Notebook    | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | Notebook    | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | Notebook    | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8af8994f80](https://linux-hardware.org/?probe=8af8994f80) | Apr 02, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| HP            | 18E9                        | Desktop     | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d34e3c79a0](https://linux-hardware.org/?probe=d34e3c79a0) | Mar 01, 2022 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| HP            | 304Ah                       | Desktop     | [078b605c39](https://linux-hardware.org/?probe=078b605c39) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [c9b246d9a8](https://linux-hardware.org/?probe=c9b246d9a8) | Jan 12, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [49234f883d](https://linux-hardware.org/?probe=49234f883d) | Jan 12, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [a27e7cdbef](https://linux-hardware.org/?probe=a27e7cdbef) | Jan 09, 2022 |
| Dell          | 0KH290                      | Desktop     | [e8c0e16dfb](https://linux-hardware.org/?probe=e8c0e16dfb) | Dec 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [142cab14c6](https://linux-hardware.org/?probe=142cab14c6) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0b2751c5c1](https://linux-hardware.org/?probe=0b2751c5c1) | Dec 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | Notebook    | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [e540507afc](https://linux-hardware.org/?probe=e540507afc) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [201bc8d044](https://linux-hardware.org/?probe=201bc8d044) | Oct 17, 2021 |
| Getac         | B300G4                      | Notebook    | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | Notebook    | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | Notebook    | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [95d389bfe5](https://linux-hardware.org/?probe=95d389bfe5) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [326b3f5892](https://linux-hardware.org/?probe=326b3f5892) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [c2c6287186](https://linux-hardware.org/?probe=c2c6287186) | Oct 07, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | Notebook    | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d339553d59](https://linux-hardware.org/?probe=d339553d59) | Sep 19, 2021 |
| Prestigio     | PNT10131DEDB                | Convertible | [39dc1df1df](https://linux-hardware.org/?probe=39dc1df1df) | Sep 18, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [47fb03fde8](https://linux-hardware.org/?probe=47fb03fde8) | Sep 17, 2021 |
| MSI           | MS-B901                     | All in one  | [282992f343](https://linux-hardware.org/?probe=282992f343) | Sep 14, 2021 |
| MSI           | MS-B901                     | All in one  | [3a288bcc81](https://linux-hardware.org/?probe=3a288bcc81) | Sep 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | Notebook    | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | Notebook    | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bf81c78371](https://linux-hardware.org/?probe=bf81c78371) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | Notebook    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | Notebook    | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [559742f4d7](https://linux-hardware.org/?probe=559742f4d7) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d28cc83aed](https://linux-hardware.org/?probe=d28cc83aed) | Aug 17, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [be5db43316](https://linux-hardware.org/?probe=be5db43316) | Aug 17, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [286d06cd5e](https://linux-hardware.org/?probe=286d06cd5e) | Aug 15, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [b2db3ea0a9](https://linux-hardware.org/?probe=b2db3ea0a9) | Aug 10, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [c086b1441c](https://linux-hardware.org/?probe=c086b1441c) | Aug 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| MSI           | GP62M 7RDX                  | Notebook    | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | M3N78                       | Desktop     | [810e386d8b](https://linux-hardware.org/?probe=810e386d8b) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a01d3d232](https://linux-hardware.org/?probe=7a01d3d232) | Jun 28, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | Notebook    | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | Notebook    | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | Notebook    | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | Notebook    | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | Notebook    | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | Notebook    | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | Notebook    | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| MSI           | B250M PRO-VD                | Desktop     | [20ff770033](https://linux-hardware.org/?probe=20ff770033) | Apr 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | Notebook    | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [72b40a39d4](https://linux-hardware.org/?probe=72b40a39d4) | Mar 25, 2021 |
| Samsung       | R410                        | Notebook    | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f555918663](https://linux-hardware.org/?probe=f555918663) | Mar 24, 2021 |
| Samsung       | R410                        | Notebook    | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| OEM           | Intel H81                   | Desktop     | [385b6ee448](https://linux-hardware.org/?probe=385b6ee448) | Mar 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [013a785195](https://linux-hardware.org/?probe=013a785195) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b991380f9](https://linux-hardware.org/?probe=9b991380f9) | Mar 17, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [273fba9fd2](https://linux-hardware.org/?probe=273fba9fd2) | Mar 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [75a661f9f8](https://linux-hardware.org/?probe=75a661f9f8) | Mar 14, 2021 |
| Notebook      | W35xSS_370SS                | Notebook    | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ff698cacf3](https://linux-hardware.org/?probe=ff698cacf3) | Feb 27, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [116202ee88](https://linux-hardware.org/?probe=116202ee88) | Feb 27, 2021 |
| Lenovo        | ThinkPad T61 766112G        | Notebook    | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | Notebook    | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| MSI           | MS-7267                     | Desktop     | [b987c1ad14](https://linux-hardware.org/?probe=b987c1ad14) | Feb 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e1dc5a8ea7](https://linux-hardware.org/?probe=e1dc5a8ea7) | Feb 14, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d3004980ee](https://linux-hardware.org/?probe=d3004980ee) | Feb 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| MSI           | Z77A-G41                    | Desktop     | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| Timi          | RedmiBook 16                | Notebook    | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | Notebook    | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| MSI           | H81I                        | Desktop     | [772ce7ff24](https://linux-hardware.org/?probe=772ce7ff24) | Dec 03, 2020 |
| MSI           | Boston                      | Desktop     | [9843e15faa](https://linux-hardware.org/?probe=9843e15faa) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [1280ebbedf](https://linux-hardware.org/?probe=1280ebbedf) | Nov 17, 2020 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [e1f6c727d9](https://linux-hardware.org/?probe=e1f6c727d9) | Oct 14, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [f61cacc391](https://linux-hardware.org/?probe=f61cacc391) | Oct 05, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | Notebook    | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| MSI           | X470 GAMING PRO             | Desktop     | [6b818c1352](https://linux-hardware.org/?probe=6b818c1352) | Sep 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3255a17583](https://linux-hardware.org/?probe=3255a17583) | Sep 28, 2020 |
| MSI           | Z170-A PRO                  | Desktop     | [bcf22d328e](https://linux-hardware.org/?probe=bcf22d328e) | Sep 28, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| Intel         | DX79TO AAG28805-400         | Desktop     | [d4cdc0726f](https://linux-hardware.org/?probe=d4cdc0726f) | Sep 26, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [118729faeb](https://linux-hardware.org/?probe=118729faeb) | Sep 23, 2020 |
| TUXEDO        | Book BA1510                 | Notebook    | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | Notebook    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | Notebook    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0dd7682249](https://linux-hardware.org/?probe=0dd7682249) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | Notebook    | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | Notebook    | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | Notebook    | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| ASRock        | P45DE3                      | Desktop     | [3fce267079](https://linux-hardware.org/?probe=3fce267079) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [5b48876c88](https://linux-hardware.org/?probe=5b48876c88) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [420e531d0c](https://linux-hardware.org/?probe=420e531d0c) | Aug 11, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [fd8d68081e](https://linux-hardware.org/?probe=fd8d68081e) | Aug 08, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [30d102a39e](https://linux-hardware.org/?probe=30d102a39e) | Aug 07, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | Notebook    | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | Notebook    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | Notebook    | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | Notebook    | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| ASRock        | B250M Pro4                  | Desktop     | [3ad9bafdc1](https://linux-hardware.org/?probe=3ad9bafdc1) | Jul 19, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [43684f5ded](https://linux-hardware.org/?probe=43684f5ded) | Jul 15, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [caa5d2a038](https://linux-hardware.org/?probe=caa5d2a038) | Jul 13, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [751ba49889](https://linux-hardware.org/?probe=751ba49889) | Jul 09, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [3149f0037a](https://linux-hardware.org/?probe=3149f0037a) | Jul 03, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9bd5a64d0d](https://linux-hardware.org/?probe=9bd5a64d0d) | Jun 25, 2020 |
| HP            | Presario CQ56               | Notebook    | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | Notebook    | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | Boston                      | Desktop     | [48a3bf1932](https://linux-hardware.org/?probe=48a3bf1932) | Jun 02, 2020 |
| Samsung       | 535U3C                      | Notebook    | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [869444acf6](https://linux-hardware.org/?probe=869444acf6) | May 26, 2020 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [d4e3d725fa](https://linux-hardware.org/?probe=d4e3d725fa) | May 19, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [369ce228c3](https://linux-hardware.org/?probe=369ce228c3) | May 16, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | Notebook    | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| MSI           | B360-A PRO                  | Desktop     | [c42cb75770](https://linux-hardware.org/?probe=c42cb75770) | Apr 24, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | Notebook    | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [61c4420d0e](https://linux-hardware.org/?probe=61c4420d0e) | Mar 22, 2020 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [76af4a7e0b](https://linux-hardware.org/?probe=76af4a7e0b) | Mar 21, 2020 |
| ASRock        | P45DE3                      | Desktop     | [fffef664cd](https://linux-hardware.org/?probe=fffef664cd) | Mar 18, 2020 |
| MSI           | B75A-G43                    | Desktop     | [9683ec9bd4](https://linux-hardware.org/?probe=9683ec9bd4) | Mar 16, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [95eb08349e](https://linux-hardware.org/?probe=95eb08349e) | Mar 15, 2020 |
| Samsung       | 275E4E/275E5E               | Notebook    | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | Notebook    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e30b449cc4](https://linux-hardware.org/?probe=e30b449cc4) | Mar 08, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [8bc7b7979a](https://linux-hardware.org/?probe=8bc7b7979a) | Mar 01, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [63e19ed1f4](https://linux-hardware.org/?probe=63e19ed1f4) | Feb 28, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [adc15c7147](https://linux-hardware.org/?probe=adc15c7147) | Feb 24, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b17f2abd3e](https://linux-hardware.org/?probe=b17f2abd3e) | Feb 20, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Gigabyte      | H81M-S1                     | Desktop     | [754bdf88c1](https://linux-hardware.org/?probe=754bdf88c1) | Jan 26, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [1eb5f177d1](https://linux-hardware.org/?probe=1eb5f177d1) | Jan 13, 2020 |
| Dell          | 0D28YY A01                  | Desktop     | [be51211fe3](https://linux-hardware.org/?probe=be51211fe3) | Dec 09, 2019 |
| Dell          | Latitude 5289               | Convertible | [dfdc8c484f](https://linux-hardware.org/?probe=dfdc8c484f) | Dec 04, 2019 |
| Gigabyte      | H81M-S1                     | Desktop     | [57524ab581](https://linux-hardware.org/?probe=57524ab581) | Dec 03, 2019 |
| Dell          | Precision 5510              | Notebook    | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| ASUSTek       | VM60                        | Desktop     | [4842363a0b](https://linux-hardware.org/?probe=4842363a0b) | Nov 14, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [8beb57338d](https://linux-hardware.org/?probe=8beb57338d) | Oct 02, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [abc398724a](https://linux-hardware.org/?probe=abc398724a) | Sep 16, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [f6acac9fc8](https://linux-hardware.org/?probe=f6acac9fc8) | Sep 15, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [d2b5c32d2f](https://linux-hardware.org/?probe=d2b5c32d2f) | Sep 15, 2019 |
| Dell          | Inspiron 5748               | Notebook    | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | Notebook    | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | Notebook    | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | Notebook    | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| HP            | 1495                        | Desktop     | [3d9e77ae8a](https://linux-hardware.org/?probe=3d9e77ae8a) | Jul 23, 2019 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [46e1a9fc55](https://linux-hardware.org/?probe=46e1a9fc55) | Jul 04, 2019 |
| Dell          | Inspiron 5558               | Notebook    | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | Notebook    | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [3a8d19c8fc](https://linux-hardware.org/?probe=3a8d19c8fc) | Jun 22, 2019 |
| Gigabyte      | 970-GAMING                  | Desktop     | [aa1385d100](https://linux-hardware.org/?probe=aa1385d100) | Jun 03, 2019 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | Notebook    | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [7f57ad053d](https://linux-hardware.org/?probe=7f57ad053d) | May 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Dell          | Latitude 5289               | Convertible | [e28d069f05](https://linux-hardware.org/?probe=e28d069f05) | May 07, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | Notebook    | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Dell          | 0KP561                      | Desktop     | [bba0fe2672](https://linux-hardware.org/?probe=bba0fe2672) | Apr 05, 2019 |
| Dell          | 0KP561                      | Desktop     | [f3085d1ae9](https://linux-hardware.org/?probe=f3085d1ae9) | Apr 04, 2019 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ba39531b87](https://linux-hardware.org/?probe=ba39531b87) | Mar 31, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | Notebook    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | 18E7                        | Desktop     | [19df4fb560](https://linux-hardware.org/?probe=19df4fb560) | Feb 22, 2019 |
| HP            | ProBook 470 G1              | Notebook    | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| ABIT          | KN9 Series                  | Desktop     | [10015b723b](https://linux-hardware.org/?probe=10015b723b) | Feb 04, 2019 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [f1a9b27e5c](https://linux-hardware.org/?probe=f1a9b27e5c) | Feb 04, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [b702949950](https://linux-hardware.org/?probe=b702949950) | Dec 19, 2018 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [158fb83dcc](https://linux-hardware.org/?probe=158fb83dcc) | Nov 13, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [a00ad66604](https://linux-hardware.org/?probe=a00ad66604) | Oct 24, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [9c47ffacd5](https://linux-hardware.org/?probe=9c47ffacd5) | Oct 24, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | Notebook    | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | Notebook    | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| ECS           | H55H-3.8L                   | Desktop     | [7e782321c8](https://linux-hardware.org/?probe=7e782321c8) | Mar 31, 2018 |
| Dell          | Inspiron N5110              | Notebook    | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [78791d4918](https://linux-hardware.org/?probe=78791d4918) | Sep 13, 2017 |
| Acer          | Aspire 6530G                | Notebook    | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| ASUSTek       | P8H67                       | Desktop     | [e36d00c6f9](https://linux-hardware.org/?probe=e36d00c6f9) | Jul 21, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | Notebook    | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | Notebook    | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| ECS           | nVidia-nForce               | Desktop     | [db8fd734f9](https://linux-hardware.org/?probe=db8fd734f9) | May 16, 2017 |
| HP            | Pavilion dv5                | Notebook    | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | Notebook    | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | Notebook    | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | Notebook    | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | Notebook    | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | Notebook    | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 31        | 8.29%   |
| Ubuntu 22.04      | 28        | 7.49%   |
| Ubuntu 18.04      | 22        | 5.88%   |
| Arch Rolling      | 18        | 4.81%   |
| ROSA R11          | 10        | 2.67%   |
| Arch              | 10        | 2.67%   |
| OpenMandriva 4.3  | 9         | 2.41%   |
| ArcoLinux Rolling | 9         | 2.41%   |
| Fedora 34         | 8         | 2.14%   |
| Ubuntu 19.04      | 7         | 1.87%   |
| ROSA R8.1         | 7         | 1.87%   |
| Kubuntu 20.04     | 7         | 1.87%   |
| Debian 12         | 7         | 1.87%   |
| Manjaro           | 6         | 1.6%    |
| Linux Mint 20.1   | 6         | 1.6%    |
| ROSA 12.2         | 5         | 1.34%   |
| OpenMandriva 4.2  | 5         | 1.34%   |
| Fedora 36         | 5         | 1.34%   |
| Fedora 35         | 5         | 1.34%   |
| Debian 11         | 5         | 1.34%   |
| Ubuntu MATE 22.04 | 4         | 1.07%   |
| ROSA R9           | 4         | 1.07%   |
| Pop!_OS 22.04     | 4         | 1.07%   |
| Kubuntu 22.04     | 4         | 1.07%   |
| KDE neon 20.04    | 4         | 1.07%   |
| Zorin 16          | 3         | 0.8%    |
| Ubuntu 21.10      | 3         | 0.8%    |
| Ubuntu 19.10      | 3         | 0.8%    |
| ROSA R10          | 3         | 0.8%    |
| Pop!_OS 20.04     | 3         | 0.8%    |
| Nobara 37         | 3         | 0.8%    |
| Linux Mint 21.2   | 3         | 0.8%    |
| Linux Mint 20.3   | 3         | 0.8%    |
| Gentoo 2.6        | 3         | 0.8%    |
| Fedora 39         | 3         | 0.8%    |
| Fedora 31         | 3         | 0.8%    |
| Debian Testing    | 3         | 0.8%    |
| Xubuntu 20.04     | 2         | 0.53%   |
| Xubuntu 18.04     | 2         | 0.53%   |
| Ubuntu MATE 20.04 | 2         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 101       | 27.67%  |
| ROSA         | 35        | 9.59%   |
| Arch         | 28        | 7.67%   |
| Fedora       | 27        | 7.4%    |
| Linux Mint   | 21        | 5.75%   |
| OpenMandriva | 19        | 5.21%   |
| Debian       | 18        | 4.93%   |
| Manjaro      | 16        | 4.38%   |
| Pop!_OS      | 11        | 3.01%   |
| Kubuntu      | 11        | 3.01%   |
| ArcoLinux    | 9         | 2.47%   |
| Xubuntu      | 6         | 1.64%   |
| Ubuntu MATE  | 6         | 1.64%   |
| KDE neon     | 6         | 1.64%   |
| Zorin        | 5         | 1.37%   |
| Nobara       | 4         | 1.1%    |
| Gentoo       | 4         | 1.1%    |
| Endless      | 4         | 1.1%    |
| Elementary   | 4         | 1.1%    |
| SteamOS      | 3         | 0.82%   |
| Reborn OS    | 3         | 0.82%   |
| openSUSE     | 3         | 0.82%   |
| Kali         | 3         | 0.82%   |
| Clear Linux  | 3         | 0.82%   |
| MX           | 2         | 0.55%   |
| LMDE         | 2         | 0.55%   |
| EndeavourOS  | 2         | 0.55%   |
| ChimeraOS    | 2         | 0.55%   |
| Xero         | 1         | 0.27%   |
| Ubuntu Unity | 1         | 0.27%   |
| TUXEDO OS    | 1         | 0.27%   |
| Parrot       | 1         | 0.27%   |
| NixOS        | 1         | 0.27%   |
| Lubuntu      | 1         | 0.27%   |
| ALT Linux    | 1         | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003             | 9         | 2.23%   |
| 5.4.0-42-generic                    | 8         | 1.99%   |
| 6.1.0-13-amd64                      | 5         | 1.24%   |
| 5.15.0-52-generic                   | 5         | 1.24%   |
| 5.10.14-desktop-1omv4002            | 5         | 1.24%   |
| 6.2.0-26-generic                    | 4         | 0.99%   |
| 5.15.0-53-generic                   | 4         | 0.99%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4         | 0.99%   |
| 5.4.0-65-generic                    | 3         | 0.74%   |
| 5.4.0-47-generic                    | 3         | 0.74%   |
| 5.4.0-28-generic                    | 3         | 0.74%   |
| 5.15.0-56-generic                   | 3         | 0.74%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 3         | 0.74%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3         | 0.74%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 3         | 0.74%   |
| 6.5.0-14-generic                    | 2         | 0.5%    |
| 6.2.6-desktop-1omv2390              | 2         | 0.5%    |
| 6.2.0-39-generic                    | 2         | 0.5%    |
| 6.1.1-desktop-1omv2290              | 2         | 0.5%    |
| 6.1.0-kali7-amd64                   | 2         | 0.5%    |
| 5.8.0-63-generic                    | 2         | 0.5%    |
| 5.8.0-53-generic                    | 2         | 0.5%    |
| 5.5.2-1-MANJARO                     | 2         | 0.5%    |
| 5.4.0-88-generic                    | 2         | 0.5%    |
| 5.4.0-58-generic                    | 2         | 0.5%    |
| 5.4.0-53-generic                    | 2         | 0.5%    |
| 5.4.0-45-generic                    | 2         | 0.5%    |
| 5.4.0-33-generic                    | 2         | 0.5%    |
| 5.4.0-29-generic                    | 2         | 0.5%    |
| 5.4.0-26-generic                    | 2         | 0.5%    |
| 5.3.0-40-generic                    | 2         | 0.5%    |
| 5.15.5-76051505-generic             | 2         | 0.5%    |
| 5.15.2-arch1-1                      | 2         | 0.5%    |
| 5.15.0-46-generic                   | 2         | 0.5%    |
| 5.15.0-41-generic                   | 2         | 0.5%    |
| 5.13.12-200.fc34.x86_64             | 2         | 0.5%    |
| 5.13.10-arch1-1                     | 2         | 0.5%    |
| 5.13.0-39-generic                   | 2         | 0.5%    |
| 5.11.0-37-generic                   | 2         | 0.5%    |
| 5.11.0-34-generic                   | 2         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 48        | 12.28%  |
| 5.15.0   | 29        | 7.42%   |
| 4.15.0   | 27        | 6.91%   |
| 5.11.0   | 15        | 3.84%   |
| 5.13.0   | 12        | 3.07%   |
| 6.5.0    | 11        | 2.81%   |
| 5.8.0    | 11        | 2.81%   |
| 5.0.0    | 10        | 2.56%   |
| 6.2.0    | 9         | 2.3%    |
| 6.1.0    | 9         | 2.3%    |
| 5.16.7   | 9         | 2.3%    |
| 5.10.0   | 7         | 1.79%   |
| 5.3.0    | 6         | 1.53%   |
| 4.18.0   | 6         | 1.53%   |
| 6.2.6    | 5         | 1.28%   |
| 5.19.0   | 5         | 1.28%   |
| 5.10.14  | 5         | 1.28%   |
| 4.9.20   | 5         | 1.28%   |
| 5.15.2   | 3         | 0.77%   |
| 5.13.12  | 3         | 0.77%   |
| 5.10.74  | 3         | 0.77%   |
| 5.10.118 | 3         | 0.77%   |
| 4.9.9    | 3         | 0.77%   |
| 6.6.10   | 2         | 0.51%   |
| 6.5.6    | 2         | 0.51%   |
| 6.1.1    | 2         | 0.51%   |
| 6.0.9    | 2         | 0.51%   |
| 6.0.11   | 2         | 0.51%   |
| 5.8.10   | 2         | 0.51%   |
| 5.5.2    | 2         | 0.51%   |
| 5.17.1   | 2         | 0.51%   |
| 5.15.5   | 2         | 0.51%   |
| 5.13.19  | 2         | 0.51%   |
| 5.13.13  | 2         | 0.51%   |
| 5.13.10  | 2         | 0.51%   |
| 5.11.12  | 2         | 0.51%   |
| 5.11.11  | 2         | 0.51%   |
| 4.9.60   | 2         | 0.51%   |
| 4.19.0   | 2         | 0.51%   |
| 6.8.8    | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 54        | 13.85%  |
| 5.15    | 37        | 9.49%   |
| 4.15    | 27        | 6.92%   |
| 6.1     | 25        | 6.41%   |
| 5.13    | 25        | 6.41%   |
| 5.10    | 25        | 6.41%   |
| 5.11    | 20        | 5.13%   |
| 6.2     | 15        | 3.85%   |
| 6.5     | 14        | 3.59%   |
| 5.8     | 14        | 3.59%   |
| 5.16    | 14        | 3.59%   |
| 4.9     | 14        | 3.59%   |
| 5.0     | 11        | 2.82%   |
| 6.6     | 9         | 2.31%   |
| 6.0     | 9         | 2.31%   |
| 5.3     | 8         | 2.05%   |
| 5.14    | 8         | 2.05%   |
| 5.19    | 7         | 1.79%   |
| 5.17    | 6         | 1.54%   |
| 4.18    | 6         | 1.54%   |
| 6.7     | 5         | 1.28%   |
| 5.9     | 4         | 1.03%   |
| 5.5     | 4         | 1.03%   |
| 5.12    | 4         | 1.03%   |
| 4.19    | 4         | 1.03%   |
| 6.8     | 3         | 0.77%   |
| 6.4     | 3         | 0.77%   |
| 5.6     | 3         | 0.77%   |
| 5.18    | 3         | 0.77%   |
| 6.3     | 2         | 0.51%   |
| 4.1     | 2         | 0.51%   |
| 5.7     | 1         | 0.26%   |
| 5.1     | 1         | 0.26%   |
| 4.4     | 1         | 0.26%   |
| 4.10    | 1         | 0.26%   |
| 3.16    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 344       | 96.36%  |
| i686   | 12        | 3.36%   |
| armv7l | 1         | 0.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 135       | 36.68%  |
| KDE5       | 72        | 19.57%  |
| Unknown    | 45        | 12.23%  |
| XFCE       | 24        | 6.52%   |
| X-Cinnamon | 20        | 5.43%   |
| KDE4       | 20        | 5.43%   |
| MATE       | 15        | 4.08%   |
| LXQt       | 5         | 1.36%   |
| KDE        | 5         | 1.36%   |
| i3         | 5         | 1.36%   |
| Pantheon   | 4         | 1.09%   |
| KDE6       | 4         | 1.09%   |
| Budgie     | 3         | 0.82%   |
| Unity      | 2         | 0.54%   |
| sway       | 2         | 0.54%   |
| LXDE       | 2         | 0.54%   |
| awesome    | 2         | 0.54%   |
| Yoyo       | 1         | 0.27%   |
| openbox    | 1         | 0.27%   |
| Cinnamon   | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 265       | 73.2%   |
| Wayland | 76        | 20.99%  |
| Unknown | 16        | 4.42%   |
| Tty     | 4         | 1.1%    |
| Web     | 1         | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 153       | 42.03%  |
| SDDM    | 69        | 18.96%  |
| GDM     | 41        | 11.26%  |
| GDM3    | 40        | 10.99%  |
| LightDM | 29        | 7.97%   |
| KDM     | 20        | 5.49%   |
| TDM     | 12        | 3.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 176       | 48.35%  |
| Unknown         | 60        | 16.48%  |
| et_EE           | 55        | 15.11%  |
| ru_RU           | 36        | 9.89%   |
| en_GB           | 15        | 4.12%   |
| de_DE           | 4         | 1.1%    |
| C               | 3         | 0.82%   |
| pl_PL           | 2         | 0.55%   |
| fr_FR           | 2         | 0.55%   |
| en_IE           | 2         | 0.55%   |
| en_DK           | 2         | 0.55%   |
| uk_UA           | 1         | 0.27%   |
| ru_UA           | 1         | 0.27%   |
| es_MX           | 1         | 0.27%   |
| en_US.utf-8     | 1         | 0.27%   |
| en_US.iso885915 | 1         | 0.27%   |
| en_DE           | 1         | 0.27%   |
| en_BW           | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 188       | 51.37%  |
| EFI  | 178       | 48.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 249       | 68.98%  |
| Btrfs   | 54        | 14.96%  |
| Overlay | 21        | 5.82%   |
| Unknown | 19        | 5.26%   |
| Tmpfs   | 8         | 2.22%   |
| Xfs     | 4         | 1.11%   |
| Zfs     | 3         | 0.83%   |
| Ext3    | 3         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 159       | 43.92%  |
| Unknown | 155       | 42.82%  |
| MBR     | 48        | 13.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 304       | 83.98%  |
| Yes       | 58        | 16.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 247       | 68.04%  |
| Yes       | 116       | 31.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 78        | 21.85%  |
| ASUSTek Computer    | 55        | 15.41%  |
| Hewlett-Packard     | 47        | 13.17%  |
| Dell                | 37        | 10.36%  |
| MSI                 | 33        | 9.24%   |
| Gigabyte Technology | 27        | 7.56%   |
| ASRock              | 11        | 3.08%   |
| Intel               | 9         | 2.52%   |
| Samsung Electronics | 8         | 2.24%   |
| Acer                | 8         | 2.24%   |
| Apple               | 6         | 1.68%   |
| Fujitsu             | 4         | 1.12%   |
| ECS                 | 4         | 1.12%   |
| Valve               | 3         | 0.84%   |
| TUXEDO              | 2         | 0.56%   |
| Timi                | 2         | 0.56%   |
| Quanta              | 2         | 0.56%   |
| Notebook            | 2         | 0.56%   |
| Alienware           | 2         | 0.56%   |
| ZOTAC               | 1         | 0.28%   |
| Toshiba             | 1         | 0.28%   |
| Supermicro          | 1         | 0.28%   |
| Prestigio           | 1         | 0.28%   |
| Packard Bell        | 1         | 0.28%   |
| OEM                 | 1         | 0.28%   |
| mPTech              | 1         | 0.28%   |
| Microsoft           | 1         | 0.28%   |
| HUAWEI              | 1         | 0.28%   |
| Huanan              | 1         | 0.28%   |
| GPD                 | 1         | 0.28%   |
| Getac               | 1         | 0.28%   |
| Fujitsu Siemens     | 1         | 0.28%   |
| Framework           | 1         | 0.28%   |
| Chuwi               | 1         | 0.28%   |
| ABIT                | 1         | 0.28%   |
| Unknown             | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 1.12%   |
| Valve Jupiter                              | 3         | 0.84%   |
| Quanta TWH                                 | 2         | 0.56%   |
| MSI MS-7C91                                | 2         | 0.56%   |
| MSI MS-7C37                                | 2         | 0.56%   |
| MSI MS-7C02                                | 2         | 0.56%   |
| MSI MS-7758                                | 2         | 0.56%   |
| Lenovo Y50-70 20378                        | 2         | 0.56%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2          | 2         | 0.56%   |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 2         | 0.56%   |
| HP Pavilion dv7                            | 2         | 0.56%   |
| HP ENVY Laptop 13-ah0xxx                   | 2         | 0.56%   |
| HP EliteBook 8470p                         | 2         | 0.56%   |
| HP EliteBook 8460p                         | 2         | 0.56%   |
| HP EliteBook 840 G5                        | 2         | 0.56%   |
| HP EliteBook 840 G2                        | 2         | 0.56%   |
| HP Compaq 8100 Elite SFF PC                | 2         | 0.56%   |
| Gigabyte X570 AORUS PRO                    | 2         | 0.56%   |
| Gigabyte Q87M-D2H                          | 2         | 0.56%   |
| Dell Latitude 7490                         | 2         | 0.56%   |
| Dell Inspiron N5110                        | 2         | 0.56%   |
| Dell Inspiron 5558                         | 2         | 0.56%   |
| ASUS ZenBook UX325EA_UX325EA               | 2         | 0.56%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.56%   |
| ASUS PRIME B550M-K                         | 2         | 0.56%   |
| Alienware 17                               | 2         | 0.56%   |
| Unknown                                    | 2         | 0.56%   |
| ZOTAC B410                                 | 1         | 0.28%   |
| TUXEDO Polaris AMD Gen5                    | 1         | 0.28%   |
| TUXEDO Book BA1510                         | 1         | 0.28%   |
| Toshiba Satellite L855                     | 1         | 0.28%   |
| Timi RedmiBook 16                          | 1         | 0.28%   |
| Timi RedmiBook 14 II                       | 1         | 0.28%   |
| Supermicro X10SLH-F/X10SLM+-F              | 1         | 0.28%   |
| Samsung R410                               | 1         | 0.28%   |
| Samsung 900X3C/900X3D/900X4C/900X4D        | 1         | 0.28%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D | 1         | 0.28%   |
| Samsung 770Z5E/780Z5E                      | 1         | 0.28%   |
| Samsung 535U3C                             | 1         | 0.28%   |
| Samsung 350V5C/351V5C/3540VC/3440VC        | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 50        | 14.01%  |
| HP EliteBook       | 14        | 3.92%   |
| Dell Latitude      | 10        | 2.8%    |
| Dell Inspiron      | 9         | 2.52%   |
| HP Pavilion        | 8         | 2.24%   |
| ASUS PRIME         | 8         | 2.24%   |
| Lenovo IdeaPad     | 6         | 1.68%   |
| HP Compaq          | 6         | 1.68%   |
| Dell Precision     | 5         | 1.4%    |
| Dell OptiPlex      | 5         | 1.4%    |
| ASUS ROG           | 5         | 1.4%    |
| HP ProBook         | 4         | 1.12%   |
| Gigabyte X570      | 4         | 1.12%   |
| Dell XPS           | 4         | 1.12%   |
| ASUS ZenBook       | 4         | 1.12%   |
| ASUS VivoBook      | 4         | 1.12%   |
| ASUS TUF           | 4         | 1.12%   |
| ASUS All           | 4         | 1.12%   |
| Acer Aspire        | 4         | 1.12%   |
| Valve Jupiter      | 3         | 0.84%   |
| Lenovo ThinkCentre | 3         | 0.84%   |
| Lenovo Legion      | 3         | 0.84%   |
| Lenovo IdeaPadFlex | 3         | 0.84%   |
| HP ENVY            | 3         | 0.84%   |
| Fujitsu LIFEBOOK   | 3         | 0.84%   |
| Timi RedmiBook     | 2         | 0.56%   |
| Samsung 900X3C     | 2         | 0.56%   |
| Quanta TWH         | 2         | 0.56%   |
| MSI MS-7C91        | 2         | 0.56%   |
| MSI MS-7C37        | 2         | 0.56%   |
| MSI MS-7C02        | 2         | 0.56%   |
| MSI MS-7758        | 2         | 0.56%   |
| Lenovo Yoga        | 2         | 0.56%   |
| Lenovo Y50-70      | 2         | 0.56%   |
| HP ProDesk         | 2         | 0.56%   |
| HP Presario        | 2         | 0.56%   |
| HP OMEN            | 2         | 0.56%   |
| Gigabyte Q87M-D2H  | 2         | 0.56%   |
| Dell Vostro        | 2         | 0.56%   |
| Apple MacBookPro5  | 2         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 42        | 11.76%  |
| 2018    | 36        | 10.08%  |
| 2013    | 34        | 9.52%   |
| 2019    | 33        | 9.24%   |
| 2012    | 25        | 7%      |
| 2011    | 23        | 6.44%   |
| 2014    | 22        | 6.16%   |
| 2015    | 20        | 5.6%    |
| 2017    | 19        | 5.32%   |
| 2021    | 16        | 4.48%   |
| 2016    | 15        | 4.2%    |
| 2010    | 15        | 4.2%    |
| 2022    | 14        | 3.92%   |
| 2009    | 11        | 3.08%   |
| 2008    | 10        | 2.8%    |
| 2007    | 9         | 2.52%   |
| 2023    | 5         | 1.4%    |
| 2006    | 4         | 1.12%   |
| 2005    | 2         | 0.56%   |
| 2004    | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 209       | 58.54%  |
| Desktop     | 130       | 36.41%  |
| Convertible | 12        | 3.36%   |
| Mini pc     | 3         | 0.84%   |
| Tablet      | 1         | 0.28%   |
| All in one  | 1         | 0.28%   |
| Server      | 1         | 0.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 339       | 94.17%  |
| Enabled  | 21        | 5.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 357       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 78        | 21.61%  |
| 8.01-16.0   | 73        | 20.22%  |
| 4.01-8.0    | 69        | 19.11%  |
| 3.01-4.0    | 53        | 14.68%  |
| 32.01-64.0  | 43        | 11.91%  |
| 24.01-32.0  | 13        | 3.6%    |
| 2.01-3.0    | 10        | 2.77%   |
| 1.01-2.0    | 10        | 2.77%   |
| 64.01-256.0 | 9         | 2.49%   |
| 0.51-1.0    | 2         | 0.55%   |
| 0.01-0.5    | 1         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 105       | 27.49%  |
| 2.01-3.0   | 90        | 23.56%  |
| 4.01-8.0   | 79        | 20.68%  |
| 3.01-4.0   | 42        | 10.99%  |
| 0.51-1.0   | 30        | 7.85%   |
| 8.01-16.0  | 25        | 6.54%   |
| 16.01-24.0 | 4         | 1.05%   |
| 0.01-0.5   | 4         | 1.05%   |
| 24.01-32.0 | 3         | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 223       | 60.93%  |
| 2      | 82        | 22.4%   |
| 3      | 32        | 8.74%   |
| 4      | 12        | 3.28%   |
| 6      | 9         | 2.46%   |
| 5      | 5         | 1.37%   |
| 0      | 2         | 0.55%   |
| 7      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 226       | 62.78%  |
| Yes       | 134       | 37.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 317       | 88.3%   |
| No        | 42        | 11.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 75.35%  |
| No        | 88        | 24.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 60.83%  |
| No        | 141       | 39.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 357       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Tallinn           | 231       | 63.11%  |
| Tartu             | 40        | 10.93%  |
| Pärnu            | 12        | 3.28%   |
| Rapla             | 8         | 2.19%   |
| Rakvere           | 7         | 1.91%   |
| Narva             | 6         | 1.64%   |
| Haapsalu          | 6         | 1.64%   |
| Tabasalu          | 3         | 0.82%   |
| Maardu            | 3         | 0.82%   |
| Vinni             | 2         | 0.55%   |
| Viljandi          | 2         | 0.55%   |
| Valga             | 2         | 0.55%   |
| Tapa              | 2         | 0.55%   |
| Saku              | 2         | 0.55%   |
| Põlva            | 2         | 0.55%   |
| Paldiski          | 2         | 0.55%   |
| Otepaeae          | 2         | 0.55%   |
| Kose              | 2         | 0.55%   |
| Kohtla-Järve     | 2         | 0.55%   |
| Keila             | 2         | 0.55%   |
| Jõhvi            | 2         | 0.55%   |
| Võru             | 1         | 0.27%   |
| Viimsi            | 1         | 0.27%   |
| Vatla             | 1         | 0.27%   |
| Vaidasoo          | 1         | 0.27%   |
| Türi             | 1         | 0.27%   |
| Sindi             | 1         | 0.27%   |
| Sillamäe         | 1         | 0.27%   |
| Sauga             | 1         | 0.27%   |
| Rae Parish        | 1         | 0.27%   |
| Pohja-Sakala vald | 1         | 0.27%   |
| Palamuse          | 1         | 0.27%   |
| Paide             | 1         | 0.27%   |
| Muraste           | 1         | 0.27%   |
| Lohkva            | 1         | 0.27%   |
| Laagri            | 1         | 0.27%   |
| Kuressaare        | 1         | 0.27%   |
| Kiviõli          | 1         | 0.27%   |
| Kärdla           | 1         | 0.27%   |
| Kaeina            | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 118       | 158    | 22.22%  |
| Seagate                     | 67        | 86     | 12.62%  |
| WDC                         | 54        | 80     | 10.17%  |
| Kingston                    | 43        | 58     | 8.1%    |
| Toshiba                     | 35        | 36     | 6.59%   |
| Sandisk                     | 20        | 23     | 3.77%   |
| Crucial                     | 20        | 30     | 3.77%   |
| SK hynix                    | 16        | 20     | 3.01%   |
| Hitachi                     | 16        | 20     | 3.01%   |
| Unknown                     | 14        | 15     | 2.64%   |
| HGST                        | 14        | 18     | 2.64%   |
| Intel                       | 13        | 15     | 2.45%   |
| A-DATA Technology           | 9         | 15     | 1.69%   |
| Patriot                     | 8         | 9      | 1.51%   |
| Apacer                      | 6         | 7      | 1.13%   |
| Micron Technology           | 5         | 5      | 0.94%   |
| China                       | 5         | 5      | 0.94%   |
| KingSpec                    | 4         | 6      | 0.75%   |
| Gigabyte Technology         | 4         | 5      | 0.75%   |
| XPG                         | 3         | 3      | 0.56%   |
| Transcend                   | 3         | 6      | 0.56%   |
| SPCC                        | 3         | 4      | 0.56%   |
| Phison Electronics          | 3         | 3      | 0.56%   |
| Lenovo                      | 3         | 3      | 0.56%   |
| KIOXIA                      | 3         | 4      | 0.56%   |
| Kingston Technology Company | 3         | 3      | 0.56%   |
| Apple                       | 3         | 3      | 0.56%   |
| ADATA Technology            | 3         | 3      | 0.56%   |
| Team                        | 2         | 3      | 0.38%   |
| Silicon Motion              | 2         | 4      | 0.38%   |
| Maxtor                      | 2         | 2      | 0.38%   |
| LITEONIT                    | 2         | 2      | 0.38%   |
| Intenso                     | 2         | 2      | 0.38%   |
| Fujitsu                     | 2         | 2      | 0.38%   |
| Corsair                     | 2         | 2      | 0.38%   |
| Unknown                     | 2         | 2      | 0.38%   |
| ZADAK                       | 1         | 1      | 0.19%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.19%   |
| UMIS                        | 1         | 1      | 0.19%   |
| PNY                         | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 10        | 1.7%    |
| Kingston SA400S37240G 240GB SSD                                 | 8         | 1.36%   |
| Samsung SSD 850 EVO 250GB                                       | 7         | 1.19%   |
| Samsung SSD 860 EVO 250GB                                       | 6         | 1.02%   |
| Samsung SSD 850 EVO 500GB                                       | 6         | 1.02%   |
| Samsung NVMe SSD Drive 1TB                                      | 6         | 1.02%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 5         | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 5         | 0.85%   |
| Toshiba DT01ACA100 1TB                                          | 4         | 0.68%   |
| Seagate ST500LT012-9WS142 500GB                                 | 4         | 0.68%   |
| Samsung SSD 970 EVO Plus 500GB                                  | 4         | 0.68%   |
| Samsung NVMe SSD Drive 512GB                                    | 4         | 0.68%   |
| Samsung HD103SJ 1TB                                             | 4         | 0.68%   |
| Kingston SA400S37120G 120GB SSD                                 | 4         | 0.68%   |
| HGST HTS721010A9E630 1TB                                        | 4         | 0.68%   |
| HGST HTS541010A9E680 1TB                                        | 4         | 0.68%   |
| SK hynix NVMe SSD Drive 256GB                                   | 3         | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 3         | 0.51%   |
| Seagate ST500DM002-1BD142 500GB                                 | 3         | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB                                    | 3         | 0.51%   |
| Samsung SSD 960 PRO 512GB                                       | 3         | 0.51%   |
| Samsung SSD 870 QVO 1TB                                         | 3         | 0.51%   |
| Samsung SSD 860 EVO 500GB                                       | 3         | 0.51%   |
| Samsung MZ7TY128HDHP-000L1 128GB SSD                            | 3         | 0.51%   |
| Samsung HD080HJ 80GB                                            | 3         | 0.51%   |
| Kingston SV300S37A120G 120GB SSD                                | 3         | 0.51%   |
| Kingston SUV400S37240G 240GB SSD                                | 3         | 0.51%   |
| Kingston SA400S37960G 960GB SSD                                 | 3         | 0.51%   |
| Crucial CT500MX500SSD1 500GB                                    | 3         | 0.51%   |
| Apacer AS350 512GB SSD                                          | 3         | 0.51%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3         | 0.51%   |
| A-DATA SX8200PNP 512GB                                          | 3         | 0.51%   |
| WDC WD10EZRZ-00HTKB0 1TB                                        | 2         | 0.34%   |
| WDC WD10EADS-00M2B0 1TB                                         | 2         | 0.34%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                            | 2         | 0.34%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB                            | 2         | 0.34%   |
| Unknown MMC Card  512GB                                         | 2         | 0.34%   |
| Unknown MMC Card  16GB                                          | 2         | 0.34%   |
| Unknown ArtisanTribute-512GB                                    | 2         | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                                    | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 83     | 35.96%  |
| WDC                 | 41        | 59     | 23.03%  |
| Toshiba             | 21        | 21     | 11.8%   |
| Samsung Electronics | 16        | 20     | 8.99%   |
| Hitachi             | 16        | 20     | 8.99%   |
| HGST                | 14        | 18     | 7.87%   |
| Maxtor              | 2         | 2      | 1.12%   |
| Fujitsu             | 2         | 2      | 1.12%   |
| Unknown             | 1         | 1      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 62        | 76     | 30.39%  |
| Kingston            | 34        | 45     | 16.67%  |
| Crucial             | 19        | 29     | 9.31%   |
| SanDisk             | 11        | 13     | 5.39%   |
| WDC                 | 8         | 12     | 3.92%   |
| Patriot             | 7         | 8      | 3.43%   |
| A-DATA Technology   | 7         | 12     | 3.43%   |
| Apacer              | 6         | 7      | 2.94%   |
| China               | 5         | 5      | 2.45%   |
| SK hynix            | 4         | 4      | 1.96%   |
| Micron Technology   | 4         | 4      | 1.96%   |
| KingSpec            | 4         | 6      | 1.96%   |
| Intel               | 4         | 5      | 1.96%   |
| Transcend           | 3         | 6      | 1.47%   |
| Toshiba             | 3         | 4      | 1.47%   |
| Team                | 2         | 3      | 0.98%   |
| SPCC                | 2         | 3      | 0.98%   |
| LITEONIT            | 2         | 2      | 0.98%   |
| Intenso             | 2         | 2      | 0.98%   |
| Gigabyte Technology | 2         | 3      | 0.98%   |
| Corsair             | 2         | 2      | 0.98%   |
| Apple               | 2         | 2      | 0.98%   |
| XPG                 | 1         | 1      | 0.49%   |
| Plextor             | 1         | 1      | 0.49%   |
| Netac               | 1         | 1      | 0.49%   |
| Lexar               | 1         | 1      | 0.49%   |
| Integral            | 1         | 1      | 0.49%   |
| i-FlashDisk         | 1         | 1      | 0.49%   |
| External            | 1         | 1      | 0.49%   |
| ASMT                | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 168       | 262    | 36.29%  |
| HDD     | 146       | 227    | 31.53%  |
| NVMe    | 129       | 169    | 27.86%  |
| MMC     | 12        | 13     | 2.59%   |
| Unknown | 8         | 9      | 1.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 258       | 483    | 62.02%  |
| NVMe | 129       | 167    | 31.01%  |
| SAS  | 17        | 17     | 4.09%   |
| MMC  | 12        | 13     | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 206       | 320    | 61.49%  |
| 0.51-1.0   | 89        | 116    | 26.57%  |
| 1.01-2.0   | 21        | 27     | 6.27%   |
| 3.01-4.0   | 7         | 7      | 2.09%   |
| 2.01-3.0   | 6         | 13     | 1.79%   |
| 4.01-10.0  | 5         | 5      | 1.49%   |
| 10.01-20.0 | 1         | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 105       | 28.3%   |
| 251-500        | 73        | 19.68%  |
| 501-1000       | 47        | 12.67%  |
| 1-20           | 34        | 9.16%   |
| 1001-2000      | 28        | 7.55%   |
| More than 3000 | 26        | 7.01%   |
| 51-100         | 26        | 7.01%   |
| Unknown        | 14        | 3.77%   |
| 21-50          | 10        | 2.7%    |
| 2001-3000      | 8         | 2.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 144       | 37.7%   |
| 21-50          | 58        | 15.18%  |
| 101-250        | 54        | 14.14%  |
| 51-100         | 37        | 9.69%   |
| 251-500        | 27        | 7.07%   |
| 501-1000       | 21        | 5.5%    |
| Unknown        | 14        | 3.66%   |
| 1001-2000      | 13        | 3.4%    |
| More than 3000 | 11        | 2.88%   |
| 2001-3000      | 3         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                        | 2         | 3      | 4.17%   |
| WDC WD60EFRX-68MYMN1 6TB                            | 1         | 1      | 2.08%   |
| WDC WD5002AALX-00J37A0 500GB                        | 1         | 1      | 2.08%   |
| WDC WD5000BPVT-00HXZT1 500GB                        | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1         | 1      | 2.08%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 2.08%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 2      | 2.08%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 2.08%   |
| WDC WD10PURX-64E5EY0 1TB                            | 1         | 1      | 2.08%   |
| WDC WD10EAVS-00D7B1 1TB                             | 1         | 1      | 2.08%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 2      | 2.08%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 2      | 2.08%   |
| Toshiba MK6475GSX 640GB                             | 1         | 1      | 2.08%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 2.08%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 2.08%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.08%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.08%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.08%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.08%   |
| Seagate ST340016A 40GB                              | 1         | 2      | 2.08%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 2.08%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.08%   |
| Seagate ST3000DM008-2DM166 3TB                      | 1         | 1      | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.08%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 840 PRO Series 128GB        | 1         | 1      | 2.08%   |
| Samsung Electronics SP0802N 80GB                    | 1         | 1      | 2.08%   |
| Samsung Electronics HD642JJ 640GB                   | 1         | 1      | 2.08%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 2.08%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 2.08%   |
| Samsung Electronics HD080HJ 80GB                    | 1         | 1      | 2.08%   |
| Patriot P210 256GB SSD                              | 1         | 1      | 2.08%   |
| Patriot Burst 480GB SSD                             | 1         | 1      | 2.08%   |
| Netac SSD 720GB                                     | 1         | 1      | 2.08%   |
| Micron Technology MTFDDAK256TDL-1AW15ABHA 256GB SSD | 1         | 1      | 2.08%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.08%   |
| Maxtor STM3250310AS 250GB                           | 1         | 1      | 2.08%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1      | 2.08%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 26.09%  |
| WDC                 | 9         | 12     | 19.57%  |
| Samsung Electronics | 5         | 6      | 10.87%  |
| Crucial             | 4         | 5      | 8.7%    |
| Toshiba             | 3         | 4      | 6.52%   |
| Hitachi             | 3         | 3      | 6.52%   |
| Patriot             | 2         | 2      | 4.35%   |
| Micron Technology   | 2         | 2      | 4.35%   |
| Kingston            | 2         | 2      | 4.35%   |
| Netac               | 1         | 1      | 2.17%   |
| Maxtor              | 1         | 1      | 2.17%   |
| HGST                | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 36.36%  |
| WDC                 | 9         | 12     | 27.27%  |
| Samsung Electronics | 4         | 5      | 12.12%  |
| Hitachi             | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Maxtor              | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 38     | 72.09%  |
| SSD  | 12        | 15     | 27.91%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 184       | 355    | 47.18%  |
| Works    | 163       | 271    | 41.79%  |
| Malfunc  | 42        | 53     | 10.77%  |
| Failed   | 1         | 1      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 229       | 50%     |
| AMD                          | 68        | 14.85%  |
| Samsung Electronics          | 52        | 11.35%  |
| Sandisk                      | 17        | 3.71%   |
| SK hynix                     | 12        | 2.62%   |
| Kingston Technology Company  | 12        | 2.62%   |
| Toshiba America Info Systems | 9         | 1.97%   |
| Marvell Technology Group     | 8         | 1.75%   |
| Nvidia                       | 7         | 1.53%   |
| ADATA Technology             | 7         | 1.53%   |
| Phison Electronics           | 6         | 1.31%   |
| KIOXIA                       | 6         | 1.31%   |
| ASMedia Technology           | 5         | 1.09%   |
| VIA Technologies             | 3         | 0.66%   |
| Silicon Motion               | 3         | 0.66%   |
| Lenovo                       | 3         | 0.66%   |
| Micron/Crucial Technology    | 2         | 0.44%   |
| JMicron Technology           | 2         | 0.44%   |
| Union Memory (Shenzhen)      | 1         | 0.22%   |
| Silicon Image                | 1         | 0.22%   |
| Seagate Technology           | 1         | 0.22%   |
| Realtek Semiconductor        | 1         | 0.22%   |
| Micron Technology            | 1         | 0.22%   |
| Hosin Global Electronics     | 1         | 0.22%   |
| Adaptec                      | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 43        | 8.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 33        | 6.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 32        | 6.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 2.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 1.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 1.75%   |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 1.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 1.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 1.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.17%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 6         | 1.17%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 0.97%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 0.78%   |
| Intel SSD 660P Series                                                          | 4         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 270       | 58.95%  |
| NVMe | 131       | 28.6%   |
| IDE  | 40        | 8.73%   |
| RAID | 16        | 3.49%   |
| SCSI | 1         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 263       | 73.67%  |
| AMD                   | 93        | 26.05%  |
| Marvell Semiconductor | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 8         | 2.24%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 6         | 1.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 1.12%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 4         | 1.12%   |
| AMD Ryzen 5 3600 6-Core Processor       | 4         | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 0.84%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 0.84%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3         | 0.84%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz      | 3         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 0.84%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.84%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 0.84%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 3         | 0.84%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 3         | 0.84%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 3         | 0.84%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 3         | 0.84%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 3         | 0.84%   |
| AMD Custom APU 0405                     | 3         | 0.84%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz     | 2         | 0.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.56%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.56%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 2         | 0.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 0.56%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 0.56%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.56%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 2         | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 2         | 0.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.56%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 88        | 24.65%  |
| Intel Core i7                  | 72        | 20.17%  |
| AMD Ryzen 7                    | 26        | 7.28%   |
| Intel Core i3                  | 23        | 6.44%   |
| Other                          | 22        | 6.16%   |
| AMD Ryzen 5                    | 21        | 5.88%   |
| Intel Celeron                  | 15        | 4.2%    |
| Intel Core 2 Duo               | 14        | 3.92%   |
| AMD Ryzen 9                    | 8         | 2.24%   |
| Intel Pentium                  | 7         | 1.96%   |
| Intel Xeon                     | 6         | 1.68%   |
| AMD Ryzen 7 PRO                | 6         | 1.68%   |
| Intel Atom                     | 5         | 1.4%    |
| AMD Phenom II X4               | 4         | 1.12%   |
| AMD FX                         | 4         | 1.12%   |
| AMD Athlon 64 X2               | 4         | 1.12%   |
| Intel Core i9                  | 3         | 0.84%   |
| Intel Pentium M                | 2         | 0.56%   |
| Intel Celeron Dual-Core        | 2         | 0.56%   |
| AMD Ryzen 3 PRO                | 2         | 0.56%   |
| AMD Ryzen 3                    | 2         | 0.56%   |
| AMD A10                        | 2         | 0.56%   |
| Intel Pentium Silver           | 1         | 0.28%   |
| Intel Pentium Gold             | 1         | 0.28%   |
| Intel Pentium Dual-Core        | 1         | 0.28%   |
| Intel Pentium Dual             | 1         | 0.28%   |
| Intel Pentium D                | 1         | 0.28%   |
| Intel Pentium 4                | 1         | 0.28%   |
| Intel Core 2                   | 1         | 0.28%   |
| Intel Celeron M                | 1         | 0.28%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.28%   |
| AMD Ryzen 5 PRO                | 1         | 0.28%   |
| AMD Phenom II X6               | 1         | 0.28%   |
| AMD E2                         | 1         | 0.28%   |
| AMD E                          | 1         | 0.28%   |
| AMD C-60                       | 1         | 0.28%   |
| AMD Athlon XP                  | 1         | 0.28%   |
| AMD Athlon II Dual-Core        | 1         | 0.28%   |
| AMD A8                         | 1         | 0.28%   |
| AMD A6                         | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 134       | 37.54%  |
| 4       | 117       | 32.77%  |
| 6       | 40        | 11.2%   |
| 8       | 36        | 10.08%  |
| 1       | 12        | 3.36%   |
| 12      | 7         | 1.96%   |
| 16      | 3         | 0.84%   |
| 14      | 3         | 0.84%   |
| Unknown | 3         | 0.84%   |
| 10      | 1         | 0.28%   |
| 3       | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 356       | 99.72%  |
| 2      | 1         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 251       | 70.11%  |
| 1       | 104       | 29.05%  |
| Unknown | 3         | 0.84%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 351       | 98.04%  |
| Unknown        | 4         | 1.12%   |
| 32-bit         | 3         | 0.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 30.54%  |
| 0x306c3    | 24        | 6.49%   |
| 0x306a9    | 22        | 5.95%   |
| 0x206a7    | 19        | 5.14%   |
| 0x806ea    | 10        | 2.7%    |
| 0x906e9    | 9         | 2.43%   |
| 0x1067a    | 9         | 2.43%   |
| 0x08600106 | 9         | 2.43%   |
| 0x40651    | 8         | 2.16%   |
| 0x906ea    | 7         | 1.89%   |
| 0x20655    | 7         | 1.89%   |
| 0x08701021 | 7         | 1.89%   |
| 0x806ec    | 6         | 1.62%   |
| 0x806e9    | 6         | 1.62%   |
| 0x506e3    | 6         | 1.62%   |
| 0x306d4    | 6         | 1.62%   |
| 0x806c1    | 5         | 1.35%   |
| 0x6fb      | 5         | 1.35%   |
| 0x08701013 | 5         | 1.35%   |
| 0xa0652    | 4         | 1.08%   |
| 0x6fd      | 4         | 1.08%   |
| 0x08108102 | 4         | 1.08%   |
| 0xa0655    | 3         | 0.81%   |
| 0x90672    | 3         | 0.81%   |
| 0x406e3    | 3         | 0.81%   |
| 0x06000852 | 3         | 0.81%   |
| 0x05000119 | 3         | 0.81%   |
| 0xa0671    | 2         | 0.54%   |
| 0x906ed    | 2         | 0.54%   |
| 0x706a1    | 2         | 0.54%   |
| 0x6d8      | 2         | 0.54%   |
| 0x406c4    | 2         | 0.54%   |
| 0x30678    | 2         | 0.54%   |
| 0x106ca    | 2         | 0.54%   |
| 0x0a50000d | 2         | 0.54%   |
| 0x0a50000c | 2         | 0.54%   |
| 0x08600103 | 2         | 0.54%   |
| 0x0810100b | 2         | 0.54%   |
| 0x08001138 | 2         | 0.54%   |
| 0x06003106 | 2         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 16.81%  |
| Haswell          | 46        | 12.89%  |
| Zen 2            | 32        | 8.96%   |
| IvyBridge        | 27        | 7.56%   |
| SandyBridge      | 25        | 7%      |
| Unknown          | 16        | 4.48%   |
| Skylake          | 15        | 4.2%    |
| Westmere         | 13        | 3.64%   |
| Zen 3            | 12        | 3.36%   |
| Core             | 12        | 3.36%   |
| Penryn           | 10        | 2.8%    |
| Broadwell        | 10        | 2.8%    |
| Zen+             | 8         | 2.24%   |
| CometLake        | 8         | 2.24%   |
| TigerLake        | 7         | 1.96%   |
| K10              | 6         | 1.68%   |
| Alderlake Hybrid | 6         | 1.68%   |
| Zen              | 5         | 1.4%    |
| Silvermont       | 5         | 1.4%    |
| Piledriver       | 5         | 1.4%    |
| K8 Hammer        | 4         | 1.12%   |
| IceLake          | 4         | 1.12%   |
| Goldmont plus    | 4         | 1.12%   |
| Steamroller      | 3         | 0.84%   |
| Bonnell          | 3         | 0.84%   |
| Bobcat           | 3         | 0.84%   |
| P6               | 2         | 0.56%   |
| NetBurst         | 2         | 0.56%   |
| K8 & K10 hybrid  | 1         | 0.28%   |
| K6               | 1         | 0.28%   |
| Goldmont         | 1         | 0.28%   |
| Excavator        | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 209       | 46.24%  |
| Nvidia            | 149       | 32.96%  |
| AMD               | 92        | 20.35%  |
| VIA Technologies  | 1         | 0.22%   |
| ASPEED Technology | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 3.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 3.66%   |
| Intel UHD Graphics 620                                                                   | 15        | 3.23%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 15        | 3.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 3.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 2.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.16%   |
| Intel HD Graphics 620                                                                    | 8         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.51%   |
| Intel HD Graphics 630                                                                    | 7         | 1.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.51%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.29%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.08%   |
| Intel HD Graphics 530                                                                    | 5         | 1.08%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.65%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 3         | 0.65%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 3         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 0.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 129       | 35.93%  |
| 1 x Nvidia     | 68        | 18.94%  |
| 1 x AMD        | 68        | 18.94%  |
| Intel + Nvidia | 67        | 18.66%  |
| AMD + Nvidia   | 10        | 2.79%   |
| Intel + AMD    | 9         | 2.51%   |
| 2 x AMD        | 3         | 0.84%   |
| 2 x Nvidia     | 2         | 0.56%   |
| Other          | 1         | 0.28%   |
| 1 x VIA        | 1         | 0.28%   |
| AMD + ASPEED   | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 256       | 70.14%  |
| Proprietary | 95        | 26.03%  |
| Unknown     | 14        | 3.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 182       | 50%     |
| 1.01-2.0   | 53        | 14.56%  |
| 0.01-0.5   | 38        | 10.44%  |
| 3.01-4.0   | 29        | 7.97%   |
| 0.51-1.0   | 20        | 5.49%   |
| 7.01-8.0   | 19        | 5.22%   |
| 5.01-6.0   | 9         | 2.47%   |
| 8.01-16.0  | 9         | 2.47%   |
| 2.01-3.0   | 2         | 0.55%   |
| 16.01-24.0 | 2         | 0.55%   |
| 4.01-5.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 54        | 12.95%  |
| Dell                    | 50        | 11.99%  |
| AU Optronics            | 43        | 10.31%  |
| Chimei Innolux          | 42        | 10.07%  |
| LG Display              | 32        | 7.67%   |
| BOE                     | 28        | 6.71%   |
| Goldstar                | 26        | 6.24%   |
| Hewlett-Packard         | 15        | 3.6%    |
| AOC                     | 13        | 3.12%   |
| Chi Mei Optoelectronics | 11        | 2.64%   |
| Philips                 | 10        | 2.4%    |
| ViewSonic               | 9         | 2.16%   |
| Sharp                   | 9         | 2.16%   |
| Lenovo                  | 9         | 2.16%   |
| BenQ                    | 7         | 1.68%   |
| Apple                   | 6         | 1.44%   |
| PANDA                   | 5         | 1.2%    |
| Ancor Communications    | 4         | 0.96%   |
| Sony                    | 3         | 0.72%   |
| LG Philips              | 3         | 0.72%   |
| Hitachi                 | 3         | 0.72%   |
| ASUSTek Computer        | 3         | 0.72%   |
| Unknown                 | 2         | 0.48%   |
| RoverScan               | 2         | 0.48%   |
| Panasonic               | 2         | 0.48%   |
| Lenovo Group Limited    | 2         | 0.48%   |
| Fujitsu Siemens         | 2         | 0.48%   |
| CSO                     | 2         | 0.48%   |
| CPT                     | 2         | 0.48%   |
| Acer                    | 2         | 0.48%   |
| Vestel Elektronik       | 1         | 0.24%   |
| Valve                   | 1         | 0.24%   |
| Toshiba                 | 1         | 0.24%   |
| Tech Concepts           | 1         | 0.24%   |
| Sun                     | 1         | 0.24%   |
| Seiko/Epson             | 1         | 0.24%   |
| Plain Tree Systems      | 1         | 0.24%   |
| LG Electronics          | 1         | 0.24%   |
| KDB                     | 1         | 0.24%   |
| JDI                     | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 5         | 1.14%   |
| Goldstar LG ULTRAGEAR GSM5B80 2560x1440 600x340mm 27.2-inch               | 4         | 0.92%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 4         | 0.92%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.69%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch             | 2         | 0.46%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.46%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.46%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                   | 2         | 0.46%   |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch         | 2         | 0.46%   |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch         | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.46%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.46%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.46%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                   | 2         | 0.46%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch               | 2         | 0.46%   |
| Hewlett-Packard 27er HWP3325 1920x1080 600x340mm 27.2-inch                | 2         | 0.46%   |
| Goldstar ULTRAWIDE GSM7768 3440x1440 800x334mm 34.1-inch                  | 2         | 0.46%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                      | 2         | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.46%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                         | 2         | 0.46%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                        | 2         | 0.46%   |
| Dell P3421W DELA1A8 3440x1440 800x335mm 34.1-inch                         | 2         | 0.46%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                         | 2         | 0.46%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                         | 2         | 0.46%   |
| Dell 2407WFP DELA017 1920x1200 519x324mm 24.1-inch                        | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.46%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 166       | 42.03%  |
| 1366x768 (WXGA)    | 52        | 13.16%  |
| 3840x2160 (4K)     | 34        | 8.61%   |
| 1920x1200 (WUXGA)  | 26        | 6.58%   |
| 2560x1440 (QHD)    | 23        | 5.82%   |
| 1280x1024 (SXGA)   | 21        | 5.32%   |
| 1600x900 (HD+)     | 19        | 4.81%   |
| 1280x800 (WXGA)    | 11        | 2.78%   |
| 3440x1440          | 10        | 2.53%   |
| 2560x1600          | 8         | 2.03%   |
| 1680x1050 (WSXGA+) | 8         | 2.03%   |
| 1440x900 (WXGA+)   | 7         | 1.77%   |
| 800x1280           | 2         | 0.51%   |
| 1600x1200          | 2         | 0.51%   |
| 3840x2400          | 1         | 0.25%   |
| 2880x1800          | 1         | 0.25%   |
| 2560x1080          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 1920x540           | 1         | 0.25%   |
| 1360x768           | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 96        | 22.7%   |
| 24      | 44        | 10.4%   |
| 13      | 41        | 9.69%   |
| 14      | 38        | 8.98%   |
| 17      | 31        | 7.33%   |
| 27      | 27        | 6.38%   |
| 23      | 24        | 5.67%   |
| Unknown | 17        | 4.02%   |
| 21      | 16        | 3.78%   |
| 34      | 9         | 2.13%   |
| 19      | 9         | 2.13%   |
| 12      | 9         | 2.13%   |
| 31      | 7         | 1.65%   |
| 84      | 6         | 1.42%   |
| 20      | 6         | 1.42%   |
| 40      | 5         | 1.18%   |
| 16      | 5         | 1.18%   |
| 32      | 4         | 0.95%   |
| 18      | 4         | 0.95%   |
| 72      | 3         | 0.71%   |
| 25      | 3         | 0.71%   |
| 22      | 3         | 0.71%   |
| 54      | 2         | 0.47%   |
| 43      | 2         | 0.47%   |
| 33      | 2         | 0.47%   |
| 86      | 1         | 0.24%   |
| 65      | 1         | 0.24%   |
| 38      | 1         | 0.24%   |
| 29      | 1         | 0.24%   |
| 28      | 1         | 0.24%   |
| 11      | 1         | 0.24%   |
| 10      | 1         | 0.24%   |
| 9       | 1         | 0.24%   |
| 7       | 1         | 0.24%   |
| 3       | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 167       | 40.34%  |
| 501-600     | 86        | 20.77%  |
| 201-300     | 35        | 8.45%   |
| 401-500     | 31        | 7.49%   |
| 351-400     | 25        | 6.04%   |
| Unknown     | 17        | 4.11%   |
| 701-800     | 15        | 3.62%   |
| 601-700     | 15        | 3.62%   |
| 1501-2000   | 9         | 2.17%   |
| 801-900     | 6         | 1.45%   |
| 1001-1500   | 4         | 0.97%   |
| 901-1000    | 2         | 0.48%   |
| 1-100       | 2         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 259       | 68.7%   |
| 16/10   | 64        | 16.98%  |
| 5/4     | 18        | 4.77%   |
| Unknown | 15        | 3.98%   |
| 21/9    | 9         | 2.39%   |
| 6/5     | 3         | 0.8%    |
| 4/3     | 3         | 0.8%    |
| 3/2     | 3         | 0.8%    |
| 32/9    | 1         | 0.27%   |
| 0.67    | 1         | 0.27%   |
| 0.56    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 22.14%  |
| 81-90          | 58        | 13.81%  |
| 201-250        | 53        | 12.62%  |
| 251-300        | 31        | 7.38%   |
| 301-350        | 27        | 6.43%   |
| 351-500        | 24        | 5.71%   |
| 71-80          | 20        | 4.76%   |
| 151-200        | 19        | 4.52%   |
| 141-150        | 17        | 4.05%   |
| Unknown        | 17        | 4.05%   |
| 121-130        | 16        | 3.81%   |
| More than 1000 | 13        | 3.1%    |
| 61-70          | 9         | 2.14%   |
| 111-120        | 8         | 1.9%    |
| 501-1000       | 8         | 1.9%    |
| 41-50          | 2         | 0.48%   |
| 1-40           | 2         | 0.48%   |
| 51-60          | 1         | 0.24%   |
| 131-140        | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 135       | 33.09%  |
| 121-160       | 118       | 28.92%  |
| 101-120       | 89        | 21.81%  |
| 161-240       | 30        | 7.35%   |
| Unknown       | 17        | 4.17%   |
| More than 240 | 11        | 2.7%    |
| 1-50          | 8         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 267       | 73.15%  |
| 2     | 77        | 21.1%   |
| 3     | 10        | 2.74%   |
| 0     | 10        | 2.74%   |
| 4     | 1         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 182       | 34.02%  |
| Realtek Semiconductor             | 176       | 32.9%   |
| Qualcomm Atheros                  | 51        | 9.53%   |
| Broadcom                          | 23        | 4.3%    |
| MediaTek                          | 15        | 2.8%    |
| TP-Link                           | 11        | 2.06%   |
| Ralink                            | 8         | 1.5%    |
| Nvidia                            | 7         | 1.31%   |
| Broadcom Limited                  | 7         | 1.31%   |
| ASIX Electronics                  | 6         | 1.12%   |
| Ralink Technology                 | 5         | 0.93%   |
| Sierra Wireless                   | 4         | 0.75%   |
| Marvell Technology Group          | 4         | 0.75%   |
| Lenovo                            | 4         | 0.75%   |
| FIBOCOM                           | 4         | 0.75%   |
| Ericsson Business Mobile Networks | 4         | 0.75%   |
| Microsoft                         | 3         | 0.56%   |
| Hewlett-Packard                   | 3         | 0.56%   |
| Samsung Electronics               | 2         | 0.37%   |
| Qualcomm Atheros Communications   | 2         | 0.37%   |
| JMicron Technology                | 2         | 0.37%   |
| Huawei Technologies               | 2         | 0.37%   |
| D-Link System                     | 2         | 0.37%   |
| VIA Technologies                  | 1         | 0.19%   |
| Van Ooijen Technische Informatica | 1         | 0.19%   |
| OPPO Electronics                  | 1         | 0.19%   |
| DisplayLink                       | 1         | 0.19%   |
| D-Link                            | 1         | 0.19%   |
| ASUSTek Computer                  | 1         | 0.19%   |
| Aquantia                          | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 115       | 17.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 22        | 3.43%   |
| Intel Wireless 8265 / 8275                                             | 17        | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 13        | 2.03%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 2.03%   |
| Intel Wireless 7260                                                    | 11        | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 1.56%   |
| Intel Wireless 7265                                                    | 9         | 1.4%    |
| Intel Ethernet Connection I217-LM                                      | 9         | 1.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.09%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.94%   |
| Intel Wireless 8260                                                    | 6         | 0.94%   |
| Intel Wireless 3165                                                    | 6         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.78%   |
| Intel Wi-Fi 6 AX201                                                    | 5         | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 5         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.62%   |
| Intel Wireless 3160                                                    | 4         | 0.62%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.62%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.62%   |
| Intel 82566MM Gigabit Network Connection                               | 4         | 0.62%   |
| FIBOCOM L830-EB-00                                                     | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 135       | 47.2%   |
| Realtek Semiconductor           | 38        | 13.29%  |
| Qualcomm Atheros                | 37        | 12.94%  |
| Broadcom                        | 18        | 6.29%   |
| MediaTek                        | 14        | 4.9%    |
| TP-Link                         | 10        | 3.5%    |
| Ralink                          | 8         | 2.8%    |
| Ralink Technology               | 5         | 1.75%   |
| Sierra Wireless                 | 4         | 1.4%    |
| FIBOCOM                         | 4         | 1.4%    |
| Broadcom Limited                | 4         | 1.4%    |
| Microsoft                       | 3         | 1.05%   |
| Qualcomm Atheros Communications | 2         | 0.7%    |
| Marvell Technology Group        | 1         | 0.35%   |
| Hewlett-Packard                 | 1         | 0.35%   |
| D-Link System                   | 1         | 0.35%   |
| D-Link                          | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 17        | 5.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 13        | 4.51%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 4.51%   |
| Intel Wireless 7260                                            | 11        | 3.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 3.82%   |
| Intel Wireless 7265                                            | 9         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 2.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.08%   |
| Intel Wireless 8260                                            | 6         | 2.08%   |
| Intel Wireless 3165                                            | 6         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 1.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.74%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 1.39%   |
| Intel Wireless 3160                                            | 4         | 1.39%   |
| FIBOCOM L830-EB-00                                             | 4         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.04%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 1.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.04%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2         | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.69%   |
| TP-Link Archer T4U ver.3                                       | 2         | 0.69%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 2         | 0.69%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 2         | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 157       | 46.73%  |
| Intel                    | 114       | 33.93%  |
| Qualcomm Atheros         | 21        | 6.25%   |
| Broadcom                 | 8         | 2.38%   |
| Nvidia                   | 7         | 2.08%   |
| ASIX Electronics         | 6         | 1.79%   |
| Marvell Technology Group | 3         | 0.89%   |
| Lenovo                   | 3         | 0.89%   |
| Broadcom Limited         | 3         | 0.89%   |
| Samsung Electronics      | 2         | 0.6%    |
| JMicron Technology       | 2         | 0.6%    |
| VIA Technologies         | 1         | 0.3%    |
| TP-Link                  | 1         | 0.3%    |
| OPPO Electronics         | 1         | 0.3%    |
| MediaTek                 | 1         | 0.3%    |
| Hewlett-Packard          | 1         | 0.3%    |
| DisplayLink              | 1         | 0.3%    |
| D-Link System            | 1         | 0.3%    |
| ASUSTek Computer         | 1         | 0.3%    |
| Aquantia                 | 1         | 0.3%    |
| Apple                    | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 115       | 33.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 22        | 6.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 3.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 2.92%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 2.63%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 2.34%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 2.34%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 2.05%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 1.75%   |
| Intel Ethernet Controller I225-V                                       | 5         | 1.46%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.46%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 1.17%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.17%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 1.17%   |
| Intel 82566MM Gigabit Network Connection                               | 4         | 1.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.58%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.58%   |
| Nvidia CK804 Ethernet Controller                                       | 2         | 0.58%   |
| Lenovo ThinkPad TBT3 LAN                                               | 2         | 0.58%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 0.58%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 0.58%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.58%   |
| Intel 82578DM Gigabit Network Connection                               | 2         | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.29%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 316       | 53.02%  |
| WiFi     | 269       | 45.13%  |
| Modem    | 11        | 1.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 201       | 54.77%  |
| Ethernet | 166       | 45.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 199       | 55.74%  |
| 1     | 146       | 40.9%   |
| 0     | 6         | 1.68%   |
| 3     | 5         | 1.4%    |
| 6     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 303       | 83.24%  |
| Yes  | 61        | 16.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 46.61%  |
| Cambridge Silicon Radio         | 18        | 8.14%   |
| Realtek Semiconductor           | 17        | 7.69%   |
| Qualcomm Atheros Communications | 17        | 7.69%   |
| Broadcom                        | 14        | 6.33%   |
| IMC Networks                    | 12        | 5.43%   |
| Foxconn / Hon Hai               | 8         | 3.62%   |
| Apple                           | 6         | 2.71%   |
| TP-Link                         | 4         | 1.81%   |
| Realtek                         | 4         | 1.81%   |
| Hewlett-Packard                 | 4         | 1.81%   |
| ASUSTek Computer                | 3         | 1.36%   |
| MediaTek                        | 2         | 0.9%    |
| Edimax Technology               | 2         | 0.9%    |
| Dell                            | 2         | 0.9%    |
| Toshiba                         | 1         | 0.45%   |
| Ralink                          | 1         | 0.45%   |
| Lite-On Technology              | 1         | 0.45%   |
| Integrated System Solution      | 1         | 0.45%   |
| Askey Computer                  | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 30        | 13.57%  |
| Intel Bluetooth Device                              | 20        | 9.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 8.14%   |
| Intel AX201 Bluetooth                               | 15        | 6.79%   |
| Intel AX200 Bluetooth                               | 11        | 4.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 4.52%   |
| Realtek Bluetooth Radio                             | 8         | 3.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 3.17%   |
| IMC Networks Bluetooth Device                       | 5         | 2.26%   |
| TP-Link UB500 Adapter                               | 4         | 1.81%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 1.81%   |
| Realtek Bluetooth Radio                             | 4         | 1.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.81%   |
| Intel AX210 Bluetooth                               | 4         | 1.81%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.81%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 1.81%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 1.81%   |
| Apple Bluetooth Host Controller                     | 4         | 1.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.36%   |
| Intel AX211 Bluetooth                               | 3         | 1.36%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.36%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 1.36%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.9%    |
| MediaTek Wireless_Device                            | 2         | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.9%    |
| Edimax Edimax Bluetooth Adapter                     | 2         | 0.9%    |
| Broadcom HP Portable SoftSailing                    | 2         | 0.9%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.9%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.9%    |
| ASUS ASUS USB-BT500                                 | 2         | 0.9%    |
| Apple Bluetooth USB Host Controller                 | 2         | 0.9%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.45%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.45%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 255       | 49.32%  |
| AMD                     | 108       | 20.89%  |
| Nvidia                  | 98        | 18.96%  |
| C-Media Electronics     | 8         | 1.55%   |
| Kingston Technology     | 6         | 1.16%   |
| Logitech                | 5         | 0.97%   |
| Lenovo                  | 5         | 0.97%   |
| Razer USA               | 3         | 0.58%   |
| TerraTec Electronic     | 2         | 0.39%   |
| SteelSeries ApS         | 2         | 0.39%   |
| Realtek Semiconductor   | 2         | 0.39%   |
| JMTek                   | 2         | 0.39%   |
| Focusrite-Novation      | 2         | 0.39%   |
| Creative Labs           | 2         | 0.39%   |
| ASUSTek Computer        | 2         | 0.39%   |
| VIA Technologies        | 1         | 0.19%   |
| Texas Instruments       | 1         | 0.19%   |
| Syntek                  | 1         | 0.19%   |
| Sony                    | 1         | 0.19%   |
| Samson Technologies     | 1         | 0.19%   |
| Roland                  | 1         | 0.19%   |
| Micronas                | 1         | 0.19%   |
| Mark of the Unicorn     | 1         | 0.19%   |
| M-Audio                 | 1         | 0.19%   |
| GYROCOM C&C             | 1         | 0.19%   |
| GN Netcom               | 1         | 0.19%   |
| Generalplus Technology  | 1         | 0.19%   |
| DSEA A/S                | 1         | 0.19%   |
| DCMT Technology         | 1         | 0.19%   |
| BEHRINGER International | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 38        | 6.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32        | 5.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 27        | 4.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 4.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 3.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 20        | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 3.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 1.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 1.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.64%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 1.64%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.31%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8         | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.99%   |
| AMD FCH Azalia Controller                                                  | 6         | 0.99%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.66%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.66%   |
| Nvidia Audio device                                                        | 4         | 0.66%   |
| Kingston Technology HyperX 7.1 Audio                                       | 4         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 23.08%  |
| SK hynix            | 46        | 17.69%  |
| Kingston            | 36        | 13.85%  |
| Micron Technology   | 24        | 9.23%   |
| Unknown             | 23        | 8.85%   |
| G.Skill             | 20        | 7.69%   |
| Crucial             | 16        | 6.15%   |
| Corsair             | 6         | 2.31%   |
| Ramaxel Technology  | 4         | 1.54%   |
| Nanya Technology    | 3         | 1.15%   |
| A-DATA Technology   | 3         | 1.15%   |
| Unknown (ABCD)      | 2         | 0.77%   |
| Patriot             | 2         | 0.77%   |
| Elpida              | 2         | 0.77%   |
| ASint Technology    | 2         | 0.77%   |
| Apacer              | 2         | 0.77%   |
| Wilk                | 1         | 0.38%   |
| Unifosa             | 1         | 0.38%   |
| Team                | 1         | 0.38%   |
| Silicon Power       | 1         | 0.38%   |
| Qimonda             | 1         | 0.38%   |
| GOODRAM             | 1         | 0.38%   |
| AMD                 | 1         | 0.38%   |
| Aeneon              | 1         | 0.38%   |
| Unknown             | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.11%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.41%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.06%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 2         | 0.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s             | 2         | 0.7%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.7%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.7%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 0.7%    |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.7%    |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB Row Of Chips DDR4 3200MT/s   | 2         | 0.7%    |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 0.7%    |
| Crucial RAM CT51264BA160BJ.C8 4GB DIMM DDR3 1632MT/s             | 2         | 0.7%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Crucial RAM BLS8G4D240FSB.16FBR2 8GB DIMM DDR4 2400MT/s          | 2         | 0.7%    |
| Wilk RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s              | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.35%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.35%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 102       | 47%     |
| DDR3    | 76        | 35.02%  |
| DDR2    | 10        | 4.61%   |
| SDRAM   | 7         | 3.23%   |
| LPDDR4  | 7         | 3.23%   |
| Unknown | 5         | 2.3%    |
| DDR5    | 4         | 1.84%   |
| LPDDR5  | 2         | 0.92%   |
| LPDDR3  | 2         | 0.92%   |
| DDR     | 2         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 121       | 56.28%  |
| DIMM         | 84        | 39.07%  |
| Row Of Chips | 10        | 4.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 89        | 37.39%  |
| 4096  | 59        | 24.79%  |
| 16384 | 40        | 16.81%  |
| 2048  | 30        | 12.61%  |
| 1024  | 9         | 3.78%   |
| 32768 | 5         | 2.1%    |
| 512   | 5         | 2.1%    |
| 256   | 1         | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 20.49%  |
| 2667    | 39        | 15.98%  |
| 3200    | 34        | 13.93%  |
| 1333    | 20        | 8.2%    |
| 2400    | 12        | 4.92%   |
| 2133    | 9         | 3.69%   |
| 1334    | 9         | 3.69%   |
| 3600    | 7         | 2.87%   |
| Unknown | 7         | 2.87%   |
| 1067    | 6         | 2.46%   |
| 667     | 6         | 2.46%   |
| 4267    | 4         | 1.64%   |
| 3266    | 4         | 1.64%   |
| 800     | 4         | 1.64%   |
| 5600    | 3         | 1.23%   |
| 3666    | 3         | 1.23%   |
| 6400    | 2         | 0.82%   |
| 4199    | 2         | 0.82%   |
| 3733    | 2         | 0.82%   |
| 2666    | 2         | 0.82%   |
| 1867    | 2         | 0.82%   |
| 1632    | 2         | 0.82%   |
| 6000    | 1         | 0.41%   |
| 4266    | 1         | 0.41%   |
| 4133    | 1         | 0.41%   |
| 3800    | 1         | 0.41%   |
| 3334    | 1         | 0.41%   |
| 3000    | 1         | 0.41%   |
| 2933    | 1         | 0.41%   |
| 2733    | 1         | 0.41%   |
| 2134    | 1         | 0.41%   |
| 1866    | 1         | 0.41%   |
| 1800    | 1         | 0.41%   |
| 1066    | 1         | 0.41%   |
| 975     | 1         | 0.41%   |
| 533     | 1         | 0.41%   |
| 400     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Brother Industries              | 3         | 30%     |
| Samsung Electronics             | 2         | 20%     |
| Seiko Epson                     | 1         | 10%     |
| QinHeng Electronics             | 1         | 10%     |
| Konica Minolta                  | 1         | 10%     |
| Hewlett-Packard                 | 1         | 10%     |
| cab Produkttechnik GmbH & Co KG | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 10%     |
| Samsung SCX-3400 Series                      | 1         | 10%     |
| Samsung ML-1670 Series                       | 1         | 10%     |
| QinHeng CH340S                               | 1         | 10%     |
| Konica Minolta Printer                       | 1         | 10%     |
| HP Smart Tank 750 series                     | 1         | 10%     |
| cab Produkttechnik GmbH & Co KG EOS2/300     | 1         | 10%     |
| Brother HL-4140CN series                     | 1         | 10%     |
| Brother DCP-L2510D series                    | 1         | 10%     |
| Brother DCP-J152W                            | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson Perfection 660                          | 1         | 50%     |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 49        | 23%     |
| Microdia                               | 20        | 9.39%   |
| IMC Networks                           | 19        | 8.92%   |
| Sunplus Innovation Technology          | 15        | 7.04%   |
| Realtek Semiconductor                  | 15        | 7.04%   |
| Bison Electronics                      | 13        | 6.1%    |
| Logitech                               | 12        | 5.63%   |
| Lite-On Technology                     | 8         | 3.76%   |
| Syntek                                 | 6         | 2.82%   |
| Silicon Motion                         | 6         | 2.82%   |
| Luxvisions Innotech Limited            | 6         | 2.82%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.82%   |
| Apple                                  | 6         | 2.82%   |
| Acer                                   | 6         | 2.82%   |
| Suyin                                  | 5         | 2.35%   |
| Quanta                                 | 4         | 1.88%   |
| Sonix Technology                       | 2         | 0.94%   |
| Lenovo                                 | 2         | 0.94%   |
| Arkmicro Technologies                  | 2         | 0.94%   |
| Alcor Micro                            | 2         | 0.94%   |
| Z-Star Microelectronics                | 1         | 0.47%   |
| Xiaomi                                 | 1         | 0.47%   |
| Tripath Technology                     | 1         | 0.47%   |
| Samsung Electronics                    | 1         | 0.47%   |
| Microsoft                              | 1         | 0.47%   |
| LG Electronics                         | 1         | 0.47%   |
| Importek                               | 1         | 0.47%   |
| Huddly                                 | 1         | 0.47%   |
| Creative Technology                    | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 13        | 6.02%   |
| Microdia Integrated_Webcam_HD                           | 10        | 4.63%   |
| Lite-On Integrated Camera                               | 6         | 2.78%   |
| IMC Networks Integrated Camera                          | 6         | 2.78%   |
| Bison Integrated Camera                                 | 6         | 2.78%   |
| Syntek Integrated Camera                                | 4         | 1.85%   |
| Realtek USB Camera                                      | 4         | 1.85%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 1.39%   |
| Logitech Webcam C930e                                   | 3         | 1.39%   |
| Logitech HD Webcam C525                                 | 3         | 1.39%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.39%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 3         | 1.39%   |
| Chicony ThinkPad T490 Webcam                            | 3         | 1.39%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.39%   |
| Chicony Integrated HP HD Webcam                         | 3         | 1.39%   |
| Chicony HP HD Webcam                                    | 3         | 1.39%   |
| Chicony FJ Camera                                       | 3         | 1.39%   |
| Sunplus Asus Webcam                                     | 2         | 0.93%   |
| Sonix USB2.0 FHD UVC WebCam                             | 2         | 0.93%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 0.93%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.93%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.93%   |
| Realtek Integrated_Webcam_HD                            | 2         | 0.93%   |
| Realtek Integrated Webcam HD                            | 2         | 0.93%   |
| Quanta HP HD Camera                                     | 2         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.93%   |
| Luxvisions Innotech Limited Integrated RGB Camera       | 2         | 0.93%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.93%   |
| Logitech Webcam C270                                    | 2         | 0.93%   |
| Logitech HD Pro Webcam C920                             | 2         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 0.93%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.93%   |
| Chicony HD Webcam                                       | 2         | 0.93%   |
| Chicony HD User Facing                                  | 2         | 0.93%   |
| Bison SunplusIT Integrated Camera                       | 2         | 0.93%   |
| Bison EasyCamera                                        | 2         | 0.93%   |
| Arkmicro USB2.0 PC CAMERA                               | 2         | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 2         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 26        | 44.07%  |
| Synaptics                          | 17        | 28.81%  |
| Upek                               | 4         | 6.78%   |
| STMicroelectronics                 | 4         | 6.78%   |
| Shenzhen Goodix Technology         | 4         | 6.78%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.69%   |
| LighTuning Technology              | 1         | 1.69%   |
| Elan Microelectronics              | 1         | 1.69%   |
| AuthenTec                          | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 8         | 13.56%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 10.17%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 8.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 5         | 8.47%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 6.78%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 6.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 3         | 5.08%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 5.08%   |
| Synaptics WBDI                                                  | 3         | 5.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 3.39%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 3.39%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 3.39%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 3.39%   |
| Validity Sensors VFS491                                         | 1         | 1.69%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 1.69%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 1.69%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.69%   |
| Synaptics UWP WBDI                                              | 1         | 1.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.69%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.69%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 34        | 46.58%  |
| OmniKey               | 19        | 26.03%  |
| Gemalto (was Gemplus) | 7         | 9.59%   |
| Broadcom              | 6         | 8.22%   |
| Lenovo                | 3         | 4.11%   |
| SCM Microsystems      | 1         | 1.37%   |
| O2 Micro              | 1         | 1.37%   |
| Clay Logic            | 1         | 1.37%   |
| Chicony Electronics   | 1         | 1.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 39.73%  |
| OmniKey CardMan 1021                                                         | 16        | 21.92%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 8.22%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 6.85%   |
| OmniKey CardMan 4321                                                         | 3         | 4.11%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.11%   |
| Broadcom 58200                                                               | 3         | 4.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.74%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.37%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.37%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.37%   |
| Clay Logic Nitrokey Start                                                    | 1         | 1.37%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.37%   |
| Broadcom 5880                                                                | 1         | 1.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 230       | 62.84%  |
| 1     | 104       | 28.42%  |
| 2     | 28        | 7.65%   |
| 3     | 3         | 0.82%   |
| 4     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 35.12%  |
| Graphics card            | 43        | 25.6%   |
| Chipcard                 | 38        | 22.62%  |
| Net/wireless             | 6         | 3.57%   |
| Multimedia controller    | 6         | 3.57%   |
| Camera                   | 5         | 2.98%   |
| Communication controller | 3         | 1.79%   |
| Net/ethernet             | 2         | 1.19%   |
| Card reader              | 2         | 1.19%   |
| Storage                  | 1         | 0.6%    |
| Sound                    | 1         | 0.6%    |
| Modem                    | 1         | 0.6%    |
| Bluetooth                | 1         | 0.6%    |


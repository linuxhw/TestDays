Artix - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Artix.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Artix/Desktop/README.md) and [notebooks](/Dist/Artix/Notebook/README.md).

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

Total: 254

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [245d23aff3](https://linux-hardware.org/?probe=245d23aff3) | Feb 26, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| ONE-NETBOO... | One-Mix3 Pro                | Notebook    | [9869b4dd9c](https://linux-hardware.org/?probe=9869b4dd9c) | Feb 15, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [92cac1a802](https://linux-hardware.org/?probe=92cac1a802) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7ad97f8b6d](https://linux-hardware.org/?probe=7ad97f8b6d) | Feb 09, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | Notebook    | [84411df81a](https://linux-hardware.org/?probe=84411df81a) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [84fb689a7e](https://linux-hardware.org/?probe=84fb689a7e) | Feb 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [405641895c](https://linux-hardware.org/?probe=405641895c) | Jan 18, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [4ac7834c5f](https://linux-hardware.org/?probe=4ac7834c5f) | Jan 16, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [99e632c9a9](https://linux-hardware.org/?probe=99e632c9a9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [3ca2dd056d](https://linux-hardware.org/?probe=3ca2dd056d) | Jan 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [b79de349a9](https://linux-hardware.org/?probe=b79de349a9) | Jan 01, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [815525e6d2](https://linux-hardware.org/?probe=815525e6d2) | Dec 27, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | Notebook    | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [f17f99d4e6](https://linux-hardware.org/?probe=f17f99d4e6) | Nov 30, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [f42473e3f6](https://linux-hardware.org/?probe=f42473e3f6) | Nov 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [85d17374e7](https://linux-hardware.org/?probe=85d17374e7) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| HP            | Pavilion 15                 | Notebook    | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d72c486584](https://linux-hardware.org/?probe=d72c486584) | Oct 22, 2022 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [debce2faa6](https://linux-hardware.org/?probe=debce2faa6) | Oct 20, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| HP            | Pavilion g4                 | Notebook    | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| Notebook      | N141CU                      | Notebook    | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a37633e1e2](https://linux-hardware.org/?probe=a37633e1e2) | Aug 24, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [6b03bfc62e](https://linux-hardware.org/?probe=6b03bfc62e) | Aug 13, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Latitude E7440              | Notebook    | [deea307e9b](https://linux-hardware.org/?probe=deea307e9b) | Jul 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [e2d8510882](https://linux-hardware.org/?probe=e2d8510882) | Jul 27, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [304f750248](https://linux-hardware.org/?probe=304f750248) | Jul 08, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [f07968d013](https://linux-hardware.org/?probe=f07968d013) | Jul 07, 2022 |
| MOTILE        | M141                        | Notebook    | [59c616a04e](https://linux-hardware.org/?probe=59c616a04e) | Jun 30, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [8ddbebd4b1](https://linux-hardware.org/?probe=8ddbebd4b1) | Jun 28, 2022 |
| AXIOO         | Mybook 14E                  | Notebook    | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [a4b535cdee](https://linux-hardware.org/?probe=a4b535cdee) | Jun 15, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [a4054a2ac8](https://linux-hardware.org/?probe=a4054a2ac8) | Jun 10, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [009ea9b40a](https://linux-hardware.org/?probe=009ea9b40a) | Jun 09, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0MV0... | Notebook    | [3c23c9dfc6](https://linux-hardware.org/?probe=3c23c9dfc6) | Jun 08, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Dell          | Precision M6600             | Notebook    | [bb044c066c](https://linux-hardware.org/?probe=bb044c066c) | Jun 05, 2022 |
| Dell          | Latitude 5490               | Notebook    | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [dfacdafc7f](https://linux-hardware.org/?probe=dfacdafc7f) | May 11, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | Notebook    | [9792863fc7](https://linux-hardware.org/?probe=9792863fc7) | May 08, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | Notebook    | [bba77106b4](https://linux-hardware.org/?probe=bba77106b4) | May 08, 2022 |
| HP            | 15                          | Notebook    | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | Notebook    | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 246                         | Notebook    | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Lenovo        | ThinkPad T430 2347H76       | Notebook    | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [313e83e0ef](https://linux-hardware.org/?probe=313e83e0ef) | Mar 10, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [604362a51f](https://linux-hardware.org/?probe=604362a51f) | Feb 18, 2022 |
| Notebook      | N141CU                      | Notebook    | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| Acer          | Aspire V3-472PG             | Notebook    | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [6cf7935dcc](https://linux-hardware.org/?probe=6cf7935dcc) | Feb 14, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [e02c6336d6](https://linux-hardware.org/?probe=e02c6336d6) | Feb 03, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [b16ba2b14a](https://linux-hardware.org/?probe=b16ba2b14a) | Jan 31, 2022 |
| ASRock        | B150M Pro4S/D3              | Desktop     | [b7a65f897c](https://linux-hardware.org/?probe=b7a65f897c) | Jan 29, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [6a49ff6317](https://linux-hardware.org/?probe=6a49ff6317) | Jan 18, 2022 |
| Lenovo        | G400s 20244                 | Notebook    | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [29b6159e9c](https://linux-hardware.org/?probe=29b6159e9c) | Jan 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ca93455055](https://linux-hardware.org/?probe=ca93455055) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1a7ef57da7](https://linux-hardware.org/?probe=1a7ef57da7) | Jan 07, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bef1d4552a](https://linux-hardware.org/?probe=bef1d4552a) | Jan 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell          | Latitude E6440              | Notebook    | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell          | Latitude E6440              | Notebook    | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [44ccc8eb49](https://linux-hardware.org/?probe=44ccc8eb49) | Nov 24, 2021 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9fca12db52](https://linux-hardware.org/?probe=9fca12db52) | Nov 22, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | Notebook    | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | Notebook    | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [65a49b7280](https://linux-hardware.org/?probe=65a49b7280) | Oct 30, 2021 |
| HP            | 1495                        | Desktop     | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e2c619e8dd](https://linux-hardware.org/?probe=e2c619e8dd) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [1e612081c8](https://linux-hardware.org/?probe=1e612081c8) | Oct 02, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell          | Precision M6600             | Notebook    | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d5871d0e2a](https://linux-hardware.org/?probe=d5871d0e2a) | Aug 25, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ec331e992a](https://linux-hardware.org/?probe=ec331e992a) | Aug 08, 2021 |
| GPD           | P2 MAX                      | Notebook    | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [558e1369e9](https://linux-hardware.org/?probe=558e1369e9) | Jul 25, 2021 |
| GPD           | P2 MAX                      | Notebook    | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP            | 250 G3                      | Notebook    | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [156577ba27](https://linux-hardware.org/?probe=156577ba27) | Jul 18, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo        | LaVie Z 20FF0012US          | Notebook    | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f8e9ea8ffa](https://linux-hardware.org/?probe=f8e9ea8ffa) | Jun 26, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| MSI           | Z270M MORTAR                | Desktop     | [5c54607559](https://linux-hardware.org/?probe=5c54607559) | Jun 22, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell          | Precision 7550              | Notebook    | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell          | Precision 7550              | Notebook    | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [cc7cb4a34e](https://linux-hardware.org/?probe=cc7cb4a34e) | May 22, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3f10e6610b](https://linux-hardware.org/?probe=3f10e6610b) | May 18, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| HP            | Laptop 17z-ca300            | Notebook    | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d1cf148ec4](https://linux-hardware.org/?probe=d1cf148ec4) | Apr 24, 2021 |
| Acer          | Aspire V3-572PG             | Notebook    | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [dbd940a4f3](https://linux-hardware.org/?probe=dbd940a4f3) | Mar 29, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI           | GP72 7RDX                   | Notebook    | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta        | SWH                         | Notebook    | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ce4b5362ed](https://linux-hardware.org/?probe=ce4b5362ed) | Mar 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Precision 7550              | Notebook    | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [91a16f1c67](https://linux-hardware.org/?probe=91a16f1c67) | Feb 21, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [f93e302542](https://linux-hardware.org/?probe=f93e302542) | Feb 15, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Alienware     | 02XRCM A01                  | Desktop     | [554d3ebf2f](https://linux-hardware.org/?probe=554d3ebf2f) | Feb 14, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b4c4d7f99c](https://linux-hardware.org/?probe=b4c4d7f99c) | Feb 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [70eabb568f](https://linux-hardware.org/?probe=70eabb568f) | Jan 30, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [fb3e2ec12b](https://linux-hardware.org/?probe=fb3e2ec12b) | Jan 24, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fda5fabbf5](https://linux-hardware.org/?probe=fda5fabbf5) | Jan 21, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell          | 0K216C                      | Desktop     | [524206eff9](https://linux-hardware.org/?probe=524206eff9) | Jan 20, 2021 |
| Dell          | 0D9JG3 A00                  | Desktop     | [6c44448201](https://linux-hardware.org/?probe=6c44448201) | Jan 19, 2021 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [c53595bd26](https://linux-hardware.org/?probe=c53595bd26) | Jan 16, 2021 |
| Dell          | Precision 5520              | Notebook    | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [335ee823bd](https://linux-hardware.org/?probe=335ee823bd) | Jan 16, 2021 |
| ASUSTek       | E402NA                      | Notebook    | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| ASUSTek       | G11CD                       | Desktop     | [145a13d355](https://linux-hardware.org/?probe=145a13d355) | Jan 07, 2021 |
| ASUSTek       | G11CD                       | Desktop     | [dc70a6fae2](https://linux-hardware.org/?probe=dc70a6fae2) | Jan 07, 2021 |
| HP            | 2B34                        | Desktop     | [e48dc00e0a](https://linux-hardware.org/?probe=e48dc00e0a) | Jan 04, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [6dbd029143](https://linux-hardware.org/?probe=6dbd029143) | Jan 03, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [7dd04be8aa](https://linux-hardware.org/?probe=7dd04be8aa) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3f9f87f288](https://linux-hardware.org/?probe=3f9f87f288) | Dec 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2acc15f485](https://linux-hardware.org/?probe=2acc15f485) | Dec 27, 2020 |
| Dell          | Latitude E6530              | Notebook    | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD           | P2 MAX                      | Notebook    | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [cefff6c6c3](https://linux-hardware.org/?probe=cefff6c6c3) | Dec 05, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [cbcb59eb96](https://linux-hardware.org/?probe=cbcb59eb96) | Dec 03, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [28b680c91d](https://linux-hardware.org/?probe=28b680c91d) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer          | Aspire A315-53              | Notebook    | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [42a67a5d5e](https://linux-hardware.org/?probe=42a67a5d5e) | Nov 18, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [848672f794](https://linux-hardware.org/?probe=848672f794) | Oct 13, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [1193653309](https://linux-hardware.org/?probe=1193653309) | Oct 04, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Dell          | Precision 7550              | Notebook    | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [b062c35766](https://linux-hardware.org/?probe=b062c35766) | Sep 16, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [962d52b690](https://linux-hardware.org/?probe=962d52b690) | Sep 14, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [a663586db5](https://linux-hardware.org/?probe=a663586db5) | Sep 14, 2020 |
| Dell          | Precision 7550              | Notebook    | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [86215bb4fb](https://linux-hardware.org/?probe=86215bb4fb) | Aug 29, 2020 |
| Dell          | Precision 7550              | Notebook    | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e988296384](https://linux-hardware.org/?probe=e988296384) | Aug 19, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [d86cfc12cc](https://linux-hardware.org/?probe=d86cfc12cc) | Aug 19, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [937f502004](https://linux-hardware.org/?probe=937f502004) | Aug 18, 2020 |
| Acer          | Nitro AN515-51              | Notebook    | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [5d992bbc09](https://linux-hardware.org/?probe=5d992bbc09) | Aug 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ff7915ae78](https://linux-hardware.org/?probe=ff7915ae78) | Aug 07, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | Notebook    | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a57e5d7e84](https://linux-hardware.org/?probe=a57e5d7e84) | Jul 08, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook      | N130BU                      | Notebook    | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9623b5be2b](https://linux-hardware.org/?probe=9623b5be2b) | Jun 16, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4125763b79](https://linux-hardware.org/?probe=4125763b79) | Jun 12, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [82af1cec2f](https://linux-hardware.org/?probe=82af1cec2f) | May 30, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [40adc1a5f5](https://linux-hardware.org/?probe=40adc1a5f5) | Apr 03, 2020 |
| Dell          | Precision 3540              | Notebook    | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell          | Precision 3540              | Notebook    | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Biostar       | G31D-M7                     | Desktop     | [9f6a5c0f39](https://linux-hardware.org/?probe=9f6a5c0f39) | Oct 25, 2018 |
| Lenovo        | B590 20206                  | Notebook    | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 108       | 59.67%  |
| Artix          | 64        | 35.36%  |
| Artix 20220123 | 3         | 1.66%   |
| Artix 20220713 | 2         | 1.1%    |
| Artix 20210726 | 2         | 1.1%    |
| Artix 20201207 | 1         | 0.55%   |
| Artix 20201128 | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 173       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.9.14-artix1-1    | 8         | 3.88%   |
| 5.7.6-artix1-1     | 5         | 2.43%   |
| 6.1.8-artix1-1     | 4         | 1.94%   |
| 6.0.7-artix1-1     | 4         | 1.94%   |
| 5.7.12-artix1-1    | 4         | 1.94%   |
| 5.15.12-artix1-1   | 4         | 1.94%   |
| 5.12.12-artix1-1   | 4         | 1.94%   |
| 5.10.4-artix2-1    | 4         | 1.94%   |
| 5.8.8-artix1-1     | 3         | 1.46%   |
| 5.8.12-artix1-1    | 3         | 1.46%   |
| 5.18.16-artix1-1   | 3         | 1.46%   |
| 5.16.3-artix1-1    | 3         | 1.46%   |
| 5.16.10-artix1-1   | 3         | 1.46%   |
| 5.12.8-artix1-1    | 3         | 1.46%   |
| 5.12.14-artix1-1   | 3         | 1.46%   |
| 5.10.8-artix1-1    | 3         | 1.46%   |
| 5.10.6-artix1-1    | 3         | 1.46%   |
| 5.10.16-artix1-1   | 3         | 1.46%   |
| 6.1.6-artix1-1     | 2         | 0.97%   |
| 6.1.10-zen1-1-zen  | 2         | 0.97%   |
| 6.0.12-artix1-1    | 2         | 0.97%   |
| 5.9.14-zen1-1-zen  | 2         | 0.97%   |
| 5.9.12-artix1-1    | 2         | 0.97%   |
| 5.8.14-artix1-1    | 2         | 0.97%   |
| 5.7.2-artix1-1     | 2         | 0.97%   |
| 5.19.12-artix1-1   | 2         | 0.97%   |
| 5.18.9-zen1-1-zen  | 2         | 0.97%   |
| 5.18.6-artix1-1    | 2         | 0.97%   |
| 5.18.10-artix1-1   | 2         | 0.97%   |
| 5.18.0-artix1-1    | 2         | 0.97%   |
| 5.17.4-artix1-1    | 2         | 0.97%   |
| 5.17.1-artix1-1    | 2         | 0.97%   |
| 5.16.8-artix1-2    | 2         | 0.97%   |
| 5.16.1-artix1-1    | 2         | 0.97%   |
| 5.15.3-zen1-1-zen  | 2         | 0.97%   |
| 5.14.16-artix1-1   | 2         | 0.97%   |
| 5.13.8-artix1-1    | 2         | 0.97%   |
| 5.12.4-artix1-1    | 2         | 0.97%   |
| 5.12.12-zen1-1-zen | 2         | 0.97%   |
| 5.11.6-artix1-1    | 2         | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 4.85%   |
| 5.12.12 | 6         | 2.91%   |
| 6.0.7   | 5         | 2.43%   |
| 5.7.6   | 5         | 2.43%   |
| 5.15.12 | 5         | 2.43%   |
| 6.1.8   | 4         | 1.94%   |
| 6.1.10  | 4         | 1.94%   |
| 5.7.12  | 4         | 1.94%   |
| 5.12.8  | 4         | 1.94%   |
| 5.12.14 | 4         | 1.94%   |
| 5.10.4  | 4         | 1.94%   |
| 5.8.8   | 3         | 1.46%   |
| 5.8.14  | 3         | 1.46%   |
| 5.8.12  | 3         | 1.46%   |
| 5.18.16 | 3         | 1.46%   |
| 5.17.1  | 3         | 1.46%   |
| 5.16.3  | 3         | 1.46%   |
| 5.16.10 | 3         | 1.46%   |
| 5.13.8  | 3         | 1.46%   |
| 5.10.8  | 3         | 1.46%   |
| 5.10.6  | 3         | 1.46%   |
| 5.10.16 | 3         | 1.46%   |
| 5.10.15 | 3         | 1.46%   |
| 6.1.6   | 2         | 0.97%   |
| 6.0.12  | 2         | 0.97%   |
| 5.9.12  | 2         | 0.97%   |
| 5.9.0   | 2         | 0.97%   |
| 5.7.2   | 2         | 0.97%   |
| 5.19.12 | 2         | 0.97%   |
| 5.18.9  | 2         | 0.97%   |
| 5.18.6  | 2         | 0.97%   |
| 5.18.10 | 2         | 0.97%   |
| 5.18.0  | 2         | 0.97%   |
| 5.17.4  | 2         | 0.97%   |
| 5.17.12 | 2         | 0.97%   |
| 5.16.8  | 2         | 0.97%   |
| 5.16.1  | 2         | 0.97%   |
| 5.15.3  | 2         | 0.97%   |
| 5.14.16 | 2         | 0.97%   |
| 5.14.14 | 2         | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 10.66%  |
| 5.15    | 20        | 10.15%  |
| 5.12    | 19        | 9.64%   |
| 5.9     | 17        | 8.63%   |
| 5.18    | 15        | 7.61%   |
| 5.16    | 13        | 6.6%    |
| 6.1     | 12        | 6.09%   |
| 5.11    | 12        | 6.09%   |
| 5.8     | 11        | 5.58%   |
| 5.17    | 11        | 5.58%   |
| 6.0     | 10        | 5.08%   |
| 5.7     | 10        | 5.08%   |
| 5.14    | 7         | 3.55%   |
| 5.19    | 6         | 3.05%   |
| 5.13    | 6         | 3.05%   |
| 5.4     | 2         | 1.02%   |
| 4.19    | 2         | 1.02%   |
| 6.0.5   | 1         | 0.51%   |
| 5.6     | 1         | 0.51%   |
| 5.5     | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 173       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 43        | 23.12%  |
| XFCE           | 27        | 14.52%  |
| GNOME          | 27        | 14.52%  |
| Unknown        | 25        | 13.44%  |
| X-Cinnamon     | 13        | 6.99%   |
| MATE           | 12        | 6.45%   |
| i3             | 6         | 3.23%   |
| Cinnamon       | 6         | 3.23%   |
| LXQt           | 5         | 2.69%   |
| LXDE           | 4         | 2.15%   |
| KDE            | 4         | 2.15%   |
| bspwm          | 4         | 2.15%   |
| sway           | 2         | 1.08%   |
| xmonad         | 1         | 0.54%   |
| xinitrc        | 1         | 0.54%   |
| sway-dbus      | 1         | 0.54%   |
| openbox        | 1         | 0.54%   |
| nxde           | 1         | 0.54%   |
| DWM            | 1         | 0.54%   |
| awesomeminimal | 1         | 0.54%   |
| awesome        | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 124       | 69.27%  |
| Tty     | 27        | 15.08%  |
| Wayland | 18        | 10.06%  |
| Unknown | 10        | 5.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 65        | 35.91%  |
| LightDM | 55        | 30.39%  |
| SDDM    | 50        | 27.62%  |
| GDM     | 4         | 2.21%   |
| XDM     | 2         | 1.1%    |
| SLiM    | 2         | 1.1%    |
| LXDM    | 2         | 1.1%    |
| Ly      | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 79        | 44.38%  |
| Unknown | 18        | 10.11%  |
| ru_RU   | 14        | 7.87%   |
| en_GB   | 9         | 5.06%   |
| fr_FR   | 8         | 4.49%   |
| C       | 8         | 4.49%   |
| de_DE   | 6         | 3.37%   |
| pt_PT   | 3         | 1.69%   |
| es_ES   | 3         | 1.69%   |
| tr_TR   | 2         | 1.12%   |
| pl_PL   | 2         | 1.12%   |
| it_IT   | 2         | 1.12%   |
| en_CA   | 2         | 1.12%   |
| en_AU   | 2         | 1.12%   |
| en_AG   | 2         | 1.12%   |
| el_GR   | 2         | 1.12%   |
| vi_VN   | 1         | 0.56%   |
| uk_UA   | 1         | 0.56%   |
| ro_RO   | 1         | 0.56%   |
| pt_BR   | 1         | 0.56%   |
| lt_LT   | 1         | 0.56%   |
| ja_JP   | 1         | 0.56%   |
| es_MX   | 1         | 0.56%   |
| es_GT   | 1         | 0.56%   |
| es_CO   | 1         | 0.56%   |
| es_AR   | 1         | 0.56%   |
| en_NZ   | 1         | 0.56%   |
| en_IN   | 1         | 0.56%   |
| en_IE   | 1         | 0.56%   |
| de_AT   | 1         | 0.56%   |
| cs_CZ   | 1         | 0.56%   |
| bg_BG   | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 120       | 68.57%  |
| BIOS | 55        | 31.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 72.41%  |
| Btrfs   | 36        | 20.69%  |
| Xfs     | 6         | 3.45%   |
| F2fs    | 3         | 1.72%   |
| Overlay | 2         | 1.15%   |
| Jfs     | 1         | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 126       | 71.59%  |
| Unknown | 27        | 15.34%  |
| MBR     | 23        | 13.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 80.68%  |
| Yes       | 34        | 19.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 72.41%  |
| Yes       | 48        | 27.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 33        | 19.08%  |
| ASUSTek Computer       | 29        | 16.76%  |
| Hewlett-Packard        | 19        | 10.98%  |
| Gigabyte Technology    | 18        | 10.4%   |
| Dell                   | 16        | 9.25%   |
| Acer                   | 13        | 7.51%   |
| MSI                    | 12        | 6.94%   |
| ASRock                 | 6         | 3.47%   |
| Apple                  | 3         | 1.73%   |
| Timi                   | 2         | 1.16%   |
| Samsung Electronics    | 2         | 1.16%   |
| Notebook               | 2         | 1.16%   |
| Intel                  | 2         | 1.16%   |
| HUAWEI                 | 2         | 1.16%   |
| GPD                    | 2         | 1.16%   |
| UNOWHY                 | 1         | 0.58%   |
| Toshiba                | 1         | 0.58%   |
| Quanta                 | 1         | 0.58%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.58%   |
| MOTILE                 | 1         | 0.58%   |
| Microsoft              | 1         | 0.58%   |
| LG Electronics         | 1         | 0.58%   |
| HONOR                  | 1         | 0.58%   |
| Fujitsu                | 1         | 0.58%   |
| Biostar                | 1         | 0.58%   |
| AXIOO                  | 1         | 0.58%   |
| Alienware              | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                 | 2         | 1.16%   |
| MSI MS-7C02                          | 2         | 1.16%   |
| MSI MS-7A38                          | 2         | 1.16%   |
| Lenovo IdeaPad 5 15IIL05 81YK        | 2         | 1.16%   |
| HP 15                                | 2         | 1.16%   |
| GPD P2 MAX                           | 2         | 1.16%   |
| Gigabyte 970A-DS3P                   | 2         | 1.16%   |
| Dell Precision M6600                 | 2         | 1.16%   |
| Dell Precision 7550                  | 2         | 1.16%   |
| Apple MacBookAir7,2                  | 2         | 1.16%   |
| UNOWHY Y13G010S4EI                   | 1         | 0.58%   |
| Toshiba Satellite P775               | 1         | 0.58%   |
| Samsung R425D/R525D                  | 1         | 0.58%   |
| Samsung 350V5C/351V5C/3540VC/3440VC  | 1         | 0.58%   |
| Quanta SWH                           | 1         | 0.58%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro  | 1         | 0.58%   |
| Notebook N141CU                      | 1         | 0.58%   |
| Notebook N130BU                      | 1         | 0.58%   |
| MSI MS-7C89                          | 1         | 0.58%   |
| MSI MS-7C56                          | 1         | 0.58%   |
| MSI MS-7C37                          | 1         | 0.58%   |
| MSI MS-7B79                          | 1         | 0.58%   |
| MSI MS-7A69                          | 1         | 0.58%   |
| MSI Modern 15 A11M                   | 1         | 0.58%   |
| MSI GP72 7RDX                        | 1         | 0.58%   |
| MSI GF65 Thin 10SDR                  | 1         | 0.58%   |
| MOTILE M141                          | 1         | 0.58%   |
| Microsoft Surface Pro                | 1         | 0.58%   |
| LG 17Z990-R.AAC9U1                   | 1         | 0.58%   |
| Lenovo ThinkPad W500 4063CJ5         | 1         | 0.58%   |
| Lenovo ThinkPad T480s 20L8S3D400     | 1         | 0.58%   |
| Lenovo ThinkPad T480 MFG_IN_GO       | 1         | 0.58%   |
| Lenovo ThinkPad T440s 20ARS0MV00     | 1         | 0.58%   |
| Lenovo ThinkPad T430 2350BC6         | 1         | 0.58%   |
| Lenovo ThinkPad T430 2347H76         | 1         | 0.58%   |
| Lenovo ThinkPad T430 2344BZU         | 1         | 0.58%   |
| Lenovo ThinkPad T430 23427YU         | 1         | 0.58%   |
| Lenovo ThinkPad T420 4236H45         | 1         | 0.58%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00 | 1         | 0.58%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800 | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 15        | 8.67%   |
| Lenovo IdeaPad                  | 9         | 5.2%    |
| Acer Aspire                     | 9         | 5.2%    |
| Dell Precision                  | 6         | 3.47%   |
| HP Laptop                       | 5         | 2.89%   |
| Dell Inspiron                   | 5         | 2.89%   |
| Dell Latitude                   | 4         | 2.31%   |
| ASUS ROG                        | 4         | 2.31%   |
| HP 250                          | 3         | 1.73%   |
| Gigabyte X570                   | 3         | 1.73%   |
| ASUS TUF                        | 3         | 1.73%   |
| ASUS PRIME                      | 3         | 1.73%   |
| Timi RedmiBook                  | 2         | 1.16%   |
| MSI MS-7C02                     | 2         | 1.16%   |
| MSI MS-7A38                     | 2         | 1.16%   |
| Lenovo IdeaPadFlex              | 2         | 1.16%   |
| HP Pavilion                     | 2         | 1.16%   |
| HP 15                           | 2         | 1.16%   |
| GPD P2                          | 2         | 1.16%   |
| Gigabyte 970A-DS3P              | 2         | 1.16%   |
| ASUS VivoBook                   | 2         | 1.16%   |
| ASUS ASUS                       | 2         | 1.16%   |
| Apple MacBookAir7               | 2         | 1.16%   |
| Acer Nitro                      | 2         | 1.16%   |
| UNOWHY Y13G010S4EI              | 1         | 0.58%   |
| Toshiba Satellite               | 1         | 0.58%   |
| Samsung R425D                   | 1         | 0.58%   |
| Samsung 350V5C                  | 1         | 0.58%   |
| Quanta SWH                      | 1         | 0.58%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.58%   |
| Notebook N141CU                 | 1         | 0.58%   |
| Notebook N130BU                 | 1         | 0.58%   |
| MSI MS-7C89                     | 1         | 0.58%   |
| MSI MS-7C56                     | 1         | 0.58%   |
| MSI MS-7C37                     | 1         | 0.58%   |
| MSI MS-7B79                     | 1         | 0.58%   |
| MSI MS-7A69                     | 1         | 0.58%   |
| MSI Modern                      | 1         | 0.58%   |
| MSI GP72                        | 1         | 0.58%   |
| MSI GF65                        | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 37        | 21.39%  |
| 2019 | 25        | 14.45%  |
| 2018 | 20        | 11.56%  |
| 2012 | 15        | 8.67%   |
| 2017 | 14        | 8.09%   |
| 2013 | 14        | 8.09%   |
| 2011 | 11        | 6.36%   |
| 2015 | 9         | 5.2%    |
| 2021 | 7         | 4.05%   |
| 2014 | 7         | 4.05%   |
| 2016 | 5         | 2.89%   |
| 2010 | 5         | 2.89%   |
| 2008 | 2         | 1.16%   |
| 2022 | 1         | 0.58%   |
| 2009 | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 115       | 66.47%  |
| Desktop     | 54        | 31.21%  |
| Convertible | 2         | 1.16%   |
| Tablet      | 1         | 0.58%   |
| Mini pc     | 1         | 0.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 172       | 99.42%  |
| Enabled  | 1         | 0.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 47        | 26.86%  |
| 8.01-16.0   | 40        | 22.86%  |
| 4.01-8.0    | 37        | 21.14%  |
| 3.01-4.0    | 23        | 13.14%  |
| 32.01-64.0  | 12        | 6.86%   |
| 64.01-256.0 | 8         | 4.57%   |
| 1.01-2.0    | 5         | 2.86%   |
| 24.01-32.0  | 3         | 1.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 46        | 23.71%  |
| 4.01-8.0   | 45        | 23.2%   |
| 1.01-2.0   | 43        | 22.16%  |
| 3.01-4.0   | 27        | 13.92%  |
| 0.51-1.0   | 18        | 9.28%   |
| 8.01-16.0  | 9         | 4.64%   |
| 0.01-0.5   | 4         | 2.06%   |
| 16.01-24.0 | 2         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 58.19%  |
| 2      | 47        | 26.55%  |
| 3      | 16        | 9.04%   |
| 4      | 6         | 3.39%   |
| 6      | 3         | 1.69%   |
| 8      | 1         | 0.56%   |
| 7      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 129       | 74.57%  |
| Yes       | 44        | 25.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 84.39%  |
| No        | 27        | 15.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 83.24%  |
| No        | 29        | 16.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 69.71%  |
| No        | 53        | 30.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 34        | 19.54%  |
| Russia      | 19        | 10.92%  |
| Germany     | 16        | 9.2%    |
| France      | 10        | 5.75%   |
| Turkey      | 6         | 3.45%   |
| India       | 6         | 3.45%   |
| Canada      | 6         | 3.45%   |
| UK          | 5         | 2.87%   |
| Poland      | 5         | 2.87%   |
| Brazil      | 5         | 2.87%   |
| Ukraine     | 4         | 2.3%    |
| Switzerland | 4         | 2.3%    |
| Spain       | 4         | 2.3%    |
| Indonesia   | 4         | 2.3%    |
| Greece      | 4         | 2.3%    |
| Bulgaria    | 4         | 2.3%    |
| Netherlands | 3         | 1.72%   |
| Italy       | 3         | 1.72%   |
| Romania     | 2         | 1.15%   |
| Lithuania   | 2         | 1.15%   |
| Japan       | 2         | 1.15%   |
| Iran        | 2         | 1.15%   |
| Finland     | 2         | 1.15%   |
| Czechia     | 2         | 1.15%   |
| Australia   | 2         | 1.15%   |
| Argentina   | 2         | 1.15%   |
| Vietnam     | 1         | 0.57%   |
| Uzbekistan  | 1         | 0.57%   |
| Sweden      | 1         | 0.57%   |
| Slovenia    | 1         | 0.57%   |
| Peru        | 1         | 0.57%   |
| Mexico      | 1         | 0.57%   |
| Israel      | 1         | 0.57%   |
| Hong Kong   | 1         | 0.57%   |
| Guatemala   | 1         | 0.57%   |
| Colombia    | 1         | 0.57%   |
| China       | 1         | 0.57%   |
| Chile       | 1         | 0.57%   |
| Bangladesh  | 1         | 0.57%   |
| Azerbaijan  | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 6         | 3.26%   |
| Moscow            | 4         | 2.17%   |
| Frankfurt am Main | 4         | 2.17%   |
| St Petersburg     | 3         | 1.63%   |
| Jakarta           | 3         | 1.63%   |
| Dnipro            | 3         | 1.63%   |
| Ankara            | 3         | 1.63%   |
| Vilnius           | 2         | 1.09%   |
| Vancouver         | 2         | 1.09%   |
| Toronto           | 2         | 1.09%   |
| Sofia             | 2         | 1.09%   |
| Snohomish         | 2         | 1.09%   |
| San Ramon         | 2         | 1.09%   |
| Samara            | 2         | 1.09%   |
| Rio de Janeiro    | 2         | 1.09%   |
| Prague            | 2         | 1.09%   |
| Omaha             | 2         | 1.09%   |
| Neuchatel         | 2         | 1.09%   |
| Milton            | 2         | 1.09%   |
| Los Angeles       | 2         | 1.09%   |
| Kłodzko          | 2         | 1.09%   |
| Helsinki          | 2         | 1.09%   |
| Charlotte         | 2         | 1.09%   |
| Bern              | 2         | 1.09%   |
| Athens            | 2         | 1.09%   |
| Amsterdam         | 2         | 1.09%   |
| Zaporizhzhya      | 1         | 0.54%   |
| Woodbridge        | 1         | 0.54%   |
| Wigan             | 1         | 0.54%   |
| Wettringen        | 1         | 0.54%   |
| Wem               | 1         | 0.54%   |
| Vladivostok       | 1         | 0.54%   |
| Vienna            | 1         | 0.54%   |
| Varna             | 1         | 0.54%   |
| Upper Norwood     | 1         | 0.54%   |
| Ufa               | 1         | 0.54%   |
| Tokyo             | 1         | 0.54%   |
| Timișoara        | 1         | 0.54%   |
| Thessaloniki      | 1         | 0.54%   |
| Tel Aviv          | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 45        | 62     | 16.61%  |
| Seagate                      | 38        | 45     | 14.02%  |
| WDC                          | 37        | 62     | 13.65%  |
| Toshiba                      | 19        | 20     | 7.01%   |
| Kingston                     | 18        | 20     | 6.64%   |
| Sandisk                      | 14        | 17     | 5.17%   |
| Crucial                      | 12        | 19     | 4.43%   |
| Intel                        | 11        | 16     | 4.06%   |
| HGST                         | 8         | 9      | 2.95%   |
| SK hynix                     | 7         | 13     | 2.58%   |
| Hitachi                      | 6         | 7      | 2.21%   |
| Phison Electronics           | 5         | 7      | 1.85%   |
| China                        | 5         | 5      | 1.85%   |
| Unknown                      | 3         | 3      | 1.11%   |
| JMicron Technology           | 3         | 3      | 1.11%   |
| Apple                        | 3         | 4      | 1.11%   |
| A-DATA Technology            | 3         | 3      | 1.11%   |
| SPCC                         | 2         | 2      | 0.74%   |
| PNY                          | 2         | 2      | 0.74%   |
| Phison                       | 2         | 2      | 0.74%   |
| Maxtor                       | 2         | 2      | 0.74%   |
| Linux                        | 2         | 2      | 0.74%   |
| Hewlett-Packard              | 2         | 2      | 0.74%   |
| Corsair                      | 2         | 2      | 0.74%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.37%   |
| Union Memory                 | 1         | 1      | 0.37%   |
| TS512GMT                     | 1         | 5      | 0.37%   |
| Transcend                    | 1         | 1      | 0.37%   |
| Timetec                      | 1         | 2      | 0.37%   |
| Solid State Storage          | 1         | 1      | 0.37%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.37%   |
| Plextor                      | 1         | 1      | 0.37%   |
| Patriot                      | 1         | 1      | 0.37%   |
| Netac                        | 1         | 1      | 0.37%   |
| Micron/Crucial Technology    | 1         | 1      | 0.37%   |
| Micron Technology            | 1         | 1      | 0.37%   |
| LITEON                       | 1         | 1      | 0.37%   |
| Lite-On                      | 1         | 1      | 0.37%   |
| LDLC                         | 1         | 5      | 0.37%   |
| Intenso                      | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 6         | 2.01%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 1.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 1.34%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 1.34%   |
| Samsung SSD 860 EVO 250GB                           | 4         | 1.34%   |
| Crucial CT1000MX500SSD1 1TB                         | 4         | 1.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 1.01%   |
| Toshiba DT01ACA100 1TB                              | 3         | 1.01%   |
| Seagate ST3500418AS 500GB                           | 3         | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 1.01%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 3         | 1.01%   |
| Samsung SSD 970 EVO 1TB                             | 3         | 1.01%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 1.01%   |
| HGST HTS545050A7E680 500GB                          | 3         | 1.01%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 1.01%   |
| China SATA SSD 960GB                                | 3         | 1.01%   |
| WDC WD80EZAZ-11TDBA0 8TB                            | 2         | 0.67%   |
| WDC WD40EZRZ-00WN9B0 4TB                            | 2         | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.67%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 2         | 0.67%   |
| WDC WD100EMAZ-00WJTA0 10TB                          | 2         | 0.67%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.67%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.67%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.67%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.67%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.67%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.67%   |
| Samsung SSD 870 EVO 250GB                           | 2         | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.67%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD                | 2         | 0.67%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 0.67%   |
| Phison PCIe SSD 256GB                               | 2         | 0.67%   |
| Phison E12 NVMe Controller 1024GB                   | 2         | 0.67%   |
| Linux scsi_debug 8.3MB                              | 2         | 0.67%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 0.67%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.67%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.67%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.67%   |
| Apple SSD SM0256G 256GB                             | 2         | 0.67%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 38        | 45     | 36.19%  |
| WDC                | 32        | 51     | 30.48%  |
| Toshiba            | 16        | 17     | 15.24%  |
| HGST               | 8         | 9      | 7.62%   |
| Hitachi            | 6         | 7      | 5.71%   |
| Maxtor             | 2         | 2      | 1.9%    |
| JMicron Technology | 2         | 2      | 1.9%    |
| Unknown            | 1         | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 25     | 24.39%  |
| Kingston            | 13        | 14     | 15.85%  |
| Crucial             | 12        | 19     | 14.63%  |
| WDC                 | 5         | 8      | 6.1%    |
| China               | 5         | 5      | 6.1%    |
| SanDisk             | 3         | 3      | 3.66%   |
| Intel               | 3         | 4      | 3.66%   |
| Apple               | 3         | 4      | 3.66%   |
| SPCC                | 2         | 2      | 2.44%   |
| Linux               | 2         | 2      | 2.44%   |
| A-DATA Technology   | 2         | 2      | 2.44%   |
| Toshiba             | 1         | 1      | 1.22%   |
| SK hynix            | 1         | 1      | 1.22%   |
| PNY                 | 1         | 1      | 1.22%   |
| Plextor             | 1         | 1      | 1.22%   |
| Patriot             | 1         | 1      | 1.22%   |
| Netac               | 1         | 1      | 1.22%   |
| LDLC                | 1         | 5      | 1.22%   |
| Intenso             | 1         | 1      | 1.22%   |
| Hewlett-Packard     | 1         | 1      | 1.22%   |
| GOODRAM             | 1         | 1      | 1.22%   |
| AMD                 | 1         | 1      | 1.22%   |
| AGI                 | 1         | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 134    | 37.55%  |
| SSD     | 75        | 104    | 30.61%  |
| NVMe    | 72        | 109    | 29.39%  |
| Unknown | 4         | 9      | 1.63%   |
| MMC     | 2         | 2      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 128       | 234    | 60.95%  |
| NVMe | 72        | 109    | 34.29%  |
| SAS  | 8         | 13     | 3.81%   |
| MMC  | 2         | 2      | 0.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 90        | 125    | 52.02%  |
| 0.51-1.0   | 57        | 78     | 32.95%  |
| 1.01-2.0   | 12        | 14     | 6.94%   |
| 4.01-10.0  | 6         | 13     | 3.47%   |
| 3.01-4.0   | 4         | 4      | 2.31%   |
| 2.01-3.0   | 4         | 4      | 2.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 41        | 22.91%  |
| 251-500        | 39        | 21.79%  |
| 501-1000       | 26        | 14.53%  |
| 1001-2000      | 23        | 12.85%  |
| More than 3000 | 16        | 8.94%   |
| 2001-3000      | 12        | 6.7%    |
| 51-100         | 8         | 4.47%   |
| Unknown        | 7         | 3.91%   |
| 1-20           | 5         | 2.79%   |
| 21-50          | 2         | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 44        | 23.4%   |
| 101-250        | 31        | 16.49%  |
| 501-1000       | 24        | 12.77%  |
| 251-500        | 22        | 11.7%   |
| 21-50          | 19        | 10.11%  |
| 51-100         | 19        | 10.11%  |
| 1001-2000      | 11        | 5.85%   |
| More than 3000 | 8         | 4.26%   |
| Unknown        | 7         | 3.72%   |
| 2001-3000      | 3         | 1.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 6.9%    |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 6.9%    |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 3.45%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 3.45%   |
| WDC WD3200AAKX-00ERMA0 320GB                     | 1         | 1      | 3.45%   |
| WDC WD30EZRX-00DC0B0 3TB                         | 1         | 1      | 3.45%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 3.45%   |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 3.45%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.45%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 3.45%   |
| Seagate ST8000DM004-2CX188 8TB                   | 1         | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.45%   |
| Seagate ST2000DX002-2DV164 2TB                   | 1         | 1      | 3.45%   |
| Seagate ST2000DM006-2DM164 2TB                   | 1         | 1      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 3.45%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.45%   |
| Maxtor 6Y080M0 82GB                              | 1         | 1      | 3.45%   |
| LDLC SSD 120GB                                   | 1         | 3      | 3.45%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 3.45%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 3.45%   |
| Intel SSDSC2BW480A4 480GB                        | 1         | 2      | 3.45%   |
| Intel SSDPEKKW128G7 128GB                        | 1         | 1      | 3.45%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 3.45%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 3.45%   |
| Hewlett-Packard SSD EX900 250GB                  | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 20.69%  |
| WDC                 | 5         | 5      | 17.24%  |
| Toshiba             | 5         | 5      | 17.24%  |
| HGST                | 3         | 3      | 10.34%  |
| Kingston            | 2         | 2      | 6.9%    |
| Intel               | 2         | 3      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |
| Samsung Electronics | 1         | 1      | 3.45%   |
| Maxtor              | 1         | 1      | 3.45%   |
| LDLC                | 1         | 3      | 3.45%   |
| Hewlett-Packard     | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 27.27%  |
| WDC     | 5         | 5      | 22.73%  |
| Toshiba | 5         | 5      | 22.73%  |
| HGST    | 3         | 3      | 13.64%  |
| Hitachi | 2         | 2      | 9.09%   |
| Maxtor  | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 22     | 75.86%  |
| SSD  | 5         | 8      | 17.24%  |
| NVMe | 2         | 2      | 6.9%    |

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
| Works    | 102       | 187    | 52.04%  |
| Detected | 66        | 139    | 33.67%  |
| Malfunc  | 28        | 32     | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 97        | 41.63%  |
| AMD                            | 50        | 21.46%  |
| Samsung Electronics            | 29        | 12.45%  |
| SanDisk                        | 13        | 5.58%   |
| Phison Electronics             | 8         | 3.43%   |
| SK hynix                       | 6         | 2.58%   |
| Marvell Technology Group       | 6         | 2.58%   |
| Kingston Technology Company    | 5         | 2.15%   |
| Union Memory (Shenzhen)        | 3         | 1.29%   |
| ASMedia Technology             | 3         | 1.29%   |
| Toshiba America Info Systems   | 2         | 0.86%   |
| Silicon Motion                 | 2         | 0.86%   |
| Solid State Storage Technology | 1         | 0.43%   |
| Shenzhen Longsys Electronics   | 1         | 0.43%   |
| Nvidia                         | 1         | 0.43%   |
| Micron/Crucial Technology      | 1         | 0.43%   |
| Micron Technology              | 1         | 0.43%   |
| Lite-On Technology             | 1         | 0.43%   |
| JMicron Technology             | 1         | 0.43%   |
| Broadcom / LSI                 | 1         | 0.43%   |
| ADATA Technology               | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 37        | 14.23%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 6.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 4.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 2.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 1.92%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.92%   |
| Phison E12 NVMe Controller                                                     | 5         | 1.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 5         | 1.92%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.54%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.54%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.54%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.15%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.15%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.15%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.15%   |
| Intel SSD 660P Series                                                          | 3         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.15%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.15%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.77%   |
| Samsung Electronics SATA controller                                            | 2         | 0.77%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 134       | 58.52%  |
| NVMe | 73        | 31.88%  |
| RAID | 12        | 5.24%   |
| IDE  | 9         | 3.93%   |
| SAS  | 1         | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 115       | 66.47%  |
| AMD    | 58        | 33.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 2.3%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 2.3%    |
| AMD FX-8350 Eight-Core Processor              | 4         | 2.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.72%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.72%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 3         | 1.72%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 1.15%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.15%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.15%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.15%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.15%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.15%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.15%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 2         | 1.15%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.15%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 1.15%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.15%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 1.15%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.15%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.15%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.15%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 2         | 1.15%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 1.15%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.15%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.15%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.57%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.57%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.57%   |
| Intel Pentium CPU A1018 @ 2.10GHz             | 1         | 0.57%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.57%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44        | 25.43%  |
| Intel Core i7           | 29        | 16.76%  |
| AMD Ryzen 7             | 19        | 10.98%  |
| AMD Ryzen 5             | 14        | 8.09%   |
| Intel Core i3           | 12        | 6.94%   |
| Intel Celeron           | 8         | 4.62%   |
| Other                   | 7         | 4.05%   |
| AMD Ryzen 9             | 5         | 2.89%   |
| AMD Ryzen 3             | 5         | 2.89%   |
| AMD FX                  | 5         | 2.89%   |
| Intel Pentium           | 3         | 1.73%   |
| Intel Core m3           | 3         | 1.73%   |
| Intel Core 2 Duo        | 3         | 1.73%   |
| Intel Core i9           | 2         | 1.16%   |
| AMD A10                 | 2         | 1.16%   |
| Intel Xeon              | 1         | 0.58%   |
| Intel Pentium Silver    | 1         | 0.58%   |
| Intel Pentium Dual-Core | 1         | 0.58%   |
| Intel Atom              | 1         | 0.58%   |
| AMD Ryzen Threadripper  | 1         | 0.58%   |
| AMD Ryzen 7 PRO         | 1         | 0.58%   |
| AMD Ryzen 5 PRO         | 1         | 0.58%   |
| AMD Phenom II X4        | 1         | 0.58%   |
| AMD Phenom II           | 1         | 0.58%   |
| AMD E1                  | 1         | 0.58%   |
| AMD Athlon              | 1         | 0.58%   |
| AMD A6                  | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 60        | 34.68%  |
| 4      | 57        | 32.95%  |
| 8      | 24        | 13.87%  |
| 6      | 24        | 13.87%  |
| 12     | 5         | 2.89%   |
| 3      | 2         | 1.16%   |
| 32     | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 173       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 131       | 75.72%  |
| 1      | 42        | 24.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 173       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 17.98%  |
| 0x206a7    | 12        | 6.74%   |
| 0x306a9    | 11        | 6.18%   |
| 0x08701013 | 6         | 3.37%   |
| 0xa0652    | 5         | 2.81%   |
| 0x806ec    | 5         | 2.81%   |
| 0x806e9    | 5         | 2.81%   |
| 0x40651    | 5         | 2.81%   |
| 0x306d4    | 5         | 2.81%   |
| 0x08600106 | 5         | 2.81%   |
| 0x0800820d | 5         | 2.81%   |
| 0x906ed    | 4         | 2.25%   |
| 0x906e9    | 4         | 2.25%   |
| 0x806ea    | 4         | 2.25%   |
| 0x806c1    | 4         | 2.25%   |
| 0x706e5    | 4         | 2.25%   |
| 0x706a1    | 4         | 2.25%   |
| 0x906ea    | 3         | 1.69%   |
| 0x506e3    | 3         | 1.69%   |
| 0x306c3    | 3         | 1.69%   |
| 0x1067a    | 3         | 1.69%   |
| 0x08701021 | 3         | 1.69%   |
| 0x06000822 | 3         | 1.69%   |
| 0xa0655    | 2         | 1.12%   |
| 0x30678    | 2         | 1.12%   |
| 0x0a201016 | 2         | 1.12%   |
| 0x08608103 | 2         | 1.12%   |
| 0x08600103 | 2         | 1.12%   |
| 0x08108109 | 2         | 1.12%   |
| 0x08108102 | 2         | 1.12%   |
| 0x06000852 | 2         | 1.12%   |
| 0xa0653    | 1         | 0.56%   |
| 0x806eb    | 1         | 0.56%   |
| 0x806d1    | 1         | 0.56%   |
| 0x806c2    | 1         | 0.56%   |
| 0x6fd      | 1         | 0.56%   |
| 0x506c9    | 1         | 0.56%   |
| 0x406e3    | 1         | 0.56%   |
| 0x206c2    | 1         | 0.56%   |
| 0x20655    | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 34        | 19.65%  |
| Zen 2         | 19        | 10.98%  |
| IvyBridge     | 14        | 8.09%   |
| SandyBridge   | 13        | 7.51%   |
| Zen+          | 12        | 6.94%   |
| Haswell       | 9         | 5.2%    |
| CometLake     | 9         | 5.2%    |
| Zen 3         | 7         | 4.05%   |
| Zen           | 6         | 3.47%   |
| TigerLake     | 6         | 3.47%   |
| Broadwell     | 6         | 3.47%   |
| Piledriver    | 5         | 2.89%   |
| Skylake       | 4         | 2.31%   |
| IceLake       | 4         | 2.31%   |
| Goldmont plus | 4         | 2.31%   |
| Unknown       | 4         | 2.31%   |
| Westmere      | 3         | 1.73%   |
| Penryn        | 3         | 1.73%   |
| Steamroller   | 2         | 1.16%   |
| Silvermont    | 2         | 1.16%   |
| K10           | 2         | 1.16%   |
| Puma          | 1         | 0.58%   |
| Jaguar        | 1         | 0.58%   |
| Goldmont      | 1         | 0.58%   |
| Core          | 1         | 0.58%   |
| Bonnell       | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 44.88%  |
| AMD    | 62        | 30.24%  |
| Nvidia | 51        | 24.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 10        | 4.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 9         | 4.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 8         | 3.83%   |
| AMD Renoir                                                                | 8         | 3.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 2.87%   |
| Intel HD Graphics 620                                                     | 6         | 2.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 2.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 6         | 2.87%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 6         | 2.87%   |
| Intel UHD Graphics 620                                                    | 5         | 2.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 2.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 1.91%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1.91%   |
| Intel HD Graphics 5500                                                    | 4         | 1.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 1.44%   |
| AMD Lucienne                                                              | 3         | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.44%   |
| Nvidia TU117M                                                             | 2         | 0.96%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 0.96%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 0.96%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 2         | 0.96%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.96%   |
| Intel UHD Graphics 615                                                    | 2         | 0.96%   |
| Intel HD Graphics 630                                                     | 2         | 0.96%   |
| Intel HD Graphics 6000                                                    | 2         | 0.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 0.96%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 0.96%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 0.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 0.96%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 2         | 0.96%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.48%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.48%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                    | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 64        | 36.57%  |
| 1 x AMD        | 52        | 29.71%  |
| 1 x Nvidia     | 25        | 14.29%  |
| Intel + Nvidia | 23        | 13.14%  |
| 2 x AMD        | 4         | 2.29%   |
| Intel + AMD    | 4         | 2.29%   |
| AMD + Nvidia   | 3         | 1.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 142       | 81.14%  |
| Proprietary | 33        | 18.86%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 53.63%  |
| 1.01-2.0   | 20        | 11.17%  |
| 7.01-8.0   | 16        | 8.94%   |
| 3.01-4.0   | 15        | 8.38%   |
| 0.01-0.5   | 13        | 7.26%   |
| 0.51-1.0   | 10        | 5.59%   |
| 5.01-6.0   | 4         | 2.23%   |
| 8.01-16.0  | 4         | 2.23%   |
| 2.01-3.0   | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 12.26%  |
| Samsung Electronics     | 22        | 10.38%  |
| LG Display              | 21        | 9.91%   |
| BOE                     | 21        | 9.91%   |
| Chimei Innolux          | 18        | 8.49%   |
| Acer                    | 11        | 5.19%   |
| Goldstar                | 10        | 4.72%   |
| Dell                    | 9         | 4.25%   |
| Philips                 | 8         | 3.77%   |
| AOC                     | 8         | 3.77%   |
| BenQ                    | 7         | 3.3%    |
| ASUSTek Computer        | 7         | 3.3%    |
| Chi Mei Optoelectronics | 4         | 1.89%   |
| InfoVision              | 3         | 1.42%   |
| Hewlett-Packard         | 3         | 1.42%   |
| Apple                   | 3         | 1.42%   |
| Ancor Communications    | 3         | 1.42%   |
| Sony                    | 2         | 0.94%   |
| Sharp                   | 2         | 0.94%   |
| PANDA                   | 2         | 0.94%   |
| MSI                     | 2         | 0.94%   |
| ViewSonic               | 1         | 0.47%   |
| Vestel Elektronik       | 1         | 0.47%   |
| Packard Bell            | 1         | 0.47%   |
| LGD                     | 1         | 0.47%   |
| Lenovo                  | 1         | 0.47%   |
| KTC                     | 1         | 0.47%   |
| KDC                     | 1         | 0.47%   |
| Jean                    | 1         | 0.47%   |
| Iiyama                  | 1         | 0.47%   |
| Idek Iiyama             | 1         | 0.47%   |
| HVR                     | 1         | 0.47%   |
| HUAWEI                  | 1         | 0.47%   |
| HKC                     | 1         | 0.47%   |
| Hitachi                 | 1         | 0.47%   |
| Envision Peripherals    | 1         | 0.47%   |
| Eizo                    | 1         | 0.47%   |
| CTV                     | 1         | 0.47%   |
| CSO                     | 1         | 0.47%   |
| Compal                  | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 4         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.39%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 2         | 0.93%   |
| MSI MAG341CQ MSI1462 3440x1440 797x334mm 34.0-inch                        | 2         | 0.93%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.93%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 2         | 0.93%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch              | 2         | 0.93%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 0.93%   |
| AOC e22t AOC2200 1920x1080 477x268mm 21.5-inch                            | 2         | 0.93%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch     | 2         | 0.93%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                             | 1         | 0.46%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 1         | 0.46%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.46%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                             | 1         | 0.46%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.46%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.46%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch         | 1         | 0.46%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.46%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch         | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch       | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.46%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.46%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.46%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch         | 1         | 0.46%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch         | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 890x500mm 40.2-inch     | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 95        | 47.03%  |
| 1366x768 (WXGA)    | 44        | 21.78%  |
| 3840x2160 (4K)     | 17        | 8.42%   |
| 2560x1440 (QHD)    | 11        | 5.45%   |
| 1600x900 (HD+)     | 6         | 2.97%   |
| 2560x1600          | 4         | 1.98%   |
| 1440x900 (WXGA+)   | 4         | 1.98%   |
| 3440x1440          | 3         | 1.49%   |
| 2560x1080          | 2         | 0.99%   |
| 1920x1200 (WUXGA)  | 2         | 0.99%   |
| 1680x1050 (WSXGA+) | 2         | 0.99%   |
| 1280x1024 (SXGA)   | 2         | 0.99%   |
| Unknown            | 2         | 0.99%   |
| 3840x1080          | 1         | 0.5%    |
| 3600x1080          | 1         | 0.5%    |
| 2736x1824          | 1         | 0.5%    |
| 2160x1440          | 1         | 0.5%    |
| 2160x1200          | 1         | 0.5%    |
| 1360x768           | 1         | 0.5%    |
| 1280x960           | 1         | 0.5%    |
| 1024x768 (XGA)     | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 59        | 28.37%  |
| 13      | 21        | 10.1%   |
| 14      | 20        | 9.62%   |
| 27      | 19        | 9.13%   |
| 24      | 16        | 7.69%   |
| 23      | 15        | 7.21%   |
| 21      | 14        | 6.73%   |
| 17      | 9         | 4.33%   |
| 34      | 5         | 2.4%    |
| Unknown | 5         | 2.4%    |
| 84      | 4         | 1.92%   |
| 31      | 4         | 1.92%   |
| 19      | 4         | 1.92%   |
| 32      | 2         | 0.96%   |
| 20      | 2         | 0.96%   |
| 16      | 2         | 0.96%   |
| 12      | 2         | 0.96%   |
| 72      | 1         | 0.48%   |
| 52      | 1         | 0.48%   |
| 18      | 1         | 0.48%   |
| 11      | 1         | 0.48%   |
| 8       | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 44.66%  |
| 501-600     | 44        | 21.36%  |
| 401-500     | 18        | 8.74%   |
| 351-400     | 16        | 7.77%   |
| 201-300     | 9         | 4.37%   |
| 601-700     | 8         | 3.88%   |
| 701-800     | 7         | 3.4%    |
| 1501-2000   | 5         | 2.43%   |
| Unknown     | 5         | 2.43%   |
| 101-200     | 1         | 0.49%   |
| 1001-1500   | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 152       | 83.98%  |
| 16/10   | 12        | 6.63%   |
| 21/9    | 5         | 2.76%   |
| Unknown | 4         | 2.21%   |
| 5/4     | 3         | 1.66%   |
| 4/3     | 2         | 1.1%    |
| 3/2     | 2         | 1.1%    |
| 0.62    | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 28.37%  |
| 201-250        | 40        | 19.23%  |
| 81-90          | 35        | 16.83%  |
| 301-350        | 19        | 9.13%   |
| 351-500        | 11        | 5.29%   |
| 151-200        | 8         | 3.85%   |
| 121-130        | 8         | 3.85%   |
| 71-80          | 7         | 3.37%   |
| More than 1000 | 6         | 2.88%   |
| Unknown        | 5         | 2.4%    |
| 251-300        | 3         | 1.44%   |
| 131-140        | 2         | 0.96%   |
| 61-70          | 1         | 0.48%   |
| 51-60          | 1         | 0.48%   |
| 1-40           | 1         | 0.48%   |
| 141-150        | 1         | 0.48%   |
| 111-120        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 68        | 34.52%  |
| 101-120       | 57        | 28.93%  |
| 51-100        | 54        | 27.41%  |
| 161-240       | 9         | 4.57%   |
| Unknown       | 5         | 2.54%   |
| More than 240 | 2         | 1.02%   |
| 1-50          | 2         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 79.21%  |
| 2     | 33        | 18.54%  |
| 3     | 3         | 1.69%   |
| 4     | 1         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 111       | 41.11%  |
| Intel                                 | 88        | 32.59%  |
| Qualcomm Atheros                      | 23        | 8.52%   |
| Broadcom                              | 10        | 3.7%    |
| TP-Link                               | 4         | 1.48%   |
| Broadcom Limited                      | 4         | 1.48%   |
| D-Link System                         | 3         | 1.11%   |
| Xiaomi                                | 2         | 0.74%   |
| Samsung Electronics                   | 2         | 0.74%   |
| Ralink Technology                     | 2         | 0.74%   |
| Ralink                                | 2         | 0.74%   |
| Qualcomm                              | 2         | 0.74%   |
| MediaTek                              | 2         | 0.74%   |
| Marvell Technology Group              | 2         | 0.74%   |
| Sierra Wireless                       | 1         | 0.37%   |
| Qualcomm Atheros Communications       | 1         | 0.37%   |
| OPPO                                  | 1         | 0.37%   |
| Microsoft                             | 1         | 0.37%   |
| Linksys                               | 1         | 0.37%   |
| Lenovo                                | 1         | 0.37%   |
| Huawei Technologies                   | 1         | 0.37%   |
| Google                                | 1         | 0.37%   |
| DisplayLink                           | 1         | 0.37%   |
| ASIX Electronics                      | 1         | 0.37%   |
| Aquantia                              | 1         | 0.37%   |
| Apple                                 | 1         | 0.37%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 77        | 23.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 4.32%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.47%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.47%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.54%   |
| Intel Wireless 7265                                               | 5         | 1.54%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.23%   |
| Realtek 802.11ac NIC                                              | 3         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.93%   |
| Intel Wireless 7260                                               | 3         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.93%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 0.93%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.93%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.62%   |
| Intel Wireless-AC 9260                                            | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 72        | 47.37%  |
| Realtek Semiconductor                 | 31        | 20.39%  |
| Qualcomm Atheros                      | 19        | 12.5%   |
| Broadcom                              | 9         | 5.92%   |
| TP-Link                               | 4         | 2.63%   |
| Broadcom Limited                      | 4         | 2.63%   |
| Ralink Technology                     | 2         | 1.32%   |
| Ralink                                | 2         | 1.32%   |
| MediaTek                              | 2         | 1.32%   |
| Sierra Wireless                       | 1         | 0.66%   |
| Qualcomm Atheros Communications       | 1         | 0.66%   |
| Qualcomm                              | 1         | 0.66%   |
| Microsoft                             | 1         | 0.66%   |
| Marvell Technology Group              | 1         | 0.66%   |
| D-Link System                         | 1         | 0.66%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 5.81%   |
| Intel Wireless 8265 / 8275                                     | 8         | 5.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 3.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.23%   |
| Intel Wireless 7265                                            | 5         | 3.23%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.58%   |
| Realtek 802.11ac NIC                                           | 3         | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.94%   |
| Intel Wireless 7260                                            | 3         | 1.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.94%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.29%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.29%   |
| Intel Wireless-AC 9260                                         | 2         | 1.29%   |
| Intel Wireless 3165                                            | 2         | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.29%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.29%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.65%   |
| Sierra Wireless MC7700                                         | 1         | 0.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 100       | 61.35%  |
| Intel                    | 38        | 23.31%  |
| Qualcomm Atheros         | 7         | 4.29%   |
| Xiaomi                   | 2         | 1.23%   |
| Samsung Electronics      | 2         | 1.23%   |
| D-Link System            | 2         | 1.23%   |
| Qualcomm                 | 1         | 0.61%   |
| OPPO                     | 1         | 0.61%   |
| Marvell Technology Group | 1         | 0.61%   |
| Linksys                  | 1         | 0.61%   |
| Lenovo                   | 1         | 0.61%   |
| Huawei Technologies      | 1         | 0.61%   |
| Google                   | 1         | 0.61%   |
| DisplayLink              | 1         | 0.61%   |
| Broadcom                 | 1         | 0.61%   |
| ASIX Electronics         | 1         | 0.61%   |
| Aquantia                 | 1         | 0.61%   |
| Apple                    | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 77        | 45.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 8.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 4.73%   |
| Intel I211 Gigabit Network Connection                             | 8         | 4.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.78%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.18%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.18%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.59%   |
| Qualcomm A0001                                                    | 1         | 0.59%   |
| OPPO CPH1923                                                      | 1         | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.59%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.59%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.59%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.59%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.59%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.59%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.59%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.59%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.59%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.59%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 146       | 50.17%  |
| WiFi     | 145       | 49.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 60.77%  |
| Ethernet | 71        | 39.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 105       | 60.34%  |
| 1     | 64        | 36.78%  |
| 4     | 2         | 1.15%   |
| 3     | 2         | 1.15%   |
| 0     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 154       | 86.52%  |
| Yes  | 24        | 13.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 49.19%  |
| Realtek Semiconductor           | 18        | 14.52%  |
| Broadcom                        | 9         | 7.26%   |
| Cambridge Silicon Radio         | 7         | 5.65%   |
| IMC Networks                    | 6         | 4.84%   |
| Qualcomm Atheros Communications | 5         | 4.03%   |
| Lite-On Technology              | 4         | 3.23%   |
| Foxconn / Hon Hai               | 3         | 2.42%   |
| ASUSTek Computer                | 3         | 2.42%   |
| Apple                           | 3         | 2.42%   |
| Realtek                         | 2         | 1.61%   |
| Ralink                          | 1         | 0.81%   |
| Marvell Semiconductor           | 1         | 0.81%   |
| HTC (High Tech Computer)        | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 18        | 14.4%   |
| Intel AX201 Bluetooth                                                | 14        | 11.2%   |
| Realtek Bluetooth Radio                                              | 12        | 9.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 10        | 8%      |
| Intel AX200 Bluetooth                                                | 9         | 7.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7         | 5.6%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 3.2%    |
| Qualcomm Atheros  Bluetooth Device                                   | 4         | 3.2%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 4         | 3.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 2.4%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3         | 2.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 2.4%    |
| Realtek Bluetooth Radio                                              | 2         | 1.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.6%    |
| Intel AX210 Bluetooth                                                | 2         | 1.6%    |
| IMC Networks Wireless_Device                                         | 2         | 1.6%    |
| IMC Networks Bluetooth Radio                                         | 2         | 1.6%    |
| IMC Networks Bluetooth Device                                        | 2         | 1.6%    |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 1.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 1.6%    |
| Apple Bluetooth USB Host Controller                                  | 2         | 1.6%    |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.8%    |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.8%    |
| Ralink RT3290 Bluetooth                                              | 1         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.8%    |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 0.8%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1         | 0.8%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                                   | 1         | 0.8%    |
| Broadcom HP Portable Valentine                                       | 1         | 0.8%    |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.8%    |
| Broadcom BCM2070 Bluetooth Device                                    | 1         | 0.8%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 0.8%    |
| ASUS BT-270 Bluetooth Adapter                                        | 1         | 0.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.8%    |
| ASUS Bluetooth Radio                                                 | 1         | 0.8%    |
| Apple Bluetooth Host Controller                                      | 1         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 113       | 43.13%  |
| AMD                                             | 69        | 26.34%  |
| Nvidia                                          | 40        | 15.27%  |
| C-Media Electronics                             | 10        | 3.82%   |
| Realtek Semiconductor                           | 5         | 1.91%   |
| Creative Labs                                   | 3         | 1.15%   |
| Logitech                                        | 2         | 0.76%   |
| Creative Technology                             | 2         | 0.76%   |
| Corsair                                         | 2         | 0.76%   |
| TC Electronic                                   | 1         | 0.38%   |
| SteelSeries ApS                                 | 1         | 0.38%   |
| Shure                                           | 1         | 0.38%   |
| Razer USA                                       | 1         | 0.38%   |
| PreSonus Audio Electronics                      | 1         | 0.38%   |
| Plantronics                                     | 1         | 0.38%   |
| Native Instruments                              | 1         | 0.38%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.38%   |
| Lenovo                                          | 1         | 0.38%   |
| Harman                                          | 1         | 0.38%   |
| GN Netcom                                       | 1         | 0.38%   |
| Generalplus Technology                          | 1         | 0.38%   |
| Focusrite-Novation                              | 1         | 0.38%   |
| EVGA                                            | 1         | 0.38%   |
| AudioQuest                                      | 1         | 0.38%   |
| Arylic                                          | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 7.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 4.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 4.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 4%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 3.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 2.77%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.15%   |
| AMD Navi 10 HDMI Audio                                                     | 7         | 2.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.85%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.85%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.23%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.23%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.23%   |
| C-Media Electronics USB Audio Device                                       | 4         | 1.23%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.23%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.23%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 0.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.92%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.62%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.62%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 22.78%  |
| SK hynix            | 34        | 18.89%  |
| Kingston            | 25        | 13.89%  |
| Corsair             | 14        | 7.78%   |
| Micron Technology   | 12        | 6.67%   |
| G.Skill             | 11        | 6.11%   |
| Unknown             | 8         | 4.44%   |
| Crucial             | 6         | 3.33%   |
| A-DATA Technology   | 5         | 2.78%   |
| Patriot             | 4         | 2.22%   |
| Silicon Power       | 3         | 1.67%   |
| Unknown             | 3         | 1.67%   |
| Unknown (ABCD)      | 2         | 1.11%   |
| Smart               | 2         | 1.11%   |
| Ramaxel Technology  | 2         | 1.11%   |
| Nanya Technology    | 2         | 1.11%   |
| AMD                 | 2         | 1.11%   |
| Transcend           | 1         | 0.56%   |
| Team                | 1         | 0.56%   |
| Smart Brazil        | 1         | 0.56%   |
| ASint Technology    | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 2.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.11%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.58%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 1.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.58%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 3         | 1.58%   |
| Unknown                                                          | 3         | 1.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.05%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.05%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.05%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.05%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.05%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.05%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.05%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.05%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.05%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.05%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.05%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s            | 2         | 1.05%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s             | 2         | 1.05%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s         | 2         | 1.05%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.05%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 2         | 1.05%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                          | 1         | 0.53%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.53%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s              | 1         | 0.53%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s              | 1         | 0.53%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.53%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.53%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 56%     |
| DDR3    | 51        | 34%     |
| LPDDR4  | 4         | 2.67%   |
| LPDDR3  | 4         | 2.67%   |
| SDRAM   | 3         | 2%      |
| Unknown | 3         | 2%      |
| DDR2    | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 58.94%  |
| DIMM         | 47        | 31.13%  |
| Row Of Chips | 13        | 8.61%   |
| Chip         | 1         | 0.66%   |
| Unknown      | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 64        | 38.1%   |
| 4096  | 59        | 35.12%  |
| 16384 | 23        | 13.69%  |
| 2048  | 15        | 8.93%   |
| 32768 | 5         | 2.98%   |
| 1024  | 2         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 26.71%  |
| 3200    | 35        | 21.74%  |
| 2667    | 24        | 14.91%  |
| 2400    | 14        | 8.7%    |
| 1333    | 9         | 5.59%   |
| 3600    | 6         | 3.73%   |
| 2133    | 5         | 3.11%   |
| 1334    | 3         | 1.86%   |
| 4199    | 2         | 1.24%   |
| 3666    | 2         | 1.24%   |
| 3466    | 2         | 1.24%   |
| 2933    | 2         | 1.24%   |
| 4267    | 1         | 0.62%   |
| 4133    | 1         | 0.62%   |
| 3733    | 1         | 0.62%   |
| 3533    | 1         | 0.62%   |
| 3400    | 1         | 0.62%   |
| 3266    | 1         | 0.62%   |
| 2800    | 1         | 0.62%   |
| 2481    | 1         | 0.62%   |
| 2465    | 1         | 0.62%   |
| 1328    | 1         | 0.62%   |
| 1067    | 1         | 0.62%   |
| 1066    | 1         | 0.62%   |
| 800     | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Ricoh              | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Ricoh SP 212SUw               | 1         | 33.33%  |
| HP Officejet Pro L7400        | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

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
| Chicony Electronics                    | 24        | 20.34%  |
| Acer                                   | 12        | 10.17%  |
| IMC Networks                           | 11        | 9.32%   |
| Realtek Semiconductor                  | 10        | 8.47%   |
| Quanta                                 | 10        | 8.47%   |
| Suyin                                  | 6         | 5.08%   |
| Logitech                               | 6         | 5.08%   |
| Microdia                               | 5         | 4.24%   |
| Alcor Micro                            | 5         | 4.24%   |
| Syntek                                 | 4         | 3.39%   |
| Sunplus Innovation Technology          | 4         | 3.39%   |
| Silicon Motion                         | 3         | 2.54%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.54%   |
| Sonix Technology                       | 2         | 1.69%   |
| DLEQNA19IFK6G2                         | 2         | 1.69%   |
| Creative Technology                    | 2         | 1.69%   |
| WaveRider Communications               | 1         | 0.85%   |
| Microsoft                              | 1         | 0.85%   |
| Luxvisions Innotech Limited            | 1         | 0.85%   |
| Lite-On Technology                     | 1         | 0.85%   |
| LG Electronics                         | 1         | 0.85%   |
| Lenovo                                 | 1         | 0.85%   |
| KYE Systems (Mouse Systems)            | 1         | 0.85%   |
| GEMBIRD                                | 1         | 0.85%   |
| ARC International                      | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera           | 7         | 5.93%   |
| Chicony HD WebCam                        | 6         | 5.08%   |
| Acer Integrated Camera                   | 5         | 4.24%   |
| Realtek Integrated_Webcam_HD             | 4         | 3.39%   |
| Chicony Integrated Camera                | 4         | 3.39%   |
| Quanta HP TrueVision HD Camera           | 3         | 2.54%   |
| Syntek Integrated Camera                 | 2         | 1.69%   |
| Syntek EasyCamera                        | 2         | 1.69%   |
| Suyin HP Webcam                          | 2         | 1.69%   |
| Sonix USB2.0 HD UVC WebCam               | 2         | 1.69%   |
| Silicon Motion 300k Pixel Camera         | 2         | 1.69%   |
| Realtek USB2.0 HD UVC WebCam             | 2         | 1.69%   |
| Realtek HD WebCam                        | 2         | 1.69%   |
| Quanta VGA WebCam                        | 2         | 1.69%   |
| Quanta HP Webcam                         | 2         | 1.69%   |
| Microdia Integrated Webcam               | 2         | 1.69%   |
| Logitech Webcam C270                     | 2         | 1.69%   |
| DLEQNA19IFK6G2 HP TrueVision HD Camera   | 2         | 1.69%   |
| Chicony USB2.0 VGA UVC WebCam            | 2         | 1.69%   |
| Chicony USB2.0 Camera                    | 2         | 1.69%   |
| Chicony thinkpad t430s camera            | 2         | 1.69%   |
| Chicony Integrated Camera (1280x720@30)  | 2         | 1.69%   |
| Alcor Micro USB 2.0 Camera               | 2         | 1.69%   |
| Acer Lenovo EasyCamera                   | 2         | 1.69%   |
| WaveRider USB 2.0 Camera                 | 1         | 0.85%   |
| Suyin USB Webcam                         | 1         | 0.85%   |
| Suyin NEC HD WebCam                      | 1         | 0.85%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.85%   |
| Suyin 1.3M HD WebCam                     | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.85%   |
| Sunplus Integrated_Webcam_HD             | 1         | 0.85%   |
| Sunplus HD WebCam                        | 1         | 0.85%   |
| Sunplus Aukey-PC-LM1E Camera             | 1         | 0.85%   |
| Silicon Motion WebCam SCB-0355N          | 1         | 0.85%   |
| Realtek Integrated Webcam                | 1         | 0.85%   |
| Realtek HP "Truevision HD" laptop camera | 1         | 0.85%   |
| Quanta USB2.0 VGA UVC WebCam             | 1         | 0.85%   |
| Quanta HD Webcam                         | 1         | 0.85%   |
| Quanta HD User Facing                    | 1         | 0.85%   |
| Microsoft LifeCam Cinema                 | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 5         | 50%     |
| Synaptics                  | 3         | 30%     |
| Validity Sensors           | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 30%     |
| Shenzhen Goodix  FingerPrint Device               | 3         | 30%     |
| Shenzhen Goodix Fingerprint Reader                | 2         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 10%     |
| AuthenTec AES2810                                 | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 129       | 73.3%   |
| 1     | 42        | 23.86%  |
| 2     | 5         | 2.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 19.23%  |
| Net/wireless             | 7         | 13.46%  |
| Multimedia controller    | 6         | 11.54%  |
| Graphics card            | 6         | 11.54%  |
| Chipcard                 | 5         | 9.62%   |
| Camera                   | 5         | 9.62%   |
| Communication controller | 4         | 7.69%   |
| Bluetooth                | 4         | 7.69%   |
| Storage                  | 2         | 3.85%   |
| Unassigned class         | 1         | 1.92%   |
| Network                  | 1         | 1.92%   |
| Dvb card                 | 1         | 1.92%   |


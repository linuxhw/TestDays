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

Total: 265

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [a15fa484d4](https://linux-hardware.org/?probe=a15fa484d4) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [18111d76fc](https://linux-hardware.org/?probe=18111d76fc) | Apr 17, 2023 |
| Intel         | X99H                        | Desktop     | [b91cbf41c0](https://linux-hardware.org/?probe=b91cbf41c0) | Apr 06, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [a2ba637448](https://linux-hardware.org/?probe=a2ba637448) | Mar 29, 2023 |
| Dell          | G3 3500                     | Notebook    | [aa79addc8c](https://linux-hardware.org/?probe=aa79addc8c) | Mar 29, 2023 |
| ASRock        | Z690 Taichi                 | Desktop     | [fbad15ab18](https://linux-hardware.org/?probe=fbad15ab18) | Mar 24, 2023 |
| ASRock        | Z690 Taichi                 | Desktop     | [76159d5fc4](https://linux-hardware.org/?probe=76159d5fc4) | Mar 22, 2023 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [47c7f6e38d](https://linux-hardware.org/?probe=47c7f6e38d) | Mar 03, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6c74aa3736](https://linux-hardware.org/?probe=6c74aa3736) | Mar 02, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 112       | 58.95%  |
| Artix          | 67        | 35.26%  |
| Artix 20220123 | 3         | 1.58%   |
| Artix 20220713 | 2         | 1.05%   |
| Artix 20210726 | 2         | 1.05%   |
| Artix 20230320 | 1         | 0.53%   |
| Artix 20230215 | 1         | 0.53%   |
| Artix 20201207 | 1         | 0.53%   |
| Artix 20201128 | 1         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 182       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.14-artix1-1   | 8         | 3.72%   |
| 5.7.6-artix1-1    | 5         | 2.33%   |
| 6.1.8-artix1-1    | 4         | 1.86%   |
| 6.0.7-artix1-1    | 4         | 1.86%   |
| 5.7.12-artix1-1   | 4         | 1.86%   |
| 5.15.12-artix1-1  | 4         | 1.86%   |
| 5.12.12-artix1-1  | 4         | 1.86%   |
| 5.10.4-artix2-1   | 4         | 1.86%   |
| 5.8.8-artix1-1    | 3         | 1.4%    |
| 5.8.12-artix1-1   | 3         | 1.4%    |
| 5.18.16-artix1-1  | 3         | 1.4%    |
| 5.16.3-artix1-1   | 3         | 1.4%    |
| 5.16.10-artix1-1  | 3         | 1.4%    |
| 5.12.8-artix1-1   | 3         | 1.4%    |
| 5.12.14-artix1-1  | 3         | 1.4%    |
| 5.10.8-artix1-1   | 3         | 1.4%    |
| 5.10.6-artix1-1   | 3         | 1.4%    |
| 5.10.16-artix1-1  | 3         | 1.4%    |
| 6.2.6-artix1-1    | 2         | 0.93%   |
| 6.1.6-artix1-1    | 2         | 0.93%   |
| 6.1.12-artix1-1   | 2         | 0.93%   |
| 6.1.10-zen1-1-zen | 2         | 0.93%   |
| 6.0.12-artix1-1   | 2         | 0.93%   |
| 5.9.14-zen1-1-zen | 2         | 0.93%   |
| 5.9.12-artix1-1   | 2         | 0.93%   |
| 5.8.14-artix1-1   | 2         | 0.93%   |
| 5.7.2-artix1-1    | 2         | 0.93%   |
| 5.19.12-artix1-1  | 2         | 0.93%   |
| 5.18.9-zen1-1-zen | 2         | 0.93%   |
| 5.18.6-artix1-1   | 2         | 0.93%   |
| 5.18.10-artix1-1  | 2         | 0.93%   |
| 5.18.0-artix1-1   | 2         | 0.93%   |
| 5.17.4-artix1-1   | 2         | 0.93%   |
| 5.17.1-artix1-1   | 2         | 0.93%   |
| 5.16.8-artix1-2   | 2         | 0.93%   |
| 5.16.1-artix1-1   | 2         | 0.93%   |
| 5.15.3-zen1-1-zen | 2         | 0.93%   |
| 5.14.16-artix1-1  | 2         | 0.93%   |
| 5.13.8-artix1-1   | 2         | 0.93%   |
| 5.12.4-artix1-1   | 2         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 4.65%   |
| 5.12.12 | 6         | 2.79%   |
| 6.0.7   | 5         | 2.33%   |
| 5.7.6   | 5         | 2.33%   |
| 5.15.12 | 5         | 2.33%   |
| 6.1.8   | 4         | 1.86%   |
| 6.1.10  | 4         | 1.86%   |
| 5.7.12  | 4         | 1.86%   |
| 5.12.8  | 4         | 1.86%   |
| 5.12.14 | 4         | 1.86%   |
| 5.10.4  | 4         | 1.86%   |
| 5.8.8   | 3         | 1.4%    |
| 5.8.14  | 3         | 1.4%    |
| 5.8.12  | 3         | 1.4%    |
| 5.18.16 | 3         | 1.4%    |
| 5.17.1  | 3         | 1.4%    |
| 5.16.3  | 3         | 1.4%    |
| 5.16.10 | 3         | 1.4%    |
| 5.13.8  | 3         | 1.4%    |
| 5.11.16 | 3         | 1.4%    |
| 5.10.8  | 3         | 1.4%    |
| 5.10.6  | 3         | 1.4%    |
| 5.10.16 | 3         | 1.4%    |
| 5.10.15 | 3         | 1.4%    |
| 6.2.6   | 2         | 0.93%   |
| 6.1.6   | 2         | 0.93%   |
| 6.1.12  | 2         | 0.93%   |
| 6.0.12  | 2         | 0.93%   |
| 5.9.12  | 2         | 0.93%   |
| 5.9.0   | 2         | 0.93%   |
| 5.7.2   | 2         | 0.93%   |
| 5.19.12 | 2         | 0.93%   |
| 5.18.9  | 2         | 0.93%   |
| 5.18.6  | 2         | 0.93%   |
| 5.18.10 | 2         | 0.93%   |
| 5.18.0  | 2         | 0.93%   |
| 5.17.4  | 2         | 0.93%   |
| 5.17.12 | 2         | 0.93%   |
| 5.16.8  | 2         | 0.93%   |
| 5.16.1  | 2         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 10.19%  |
| 5.15    | 20        | 9.71%   |
| 5.12    | 19        | 9.22%   |
| 5.9     | 17        | 8.25%   |
| 6.1     | 15        | 7.28%   |
| 5.18    | 15        | 7.28%   |
| 5.16    | 13        | 6.31%   |
| 5.11    | 13        | 6.31%   |
| 5.8     | 11        | 5.34%   |
| 5.17    | 11        | 5.34%   |
| 6.0     | 10        | 4.85%   |
| 5.7     | 10        | 4.85%   |
| 5.14    | 7         | 3.4%    |
| 5.19    | 6         | 2.91%   |
| 5.13    | 6         | 2.91%   |
| 6.2     | 5         | 2.43%   |
| 5.4     | 2         | 0.97%   |
| 4.19    | 2         | 0.97%   |
| 6.0.5   | 1         | 0.49%   |
| 5.6     | 1         | 0.49%   |
| 5.5     | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 182       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 47        | 24.1%   |
| XFCE           | 29        | 14.87%  |
| GNOME          | 28        | 14.36%  |
| Unknown        | 26        | 13.33%  |
| X-Cinnamon     | 13        | 6.67%   |
| MATE           | 13        | 6.67%   |
| i3             | 6         | 3.08%   |
| Cinnamon       | 6         | 3.08%   |
| LXQt           | 5         | 2.56%   |
| LXDE           | 4         | 2.05%   |
| KDE            | 4         | 2.05%   |
| bspwm          | 4         | 2.05%   |
| Sway           | 2         | 1.03%   |
| xmonad         | 1         | 0.51%   |
| xinitrc        | 1         | 0.51%   |
| sway-dbus      | 1         | 0.51%   |
| openbox        | 1         | 0.51%   |
| nxde           | 1         | 0.51%   |
| DWM            | 1         | 0.51%   |
| awesomeminimal | 1         | 0.51%   |
| awesome        | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 131       | 69.68%  |
| Tty     | 27        | 14.36%  |
| Wayland | 19        | 10.11%  |
| Unknown | 11        | 5.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 36.84%  |
| LightDM | 56        | 29.47%  |
| SDDM    | 52        | 27.37%  |
| GDM     | 4         | 2.11%   |
| XDM     | 3         | 1.58%   |
| SLiM    | 2         | 1.05%   |
| LXDM    | 2         | 1.05%   |
| Ly      | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 83        | 44.39%  |
| Unknown | 19        | 10.16%  |
| ru_RU   | 15        | 8.02%   |
| en_GB   | 9         | 4.81%   |
| C       | 9         | 4.81%   |
| fr_FR   | 8         | 4.28%   |
| de_DE   | 7         | 3.74%   |
| pt_PT   | 3         | 1.6%    |
| es_ES   | 3         | 1.6%    |
| tr_TR   | 2         | 1.07%   |
| pt_BR   | 2         | 1.07%   |
| pl_PL   | 2         | 1.07%   |
| it_IT   | 2         | 1.07%   |
| en_CA   | 2         | 1.07%   |
| en_AU   | 2         | 1.07%   |
| en_AG   | 2         | 1.07%   |
| el_GR   | 2         | 1.07%   |
| vi_VN   | 1         | 0.53%   |
| uk_UA   | 1         | 0.53%   |
| ro_RO   | 1         | 0.53%   |
| lt_LT   | 1         | 0.53%   |
| ja_JP   | 1         | 0.53%   |
| es_MX   | 1         | 0.53%   |
| es_GT   | 1         | 0.53%   |
| es_CO   | 1         | 0.53%   |
| es_AR   | 1         | 0.53%   |
| en_NZ   | 1         | 0.53%   |
| en_IN   | 1         | 0.53%   |
| en_IE   | 1         | 0.53%   |
| de_AT   | 1         | 0.53%   |
| cs_CZ   | 1         | 0.53%   |
| bg_BG   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 125       | 67.93%  |
| BIOS | 59        | 32.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 134       | 73.22%  |
| Btrfs   | 37        | 20.22%  |
| Xfs     | 6         | 3.28%   |
| F2fs    | 3         | 1.64%   |
| Overlay | 2         | 1.09%   |
| Jfs     | 1         | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 131       | 70.81%  |
| Unknown | 31        | 16.76%  |
| MBR     | 23        | 12.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 80%     |
| Yes       | 37        | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 72.13%  |
| Yes       | 51        | 27.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 34        | 18.68%  |
| ASUSTek Computer       | 32        | 17.58%  |
| Hewlett-Packard        | 19        | 10.44%  |
| Gigabyte Technology    | 18        | 9.89%   |
| Dell                   | 17        | 9.34%   |
| MSI                    | 13        | 7.14%   |
| Acer                   | 13        | 7.14%   |
| ASRock                 | 7         | 3.85%   |
| Samsung Electronics    | 3         | 1.65%   |
| Intel                  | 3         | 1.65%   |
| Apple                  | 3         | 1.65%   |
| Timi                   | 2         | 1.1%    |
| Notebook               | 2         | 1.1%    |
| HUAWEI                 | 2         | 1.1%    |
| GPD                    | 2         | 1.1%    |
| UNOWHY                 | 1         | 0.55%   |
| Toshiba                | 1         | 0.55%   |
| Quanta                 | 1         | 0.55%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.55%   |
| MOTILE                 | 1         | 0.55%   |
| Microsoft              | 1         | 0.55%   |
| LG Electronics         | 1         | 0.55%   |
| HONOR                  | 1         | 0.55%   |
| Fujitsu                | 1         | 0.55%   |
| Biostar                | 1         | 0.55%   |
| AXIOO                  | 1         | 0.55%   |
| Alienware              | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| MSI MS-7A38                                           | 3         | 1.65%   |
| Timi RedmiBook 14 II                                  | 2         | 1.1%    |
| MSI MS-7C02                                           | 2         | 1.1%    |
| Lenovo IdeaPad 5 15IIL05 81YK                         | 2         | 1.1%    |
| HP 15                                                 | 2         | 1.1%    |
| GPD P2 MAX                                            | 2         | 1.1%    |
| Gigabyte 970A-DS3P                                    | 2         | 1.1%    |
| Dell Precision M6600                                  | 2         | 1.1%    |
| Dell Precision 7550                                   | 2         | 1.1%    |
| Apple MacBookAir7,2                                   | 2         | 1.1%    |
| UNOWHY Y13G010S4EI                                    | 1         | 0.55%   |
| Toshiba Satellite P775                                | 1         | 0.55%   |
| Samsung R425D/R525D                                   | 1         | 0.55%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.55%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.55%   |
| Quanta SWH                                            | 1         | 0.55%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro                   | 1         | 0.55%   |
| Notebook N141CU                                       | 1         | 0.55%   |
| Notebook N130BU                                       | 1         | 0.55%   |
| MSI MS-7C89                                           | 1         | 0.55%   |
| MSI MS-7C56                                           | 1         | 0.55%   |
| MSI MS-7C37                                           | 1         | 0.55%   |
| MSI MS-7B79                                           | 1         | 0.55%   |
| MSI MS-7A69                                           | 1         | 0.55%   |
| MSI Modern 15 A11M                                    | 1         | 0.55%   |
| MSI GP72 7RDX                                         | 1         | 0.55%   |
| MSI GF65 Thin 10SDR                                   | 1         | 0.55%   |
| MOTILE M141                                           | 1         | 0.55%   |
| Microsoft Surface Pro                                 | 1         | 0.55%   |
| LG 17Z990-R.AAC9U1                                    | 1         | 0.55%   |
| Lenovo ThinkPad W500 4063CJ5                          | 1         | 0.55%   |
| Lenovo ThinkPad T480s 20L8S3D400                      | 1         | 0.55%   |
| Lenovo ThinkPad T480 MFG_IN_GO                        | 1         | 0.55%   |
| Lenovo ThinkPad T440s 20ARS0MV00                      | 1         | 0.55%   |
| Lenovo ThinkPad T430 2350BC6                          | 1         | 0.55%   |
| Lenovo ThinkPad T430 2347H76                          | 1         | 0.55%   |
| Lenovo ThinkPad T430 2344BZU                          | 1         | 0.55%   |
| Lenovo ThinkPad T430 23427YU                          | 1         | 0.55%   |
| Lenovo ThinkPad T420 4236H45                          | 1         | 0.55%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00                  | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 15        | 8.24%   |
| Lenovo IdeaPad                  | 10        | 5.49%   |
| Acer Aspire                     | 9         | 4.95%   |
| Dell Precision                  | 6         | 3.3%    |
| HP Laptop                       | 5         | 2.75%   |
| Dell Inspiron                   | 5         | 2.75%   |
| ASUS ROG                        | 5         | 2.75%   |
| Dell Latitude                   | 4         | 2.2%    |
| MSI MS-7A38                     | 3         | 1.65%   |
| HP 250                          | 3         | 1.65%   |
| Gigabyte X570                   | 3         | 1.65%   |
| ASUS TUF                        | 3         | 1.65%   |
| ASUS PRIME                      | 3         | 1.65%   |
| ASUS ASUS                       | 3         | 1.65%   |
| Timi RedmiBook                  | 2         | 1.1%    |
| MSI MS-7C02                     | 2         | 1.1%    |
| Lenovo IdeaPadFlex              | 2         | 1.1%    |
| HP Pavilion                     | 2         | 1.1%    |
| HP 15                           | 2         | 1.1%    |
| GPD P2                          | 2         | 1.1%    |
| Gigabyte 970A-DS3P              | 2         | 1.1%    |
| ASUS VivoBook                   | 2         | 1.1%    |
| Apple MacBookAir7               | 2         | 1.1%    |
| Acer Nitro                      | 2         | 1.1%    |
| UNOWHY Y13G010S4EI              | 1         | 0.55%   |
| Toshiba Satellite               | 1         | 0.55%   |
| Samsung R425D                   | 1         | 0.55%   |
| Samsung 350V5C                  | 1         | 0.55%   |
| Samsung 300E5EV                 | 1         | 0.55%   |
| Quanta SWH                      | 1         | 0.55%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.55%   |
| Notebook N141CU                 | 1         | 0.55%   |
| Notebook N130BU                 | 1         | 0.55%   |
| MSI MS-7C89                     | 1         | 0.55%   |
| MSI MS-7C56                     | 1         | 0.55%   |
| MSI MS-7C37                     | 1         | 0.55%   |
| MSI MS-7B79                     | 1         | 0.55%   |
| MSI MS-7A69                     | 1         | 0.55%   |
| MSI Modern                      | 1         | 0.55%   |
| MSI GP72                        | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 37        | 20.33%  |
| 2019 | 27        | 14.84%  |
| 2018 | 20        | 10.99%  |
| 2017 | 16        | 8.79%   |
| 2012 | 16        | 8.79%   |
| 2013 | 14        | 7.69%   |
| 2011 | 11        | 6.04%   |
| 2015 | 9         | 4.95%   |
| 2014 | 8         | 4.4%    |
| 2021 | 7         | 3.85%   |
| 2016 | 5         | 2.75%   |
| 2010 | 5         | 2.75%   |
| 2022 | 4         | 2.2%    |
| 2008 | 2         | 1.1%    |
| 2009 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 119       | 65.38%  |
| Desktop     | 59        | 32.42%  |
| Convertible | 2         | 1.1%    |
| Tablet      | 1         | 0.55%   |
| Mini pc     | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 181       | 99.45%  |
| Enabled  | 1         | 0.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 182       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 50        | 27.17%  |
| 8.01-16.0   | 42        | 22.83%  |
| 4.01-8.0    | 40        | 21.74%  |
| 3.01-4.0    | 23        | 12.5%   |
| 32.01-64.0  | 12        | 6.52%   |
| 64.01-256.0 | 9         | 4.89%   |
| 1.01-2.0    | 5         | 2.72%   |
| 24.01-32.0  | 3         | 1.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 49        | 24.14%  |
| 4.01-8.0   | 45        | 22.17%  |
| 1.01-2.0   | 44        | 21.67%  |
| 3.01-4.0   | 32        | 15.76%  |
| 0.51-1.0   | 18        | 8.87%   |
| 8.01-16.0  | 9         | 4.43%   |
| 0.01-0.5   | 4         | 1.97%   |
| 16.01-24.0 | 2         | 0.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 107       | 57.53%  |
| 2      | 50        | 26.88%  |
| 3      | 18        | 9.68%   |
| 4      | 6         | 3.23%   |
| 6      | 3         | 1.61%   |
| 8      | 1         | 0.54%   |
| 7      | 1         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 136       | 74.73%  |
| Yes       | 46        | 25.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 85.16%  |
| No        | 27        | 14.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 82.42%  |
| No        | 32        | 17.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 70.11%  |
| No        | 55        | 29.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 36        | 19.67%  |
| Russia      | 20        | 10.93%  |
| Germany     | 17        | 9.29%   |
| France      | 10        | 5.46%   |
| India       | 7         | 3.83%   |
| UK          | 6         | 3.28%   |
| Turkey      | 6         | 3.28%   |
| Canada      | 6         | 3.28%   |
| Brazil      | 6         | 3.28%   |
| Poland      | 5         | 2.73%   |
| Ukraine     | 4         | 2.19%   |
| Switzerland | 4         | 2.19%   |
| Spain       | 4         | 2.19%   |
| Indonesia   | 4         | 2.19%   |
| Greece      | 4         | 2.19%   |
| Bulgaria    | 4         | 2.19%   |
| Netherlands | 3         | 1.64%   |
| Italy       | 3         | 1.64%   |
| Romania     | 2         | 1.09%   |
| Pakistan    | 2         | 1.09%   |
| Lithuania   | 2         | 1.09%   |
| Japan       | 2         | 1.09%   |
| Iran        | 2         | 1.09%   |
| Finland     | 2         | 1.09%   |
| Czechia     | 2         | 1.09%   |
| Australia   | 2         | 1.09%   |
| Argentina   | 2         | 1.09%   |
| Vietnam     | 1         | 0.55%   |
| Uzbekistan  | 1         | 0.55%   |
| Sweden      | 1         | 0.55%   |
| Slovenia    | 1         | 0.55%   |
| Peru        | 1         | 0.55%   |
| Mexico      | 1         | 0.55%   |
| Israel      | 1         | 0.55%   |
| Hong Kong   | 1         | 0.55%   |
| Guatemala   | 1         | 0.55%   |
| Colombia    | 1         | 0.55%   |
| China       | 1         | 0.55%   |
| Chile       | 1         | 0.55%   |
| Bangladesh  | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 6         | 3.11%   |
| Moscow            | 4         | 2.07%   |
| Frankfurt am Main | 4         | 2.07%   |
| St Petersburg     | 3         | 1.55%   |
| Jakarta           | 3         | 1.55%   |
| Dnipro            | 3         | 1.55%   |
| Ankara            | 3         | 1.55%   |
| Vilnius           | 2         | 1.04%   |
| Vancouver         | 2         | 1.04%   |
| Toronto           | 2         | 1.04%   |
| Sofia             | 2         | 1.04%   |
| Snohomish         | 2         | 1.04%   |
| San Ramon         | 2         | 1.04%   |
| Samara            | 2         | 1.04%   |
| Rio de Janeiro    | 2         | 1.04%   |
| Prague            | 2         | 1.04%   |
| Omaha             | 2         | 1.04%   |
| Neuchatel         | 2         | 1.04%   |
| Milton            | 2         | 1.04%   |
| Los Angeles       | 2         | 1.04%   |
| Kłodzko          | 2         | 1.04%   |
| Helsinki          | 2         | 1.04%   |
| Charlotte         | 2         | 1.04%   |
| Bern              | 2         | 1.04%   |
| Athens            | 2         | 1.04%   |
| Amsterdam         | 2         | 1.04%   |
| Zaporizhzhya      | 1         | 0.52%   |
| Woodbridge        | 1         | 0.52%   |
| Wigan             | 1         | 0.52%   |
| Wettringen        | 1         | 0.52%   |
| Wem               | 1         | 0.52%   |
| Vladivostok       | 1         | 0.52%   |
| Vienna            | 1         | 0.52%   |
| Varna             | 1         | 0.52%   |
| Upper Norwood     | 1         | 0.52%   |
| Ufa               | 1         | 0.52%   |
| Tokyo             | 1         | 0.52%   |
| Timișoara        | 1         | 0.52%   |
| Thessaloniki      | 1         | 0.52%   |
| Tel Aviv          | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 48        | 66     | 16.84%  |
| WDC                          | 40        | 65     | 14.04%  |
| Seagate                      | 38        | 45     | 13.33%  |
| Toshiba                      | 21        | 22     | 7.37%   |
| Kingston                     | 18        | 20     | 6.32%   |
| SanDisk                      | 14        | 17     | 4.91%   |
| Crucial                      | 13        | 20     | 4.56%   |
| Intel                        | 11        | 16     | 3.86%   |
| HGST                         | 8         | 9      | 2.81%   |
| SK hynix                     | 7         | 13     | 2.46%   |
| Phison Electronics           | 6         | 8      | 2.11%   |
| Hitachi                      | 6         | 7      | 2.11%   |
| China                        | 6         | 7      | 2.11%   |
| A-DATA Technology            | 4         | 4      | 1.4%    |
| Unknown                      | 3         | 3      | 1.05%   |
| JMicron Technology           | 3         | 3      | 1.05%   |
| Apple                        | 3         | 4      | 1.05%   |
| SPCC                         | 2         | 2      | 0.7%    |
| PNY                          | 2         | 2      | 0.7%    |
| Phison                       | 2         | 2      | 0.7%    |
| Maxtor                       | 2         | 2      | 0.7%    |
| Linux                        | 2         | 2      | 0.7%    |
| Hewlett-Packard              | 2         | 2      | 0.7%    |
| Corsair                      | 2         | 2      | 0.7%    |
| Union Memory (Shenzhen)      | 1         | 1      | 0.35%   |
| Union Memory                 | 1         | 1      | 0.35%   |
| TS512GMT                     | 1         | 5      | 0.35%   |
| Transcend                    | 1         | 1      | 0.35%   |
| Timetec                      | 1         | 2      | 0.35%   |
| SPCC Sol                     | 1         | 1      | 0.35%   |
| Solid State Storage          | 1         | 1      | 0.35%   |
| Silicon Motion               | 1         | 1      | 0.35%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.35%   |
| Plextor                      | 1         | 1      | 0.35%   |
| Patriot                      | 1         | 1      | 0.35%   |
| Netac                        | 1         | 1      | 0.35%   |
| Micron/Crucial Technology    | 1         | 1      | 0.35%   |
| Micron Technology            | 1         | 1      | 0.35%   |
| LITEON                       | 1         | 1      | 0.35%   |
| Lite-On                      | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 7         | 2.23%   |
| Seagate ST1000LM035-1RK172 970GB                  | 4         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 4         | 1.27%   |
| SanDisk NVMe SSD Drive 512GB                      | 4         | 1.27%   |
| Samsung SSD 860 EVO 250GB                         | 4         | 1.27%   |
| Crucial CT1000MX500SSD1 1TB                       | 4         | 1.27%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3         | 0.96%   |
| Toshiba MQ01ABF050 500GB                          | 3         | 0.96%   |
| Toshiba DT01ACA100 1TB                            | 3         | 0.96%   |
| Seagate ST3500418AS 500GB                         | 3         | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB                    | 3         | 0.96%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB             | 3         | 0.96%   |
| Samsung SSD 970 EVO 1TB                           | 3         | 0.96%   |
| Samsung NVMe SSD Drive 1TB                        | 3         | 0.96%   |
| HGST HTS545050A7E680 500GB                        | 3         | 0.96%   |
| Crucial CT240BX500SSD1 240GB                      | 3         | 0.96%   |
| China SATA SSD 960GB                              | 3         | 0.96%   |
| WDC WD80EZAZ-11TDBA0 8TB                          | 2         | 0.64%   |
| WDC WD40EZRZ-00WN9B0 4TB                          | 2         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.64%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 2         | 0.64%   |
| WDC WD100EMAZ-00WJTA0 10TB                        | 2         | 0.64%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 0.64%   |
| Toshiba MQ01ABD100 1TB                            | 2         | 0.64%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.64%   |
| Seagate ST500DM002-1BD142 500GB                   | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 500GB                      | 2         | 0.64%   |
| Samsung SSD 980 1TB                               | 2         | 0.64%   |
| Samsung SSD 870 EVO 250GB                         | 2         | 0.64%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.64%   |
| Samsung SSD 840 EVO 250GB                         | 2         | 0.64%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD              | 2         | 0.64%   |
| Samsung MZNLH512HALU-00000 512GB SSD              | 2         | 0.64%   |
| Phison PS5013 E13 NVMe Controller 500GB           | 2         | 0.64%   |
| Phison PCIe SSD 8TB                               | 2         | 0.64%   |
| Phison E12 NVMe Controller 512GB                  | 2         | 0.64%   |
| Linux scsi_debug 8.3MB                            | 2         | 0.64%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 0.64%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 0.64%   |
| Kingston OM8PCP3512F-AI1 512GB                    | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 38        | 45     | 34.55%  |
| WDC                | 35        | 54     | 31.82%  |
| Toshiba            | 18        | 19     | 16.36%  |
| HGST               | 8         | 9      | 7.27%   |
| Hitachi            | 6         | 7      | 5.45%   |
| Maxtor             | 2         | 2      | 1.82%   |
| JMicron Technology | 2         | 2      | 1.82%   |
| Unknown            | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 26     | 24.42%  |
| Kingston            | 13        | 14     | 15.12%  |
| Crucial             | 13        | 20     | 15.12%  |
| China               | 6         | 7      | 6.98%   |
| WDC                 | 5         | 8      | 5.81%   |
| SanDisk             | 3         | 3      | 3.49%   |
| Intel               | 3         | 4      | 3.49%   |
| Apple               | 3         | 4      | 3.49%   |
| SPCC                | 2         | 2      | 2.33%   |
| Linux               | 2         | 2      | 2.33%   |
| A-DATA Technology   | 2         | 2      | 2.33%   |
| Toshiba             | 1         | 1      | 1.16%   |
| SPCC Sol            | 1         | 1      | 1.16%   |
| SK hynix            | 1         | 1      | 1.16%   |
| PNY                 | 1         | 1      | 1.16%   |
| Plextor             | 1         | 1      | 1.16%   |
| Patriot             | 1         | 1      | 1.16%   |
| Netac               | 1         | 1      | 1.16%   |
| LDLC                | 1         | 5      | 1.16%   |
| Intenso             | 1         | 1      | 1.16%   |
| Hewlett-Packard     | 1         | 1      | 1.16%   |
| GOODRAM             | 1         | 1      | 1.16%   |
| AMD                 | 1         | 1      | 1.16%   |
| AGI                 | 1         | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 97        | 139    | 37.31%  |
| SSD     | 79        | 109    | 30.38%  |
| NVMe    | 78        | 115    | 30%     |
| Unknown | 4         | 9      | 1.54%   |
| MMC     | 2         | 2      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135       | 243    | 60.27%  |
| NVMe | 78        | 115    | 34.82%  |
| SAS  | 9         | 14     | 4.02%   |
| MMC  | 2         | 2      | 0.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 129    | 51.65%  |
| 0.51-1.0   | 60        | 82     | 32.97%  |
| 1.01-2.0   | 13        | 15     | 7.14%   |
| 4.01-10.0  | 6         | 13     | 3.3%    |
| 3.01-4.0   | 5         | 5      | 2.75%   |
| 2.01-3.0   | 4         | 4      | 2.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 43        | 22.87%  |
| 251-500        | 41        | 21.81%  |
| 501-1000       | 27        | 14.36%  |
| 1001-2000      | 25        | 13.3%   |
| More than 3000 | 16        | 8.51%   |
| 2001-3000      | 13        | 6.91%   |
| 51-100         | 8         | 4.26%   |
| Unknown        | 7         | 3.72%   |
| 1-20           | 5         | 2.66%   |
| 21-50          | 3         | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 23.86%  |
| 101-250        | 32        | 16.24%  |
| 501-1000       | 24        | 12.18%  |
| 251-500        | 23        | 11.68%  |
| 51-100         | 21        | 10.66%  |
| 21-50          | 19        | 9.64%   |
| 1001-2000      | 13        | 6.6%    |
| More than 3000 | 8         | 4.06%   |
| Unknown        | 7         | 3.55%   |
| 2001-3000      | 3         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 6.67%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 6.67%   |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 3.33%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 3.33%   |
| WDC WD3200AAKX-00ERMA0 320GB                     | 1         | 1      | 3.33%   |
| WDC WD30EZRX-00DC0B0 3TB                         | 1         | 1      | 3.33%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 3.33%   |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 3.33%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.33%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.33%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 3.33%   |
| Seagate ST8000DM004-2CX188 8TB                   | 1         | 1      | 3.33%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.33%   |
| Seagate ST2000DX002-2DV164 2TB                   | 1         | 1      | 3.33%   |
| Seagate ST2000DM006-2DM164 2TB                   | 1         | 1      | 3.33%   |
| Seagate ST1000LM035-1RK172 970GB                 | 1         | 1      | 3.33%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.33%   |
| Maxtor 6Y080M0 82GB                              | 1         | 1      | 3.33%   |
| LDLC SSD 120GB                                   | 1         | 3      | 3.33%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 3.33%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 3.33%   |
| Intel SSDSC2BW480A4 480GB                        | 1         | 2      | 3.33%   |
| Intel SSDPEKKW128G7 128GB                        | 1         | 1      | 3.33%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 3.33%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 3.33%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 3.33%   |
| Hewlett-Packard SSD EX900 250GB                  | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 20%     |
| Seagate             | 6         | 6      | 20%     |
| WDC                 | 5         | 5      | 16.67%  |
| HGST                | 3         | 3      | 10%     |
| Kingston            | 2         | 2      | 6.67%   |
| Intel               | 2         | 3      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| Maxtor              | 1         | 1      | 3.33%   |
| LDLC                | 1         | 3      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 26.09%  |
| Seagate | 6         | 6      | 26.09%  |
| WDC     | 5         | 5      | 21.74%  |
| HGST    | 3         | 3      | 13.04%  |
| Hitachi | 2         | 2      | 8.7%    |
| Maxtor  | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 23     | 76.67%  |
| SSD  | 5         | 8      | 16.67%  |
| NVMe | 2         | 2      | 6.67%   |

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
| Works    | 106       | 191    | 51.21%  |
| Detected | 72        | 150    | 34.78%  |
| Malfunc  | 29        | 33     | 14.01%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 103       | 41.53%  |
| AMD                            | 53        | 21.37%  |
| Samsung Electronics            | 32        | 12.9%   |
| SanDisk                        | 13        | 5.24%   |
| Phison Electronics             | 9         | 3.63%   |
| SK hynix                       | 6         | 2.42%   |
| Marvell Technology Group       | 6         | 2.42%   |
| Kingston Technology Company    | 5         | 2.02%   |
| Union Memory (Shenzhen)        | 3         | 1.21%   |
| Silicon Motion                 | 3         | 1.21%   |
| ASMedia Technology             | 3         | 1.21%   |
| Toshiba America Info Systems   | 2         | 0.81%   |
| ADATA Technology               | 2         | 0.81%   |
| Solid State Storage Technology | 1         | 0.4%    |
| Shenzhen Longsys Electronics   | 1         | 0.4%    |
| Nvidia                         | 1         | 0.4%    |
| Micron/Crucial Technology      | 1         | 0.4%    |
| Micron Technology              | 1         | 0.4%    |
| Lite-On Technology             | 1         | 0.4%    |
| JMicron Technology             | 1         | 0.4%    |
| Broadcom / LSI                 | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 40        | 14.44%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 6.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 4.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 3.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 2.89%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 2.53%   |
| AMD 300 Series Chipset SATA Controller                                         | 7         | 2.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 2.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 1.81%   |
| Phison E12 NVMe Controller                                                     | 5         | 1.81%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 1.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.44%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.44%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.08%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.08%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.08%   |
| Intel SSD 660P Series                                                          | 3         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.08%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.08%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.72%   |
| SanDisk NVMe Controller                                                        | 2         | 0.72%   |
| Samsung Electronics SATA controller                                            | 2         | 0.72%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.72%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 142       | 58.2%   |
| NVMe | 79        | 32.38%  |
| RAID | 13        | 5.33%   |
| IDE  | 9         | 3.69%   |
| SAS  | 1         | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 121       | 66.48%  |
| AMD    | 61        | 33.52%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 2.19%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 2.19%   |
| AMD FX-8350 Eight-Core Processor              | 4         | 2.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.64%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.64%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 1.64%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 3         | 1.64%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 1.09%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.09%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.09%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.09%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.09%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.09%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 1.09%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.09%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 2         | 1.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.09%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 1.09%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.09%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.09%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.09%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 2         | 1.09%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 1.09%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.09%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.09%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.09%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 1         | 0.55%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.55%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.55%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 47        | 25.82%  |
| Intel Core i7           | 29        | 15.93%  |
| AMD Ryzen 7             | 20        | 10.99%  |
| AMD Ryzen 5             | 15        | 8.24%   |
| Intel Core i3           | 12        | 6.59%   |
| Other                   | 9         | 4.95%   |
| Intel Celeron           | 8         | 4.4%    |
| AMD Ryzen 9             | 5         | 2.75%   |
| AMD Ryzen 3             | 5         | 2.75%   |
| AMD FX                  | 5         | 2.75%   |
| Intel Pentium           | 3         | 1.65%   |
| Intel Core m3           | 3         | 1.65%   |
| Intel Core 2 Duo        | 3         | 1.65%   |
| Intel Xeon              | 2         | 1.1%    |
| Intel Core i9           | 2         | 1.1%    |
| AMD A6                  | 2         | 1.1%    |
| AMD A10                 | 2         | 1.1%    |
| Intel Pentium Silver    | 1         | 0.55%   |
| Intel Pentium Dual-Core | 1         | 0.55%   |
| Intel Atom              | 1         | 0.55%   |
| AMD Ryzen Threadripper  | 1         | 0.55%   |
| AMD Ryzen 7 PRO         | 1         | 0.55%   |
| AMD Ryzen 5 PRO         | 1         | 0.55%   |
| AMD Phenom II X4        | 1         | 0.55%   |
| AMD Phenom II           | 1         | 0.55%   |
| AMD E1                  | 1         | 0.55%   |
| AMD Athlon              | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 61        | 33.52%  |
| 4      | 59        | 32.42%  |
| 6      | 26        | 14.29%  |
| 8      | 25        | 13.74%  |
| 12     | 5         | 2.75%   |
| 10     | 2         | 1.1%    |
| 3      | 2         | 1.1%    |
| 32     | 1         | 0.55%   |
| 1      | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 182       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 140       | 76.92%  |
| 1      | 42        | 23.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 182       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 20.86%  |
| 0x206a7    | 12        | 6.42%   |
| 0x306a9    | 11        | 5.88%   |
| 0xa0652    | 6         | 3.21%   |
| 0x08701013 | 6         | 3.21%   |
| 0x0800820d | 6         | 3.21%   |
| 0x806ec    | 5         | 2.67%   |
| 0x806e9    | 5         | 2.67%   |
| 0x40651    | 5         | 2.67%   |
| 0x306d4    | 5         | 2.67%   |
| 0x08600106 | 5         | 2.67%   |
| 0x906ed    | 4         | 2.14%   |
| 0x906e9    | 4         | 2.14%   |
| 0x806ea    | 4         | 2.14%   |
| 0x806c1    | 4         | 2.14%   |
| 0x706e5    | 4         | 2.14%   |
| 0x706a1    | 4         | 2.14%   |
| 0x906ea    | 3         | 1.6%    |
| 0x506e3    | 3         | 1.6%    |
| 0x306c3    | 3         | 1.6%    |
| 0x1067a    | 3         | 1.6%    |
| 0x08701021 | 3         | 1.6%    |
| 0x06000822 | 3         | 1.6%    |
| 0xa0655    | 2         | 1.07%   |
| 0x30678    | 2         | 1.07%   |
| 0x0a201016 | 2         | 1.07%   |
| 0x08608103 | 2         | 1.07%   |
| 0x08600103 | 2         | 1.07%   |
| 0x08108109 | 2         | 1.07%   |
| 0x08108102 | 2         | 1.07%   |
| 0x06000852 | 2         | 1.07%   |
| 0xa0653    | 1         | 0.53%   |
| 0x806eb    | 1         | 0.53%   |
| 0x806d1    | 1         | 0.53%   |
| 0x806c2    | 1         | 0.53%   |
| 0x6fd      | 1         | 0.53%   |
| 0x506c9    | 1         | 0.53%   |
| 0x406e3    | 1         | 0.53%   |
| 0x206c2    | 1         | 0.53%   |
| 0x20655    | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 19.23%  |
| Zen 2            | 19        | 10.44%  |
| IvyBridge        | 15        | 8.24%   |
| Zen+             | 14        | 7.69%   |
| SandyBridge      | 13        | 7.14%   |
| Haswell          | 10        | 5.49%   |
| CometLake        | 10        | 5.49%   |
| Zen 3            | 7         | 3.85%   |
| Zen              | 6         | 3.3%    |
| TigerLake        | 6         | 3.3%    |
| Piledriver       | 6         | 3.3%    |
| Broadwell        | 6         | 3.3%    |
| Unknown          | 5         | 2.75%   |
| Skylake          | 4         | 2.2%    |
| IceLake          | 4         | 2.2%    |
| Goldmont plus    | 4         | 2.2%    |
| Westmere         | 3         | 1.65%   |
| Penryn           | 3         | 1.65%   |
| Steamroller      | 2         | 1.1%    |
| Silvermont       | 2         | 1.1%    |
| K10              | 2         | 1.1%    |
| Puma             | 1         | 0.55%   |
| Jaguar           | 1         | 0.55%   |
| Goldmont         | 1         | 0.55%   |
| Core             | 1         | 0.55%   |
| Bonnell          | 1         | 0.55%   |
| Alderlake Hybrid | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 96        | 44.24%  |
| AMD    | 66        | 30.41%  |
| Nvidia | 55        | 25.35%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 11        | 4.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 9         | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 8         | 3.62%   |
| AMD Renoir                                                                | 8         | 3.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 3.17%   |
| Intel UHD Graphics 620                                                    | 6         | 2.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 2.71%   |
| Intel HD Graphics 620                                                     | 6         | 2.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 2.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 6         | 2.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 2.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 1.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 1.81%   |
| Intel HD Graphics 5500                                                    | 4         | 1.81%   |
| Nvidia TU117M                                                             | 3         | 1.36%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.36%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 1.36%   |
| AMD Lucienne                                                              | 3         | 1.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.36%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 3         | 1.36%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 0.9%    |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 0.9%    |
| Nvidia GM206 [GeForce GTX 950]                                            | 2         | 0.9%    |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.9%    |
| Intel UHD Graphics 615                                                    | 2         | 0.9%    |
| Intel HD Graphics 630                                                     | 2         | 0.9%    |
| Intel HD Graphics 6000                                                    | 2         | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 0.9%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 0.9%    |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 0.9%    |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                 | 2         | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 0.9%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 2         | 0.9%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 0.9%    |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.45%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 35.33%  |
| 1 x AMD        | 56        | 30.43%  |
| 1 x Nvidia     | 26        | 14.13%  |
| Intel + Nvidia | 26        | 14.13%  |
| 2 x AMD        | 4         | 2.17%   |
| Intel + AMD    | 4         | 2.17%   |
| AMD + Nvidia   | 3         | 1.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 149       | 80.98%  |
| Proprietary | 35        | 19.02%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 54.26%  |
| 1.01-2.0   | 21        | 11.17%  |
| 7.01-8.0   | 16        | 8.51%   |
| 3.01-4.0   | 15        | 7.98%   |
| 0.01-0.5   | 13        | 6.91%   |
| 0.51-1.0   | 10        | 5.32%   |
| 8.01-16.0  | 6         | 3.19%   |
| 5.01-6.0   | 4         | 2.13%   |
| 2.01-3.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 11.31%  |
| Samsung Electronics     | 23        | 10.41%  |
| LG Display              | 21        | 9.5%    |
| BOE                     | 21        | 9.5%    |
| Chimei Innolux          | 20        | 9.05%   |
| Acer                    | 11        | 4.98%   |
| Goldstar                | 10        | 4.52%   |
| Dell                    | 9         | 4.07%   |
| Philips                 | 8         | 3.62%   |
| ASUSTek Computer        | 8         | 3.62%   |
| AOC                     | 8         | 3.62%   |
| BenQ                    | 7         | 3.17%   |
| Chi Mei Optoelectronics | 5         | 2.26%   |
| PANDA                   | 3         | 1.36%   |
| InfoVision              | 3         | 1.36%   |
| Hewlett-Packard         | 3         | 1.36%   |
| Apple                   | 3         | 1.36%   |
| Ancor Communications    | 3         | 1.36%   |
| ViewSonic               | 2         | 0.9%    |
| Sony                    | 2         | 0.9%    |
| Sharp                   | 2         | 0.9%    |
| MSI                     | 2         | 0.9%    |
| Lenovo                  | 2         | 0.9%    |
| Vestel Elektronik       | 1         | 0.45%   |
| Packard Bell            | 1         | 0.45%   |
| LGD                     | 1         | 0.45%   |
| LG Electronics          | 1         | 0.45%   |
| Lenovo Group Limited    | 1         | 0.45%   |
| KTC                     | 1         | 0.45%   |
| KDC                     | 1         | 0.45%   |
| Jean                    | 1         | 0.45%   |
| Iiyama                  | 1         | 0.45%   |
| Idek Iiyama             | 1         | 0.45%   |
| HVR                     | 1         | 0.45%   |
| HUAWEI                  | 1         | 0.45%   |
| HKC                     | 1         | 0.45%   |
| Hitachi                 | 1         | 0.45%   |
| Envision Peripherals    | 1         | 0.45%   |
| Eizo                    | 1         | 0.45%   |
| CTV                     | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 4         | 1.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.33%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 2         | 0.89%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                        | 2         | 0.89%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.89%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 0.89%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 0.89%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 0.89%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 2         | 0.89%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch              | 2         | 0.89%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 0.89%   |
| AOC e22t AOC2200 1920x1080 477x268mm 21.5-inch                            | 2         | 0.89%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch     | 2         | 0.89%   |
| ViewSonic VA2256 Series VSC3136 1920x1080 476x268mm 21.5-inch             | 1         | 0.44%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                             | 1         | 0.44%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 1         | 0.44%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.44%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                             | 1         | 0.44%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.44%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.44%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch         | 1         | 0.44%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.44%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch         | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch       | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.44%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch        | 1         | 0.44%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.44%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.44%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch         | 1         | 0.44%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch         | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 100       | 47.17%  |
| 1366x768 (WXGA)    | 46        | 21.7%   |
| 3840x2160 (4K)     | 17        | 8.02%   |
| 2560x1440 (QHD)    | 10        | 4.72%   |
| 1600x900 (HD+)     | 6         | 2.83%   |
| 1440x900 (WXGA+)   | 5         | 2.36%   |
| 2560x1600          | 4         | 1.89%   |
| 3440x1440          | 3         | 1.42%   |
| Unknown            | 3         | 1.42%   |
| 2560x1080          | 2         | 0.94%   |
| 1920x1200 (WUXGA)  | 2         | 0.94%   |
| 1680x1050 (WSXGA+) | 2         | 0.94%   |
| 1360x768           | 2         | 0.94%   |
| 1280x1024 (SXGA)   | 2         | 0.94%   |
| 4480x1080          | 1         | 0.47%   |
| 3840x1080          | 1         | 0.47%   |
| 3600x1080          | 1         | 0.47%   |
| 2736x1824          | 1         | 0.47%   |
| 2160x1440          | 1         | 0.47%   |
| 2160x1200          | 1         | 0.47%   |
| 1280x960           | 1         | 0.47%   |
| 1024x768 (XGA)     | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 62        | 28.7%   |
| 13      | 22        | 10.19%  |
| 14      | 20        | 9.26%   |
| 27      | 18        | 8.33%   |
| 24      | 17        | 7.87%   |
| 23      | 16        | 7.41%   |
| 21      | 15        | 6.94%   |
| 17      | 9         | 4.17%   |
| Unknown | 6         | 2.78%   |
| 34      | 5         | 2.31%   |
| 19      | 5         | 2.31%   |
| 84      | 4         | 1.85%   |
| 31      | 4         | 1.85%   |
| 32      | 2         | 0.93%   |
| 20      | 2         | 0.93%   |
| 16      | 2         | 0.93%   |
| 12      | 2         | 0.93%   |
| 72      | 1         | 0.46%   |
| 52      | 1         | 0.46%   |
| 18      | 1         | 0.46%   |
| 11      | 1         | 0.46%   |
| 8       | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 44.86%  |
| 501-600     | 45        | 21.03%  |
| 401-500     | 20        | 9.35%   |
| 351-400     | 16        | 7.48%   |
| 201-300     | 9         | 4.21%   |
| 601-700     | 8         | 3.74%   |
| 701-800     | 7         | 3.27%   |
| Unknown     | 6         | 2.8%    |
| 1501-2000   | 5         | 2.34%   |
| 101-200     | 1         | 0.47%   |
| 1001-1500   | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 158       | 83.6%   |
| 16/10   | 13        | 6.88%   |
| 21/9    | 5         | 2.65%   |
| Unknown | 5         | 2.65%   |
| 5/4     | 3         | 1.59%   |
| 4/3     | 2         | 1.06%   |
| 3/2     | 2         | 1.06%   |
| 0.62    | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 28.7%   |
| 201-250        | 43        | 19.91%  |
| 81-90          | 36        | 16.67%  |
| 301-350        | 18        | 8.33%   |
| 351-500        | 11        | 5.09%   |
| 151-200        | 9         | 4.17%   |
| 121-130        | 8         | 3.7%    |
| 71-80          | 7         | 3.24%   |
| More than 1000 | 6         | 2.78%   |
| Unknown        | 6         | 2.78%   |
| 251-300        | 3         | 1.39%   |
| 131-140        | 2         | 0.93%   |
| 61-70          | 1         | 0.46%   |
| 51-60          | 1         | 0.46%   |
| 1-40           | 1         | 0.46%   |
| 141-150        | 1         | 0.46%   |
| 111-120        | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 33.99%  |
| 101-120       | 58        | 28.57%  |
| 51-100        | 57        | 28.08%  |
| 161-240       | 9         | 4.43%   |
| Unknown       | 6         | 2.96%   |
| More than 240 | 2         | 0.99%   |
| 1-50          | 2         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 147       | 78.61%  |
| 2     | 36        | 19.25%  |
| 3     | 3         | 1.6%    |
| 4     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 119       | 42.05%  |
| Intel                                 | 92        | 32.51%  |
| Qualcomm Atheros                      | 24        | 8.48%   |
| Broadcom                              | 10        | 3.53%   |
| TP-Link                               | 4         | 1.41%   |
| Broadcom Limited                      | 4         | 1.41%   |
| D-Link System                         | 3         | 1.06%   |
| Xiaomi                                | 2         | 0.71%   |
| Samsung Electronics                   | 2         | 0.71%   |
| Ralink Technology                     | 2         | 0.71%   |
| Ralink                                | 2         | 0.71%   |
| Qualcomm                              | 2         | 0.71%   |
| MediaTek                              | 2         | 0.71%   |
| Marvell Technology Group              | 2         | 0.71%   |
| Sierra Wireless                       | 1         | 0.35%   |
| Qualcomm Atheros Communications       | 1         | 0.35%   |
| OPPO Electronics                      | 1         | 0.35%   |
| Microsoft                             | 1         | 0.35%   |
| Linksys                               | 1         | 0.35%   |
| Lenovo                                | 1         | 0.35%   |
| Huawei Technologies                   | 1         | 0.35%   |
| Google                                | 1         | 0.35%   |
| DisplayLink                           | 1         | 0.35%   |
| ASIX Electronics                      | 1         | 0.35%   |
| Aquantia                              | 1         | 0.35%   |
| Apple                                 | 1         | 0.35%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 23.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 4.71%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 2.65%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.35%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.06%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.47%   |
| Intel Wireless 7265                                               | 5         | 1.47%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.18%   |
| Realtek 802.11ac NIC                                              | 3         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.88%   |
| Intel Wireless 7260                                               | 3         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.88%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 0.88%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.59%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 75        | 47.47%  |
| Realtek Semiconductor                 | 33        | 20.89%  |
| Qualcomm Atheros                      | 20        | 12.66%  |
| Broadcom                              | 9         | 5.7%    |
| TP-Link                               | 4         | 2.53%   |
| Broadcom Limited                      | 4         | 2.53%   |
| Ralink Technology                     | 2         | 1.27%   |
| Ralink                                | 2         | 1.27%   |
| MediaTek                              | 2         | 1.27%   |
| Sierra Wireless                       | 1         | 0.63%   |
| Qualcomm Atheros Communications       | 1         | 0.63%   |
| Qualcomm                              | 1         | 0.63%   |
| Microsoft                             | 1         | 0.63%   |
| Marvell Technology Group              | 1         | 0.63%   |
| D-Link System                         | 1         | 0.63%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 5.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.97%   |
| Intel Wireless 8265 / 8275                                     | 8         | 4.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 3.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.11%   |
| Intel Wireless 7265                                            | 5         | 3.11%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 3.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 3.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.48%   |
| Realtek 802.11ac NIC                                           | 3         | 1.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.86%   |
| Intel Wireless 7260                                            | 3         | 1.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.86%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.86%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.24%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.24%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.24%   |
| Intel Wireless-AC 9260                                         | 2         | 1.24%   |
| Intel Wireless 3165                                            | 2         | 1.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.24%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.24%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.62%   |
| Sierra Wireless MC7710                                         | 1         | 0.62%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 107       | 62.21%  |
| Intel                    | 41        | 23.84%  |
| Qualcomm Atheros         | 7         | 4.07%   |
| Xiaomi                   | 2         | 1.16%   |
| D-Link System            | 2         | 1.16%   |
| Samsung Electronics      | 1         | 0.58%   |
| Qualcomm                 | 1         | 0.58%   |
| OPPO Electronics         | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Linksys                  | 1         | 0.58%   |
| Lenovo                   | 1         | 0.58%   |
| Huawei Technologies      | 1         | 0.58%   |
| Google                   | 1         | 0.58%   |
| DisplayLink              | 1         | 0.58%   |
| Broadcom                 | 1         | 0.58%   |
| ASIX Electronics         | 1         | 0.58%   |
| Aquantia                 | 1         | 0.58%   |
| Apple                    | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 45.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 8.99%   |
| Intel I211 Gigabit Network Connection                             | 9         | 5.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 4.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.69%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.69%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.12%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.12%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.12%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm A0001                                                    | 1         | 0.56%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.56%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.56%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.56%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.56%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 155       | 50.49%  |
| WiFi     | 151       | 49.19%  |
| Modem    | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 116       | 61.05%  |
| Ethernet | 74        | 38.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 110       | 60.11%  |
| 1     | 67        | 36.61%  |
| 3     | 3         | 1.64%   |
| 4     | 2         | 1.09%   |
| 0     | 1         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 159       | 85.03%  |
| Yes  | 28        | 14.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 48.85%  |
| Realtek Semiconductor           | 19        | 14.5%   |
| Broadcom                        | 9         | 6.87%   |
| Cambridge Silicon Radio         | 8         | 6.11%   |
| Qualcomm Atheros Communications | 6         | 4.58%   |
| IMC Networks                    | 6         | 4.58%   |
| Lite-On Technology              | 4         | 3.05%   |
| Foxconn / Hon Hai               | 3         | 2.29%   |
| ASUSTek Computer                | 3         | 2.29%   |
| Apple                           | 3         | 2.29%   |
| Realtek                         | 2         | 1.53%   |
| Ralink                          | 1         | 0.76%   |
| Marvell Semiconductor           | 1         | 0.76%   |
| HTC (High Tech Computer)        | 1         | 0.76%   |
| Dynex                           | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 18        | 13.64%  |
| Intel AX201 Bluetooth                                                | 16        | 12.12%  |
| Realtek Bluetooth Radio                                              | 12        | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 10        | 7.58%   |
| Intel AX200 Bluetooth                                                | 9         | 6.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 8         | 6.06%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 3.03%   |
| Qualcomm Atheros  Bluetooth Device                                   | 4         | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4         | 3.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3         | 2.27%   |
| Intel AX210 Bluetooth                                                | 3         | 2.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 2.27%   |
| Realtek Bluetooth Radio                                              | 2         | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.52%   |
| IMC Networks Wireless_Device                                         | 2         | 1.52%   |
| IMC Networks Bluetooth Radio                                         | 2         | 1.52%   |
| IMC Networks Bluetooth Device                                        | 2         | 1.52%   |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 1.52%   |
| Apple Bluetooth USB Host Controller                                  | 2         | 1.52%   |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.76%   |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.76%   |
| Realtek Bluetooth 5.1 Radio                                          | 1         | 0.76%   |
| Ralink RT3290 Bluetooth                                              | 1         | 0.76%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 0.76%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1         | 0.76%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1         | 0.76%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1         | 0.76%   |
| Broadcom HP Portable Valentine                                       | 1         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.76%   |
| Broadcom BCM2070 Bluetooth Device                                    | 1         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 0.76%   |
| ASUS BT-270 Bluetooth Adapter                                        | 1         | 0.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.76%   |
| ASUS Bluetooth Radio                                                 | 1         | 0.76%   |
| Apple Bluetooth Host Controller                                      | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 119       | 42.81%  |
| AMD                                             | 74        | 26.62%  |
| Nvidia                                          | 42        | 15.11%  |
| C-Media Electronics                             | 12        | 4.32%   |
| Realtek Semiconductor                           | 5         | 1.8%    |
| Creative Labs                                   | 3         | 1.08%   |
| Logitech                                        | 2         | 0.72%   |
| Creative Technology                             | 2         | 0.72%   |
| Corsair                                         | 2         | 0.72%   |
| TC Electronic                                   | 1         | 0.36%   |
| SteelSeries ApS                                 | 1         | 0.36%   |
| Shure                                           | 1         | 0.36%   |
| Razer USA                                       | 1         | 0.36%   |
| PreSonus Audio Electronics                      | 1         | 0.36%   |
| Plantronics                                     | 1         | 0.36%   |
| Native Instruments                              | 1         | 0.36%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.36%   |
| Lenovo                                          | 1         | 0.36%   |
| Harman                                          | 1         | 0.36%   |
| GN Netcom                                       | 1         | 0.36%   |
| Generalplus Technology                          | 1         | 0.36%   |
| Focusrite-Novation                              | 1         | 0.36%   |
| EVGA                                            | 1         | 0.36%   |
| AudioQuest                                      | 1         | 0.36%   |
| ASUSTek Computer                                | 1         | 0.36%   |
| Arylic                                          | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 6.71%   |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 4.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 3.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 3.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 3.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10        | 2.92%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.04%   |
| AMD Navi 10 HDMI Audio                                                     | 7         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.75%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.46%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 1.46%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.46%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5         | 1.46%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.17%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.17%   |
| C-Media Electronics USB Audio Device                                       | 4         | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.87%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.58%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.58%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 23.53%  |
| SK hynix            | 34        | 18.18%  |
| Kingston            | 25        | 13.37%  |
| Corsair             | 15        | 8.02%   |
| Micron Technology   | 12        | 6.42%   |
| G.Skill             | 12        | 6.42%   |
| Unknown             | 8         | 4.28%   |
| Crucial             | 7         | 3.74%   |
| Patriot             | 5         | 2.67%   |
| A-DATA Technology   | 5         | 2.67%   |
| Silicon Power       | 3         | 1.6%    |
| Unknown             | 3         | 1.6%    |
| Unknown (ABCD)      | 2         | 1.07%   |
| Smart               | 2         | 1.07%   |
| Ramaxel Technology  | 2         | 1.07%   |
| Nanya Technology    | 2         | 1.07%   |
| AMD                 | 2         | 1.07%   |
| Transcend           | 1         | 0.53%   |
| Team                | 1         | 0.53%   |
| Smart Brazil        | 1         | 0.53%   |
| ASint Technology    | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 2.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 2.03%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.52%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 1.52%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 3         | 1.52%   |
| Unknown                                                          | 3         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.02%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.02%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.02%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.02%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.02%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.02%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.02%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.02%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.02%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s            | 2         | 1.02%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s             | 2         | 1.02%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s         | 2         | 1.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.02%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 2         | 1.02%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.51%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                          | 1         | 0.51%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.51%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s              | 1         | 0.51%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s              | 1         | 0.51%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.51%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 87        | 56.13%  |
| DDR3    | 52        | 33.55%  |
| LPDDR4  | 4         | 2.58%   |
| LPDDR3  | 4         | 2.58%   |
| SDRAM   | 3         | 1.94%   |
| Unknown | 3         | 1.94%   |
| DDR5    | 1         | 0.65%   |
| DDR2    | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 58.97%  |
| DIMM         | 49        | 31.41%  |
| Row Of Chips | 13        | 8.33%   |
| Chip         | 1         | 0.64%   |
| Unknown      | 1         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 37.57%  |
| 4096  | 62        | 35.84%  |
| 16384 | 23        | 13.29%  |
| 2048  | 15        | 8.67%   |
| 32768 | 6         | 3.47%   |
| 1024  | 2         | 1.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 44        | 26.35%  |
| 3200    | 37        | 22.16%  |
| 2667    | 24        | 14.37%  |
| 2400    | 15        | 8.98%   |
| 1333    | 9         | 5.39%   |
| 3600    | 6         | 3.59%   |
| 2133    | 5         | 2.99%   |
| 1334    | 3         | 1.8%    |
| 4199    | 2         | 1.2%    |
| 3666    | 2         | 1.2%    |
| 3466    | 2         | 1.2%    |
| 3266    | 2         | 1.2%    |
| 2933    | 2         | 1.2%    |
| 4800    | 1         | 0.6%    |
| 4267    | 1         | 0.6%    |
| 4133    | 1         | 0.6%    |
| 3733    | 1         | 0.6%    |
| 3533    | 1         | 0.6%    |
| 3400    | 1         | 0.6%    |
| 2800    | 1         | 0.6%    |
| 2481    | 1         | 0.6%    |
| 2465    | 1         | 0.6%    |
| 1328    | 1         | 0.6%    |
| 1067    | 1         | 0.6%    |
| 1066    | 1         | 0.6%    |
| 800     | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| Ricoh               | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 1         | 25%     |
| Ricoh SP 210SU                | 1         | 25%     |
| HP Officejet Pro L7400        | 1         | 25%     |
| Brother HL-2030 Laser Printer | 1         | 25%     |

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
| Chicony Electronics                    | 24        | 19.67%  |
| IMC Networks                           | 11        | 9.02%   |
| Realtek Semiconductor                  | 10        | 8.2%    |
| Quanta                                 | 10        | 8.2%    |
| Acer                                   | 7         | 5.74%   |
| Suyin                                  | 6         | 4.92%   |
| Microdia                               | 6         | 4.92%   |
| Logitech                               | 6         | 4.92%   |
| Syntek                                 | 5         | 4.1%    |
| Bison Electronics                      | 5         | 4.1%    |
| Alcor Micro                            | 5         | 4.1%    |
| Sunplus Innovation Technology          | 4         | 3.28%   |
| Silicon Motion                         | 4         | 3.28%   |
| Sonix Technology                       | 3         | 2.46%   |
| Luxvisions Innotech Limited            | 3         | 2.46%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.46%   |
| Creative Technology                    | 2         | 1.64%   |
| WaveRider Communications               | 1         | 0.82%   |
| Microsoft                              | 1         | 0.82%   |
| Lite-On Technology                     | 1         | 0.82%   |
| LG Electronics                         | 1         | 0.82%   |
| Lenovo                                 | 1         | 0.82%   |
| KYE Systems (Mouse Systems)            | 1         | 0.82%   |
| GEMBIRD                                | 1         | 0.82%   |
| ARC International                      | 1         | 0.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 7         | 5.74%   |
| Chicony HD WebCam                                   | 6         | 4.92%   |
| Realtek Integrated_Webcam_HD                        | 4         | 3.28%   |
| Chicony Integrated Camera                           | 4         | 3.28%   |
| Syntek EasyCamera                                   | 3         | 2.46%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 2.46%   |
| Quanta HP TrueVision HD Camera                      | 3         | 2.46%   |
| Acer Integrated Camera                              | 3         | 2.46%   |
| Syntek Integrated Camera                            | 2         | 1.64%   |
| Suyin HP Webcam                                     | 2         | 1.64%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 1.64%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 1.64%   |
| Realtek HD WebCam                                   | 2         | 1.64%   |
| Quanta VGA WebCam                                   | 2         | 1.64%   |
| Quanta HP Webcam                                    | 2         | 1.64%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.64%   |
| Microdia Integrated Webcam                          | 2         | 1.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.64%   |
| Logitech Webcam C270                                | 2         | 1.64%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.64%   |
| Chicony USB2.0 Camera                               | 2         | 1.64%   |
| Chicony thinkpad t430s camera                       | 2         | 1.64%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.64%   |
| Bison Integrated Camera                             | 2         | 1.64%   |
| WaveRider USB 2.0 Camera                            | 1         | 0.82%   |
| Suyin USB Webcam                                    | 1         | 0.82%   |
| Suyin NEC HD WebCam                                 | 1         | 0.82%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.82%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.82%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.82%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.82%   |
| Sunplus HD WebCam                                   | 1         | 0.82%   |
| Sunplus Aukey-PC-LM1E Camera                        | 1         | 0.82%   |
| Silicon Motion WebCam SCB-0355N                     | 1         | 0.82%   |
| Silicon Motion WebCam SC-10HDD12636N                | 1         | 0.82%   |
| Realtek Integrated Webcam                           | 1         | 0.82%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.82%   |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 0.82%   |
| Quanta HD Webcam                                    | 1         | 0.82%   |
| Quanta HD User Facing                               | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 5         | 50%     |
| Synaptics                  | 3         | 30%     |
| Validity Sensors           | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 136       | 73.51%  |
| 1     | 44        | 23.78%  |
| 2     | 5         | 2.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 18.52%  |
| Net/wireless             | 7         | 12.96%  |
| Graphics card            | 7         | 12.96%  |
| Multimedia controller    | 6         | 11.11%  |
| Chipcard                 | 5         | 9.26%   |
| Camera                   | 5         | 9.26%   |
| Communication controller | 4         | 7.41%   |
| Bluetooth                | 4         | 7.41%   |
| Storage                  | 2         | 3.7%    |
| Unassigned class         | 1         | 1.85%   |
| Network                  | 1         | 1.85%   |
| Net/ethernet             | 1         | 1.85%   |
| Dvb card                 | 1         | 1.85%   |


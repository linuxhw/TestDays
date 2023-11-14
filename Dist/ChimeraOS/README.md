ChimeraOS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ChimeraOS/Desktop/README.md) and [notebooks](/Dist/ChimeraOS/Notebook/README.md).

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

Total: 135

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B550-A PRO                  | Desktop     | [3333de3c07](https://linux-hardware.org/?probe=3333de3c07) | Nov 06, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [e005a7da3a](https://linux-hardware.org/?probe=e005a7da3a) | Nov 06, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9f47c70860](https://linux-hardware.org/?probe=9f47c70860) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | Desktop     | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e073d8c90a](https://linux-hardware.org/?probe=e073d8c90a) | Nov 03, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [877ab8782b](https://linux-hardware.org/?probe=877ab8782b) | Nov 01, 2023 |
| Dell          | G15 5510                    | Notebook    | [12bd3f99da](https://linux-hardware.org/?probe=12bd3f99da) | Oct 31, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [d7fb2de5a7](https://linux-hardware.org/?probe=d7fb2de5a7) | Oct 30, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a58f65d857](https://linux-hardware.org/?probe=a58f65d857) | Oct 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [480f22e1b7](https://linux-hardware.org/?probe=480f22e1b7) | Oct 24, 2023 |
| Dell          | Precision 7520              | Notebook    | [ab5ec5ba37](https://linux-hardware.org/?probe=ab5ec5ba37) | Oct 22, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6d454c05e2](https://linux-hardware.org/?probe=6d454c05e2) | Oct 21, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6cc2145e11](https://linux-hardware.org/?probe=6cc2145e11) | Oct 21, 2023 |
| GMKtec        | NucBox K4                   | Desktop     | [b0f8dc54f3](https://linux-hardware.org/?probe=b0f8dc54f3) | Oct 20, 2023 |
| AZW           | SER V1                      | Desktop     | [eca53f2271](https://linux-hardware.org/?probe=eca53f2271) | Oct 18, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11820fb443](https://linux-hardware.org/?probe=11820fb443) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [257a13e71a](https://linux-hardware.org/?probe=257a13e71a) | Oct 02, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [48f4eb15cc](https://linux-hardware.org/?probe=48f4eb15cc) | Oct 02, 2023 |
| ASRock        | A320M-HDV                   | Desktop     | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| Alienware     | 17 R2                       | Notebook    | [6ad5704e29](https://linux-hardware.org/?probe=6ad5704e29) | Sep 21, 2023 |
| Alienware     | 17 R2                       | Notebook    | [76bf895d62](https://linux-hardware.org/?probe=76bf895d62) | Sep 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Notebook    | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [27d1633bc3](https://linux-hardware.org/?probe=27d1633bc3) | Sep 11, 2023 |
| HP            | 18E7                        | Desktop     | [1b966d0110](https://linux-hardware.org/?probe=1b966d0110) | Sep 11, 2023 |
| HP            | 89B5 A                      | Desktop     | [4934bfa1a8](https://linux-hardware.org/?probe=4934bfa1a8) | Sep 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Notebook    | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [6192c839f5](https://linux-hardware.org/?probe=6192c839f5) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [3429c55014](https://linux-hardware.org/?probe=3429c55014) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [72fb0f052e](https://linux-hardware.org/?probe=72fb0f052e) | Sep 06, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [f1c877be0e](https://linux-hardware.org/?probe=f1c877be0e) | Sep 05, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9406fe5cf7](https://linux-hardware.org/?probe=9406fe5cf7) | Sep 02, 2023 |
| Gigabyte      | Z490 GAMING X AX y.y        | Desktop     | [94a6d62c4b](https://linux-hardware.org/?probe=94a6d62c4b) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [5afb05e780](https://linux-hardware.org/?probe=5afb05e780) | Aug 27, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [64b9dbafae](https://linux-hardware.org/?probe=64b9dbafae) | Aug 16, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [64aa93e41b](https://linux-hardware.org/?probe=64aa93e41b) | Aug 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| Anbernic      | Win600                      | Notebook    | [32213b8d3b](https://linux-hardware.org/?probe=32213b8d3b) | Aug 13, 2023 |
| Dell          | 05YDCW A01                  | Desktop     | [3f3195be63](https://linux-hardware.org/?probe=3f3195be63) | Aug 12, 2023 |
| Dell          | 05YDCW A01                  | Desktop     | [80c27f0ac1](https://linux-hardware.org/?probe=80c27f0ac1) | Aug 12, 2023 |
| GPD           | P2 MAX                      | Notebook    | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b1b6854522](https://linux-hardware.org/?probe=b1b6854522) | Jul 29, 2023 |
| AZW           | SER V01                     | Mini pc     | [a3b4c40b6e](https://linux-hardware.org/?probe=a3b4c40b6e) | Jul 28, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [f8a02ab68e](https://linux-hardware.org/?probe=f8a02ab68e) | Jul 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8a41127a9](https://linux-hardware.org/?probe=c8a41127a9) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9186fec300](https://linux-hardware.org/?probe=9186fec300) | Jul 23, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [80e44d8594](https://linux-hardware.org/?probe=80e44d8594) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| Acer          | Veriton X6610G              | Desktop     | [e1189e3406](https://linux-hardware.org/?probe=e1189e3406) | Jul 13, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| HP            | 1791                        | Desktop     | [a2bf914a45](https://linux-hardware.org/?probe=a2bf914a45) | Jul 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [13195d7ff3](https://linux-hardware.org/?probe=13195d7ff3) | Jul 02, 2023 |
| HP            | 1998                        | Desktop     | [91f6e54877](https://linux-hardware.org/?probe=91f6e54877) | Jun 30, 2023 |
| AMI           | Unknown                     | Notebook    | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [50efda9604](https://linux-hardware.org/?probe=50efda9604) | Jun 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| Dell          | 07HXY6 A01                  | Desktop     | [ec3adcbe42](https://linux-hardware.org/?probe=ec3adcbe42) | Jun 16, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [c6401638dd](https://linux-hardware.org/?probe=c6401638dd) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [798d8e8914](https://linux-hardware.org/?probe=798d8e8914) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [d7b5162532](https://linux-hardware.org/?probe=d7b5162532) | Jun 09, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [8c6370ac0d](https://linux-hardware.org/?probe=8c6370ac0d) | May 23, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [95fcf79dd4](https://linux-hardware.org/?probe=95fcf79dd4) | May 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [41b69ae4db](https://linux-hardware.org/?probe=41b69ae4db) | May 12, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [bb01d9e92b](https://linux-hardware.org/?probe=bb01d9e92b) | May 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [bf3fee03d2](https://linux-hardware.org/?probe=bf3fee03d2) | May 09, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ad66608cf0](https://linux-hardware.org/?probe=ad66608cf0) | May 08, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [101ec0a833](https://linux-hardware.org/?probe=101ec0a833) | May 05, 2023 |
| AYANEO        | 2                           | Tablet      | [672b480b96](https://linux-hardware.org/?probe=672b480b96) | May 05, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [4ec161ab9b](https://linux-hardware.org/?probe=4ec161ab9b) | May 04, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| AYANEO        | 2                           | Tablet      | [4db5d91519](https://linux-hardware.org/?probe=4db5d91519) | Apr 21, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [a6865b8591](https://linux-hardware.org/?probe=a6865b8591) | Apr 16, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | Notebook    | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [b21cd49226](https://linux-hardware.org/?probe=b21cd49226) | Mar 16, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [9f40b861a5](https://linux-hardware.org/?probe=9f40b861a5) | Mar 12, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [7f8fc2ba96](https://linux-hardware.org/?probe=7f8fc2ba96) | Mar 10, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fa504e81f](https://linux-hardware.org/?probe=8fa504e81f) | Mar 07, 2023 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [4a0feca3f5](https://linux-hardware.org/?probe=4a0feca3f5) | Mar 02, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [01eb743492](https://linux-hardware.org/?probe=01eb743492) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [766790f373](https://linux-hardware.org/?probe=766790f373) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| HP            | 1998                        | Desktop     | [dbb952f3f6](https://linux-hardware.org/?probe=dbb952f3f6) | Feb 13, 2023 |
| HP            | 1998                        | Desktop     | [0171575a1d](https://linux-hardware.org/?probe=0171575a1d) | Feb 13, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [49ca01435b](https://linux-hardware.org/?probe=49ca01435b) | Dec 27, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [d721c7ae17](https://linux-hardware.org/?probe=d721c7ae17) | Dec 27, 2022 |
| Lenovo        | ThinkCentre M70e 0832B1U    | Desktop     | [d95663a632](https://linux-hardware.org/?probe=d95663a632) | Dec 07, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [2a7b6d570f](https://linux-hardware.org/?probe=2a7b6d570f) | Nov 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [58b3db6784](https://linux-hardware.org/?probe=58b3db6784) | Nov 23, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [9bec9e1625](https://linux-hardware.org/?probe=9bec9e1625) | Oct 01, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [501a588f11](https://linux-hardware.org/?probe=501a588f11) | Oct 01, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| ChimeraOS 43-1 | 25        | 23.15%  |
| ChimeraOS 42   | 18        | 16.67%  |
| ChimeraOS 39   | 15        | 13.89%  |
| ChimeraOS 44-1 | 14        | 12.96%  |
| ChimeraOS 41   | 11        | 10.19%  |
| ChimeraOS 43   | 8         | 7.41%   |
| ChimeraOS 38   | 6         | 5.56%   |
| ChimeraOS 44   | 5         | 4.63%   |
| ChimeraOS 37   | 4         | 3.7%    |
| ChimeraOS 35   | 1         | 0.93%   |
| ChimeraOS      | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 106       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.3.9-chimeraos-1       | 32        | 29.36%  |
| 6.1.27-1-lts            | 18        | 16.51%  |
| 6.1.11-arch1-1          | 15        | 13.76%  |
| 6.5.6-chos1-chimeraos-1 | 14        | 12.84%  |
| 6.1.21-1-lts            | 11        | 10.09%  |
| 6.1.1-arch1-1           | 6         | 5.5%    |
| 6.5.3-chos1-chimeraos-1 | 5         | 4.59%   |
| 6.0.8-arch1-1           | 4         | 3.67%   |
| 6.4.9-0-generic         | 1         | 0.92%   |
| 6.3.3-arch1-1           | 1         | 0.92%   |
| 6.3.1-arch2-1           | 1         | 0.92%   |
| 5.19.6-arch1-1          | 1         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.9   | 32        | 29.36%  |
| 6.1.27  | 18        | 16.51%  |
| 6.1.11  | 15        | 13.76%  |
| 6.5.6   | 14        | 12.84%  |
| 6.1.21  | 11        | 10.09%  |
| 6.1.1   | 6         | 5.5%    |
| 6.5.3   | 5         | 4.59%   |
| 6.0.8   | 4         | 3.67%   |
| 6.4.9   | 1         | 0.92%   |
| 6.3.3   | 1         | 0.92%   |
| 6.3.1   | 1         | 0.92%   |
| 5.19.6  | 1         | 0.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 49        | 45.79%  |
| 6.3     | 33        | 30.84%  |
| 6.5     | 19        | 17.76%  |
| 6.0     | 4         | 3.74%   |
| 6.4     | 1         | 0.93%   |
| 5.19    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 106       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 105       | 99.06%  |
| steamos | 1         | 0.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 100       | 94.34%  |
| X11     | 6         | 5.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 106       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 90        | 84.91%  |
| pt_BR | 4         | 3.77%   |
| es_ES | 4         | 3.77%   |
| it_IT | 2         | 1.89%   |
| fr_FR | 2         | 1.89%   |
| de_DE | 2         | 1.89%   |
| ja_JP | 1         | 0.94%   |
| C     | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 106       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 105       | 99.06%  |
| Ext4  | 1         | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 106       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 22        | 20.75%  |
| Gigabyte Technology    | 19        | 17.92%  |
| Dell                   | 12        | 11.32%  |
| Hewlett-Packard        | 8         | 7.55%   |
| Acer                   | 8         | 7.55%   |
| Lenovo                 | 7         | 6.6%    |
| MSI                    | 6         | 5.66%   |
| ASRock                 | 4         | 3.77%   |
| Razer                  | 2         | 1.89%   |
| ONE-NETBOOK TECHNOLOGY | 2         | 1.89%   |
| ONE-NETBOOK            | 2         | 1.89%   |
| AZW                    | 2         | 1.89%   |
| AYANEO                 | 2         | 1.89%   |
| Microsoft              | 1         | 0.94%   |
| Micro Electronics      | 1         | 0.94%   |
| MACHINIST              | 1         | 0.94%   |
| Intel                  | 1         | 0.94%   |
| GPD                    | 1         | 0.94%   |
| Google                 | 1         | 0.94%   |
| GMKtec                 | 1         | 0.94%   |
| Anbernic               | 1         | 0.94%   |
| AMI                    | 1         | 0.94%   |
| Alienware              | 1         | 0.94%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Gigabyte B550I AORUS PRO AX                 | 3         | 2.83%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER          | 2         | 1.89%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 1.89%   |
| HP EliteDesk 800 G1 SFF                     | 2         | 1.89%   |
| AZW SER                                     | 2         | 1.89%   |
| AYANEO 2                                    | 2         | 1.89%   |
| ASUS ROG STRIX B550-F GAMING                | 2         | 1.89%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 0.94%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 0.94%   |
| MSI MS-7D73                                 | 1         | 0.94%   |
| MSI MS-7C91                                 | 1         | 0.94%   |
| MSI MS-7C56                                 | 1         | 0.94%   |
| MSI MS-7B86                                 | 1         | 0.94%   |
| MSI GE75 Raider 10SF                        | 1         | 0.94%   |
| MSI CX62 6QD                                | 1         | 0.94%   |
| Microsoft Surface Book                      | 1         | 0.94%   |
| Micro MG-VCP17I-3070                        | 1         | 0.94%   |
| MACHINIST X99-RS9 V2.0                      | 1         | 0.94%   |
| Lenovo Y50-70 20378                         | 1         | 0.94%   |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 0.94%   |
| Lenovo ThinkCentre M70e 0832B1U             | 1         | 0.94%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 0.94%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 0.94%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 0.94%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 0.94%   |
| Intel DB75EN AAG39650-400                   | 1         | 0.94%   |
| HP Z220 SFF Workstation                     | 1         | 0.94%   |
| HP Victus by Laptop 16-d1xxx                | 1         | 0.94%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx   | 1         | 0.94%   |
| HP ProDesk 600 G1 SFF                       | 1         | 0.94%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 0.94%   |
| HP 250 G4 Notebook PC                       | 1         | 0.94%   |
| GPD P2 MAX                                  | 1         | 0.94%   |
| Google Snappy                               | 1         | 0.94%   |
| GMKtec NucBox K4                            | 1         | 0.94%   |
| Gigabyte Z97X-Gaming 5                      | 1         | 0.94%   |
| Gigabyte Z490 GAMING X AX                   | 1         | 0.94%   |
| Gigabyte X570S AORUS ELITE AX               | 1         | 0.94%   |
| Gigabyte X570 I AORUS PRO WIFI              | 1         | 0.94%   |
| Gigabyte X570 AORUS ELITE WIFI              | 1         | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell OptiPlex              | 6         | 5.66%   |
| ASUS ROG                   | 6         | 5.66%   |
| Acer Aspire                | 5         | 4.72%   |
| Lenovo IdeaPad             | 3         | 2.83%   |
| Gigabyte B550I             | 3         | 2.83%   |
| Razer Blade                | 2         | 1.89%   |
| ONE-NETBOOK TECHNOLOGY ONE | 2         | 1.89%   |
| ONE-NETBOOK ONEXPLAYER     | 2         | 1.89%   |
| HP Victus                  | 2         | 1.89%   |
| HP EliteDesk               | 2         | 1.89%   |
| Gigabyte X570              | 2         | 1.89%   |
| Gigabyte B450              | 2         | 1.89%   |
| Dell Precision             | 2         | 1.89%   |
| Dell Inspiron              | 2         | 1.89%   |
| AZW SER                    | 2         | 1.89%   |
| AYANEO 2                   | 2         | 1.89%   |
| ASUS TUF                   | 2         | 1.89%   |
| ASUS PRIME                 | 2         | 1.89%   |
| Acer Nitro                 | 2         | 1.89%   |
| MSI MS-7D73                | 1         | 0.94%   |
| MSI MS-7C91                | 1         | 0.94%   |
| MSI MS-7C56                | 1         | 0.94%   |
| MSI MS-7B86                | 1         | 0.94%   |
| MSI GE75                   | 1         | 0.94%   |
| MSI CX62                   | 1         | 0.94%   |
| Microsoft Surface          | 1         | 0.94%   |
| Micro MG-VCP17I-3070       | 1         | 0.94%   |
| MACHINIST X99-RS9          | 1         | 0.94%   |
| Lenovo Y50-70              | 1         | 0.94%   |
| Lenovo ThinkPad            | 1         | 0.94%   |
| Lenovo ThinkCentre         | 1         | 0.94%   |
| Lenovo Legion              | 1         | 0.94%   |
| Intel DB75EN               | 1         | 0.94%   |
| HP Z220                    | 1         | 0.94%   |
| HP ProDesk                 | 1         | 0.94%   |
| HP EliteBook               | 1         | 0.94%   |
| HP 250                     | 1         | 0.94%   |
| GPD P2                     | 1         | 0.94%   |
| Google Snappy              | 1         | 0.94%   |
| GMKtec NucBox              | 1         | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 17        | 16.04%  |
| 2020 | 16        | 15.09%  |
| 2022 | 11        | 10.38%  |
| 2018 | 9         | 8.49%   |
| 2017 | 9         | 8.49%   |
| 2019 | 8         | 7.55%   |
| 2023 | 7         | 6.6%    |
| 2015 | 7         | 6.6%    |
| 2012 | 7         | 6.6%    |
| 2016 | 6         | 5.66%   |
| 2013 | 4         | 3.77%   |
| 2014 | 3         | 2.83%   |
| 2011 | 1         | 0.94%   |
| 2010 | 1         | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 57        | 53.77%  |
| Notebook    | 40        | 37.74%  |
| Tablet      | 5         | 4.72%   |
| Mini pc     | 2         | 1.89%   |
| Convertible | 1         | 0.94%   |
| All in one  | 1         | 0.94%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 106       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 105       | 99.06%  |
| Yes  | 1         | 0.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 29        | 27.36%  |
| 16.01-24.0  | 28        | 26.42%  |
| 8.01-16.0   | 16        | 15.09%  |
| 4.01-8.0    | 15        | 14.15%  |
| 24.01-32.0  | 9         | 8.49%   |
| 3.01-4.0    | 5         | 4.72%   |
| 64.01-256.0 | 4         | 3.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 45        | 41.67%  |
| 1.01-2.0   | 27        | 25%     |
| 3.01-4.0   | 19        | 17.59%  |
| 4.01-8.0   | 16        | 14.81%  |
| 16.01-24.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 48.15%  |
| 2      | 34        | 31.48%  |
| 3      | 15        | 13.89%  |
| 5      | 2         | 1.85%   |
| 4      | 2         | 1.85%   |
| 8      | 1         | 0.93%   |
| 7      | 1         | 0.93%   |
| 6      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 86.79%  |
| Yes       | 14        | 13.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 87.74%  |
| No        | 13        | 12.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 78.3%   |
| No        | 23        | 21.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 72.64%  |
| No        | 29        | 27.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 44        | 41.51%  |
| Germany      | 8         | 7.55%   |
| Brazil       | 7         | 6.6%    |
| Spain        | 4         | 3.77%   |
| Australia    | 4         | 3.77%   |
| Vietnam      | 3         | 2.83%   |
| UK           | 3         | 2.83%   |
| Russia       | 3         | 2.83%   |
| Italy        | 3         | 2.83%   |
| France       | 3         | 2.83%   |
| Saudi Arabia | 2         | 1.89%   |
| Poland       | 2         | 1.89%   |
| Japan        | 2         | 1.89%   |
| Hungary      | 2         | 1.89%   |
| Canada       | 2         | 1.89%   |
| Turkey       | 1         | 0.94%   |
| Switzerland  | 1         | 0.94%   |
| Romania      | 1         | 0.94%   |
| Norway       | 1         | 0.94%   |
| New Zealand  | 1         | 0.94%   |
| Netherlands  | 1         | 0.94%   |
| Malaysia     | 1         | 0.94%   |
| Macao        | 1         | 0.94%   |
| Iceland      | 1         | 0.94%   |
| Honduras     | 1         | 0.94%   |
| Finland      | 1         | 0.94%   |
| Estonia      | 1         | 0.94%   |
| Costa Rica   | 1         | 0.94%   |
| Belgium      | 1         | 0.94%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Sanford                  | 2         | 1.87%   |
| Melbourne                | 2         | 1.87%   |
| Las Vegas                | 2         | 1.87%   |
| Chattanooga              | 2         | 1.87%   |
| Yekaterinburg            | 1         | 0.93%   |
| Yaroslavl                | 1         | 0.93%   |
| Wroclaw                  | 1         | 0.93%   |
| Wiesbaden                | 1         | 0.93%   |
| Watsonville              | 1         | 0.93%   |
| Warsaw                   | 1         | 0.93%   |
| Vũng Tàu               | 1         | 0.93%   |
| Virginia Beach           | 1         | 0.93%   |
| Vila-seca                | 1         | 0.93%   |
| Valence                  | 1         | 0.93%   |
| Umeda                    | 1         | 0.93%   |
| Tulcea                   | 1         | 0.93%   |
| Toronto                  | 1         | 0.93%   |
| Tegucigalpa              | 1         | 0.93%   |
| Tampa                    | 1         | 0.93%   |
| Tallinn                  | 1         | 0.93%   |
| Sydney                   | 1         | 0.93%   |
| Sumaré                  | 1         | 0.93%   |
| Steyning                 | 1         | 0.93%   |
| St Louis                 | 1         | 0.93%   |
| Springfield              | 1         | 0.93%   |
| Shelbyville              | 1         | 0.93%   |
| Seattle                  | 1         | 0.93%   |
| Sao Paulo                | 1         | 0.93%   |
| Santa Cruz das Palmeiras | 1         | 0.93%   |
| San José                | 1         | 0.93%   |
| Samara                   | 1         | 0.93%   |
| Saltillo                 | 1         | 0.93%   |
| Round Rock               | 1         | 0.93%   |
| Rockford                 | 1         | 0.93%   |
| Ridley Park              | 1         | 0.93%   |
| Reykjavik                | 1         | 0.93%   |
| Racine                   | 1         | 0.93%   |
| Pittsburg                | 1         | 0.93%   |
| Phoenix                  | 1         | 0.93%   |
| Philadelphia             | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 23        | 28     | 12.92%  |
| Samsung Electronics          | 22        | 33     | 12.36%  |
| WDC                          | 17        | 23     | 9.55%   |
| Kingston                     | 14        | 14     | 7.87%   |
| Sandisk                      | 11        | 16     | 6.18%   |
| Micron/Crucial Technology    | 10        | 11     | 5.62%   |
| Micron Technology            | 8         | 10     | 4.49%   |
| Unknown                      | 6         | 6      | 3.37%   |
| Toshiba                      | 6         | 7      | 3.37%   |
| SK hynix                     | 6         | 6      | 3.37%   |
| Crucial                      | 6         | 8      | 3.37%   |
| Phison Electronics           | 5         | 5      | 2.81%   |
| Intel                        | 5         | 6      | 2.81%   |
| Kingston Technology Company  | 4         | 4      | 2.25%   |
| Silicon Motion               | 3         | 3      | 1.69%   |
| KIOXIA                       | 3         | 3      | 1.69%   |
| Shenzhen Longsys Electronics | 2         | 2      | 1.12%   |
| Realtek Semiconductor        | 2         | 2      | 1.12%   |
| Hitachi                      | 2         | 2      | 1.12%   |
| Fanxiang                     | 2         | 2      | 1.12%   |
| China                        | 2         | 2      | 1.12%   |
| ADATA Technology             | 2         | 3      | 1.12%   |
| WDC PC S                     | 1         | 1      | 0.56%   |
| SSSTC                        | 1         | 1      | 0.56%   |
| PNY                          | 1         | 1      | 0.56%   |
| O2 Micro                     | 1         | 1      | 0.56%   |
| NT-1TB                       | 1         | 1      | 0.56%   |
| Netac                        | 1         | 1      | 0.56%   |
| KingFast                     | 1         | 1      | 0.56%   |
| KingDian                     | 1         | 3      | 0.56%   |
| JMicron Technology           | 1         | 1      | 0.56%   |
| HGST                         | 1         | 1      | 0.56%   |
| Hewlett-Packard              | 1         | 1      | 0.56%   |
| Corsair                      | 1         | 1      | 0.56%   |
| Biwin Storage Technology     | 1         | 1      | 0.56%   |
| ASMedia                      | 1         | 1      | 0.56%   |
| AMD                          | 1         | 1      | 0.56%   |
| A-DATA Technology            | 1         | 1      | 0.56%   |
| Unknown                      | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 10        | 5.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                 | 8         | 4.17%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 5         | 2.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                | 4         | 2.08%   |
| Kingston SA400S37120G 120GB SSD                                   | 3         | 1.56%   |
| Unknown MMC Card  64GB                                            | 2         | 1.04%   |
| SK hynix HFM512GD3JX016N 512GB                                    | 2         | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 2         | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 2         | 1.04%   |
| Samsung SSD 870 QVO 2TB                                           | 2         | 1.04%   |
| Samsung SSD 860 EVO 1TB                                           | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB               | 2         | 1.04%   |
| Phison PS5013 E13 NVMe Controller 256GB                           | 2         | 1.04%   |
| Phison E12 NVMe Controller 1TB                                    | 2         | 1.04%   |
| Micron 1100 SATA 256GB SSD                                        | 2         | 1.04%   |
| Kingston Company SNV2S1000G 1TB                                   | 2         | 1.04%   |
| Kingston SNVS500G 500GB                                           | 2         | 1.04%   |
| Kingston SA400S37480G 480GB SSD                                   | 2         | 1.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 2         | 1.04%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                                  | 1         | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 1         | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                  | 1         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                  | 1         | 0.52%   |
| WDC WDBNCE5000PNC 500GB SSD                                       | 1         | 0.52%   |
| WDC WDBNCE0010PNC 1TB SSD                                         | 1         | 0.52%   |
| WDC WD7500BPVT-80HXZT3 752GB                                      | 1         | 0.52%   |
| WDC WD5000BEVT-22A0RT0 500GB                                      | 1         | 0.52%   |
| WDC WD5000AVDS-63U7B1 500GB                                       | 1         | 0.52%   |
| WDC WD40EZRX-00SPEB0 4TB                                          | 1         | 0.52%   |
| WDC WD20SPZX-08UA7 2TB                                            | 1         | 0.52%   |
| WDC WD20EARX-00PASB0 2TB                                          | 1         | 0.52%   |
| WDC WD201KFGX-68BKJN0 20TB                                        | 1         | 0.52%   |
| WDC WD1500HLFS-01G6U0 150GB                                       | 1         | 0.52%   |
| WDC WD10SPZX-80Z10T2 1TB                                          | 1         | 0.52%   |
| WDC WD10SPZX-24Z10 1TB                                            | 1         | 0.52%   |
| WDC WD10SPCX-24HWST1 1TB                                          | 1         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                                          | 1         | 0.52%   |
| WDC WD10JPLX-00MBPT0 1TB                                          | 1         | 0.52%   |
| WDC WD10EZEX-60M2NA0 1TB                                          | 1         | 0.52%   |
| WDC PC S N530 SDBPNPZ 256GB                                       | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 26     | 48.89%  |
| WDC                 | 14        | 16     | 31.11%  |
| Toshiba             | 4         | 5      | 8.89%   |
| Hitachi             | 2         | 2      | 4.44%   |
| Unknown             | 1         | 1      | 2.22%   |
| Samsung Electronics | 1         | 1      | 2.22%   |
| HGST                | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 13     | 15.79%  |
| Kingston            | 9         | 9      | 15.79%  |
| SanDisk             | 6         | 8      | 10.53%  |
| Micron Technology   | 6         | 8      | 10.53%  |
| Crucial             | 6         | 8      | 10.53%  |
| WDC                 | 5         | 7      | 8.77%   |
| Fanxiang            | 2         | 2      | 3.51%   |
| China               | 2         | 2      | 3.51%   |
| SSSTC               | 1         | 1      | 1.75%   |
| Seagate             | 1         | 1      | 1.75%   |
| PNY                 | 1         | 1      | 1.75%   |
| NT-1TB              | 1         | 1      | 1.75%   |
| Netac               | 1         | 1      | 1.75%   |
| KingDian            | 1         | 3      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 1.75%   |
| Corsair             | 1         | 1      | 1.75%   |
| ASMedia             | 1         | 1      | 1.75%   |
| AMD                 | 1         | 1      | 1.75%   |
| A-DATA Technology   | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 67        | 83     | 42.68%  |
| SSD     | 45        | 71     | 28.66%  |
| HDD     | 36        | 52     | 22.93%  |
| Unknown | 5         | 5      | 3.18%   |
| MMC     | 4         | 4      | 2.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 67        | 83     | 45.89%  |
| SATA | 67        | 119    | 45.89%  |
| SAS  | 8         | 9      | 5.48%   |
| MMC  | 4         | 4      | 2.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 65     | 42.53%  |
| 0.51-1.0   | 30        | 33     | 34.48%  |
| 1.01-2.0   | 11        | 13     | 12.64%  |
| 2.01-3.0   | 3         | 3      | 3.45%   |
| 3.01-4.0   | 2         | 5      | 2.3%    |
| 10.01-20.0 | 2         | 2      | 2.3%    |
| 4.01-10.0  | 2         | 2      | 2.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 45        | 42.06%  |
| 1001-2000      | 32        | 29.91%  |
| 501-1000       | 14        | 13.08%  |
| 251-500        | 10        | 9.35%   |
| 2001-3000      | 4         | 3.74%   |
| 101-250        | 2         | 1.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 32        | 29.63%  |
| 51-100         | 17        | 15.74%  |
| 101-250        | 16        | 14.81%  |
| 501-1000       | 15        | 13.89%  |
| 251-500        | 9         | 8.33%   |
| 1001-2000      | 8         | 7.41%   |
| More than 3000 | 5         | 4.63%   |
| 2001-3000      | 5         | 4.63%   |
| 1-20           | 1         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 106       | 215    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 57        | 34.97%  |
| AMD                          | 33        | 20.25%  |
| Samsung Electronics          | 15        | 9.2%    |
| Micron/Crucial Technology    | 10        | 6.13%   |
| Kingston Technology Company  | 9         | 5.52%   |
| SK hynix                     | 6         | 3.68%   |
| SanDisk                      | 6         | 3.68%   |
| Phison Electronics           | 5         | 3.07%   |
| Silicon Motion               | 3         | 1.84%   |
| KIOXIA                       | 3         | 1.84%   |
| Toshiba America Info Systems | 2         | 1.23%   |
| Shenzhen Longsys Electronics | 2         | 1.23%   |
| Realtek Semiconductor        | 2         | 1.23%   |
| Micron Technology            | 2         | 1.23%   |
| Biwin Storage Technology     | 2         | 1.23%   |
| ADATA Technology             | 2         | 1.23%   |
| O2 Micro                     | 1         | 0.61%   |
| Marvell Technology Group     | 1         | 0.61%   |
| INNOGRIT                     | 1         | 0.61%   |
| ASMedia Technology           | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 11.05%  |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 6.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 5.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 4.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 3.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 3.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 2.76%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 2.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 2.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.21%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.21%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.66%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 3         | 1.66%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.66%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.1%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 1.1%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 1.1%    |
| Phison E12 NVMe Controller                                                     | 2         | 1.1%    |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 2         | 1.1%    |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.1%    |
| Biwin Storage Non-Volatile memory controller                                   | 2         | 1.1%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.55%   |
| Toshiba America Info Systems XG3 NVMe SSD Controller                           | 1         | 0.55%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.55%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.55%   |
| Silicon Motion SM2260 NVMe SSD Controller                                      | 1         | 0.55%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 0.55%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1         | 0.55%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.55%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 73        | 45.91%  |
| NVMe | 67        | 42.14%  |
| RAID | 15        | 9.43%   |
| IDE  | 4         | 2.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 62        | 58.49%  |
| AMD    | 44        | 41.51%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor            | 5         | 4.67%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 4         | 3.74%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 3         | 2.8%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 2.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 2.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.87%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2         | 1.87%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 1.87%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 2         | 1.87%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 1.87%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.87%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 1.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.87%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1         | 0.93%   |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz           | 1         | 0.93%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.93%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.93%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.93%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.93%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.93%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.93%   |
| Intel Core i5-9500T CPU @ 2.20GHz             | 1         | 0.93%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 1         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.93%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 0.93%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1         | 0.93%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 24        | 22.43%  |
| Intel Core i7     | 18        | 16.82%  |
| AMD Ryzen 5       | 17        | 15.89%  |
| AMD Ryzen 7       | 16        | 14.95%  |
| Other             | 9         | 8.41%   |
| AMD Ryzen 9       | 9         | 8.41%   |
| Intel Core i3     | 4         | 3.74%   |
| Intel Xeon        | 2         | 1.87%   |
| Intel Celeron     | 2         | 1.87%   |
| Intel Core m3     | 1         | 0.93%   |
| Intel Core 2 Quad | 1         | 0.93%   |
| Intel Atom        | 1         | 0.93%   |
| AMD Ryzen 5 PRO   | 1         | 0.93%   |
| AMD Athlon        | 1         | 0.93%   |
| AMD A10           | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 41        | 38.32%  |
| 6      | 24        | 22.43%  |
| 8      | 21        | 19.63%  |
| 2      | 12        | 11.21%  |
| 16     | 3         | 2.8%    |
| 12     | 3         | 2.8%    |
| 24     | 1         | 0.93%   |
| 14     | 1         | 0.93%   |
| 10     | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 106       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 83        | 78.3%   |
| 1      | 23        | 21.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 106       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Zen 3       | 18        | 16.98%  |
| KabyLake    | 17        | 16.04%  |
| Unknown     | 17        | 16.04%  |
| Haswell     | 10        | 9.43%   |
| CometLake   | 8         | 7.55%   |
| Skylake     | 7         | 6.6%    |
| Zen+        | 6         | 5.66%   |
| Zen 2       | 5         | 4.72%   |
| Zen         | 4         | 3.77%   |
| IvyBridge   | 4         | 3.77%   |
| SandyBridge | 3         | 2.83%   |
| TigerLake   | 2         | 1.89%   |
| Silvermont  | 1         | 0.94%   |
| Piledriver  | 1         | 0.94%   |
| Penryn      | 1         | 0.94%   |
| Goldmont    | 1         | 0.94%   |
| Broadwell   | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 51        | 37.5%   |
| AMD    | 45        | 33.09%  |
| Intel  | 40        | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 3.65%   |
| AMD Rembrandt [Radeon 680M]                                                 | 5         | 3.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 3.65%   |
| Intel HD Graphics 630                                                       | 4         | 2.92%   |
| Intel HD Graphics 530                                                       | 4         | 2.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 2.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 2.19%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 3         | 2.19%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 3         | 2.19%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3         | 2.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 2.19%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 2.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.46%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 1.46%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1.46%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 1.46%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2         | 1.46%   |
| Intel UHD Graphics 620                                                      | 2         | 1.46%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.46%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.46%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.46%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2         | 1.46%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2         | 1.46%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2         | 1.46%   |
| AMD Lucienne                                                                | 2         | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.73%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1         | 0.73%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 0.73%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.73%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.73%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.73%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                    | 1         | 0.73%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1         | 0.73%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 0.73%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                       | 1         | 0.73%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.73%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 37        | 34.58%  |
| 1 x Nvidia     | 28        | 26.17%  |
| Intel + Nvidia | 18        | 16.82%  |
| 1 x Intel      | 15        | 14.02%  |
| AMD + Nvidia   | 5         | 4.67%   |
| Intel + AMD    | 3         | 2.8%    |
| Other          | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 61        | 57.55%  |
| Proprietary | 36        | 33.96%  |
| Unknown     | 9         | 8.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 97.17%  |
| 3.01-4.0   | 2         | 1.89%   |
| 8.01-16.0  | 1         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 14        | 14.74%  |
| BOE                  | 11        | 11.58%  |
| Chimei Innolux       | 8         | 8.42%   |
| AU Optronics         | 7         | 7.37%   |
| LG Display           | 6         | 6.32%   |
| Sharp                | 3         | 3.16%   |
| Philips              | 3         | 3.16%   |
| MSI                  | 3         | 3.16%   |
| Insignia             | 3         | 3.16%   |
| Goldstar             | 3         | 3.16%   |
| BenQ                 | 3         | 3.16%   |
| Vizio                | 2         | 2.11%   |
| Unknown (XXX)        | 2         | 2.11%   |
| Toshiba              | 2         | 2.11%   |
| Sony                 | 2         | 2.11%   |
| Hewlett-Packard      | 2         | 2.11%   |
| ASUSTek Computer     | 2         | 2.11%   |
| TMX                  | 1         | 1.05%   |
| SANYO                | 1         | 1.05%   |
| RTK                  | 1         | 1.05%   |
| PXO                  | 1         | 1.05%   |
| PANDA                | 1         | 1.05%   |
| Panasonic            | 1         | 1.05%   |
| Onkyo                | 1         | 1.05%   |
| HJW                  | 1         | 1.05%   |
| Hitachi              | 1         | 1.05%   |
| Gigabyte Technology  | 1         | 1.05%   |
| GameMax              | 1         | 1.05%   |
| Fujitsu Siemens      | 1         | 1.05%   |
| DENON                | 1         | 1.05%   |
| Dell                 | 1         | 1.05%   |
| AYANEO               | 1         | 1.05%   |
| AYA                  | 1         | 1.05%   |
| Ancor Communications | 1         | 1.05%   |
| AGO                  | 1         | 1.05%   |
| Acer                 | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 2         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 2.08%   |
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                   | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.08%   |
| Vizio E550i-B2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 1         | 1.04%   |
| Vizio D32f-G1 VIZ1027 1920x1080 698x392mm 31.5-inch                     | 1         | 1.04%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 1.04%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1         | 1.04%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                       | 1         | 1.04%   |
| Toshiba TSB-TV TSB0206 1360x768 930x520mm 41.9-inch                     | 1         | 1.04%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                 | 1         | 1.04%   |
| Sony TV SNYEE01 1920x1080                                               | 1         | 1.04%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                           | 1         | 1.04%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch                 | 1         | 1.04%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1         | 1.04%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                       | 1         | 1.04%   |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                          | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch    | 1         | 1.04%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch     | 1         | 1.04%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch       | 1         | 1.04%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch       | 1         | 1.04%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch       | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                       | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM020B 1920x540                        | 1         | 1.04%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 1.04%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 697x392mm 31.5-inch       | 1         | 1.04%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.04%   |
| RTK FHD HDR RTK2A3B 1920x1080 344x195mm 15.6-inch                       | 1         | 1.04%   |
| PXO Pixio PX248P PXO0279 1920x1080 698x393mm 31.5-inch                  | 1         | 1.04%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1         | 1.04%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch               | 1         | 1.04%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch                | 1         | 1.04%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.04%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch             | 1         | 1.04%   |
| Onkyo AV Receiver ONK1150 3840x2160 1872x1053mm 84.6-inch               | 1         | 1.04%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                      | 1         | 1.04%   |
| MSI MAG301CR2 MSI3CB4 2560x1080 690x291mm 29.5-inch                     | 1         | 1.04%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                          | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 53.26%  |
| 3840x2160 (4K)     | 11        | 11.96%  |
| 2560x1440 (QHD)    | 9         | 9.78%   |
| 1366x768 (WXGA)    | 6         | 6.52%   |
| 1200x1920          | 3         | 3.26%   |
| 1920x540           | 2         | 2.17%   |
| 1600x2560          | 2         | 2.17%   |
| 800x1280           | 1         | 1.09%   |
| 3840x1600          | 1         | 1.09%   |
| 3840x1080          | 1         | 1.09%   |
| 3440x1440          | 1         | 1.09%   |
| 2560x1080          | 1         | 1.09%   |
| 1920x1200 (WUXGA)  | 1         | 1.09%   |
| 1680x1050 (WSXGA+) | 1         | 1.09%   |
| 1600x900 (HD+)     | 1         | 1.09%   |
| 1280x960           | 1         | 1.09%   |
| 1280x768           | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 23.96%  |
| 27      | 8         | 8.33%   |
| Unknown | 6         | 6.25%   |
| 84      | 5         | 5.21%   |
| 31      | 5         | 5.21%   |
| 24      | 5         | 5.21%   |
| 17      | 5         | 5.21%   |
| 23      | 4         | 4.17%   |
| 72      | 3         | 3.13%   |
| 54      | 3         | 3.13%   |
| 14      | 3         | 3.13%   |
| 49      | 2         | 2.08%   |
| 48      | 2         | 2.08%   |
| 40      | 2         | 2.08%   |
| 34      | 2         | 2.08%   |
| 8       | 2         | 2.08%   |
| 74      | 1         | 1.04%   |
| 57      | 1         | 1.04%   |
| 52      | 1         | 1.04%   |
| 47      | 1         | 1.04%   |
| 46      | 1         | 1.04%   |
| 38      | 1         | 1.04%   |
| 37      | 1         | 1.04%   |
| 29      | 1         | 1.04%   |
| 26      | 1         | 1.04%   |
| 22      | 1         | 1.04%   |
| 21      | 1         | 1.04%   |
| 20      | 1         | 1.04%   |
| 18      | 1         | 1.04%   |
| 16      | 1         | 1.04%   |
| 12      | 1         | 1.04%   |
| 11      | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 27.37%  |
| 501-600     | 15        | 15.79%  |
| 1001-1500   | 10        | 10.53%  |
| 601-700     | 9         | 9.47%   |
| 1501-2000   | 8         | 8.42%   |
| 351-400     | 6         | 6.32%   |
| Unknown     | 6         | 6.32%   |
| 801-900     | 4         | 4.21%   |
| 401-500     | 4         | 4.21%   |
| 701-800     | 3         | 3.16%   |
| 201-300     | 2         | 2.11%   |
| 101-200     | 2         | 2.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 73        | 80.22%  |
| 0.62  | 6         | 6.59%   |
| 16/10 | 4         | 4.4%    |
| 21/9  | 3         | 3.3%    |
| 32/9  | 2         | 2.2%    |
| 4/3   | 1         | 1.1%    |
| 1.96  | 1         | 1.1%    |
| 0.56  | 1         | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 25.81%  |
| More than 1000 | 14        | 15.05%  |
| 301-350        | 10        | 10.75%  |
| 201-250        | 10        | 10.75%  |
| 501-1000       | 9         | 9.68%   |
| 351-500        | 6         | 6.45%   |
| Unknown        | 6         | 6.45%   |
| 121-130        | 5         | 5.38%   |
| 81-90          | 3         | 3.23%   |
| 1-40           | 2         | 2.15%   |
| 71-80          | 1         | 1.08%   |
| 51-60          | 1         | 1.08%   |
| 151-200        | 1         | 1.08%   |
| 141-150        | 1         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 33        | 35.48%  |
| 121-160       | 27        | 29.03%  |
| 1-50          | 11        | 11.83%  |
| 101-120       | 8         | 8.6%    |
| Unknown       | 6         | 6.45%   |
| 161-240       | 5         | 5.38%   |
| More than 240 | 3         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 85        | 79.44%  |
| 0     | 12        | 11.21%  |
| 2     | 10        | 9.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 66        | 39.29%  |
| Intel                           | 55        | 32.74%  |
| Qualcomm Atheros                | 15        | 8.93%   |
| MediaTek                        | 12        | 7.14%   |
| Microsoft                       | 4         | 2.38%   |
| Broadcom                        | 4         | 2.38%   |
| TP-Link                         | 3         | 1.79%   |
| Marvell Technology Group        | 2         | 1.19%   |
| Ralink Technology               | 1         | 0.6%    |
| Ralink                          | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| OnePlus Technology (Shenzhen)   | 1         | 0.6%    |
| Edimax Technology               | 1         | 0.6%    |
| Broadcom Limited                | 1         | 0.6%    |
| ASIX Electronics                | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 22.92%  |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 6.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 4.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 7         | 3.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 3.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 2.6%    |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.6%    |
| Intel I211 Gigabit Network Connection                             | 5         | 2.6%    |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.08%   |
| Intel Wireless 3165                                               | 4         | 2.08%   |
| Intel Ethernet Controller I225-V                                  | 4         | 2.08%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.56%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 3         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.56%   |
| Intel Wireless 7265                                               | 3         | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.56%   |
| Realtek PCIe GbE Family Controller                                | 2         | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.04%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.04%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.04%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.52%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.52%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.52%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.52%   |
| Realtek Realtek WLAN controller                                   | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 45.05%  |
| MediaTek                        | 12        | 13.19%  |
| Realtek Semiconductor           | 11        | 12.09%  |
| Qualcomm Atheros                | 11        | 12.09%  |
| Microsoft                       | 4         | 4.4%    |
| TP-Link                         | 3         | 3.3%    |
| Broadcom                        | 3         | 3.3%    |
| Ralink Technology               | 1         | 1.1%    |
| Ralink                          | 1         | 1.1%    |
| Qualcomm Atheros Communications | 1         | 1.1%    |
| Marvell Technology Group        | 1         | 1.1%    |
| Edimax Technology               | 1         | 1.1%    |
| Broadcom Limited                | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 8         | 8.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 7         | 7.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 6         | 6.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 5         | 5.26%   |
| Intel Wi-Fi 6 AX200                                                                  | 5         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 4         | 4.21%   |
| Intel Wireless 3165                                                                  | 4         | 4.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 4         | 4.21%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4         | 4.21%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 3         | 3.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3         | 3.16%   |
| Intel Wireless 7265                                                                  | 3         | 3.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 3         | 3.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 3         | 3.16%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 2.11%   |
| Intel Wireless 8265 / 8275                                                           | 2         | 2.11%   |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 2.11%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 1.05%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 1.05%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1         | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                             | 1         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 1.05%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1         | 1.05%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 1.05%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 1.05%   |
| Realtek Realtek WLAN controller                                                      | 1         | 1.05%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 1.05%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 1.05%   |
| Microsoft Wireless XBox Controller Dongle                                            | 1         | 1.05%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                    | 1         | 1.05%   |
| Intel Wireless-AC 9260                                                               | 1         | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 1         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                     | 1         | 1.05%   |
| Edimax Wi-Fi                                                                         | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 62        | 65.26%  |
| Intel                    | 25        | 26.32%  |
| Qualcomm Atheros         | 5         | 5.26%   |
| Marvell Technology Group | 1         | 1.05%   |
| Broadcom                 | 1         | 1.05%   |
| ASIX Electronics         | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 45.83%  |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 13.54%  |
| Intel I211 Gigabit Network Connection                             | 5         | 5.21%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 5.21%   |
| Intel Ethernet Controller I225-V                                  | 4         | 4.17%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.13%   |
| Realtek PCIe GbE Family Controller                                | 2         | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.08%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.04%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.04%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.04%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.04%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 92        | 52.57%  |
| WiFi     | 82        | 46.86%  |
| Unknown  | 1         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 58.18%  |
| Ethernet | 46        | 41.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 57        | 53.77%  |
| 1     | 46        | 43.4%   |
| 3     | 3         | 2.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 63.55%  |
| Yes  | 39        | 36.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 51.95%  |
| MediaTek                        | 8         | 10.39%  |
| Cambridge Silicon Radio         | 7         | 9.09%   |
| Qualcomm Atheros Communications | 5         | 6.49%   |
| IMC Networks                    | 5         | 6.49%   |
| Lite-On Technology              | 4         | 5.19%   |
| Realtek Semiconductor           | 3         | 3.9%    |
| ASUSTek Computer                | 2         | 2.6%    |
| TP-Link                         | 1         | 1.3%    |
| Foxconn / Hon Hai               | 1         | 1.3%    |
| Apple                           | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 12.82%  |
| Intel AX201 Bluetooth                               | 9         | 11.54%  |
| MediaTek Wireless_Device                            | 8         | 10.26%  |
| Intel AX210 Bluetooth                               | 8         | 10.26%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 8.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 5.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.13%   |
| Intel AX200 Bluetooth                               | 4         | 5.13%   |
| Realtek Bluetooth Radio                             | 3         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.56%   |
| IMC Networks Wireless_Device                        | 2         | 2.56%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.56%   |
| TP-Link UB500 Adapter                               | 1         | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.28%   |
| Lite-On Wireless_Device                             | 1         | 1.28%   |
| Lite-On Bluetooth Device                            | 1         | 1.28%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.28%   |
| Intel Bluetooth Device                              | 1         | 1.28%   |
| IMC Networks Bluetooth Device                       | 1         | 1.28%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.28%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 1.28%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.28%   |
| Apple Bluetooth Host Controller                     | 1         | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 59        | 32.42%  |
| AMD                      | 56        | 30.77%  |
| Nvidia                   | 41        | 22.53%  |
| Sony                     | 4         | 2.2%    |
| Logitech                 | 4         | 2.2%    |
| Kingston Technology      | 3         | 1.65%   |
| Razer USA                | 2         | 1.1%    |
| C-Media Electronics      | 2         | 1.1%    |
| Texas Instruments        | 1         | 0.55%   |
| SteelSeries ApS          | 1         | 0.55%   |
| Realtek Semiconductor    | 1         | 0.55%   |
| Micro Star International | 1         | 0.55%   |
| JMTek                    | 1         | 0.55%   |
| Hewlett-Packard          | 1         | 0.55%   |
| Generalplus Technology   | 1         | 0.55%   |
| Focusrite-Novation       | 1         | 0.55%   |
| Comtrue                  | 1         | 0.55%   |
| ASUSTek Computer         | 1         | 0.55%   |
| Astro Gaming             | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 22        | 9.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 16        | 7.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9         | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 3.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 3.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 2.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 2.23%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 1.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.79%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 4         | 1.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.34%   |
| Nvidia Audio device                                                        | 3         | 1.34%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.34%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.34%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.34%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2         | 0.89%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.89%   |
| Razer USA Razer Seiren Mini                                                | 2         | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.89%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 0.89%   |
| Kingston Technology HyperX QuadCast                                        | 2         | 0.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.89%   |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.89%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 30.56%  |
| Microdia                      | 8         | 22.22%  |
| IMC Networks                  | 4         | 11.11%  |
| Sunplus Innovation Technology | 3         | 8.33%   |
| Quanta                        | 2         | 5.56%   |
| Bison Electronics             | 2         | 5.56%   |
| Sonix Technology              | 1         | 2.78%   |
| Silicon Motion                | 1         | 2.78%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 2.78%   |
| Realtek Semiconductor         | 1         | 2.78%   |
| Logitech                      | 1         | 2.78%   |
| Apple                         | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks Integrated Camera       | 3         | 8.33%   |
| Microdia Integrated_Webcam_FHD       | 2         | 5.56%   |
| Chicony Integrated Camera            | 2         | 5.56%   |
| Chicony HD WebCam                    | 2         | 5.56%   |
| Chicony HD User Facing               | 2         | 5.56%   |
| Bison Lenovo EasyCamera              | 2         | 5.56%   |
| Sunplus Integrated_Webcam_HD         | 1         | 2.78%   |
| Sunplus HD WebCam                    | 1         | 2.78%   |
| Sunplus Full HD webcam               | 1         | 2.78%   |
| Sonix USB2.0 HD UVC WebCam           | 1         | 2.78%   |
| Silicon Motion 300k Pixel Camera     | 1         | 2.78%   |
| SHENZHEN EMEET TECHNOLOGY eMeet Nova | 1         | 2.78%   |
| Realtek Integrated Webcam            | 1         | 2.78%   |
| Quanta HP HD Camera                  | 1         | 2.78%   |
| Quanta HD User Facing                | 1         | 2.78%   |
| Microdia Webcam Vitade AF            | 1         | 2.78%   |
| Microdia USB Camera                  | 1         | 2.78%   |
| Microdia USB 2.0 Camera              | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD        | 1         | 2.78%   |
| Microdia HP Webcam                   | 1         | 2.78%   |
| Microdia Camera                      | 1         | 2.78%   |
| Logitech Webcam C200                 | 1         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam    | 1         | 2.78%   |
| Chicony USB2.0 FHD Camera            | 1         | 2.78%   |
| Chicony USB2.0 0.3M UVC WebCam       | 1         | 2.78%   |
| Chicony HP Wide Vision HD Camera     | 1         | 2.78%   |
| Chicony HP Truevision HD             | 1         | 2.78%   |
| Chicony EasyCamera                   | 1         | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X      | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 50%     |
| Shenzhen Goodix Technology | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 50%     |
| Shenzhen Goodix  FingerPrint Device                      | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 75        | 70.75%  |
| 1     | 30        | 28.3%   |
| 2     | 1         | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 16        | 50%     |
| Multimedia controller | 6         | 18.75%  |
| Network               | 3         | 9.38%   |
| Net/wireless          | 3         | 9.38%   |
| Fingerprint reader    | 2         | 6.25%   |
| Storage/nvme          | 1         | 3.13%   |
| Chipcard              | 1         | 3.13%   |


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

Total: 114

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| ChimeraOS 43-1 | 25        | 27.78%  |
| ChimeraOS 42   | 18        | 20%     |
| ChimeraOS 39   | 15        | 16.67%  |
| ChimeraOS 41   | 11        | 12.22%  |
| ChimeraOS 43   | 8         | 8.89%   |
| ChimeraOS 38   | 6         | 6.67%   |
| ChimeraOS 37   | 4         | 4.44%   |
| ChimeraOS 44   | 1         | 1.11%   |
| ChimeraOS 35   | 1         | 1.11%   |
| ChimeraOS      | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 88        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.3.9-chimeraos-1       | 32        | 35.16%  |
| 6.1.27-1-lts            | 18        | 19.78%  |
| 6.1.11-arch1-1          | 15        | 16.48%  |
| 6.1.21-1-lts            | 11        | 12.09%  |
| 6.1.1-arch1-1           | 6         | 6.59%   |
| 6.0.8-arch1-1           | 4         | 4.4%    |
| 6.5.3-chos1-chimeraos-1 | 1         | 1.1%    |
| 6.4.9-0-generic         | 1         | 1.1%    |
| 6.3.3-arch1-1           | 1         | 1.1%    |
| 6.3.1-arch2-1           | 1         | 1.1%    |
| 5.19.6-arch1-1          | 1         | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.9   | 32        | 35.16%  |
| 6.1.27  | 18        | 19.78%  |
| 6.1.11  | 15        | 16.48%  |
| 6.1.21  | 11        | 12.09%  |
| 6.1.1   | 6         | 6.59%   |
| 6.0.8   | 4         | 4.4%    |
| 6.5.3   | 1         | 1.1%    |
| 6.4.9   | 1         | 1.1%    |
| 6.3.3   | 1         | 1.1%    |
| 6.3.1   | 1         | 1.1%    |
| 5.19.6  | 1         | 1.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 49        | 55.06%  |
| 6.3     | 33        | 37.08%  |
| 6.0     | 4         | 4.49%   |
| 6.5     | 1         | 1.12%   |
| 6.4     | 1         | 1.12%   |
| 5.19    | 1         | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 88        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 87        | 98.86%  |
| steamos | 1         | 1.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 82        | 93.18%  |
| X11     | 6         | 6.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 77        | 87.5%   |
| pt_BR | 3         | 3.41%   |
| es_ES | 3         | 3.41%   |
| it_IT | 2         | 2.27%   |
| fr_FR | 1         | 1.14%   |
| de_DE | 1         | 1.14%   |
| C     | 1         | 1.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 88        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 87        | 98.86%  |
| Ext4  | 1         | 1.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 19        | 21.59%  |
| Gigabyte Technology    | 13        | 14.77%  |
| Dell                   | 9         | 10.23%  |
| Hewlett-Packard        | 8         | 9.09%   |
| Lenovo                 | 7         | 7.95%   |
| Acer                   | 7         | 7.95%   |
| MSI                    | 4         | 4.55%   |
| ASRock                 | 3         | 3.41%   |
| Razer                  | 2         | 2.27%   |
| ONE-NETBOOK TECHNOLOGY | 2         | 2.27%   |
| ONE-NETBOOK            | 2         | 2.27%   |
| AYANEO                 | 2         | 2.27%   |
| Microsoft              | 1         | 1.14%   |
| Micro Electronics      | 1         | 1.14%   |
| MACHINIST              | 1         | 1.14%   |
| Intel                  | 1         | 1.14%   |
| GPD                    | 1         | 1.14%   |
| Google                 | 1         | 1.14%   |
| AZW                    | 1         | 1.14%   |
| Anbernic               | 1         | 1.14%   |
| AMI                    | 1         | 1.14%   |
| Alienware              | 1         | 1.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER          | 2         | 2.27%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 2.27%   |
| HP EliteDesk 800 G1 SFF                     | 2         | 2.27%   |
| Gigabyte B550I AORUS PRO AX                 | 2         | 2.27%   |
| AYANEO 2                                    | 2         | 2.27%   |
| ASUS ROG STRIX B550-F GAMING                | 2         | 2.27%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 1.14%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 1.14%   |
| MSI MS-7D73                                 | 1         | 1.14%   |
| MSI MS-7C91                                 | 1         | 1.14%   |
| MSI GE75 Raider 10SF                        | 1         | 1.14%   |
| MSI CX62 6QD                                | 1         | 1.14%   |
| Microsoft Surface Book                      | 1         | 1.14%   |
| Micro MG-VCP17I-3070                        | 1         | 1.14%   |
| MACHINIST X99-RS9 V2.0                      | 1         | 1.14%   |
| Lenovo Y50-70 20378                         | 1         | 1.14%   |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 1.14%   |
| Lenovo ThinkCentre M70e 0832B1U             | 1         | 1.14%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 1.14%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.14%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 1.14%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 1.14%   |
| Intel DB75EN AAG39650-400                   | 1         | 1.14%   |
| HP Z220 SFF Workstation                     | 1         | 1.14%   |
| HP Victus by Laptop 16-d1xxx                | 1         | 1.14%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx   | 1         | 1.14%   |
| HP ProDesk 600 G1 SFF                       | 1         | 1.14%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 1.14%   |
| HP 250 G4 Notebook PC                       | 1         | 1.14%   |
| GPD P2 MAX                                  | 1         | 1.14%   |
| Google Snappy                               | 1         | 1.14%   |
| Gigabyte Z97X-Gaming 5                      | 1         | 1.14%   |
| Gigabyte Z490 GAMING X AX                   | 1         | 1.14%   |
| Gigabyte X570S AORUS ELITE AX               | 1         | 1.14%   |
| Gigabyte X570 AORUS ELITE WIFI              | 1         | 1.14%   |
| Gigabyte X470 AORUS GAMING 5 WIFI           | 1         | 1.14%   |
| Gigabyte H77M-D3H                           | 1         | 1.14%   |
| Gigabyte H510M H                            | 1         | 1.14%   |
| Gigabyte G1.Sniper A88X-CF                  | 1         | 1.14%   |
| Gigabyte B460M DS3H AC V2-Y1                | 1         | 1.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell OptiPlex              | 6         | 6.82%   |
| ASUS ROG                   | 6         | 6.82%   |
| Acer Aspire                | 4         | 4.55%   |
| Lenovo IdeaPad             | 3         | 3.41%   |
| Razer Blade                | 2         | 2.27%   |
| ONE-NETBOOK TECHNOLOGY ONE | 2         | 2.27%   |
| ONE-NETBOOK ONEXPLAYER     | 2         | 2.27%   |
| HP Victus                  | 2         | 2.27%   |
| HP EliteDesk               | 2         | 2.27%   |
| Gigabyte B550I             | 2         | 2.27%   |
| Gigabyte B450              | 2         | 2.27%   |
| Dell Inspiron              | 2         | 2.27%   |
| AYANEO 2                   | 2         | 2.27%   |
| ASUS TUF                   | 2         | 2.27%   |
| ASUS PRIME                 | 2         | 2.27%   |
| Acer Nitro                 | 2         | 2.27%   |
| MSI MS-7D73                | 1         | 1.14%   |
| MSI MS-7C91                | 1         | 1.14%   |
| MSI GE75                   | 1         | 1.14%   |
| MSI CX62                   | 1         | 1.14%   |
| Microsoft Surface          | 1         | 1.14%   |
| Micro MG-VCP17I-3070       | 1         | 1.14%   |
| MACHINIST X99-RS9          | 1         | 1.14%   |
| Lenovo Y50-70              | 1         | 1.14%   |
| Lenovo ThinkPad            | 1         | 1.14%   |
| Lenovo ThinkCentre         | 1         | 1.14%   |
| Lenovo Legion              | 1         | 1.14%   |
| Intel DB75EN               | 1         | 1.14%   |
| HP Z220                    | 1         | 1.14%   |
| HP ProDesk                 | 1         | 1.14%   |
| HP EliteBook               | 1         | 1.14%   |
| HP 250                     | 1         | 1.14%   |
| GPD P2                     | 1         | 1.14%   |
| Google Snappy              | 1         | 1.14%   |
| Gigabyte Z97X-Gaming       | 1         | 1.14%   |
| Gigabyte Z490              | 1         | 1.14%   |
| Gigabyte X570S             | 1         | 1.14%   |
| Gigabyte X570              | 1         | 1.14%   |
| Gigabyte X470              | 1         | 1.14%   |
| Gigabyte H77M-D3H          | 1         | 1.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 14        | 15.91%  |
| 2021 | 13        | 14.77%  |
| 2022 | 11        | 12.5%   |
| 2019 | 7         | 7.95%   |
| 2017 | 7         | 7.95%   |
| 2018 | 6         | 6.82%   |
| 2016 | 6         | 6.82%   |
| 2012 | 6         | 6.82%   |
| 2015 | 5         | 5.68%   |
| 2023 | 4         | 4.55%   |
| 2013 | 4         | 4.55%   |
| 2014 | 3         | 3.41%   |
| 2011 | 1         | 1.14%   |
| 2010 | 1         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 43        | 48.86%  |
| Notebook    | 36        | 40.91%  |
| Tablet      | 5         | 5.68%   |
| Mini pc     | 2         | 2.27%   |
| Convertible | 1         | 1.14%   |
| All in one  | 1         | 1.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 88        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 87        | 98.86%  |
| Yes  | 1         | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 24        | 27.27%  |
| 32.01-64.0  | 22        | 25%     |
| 8.01-16.0   | 14        | 15.91%  |
| 4.01-8.0    | 13        | 14.77%  |
| 24.01-32.0  | 7         | 7.95%   |
| 3.01-4.0    | 5         | 5.68%   |
| 64.01-256.0 | 3         | 3.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 41        | 45.56%  |
| 1.01-2.0   | 20        | 22.22%  |
| 3.01-4.0   | 17        | 18.89%  |
| 4.01-8.0   | 11        | 12.22%  |
| 16.01-24.0 | 1         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 45.56%  |
| 2      | 29        | 32.22%  |
| 3      | 14        | 15.56%  |
| 4      | 2         | 2.22%   |
| 8      | 1         | 1.11%   |
| 7      | 1         | 1.11%   |
| 6      | 1         | 1.11%   |
| 5      | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 84.09%  |
| Yes       | 14        | 15.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 85.23%  |
| No        | 13        | 14.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 79.55%  |
| No        | 18        | 20.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 76.14%  |
| No        | 21        | 23.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 36        | 40.91%  |
| Germany      | 6         | 6.82%   |
| Brazil       | 6         | 6.82%   |
| Australia    | 4         | 4.55%   |
| Vietnam      | 3         | 3.41%   |
| UK           | 3         | 3.41%   |
| Spain        | 3         | 3.41%   |
| Russia       | 3         | 3.41%   |
| Italy        | 3         | 3.41%   |
| Saudi Arabia | 2         | 2.27%   |
| Poland       | 2         | 2.27%   |
| Canada       | 2         | 2.27%   |
| Switzerland  | 1         | 1.14%   |
| Romania      | 1         | 1.14%   |
| Norway       | 1         | 1.14%   |
| Netherlands  | 1         | 1.14%   |
| Malaysia     | 1         | 1.14%   |
| Macao        | 1         | 1.14%   |
| Japan        | 1         | 1.14%   |
| Iceland      | 1         | 1.14%   |
| Hungary      | 1         | 1.14%   |
| Honduras     | 1         | 1.14%   |
| France       | 1         | 1.14%   |
| Finland      | 1         | 1.14%   |
| Estonia      | 1         | 1.14%   |
| Costa Rica   | 1         | 1.14%   |
| Belgium      | 1         | 1.14%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Sanford                  | 2         | 2.25%   |
| Melbourne                | 2         | 2.25%   |
| Chattanooga              | 2         | 2.25%   |
| Yekaterinburg            | 1         | 1.12%   |
| Yaroslavl                | 1         | 1.12%   |
| Wroclaw                  | 1         | 1.12%   |
| Wiesbaden                | 1         | 1.12%   |
| Watsonville              | 1         | 1.12%   |
| Warsaw                   | 1         | 1.12%   |
| Vũng Tàu               | 1         | 1.12%   |
| Virginia Beach           | 1         | 1.12%   |
| Vila-seca                | 1         | 1.12%   |
| Valence                  | 1         | 1.12%   |
| Umeda                    | 1         | 1.12%   |
| Tulcea                   | 1         | 1.12%   |
| Toronto                  | 1         | 1.12%   |
| Tegucigalpa              | 1         | 1.12%   |
| Tallinn                  | 1         | 1.12%   |
| Sydney                   | 1         | 1.12%   |
| Sumaré                  | 1         | 1.12%   |
| Steyning                 | 1         | 1.12%   |
| St Louis                 | 1         | 1.12%   |
| Springfield              | 1         | 1.12%   |
| Shelbyville              | 1         | 1.12%   |
| Seattle                  | 1         | 1.12%   |
| Sao Paulo                | 1         | 1.12%   |
| Santa Cruz das Palmeiras | 1         | 1.12%   |
| San José                | 1         | 1.12%   |
| Samara                   | 1         | 1.12%   |
| Saltillo                 | 1         | 1.12%   |
| Round Rock               | 1         | 1.12%   |
| Rockford                 | 1         | 1.12%   |
| Ridley Park              | 1         | 1.12%   |
| Reykjavik                | 1         | 1.12%   |
| Racine                   | 1         | 1.12%   |
| Pittsburg                | 1         | 1.12%   |
| Phoenix                  | 1         | 1.12%   |
| Philadelphia             | 1         | 1.12%   |
| Pennsauken               | 1         | 1.12%   |
| Parma                    | 1         | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 21        | 26     | 13.73%  |
| Samsung Electronics          | 21        | 31     | 13.73%  |
| WDC                          | 15        | 20     | 9.8%    |
| Kingston                     | 12        | 12     | 7.84%   |
| SanDisk                      | 9         | 13     | 5.88%   |
| Micron Technology            | 8         | 10     | 5.23%   |
| Unknown                      | 6         | 6      | 3.92%   |
| Toshiba                      | 6         | 7      | 3.92%   |
| Micron/Crucial Technology    | 6         | 6      | 3.92%   |
| SK hynix                     | 5         | 5      | 3.27%   |
| Phison Electronics           | 5         | 5      | 3.27%   |
| Intel                        | 5         | 6      | 3.27%   |
| Crucial                      | 4         | 6      | 2.61%   |
| Kingston Technology Company  | 3         | 3      | 1.96%   |
| Silicon Motion               | 2         | 2      | 1.31%   |
| KIOXIA                       | 2         | 2      | 1.31%   |
| Hitachi                      | 2         | 2      | 1.31%   |
| Fanxiang                     | 2         | 2      | 1.31%   |
| China                        | 2         | 2      | 1.31%   |
| ADATA Technology             | 2         | 3      | 1.31%   |
| WDC PC S                     | 1         | 1      | 0.65%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.65%   |
| Realtek Semiconductor        | 1         | 1      | 0.65%   |
| NT-1TB                       | 1         | 1      | 0.65%   |
| Netac                        | 1         | 1      | 0.65%   |
| KingFast                     | 1         | 1      | 0.65%   |
| KingDian                     | 1         | 3      | 0.65%   |
| JMicron Technology           | 1         | 1      | 0.65%   |
| HGST                         | 1         | 1      | 0.65%   |
| Hewlett-Packard              | 1         | 1      | 0.65%   |
| Corsair                      | 1         | 1      | 0.65%   |
| Biwin Storage Technology     | 1         | 1      | 0.65%   |
| AMD                          | 1         | 1      | 0.65%   |
| A-DATA Technology            | 1         | 1      | 0.65%   |
| Unknown                      | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB               | 7         | 4.27%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                               | 6         | 3.66%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 5         | 3.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                | 4         | 2.44%   |
| Kingston SA400S37120G 120GB SSD                                   | 3         | 1.83%   |
| Unknown MMC Card  64GB                                            | 2         | 1.22%   |
| SK hynix HFM512GD3JX016N 512GB                                    | 2         | 1.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB             | 2         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 2         | 1.22%   |
| Samsung SSD 870 QVO 2TB                                           | 2         | 1.22%   |
| Samsung SSD 860 EVO 1TB                                           | 2         | 1.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB               | 2         | 1.22%   |
| Phison PS5013 E13 NVMe Controller 512GB                           | 2         | 1.22%   |
| Phison E12 NVMe Controller 2TB                                    | 2         | 1.22%   |
| Micron 1100 SATA 256GB SSD                                        | 2         | 1.22%   |
| Kingston SNVS500G 500GB                                           | 2         | 1.22%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 2         | 1.22%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 1         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                  | 1         | 0.61%   |
| WDC WDBNCE5000PNC 500GB SSD                                       | 1         | 0.61%   |
| WDC WDBNCE0010PNC 1TB SSD                                         | 1         | 0.61%   |
| WDC WD7500BPVT-80HXZT3 752GB                                      | 1         | 0.61%   |
| WDC WD5000BEVT-22A0RT0 500GB                                      | 1         | 0.61%   |
| WDC WD5000AVDS-63U7B1 500GB                                       | 1         | 0.61%   |
| WDC WD40EZRX-00SPEB0 4TB                                          | 1         | 0.61%   |
| WDC WD20SPZX-08UA7 2TB                                            | 1         | 0.61%   |
| WDC WD20EARX-00PASB0 2TB                                          | 1         | 0.61%   |
| WDC WD201KFGX-68BKJN0 20TB                                        | 1         | 0.61%   |
| WDC WD1500HLFS-01G6U0 150GB                                       | 1         | 0.61%   |
| WDC WD10SPZX-80Z10T2 1TB                                          | 1         | 0.61%   |
| WDC WD10SPZX-24Z10 1TB                                            | 1         | 0.61%   |
| WDC WD10SPCX-24HWST1 1TB                                          | 1         | 0.61%   |
| WDC WD10JPLX-00MBPT0 1TB                                          | 1         | 0.61%   |
| WDC WD10EZEX-60M2NA0 1TB                                          | 1         | 0.61%   |
| WDC PC S N530 SDBPNPZ 256GB                                       | 1         | 0.61%   |
| Unknown SD/MMC/MS PRO 128GB                                       | 1         | 0.61%   |
| Unknown NVMe SSD Drive 1024GB                                     | 1         | 0.61%   |
| Unknown MMC Card  512GB                                           | 1         | 0.61%   |
| Unknown MMC Card  16GB                                            | 1         | 0.61%   |
| Toshiba XG6 NVMe SSD Controller 512GB                             | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 24     | 47.62%  |
| WDC                 | 13        | 15     | 30.95%  |
| Toshiba             | 4         | 5      | 9.52%   |
| Hitachi             | 2         | 2      | 4.76%   |
| Unknown             | 1         | 1      | 2.38%   |
| Samsung Electronics | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 12     | 16.67%  |
| Kingston            | 8         | 8      | 16.67%  |
| SanDisk             | 6         | 8      | 12.5%   |
| Micron Technology   | 6         | 8      | 12.5%   |
| Crucial             | 4         | 6      | 8.33%   |
| WDC                 | 3         | 5      | 6.25%   |
| Fanxiang            | 2         | 2      | 4.17%   |
| China               | 2         | 2      | 4.17%   |
| Seagate             | 1         | 1      | 2.08%   |
| NT-1TB              | 1         | 1      | 2.08%   |
| Netac               | 1         | 1      | 2.08%   |
| KingDian            | 1         | 3      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| Hewlett-Packard     | 1         | 1      | 2.08%   |
| Corsair             | 1         | 1      | 2.08%   |
| AMD                 | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 54        | 66     | 40.6%   |
| SSD     | 37        | 62     | 27.82%  |
| HDD     | 33        | 49     | 24.81%  |
| Unknown | 5         | 5      | 3.76%   |
| MMC     | 4         | 4      | 3.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 108    | 47.15%  |
| NVMe | 54        | 66     | 43.9%   |
| SAS  | 7         | 8      | 5.69%   |
| MMC  | 4         | 4      | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 57     | 38.67%  |
| 0.51-1.0   | 28        | 31     | 37.33%  |
| 1.01-2.0   | 12        | 14     | 16%     |
| 3.01-4.0   | 2         | 5      | 2.67%   |
| 4.01-10.0  | 2         | 2      | 2.67%   |
| 2.01-3.0   | 1         | 1      | 1.33%   |
| 10.01-20.0 | 1         | 1      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 37        | 41.57%  |
| 1001-2000      | 27        | 30.34%  |
| 501-1000       | 11        | 12.36%  |
| 251-500        | 9         | 10.11%  |
| 2001-3000      | 3         | 3.37%   |
| 101-250        | 2         | 2.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 28        | 31.11%  |
| 51-100         | 16        | 17.78%  |
| 101-250        | 13        | 14.44%  |
| 501-1000       | 11        | 12.22%  |
| 251-500        | 8         | 8.89%   |
| 1001-2000      | 6         | 6.67%   |
| More than 3000 | 4         | 4.44%   |
| 2001-3000      | 3         | 3.33%   |
| 1-20           | 1         | 1.11%   |

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
| Detected | 88        | 186    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 51        | 38.06%  |
| AMD                          | 25        | 18.66%  |
| Samsung Electronics          | 14        | 10.45%  |
| Kingston Technology Company  | 7         | 5.22%   |
| Micron/Crucial Technology    | 6         | 4.48%   |
| SK hynix                     | 5         | 3.73%   |
| Phison Electronics           | 5         | 3.73%   |
| SanDisk                      | 4         | 2.99%   |
| Toshiba America Info Systems | 2         | 1.49%   |
| Silicon Motion               | 2         | 1.49%   |
| Micron Technology            | 2         | 1.49%   |
| KIOXIA                       | 2         | 1.49%   |
| Biwin Storage Technology     | 2         | 1.49%   |
| ADATA Technology             | 2         | 1.49%   |
| Shenzhen Longsys Electronics | 1         | 0.75%   |
| Realtek Semiconductor        | 1         | 0.75%   |
| Marvell Technology Group     | 1         | 0.75%   |
| INNOGRIT                     | 1         | 0.75%   |
| ASMedia Technology           | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 11.49%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 4.73%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 4.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6         | 4.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 4.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.38%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.7%    |
| Intel SATA Controller [RAID mode]                                              | 4         | 2.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.7%    |
| Kingston Company NVMe Controller                                               | 3         | 2.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.03%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.35%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.35%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.35%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.35%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.35%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.35%   |
| Biwin Storage Non-Volatile memory controller                                   | 2         | 1.35%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 1.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.68%   |
| Toshiba America Info Systems XG3 NVMe SSD Controller                           | 1         | 0.68%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.68%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 0.68%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.68%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.68%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.68%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.68%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 61        | 46.21%  |
| NVMe | 54        | 40.91%  |
| RAID | 14        | 10.61%  |
| IDE  | 3         | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 54        | 61.36%  |
| AMD    | 34        | 38.64%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 6800U with Radeon Graphics        | 4         | 4.49%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 4         | 4.49%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 3         | 3.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.25%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 2.25%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.25%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2         | 2.25%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 2.25%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 2.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 2.25%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 2.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.25%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1         | 1.12%   |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz           | 1         | 1.12%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.12%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 1.12%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.12%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 1.12%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 1.12%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.12%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.12%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.12%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.12%   |
| Intel Core i5-9500T CPU @ 2.20GHz             | 1         | 1.12%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 1         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.12%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.12%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 1.12%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1         | 1.12%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 1.12%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1         | 1.12%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 1         | 1.12%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1         | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1         | 1.12%   |
| Intel Core i5-10600KF CPU @ 4.10GHz           | 1         | 1.12%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 21        | 23.6%   |
| Intel Core i7     | 15        | 16.85%  |
| AMD Ryzen 7       | 13        | 14.61%  |
| AMD Ryzen 5       | 12        | 13.48%  |
| Other             | 8         | 8.99%   |
| AMD Ryzen 9       | 7         | 7.87%   |
| Intel Core i3     | 4         | 4.49%   |
| Intel Xeon        | 2         | 2.25%   |
| Intel Core m3     | 1         | 1.12%   |
| Intel Core 2 Quad | 1         | 1.12%   |
| Intel Celeron     | 1         | 1.12%   |
| Intel Atom        | 1         | 1.12%   |
| AMD Ryzen 5 PRO   | 1         | 1.12%   |
| AMD Athlon        | 1         | 1.12%   |
| AMD A10           | 1         | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 36        | 40.45%  |
| 6      | 18        | 20.22%  |
| 8      | 16        | 17.98%  |
| 2      | 11        | 12.36%  |
| 12     | 3         | 3.37%   |
| 16     | 2         | 2.25%   |
| 24     | 1         | 1.12%   |
| 14     | 1         | 1.12%   |
| 10     | 1         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 68        | 77.27%  |
| 1      | 20        | 22.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 88        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 16        | 18.18%  |
| Zen 3       | 14        | 15.91%  |
| Unknown     | 14        | 15.91%  |
| Haswell     | 10        | 11.36%  |
| CometLake   | 6         | 6.82%   |
| Zen+        | 4         | 4.55%   |
| Zen         | 4         | 4.55%   |
| Skylake     | 4         | 4.55%   |
| Zen 2       | 3         | 3.41%   |
| SandyBridge | 3         | 3.41%   |
| IvyBridge   | 3         | 3.41%   |
| TigerLake   | 2         | 2.27%   |
| Silvermont  | 1         | 1.14%   |
| Piledriver  | 1         | 1.14%   |
| Penryn      | 1         | 1.14%   |
| Goldmont    | 1         | 1.14%   |
| Broadwell   | 1         | 1.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 40        | 35.4%   |
| Nvidia | 38        | 33.63%  |
| Intel  | 35        | 30.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 4.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 4.39%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 3.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 3.51%   |
| Intel HD Graphics 630                                                       | 3         | 2.63%   |
| Intel HD Graphics 530                                                       | 3         | 2.63%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3         | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 2.63%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 2.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.75%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 1.75%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2         | 1.75%   |
| Intel UHD Graphics 620                                                      | 2         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.75%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 2         | 1.75%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2         | 1.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2         | 1.75%   |
| AMD Lucienne                                                                | 2         | 1.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.88%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 0.88%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.88%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.88%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.88%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                    | 1         | 0.88%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 0.88%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                       | 1         | 0.88%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 0.88%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.88%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                  | 1         | 0.88%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 0.88%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 32        | 35.96%  |
| 1 x Nvidia     | 19        | 21.35%  |
| 1 x Intel      | 15        | 16.85%  |
| Intel + Nvidia | 14        | 15.73%  |
| AMD + Nvidia   | 5         | 5.62%   |
| Intel + AMD    | 3         | 3.37%   |
| Other          | 1         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 57.95%  |
| Proprietary | 36        | 40.91%  |
| Unknown     | 1         | 1.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 96.59%  |
| 3.01-4.0   | 2         | 2.27%   |
| 8.01-16.0  | 1         | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 13        | 15.12%  |
| BOE                  | 10        | 11.63%  |
| Chimei Innolux       | 7         | 8.14%   |
| LG Display           | 6         | 6.98%   |
| AU Optronics         | 5         | 5.81%   |
| Philips              | 3         | 3.49%   |
| MSI                  | 3         | 3.49%   |
| Goldstar             | 3         | 3.49%   |
| BenQ                 | 3         | 3.49%   |
| Unknown (XXX)        | 2         | 2.33%   |
| Toshiba              | 2         | 2.33%   |
| Sony                 | 2         | 2.33%   |
| Sharp                | 2         | 2.33%   |
| Insignia             | 2         | 2.33%   |
| Hewlett-Packard      | 2         | 2.33%   |
| ASUSTek Computer     | 2         | 2.33%   |
| Vizio                | 1         | 1.16%   |
| TMX                  | 1         | 1.16%   |
| SANYO                | 1         | 1.16%   |
| RTK                  | 1         | 1.16%   |
| PANDA                | 1         | 1.16%   |
| Panasonic            | 1         | 1.16%   |
| Onkyo                | 1         | 1.16%   |
| HJW                  | 1         | 1.16%   |
| Hitachi              | 1         | 1.16%   |
| Gigabyte Technology  | 1         | 1.16%   |
| GameMax              | 1         | 1.16%   |
| Fujitsu Siemens      | 1         | 1.16%   |
| DENON                | 1         | 1.16%   |
| Dell                 | 1         | 1.16%   |
| AYANEO               | 1         | 1.16%   |
| AYA                  | 1         | 1.16%   |
| Ancor Communications | 1         | 1.16%   |
| AGO                  | 1         | 1.16%   |
| Acer                 | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 2         | 2.3%    |
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                   | 2         | 2.3%    |
| Vizio D24f-F1 VIZ1027 1920x1080 527x296mm 23.8-inch                     | 1         | 1.15%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 1.15%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1         | 1.15%   |
| Toshiba TV TSB0206 1920x1080                                            | 1         | 1.15%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                       | 1         | 1.15%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                 | 1         | 1.15%   |
| Sony TV SNYEE01 1920x1080                                               | 1         | 1.15%   |
| Sony TV SNY3002 1920x1080 710x400mm 32.1-inch                           | 1         | 1.15%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch                 | 1         | 1.15%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                       | 1         | 1.15%   |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                          | 1         | 1.15%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch    | 1         | 1.15%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 530x300mm 24.0-inch     | 1         | 1.15%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch       | 1         | 1.15%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch       | 1         | 1.15%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch       | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                       | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM020B 1920x540                        | 1         | 1.15%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1190x340mm 48.7-inch     | 1         | 1.15%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 1.15%   |
| RTK FHD HDR RTK2A3B 1920x1080 344x195mm 15.6-inch                       | 1         | 1.15%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                 | 1         | 1.15%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch               | 1         | 1.15%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch                | 1         | 1.15%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.15%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch             | 1         | 1.15%   |
| Onkyo AV Receiver ONK1150 3840x2160 1872x1053mm 84.6-inch               | 1         | 1.15%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                  | 1         | 1.15%   |
| MSI MAG301CR2 MSI3CB4 2560x1080 690x291mm 29.5-inch                     | 1         | 1.15%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                          | 1         | 1.15%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD0459 1920x1080 382x215mm 17.3-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch             | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 49.4%   |
| 3840x2160 (4K)     | 11        | 13.25%  |
| 2560x1440 (QHD)    | 8         | 9.64%   |
| 1366x768 (WXGA)    | 6         | 7.23%   |
| 1200x1920          | 3         | 3.61%   |
| 1920x540           | 2         | 2.41%   |
| 1600x2560          | 2         | 2.41%   |
| 800x1280           | 1         | 1.2%    |
| 3840x1600          | 1         | 1.2%    |
| 3840x1080          | 1         | 1.2%    |
| 3440x1440          | 1         | 1.2%    |
| 2560x1080          | 1         | 1.2%    |
| 1920x1200 (WUXGA)  | 1         | 1.2%    |
| 1680x1050 (WSXGA+) | 1         | 1.2%    |
| 1600x900 (HD+)     | 1         | 1.2%    |
| 1280x960           | 1         | 1.2%    |
| 1280x768           | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 22.09%  |
| 27      | 8         | 9.3%    |
| Unknown | 6         | 6.98%   |
| 84      | 5         | 5.81%   |
| 24      | 5         | 5.81%   |
| 17      | 5         | 5.81%   |
| 23      | 4         | 4.65%   |
| 72      | 3         | 3.49%   |
| 31      | 3         | 3.49%   |
| 14      | 3         | 3.49%   |
| 54      | 2         | 2.33%   |
| 49      | 2         | 2.33%   |
| 48      | 2         | 2.33%   |
| 34      | 2         | 2.33%   |
| 8       | 2         | 2.33%   |
| 74      | 1         | 1.16%   |
| 57      | 1         | 1.16%   |
| 52      | 1         | 1.16%   |
| 46      | 1         | 1.16%   |
| 40      | 1         | 1.16%   |
| 38      | 1         | 1.16%   |
| 29      | 1         | 1.16%   |
| 26      | 1         | 1.16%   |
| 22      | 1         | 1.16%   |
| 21      | 1         | 1.16%   |
| 20      | 1         | 1.16%   |
| 18      | 1         | 1.16%   |
| 16      | 1         | 1.16%   |
| 12      | 1         | 1.16%   |
| 11      | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 25.58%  |
| 501-600     | 16        | 18.6%   |
| 1501-2000   | 8         | 9.3%    |
| 1001-1500   | 8         | 9.3%    |
| 601-700     | 7         | 8.14%   |
| 351-400     | 6         | 6.98%   |
| Unknown     | 6         | 6.98%   |
| 401-500     | 4         | 4.65%   |
| 701-800     | 3         | 3.49%   |
| 801-900     | 2         | 2.33%   |
| 201-300     | 2         | 2.33%   |
| 101-200     | 2         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 64        | 78.05%  |
| 0.62  | 6         | 7.32%   |
| 16/10 | 4         | 4.88%   |
| 21/9  | 3         | 3.66%   |
| 32/9  | 2         | 2.44%   |
| 4/3   | 1         | 1.22%   |
| 1.96  | 1         | 1.22%   |
| 0.56  | 1         | 1.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 24.1%   |
| More than 1000 | 13        | 15.66%  |
| 301-350        | 10        | 12.05%  |
| 201-250        | 10        | 12.05%  |
| 501-1000       | 6         | 7.23%   |
| Unknown        | 6         | 7.23%   |
| 121-130        | 5         | 6.02%   |
| 351-500        | 4         | 4.82%   |
| 81-90          | 3         | 3.61%   |
| 1-40           | 2         | 2.41%   |
| 71-80          | 1         | 1.2%    |
| 51-60          | 1         | 1.2%    |
| 151-200        | 1         | 1.2%    |
| 141-150        | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 29        | 34.52%  |
| 121-160       | 23        | 27.38%  |
| 1-50          | 9         | 10.71%  |
| 101-120       | 9         | 10.71%  |
| Unknown       | 6         | 7.14%   |
| 161-240       | 5         | 5.95%   |
| More than 240 | 3         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 76        | 85.39%  |
| 2     | 10        | 11.24%  |
| 0     | 3         | 3.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 52        | 36.88%  |
| Intel                           | 46        | 32.62%  |
| Qualcomm Atheros                | 14        | 9.93%   |
| MediaTek                        | 12        | 8.51%   |
| Microsoft                       | 3         | 2.13%   |
| Broadcom                        | 3         | 2.13%   |
| TP-Link                         | 2         | 1.42%   |
| Marvell Technology Group        | 2         | 1.42%   |
| Ralink Technology               | 1         | 0.71%   |
| Ralink                          | 1         | 0.71%   |
| Qualcomm Atheros Communications | 1         | 0.71%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.71%   |
| Edimax Technology               | 1         | 0.71%   |
| Broadcom Limited                | 1         | 0.71%   |
| ASIX Electronics                | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 21.88%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 6.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 7         | 4.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 4.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 3.13%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.5%    |
| Intel Wireless 3165                                               | 4         | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 4         | 2.5%    |
| Microsoft Xbox Wireless Adapter for Windows                       | 3         | 1.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.88%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.88%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.25%   |
| Intel Wireless 7265                                               | 2         | 1.25%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.25%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.63%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.63%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.63%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.63%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1         | 0.63%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 42.86%  |
| MediaTek                        | 12        | 15.58%  |
| Qualcomm Atheros                | 10        | 12.99%  |
| Realtek Semiconductor           | 9         | 11.69%  |
| Microsoft                       | 3         | 3.9%    |
| TP-Link                         | 2         | 2.6%    |
| Broadcom                        | 2         | 2.6%    |
| Ralink Technology               | 1         | 1.3%    |
| Ralink                          | 1         | 1.3%    |
| Qualcomm Atheros Communications | 1         | 1.3%    |
| Marvell Technology Group        | 1         | 1.3%    |
| Edimax Technology               | 1         | 1.3%    |
| Broadcom Limited                | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 7         | 8.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 7         | 8.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 5         | 6.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 5         | 6.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 4         | 4.94%   |
| Intel Wireless 3165                                                                  | 4         | 4.94%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 3         | 3.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                                  | 3         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 3         | 3.7%    |
| Intel Comet Lake PCH CNVi WiFi                                                       | 3         | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 3         | 3.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 2.47%   |
| Intel Wireless 7265                                                                  | 2         | 2.47%   |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 2.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 2         | 2.47%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 1.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 1.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                             | 1         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 1.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1         | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 1.23%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 1.23%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 1.23%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 1.23%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 1.23%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                    | 1         | 1.23%   |
| Intel Wireless-AC 9260                                                               | 1         | 1.23%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 1         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                     | 1         | 1.23%   |
| Edimax Wi-Fi                                                                         | 1         | 1.23%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                           | 1         | 1.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1         | 1.23%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                                   | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 62.34%  |
| Intel                    | 21        | 27.27%  |
| Qualcomm Atheros         | 5         | 6.49%   |
| Marvell Technology Group | 1         | 1.3%    |
| Broadcom                 | 1         | 1.3%    |
| ASIX Electronics         | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 44.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 12.82%  |
| Intel Ethernet Connection I217-LM                                 | 5         | 6.41%   |
| Intel I211 Gigabit Network Connection                             | 4         | 5.13%   |
| Intel Ethernet Controller I225-V                                  | 3         | 3.85%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.56%   |
| Realtek PCIe GbE Family Controller                                | 1         | 1.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.28%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.28%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.28%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.28%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 74        | 51.39%  |
| WiFi     | 69        | 47.92%  |
| Unknown  | 1         | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 58.7%   |
| Ethernet | 38        | 41.3%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 52.27%  |
| 1     | 39        | 44.32%  |
| 3     | 3         | 3.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 67.42%  |
| Yes  | 29        | 32.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 49.25%  |
| MediaTek                        | 8         | 11.94%  |
| Cambridge Silicon Radio         | 6         | 8.96%   |
| IMC Networks                    | 5         | 7.46%   |
| Qualcomm Atheros Communications | 4         | 5.97%   |
| Lite-On Technology              | 4         | 5.97%   |
| Realtek Semiconductor           | 2         | 2.99%   |
| ASUSTek Computer                | 2         | 2.99%   |
| TP-Link                         | 1         | 1.49%   |
| Foxconn / Hon Hai               | 1         | 1.49%   |
| Apple                           | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 13.24%  |
| MediaTek Wireless_Device                            | 8         | 11.76%  |
| Intel AX210 Bluetooth                               | 7         | 10.29%  |
| Intel AX201 Bluetooth                               | 7         | 10.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4.41%   |
| Realtek Bluetooth Radio                             | 2         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.94%   |
| Intel AX200 Bluetooth                               | 2         | 2.94%   |
| IMC Networks Wireless_Device                        | 2         | 2.94%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.94%   |
| TP-Link UB5A Adapter                                | 1         | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.47%   |
| Lite-On Wireless_Device                             | 1         | 1.47%   |
| Lite-On Bluetooth Device                            | 1         | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.47%   |
| Intel Bluetooth Device                              | 1         | 1.47%   |
| IMC Networks Bluetooth Device                       | 1         | 1.47%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.47%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 1.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.47%   |
| Apple Bluetooth Host Controller                     | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 53        | 35.57%  |
| AMD                      | 46        | 30.87%  |
| Nvidia                   | 29        | 19.46%  |
| Sony                     | 4         | 2.68%   |
| Logitech                 | 3         | 2.01%   |
| Kingston Technology      | 2         | 1.34%   |
| Texas Instruments        | 1         | 0.67%   |
| SteelSeries ApS          | 1         | 0.67%   |
| Realtek Semiconductor    | 1         | 0.67%   |
| Razer USA                | 1         | 0.67%   |
| Micro Star International | 1         | 0.67%   |
| JMTek                    | 1         | 0.67%   |
| Hewlett-Packard          | 1         | 0.67%   |
| Generalplus Technology   | 1         | 0.67%   |
| Focusrite-Novation       | 1         | 0.67%   |
| C-Media Electronics      | 1         | 0.67%   |
| ASUSTek Computer         | 1         | 0.67%   |
| Astro Gaming             | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 10.22%  |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 5.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 4.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 4.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 4.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8         | 4.3%    |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 3.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 3.23%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 2.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 2.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 2.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.61%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.61%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2         | 1.08%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.08%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 1.08%   |
| Kingston Technology HyperX QuadCast                                        | 2         | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.08%   |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 1.08%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.08%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2         | 1.08%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.54%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1         | 0.54%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.54%   |
| Razer USA Razer Seiren Mini                                                | 1         | 0.54%   |

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
| Chicony Electronics           | 10        | 31.25%  |
| Microdia                      | 6         | 18.75%  |
| IMC Networks                  | 4         | 12.5%   |
| Sunplus Innovation Technology | 3         | 9.38%   |
| Quanta                        | 2         | 6.25%   |
| Acer                          | 2         | 6.25%   |
| Silicon Motion                | 1         | 3.13%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 3.13%   |
| Realtek Semiconductor         | 1         | 3.13%   |
| Logitech                      | 1         | 3.13%   |
| Apple                         | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks Integrated Camera       | 3         | 9.38%   |
| Microdia Integrated_Webcam_FHD       | 2         | 6.25%   |
| Chicony Integrated Camera            | 2         | 6.25%   |
| Chicony HD User Facing               | 2         | 6.25%   |
| Acer Lenovo EasyCamera               | 2         | 6.25%   |
| Sunplus Integrated_Webcam_HD         | 1         | 3.13%   |
| Sunplus HD WebCam                    | 1         | 3.13%   |
| Sunplus HD 720P webcam               | 1         | 3.13%   |
| Silicon Motion 300k Pixel Camera     | 1         | 3.13%   |
| SHENZHEN EMEET TECHNOLOGY eMeet Nova | 1         | 3.13%   |
| Realtek Integrated Webcam            | 1         | 3.13%   |
| Quanta HP HD Camera                  | 1         | 3.13%   |
| Quanta HD User Facing                | 1         | 3.13%   |
| Microdia Webcam Vitade AF            | 1         | 3.13%   |
| Microdia USB Camera                  | 1         | 3.13%   |
| Microdia USB 2.0 Camera              | 1         | 3.13%   |
| Microdia HP Webcam                   | 1         | 3.13%   |
| Logitech Webcam C200                 | 1         | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam    | 1         | 3.13%   |
| Chicony USB2.0 FHD Camera            | 1         | 3.13%   |
| Chicony USB2.0 0.3M UVC WebCam       | 1         | 3.13%   |
| Chicony Integrated IR Camera         | 1         | 3.13%   |
| Chicony HP Wide Vision HD Camera     | 1         | 3.13%   |
| Chicony HP Truevision HD             | 1         | 3.13%   |
| Chicony EasyCamera                   | 1         | 3.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR   | 1         | 3.13%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 74        | 84.09%  |
| 1     | 14        | 15.91%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 6         | 42.86%  |
| Graphics card         | 3         | 21.43%  |
| Fingerprint reader    | 2         | 14.29%  |
| Storage/nvme          | 1         | 7.14%   |
| Network               | 1         | 7.14%   |
| Net/wireless          | 1         | 7.14%   |


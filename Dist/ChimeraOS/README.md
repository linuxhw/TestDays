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

Total: 93

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| ChimeraOS 42   | 18        | 25.35%  |
| ChimeraOS 39   | 15        | 21.13%  |
| ChimeraOS 41   | 11        | 15.49%  |
| ChimeraOS 43   | 8         | 11.27%  |
| ChimeraOS 43-1 | 7         | 9.86%   |
| ChimeraOS 38   | 6         | 8.45%   |
| ChimeraOS 37   | 4         | 5.63%   |
| ChimeraOS 35   | 1         | 1.41%   |
| ChimeraOS      | 1         | 1.41%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 69        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 6.1.27-1-lts      | 18        | 25%     |
| 6.1.11-arch1-1    | 15        | 20.83%  |
| 6.3.9-chimeraos-1 | 14        | 19.44%  |
| 6.1.21-1-lts      | 11        | 15.28%  |
| 6.1.1-arch1-1     | 6         | 8.33%   |
| 6.0.8-arch1-1     | 4         | 5.56%   |
| 6.4.9-0-generic   | 1         | 1.39%   |
| 6.3.3-arch1-1     | 1         | 1.39%   |
| 6.3.1-arch2-1     | 1         | 1.39%   |
| 5.19.6-arch1-1    | 1         | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.27  | 18        | 25%     |
| 6.1.11  | 15        | 20.83%  |
| 6.3.9   | 14        | 19.44%  |
| 6.1.21  | 11        | 15.28%  |
| 6.1.1   | 6         | 8.33%   |
| 6.0.8   | 4         | 5.56%   |
| 6.4.9   | 1         | 1.39%   |
| 6.3.3   | 1         | 1.39%   |
| 6.3.1   | 1         | 1.39%   |
| 5.19.6  | 1         | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 49        | 70%     |
| 6.3     | 15        | 21.43%  |
| 6.0     | 4         | 5.71%   |
| 6.4     | 1         | 1.43%   |
| 5.19    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 68        | 98.55%  |
| steamos | 1         | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 63        | 91.3%   |
| X11     | 6         | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 61        | 88.41%  |
| pt_BR | 2         | 2.9%    |
| it_IT | 2         | 2.9%    |
| es_ES | 2         | 2.9%    |
| de_DE | 1         | 1.45%   |
| C     | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 69        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 68        | 98.55%  |
| Ext4  | 1         | 1.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 12        | 17.39%  |
| Gigabyte Technology    | 11        | 15.94%  |
| Lenovo                 | 7         | 10.14%  |
| Hewlett-Packard        | 6         | 8.7%    |
| Dell                   | 6         | 8.7%    |
| Acer                   | 6         | 8.7%    |
| MSI                    | 4         | 5.8%    |
| Razer                  | 2         | 2.9%    |
| ONE-NETBOOK TECHNOLOGY | 2         | 2.9%    |
| ONE-NETBOOK            | 2         | 2.9%    |
| AYANEO                 | 2         | 2.9%    |
| Microsoft              | 1         | 1.45%   |
| Micro Electronics      | 1         | 1.45%   |
| MACHINIST              | 1         | 1.45%   |
| Intel                  | 1         | 1.45%   |
| GPD                    | 1         | 1.45%   |
| Google                 | 1         | 1.45%   |
| AZW                    | 1         | 1.45%   |
| ASRock                 | 1         | 1.45%   |
| AMI                    | 1         | 1.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER          | 2         | 2.9%    |
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 2.9%    |
| HP EliteDesk 800 G1 SFF                     | 2         | 2.9%    |
| Gigabyte B550I AORUS PRO AX                 | 2         | 2.9%    |
| AYANEO 2                                    | 2         | 2.9%    |
| ASUS ROG STRIX B550-F GAMING                | 2         | 2.9%    |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 1.45%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 1.45%   |
| MSI MS-7D73                                 | 1         | 1.45%   |
| MSI MS-7C91                                 | 1         | 1.45%   |
| MSI GE75 Raider 10SF                        | 1         | 1.45%   |
| MSI CX62 6QD                                | 1         | 1.45%   |
| Microsoft Surface Book                      | 1         | 1.45%   |
| Micro MG-VCP17I-3070                        | 1         | 1.45%   |
| MACHINIST X99-RS9 V2.0                      | 1         | 1.45%   |
| Lenovo Y50-70 20378                         | 1         | 1.45%   |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 1.45%   |
| Lenovo ThinkCentre M70e 0832B1U             | 1         | 1.45%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 1.45%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.45%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 1.45%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 1.45%   |
| Intel DB75EN AAG39650-400                   | 1         | 1.45%   |
| HP Z220 SFF Workstation                     | 1         | 1.45%   |
| HP Victus by Laptop 16-d1xxx                | 1         | 1.45%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 1.45%   |
| HP 250 G4 Notebook PC                       | 1         | 1.45%   |
| GPD P2 MAX                                  | 1         | 1.45%   |
| Google Snappy                               | 1         | 1.45%   |
| Gigabyte X570S AORUS ELITE AX               | 1         | 1.45%   |
| Gigabyte X570 AORUS ELITE WIFI              | 1         | 1.45%   |
| Gigabyte X470 AORUS GAMING 5 WIFI           | 1         | 1.45%   |
| Gigabyte H77M-D3H                           | 1         | 1.45%   |
| Gigabyte H510M H                            | 1         | 1.45%   |
| Gigabyte G1.Sniper A88X-CF                  | 1         | 1.45%   |
| Gigabyte B460M DS3H AC V2-Y1                | 1         | 1.45%   |
| Gigabyte B450 AORUS PRO WIFI                | 1         | 1.45%   |
| Gigabyte B450 AORUS M                       | 1         | 1.45%   |
| Dell OptiPlex 9020                          | 1         | 1.45%   |
| Dell OptiPlex 7050                          | 1         | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell OptiPlex              | 5         | 7.25%   |
| ASUS ROG                   | 5         | 7.25%   |
| Acer Aspire                | 4         | 5.8%    |
| Lenovo IdeaPad             | 3         | 4.35%   |
| Razer Blade                | 2         | 2.9%    |
| ONE-NETBOOK TECHNOLOGY ONE | 2         | 2.9%    |
| ONE-NETBOOK ONEXPLAYER     | 2         | 2.9%    |
| HP EliteDesk               | 2         | 2.9%    |
| Gigabyte B550I             | 2         | 2.9%    |
| Gigabyte B450              | 2         | 2.9%    |
| AYANEO 2                   | 2         | 2.9%    |
| ASUS PRIME                 | 2         | 2.9%    |
| MSI MS-7D73                | 1         | 1.45%   |
| MSI MS-7C91                | 1         | 1.45%   |
| MSI GE75                   | 1         | 1.45%   |
| MSI CX62                   | 1         | 1.45%   |
| Microsoft Surface          | 1         | 1.45%   |
| Micro MG-VCP17I-3070       | 1         | 1.45%   |
| MACHINIST X99-RS9          | 1         | 1.45%   |
| Lenovo Y50-70              | 1         | 1.45%   |
| Lenovo ThinkPad            | 1         | 1.45%   |
| Lenovo ThinkCentre         | 1         | 1.45%   |
| Lenovo Legion              | 1         | 1.45%   |
| Intel DB75EN               | 1         | 1.45%   |
| HP Z220                    | 1         | 1.45%   |
| HP Victus                  | 1         | 1.45%   |
| HP EliteBook               | 1         | 1.45%   |
| HP 250                     | 1         | 1.45%   |
| GPD P2                     | 1         | 1.45%   |
| Google Snappy              | 1         | 1.45%   |
| Gigabyte X570S             | 1         | 1.45%   |
| Gigabyte X570              | 1         | 1.45%   |
| Gigabyte X470              | 1         | 1.45%   |
| Gigabyte H77M-D3H          | 1         | 1.45%   |
| Gigabyte H510M             | 1         | 1.45%   |
| Gigabyte G1.Sniper         | 1         | 1.45%   |
| Gigabyte B460M             | 1         | 1.45%   |
| Dell Inspiron              | 1         | 1.45%   |
| AZW SER                    | 1         | 1.45%   |
| ASUS TUF                   | 1         | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 12        | 17.39%  |
| 2022 | 10        | 14.49%  |
| 2021 | 9         | 13.04%  |
| 2019 | 6         | 8.7%    |
| 2012 | 6         | 8.7%    |
| 2016 | 5         | 7.25%   |
| 2017 | 4         | 5.8%    |
| 2023 | 3         | 4.35%   |
| 2018 | 3         | 4.35%   |
| 2015 | 3         | 4.35%   |
| 2014 | 3         | 4.35%   |
| 2013 | 3         | 4.35%   |
| 2011 | 1         | 1.45%   |
| 2010 | 1         | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 34        | 49.28%  |
| Notebook    | 27        | 39.13%  |
| Tablet      | 5         | 7.25%   |
| Convertible | 1         | 1.45%   |
| Mini pc     | 1         | 1.45%   |
| All in one  | 1         | 1.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 69        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 98.55%  |
| Yes  | 1         | 1.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 19        | 27.54%  |
| 16.01-24.0  | 17        | 24.64%  |
| 8.01-16.0   | 12        | 17.39%  |
| 4.01-8.0    | 10        | 14.49%  |
| 3.01-4.0    | 4         | 5.8%    |
| 24.01-32.0  | 4         | 5.8%    |
| 64.01-256.0 | 3         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 31        | 43.66%  |
| 1.01-2.0   | 16        | 22.54%  |
| 3.01-4.0   | 14        | 19.72%  |
| 4.01-8.0   | 9         | 12.68%  |
| 16.01-24.0 | 1         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 47.89%  |
| 2      | 22        | 30.99%  |
| 3      | 10        | 14.08%  |
| 4      | 2         | 2.82%   |
| 8      | 1         | 1.41%   |
| 7      | 1         | 1.41%   |
| 5      | 1         | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 85.51%  |
| Yes       | 10        | 14.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 81.16%  |
| No        | 13        | 18.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 81.16%  |
| No        | 13        | 18.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 76.81%  |
| No        | 16        | 23.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 29        | 42.03%  |
| Germany      | 5         | 7.25%   |
| Brazil       | 4         | 5.8%    |
| UK           | 3         | 4.35%   |
| Italy        | 3         | 4.35%   |
| Australia    | 3         | 4.35%   |
| Spain        | 2         | 2.9%    |
| Saudi Arabia | 2         | 2.9%    |
| Russia       | 2         | 2.9%    |
| Poland       | 2         | 2.9%    |
| Canada       | 2         | 2.9%    |
| Vietnam      | 1         | 1.45%   |
| Switzerland  | 1         | 1.45%   |
| Romania      | 1         | 1.45%   |
| Norway       | 1         | 1.45%   |
| Netherlands  | 1         | 1.45%   |
| Malaysia     | 1         | 1.45%   |
| Macao        | 1         | 1.45%   |
| Japan        | 1         | 1.45%   |
| Hungary      | 1         | 1.45%   |
| Estonia      | 1         | 1.45%   |
| Costa Rica   | 1         | 1.45%   |
| Belgium      | 1         | 1.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Chattanooga              | 2         | 2.86%   |
| Yaroslavl                | 1         | 1.43%   |
| Wroclaw                  | 1         | 1.43%   |
| Wiesbaden                | 1         | 1.43%   |
| Watsonville              | 1         | 1.43%   |
| Warsaw                   | 1         | 1.43%   |
| Virginia Beach           | 1         | 1.43%   |
| Umeda                    | 1         | 1.43%   |
| Tulcea                   | 1         | 1.43%   |
| Toronto                  | 1         | 1.43%   |
| Tallinn                  | 1         | 1.43%   |
| Sydney                   | 1         | 1.43%   |
| Sumaré                  | 1         | 1.43%   |
| Steyning                 | 1         | 1.43%   |
| St Louis                 | 1         | 1.43%   |
| Shelbyville              | 1         | 1.43%   |
| Seattle                  | 1         | 1.43%   |
| Sao Paulo                | 1         | 1.43%   |
| Santa Cruz das Palmeiras | 1         | 1.43%   |
| Sanford                  | 1         | 1.43%   |
| San José                | 1         | 1.43%   |
| Samara                   | 1         | 1.43%   |
| Saltillo                 | 1         | 1.43%   |
| Round Rock               | 1         | 1.43%   |
| Ridley Park              | 1         | 1.43%   |
| Racine                   | 1         | 1.43%   |
| Pittsburg                | 1         | 1.43%   |
| Phoenix                  | 1         | 1.43%   |
| Philadelphia             | 1         | 1.43%   |
| Pennsauken               | 1         | 1.43%   |
| Parma                    | 1         | 1.43%   |
| Newport News             | 1         | 1.43%   |
| New York                 | 1         | 1.43%   |
| Monticello               | 1         | 1.43%   |
| Milan                    | 1         | 1.43%   |
| Melbourne                | 1         | 1.43%   |
| Meissen                  | 1         | 1.43%   |
| Madison                  | 1         | 1.43%   |
| Macao                    | 1         | 1.43%   |
| Longueuil                | 1         | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 17        | 27     | 14.53%  |
| Seagate                      | 14        | 18     | 11.97%  |
| Kingston                     | 12        | 12     | 10.26%  |
| WDC                          | 11        | 14     | 9.4%    |
| Sandisk                      | 8         | 12     | 6.84%   |
| Unknown                      | 6         | 6      | 5.13%   |
| Micron/Crucial Technology    | 6         | 6      | 5.13%   |
| Toshiba                      | 5         | 6      | 4.27%   |
| Phison Electronics           | 5         | 5      | 4.27%   |
| Micron Technology            | 5         | 7      | 4.27%   |
| Intel                        | 4         | 5      | 3.42%   |
| SK hynix                     | 3         | 3      | 2.56%   |
| Crucial                      | 3         | 5      | 2.56%   |
| Silicon Motion               | 2         | 2      | 1.71%   |
| KIOXIA                       | 2         | 2      | 1.71%   |
| Hitachi                      | 2         | 2      | 1.71%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.85%   |
| Netac                        | 1         | 1      | 0.85%   |
| Kingston Technology Company  | 1         | 1      | 0.85%   |
| KingFast                     | 1         | 1      | 0.85%   |
| KingDian                     | 1         | 3      | 0.85%   |
| JMicron Technology           | 1         | 1      | 0.85%   |
| Hewlett-Packard              | 1         | 1      | 0.85%   |
| Fanxiang                     | 1         | 1      | 0.85%   |
| Corsair                      | 1         | 1      | 0.85%   |
| Biwin Storage Technology     | 1         | 1      | 0.85%   |
| ADATA Technology             | 1         | 2      | 0.85%   |
| Unknown                      | 1         | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 7         | 5.56%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 6         | 4.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 4         | 3.17%   |
| Kingston SA400S37120G 120GB SSD                       | 3         | 2.38%   |
| Unknown MMC Card  64GB                                | 2         | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 2         | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB                        | 2         | 1.59%   |
| Samsung SSD 870 QVO 2TB                               | 2         | 1.59%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 2         | 1.59%   |
| Phison E12 NVMe Controller 2TB                        | 2         | 1.59%   |
| Kingston SNVS500G 500GB                               | 2         | 1.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1         | 0.79%   |
| WDC WDBNCE5000PNC 500GB SSD                           | 1         | 0.79%   |
| WDC WD7500BPVT-80HXZT3 752GB                          | 1         | 0.79%   |
| WDC WD5000BEVT-22A0RT0 500GB                          | 1         | 0.79%   |
| WDC WD5000AVDS-63U7B1 500GB                           | 1         | 0.79%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 1         | 0.79%   |
| WDC WD20SPZX-08UA7 2TB                                | 1         | 0.79%   |
| WDC WD20EARX-00PASB0 2TB                              | 1         | 0.79%   |
| WDC WD201KFGX-68BKJN0 20TB                            | 1         | 0.79%   |
| WDC WD1500HLFS-01G6U0 150GB                           | 1         | 0.79%   |
| WDC WD10SPCX-24HWST1 1TB                              | 1         | 0.79%   |
| WDC WD10JPLX-00MBPT0 1TB                              | 1         | 0.79%   |
| Unknown SD/MMC/MS PRO 128GB                           | 1         | 0.79%   |
| Unknown NVMe SSD Drive 1024GB                         | 1         | 0.79%   |
| Unknown MMC Card  512GB                               | 1         | 0.79%   |
| Unknown MMC Card  16GB                                | 1         | 0.79%   |
| Toshiba XG6 NVMe SSD Controller 512GB                 | 1         | 0.79%   |
| Toshiba NVMe Controller 128GB                         | 1         | 0.79%   |
| Toshiba MQ02ABD100H 1TB                               | 1         | 0.79%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 0.79%   |
| Toshiba MK1234GSX 120GB                               | 1         | 0.79%   |
| SK hynix SHGP31-2000GM 2TB                            | 1         | 0.79%   |
| SK hynix PC601 NVMe 256GB                             | 1         | 0.79%   |
| SK hynix HFM512GD3JX016N 512GB                        | 1         | 0.79%   |
| Shenzhen Longsys Lexar SSD NM710 2TB                  | 1         | 0.79%   |
| Seagate ST9500325AS 500GB                             | 1         | 0.79%   |
| Seagate ST9320423AS 320GB                             | 1         | 0.79%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB                  | 1         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB                       | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 16     | 43.33%  |
| WDC                 | 10        | 12     | 33.33%  |
| Toshiba             | 3         | 4      | 10%     |
| Hitachi             | 2         | 2      | 6.67%   |
| Unknown             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 8      | 23.53%  |
| Samsung Electronics | 7         | 11     | 20.59%  |
| SanDisk             | 5         | 7      | 14.71%  |
| Micron Technology   | 3         | 5      | 8.82%   |
| Crucial             | 3         | 5      | 8.82%   |
| WDC                 | 1         | 2      | 2.94%   |
| Seagate             | 1         | 1      | 2.94%   |
| Netac               | 1         | 1      | 2.94%   |
| KingDian            | 1         | 3      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |
| Fanxiang            | 1         | 1      | 2.94%   |
| Corsair             | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 44        | 56     | 43.14%  |
| SSD     | 27        | 47     | 26.47%  |
| HDD     | 23        | 36     | 22.55%  |
| MMC     | 4         | 4      | 3.92%   |
| Unknown | 4         | 4      | 3.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 56     | 46.81%  |
| SATA | 41        | 81     | 43.62%  |
| SAS  | 5         | 6      | 5.32%   |
| MMC  | 4         | 4      | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 48     | 45.28%  |
| 0.51-1.0   | 16        | 17     | 30.19%  |
| 1.01-2.0   | 8         | 10     | 15.09%  |
| 3.01-4.0   | 2         | 5      | 3.77%   |
| 2.01-3.0   | 1         | 1      | 1.89%   |
| 10.01-20.0 | 1         | 1      | 1.89%   |
| 4.01-10.0  | 1         | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 26        | 37.14%  |
| 1001-2000      | 23        | 32.86%  |
| 251-500        | 9         | 12.86%  |
| 501-1000       | 7         | 10%     |
| 2001-3000      | 3         | 4.29%   |
| 101-250        | 2         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 23        | 32.39%  |
| 51-100         | 13        | 18.31%  |
| 101-250        | 11        | 15.49%  |
| 251-500        | 7         | 9.86%   |
| 501-1000       | 5         | 7.04%   |
| More than 3000 | 4         | 5.63%   |
| 1001-2000      | 4         | 5.63%   |
| 2001-3000      | 3         | 4.23%   |
| 1-20           | 1         | 1.41%   |

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
| Detected | 69        | 147    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 37.14%  |
| AMD                          | 18        | 17.14%  |
| Samsung Electronics          | 11        | 10.48%  |
| Micron/Crucial Technology    | 6         | 5.71%   |
| Phison Electronics           | 5         | 4.76%   |
| Kingston Technology Company  | 5         | 4.76%   |
| SanDisk                      | 4         | 3.81%   |
| SK hynix                     | 3         | 2.86%   |
| Toshiba America Info Systems | 2         | 1.9%    |
| Silicon Motion               | 2         | 1.9%    |
| Micron Technology            | 2         | 1.9%    |
| KIOXIA                       | 2         | 1.9%    |
| Biwin Storage Technology     | 2         | 1.9%    |
| Shenzhen Longsys Electronics | 1         | 0.95%   |
| Marvell Technology Group     | 1         | 0.95%   |
| INNOGRIT                     | 1         | 0.95%   |
| ADATA Technology             | 1         | 0.95%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 10.34%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 6.03%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6         | 5.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 5.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 3.45%   |
| Kingston Company NVMe Controller                                               | 3         | 2.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.59%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.59%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 1.72%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.72%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.72%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.72%   |
| Biwin Storage Non-Volatile memory controller                                   | 2         | 1.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.86%   |
| Toshiba America Info Systems XG3 NVMe SSD Controller                           | 1         | 0.86%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.86%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 0.86%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.86%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.86%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.86%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 0.86%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 0.86%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 0.86%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1         | 0.86%   |
| Kingston Company OM3PGP4 NVMe SSD                                              | 1         | 0.86%   |
| Kingston Company NV1 NVMe SSD                                                  | 1         | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 48        | 46.6%   |
| NVMe | 44        | 42.72%  |
| RAID | 8         | 7.77%   |
| IDE  | 3         | 2.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 42        | 60.87%  |
| AMD    | 27        | 39.13%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| AMD Ryzen 7 6800U with Radeon Graphics | 4         | 5.71%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 4         | 5.71%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 2         | 2.86%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz     | 2         | 2.86%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 2         | 2.86%   |
| AMD Ryzen 7 5800U with Radeon Graphics | 2         | 2.86%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 1         | 1.43%   |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz    | 1         | 1.43%   |
| Intel Core m3-8100Y CPU @ 1.10GHz      | 1         | 1.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 1         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.43%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.43%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1         | 1.43%   |
| Intel Core i7-3610QM CPU @ 2.30GHz     | 1         | 1.43%   |
| Intel Core i7-10875H CPU @ 2.30GHz     | 1         | 1.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz     | 1         | 1.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 1         | 1.43%   |
| Intel Core i5-9500T CPU @ 2.20GHz      | 1         | 1.43%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1         | 1.43%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz     | 1         | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 1         | 1.43%   |
| Intel Core i5-4590S CPU @ 3.00GHz      | 1         | 1.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1         | 1.43%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1         | 1.43%   |
| Intel Core i5-4210H CPU @ 2.90GHz      | 1         | 1.43%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 1         | 1.43%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 1         | 1.43%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 1         | 1.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 1         | 1.43%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1         | 1.43%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 1         | 1.43%   |
| Intel Core i3-4160 CPU @ 3.60GHz       | 1         | 1.43%   |
| Intel Core i3-10100F CPU @ 3.60GHz     | 1         | 1.43%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 1         | 1.43%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz  | 1         | 1.43%   |
| Intel Celeron CPU N3350 @ 1.10GHz      | 1         | 1.43%   |
| Intel Atom x7-Z8700 CPU @ 1.60GHz      | 1         | 1.43%   |
| Intel 13th Gen Core i9-13900K          | 1         | 1.43%   |
| Intel 12th Gen Core i7-12700H          | 1         | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 16        | 22.86%  |
| AMD Ryzen 7       | 13        | 18.57%  |
| Intel Core i7     | 10        | 14.29%  |
| AMD Ryzen 5       | 7         | 10%     |
| Other             | 6         | 8.57%   |
| AMD Ryzen 9       | 6         | 8.57%   |
| Intel Core i3     | 4         | 5.71%   |
| Intel Xeon        | 2         | 2.86%   |
| Intel Core m3     | 1         | 1.43%   |
| Intel Core 2 Quad | 1         | 1.43%   |
| Intel Celeron     | 1         | 1.43%   |
| Intel Atom        | 1         | 1.43%   |
| AMD Ryzen 5 PRO   | 1         | 1.43%   |
| AMD A10           | 1         | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 26        | 37.14%  |
| 8      | 16        | 22.86%  |
| 6      | 11        | 15.71%  |
| 2      | 10        | 14.29%  |
| 16     | 2         | 2.86%   |
| 12     | 2         | 2.86%   |
| 24     | 1         | 1.43%   |
| 14     | 1         | 1.43%   |
| 10     | 1         | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 53        | 76.81%  |
| 1      | 16        | 23.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Zen 3       | 14        | 20.29%  |
| Unknown     | 11        | 15.94%  |
| KabyLake    | 10        | 14.49%  |
| Haswell     | 7         | 10.14%  |
| CometLake   | 5         | 7.25%   |
| Skylake     | 4         | 5.8%    |
| Zen+        | 3         | 4.35%   |
| SandyBridge | 3         | 4.35%   |
| IvyBridge   | 3         | 4.35%   |
| Zen         | 2         | 2.9%    |
| TigerLake   | 2         | 2.9%    |
| Silvermont  | 1         | 1.45%   |
| Piledriver  | 1         | 1.45%   |
| Penryn      | 1         | 1.45%   |
| Goldmont    | 1         | 1.45%   |
| Broadwell   | 1         | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 33        | 37.08%  |
| Nvidia | 28        | 31.46%  |
| Intel  | 28        | 31.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 5.56%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 4.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 3.33%   |
| Intel HD Graphics 530                                                       | 3         | 3.33%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3         | 3.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 3.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 2.22%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 2.22%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2.22%   |
| Intel HD Graphics 630                                                       | 2         | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 2.22%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 2         | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2.22%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 1.11%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1         | 1.11%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 1.11%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 1.11%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 1.11%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.11%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 1.11%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                       | 1         | 1.11%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 1.11%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 1.11%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 1.11%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.11%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 1.11%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.11%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 1.11%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                           | 1         | 1.11%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 1.11%   |
| Nvidia GA106 [RTX A2000]                                                    | 1         | 1.11%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1         | 1.11%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1         | 1.11%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1         | 1.11%   |
| Intel UHD Graphics 620                                                      | 1         | 1.11%   |
| Intel UHD Graphics 615                                                      | 1         | 1.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.11%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 1         | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 27        | 38.57%  |
| 1 x Nvidia     | 13        | 18.57%  |
| 1 x Intel      | 12        | 17.14%  |
| Intel + Nvidia | 11        | 15.71%  |
| AMD + Nvidia   | 4         | 5.71%   |
| Intel + AMD    | 2         | 2.86%   |
| Other          | 1         | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 42        | 60.87%  |
| Proprietary | 27        | 39.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 95.65%  |
| 3.01-4.0   | 2         | 2.9%    |
| 8.01-16.0  | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 11        | 16.67%  |
| BOE                  | 9         | 13.64%  |
| Chimei Innolux       | 6         | 9.09%   |
| LG Display           | 4         | 6.06%   |
| MSI                  | 3         | 4.55%   |
| Goldstar             | 3         | 4.55%   |
| BenQ                 | 3         | 4.55%   |
| AU Optronics         | 3         | 4.55%   |
| Toshiba              | 2         | 3.03%   |
| Sony                 | 2         | 3.03%   |
| Sharp                | 2         | 3.03%   |
| ASUSTek Computer     | 2         | 3.03%   |
| Vizio                | 1         | 1.52%   |
| Unknown (XXX)        | 1         | 1.52%   |
| TMX                  | 1         | 1.52%   |
| SANYO                | 1         | 1.52%   |
| PANDA                | 1         | 1.52%   |
| Panasonic            | 1         | 1.52%   |
| Onkyo                | 1         | 1.52%   |
| Insignia             | 1         | 1.52%   |
| Hewlett-Packard      | 1         | 1.52%   |
| Fujitsu Siemens      | 1         | 1.52%   |
| Dell                 | 1         | 1.52%   |
| AYANEO               | 1         | 1.52%   |
| AYA                  | 1         | 1.52%   |
| Ancor Communications | 1         | 1.52%   |
| AGO                  | 1         | 1.52%   |
| Acer                 | 1         | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE TV080WUM-NL0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 2.99%   |
| Vizio D40f-G9 VIZ1027 1920x1080 477x268mm 21.5-inch                  | 1         | 1.49%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch       | 1         | 1.49%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                   | 1         | 1.49%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                    | 1         | 1.49%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 1.49%   |
| Sony TV SNYEE01 1920x1080                                            | 1         | 1.49%   |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                        | 1         | 1.49%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 1.49%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                    | 1         | 1.49%   |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                       | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch | 1         | 1.49%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch  | 1         | 1.49%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch    | 1         | 1.49%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch    | 1         | 1.49%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                    | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM020B 1920x540                     | 1         | 1.49%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch  | 1         | 1.49%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 610x350mm 27.7-inch    | 1         | 1.49%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 1.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.49%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch          | 1         | 1.49%   |
| Onkyo AV Receiver ONK1150 3840x2160 1872x1053mm 84.6-inch            | 1         | 1.49%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch               | 1         | 1.49%   |
| MSI MAG301CR2 MSI3CB4 2560x1080 690x291mm 29.5-inch                  | 1         | 1.49%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                       | 1         | 1.49%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 1.49%   |
| Insignia BBY LCD BBY0032 1920x540                                    | 1         | 1.49%   |
| Hewlett-Packard M24fwa FHD HPN372F 1920x1080 527x296mm 23.8-inch     | 1         | 1.49%   |
| Goldstar TV GSMC0A0 3840x2160                                        | 1         | 1.49%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 1.49%   |
| Goldstar 38GL950G GSM7734 3840x1600 890x388mm 38.2-inch              | 1         | 1.49%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch  | 1         | 1.49%   |
| Dell IN1910N DELA04C 1366x768 410x230mm 18.5-inch                    | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 48.44%  |
| 3840x2160 (4K)     | 7         | 10.94%  |
| 2560x1440 (QHD)    | 6         | 9.38%   |
| 1366x768 (WXGA)    | 6         | 9.38%   |
| 1200x1920          | 3         | 4.69%   |
| 1920x540           | 2         | 3.13%   |
| 1600x2560          | 2         | 3.13%   |
| 800x1280           | 1         | 1.56%   |
| 3840x1600          | 1         | 1.56%   |
| 3840x1080          | 1         | 1.56%   |
| 3440x1440          | 1         | 1.56%   |
| 2560x1080          | 1         | 1.56%   |
| 1920x1200 (WUXGA)  | 1         | 1.56%   |
| 1680x1050 (WSXGA+) | 1         | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 21.21%  |
| Unknown | 6         | 9.09%   |
| 27      | 5         | 7.58%   |
| 24      | 4         | 6.06%   |
| 23      | 4         | 6.06%   |
| 17      | 4         | 6.06%   |
| 84      | 3         | 4.55%   |
| 72      | 3         | 4.55%   |
| 14      | 3         | 4.55%   |
| 48      | 2         | 3.03%   |
| 8       | 2         | 3.03%   |
| 74      | 1         | 1.52%   |
| 54      | 1         | 1.52%   |
| 52      | 1         | 1.52%   |
| 49      | 1         | 1.52%   |
| 46      | 1         | 1.52%   |
| 40      | 1         | 1.52%   |
| 38      | 1         | 1.52%   |
| 34      | 1         | 1.52%   |
| 29      | 1         | 1.52%   |
| 26      | 1         | 1.52%   |
| 22      | 1         | 1.52%   |
| 21      | 1         | 1.52%   |
| 18      | 1         | 1.52%   |
| 16      | 1         | 1.52%   |
| 12      | 1         | 1.52%   |
| 11      | 1         | 1.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 25.76%  |
| 501-600     | 13        | 19.7%   |
| 1501-2000   | 6         | 9.09%   |
| 1001-1500   | 6         | 9.09%   |
| Unknown     | 6         | 9.09%   |
| 351-400     | 5         | 7.58%   |
| 601-700     | 3         | 4.55%   |
| 401-500     | 3         | 4.55%   |
| 801-900     | 2         | 3.03%   |
| 201-300     | 2         | 3.03%   |
| 101-200     | 2         | 3.03%   |
| 701-800     | 1         | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 73.44%  |
| 0.62  | 6         | 9.38%   |
| 16/10 | 4         | 6.25%   |
| 21/9  | 3         | 4.69%   |
| 32/9  | 2         | 3.13%   |
| 4/3   | 1         | 1.56%   |
| 1.96  | 1         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 23.44%  |
| More than 1000 | 9         | 14.06%  |
| 201-250        | 9         | 14.06%  |
| 301-350        | 7         | 10.94%  |
| Unknown        | 6         | 9.38%   |
| 501-1000       | 5         | 7.81%   |
| 121-130        | 4         | 6.25%   |
| 81-90          | 3         | 4.69%   |
| 1-40           | 2         | 3.13%   |
| 71-80          | 1         | 1.56%   |
| 51-60          | 1         | 1.56%   |
| 351-500        | 1         | 1.56%   |
| 141-150        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 21        | 31.82%  |
| 121-160       | 16        | 24.24%  |
| 101-120       | 9         | 13.64%  |
| 1-50          | 6         | 9.09%   |
| Unknown       | 6         | 9.09%   |
| 161-240       | 5         | 7.58%   |
| More than 240 | 3         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 87.14%  |
| 2     | 7         | 10%     |
| 0     | 2         | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 36        | 33.33%  |
| Intel                           | 36        | 33.33%  |
| MediaTek                        | 12        | 11.11%  |
| Qualcomm Atheros                | 10        | 9.26%   |
| Broadcom                        | 3         | 2.78%   |
| TP-Link                         | 2         | 1.85%   |
| Marvell Technology Group        | 2         | 1.85%   |
| Ralink Technology               | 1         | 0.93%   |
| Ralink                          | 1         | 0.93%   |
| Qualcomm Atheros Communications | 1         | 0.93%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.93%   |
| Microsoft                       | 1         | 0.93%   |
| Edimax Technology               | 1         | 0.93%   |
| Broadcom Limited                | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 24        | 19.51%  |
| Realtek RTL8125 2.5GbE Controller                                                    | 8         | 6.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 7         | 5.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 6         | 4.88%   |
| Intel Ethernet Connection I217-LM                                                    | 4         | 3.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 3         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 3         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 3         | 2.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                                  | 3         | 2.44%   |
| Intel I211 Gigabit Network Connection                                                | 3         | 2.44%   |
| Intel Ethernet Controller I225-V                                                     | 3         | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2         | 1.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 1.63%   |
| Intel Wireless 7265                                                                  | 2         | 1.63%   |
| Intel Wireless 3165                                                                  | 2         | 1.63%   |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 1.63%   |
| Intel Ethernet Connection (2) I219-V                                                 | 2         | 1.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 2         | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 2         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 2         | 1.63%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 0.81%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 0.81%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 0.81%   |
| Realtek PCIe GbE Family Controller                                                   | 1         | 0.81%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                            | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                            | 1         | 0.81%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 0.81%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:5A38C392                                           | 1         | 0.81%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 40.98%  |
| MediaTek                        | 12        | 19.67%  |
| Qualcomm Atheros                | 7         | 11.48%  |
| Realtek Semiconductor           | 6         | 9.84%   |
| TP-Link                         | 2         | 3.28%   |
| Broadcom                        | 2         | 3.28%   |
| Ralink Technology               | 1         | 1.64%   |
| Ralink                          | 1         | 1.64%   |
| Qualcomm Atheros Communications | 1         | 1.64%   |
| Microsoft                       | 1         | 1.64%   |
| Marvell Technology Group        | 1         | 1.64%   |
| Edimax Technology               | 1         | 1.64%   |
| Broadcom Limited                | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 7         | 10.77%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 6         | 9.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 3         | 4.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 3         | 4.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 3         | 4.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3         | 4.62%   |
| Intel Wi-Fi 6 AX200                                                                  | 3         | 4.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 3.08%   |
| Intel Wireless 7265                                                                  | 2         | 3.08%   |
| Intel Wireless 3165                                                                  | 2         | 3.08%   |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 2         | 3.08%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 2         | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 3.08%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 1.54%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 1.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 1.54%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 1.54%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 1.54%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 1.54%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 1.54%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 1         | 1.54%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                    | 1         | 1.54%   |
| Intel Wireless-AC 9260                                                               | 1         | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 1         | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 1         | 1.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                     | 1         | 1.54%   |
| Edimax Wi-Fi                                                                         | 1         | 1.54%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                           | 1         | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1         | 1.54%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                                   | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 60.71%  |
| Intel                    | 17        | 30.36%  |
| Qualcomm Atheros         | 3         | 5.36%   |
| Marvell Technology Group | 1         | 1.79%   |
| Broadcom                 | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 42.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 14.04%  |
| Intel Ethernet Connection I217-LM                                 | 4         | 7.02%   |
| Intel I211 Gigabit Network Connection                             | 3         | 5.26%   |
| Intel Ethernet Controller I225-V                                  | 3         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.51%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.51%   |
| Realtek PCIe GbE Family Controller                                | 1         | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.75%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 49.55%  |
| Ethernet | 55        | 49.55%  |
| Unknown  | 1         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 62.5%   |
| Ethernet | 27        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35        | 50.72%  |
| 1     | 32        | 46.38%  |
| 3     | 2         | 2.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 67.14%  |
| Yes  | 23        | 32.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 45.28%  |
| MediaTek                        | 8         | 15.09%  |
| Cambridge Silicon Radio         | 5         | 9.43%   |
| Lite-On Technology              | 4         | 7.55%   |
| IMC Networks                    | 4         | 7.55%   |
| Qualcomm Atheros Communications | 2         | 3.77%   |
| ASUSTek Computer                | 2         | 3.77%   |
| TP-Link                         | 1         | 1.89%   |
| Realtek Semiconductor           | 1         | 1.89%   |
| Foxconn / Hon Hai               | 1         | 1.89%   |
| Apple                           | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| MediaTek Wireless_Device                            | 8         | 14.81%  |
| Intel AX210 Bluetooth                               | 6         | 11.11%  |
| Intel Bluetooth wireless interface                  | 5         | 9.26%   |
| Intel AX201 Bluetooth                               | 5         | 9.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 9.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.7%    |
| Intel AX200 Bluetooth                               | 2         | 3.7%    |
| IMC Networks Wireless_Device                        | 2         | 3.7%    |
| IMC Networks Bluetooth Radio                        | 2         | 3.7%    |
| TP-Link UB500 Adapter                               | 1         | 1.85%   |
| Realtek Bluetooth Radio                             | 1         | 1.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.85%   |
| Lite-On Wireless_Device                             | 1         | 1.85%   |
| Lite-On Bluetooth Device                            | 1         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.85%   |
| Intel Bluetooth Device                              | 1         | 1.85%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.85%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 1.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.85%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 41        | 35.96%  |
| AMD                      | 37        | 32.46%  |
| Nvidia                   | 21        | 18.42%  |
| Logitech                 | 3         | 2.63%   |
| Sony                     | 2         | 1.75%   |
| Texas Instruments        | 1         | 0.88%   |
| SteelSeries ApS          | 1         | 0.88%   |
| Razer USA                | 1         | 0.88%   |
| Micro Star International | 1         | 0.88%   |
| Kingston Technology      | 1         | 0.88%   |
| Hewlett-Packard          | 1         | 0.88%   |
| Generalplus Technology   | 1         | 0.88%   |
| Focusrite-Novation       | 1         | 0.88%   |
| ASUSTek Computer         | 1         | 0.88%   |
| Astro Gaming             | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 16        | 11.19%  |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 4.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 4.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 4.2%    |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 3.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.5%    |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 3.5%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 3.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 2.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 2.1%    |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.4%    |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 1.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.4%    |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 1.4%    |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.4%    |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.4%    |
| AMD Navi 31 HDMI/DP Audio                                                  | 2         | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.4%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.4%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.7%    |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1         | 0.7%    |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.7%    |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.7%    |
| Razer USA Razer Seiren Mini                                                | 1         | 0.7%    |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.7%    |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.7%    |
| Micro Star International USB Audio                                         | 1         | 0.7%    |
| Logitech Yeti X                                                            | 1         | 0.7%    |
| Logitech Logitech USB Microphone                                           | 1         | 0.7%    |

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
| Chicony Electronics           | 9         | 34.62%  |
| Microdia                      | 4         | 15.38%  |
| IMC Networks                  | 4         | 15.38%  |
| Quanta                        | 2         | 7.69%   |
| YT-221117-J                   | 1         | 3.85%   |
| Sunplus Innovation Technology | 1         | 3.85%   |
| Silicon Motion                | 1         | 3.85%   |
| Logitech                      | 1         | 3.85%   |
| Bison Electronics             | 1         | 3.85%   |
| Apple                         | 1         | 3.85%   |
| Acer                          | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| IMC Networks Integrated Camera    | 3         | 11.54%  |
| Chicony Integrated Camera         | 2         | 7.69%   |
| YT-221117-J USB2.0 Camera         | 1         | 3.85%   |
| Sunplus HD WebCam                 | 1         | 3.85%   |
| Silicon Motion 300k Pixel Camera  | 1         | 3.85%   |
| Quanta HP HD Camera               | 1         | 3.85%   |
| Quanta HD User Facing             | 1         | 3.85%   |
| Microdia Webcam Vitade AF         | 1         | 3.85%   |
| Microdia USB Camera               | 1         | 3.85%   |
| Microdia Integrated_Webcam_FHD    | 1         | 3.85%   |
| Microdia HP Webcam                | 1         | 3.85%   |
| Logitech Webcam C200              | 1         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 3.85%   |
| Chicony USB2.0 FHD Camera         | 1         | 3.85%   |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 3.85%   |
| Chicony Integrated IR Camera      | 1         | 3.85%   |
| Chicony HP Wide Vision HD Camera  | 1         | 3.85%   |
| Chicony HP Truevision HD          | 1         | 3.85%   |
| Chicony HD User Facing            | 1         | 3.85%   |
| Chicony EasyCamera                | 1         | 3.85%   |
| Bison Lenovo EasyCamera           | 1         | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X   | 1         | 3.85%   |
| Acer Lenovo EasyCamera            | 1         | 3.85%   |

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
| 0     | 57        | 82.61%  |
| 1     | 12        | 17.39%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 5         | 41.67%  |
| Graphics card         | 2         | 16.67%  |
| Fingerprint reader    | 2         | 16.67%  |
| Storage/nvme          | 1         | 8.33%   |
| Network               | 1         | 8.33%   |
| Net/wireless          | 1         | 8.33%   |


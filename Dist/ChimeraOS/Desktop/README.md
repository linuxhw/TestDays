ChimeraOS - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 100

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI       | PRO B650-P WIFI             | [544a799ce8](https://linux-hardware.org/?probe=544a799ce8) | Jan 02, 2024 |
| ASRock    | Z77 Professional            | [d1d9fce85d](https://linux-hardware.org/?probe=d1d9fce85d) | Jan 01, 2024 |
| ASUSTek   | ROG STRIX B650-A GAMING ... | [dffaa09f84](https://linux-hardware.org/?probe=dffaa09f84) | Dec 29, 2023 |
| Dell      | 07WP95 A02                  | [b5d957b7ec](https://linux-hardware.org/?probe=b5d957b7ec) | Dec 12, 2023 |
| Gigabyte  | 970A-DS3P                   | [ea510ad39c](https://linux-hardware.org/?probe=ea510ad39c) | Dec 09, 2023 |
| Gigabyte  | H81M-H                      | [108ddf7f8e](https://linux-hardware.org/?probe=108ddf7f8e) | Dec 07, 2023 |
| Dell      | 07HXY6 A01                  | [37ba613bd3](https://linux-hardware.org/?probe=37ba613bd3) | Dec 01, 2023 |
| Dell      | 0T0MHW A03                  | [91cd726063](https://linux-hardware.org/?probe=91cd726063) | Nov 30, 2023 |
| ASUSTek   | PRIME X370-A                | [491dd5c51b](https://linux-hardware.org/?probe=491dd5c51b) | Nov 28, 2023 |
| Gigabyte  | A520I AC                    | [9672d50090](https://linux-hardware.org/?probe=9672d50090) | Nov 28, 2023 |
| ASUSTek   | TUF Gaming B450M-PRO S      | [606a157eb4](https://linux-hardware.org/?probe=606a157eb4) | Nov 24, 2023 |
| Dell      | 03KWTV A00                  | [f641738a49](https://linux-hardware.org/?probe=f641738a49) | Nov 23, 2023 |
| ASUSTek   | PRIME B560M-A               | [4048fd2631](https://linux-hardware.org/?probe=4048fd2631) | Nov 22, 2023 |
| Gigabyte  | A520M H                     | [abba035964](https://linux-hardware.org/?probe=abba035964) | Nov 19, 2023 |
| ASRock    | Z87 Extreme4                | [84a46af7ee](https://linux-hardware.org/?probe=84a46af7ee) | Nov 19, 2023 |
| Gigabyte  | B550I AORUS PRO AX          | [694b0754fa](https://linux-hardware.org/?probe=694b0754fa) | Nov 18, 2023 |
| Dell      | 0DY62R A01                  | [03f9c7a1f2](https://linux-hardware.org/?probe=03f9c7a1f2) | Nov 17, 2023 |
| HP        | 8464                        | [2eae0556b2](https://linux-hardware.org/?probe=2eae0556b2) | Nov 16, 2023 |
| MSI       | B550-A PRO                  | [10e26870d7](https://linux-hardware.org/?probe=10e26870d7) | Nov 13, 2023 |
| Gigabyte  | B550I AORUS PRO AX          | [b15037e662](https://linux-hardware.org/?probe=b15037e662) | Nov 11, 2023 |
| ASUSTek   | TUF Gaming B550M-PLUS       | [2c921ede59](https://linux-hardware.org/?probe=2c921ede59) | Nov 08, 2023 |
| ASRock    | B550M-HDV                   | [6f0980a8f2](https://linux-hardware.org/?probe=6f0980a8f2) | Nov 07, 2023 |
| MSI       | B550-A PRO                  | [3333de3c07](https://linux-hardware.org/?probe=3333de3c07) | Nov 06, 2023 |
| ASRock    | B550M-HDV                   | [e005a7da3a](https://linux-hardware.org/?probe=e005a7da3a) | Nov 06, 2023 |
| Gigabyte  | B450M S2H                   | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| Gigabyte  | B450M S2H                   | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| Gigabyte  | B550I AORUS PRO AX          | [9f47c70860](https://linux-hardware.org/?probe=9f47c70860) | Nov 04, 2023 |
| Dell      | 01NP3N A00                  | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte  | B550I AORUS PRO AX          | [e073d8c90a](https://linux-hardware.org/?probe=e073d8c90a) | Nov 03, 2023 |
| Gigabyte  | H61M-DS2                    | [877ab8782b](https://linux-hardware.org/?probe=877ab8782b) | Nov 01, 2023 |
| MSI       | B450 GAMING PLUS            | [d7fb2de5a7](https://linux-hardware.org/?probe=d7fb2de5a7) | Oct 30, 2023 |
| ASUSTek   | H110M-A                     | [a58f65d857](https://linux-hardware.org/?probe=a58f65d857) | Oct 27, 2023 |
| ASUSTek   | Z170-A                      | [480f22e1b7](https://linux-hardware.org/?probe=480f22e1b7) | Oct 24, 2023 |
| Gigabyte  | X570 I AORUS PRO WIFI       | [6d454c05e2](https://linux-hardware.org/?probe=6d454c05e2) | Oct 21, 2023 |
| Gigabyte  | X570 I AORUS PRO WIFI       | [6cc2145e11](https://linux-hardware.org/?probe=6cc2145e11) | Oct 21, 2023 |
| GMKtec    | NucBox K4                   | [b0f8dc54f3](https://linux-hardware.org/?probe=b0f8dc54f3) | Oct 20, 2023 |
| AZW       | SER V1                      | [eca53f2271](https://linux-hardware.org/?probe=eca53f2271) | Oct 18, 2023 |
| Gigabyte  | B550M AORUS PRO-P           | [257a13e71a](https://linux-hardware.org/?probe=257a13e71a) | Oct 02, 2023 |
| Gigabyte  | A520I AC                    | [48f4eb15cc](https://linux-hardware.org/?probe=48f4eb15cc) | Oct 02, 2023 |
| ASRock    | A320M-HDV                   | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| ASUSTek   | SABERTOOTH Z170 MARK 1      | [27d1633bc3](https://linux-hardware.org/?probe=27d1633bc3) | Sep 11, 2023 |
| HP        | 18E7                        | [1b966d0110](https://linux-hardware.org/?probe=1b966d0110) | Sep 11, 2023 |
| HP        | 89B5 A                      | [4934bfa1a8](https://linux-hardware.org/?probe=4934bfa1a8) | Sep 09, 2023 |
| ASUSTek   | GD30CI                      | [f1c877be0e](https://linux-hardware.org/?probe=f1c877be0e) | Sep 05, 2023 |
| Gigabyte  | Z490 GAMING X AX y.y        | [94a6d62c4b](https://linux-hardware.org/?probe=94a6d62c4b) | Aug 28, 2023 |
| Dell      | 04Y8V0 A02                  | [5afb05e780](https://linux-hardware.org/?probe=5afb05e780) | Aug 27, 2023 |
| ASRock    | B550M-ITX/ac                | [64aa93e41b](https://linux-hardware.org/?probe=64aa93e41b) | Aug 14, 2023 |
| ASUSTek   | TUF B450M-PLUS GAMING       | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| Dell      | 05YDCW A01                  | [3f3195be63](https://linux-hardware.org/?probe=3f3195be63) | Aug 12, 2023 |
| Dell      | 05YDCW A01                  | [80c27f0ac1](https://linux-hardware.org/?probe=80c27f0ac1) | Aug 12, 2023 |
| Gigabyte  | B550I AORUS PRO AX          | [b1b6854522](https://linux-hardware.org/?probe=b1b6854522) | Jul 29, 2023 |
| ASRock    | H97M Anniversary            | [f8a02ab68e](https://linux-hardware.org/?probe=f8a02ab68e) | Jul 27, 2023 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [c8a41127a9](https://linux-hardware.org/?probe=c8a41127a9) | Jul 23, 2023 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [9186fec300](https://linux-hardware.org/?probe=9186fec300) | Jul 23, 2023 |
| ASUSTek   | STRIX Z270F GAMING          | [80e44d8594](https://linux-hardware.org/?probe=80e44d8594) | Jul 22, 2023 |
| Gigabyte  | B450 AORUS PRO WIFI-CF      | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| Acer      | Veriton X6610G              | [e1189e3406](https://linux-hardware.org/?probe=e1189e3406) | Jul 13, 2023 |
| Dell      | 0KC9NP A01                  | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell      | 0KC9NP A01                  | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| HP        | 1791                        | [a2bf914a45](https://linux-hardware.org/?probe=a2bf914a45) | Jul 08, 2023 |
| ASUSTek   | PRIME B550-PLUS             | [13195d7ff3](https://linux-hardware.org/?probe=13195d7ff3) | Jul 02, 2023 |
| HP        | 1998                        | [91f6e54877](https://linux-hardware.org/?probe=91f6e54877) | Jun 30, 2023 |
| Gigabyte  | G1.Sniper A88X-CF           | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Dell      | 02YYK5 A01                  | [50efda9604](https://linux-hardware.org/?probe=50efda9604) | Jun 19, 2023 |
| Gigabyte  | B450 AORUS M                | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| Dell      | 07HXY6 A01                  | [ec3adcbe42](https://linux-hardware.org/?probe=ec3adcbe42) | Jun 16, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [c6401638dd](https://linux-hardware.org/?probe=c6401638dd) | Jun 11, 2023 |
| Gigabyte  | B550I AORUS PRO AX          | [798d8e8914](https://linux-hardware.org/?probe=798d8e8914) | Jun 11, 2023 |
| MSI       | MPG B650I EDGE WIFI         | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [8c6370ac0d](https://linux-hardware.org/?probe=8c6370ac0d) | May 23, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [41b69ae4db](https://linux-hardware.org/?probe=41b69ae4db) | May 12, 2023 |
| ASUSTek   | PRIME B760-PLUS D4          | [bb01d9e92b](https://linux-hardware.org/?probe=bb01d9e92b) | May 12, 2023 |
| ASUSTek   | ROG STRIX B460-I GAMING     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [bf3fee03d2](https://linux-hardware.org/?probe=bf3fee03d2) | May 09, 2023 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [ad66608cf0](https://linux-hardware.org/?probe=ad66608cf0) | May 08, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [101ec0a833](https://linux-hardware.org/?probe=101ec0a833) | May 05, 2023 |
| ASUSTek   | PRIME B760-PLUS D4          | [4ec161ab9b](https://linux-hardware.org/?probe=4ec161ab9b) | May 04, 2023 |
| Dell      | 0FDY5C A00                  | [a6865b8591](https://linux-hardware.org/?probe=a6865b8591) | Apr 16, 2023 |
| ASUSTek   | ROG STRIX B460-I GAMING     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| ASUSTek   | ROG STRIX B650E-I GAMING... | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek   | ROG STRIX B650E-I GAMING... | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| MACHINIST | X99-RS9 V2.0                | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| Gigabyte  | B460M DS3H AC V2-Y1         | [b21cd49226](https://linux-hardware.org/?probe=b21cd49226) | Mar 16, 2023 |
| MSI       | MPG B650I EDGE WIFI         | [9f40b861a5](https://linux-hardware.org/?probe=9f40b861a5) | Mar 12, 2023 |
| Gigabyte  | B460M DS3H AC V2-Y1         | [7f8fc2ba96](https://linux-hardware.org/?probe=7f8fc2ba96) | Mar 10, 2023 |
| Dell      | 0XHGV1 A00                  | [8fa504e81f](https://linux-hardware.org/?probe=8fa504e81f) | Mar 07, 2023 |
| Intel     | DB75EN AAG39650-400         | [4a0feca3f5](https://linux-hardware.org/?probe=4a0feca3f5) | Mar 02, 2023 |
| Gigabyte  | H77M-D3H                    | [01eb743492](https://linux-hardware.org/?probe=01eb743492) | Feb 25, 2023 |
| Gigabyte  | H77M-D3H                    | [766790f373](https://linux-hardware.org/?probe=766790f373) | Feb 25, 2023 |
| ASUSTek   | B150I PRO GAMING/WIFI/AU... | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| HP        | 1998                        | [dbb952f3f6](https://linux-hardware.org/?probe=dbb952f3f6) | Feb 13, 2023 |
| HP        | 1998                        | [0171575a1d](https://linux-hardware.org/?probe=0171575a1d) | Feb 13, 2023 |
| Gigabyte  | H510M H                     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| ASUSTek   | P8H61-MX R2.0               | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Gigabyte  | X570S AORUS ELITE AX        | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte  | X570S AORUS ELITE AX        | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| Gigabyte  | X570 AORUS ELITE WIFI       | [49ca01435b](https://linux-hardware.org/?probe=49ca01435b) | Dec 27, 2022 |
| Lenovo    | ThinkCentre M70e 0832B1U    | [d95663a632](https://linux-hardware.org/?probe=d95663a632) | Dec 07, 2022 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [2a7b6d570f](https://linux-hardware.org/?probe=2a7b6d570f) | Nov 26, 2022 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [58b3db6784](https://linux-hardware.org/?probe=58b3db6784) | Nov 23, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| ChimeraOS 44-1 | 31       | 39.74%  |
| ChimeraOS 43-1 | 11       | 14.1%   |
| ChimeraOS 42   | 8        | 10.26%  |
| ChimeraOS 43   | 7        | 8.97%   |
| ChimeraOS 39   | 7        | 8.97%   |
| ChimeraOS 41   | 4        | 5.13%   |
| ChimeraOS 38   | 4        | 5.13%   |
| ChimeraOS 44   | 3        | 3.85%   |
| ChimeraOS 37   | 3        | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ChimeraOS | 76       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.5.6-chos1-chimeraos-1 | 30       | 37.97%  |
| 6.3.9-chimeraos-1       | 17       | 21.52%  |
| 6.1.27-1-lts            | 8        | 10.13%  |
| 6.1.11-arch1-1          | 7        | 8.86%   |
| 6.1.21-1-lts            | 4        | 5.06%   |
| 6.1.1-arch1-1           | 4        | 5.06%   |
| 6.5.3-chos1-chimeraos-1 | 3        | 3.8%    |
| 6.0.8-arch1-1           | 3        | 3.8%    |
| 6.6.6-arch1-1           | 1        | 1.27%   |
| 6.3.3-arch1-1           | 1        | 1.27%   |
| 6.3.1-arch2-1           | 1        | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5.6   | 30       | 37.97%  |
| 6.3.9   | 17       | 21.52%  |
| 6.1.27  | 8        | 10.13%  |
| 6.1.11  | 7        | 8.86%   |
| 6.1.21  | 4        | 5.06%   |
| 6.1.1   | 4        | 5.06%   |
| 6.5.3   | 3        | 3.8%    |
| 6.0.8   | 3        | 3.8%    |
| 6.6.6   | 1        | 1.27%   |
| 6.3.3   | 1        | 1.27%   |
| 6.3.1   | 1        | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5     | 33       | 42.86%  |
| 6.1     | 22       | 28.57%  |
| 6.3     | 18       | 23.38%  |
| 6.0     | 3        | 3.9%    |
| 6.6     | 1        | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 76       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 75       | 98.68%  |
| steamos | 1        | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 72       | 94.74%  |
| X11     | 4        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 76       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 66       | 86.84%  |
| de_DE | 3        | 3.95%   |
| es_ES | 2        | 2.63%   |
| pt_BR | 1        | 1.32%   |
| ja_JP | 1        | 1.32%   |
| fr_FR | 1        | 1.32%   |
| es_AR | 1        | 1.32%   |
| en_GB | 1        | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 76       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 76       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 76       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 23       | 30.26%  |
| ASUSTek Computer    | 19       | 25%     |
| Dell                | 12       | 15.79%  |
| Hewlett-Packard     | 6        | 7.89%   |
| ASRock              | 6        | 7.89%   |
| MSI                 | 4        | 5.26%   |
| MACHINIST           | 1        | 1.32%   |
| Lenovo              | 1        | 1.32%   |
| Intel               | 1        | 1.32%   |
| GMKtec              | 1        | 1.32%   |
| AZW                 | 1        | 1.32%   |
| Acer                | 1        | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Gigabyte B550I AORUS PRO AX               | 4        | 5.26%   |
| Dell OptiPlex 3060                        | 3        | 3.95%   |
| HP EliteDesk 800 G1 SFF                   | 2        | 2.63%   |
| Gigabyte A520I AC                         | 2        | 2.63%   |
| Dell OptiPlex 5055 Ryzen APU              | 2        | 2.63%   |
| Dell OptiPlex 3070                        | 2        | 2.63%   |
| ASUS ROG STRIX B550-F GAMING              | 2        | 2.63%   |
| MSI MS-7D78                               | 1        | 1.32%   |
| MSI MS-7D73                               | 1        | 1.32%   |
| MSI MS-7C56                               | 1        | 1.32%   |
| MSI MS-7B86                               | 1        | 1.32%   |
| MACHINIST X99-RS9 V2.0                    | 1        | 1.32%   |
| Lenovo ThinkCentre M70e 0832B1U           | 1        | 1.32%   |
| Intel DB75EN AAG39650-400                 | 1        | 1.32%   |
| HP Z220 SFF Workstation                   | 1        | 1.32%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx | 1        | 1.32%   |
| HP ProDesk 600 G1 SFF                     | 1        | 1.32%   |
| HP EliteDesk 705 G4 DM 35W                | 1        | 1.32%   |
| GMKtec NucBox K4                          | 1        | 1.32%   |
| Gigabyte Z490 GAMING X AX                 | 1        | 1.32%   |
| Gigabyte X570S AORUS ELITE AX             | 1        | 1.32%   |
| Gigabyte X570 I AORUS PRO WIFI            | 1        | 1.32%   |
| Gigabyte X570 AORUS ELITE WIFI            | 1        | 1.32%   |
| Gigabyte X470 AORUS GAMING 5 WIFI         | 1        | 1.32%   |
| Gigabyte H81M-H                           | 1        | 1.32%   |
| Gigabyte H77M-D3H                         | 1        | 1.32%   |
| Gigabyte H61M-DS2                         | 1        | 1.32%   |
| Gigabyte H510M H                          | 1        | 1.32%   |
| Gigabyte G1.Sniper A88X-CF                | 1        | 1.32%   |
| Gigabyte B550M AORUS PRO-P                | 1        | 1.32%   |
| Gigabyte B460M DS3H AC V2-Y1              | 1        | 1.32%   |
| Gigabyte B450M S2H                        | 1        | 1.32%   |
| Gigabyte B450 AORUS PRO WIFI              | 1        | 1.32%   |
| Gigabyte B450 AORUS M                     | 1        | 1.32%   |
| Gigabyte A520M H                          | 1        | 1.32%   |
| Gigabyte 970A-DS3P                        | 1        | 1.32%   |
| Dell Precision 3240 Compact               | 1        | 1.32%   |
| Dell OptiPlex 9020                        | 1        | 1.32%   |
| Dell OptiPlex 7050                        | 1        | 1.32%   |
| Dell OptiPlex 7020                        | 1        | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 11       | 14.47%  |
| ASUS ROG           | 5        | 6.58%   |
| Gigabyte B550I     | 4        | 5.26%   |
| ASUS PRIME         | 4        | 5.26%   |
| HP EliteDesk       | 3        | 3.95%   |
| ASUS TUF           | 3        | 3.95%   |
| Gigabyte X570      | 2        | 2.63%   |
| Gigabyte B450      | 2        | 2.63%   |
| Gigabyte A520I     | 2        | 2.63%   |
| MSI MS-7D78        | 1        | 1.32%   |
| MSI MS-7D73        | 1        | 1.32%   |
| MSI MS-7C56        | 1        | 1.32%   |
| MSI MS-7B86        | 1        | 1.32%   |
| MACHINIST X99-RS9  | 1        | 1.32%   |
| Lenovo ThinkCentre | 1        | 1.32%   |
| Intel DB75EN       | 1        | 1.32%   |
| HP Z220            | 1        | 1.32%   |
| HP Victus          | 1        | 1.32%   |
| HP ProDesk         | 1        | 1.32%   |
| GMKtec NucBox      | 1        | 1.32%   |
| Gigabyte Z490      | 1        | 1.32%   |
| Gigabyte X570S     | 1        | 1.32%   |
| Gigabyte X470      | 1        | 1.32%   |
| Gigabyte H81M-H    | 1        | 1.32%   |
| Gigabyte H77M-D3H  | 1        | 1.32%   |
| Gigabyte H61M-DS2  | 1        | 1.32%   |
| Gigabyte H510M     | 1        | 1.32%   |
| Gigabyte G1.Sniper | 1        | 1.32%   |
| Gigabyte B550M     | 1        | 1.32%   |
| Gigabyte B460M     | 1        | 1.32%   |
| Gigabyte B450M     | 1        | 1.32%   |
| Gigabyte A520M     | 1        | 1.32%   |
| Gigabyte 970A-DS3P | 1        | 1.32%   |
| Dell Precision     | 1        | 1.32%   |
| AZW SER            | 1        | 1.32%   |
| ASUS Z170-A        | 1        | 1.32%   |
| ASUS STRIX         | 1        | 1.32%   |
| ASUS SABERTOOTH    | 1        | 1.32%   |
| ASUS P8H61-MX      | 1        | 1.32%   |
| ASUS H110M-A       | 1        | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 18       | 23.68%  |
| 2021 | 9        | 11.84%  |
| 2018 | 9        | 11.84%  |
| 2013 | 7        | 9.21%   |
| 2012 | 6        | 7.89%   |
| 2019 | 5        | 6.58%   |
| 2023 | 4        | 5.26%   |
| 2022 | 4        | 5.26%   |
| 2017 | 4        | 5.26%   |
| 2016 | 3        | 3.95%   |
| 2015 | 3        | 3.95%   |
| 2014 | 2        | 2.63%   |
| 2011 | 1        | 1.32%   |
| 2010 | 1        | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 76       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 76       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 76       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 24       | 31.58%  |
| 32.01-64.0  | 22       | 28.95%  |
| 4.01-8.0    | 11       | 14.47%  |
| 8.01-16.0   | 9        | 11.84%  |
| 24.01-32.0  | 8        | 10.53%  |
| 64.01-256.0 | 2        | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 25       | 32.05%  |
| 1.01-2.0   | 24       | 30.77%  |
| 4.01-8.0   | 14       | 17.95%  |
| 3.01-4.0   | 14       | 17.95%  |
| 16.01-24.0 | 1        | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 43.59%  |
| 2      | 18       | 23.08%  |
| 3      | 16       | 20.51%  |
| 4      | 5        | 6.41%   |
| 5      | 3        | 3.85%   |
| 8      | 1        | 1.28%   |
| 7      | 1        | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 80.26%  |
| Yes       | 15       | 19.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 47       | 61.84%  |
| No        | 29       | 38.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 56.58%  |
| No        | 33       | 43.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 33       | 43.42%  |
| Germany     | 7        | 9.21%   |
| UK          | 5        | 6.58%   |
| Brazil      | 5        | 6.58%   |
| Australia   | 4        | 5.26%   |
| Russia      | 3        | 3.95%   |
| Spain       | 2        | 2.63%   |
| Japan       | 2        | 2.63%   |
| France      | 2        | 2.63%   |
| Canada      | 2        | 2.63%   |
| Vietnam     | 1        | 1.32%   |
| Turkey      | 1        | 1.32%   |
| Poland      | 1        | 1.32%   |
| Norway      | 1        | 1.32%   |
| New Zealand | 1        | 1.32%   |
| Malaysia    | 1        | 1.32%   |
| Iceland     | 1        | 1.32%   |
| Hungary     | 1        | 1.32%   |
| Honduras    | 1        | 1.32%   |
| Chile       | 1        | 1.32%   |
| Argentina   | 1        | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Sanford       | 2        | 2.6%    |
| Salvador      | 2        | 2.6%    |
| Melbourne     | 2        | 2.6%    |
| Yekaterinburg | 1        | 1.3%    |
| Yaroslavl     | 1        | 1.3%    |
| Watsonville   | 1        | 1.3%    |
| Warsaw        | 1        | 1.3%    |
| Valence       | 1        | 1.3%    |
| Umeda         | 1        | 1.3%    |
| Toronto       | 1        | 1.3%    |
| Tegucigalpa   | 1        | 1.3%    |
| Tampa         | 1        | 1.3%    |
| Sydney        | 1        | 1.3%    |
| Sumaré       | 1        | 1.3%    |
| Steyning      | 1        | 1.3%    |
| Shelbyville   | 1        | 1.3%    |
| Sao Paulo     | 1        | 1.3%    |
| Santiago      | 1        | 1.3%    |
| San Leandro   | 1        | 1.3%    |
| San Jose      | 1        | 1.3%    |
| Round Rock    | 1        | 1.3%    |
| Rockford      | 1        | 1.3%    |
| Reykjavik     | 1        | 1.3%    |
| Racine        | 1        | 1.3%    |
| Porto Alegre  | 1        | 1.3%    |
| Phoenix       | 1        | 1.3%    |
| Philadelphia  | 1        | 1.3%    |
| New City      | 1        | 1.3%    |
| Moscow        | 1        | 1.3%    |
| Minneapolis   | 1        | 1.3%    |
| Meissen       | 1        | 1.3%    |
| Madrid        | 1        | 1.3%    |
| Madison       | 1        | 1.3%    |
| Los Angeles   | 1        | 1.3%    |
| Longueuil     | 1        | 1.3%    |
| London        | 1        | 1.3%    |
| Lille         | 1        | 1.3%    |
| Lewiston      | 1        | 1.3%    |
| Leipzig       | 1        | 1.3%    |
| Las Vegas     | 1        | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 21       | 26     | 14.89%  |
| Samsung Electronics          | 16       | 29     | 11.35%  |
| WDC                          | 13       | 19     | 9.22%   |
| Sandisk                      | 11       | 16     | 7.8%    |
| Kingston                     | 9        | 9      | 6.38%   |
| Micron/Crucial Technology    | 8        | 8      | 5.67%   |
| Crucial                      | 7        | 9      | 4.96%   |
| SK hynix                     | 6        | 6      | 4.26%   |
| Toshiba                      | 4        | 5      | 2.84%   |
| Silicon Motion               | 3        | 3      | 2.13%   |
| Realtek Semiconductor        | 3        | 3      | 2.13%   |
| Phison Electronics           | 3        | 3      | 2.13%   |
| Micron Technology            | 3        | 5      | 2.13%   |
| Intel                        | 3        | 4      | 2.13%   |
| China                        | 3        | 3      | 2.13%   |
| ADATA Technology             | 3        | 4      | 2.13%   |
| PNY                          | 2        | 2      | 1.42%   |
| Kingston Technology Company  | 2        | 2      | 1.42%   |
| Hitachi                      | 2        | 2      | 1.42%   |
| Fanxiang                     | 2        | 2      | 1.42%   |
| Unknown                      | 1        | 1      | 0.71%   |
| TO Exter                     | 1        | 1      | 0.71%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.71%   |
| O2 Micro                     | 1        | 1      | 0.71%   |
| Netac                        | 1        | 1      | 0.71%   |
| MAXIO Technology (Hangzhou)  | 1        | 1      | 0.71%   |
| KIOXIA                       | 1        | 1      | 0.71%   |
| KingFast                     | 1        | 1      | 0.71%   |
| KingDian                     | 1        | 3      | 0.71%   |
| HGST                         | 1        | 1      | 0.71%   |
| Hewlett-Packard              | 1        | 1      | 0.71%   |
| GALAX                        | 1        | 1      | 0.71%   |
| Corsair                      | 1        | 1      | 0.71%   |
| ASMedia                      | 1        | 1      | 0.71%   |
| AMD                          | 1        | 1      | 0.71%   |
| A-DATA Technology            | 1        | 1      | 0.71%   |
| Unknown                      | 1        | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Micron/Crucial P2 NVMe PCIe SSD 4TB                               | 7        | 4.46%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 5        | 3.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 5        | 3.18%   |
| WDC WD10EZEX-00BN5A0 1TB                                          | 2        | 1.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB             | 2        | 1.27%   |
| Samsung SSD 870 QVO 2TB                                           | 2        | 1.27%   |
| Samsung SSD 860 EVO 1TB                                           | 2        | 1.27%   |
| Samsung SSD 850 EVO 250GB                                         | 2        | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB               | 2        | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB                | 2        | 1.27%   |
| Kingston Company SNV2S1000G 1TB                                   | 2        | 1.27%   |
| Kingston SA400S37120G 120GB SSD                                   | 2        | 1.27%   |
| Crucial CT500MX500SSD1 500GB                                      | 2        | 1.27%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 2        | 1.27%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                                  | 1        | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 1        | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                                  | 1        | 0.64%   |
| WDC WDBNCE5000PNC 500GB SSD                                       | 1        | 0.64%   |
| WDC WD5000BEVT-22A0RT0 500GB                                      | 1        | 0.64%   |
| WDC WD5000AVDS-63U7B1 500GB                                       | 1        | 0.64%   |
| WDC WD5000AAKX-003CA0 500GB                                       | 1        | 0.64%   |
| WDC WD40EZRX-00SPEB0 4TB                                          | 1        | 0.64%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 1        | 0.64%   |
| WDC WD20EARX-00PASB0 2TB                                          | 1        | 0.64%   |
| WDC WD1600AAJS-00B4A0 160GB                                       | 1        | 0.64%   |
| WDC WD1500HLFS-01G6U0 150GB                                       | 1        | 0.64%   |
| WDC WD10EARS-00Y5B1 1TB                                           | 1        | 0.64%   |
| WDC WD Green 2.5 240GB SSD                                        | 1        | 0.64%   |
| Unknown NVMe SSD Drive 2TB                                        | 1        | 0.64%   |
| Toshiba MQ04ABF100 1TB                                            | 1        | 0.64%   |
| Toshiba MQ02ABD100H 1TB                                           | 1        | 0.64%   |
| Toshiba MK1655GSX 160GB                                           | 1        | 0.64%   |
| Toshiba DT01ABA200V 2TB                                           | 1        | 0.64%   |
| TO Exter nal USB 3.0 480GB                                        | 1        | 0.64%   |
| SK hynix SHGP31-2000GM 2TB                                        | 1        | 0.64%   |
| SK hynix SH920 2.5 7MM 256GB SSD                                  | 1        | 0.64%   |
| SK hynix SC311 SATA 256GB SSD                                     | 1        | 0.64%   |
| SK hynix PC611 NVMe 256GB                                         | 1        | 0.64%   |
| SK hynix PC601 NVMe 256GB                                         | 1        | 0.64%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                              | 1        | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 25     | 52.5%   |
| WDC                 | 10       | 13     | 25%     |
| Toshiba             | 4        | 5      | 10%     |
| Hitachi             | 2        | 2      | 5%      |
| TO Exter            | 1        | 1      | 2.5%    |
| Samsung Electronics | 1        | 1      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 15     | 16.67%  |
| Kingston            | 7        | 7      | 12.96%  |
| Crucial             | 7        | 9      | 12.96%  |
| SanDisk             | 6        | 8      | 11.11%  |
| WDC                 | 4        | 6      | 7.41%   |
| China               | 3        | 3      | 5.56%   |
| SK hynix            | 2        | 2      | 3.7%    |
| PNY                 | 2        | 2      | 3.7%    |
| Micron Technology   | 2        | 4      | 3.7%    |
| Fanxiang            | 2        | 2      | 3.7%    |
| Seagate             | 1        | 1      | 1.85%   |
| Netac               | 1        | 1      | 1.85%   |
| KingDian            | 1        | 3      | 1.85%   |
| Intel               | 1        | 1      | 1.85%   |
| Hewlett-Packard     | 1        | 1      | 1.85%   |
| GALAX               | 1        | 1      | 1.85%   |
| Corsair             | 1        | 1      | 1.85%   |
| ASMedia             | 1        | 1      | 1.85%   |
| AMD                 | 1        | 1      | 1.85%   |
| A-DATA Technology   | 1        | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 46       | 59     | 37.7%   |
| SSD     | 43       | 70     | 35.25%  |
| HDD     | 31       | 48     | 25.41%  |
| Unknown | 2        | 2      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 58       | 115    | 53.21%  |
| NVMe | 46       | 59     | 42.2%   |
| SAS  | 5        | 5      | 4.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 67     | 49.37%  |
| 0.51-1.0   | 22       | 28     | 27.85%  |
| 1.01-2.0   | 11       | 13     | 13.92%  |
| 4.01-10.0  | 3        | 3      | 3.8%    |
| 3.01-4.0   | 2        | 5      | 2.53%   |
| 2.01-3.0   | 1        | 1      | 1.27%   |
| 10.01-20.0 | 1        | 1      | 1.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 33       | 42.86%  |
| 1001-2000      | 18       | 23.38%  |
| 501-1000       | 15       | 19.48%  |
| 2001-3000      | 8        | 10.39%  |
| 251-500        | 3        | 3.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 18       | 23.08%  |
| 1001-2000      | 11       | 14.1%   |
| 501-1000       | 11       | 14.1%   |
| 51-100         | 11       | 14.1%   |
| 101-250        | 10       | 12.82%  |
| 251-500        | 6        | 7.69%   |
| 2001-3000      | 6        | 7.69%   |
| More than 3000 | 5        | 6.41%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 76       | 179    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 40       | 30.3%   |
| AMD                          | 36       | 27.27%  |
| Samsung Electronics          | 9        | 6.82%   |
| Micron/Crucial Technology    | 8        | 6.06%   |
| SanDisk                      | 6        | 4.55%   |
| SK hynix                     | 4        | 3.03%   |
| Kingston Technology Company  | 4        | 3.03%   |
| ASMedia Technology           | 4        | 3.03%   |
| Silicon Motion               | 3        | 2.27%   |
| Realtek Semiconductor        | 3        | 2.27%   |
| Phison Electronics           | 3        | 2.27%   |
| ADATA Technology             | 3        | 2.27%   |
| VIA Technologies             | 1        | 0.76%   |
| Solidigm                     | 1        | 0.76%   |
| Shenzhen Longsys Electronics | 1        | 0.76%   |
| O2 Micro                     | 1        | 0.76%   |
| Micron Technology            | 1        | 0.76%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.76%   |
| Marvell Technology Group     | 1        | 0.76%   |
| KIOXIA                       | 1        | 0.76%   |
| Biwin Storage Technology     | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19       | 12.58%  |
| AMD 500 Series Chipset SATA Controller                                         | 15       | 9.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7        | 4.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 4.64%   |
| Intel SATA Controller [RAID mode]                                              | 6        | 3.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 3.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 3.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 1.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 1.99%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 1.99%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2        | 1.32%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 1.32%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2        | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 1.32%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 2        | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 1.32%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 1.32%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.66%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                           | 1        | 0.66%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1        | 0.66%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 0.66%   |
| Silicon Motion SM2260 NVMe SSD Controller                                      | 1        | 0.66%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 1        | 0.66%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1        | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1        | 0.66%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1        | 0.66%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1        | 0.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 0.66%   |
| Realtek RTS5772DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.66%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1        | 0.66%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 1        | 0.66%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 65       | 52%     |
| NVMe | 46       | 36.8%   |
| RAID | 8        | 6.4%    |
| IDE  | 6        | 4.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 38       | 50%     |
| AMD    | 38       | 50%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor              | 5        | 6.49%   |
| AMD Ryzen 5 3600 6-Core Processor               | 5        | 6.49%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 4        | 5.19%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 3        | 3.9%    |
| Intel Core i5-8500 CPU @ 3.00GHz                | 2        | 2.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2        | 2.6%    |
| Intel Core i5-4440 CPU @ 3.10GHz                | 2        | 2.6%    |
| AMD Ryzen 9 5950X 16-Core Processor             | 2        | 2.6%    |
| AMD Ryzen 7 7700X 8-Core Processor              | 2        | 2.6%    |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 2        | 2.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 2.6%    |
| AMD Ryzen 5 2600X Six-Core Processor            | 2        | 2.6%    |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz             | 1        | 1.3%    |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz             | 1        | 1.3%    |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 1.3%    |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 1.3%    |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 1.3%    |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1        | 1.3%    |
| Intel Core i7-10700K CPU @ 3.80GHz              | 1        | 1.3%    |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1        | 1.3%    |
| Intel Core i5-9500T CPU @ 2.20GHz               | 1        | 1.3%    |
| Intel Core i5-9500 CPU @ 3.00GHz                | 1        | 1.3%    |
| Intel Core i5-8500T CPU @ 2.10GHz               | 1        | 1.3%    |
| Intel Core i5-7500 CPU @ 3.40GHz                | 1        | 1.3%    |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1        | 1.3%    |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 1.3%    |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 1.3%    |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.3%    |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 1.3%    |
| Intel Core i5-2500 CPU @ 3.30GHz                | 1        | 1.3%    |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 1.3%    |
| Intel Core i5-10600KF CPU @ 4.10GHz             | 1        | 1.3%    |
| Intel Core i5-10505 CPU @ 3.20GHz               | 1        | 1.3%    |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 1.3%    |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 1.3%    |
| Intel Core i3-10100F CPU @ 3.60GHz              | 1        | 1.3%    |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 1.3%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 1.3%    |
| Intel Celeron CPU G3900 @ 2.80GHz               | 1        | 1.3%    |
| Intel 13th Gen Core i9-13900K                   | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 20       | 25.97%  |
| AMD Ryzen 5       | 18       | 23.38%  |
| AMD Ryzen 7       | 11       | 14.29%  |
| Intel Core i7     | 9        | 11.69%  |
| AMD Ryzen 9       | 5        | 6.49%   |
| Intel Core i3     | 3        | 3.9%    |
| Other             | 2        | 2.6%    |
| Intel Xeon        | 2        | 2.6%    |
| AMD Ryzen 5 PRO   | 2        | 2.6%    |
| Intel Core 2 Quad | 1        | 1.3%    |
| Intel Celeron     | 1        | 1.3%    |
| AMD PRO A10       | 1        | 1.3%    |
| AMD FX            | 1        | 1.3%    |
| AMD A10           | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 29       | 37.66%  |
| 6      | 25       | 32.47%  |
| 8      | 14       | 18.18%  |
| 2      | 4        | 5.19%   |
| 16     | 3        | 3.9%    |
| 24     | 1        | 1.3%    |
| 12     | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 57       | 75%     |
| 1      | 19       | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 76       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 76       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 15       | 19.74%  |
| KabyLake    | 10       | 13.16%  |
| Haswell     | 9        | 11.84%  |
| Unknown     | 8        | 10.53%  |
| CometLake   | 7        | 9.21%   |
| Zen 2       | 6        | 7.89%   |
| Zen+        | 4        | 5.26%   |
| Zen         | 4        | 5.26%   |
| IvyBridge   | 4        | 5.26%   |
| SandyBridge | 3        | 3.95%   |
| Skylake     | 2        | 2.63%   |
| Piledriver  | 2        | 2.63%   |
| Penryn      | 1        | 1.32%   |
| Excavator   | 1        | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 39       | 45.88%  |
| Nvidia | 29       | 34.12%  |
| Intel  | 17       | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 5.68%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 4.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 3.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 3.41%   |
| AMD Raphael                                                                 | 3        | 3.41%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 3.41%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 3.41%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 3.41%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 2.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.27%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 2.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.27%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 2.27%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 2        | 2.27%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 2        | 2.27%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 2.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.27%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1        | 1.14%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.14%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 1.14%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 1.14%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.14%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.14%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.14%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 1.14%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.14%   |
| Nvidia GA106 [RTX A2000]                                                    | 1        | 1.14%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 1.14%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.14%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.14%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.14%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 1.14%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.14%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 1.14%   |
| Nvidia AD107 [GeForce RTX 4060]                                             | 1        | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 35       | 45.45%  |
| 1 x Nvidia     | 28       | 36.36%  |
| 1 x Intel      | 10       | 12.99%  |
| 2 x AMD        | 2        | 2.6%    |
| Intel + Nvidia | 1        | 1.3%    |
| Intel + AMD    | 1        | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 51       | 67.11%  |
| Proprietary | 14       | 18.42%  |
| Unknown     | 11       | 14.47%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 73       | 96.05%  |
| 3.01-4.0   | 2        | 2.63%   |
| 8.01-16.0  | 1        | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 26.23%  |
| Goldstar             | 4        | 6.56%   |
| Dell                 | 3        | 4.92%   |
| BenQ                 | 3        | 4.92%   |
| Vizio                | 2        | 3.28%   |
| Unknown (XXX)        | 2        | 3.28%   |
| Toshiba              | 2        | 3.28%   |
| Sony                 | 2        | 3.28%   |
| Sharp                | 2        | 3.28%   |
| Philips              | 2        | 3.28%   |
| MSI                  | 2        | 3.28%   |
| Insignia             | 2        | 3.28%   |
| Hewlett-Packard      | 2        | 3.28%   |
| DENON                | 2        | 3.28%   |
| ASUSTek Computer     | 2        | 3.28%   |
| Ancor Communications | 2        | 3.28%   |
| VIE                  | 1        | 1.64%   |
| SANYO                | 1        | 1.64%   |
| PXO                  | 1        | 1.64%   |
| Onkyo                | 1        | 1.64%   |
| ITE                  | 1        | 1.64%   |
| Hitachi              | 1        | 1.64%   |
| Gigabyte Technology  | 1        | 1.64%   |
| Gateway              | 1        | 1.64%   |
| CGC                  | 1        | 1.64%   |
| AGO                  | 1        | 1.64%   |
| Acer                 | 1        | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch          | 2        | 3.23%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 2        | 3.23%   |
| Vizio E480i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 1        | 1.61%   |
| Vizio D24f-F1 VIZ1027 1920x1080 530x300mm 24.0-inch                     | 1        | 1.61%   |
| VIE HORIZON Z24 VIE2380 1920x1080 527x296mm 23.8-inch                   | 1        | 1.61%   |
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                        | 1        | 1.61%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                       | 1        | 1.61%   |
| Sony TV SNYEE01 1920x1080                                               | 1        | 1.61%   |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                          | 1        | 1.61%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1        | 1.61%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                       | 1        | 1.61%   |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                          | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch    | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM01AC 1600x1200 312x234mm 15.4-inch    | 1        | 1.61%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch     | 1        | 1.61%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch       | 1        | 1.61%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch       | 1        | 1.61%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 597x336mm 27.0-inch  | 1        | 1.61%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 1110x620mm 50.1-inch  | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                       | 1        | 1.61%   |
| Samsung Electronics LCD Monitor SAM020B 1920x540                        | 1        | 1.61%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1        | 1.61%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 697x392mm 31.5-inch       | 1        | 1.61%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1        | 1.61%   |
| PXO Pixio PX248P PXO0279 1920x1080 698x393mm 31.5-inch                  | 1        | 1.61%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 1.61%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch               | 1        | 1.61%   |
| Onkyo AV Receiver ONK1150 3840x2160 1872x1053mm 84.6-inch               | 1        | 1.61%   |
| MSI MAG301CR2 MSI3CB4 2560x1080 690x291mm 29.5-inch                     | 1        | 1.61%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                          | 1        | 1.61%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                   | 1        | 1.61%   |
| Insignia DX-32L200NA14 BBY0032 1360x768 544x326mm 25.0-inch             | 1        | 1.61%   |
| Insignia 48DR510NA17 BBY3253 1920x1080 1054x591mm 47.6-inch             | 1        | 1.61%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                 | 1        | 1.61%   |
| Hewlett-Packard M24fwa FHD HPN372F 1920x1080 527x296mm 23.8-inch        | 1        | 1.61%   |
| Hewlett-Packard 2009 HWP2828 1600x900 443x250mm 20.0-inch               | 1        | 1.61%   |
| Goldstar ULTRAGEAR GSM5C1C 1920x1080 600x340mm 27.2-inch                | 1        | 1.61%   |
| Goldstar TV GSMC0A0 3840x2160                                           | 1        | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 29       | 48.33%  |
| 3840x2160 (4K)     | 13       | 21.67%  |
| 2560x1440 (QHD)    | 6        | 10%     |
| 1920x540           | 2        | 3.33%   |
| 1680x1050 (WSXGA+) | 2        | 3.33%   |
| 1600x900 (HD+)     | 2        | 3.33%   |
| 3840x1600          | 1        | 1.67%   |
| 3840x1080          | 1        | 1.67%   |
| 3440x1440          | 1        | 1.67%   |
| 2560x1080          | 1        | 1.67%   |
| 1600x1200          | 1        | 1.67%   |
| 1366x768 (WXGA)    | 1        | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 12       | 19.67%  |
| 84      | 5        | 8.2%    |
| 24      | 5        | 8.2%    |
| 23      | 5        | 8.2%    |
| 31      | 4        | 6.56%   |
| 72      | 3        | 4.92%   |
| 54      | 3        | 4.92%   |
| Unknown | 3        | 4.92%   |
| 48      | 2        | 3.28%   |
| 40      | 2        | 3.28%   |
| 22      | 2        | 3.28%   |
| 20      | 2        | 3.28%   |
| 74      | 1        | 1.64%   |
| 52      | 1        | 1.64%   |
| 49      | 1        | 1.64%   |
| 47      | 1        | 1.64%   |
| 46      | 1        | 1.64%   |
| 38      | 1        | 1.64%   |
| 37      | 1        | 1.64%   |
| 34      | 1        | 1.64%   |
| 29      | 1        | 1.64%   |
| 28      | 1        | 1.64%   |
| 18      | 1        | 1.64%   |
| 15      | 1        | 1.64%   |
| 12      | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 31.67%  |
| 601-700     | 9        | 15%     |
| 1001-1500   | 9        | 15%     |
| 1501-2000   | 8        | 13.33%  |
| 401-500     | 5        | 8.33%   |
| 801-900     | 4        | 6.67%   |
| Unknown     | 3        | 5%      |
| 701-800     | 1        | 1.67%   |
| 301-350     | 1        | 1.67%   |
| 201-300     | 1        | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 47       | 81.03%  |
| 21/9  | 3        | 5.17%   |
| 16/10 | 3        | 5.17%   |
| 4/3   | 2        | 3.45%   |
| 32/9  | 2        | 3.45%   |
| 1.96  | 1        | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| More than 1000 | 13       | 22.03%  |
| 301-350        | 13       | 22.03%  |
| 201-250        | 11       | 18.64%  |
| 501-1000       | 8        | 13.56%  |
| 351-500        | 6        | 10.17%  |
| Unknown        | 3        | 5.08%   |
| 151-200        | 2        | 3.39%   |
| 71-80          | 1        | 1.69%   |
| 141-150        | 1        | 1.69%   |
| 111-120        | 1        | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 38       | 63.33%  |
| 1-50    | 8        | 13.33%  |
| 101-120 | 5        | 8.33%   |
| 121-160 | 4        | 6.67%   |
| Unknown | 3        | 5%      |
| 161-240 | 2        | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 74.03%  |
| 0     | 13       | 16.88%  |
| 2     | 7        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 50       | 42.02%  |
| Intel                    | 35       | 29.41%  |
| MediaTek                 | 7        | 5.88%   |
| Qualcomm Atheros         | 6        | 5.04%   |
| Microsoft                | 6        | 5.04%   |
| Broadcom                 | 5        | 4.2%    |
| TP-Link                  | 4        | 3.36%   |
| Samsung Electronics      | 1        | 0.84%   |
| Ralink Technology        | 1        | 0.84%   |
| Ralink                   | 1        | 0.84%   |
| Qualcomm                 | 1        | 0.84%   |
| Marvell Technology Group | 1        | 0.84%   |
| Edimax Technology        | 1        | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 22.86%  |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 8.57%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 4.29%   |
| Intel Ethernet Controller I225-V                                  | 5        | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5        | 3.57%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 4        | 2.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4        | 2.86%   |
| Intel I211 Gigabit Network Connection                             | 4        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 2.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 2.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 2.14%   |
| TP-Link Archer T4U ver.3                                          | 2        | 1.43%   |
| Realtek Realtek WLAN controller                                   | 2        | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.43%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 1.43%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.71%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.71%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1        | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1        | 0.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.71%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.71%   |
| Realtek 802.11ac NIC                                              | 1        | 0.71%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.71%   |
| Qualcomm MDM9207-MTP _SN:E28CB43E                                 | 1        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.71%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.71%   |
| Microsoft Wireless XBox Controller Dongle                         | 1        | 0.71%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 17       | 30.91%  |
| Realtek Semiconductor | 11       | 20%     |
| MediaTek              | 7        | 12.73%  |
| Microsoft             | 6        | 10.91%  |
| Qualcomm Atheros      | 5        | 9.09%   |
| TP-Link               | 4        | 7.27%   |
| Broadcom              | 2        | 3.64%   |
| Ralink Technology     | 1        | 1.82%   |
| Ralink                | 1        | 1.82%   |
| Edimax Technology     | 1        | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 6        | 10.17%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 5        | 8.47%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 4        | 6.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 4        | 6.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 3        | 5.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 3        | 5.08%   |
| TP-Link Archer T4U ver.3                                      | 2        | 3.39%   |
| Realtek Realtek WLAN controller                               | 2        | 3.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2        | 3.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2        | 3.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2        | 3.39%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1        | 1.69%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1        | 1.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1        | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 1.69%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1        | 1.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 1.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 1        | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 1.69%   |
| Realtek RTL8187 Wireless Adapter                              | 1        | 1.69%   |
| Realtek 802.11ac NIC                                          | 1        | 1.69%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 1        | 1.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 1.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 1        | 1.69%   |
| Microsoft Xbox 360 Wireless Adapter                           | 1        | 1.69%   |
| Microsoft Wireless XBox Controller Dongle                     | 1        | 1.69%   |
| Intel Wireless-AC 9260                                        | 1        | 1.69%   |
| Intel Wireless 8265 / 8275                                    | 1        | 1.69%   |
| Intel Wireless 3165                                           | 1        | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1        | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1        | 1.69%   |
| Edimax Wi-Fi                                                  | 1        | 1.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 1        | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 1        | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 46       | 58.23%  |
| Intel                    | 27       | 34.18%  |
| Broadcom                 | 3        | 3.8%    |
| Qualcomm Atheros         | 1        | 1.27%   |
| Qualcomm                 | 1        | 1.27%   |
| Marvell Technology Group | 1        | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 40%     |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 15%     |
| Intel Ethernet Controller I225-V                                  | 5        | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 6.25%   |
| Intel I211 Gigabit Network Connection                             | 4        | 5%      |
| Intel Ethernet Connection (2) I219-V                              | 4        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.5%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 2.5%    |
| Qualcomm MDM9207-MTP _SN:E28CB43E                                 | 1        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.25%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.25%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.25%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.25%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.25%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.25%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.25%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 61.79%  |
| WiFi     | 46       | 37.4%   |
| Modem    | 1        | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 58.97%  |
| WiFi     | 32       | 41.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 50%     |
| 2     | 36       | 47.37%  |
| 3     | 2        | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 61.04%  |
| Yes  | 30       | 38.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 36.36%  |
| Cambridge Silicon Radio         | 8        | 18.18%  |
| MediaTek                        | 5        | 11.36%  |
| Realtek Semiconductor           | 4        | 9.09%   |
| IMC Networks                    | 3        | 6.82%   |
| Qualcomm Atheros Communications | 2        | 4.55%   |
| ASUSTek Computer                | 2        | 4.55%   |
| TP-Link                         | 1        | 2.27%   |
| Foxconn / Hon Hai               | 1        | 2.27%   |
| Apple                           | 1        | 2.27%   |
| Actions                         | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 17.78%  |
| MediaTek Wireless_Device                            | 5        | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 11.11%  |
| Intel AX200 Bluetooth                               | 5        | 11.11%  |
| Realtek Bluetooth Radio                             | 4        | 8.89%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 4.44%   |
| Intel Bluetooth wireless interface                  | 2        | 4.44%   |
| Intel AX210 Bluetooth                               | 2        | 4.44%   |
| IMC Networks Bluetooth Radio                        | 2        | 4.44%   |
| TP-Link UB500 Adapter                               | 1        | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.22%   |
| Intel Bluetooth Device                              | 1        | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.22%   |
| IMC Networks Bluetooth Device                       | 1        | 2.22%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 2.22%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 2.22%   |
| Apple Bluetooth USB Host Controller                 | 1        | 2.22%   |
| Actions general adapter                             | 1        | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 51       | 36.69%  |
| Intel                    | 37       | 26.62%  |
| Nvidia                   | 29       | 20.86%  |
| Logitech                 | 4        | 2.88%   |
| Kingston Technology      | 3        | 2.16%   |
| Razer USA                | 2        | 1.44%   |
| Hewlett-Packard          | 2        | 1.44%   |
| C-Media Electronics      | 2        | 1.44%   |
| ASUSTek Computer         | 2        | 1.44%   |
| Texas Instruments        | 1        | 0.72%   |
| SteelSeries ApS          | 1        | 0.72%   |
| Micro Star International | 1        | 0.72%   |
| JMTek                    | 1        | 0.72%   |
| Focusrite-Novation       | 1        | 0.72%   |
| Comtrue                  | 1        | 0.72%   |
| Astro Gaming             | 1        | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 18       | 10.23%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 5.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5        | 2.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 2.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 2.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 2.27%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 4        | 2.27%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 2.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.27%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 2.27%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 1.7%    |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.7%    |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.7%    |
| Razer USA Razer Seiren Mini                                                | 2        | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.14%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.14%   |
| Logitech Yeti X                                                            | 2        | 1.14%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 1.14%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 1.14%   |
| ASUSTek Computer USB Audio                                                 | 2        | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.14%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.57%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1        | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.57%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.57%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.57%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.57%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.57%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia                      | 3        | 37.5%   |
| Logitech                      | 2        | 25%     |
| YT-221117-J                   | 1        | 12.5%   |
| Sunplus Innovation Technology | 1        | 12.5%   |
| Samsung Electronics           | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| YT-221117-J USB2.0 Camera               | 1        | 12.5%   |
| Sunplus HD 720P webcam                  | 1        | 12.5%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 12.5%   |
| Microdia Webcam Vitade AF               | 1        | 12.5%   |
| Microdia USB Camera                     | 1        | 12.5%   |
| Microdia Camera                         | 1        | 12.5%   |
| Logitech Webcam C200                    | 1        | 12.5%   |
| Logitech Logi Webcam C920e              | 1        | 12.5%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 49       | 64.47%  |
| 1     | 27       | 35.53%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 16       | 59.26%  |
| Network       | 6        | 22.22%  |
| Net/wireless  | 2        | 7.41%   |
| Net/ethernet  | 2        | 7.41%   |
| Storage/nvme  | 1        | 3.7%    |


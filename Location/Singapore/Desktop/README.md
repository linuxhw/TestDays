Linux in Singapore - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

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

Total: 107

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | X99-Ultra Gaming-CF         | [568bffc355](https://linux-hardware.org/?probe=568bffc355) | Sep 22, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [73fd6c23e1](https://linux-hardware.org/?probe=73fd6c23e1) | Sep 21, 2022 |
| ASUSTek    | X99-E WS                    | [c76dceef8e](https://linux-hardware.org/?probe=c76dceef8e) | Sep 08, 2022 |
| ASUSTek    | ROG STRIX H370-F GAMING     | [a61798e4d3](https://linux-hardware.org/?probe=a61798e4d3) | Sep 05, 2022 |
| ASUSTek    | ROG STRIX H370-F GAMING     | [0ba66b6e07](https://linux-hardware.org/?probe=0ba66b6e07) | Sep 05, 2022 |
| ASUSTek    | ROG STRIX H370-F GAMING     | [169df470a6](https://linux-hardware.org/?probe=169df470a6) | Sep 05, 2022 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| HP         | 843B                        | [6033dabb9d](https://linux-hardware.org/?probe=6033dabb9d) | Aug 09, 2022 |
| Gigabyte   | H61M-S2PH                   | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI        | PRO B660M-A WIFI DDR4       | [b33dcf5312](https://linux-hardware.org/?probe=b33dcf5312) | Jul 12, 2022 |
| Gigabyte   | H87N-WIFI                   | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| MSI        | Z87-G45 GAMING              | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| ASUSTek    | B85M-E                      | [bd4201a786](https://linux-hardware.org/?probe=bd4201a786) | May 09, 2022 |
| ASUSTek    | B85M-E                      | [78752966d0](https://linux-hardware.org/?probe=78752966d0) | May 02, 2022 |
| ASUSTek    | B85M-E                      | [200ed04d31](https://linux-hardware.org/?probe=200ed04d31) | May 02, 2022 |
| Dell       | 06CV2N A00                  | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Dell       | 0NK70N A03                  | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| HP         | 8054                        | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| Dell       | 09M8Y8 A02                  | [862667e874](https://linux-hardware.org/?probe=862667e874) | Feb 22, 2022 |
| Dell       | 06CV2N A00                  | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Gigabyte   | Z77-D3H                     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| ASRock     | AB350 Gaming-ITX/ac         | [6c19d2fbd6](https://linux-hardware.org/?probe=6c19d2fbd6) | Jan 11, 2022 |
| Gigabyte   | B550I AORUS PRO AX          | [9309138e99](https://linux-hardware.org/?probe=9309138e99) | Dec 31, 2021 |
| ASRock     | B560M Pro4                  | [bd3ec294cb](https://linux-hardware.org/?probe=bd3ec294cb) | Dec 18, 2021 |
| Dell       | 0VD5HY A04                  | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| Dell       | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| AMI        | Cherry Trail CR             | [96c2c68676](https://linux-hardware.org/?probe=96c2c68676) | Dec 16, 2021 |
| Dell       | 0C96W1 A02                  | [31f32bf184](https://linux-hardware.org/?probe=31f32bf184) | Dec 16, 2021 |
| ASRock     | B450M Steel Legend          | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| MSI        | MPG Z690 CARBON WIFI        | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI        | MPG Z690 CARBON WIFI        | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte   | B365M GAMING HD             | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| Dell       | 0XCR8D A03                  | [97e2f36d1f](https://linux-hardware.org/?probe=97e2f36d1f) | Nov 07, 2021 |
| ASUSTek    | Z170-A                      | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| MSI        | B450 TOMAHAWK               | [02983fa577](https://linux-hardware.org/?probe=02983fa577) | Sep 08, 2021 |
| MSI        | A320M-A PRO MAX             | [6daf2c7553](https://linux-hardware.org/?probe=6daf2c7553) | Sep 04, 2021 |
| MSI        | A320M-A PRO MAX             | [bea89f1164](https://linux-hardware.org/?probe=bea89f1164) | Sep 04, 2021 |
| ASRock     | Z77 Extreme3                | [0e95fc1e3d](https://linux-hardware.org/?probe=0e95fc1e3d) | Sep 03, 2021 |
| Lenovo     | 1046 SDK0T08861 WIN 3305... | [adf156f9db](https://linux-hardware.org/?probe=adf156f9db) | Aug 26, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Lenovo     | NOK                         | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Biostar    | TB250-BTC+                  | [f45d61ab64](https://linux-hardware.org/?probe=f45d61ab64) | Jul 31, 2021 |
| Dell       | 0NKW6Y A00                  | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Dell       | 0NKW6Y A00                  | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| ASUSTek    | M5A78L-M LX V2              | [502fe1bf66](https://linux-hardware.org/?probe=502fe1bf66) | Jul 19, 2021 |
| MSI        | A68HM-E33 V2                | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| LattePanda | Alpha                       | [1d9daab9aa](https://linux-hardware.org/?probe=1d9daab9aa) | Jun 20, 2021 |
| LattePanda | Alpha                       | [e9ef19ed6e](https://linux-hardware.org/?probe=e9ef19ed6e) | Jun 20, 2021 |
| HP         | 198E                        | [a44ce74aaa](https://linux-hardware.org/?probe=a44ce74aaa) | May 22, 2021 |
| Gigabyte   | H81M-DS2                    | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| ASUSTek    | M5A78L-M LX V2              | [e20da66200](https://linux-hardware.org/?probe=e20da66200) | Apr 17, 2021 |
| ASRock     | HM55-MXM                    | [e56d216ab7](https://linux-hardware.org/?probe=e56d216ab7) | Apr 14, 2021 |
| Lenovo     | ThinkCentre M90p 5864BM3    | [666e4f970e](https://linux-hardware.org/?probe=666e4f970e) | Apr 10, 2021 |
| Dell       | 0D6H9T A00                  | [94d321f020](https://linux-hardware.org/?probe=94d321f020) | Apr 02, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [9eff035231](https://linux-hardware.org/?probe=9eff035231) | Mar 01, 2021 |
| Gigabyte   | X570 AORUS PRO WIFI         | [e6cb859b40](https://linux-hardware.org/?probe=e6cb859b40) | Feb 21, 2021 |
| Lenovo     | SHARKBAY NOK                | [563ceb4238](https://linux-hardware.org/?probe=563ceb4238) | Jan 28, 2021 |
| Dell       | 00V62H A01                  | [e08b05c812](https://linux-hardware.org/?probe=e08b05c812) | Jan 09, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [e5b808ee57](https://linux-hardware.org/?probe=e5b808ee57) | Jan 02, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [ca915222e5](https://linux-hardware.org/?probe=ca915222e5) | Dec 07, 2020 |
| Dell       | 0D02VH A01                  | [1d822ef5a3](https://linux-hardware.org/?probe=1d822ef5a3) | Dec 07, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [b9461ebddd](https://linux-hardware.org/?probe=b9461ebddd) | Nov 29, 2020 |
| Dell       | 0D441T A03                  | [b57394e325](https://linux-hardware.org/?probe=b57394e325) | Nov 20, 2020 |
| ASUSTek    | E3M-ET V5 SERIES            | [f1faffa793](https://linux-hardware.org/?probe=f1faffa793) | Nov 20, 2020 |
| ASUSTek    | E3M-ET V5 SERIES            | [e727ca80a6](https://linux-hardware.org/?probe=e727ca80a6) | Nov 20, 2020 |
| ASUSTek    | M4A78-EM-1394               | [3736bdc191](https://linux-hardware.org/?probe=3736bdc191) | Nov 12, 2020 |
| ASRock     | H110M-HDS R3.0              | [7dea4e7c04](https://linux-hardware.org/?probe=7dea4e7c04) | Nov 10, 2020 |
| ASRock     | 990FX Killer                | [4faf15fe7f](https://linux-hardware.org/?probe=4faf15fe7f) | Oct 08, 2020 |
| MSI        | X370 GAMING PRO CARBON      | [f542320df7](https://linux-hardware.org/?probe=f542320df7) | Sep 28, 2020 |
| ASUSTek    | M3A78-EM                    | [65ed8bba9c](https://linux-hardware.org/?probe=65ed8bba9c) | Sep 23, 2020 |
| ASUSTek    | Z97M-PLUS                   | [db8a9ea1ef](https://linux-hardware.org/?probe=db8a9ea1ef) | Sep 04, 2020 |
| Gigabyte   | 945GZM-S2                   | [56d2f5c077](https://linux-hardware.org/?probe=56d2f5c077) | Sep 03, 2020 |
| Gigabyte   | 945GZM-S2                   | [3a8e991dee](https://linux-hardware.org/?probe=3a8e991dee) | Sep 01, 2020 |
| ASUSTek    | P8H77-V LE                  | [efb532b71e](https://linux-hardware.org/?probe=efb532b71e) | Jul 24, 2020 |
| ASRock     | HM55-MXM                    | [7f12e5a53c](https://linux-hardware.org/?probe=7f12e5a53c) | Jul 19, 2020 |
| Gigabyte   | G1.Sniper A88X-CF           | [6d5b75622f](https://linux-hardware.org/?probe=6d5b75622f) | Jul 10, 2020 |
| ECS        | H61H2-MV                    | [a4ebb57c65](https://linux-hardware.org/?probe=a4ebb57c65) | Jun 19, 2020 |
| ASUSTek    | P8H77-V LE                  | [5d31ba79a1](https://linux-hardware.org/?probe=5d31ba79a1) | Jun 17, 2020 |
| ASUSTek    | H87I-PLUS                   | [9e8603cab8](https://linux-hardware.org/?probe=9e8603cab8) | Jun 05, 2020 |
| ASRock     | A320M-HDV R4.0              | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASRock     | H110M-HDS R3.0              | [8610132ae8](https://linux-hardware.org/?probe=8610132ae8) | Jun 03, 2020 |
| ASUSTek    | H87I-PLUS                   | [74e66b2a4a](https://linux-hardware.org/?probe=74e66b2a4a) | May 30, 2020 |
| ASUSTek    | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek    | Berkeley                    | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| ASRock     | A320M-HDV R4.0              | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek    | Berkeley                    | [ea544afa99](https://linux-hardware.org/?probe=ea544afa99) | May 12, 2020 |
| ASUSTek    | Berkeley                    | [058ecc2781](https://linux-hardware.org/?probe=058ecc2781) | May 12, 2020 |
| ASUSTek    | PRIME H310M-A               | [aaed21ffd0](https://linux-hardware.org/?probe=aaed21ffd0) | May 08, 2020 |
| Dell       | 06D7TR A00                  | [60b49366ed](https://linux-hardware.org/?probe=60b49366ed) | Apr 30, 2020 |
| ASUSTek    | ROG CROSSHAIR VII HERO      | [26486f2fff](https://linux-hardware.org/?probe=26486f2fff) | Mar 24, 2020 |
| Dell       | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Dell       | 00V62H A01                  | [001695659e](https://linux-hardware.org/?probe=001695659e) | Mar 04, 2020 |
| Dell       | 00V62H A01                  | [199fc82812](https://linux-hardware.org/?probe=199fc82812) | Mar 04, 2020 |
| Gigabyte   | Z270X-UD5-CF                | [a38c129cd9](https://linux-hardware.org/?probe=a38c129cd9) | Jan 04, 2020 |
| Acer       | Aspire X3950                | [fd467d33f5](https://linux-hardware.org/?probe=fd467d33f5) | Jan 03, 2020 |
| ASRock     | Z370 Pro4                   | [f681da046d](https://linux-hardware.org/?probe=f681da046d) | Dec 09, 2019 |
| Lenovo     | 30C0 SDK0J40697 WIN 3305... | [f35675231e](https://linux-hardware.org/?probe=f35675231e) | Dec 02, 2019 |
| Gigabyte   | X570 AORUS PRO WIFI         | [6bee5d9a22](https://linux-hardware.org/?probe=6bee5d9a22) | Nov 16, 2019 |
| Gigabyte   | X570 AORUS PRO WIFI         | [1b0467dde0](https://linux-hardware.org/?probe=1b0467dde0) | Nov 16, 2019 |
| Dell       | 0F3KHR A00                  | [636fbfdcb6](https://linux-hardware.org/?probe=636fbfdcb6) | Sep 22, 2019 |
| ASUSTek    | P8H67-M PRO                 | [c6888a9735](https://linux-hardware.org/?probe=c6888a9735) | May 31, 2019 |
| ASUSTek    | ET2020I                     | [a695a9c422](https://linux-hardware.org/?probe=a695a9c422) | Apr 07, 2019 |
| MSI        | X299 RAIDER                 | [3f982f3e86](https://linux-hardware.org/?probe=3f982f3e86) | Dec 04, 2018 |
| MSI        | X299 RAIDER                 | [1207b80721](https://linux-hardware.org/?probe=1207b80721) | Dec 04, 2018 |
| MSI        | Boston                      | [104569cafb](https://linux-hardware.org/?probe=104569cafb) | Oct 24, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 19       | 22.62%  |
| Ubuntu 18.04                 | 13       | 15.48%  |
| Pop!_OS 20.04                | 3        | 3.57%   |
| Manjaro                      | 3        | 3.57%   |
| KDE neon 20.04               | 3        | 3.57%   |
| Debian 11                    | 3        | 3.57%   |
| Arch Rolling                 | 3        | 3.57%   |
| Ubuntu 21.04                 | 2        | 2.38%   |
| Rocky Linux 8.5              | 2        | 2.38%   |
| Pop!_OS 21.04                | 2        | 2.38%   |
| OpenMandriva 4.50            | 2        | 2.38%   |
| OpenMandriva 4.3             | 2        | 2.38%   |
| Linux Mint 20                | 2        | 2.38%   |
| Fedora 33                    | 2        | 2.38%   |
| Arch                         | 2        | 2.38%   |
| Xubuntu 20.04                | 1        | 1.19%   |
| Ubuntu Unity 20.04           | 1        | 1.19%   |
| Ubuntu Unity 16.04           | 1        | 1.19%   |
| Ubuntu MATE 20.04            | 1        | 1.19%   |
| Ubuntu 22.04                 | 1        | 1.19%   |
| Ubuntu 19.10                 | 1        | 1.19%   |
| Ubuntu 19.04                 | 1        | 1.19%   |
| Ubuntu 18.10                 | 1        | 1.19%   |
| Rocky Linux 8.4              | 1        | 1.19%   |
| Pop!_OS 21.10                | 1        | 1.19%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 1.19%   |
| OpenMandriva 4.2             | 1        | 1.19%   |
| Manjaro 20.2                 | 1        | 1.19%   |
| Lubuntu 20.04                | 1        | 1.19%   |
| Linux Mint 19.3              | 1        | 1.19%   |
| Fedora 36                    | 1        | 1.19%   |
| Fedora 34                    | 1        | 1.19%   |
| EndeavourOS Rolling          | 1        | 1.19%   |
| Debian 9                     | 1        | 1.19%   |
| CentOS 7                     | 1        | 1.19%   |
| ArcoLinux Rolling            | 1        | 1.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 38       | 45.78%  |
| Pop!_OS      | 6        | 7.23%   |
| OpenMandriva | 5        | 6.02%   |
| Arch         | 5        | 6.02%   |
| Manjaro      | 4        | 4.82%   |
| Fedora       | 4        | 4.82%   |
| Debian       | 4        | 4.82%   |
| Rocky Linux  | 3        | 3.61%   |
| KDE neon     | 3        | 3.61%   |
| Ubuntu Unity | 2        | 2.41%   |
| Linux Mint   | 2        | 2.41%   |
| Xubuntu      | 1        | 1.2%    |
| Ubuntu MATE  | 1        | 1.2%    |
| openSUSE     | 1        | 1.2%    |
| Lubuntu      | 1        | 1.2%    |
| EndeavourOS  | 1        | 1.2%    |
| CentOS       | 1        | 1.2%    |
| ArcoLinux    | 1        | 1.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.0-46-generic            | 4        | 4.4%    |
| 5.4.0-29-generic             | 3        | 3.3%    |
| 5.9.8-200.fc33.x86_64        | 2        | 2.2%    |
| 5.4.0-7642-generic           | 2        | 2.2%    |
| 5.4.0-70-generic             | 2        | 2.2%    |
| 5.4.0-42-generic             | 2        | 2.2%    |
| 5.4.0-40-generic             | 2        | 2.2%    |
| 5.4.0-37-generic             | 2        | 2.2%    |
| 5.3.0-51-generic             | 2        | 2.2%    |
| 5.16.7-desktop-1omv4003      | 2        | 2.2%    |
| 5.12.7-desktop-1omv4003      | 2        | 2.2%    |
| 5.11.0-27-generic            | 2        | 2.2%    |
| 5.0.0-36-generic             | 2        | 2.2%    |
| 4.18.0-348.12.2.el8_5.x86_64 | 2        | 2.2%    |
| 5.9.11-3-MANJARO             | 1        | 1.1%    |
| 5.8.18-1-MANJARO             | 1        | 1.1%    |
| 5.8.0-53-generic             | 1        | 1.1%    |
| 5.8.0-48-generic             | 1        | 1.1%    |
| 5.8.0-31-generic             | 1        | 1.1%    |
| 5.4.0-96-generic             | 1        | 1.1%    |
| 5.4.0-81-generic             | 1        | 1.1%    |
| 5.4.0-7634-generic           | 1        | 1.1%    |
| 5.4.0-7629-generic           | 1        | 1.1%    |
| 5.4.0-66-generic             | 1        | 1.1%    |
| 5.4.0-65-generic             | 1        | 1.1%    |
| 5.4.0-53-generic             | 1        | 1.1%    |
| 5.4.0-52-generic             | 1        | 1.1%    |
| 5.4.0-48-generic             | 1        | 1.1%    |
| 5.4.0-45-generic             | 1        | 1.1%    |
| 5.4.0-33-generic             | 1        | 1.1%    |
| 5.3.0-53-generic             | 1        | 1.1%    |
| 5.3.0-40-generic             | 1        | 1.1%    |
| 5.18.2-1-default             | 1        | 1.1%    |
| 5.17.5-300.fc36.x86_64       | 1        | 1.1%    |
| 5.16.18-100.fc34.x86_64      | 1        | 1.1%    |
| 5.16.11-76051611-generic     | 1        | 1.1%    |
| 5.15.8-arch1-1               | 1        | 1.1%    |
| 5.15.7-arch1-1               | 1        | 1.1%    |
| 5.15.6-tkg-pds               | 1        | 1.1%    |
| 5.15.53-1-MANJARO            | 1        | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 21       | 24.14%  |
| 5.0.0   | 7        | 8.05%   |
| 5.15.0  | 6        | 6.9%    |
| 5.11.0  | 6        | 6.9%    |
| 4.18.0  | 5        | 5.75%   |
| 5.8.0   | 3        | 3.45%   |
| 5.3.0   | 3        | 3.45%   |
| 5.10.0  | 3        | 3.45%   |
| 4.15.0  | 3        | 3.45%   |
| 5.9.8   | 2        | 2.3%    |
| 5.16.7  | 2        | 2.3%    |
| 5.13.0  | 2        | 2.3%    |
| 5.12.7  | 2        | 2.3%    |
| 5.9.11  | 1        | 1.15%   |
| 5.8.18  | 1        | 1.15%   |
| 5.18.2  | 1        | 1.15%   |
| 5.17.5  | 1        | 1.15%   |
| 5.16.18 | 1        | 1.15%   |
| 5.16.11 | 1        | 1.15%   |
| 5.15.8  | 1        | 1.15%   |
| 5.15.7  | 1        | 1.15%   |
| 5.15.6  | 1        | 1.15%   |
| 5.15.53 | 1        | 1.15%   |
| 5.15.13 | 1        | 1.15%   |
| 5.15.10 | 1        | 1.15%   |
| 5.14.18 | 1        | 1.15%   |
| 5.14.16 | 1        | 1.15%   |
| 5.13.13 | 1        | 1.15%   |
| 5.13.12 | 1        | 1.15%   |
| 5.12.11 | 1        | 1.15%   |
| 5.11.11 | 1        | 1.15%   |
| 5.10.84 | 1        | 1.15%   |
| 5.10.14 | 1        | 1.15%   |
| 4.16.0  | 1        | 1.15%   |
| 3.10.0  | 1        | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 21       | 24.14%  |
| 5.15    | 12       | 13.79%  |
| 5.11    | 7        | 8.05%   |
| 5.0     | 7        | 8.05%   |
| 5.10    | 5        | 5.75%   |
| 4.18    | 5        | 5.75%   |
| 5.8     | 4        | 4.6%    |
| 5.16    | 4        | 4.6%    |
| 5.13    | 4        | 4.6%    |
| 5.9     | 3        | 3.45%   |
| 5.3     | 3        | 3.45%   |
| 5.12    | 3        | 3.45%   |
| 4.15    | 3        | 3.45%   |
| 5.14    | 2        | 2.3%    |
| 5.18    | 1        | 1.15%   |
| 5.17    | 1        | 1.15%   |
| 4.16    | 1        | 1.15%   |
| 3.10    | 1        | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 82       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 41       | 48.81%  |
| Unknown       | 16       | 19.05%  |
| KDE5          | 12       | 14.29%  |
| X-Cinnamon    | 3        | 3.57%   |
| XFCE          | 2        | 2.38%   |
| Unity         | 2        | 2.38%   |
| i3            | 2        | 2.38%   |
| MATE          | 1        | 1.19%   |
| LXQt          | 1        | 1.19%   |
| KDE           | 1        | 1.19%   |
| GNOME Classic | 1        | 1.19%   |
| Cinnamon      | 1        | 1.19%   |
| Budgie        | 1        | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 68       | 81.93%  |
| Unknown | 6        | 7.23%   |
| Wayland | 5        | 6.02%   |
| Tty     | 4        | 4.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 60.98%  |
| GDM     | 15       | 18.29%  |
| SDDM    | 10       | 12.2%   |
| LightDM | 3        | 3.66%   |
| GDM3    | 3        | 3.66%   |
| TDM     | 1        | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_SG   | 34       | 40.96%  |
| en_US   | 31       | 37.35%  |
| Unknown | 8        | 9.64%   |
| en_AU   | 3        | 3.61%   |
| de_DE   | 2        | 2.41%   |
| C       | 2        | 2.41%   |
| zh_CN   | 1        | 1.2%    |
| fr_FR   | 1        | 1.2%    |
| en_PH   | 1        | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 41       | 50%     |
| EFI  | 41       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 62       | 74.7%   |
| Btrfs   | 8        | 9.64%   |
| Xfs     | 5        | 6.02%   |
| Overlay | 5        | 6.02%   |
| Unknown | 3        | 3.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 46       | 56.1%   |
| GPT     | 31       | 37.8%   |
| MBR     | 5        | 6.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 79.52%  |
| Yes       | 17       | 20.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 71.95%  |
| Yes       | 23       | 28.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 23.17%  |
| Dell                | 15       | 18.29%  |
| Gigabyte Technology | 14       | 17.07%  |
| MSI                 | 12       | 14.63%  |
| ASRock              | 9        | 10.98%  |
| Lenovo              | 5        | 6.1%    |
| Hewlett-Packard     | 3        | 3.66%   |
| LattePanda          | 1        | 1.22%   |
| ECS                 | 1        | 1.22%   |
| Biostar             | 1        | 1.22%   |
| AMI                 | 1        | 1.22%   |
| Acer                | 1        | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 4        | 4.88%   |
| MSI MS-7C84                         | 3        | 3.66%   |
| Gigabyte X570 AORUS PRO WIFI        | 3        | 3.66%   |
| Gigabyte B550I AORUS PRO AX         | 2        | 2.44%   |
| Dell OptiPlex 990                   | 2        | 2.44%   |
| Dell OptiPlex 9020                  | 2        | 2.44%   |
| ASUS ROG STRIX B550-I GAMING        | 2        | 2.44%   |
| MSI MS-7D43                         | 1        | 1.22%   |
| MSI MS-7D30                         | 1        | 1.22%   |
| MSI MS-7C52                         | 1        | 1.22%   |
| MSI MS-7C02                         | 1        | 1.22%   |
| MSI MS-7A94                         | 1        | 1.22%   |
| MSI MS-7A32                         | 1        | 1.22%   |
| MSI MS-7821                         | 1        | 1.22%   |
| MSI MS-7721                         | 1        | 1.22%   |
| MSI KT308AA-AB4 SR5472CF            | 1        | 1.22%   |
| Lenovo ThinkStation P620 30E1S3VH00 | 1        | 1.22%   |
| Lenovo ThinkStation P310 30ASS2WG00 | 1        | 1.22%   |
| Lenovo ThinkCentre M90p 5864BM3     | 1        | 1.22%   |
| Lenovo ThinkCentre M73 10AXS26C00   | 1        | 1.22%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 1.22%   |
| LattePanda Alpha                    | 1        | 1.22%   |
| HP ProDesk 400 G2 MT                | 1        | 1.22%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.22%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.22%   |
| Gigabyte Z77-D3H                    | 1        | 1.22%   |
| Gigabyte Z270X-UD5                  | 1        | 1.22%   |
| Gigabyte X99-Ultra Gaming-CF        | 1        | 1.22%   |
| Gigabyte H87N-WIFI                  | 1        | 1.22%   |
| Gigabyte H81M-DS2                   | 1        | 1.22%   |
| Gigabyte H61M-S2PH                  | 1        | 1.22%   |
| Gigabyte G1.Sniper A88X-CF          | 1        | 1.22%   |
| Gigabyte B365M GAMING HD            | 1        | 1.22%   |
| Gigabyte 945GZM-S2                  | 1        | 1.22%   |
| ECS H61H2-MV                        | 1        | 1.22%   |
| Dell Vostro 3681                    | 1        | 1.22%   |
| Dell Precision T7610                | 1        | 1.22%   |
| Dell Precision T3610                | 1        | 1.22%   |
| Dell Precision 5820 Tower           | 1        | 1.22%   |
| Dell PowerEdge T20                  | 1        | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 9        | 10.98%  |
| ASUS ROG            | 4        | 4.88%   |
| ASUS All            | 4        | 4.88%   |
| MSI MS-7C84         | 3        | 3.66%   |
| Lenovo ThinkCentre  | 3        | 3.66%   |
| Gigabyte X570       | 3        | 3.66%   |
| Dell Precision      | 3        | 3.66%   |
| Lenovo ThinkStation | 2        | 2.44%   |
| Gigabyte B550I      | 2        | 2.44%   |
| MSI MS-7D43         | 1        | 1.22%   |
| MSI MS-7D30         | 1        | 1.22%   |
| MSI MS-7C52         | 1        | 1.22%   |
| MSI MS-7C02         | 1        | 1.22%   |
| MSI MS-7A94         | 1        | 1.22%   |
| MSI MS-7A32         | 1        | 1.22%   |
| MSI MS-7821         | 1        | 1.22%   |
| MSI MS-7721         | 1        | 1.22%   |
| MSI KT308AA-AB4     | 1        | 1.22%   |
| LattePanda Alpha    | 1        | 1.22%   |
| HP ProDesk          | 1        | 1.22%   |
| HP Pavilion         | 1        | 1.22%   |
| HP EliteDesk        | 1        | 1.22%   |
| Gigabyte Z77-D3H    | 1        | 1.22%   |
| Gigabyte Z270X-UD5  | 1        | 1.22%   |
| Gigabyte X99-Ultra  | 1        | 1.22%   |
| Gigabyte H87N-WIFI  | 1        | 1.22%   |
| Gigabyte H81M-DS2   | 1        | 1.22%   |
| Gigabyte H61M-S2PH  | 1        | 1.22%   |
| Gigabyte G1.Sniper  | 1        | 1.22%   |
| Gigabyte B365M      | 1        | 1.22%   |
| Gigabyte 945GZM-S2  | 1        | 1.22%   |
| ECS H61H2-MV        | 1        | 1.22%   |
| Dell Vostro         | 1        | 1.22%   |
| Dell PowerEdge      | 1        | 1.22%   |
| Dell Inspiron       | 1        | 1.22%   |
| Biostar TB250-BTC+  | 1        | 1.22%   |
| ASUS Z170-A         | 1        | 1.22%   |
| ASUS Pro            | 1        | 1.22%   |
| ASUS PRIME          | 1        | 1.22%   |
| ASUS P8H77-V        | 1        | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 15.85%  |
| 2020 | 11       | 13.41%  |
| 2018 | 10       | 12.2%   |
| 2019 | 7        | 8.54%   |
| 2016 | 6        | 7.32%   |
| 2011 | 6        | 7.32%   |
| 2015 | 5        | 6.1%    |
| 2014 | 5        | 6.1%    |
| 2017 | 4        | 4.88%   |
| 2012 | 4        | 4.88%   |
| 2010 | 4        | 4.88%   |
| 2021 | 3        | 3.66%   |
| 2008 | 2        | 2.44%   |
| 2007 | 2        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 82       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 81       | 98.78%  |
| Enabled  | 1        | 1.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 21       | 25.61%  |
| 8.01-16.0       | 16       | 19.51%  |
| 4.01-8.0        | 14       | 17.07%  |
| 32.01-64.0      | 14       | 17.07%  |
| 3.01-4.0        | 5        | 6.1%    |
| 24.01-32.0      | 5        | 6.1%    |
| 64.01-256.0     | 4        | 4.88%   |
| 1.01-2.0        | 2        | 2.44%   |
| More than 256.0 | 1        | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 28       | 32.94%  |
| 2.01-3.0  | 21       | 24.71%  |
| 3.01-4.0  | 17       | 20%     |
| 4.01-8.0  | 10       | 11.76%  |
| 0.51-1.0  | 5        | 5.88%   |
| 8.01-16.0 | 4        | 4.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 42.17%  |
| 2      | 21       | 25.3%   |
| 3      | 14       | 16.87%  |
| 4      | 9        | 10.84%  |
| 5      | 2        | 2.41%   |
| 0      | 2        | 2.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 59.76%  |
| Yes       | 33       | 40.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 50.6%   |
| No        | 41       | 49.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 69.51%  |
| Yes       | 25       | 30.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Singapore | 82       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Singapore         | 78       | 95.12%  |
| Jurong West       | 3        | 3.66%   |
| Queenstown Estate | 1        | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 27       | 40     | 19.42%  |
| Seagate                   | 23       | 27     | 16.55%  |
| WDC                       | 20       | 28     | 14.39%  |
| Toshiba                   | 15       | 17     | 10.79%  |
| Hitachi                   | 6        | 7      | 4.32%   |
| SanDisk                   | 5        | 6      | 3.6%    |
| Kingston                  | 5        | 7      | 3.6%    |
| Crucial                   | 4        | 5      | 2.88%   |
| JMicron Technology        | 3        | 4      | 2.16%   |
| HGST                      | 3        | 5      | 2.16%   |
| Unknown                   | 2        | 2      | 1.44%   |
| SK hynix                  | 2        | 2      | 1.44%   |
| Phison                    | 2        | 2      | 1.44%   |
| Micron/Crucial Technology | 2        | 2      | 1.44%   |
| KLEVV                     | 2        | 2      | 1.44%   |
| Intel                     | 2        | 2      | 1.44%   |
| Hewlett-Packard           | 2        | 2      | 1.44%   |
| A-DATA Technology         | 2        | 2      | 1.44%   |
| Vaseky                    | 1        | 1      | 0.72%   |
| USB30                     | 1        | 1      | 0.72%   |
| Silicon Motion            | 1        | 2      | 0.72%   |
| Plextor                   | 1        | 1      | 0.72%   |
| Pioneer                   | 1        | 1      | 0.72%   |
| OCZ                       | 1        | 1      | 0.72%   |
| Mushkin                   | 1        | 1      | 0.72%   |
| Lexar                     | 1        | 1      | 0.72%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.72%   |
| GAMER                     | 1        | 1      | 0.72%   |
| Drevo                     | 1        | 1      | 0.72%   |
| Apacer                    | 1        | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB           | 6        | 3.85%   |
| Toshiba DT01ACA200 2TB           | 4        | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 1.92%   |
| Samsung SSD 860 EVO 500GB        | 3        | 1.92%   |
| Samsung SSD 850 EVO 250GB        | 3        | 1.92%   |
| JMicron Generic 120GB            | 3        | 1.92%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 1.92%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 1.28%   |
| WDC WD6400AAKS-22A7B2 640GB      | 2        | 1.28%   |
| SK hynix SC311 SATA 128GB SSD    | 2        | 1.28%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.28%   |
| Seagate BUP Portable 4TB         | 2        | 1.28%   |
| Samsung SSD 960 EVO 250GB        | 2        | 1.28%   |
| Samsung SSD 860 EVO 1TB          | 2        | 1.28%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 1.28%   |
| Samsung NVMe SSD Drive 1024GB    | 2        | 1.28%   |
| A-DATA HC660 1TB SSD             | 2        | 1.28%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.64%   |
| WDC WDS500G1X0E-00AFY0 500GB     | 1        | 0.64%   |
| WDC WDS200T2B0C-00PXH0 2TB       | 1        | 0.64%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 1        | 0.64%   |
| WDC WD800JD-08MSA1 80GB          | 1        | 0.64%   |
| WDC WD6002FFWX-68TZ4N0 6TB       | 1        | 0.64%   |
| WDC WD5000AZLX-08K2TA0 500GB     | 1        | 0.64%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1        | 0.64%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.64%   |
| WDC WD5000AAKS-22V1A0 500GB      | 1        | 0.64%   |
| WDC WD50 EZRX-00MVLB1 5TB        | 1        | 0.64%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1        | 0.64%   |
| WDC WD40EZRX-19SPEB0 4TB         | 1        | 0.64%   |
| WDC WD30EZRX-19D8PB0 3TB         | 1        | 0.64%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.64%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.64%   |
| WDC WD15EADS-11R6B1 1TB          | 1        | 0.64%   |
| WDC WD15EADS-00R6B0 1TB          | 1        | 0.64%   |
| WDC WD10JPVT-00A1YT0 1TB         | 1        | 0.64%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 0.64%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1        | 0.64%   |
| Vaseky V800/500G 512GB           | 1        | 0.64%   |
| USB30 Disk 120GB                 | 1        | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 26     | 36.07%  |
| WDC                 | 16       | 22     | 26.23%  |
| Toshiba             | 13       | 15     | 21.31%  |
| Hitachi             | 6        | 7      | 9.84%   |
| HGST                | 3        | 5      | 4.92%   |
| Samsung Electronics | 1        | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 23     | 35.42%  |
| Kingston            | 5        | 7      | 10.42%  |
| SanDisk             | 4        | 4      | 8.33%   |
| Crucial             | 4        | 5      | 8.33%   |
| WDC                 | 2        | 2      | 4.17%   |
| SK hynix            | 2        | 2      | 4.17%   |
| Hewlett-Packard     | 2        | 2      | 4.17%   |
| A-DATA Technology   | 2        | 2      | 4.17%   |
| Vaseky              | 1        | 1      | 2.08%   |
| USB30               | 1        | 1      | 2.08%   |
| Plextor             | 1        | 1      | 2.08%   |
| Pioneer             | 1        | 1      | 2.08%   |
| OCZ                 | 1        | 1      | 2.08%   |
| Lexar               | 1        | 1      | 2.08%   |
| KLEVV               | 1        | 1      | 2.08%   |
| Intel               | 1        | 1      | 2.08%   |
| GAMER               | 1        | 1      | 2.08%   |
| Apacer              | 1        | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 52       | 76     | 42.98%  |
| SSD     | 39       | 57     | 32.23%  |
| NVMe    | 26       | 38     | 21.49%  |
| MMC     | 2        | 2      | 1.65%   |
| Unknown | 2        | 2      | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 69       | 127    | 64.49%  |
| NVMe | 25       | 34     | 23.36%  |
| SAS  | 11       | 12     | 10.28%  |
| MMC  | 2        | 2      | 1.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 44       | 66     | 45.36%  |
| 0.51-1.0   | 26       | 34     | 26.8%   |
| 1.01-2.0   | 13       | 17     | 13.4%   |
| 3.01-4.0   | 7        | 7      | 7.22%   |
| 4.01-10.0  | 4        | 6      | 4.12%   |
| 2.01-3.0   | 3        | 3      | 3.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 18       | 20.93%  |
| 101-250        | 17       | 19.77%  |
| 251-500        | 11       | 12.79%  |
| 1001-2000      | 10       | 11.63%  |
| More than 3000 | 9        | 10.47%  |
| 2001-3000      | 6        | 6.98%   |
| 1-20           | 6        | 6.98%   |
| Unknown        | 6        | 6.98%   |
| 21-50          | 3        | 3.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 23       | 26.74%  |
| 21-50          | 16       | 18.6%   |
| 101-250        | 13       | 15.12%  |
| 251-500        | 9        | 10.47%  |
| 51-100         | 8        | 9.3%    |
| Unknown        | 6        | 6.98%   |
| 501-1000       | 4        | 4.65%   |
| More than 3000 | 3        | 3.49%   |
| 1001-2000      | 3        | 3.49%   |
| 2001-3000      | 1        | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB | 2        | 3      | 25%     |
| WDC WD5000AAKS-22V1A0 500GB | 1        | 1      | 12.5%   |
| WDC WD50 EZRX-00MVLB1 5TB   | 1        | 1      | 12.5%   |
| WDC WD10EZEX-60M2NA0 1TB    | 1        | 1      | 12.5%   |
| Hitachi HDS721010CLA632 1TB | 1        | 1      | 12.5%   |
| HGST HTS545050A7E380 500GB  | 1        | 1      | 12.5%   |
| Crucial CT120M500SSD1 120GB | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 6      | 62.5%   |
| Hitachi | 1        | 1      | 12.5%   |
| HGST    | 1        | 1      | 12.5%   |
| Crucial | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 6      | 71.43%  |
| Hitachi | 1        | 1      | 14.29%  |
| HGST    | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 8      | 87.5%   |
| SSD  | 1        | 1      | 12.5%   |

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
| Detected | 49       | 98     | 53.85%  |
| Works    | 34       | 68     | 37.36%  |
| Malfunc  | 8        | 9      | 8.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 55       | 47.83%  |
| AMD                          | 25       | 21.74%  |
| Samsung Electronics          | 14       | 12.17%  |
| SanDisk                      | 5        | 4.35%   |
| Silicon Motion               | 3        | 2.61%   |
| ASMedia Technology           | 3        | 2.61%   |
| Toshiba America Info Systems | 2        | 1.74%   |
| Phison Electronics           | 2        | 1.74%   |
| Micron/Crucial Technology    | 2        | 1.74%   |
| VIA Technologies             | 1        | 0.87%   |
| Marvell Technology Group     | 1        | 0.87%   |
| KIOXIA                       | 1        | 0.87%   |
| Broadcom / LSI               | 1        | 0.87%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 11.68%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 6.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 5.84%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 5.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 3.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 3.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 3.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.92%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 2.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 2.19%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2        | 1.46%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.46%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.46%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.46%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.46%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.46%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.73%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 0.73%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.73%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.73%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.73%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.73%   |
| Micron/Crucial Non-Volatile memory controller                                           | 1        | 0.73%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.73%   |
| KIOXIA Non-Volatile memory controller                                                   | 1        | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 66       | 57.89%  |
| NVMe | 25       | 21.93%  |
| IDE  | 14       | 12.28%  |
| RAID | 8        | 7.02%   |
| SAS  | 1        | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 57       | 69.51%  |
| AMD    | 25       | 30.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 3.66%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 3.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 3.66%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 3.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 2.44%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 2.44%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 2.44%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 2.44%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 2.44%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores  | 2        | 2.44%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 2.44%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2        | 2.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 2.44%   |
| Intel Xeon W-2155 CPU @ 3.30GHz             | 1        | 1.22%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 1.22%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 1.22%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 1.22%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 1.22%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 1.22%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 1.22%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 1.22%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.22%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.22%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 1.22%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 1.22%   |
| Intel Core i9-7940X CPU @ 3.10GHz           | 1        | 1.22%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.22%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1        | 1.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.22%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.22%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1        | 1.22%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.22%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.22%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.22%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 1.22%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 24       | 29.27%  |
| Intel Core i7          | 11       | 13.41%  |
| AMD Ryzen 5            | 9        | 10.98%  |
| Intel Xeon             | 7        | 8.54%   |
| Intel Core i3          | 4        | 4.88%   |
| AMD Ryzen 7            | 4        | 4.88%   |
| Other                  | 3        | 3.66%   |
| AMD Ryzen Threadripper | 2        | 2.44%   |
| AMD Ryzen 9            | 2        | 2.44%   |
| AMD FX                 | 2        | 2.44%   |
| AMD Athlon             | 2        | 2.44%   |
| AMD A10                | 2        | 2.44%   |
| Intel Pentium Gold     | 1        | 1.22%   |
| Intel Pentium Dual     | 1        | 1.22%   |
| Intel Pentium 4        | 1        | 1.22%   |
| Intel Pentium          | 1        | 1.22%   |
| Intel Core m3          | 1        | 1.22%   |
| Intel Core i9          | 1        | 1.22%   |
| Intel Core 2 Quad      | 1        | 1.22%   |
| Intel Atom             | 1        | 1.22%   |
| AMD Ryzen 5 PRO        | 1        | 1.22%   |
| AMD Phenom II X4       | 1        | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 33       | 40.24%  |
| 6      | 16       | 19.51%  |
| 2      | 15       | 18.29%  |
| 8      | 8        | 9.76%   |
| 16     | 3        | 3.66%   |
| 12     | 3        | 3.66%   |
| 14     | 1        | 1.22%   |
| 10     | 1        | 1.22%   |
| 3      | 1        | 1.22%   |
| 1      | 1        | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 49       | 59.76%  |
| 1      | 33       | 40.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 81       | 98.78%  |
| Unknown        | 1        | 1.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 13.25%  |
| 0x306c3    | 9        | 10.84%  |
| 0x906ea    | 6        | 7.23%   |
| 0x506e3    | 6        | 7.23%   |
| 0x306a9    | 6        | 7.23%   |
| 0x20655    | 4        | 4.82%   |
| 0x08701021 | 4        | 4.82%   |
| 0x206a7    | 3        | 3.61%   |
| 0x08701013 | 3        | 3.61%   |
| 0x906e9    | 2        | 2.41%   |
| 0x50654    | 2        | 2.41%   |
| 0x406f1    | 2        | 2.41%   |
| 0x306e4    | 2        | 2.41%   |
| 0x0a201016 | 2        | 2.41%   |
| 0x06003106 | 2        | 2.41%   |
| 0x06000852 | 2        | 2.41%   |
| 0xf41      | 1        | 1.2%    |
| 0xa0671    | 1        | 1.2%    |
| 0xa0655    | 1        | 1.2%    |
| 0x90672    | 1        | 1.2%    |
| 0x6fd      | 1        | 1.2%    |
| 0x6fb      | 1        | 1.2%    |
| 0x0a201009 | 1        | 1.2%    |
| 0x08600106 | 1        | 1.2%    |
| 0x0830104d | 1        | 1.2%    |
| 0x08301039 | 1        | 1.2%    |
| 0x08108109 | 1        | 1.2%    |
| 0x08101102 | 1        | 1.2%    |
| 0x08001138 | 1        | 1.2%    |
| 0x08001137 | 1        | 1.2%    |
| 0x0600081c | 1        | 1.2%    |
| 0x010000db | 1        | 1.2%    |
| 0x01000083 | 1        | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 11       | 13.41%  |
| Zen 2            | 10       | 12.2%   |
| KabyLake         | 10       | 12.2%   |
| IvyBridge        | 9        | 10.98%  |
| Skylake          | 8        | 9.76%   |
| SandyBridge      | 5        | 6.1%    |
| Zen 3            | 4        | 4.88%   |
| Westmere         | 4        | 4.88%   |
| Zen              | 3        | 3.66%   |
| Zen+             | 2        | 2.44%   |
| Steamroller      | 2        | 2.44%   |
| Piledriver       | 2        | 2.44%   |
| K10              | 2        | 2.44%   |
| Core             | 2        | 2.44%   |
| Broadwell        | 2        | 2.44%   |
| Silvermont       | 1        | 1.22%   |
| NetBurst         | 1        | 1.22%   |
| Icelake          | 1        | 1.22%   |
| CometLake        | 1        | 1.22%   |
| Alderlake Hybrid | 1        | 1.22%   |
| Unknown          | 1        | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 36       | 37.89%  |
| Intel             | 36       | 37.89%  |
| AMD               | 22       | 23.16%  |
| ASPEED Technology | 1        | 1.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5.1%    |
| Intel HD Graphics 530                                                       | 4        | 4.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 4.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 3.06%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 3.06%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.06%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 2.04%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 2.04%   |
| Intel AlderLake-S GT1                                                       | 2        | 2.04%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.04%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 2.04%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 2        | 2.04%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.02%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.02%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.02%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.02%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.02%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.02%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.02%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.02%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.02%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.02%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.02%   |
| Nvidia GF108M [GeForce GT 425M]                                             | 1        | 1.02%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.02%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.02%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.02%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.02%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.02%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 29       | 34.12%  |
| 1 x Intel       | 27       | 31.76%  |
| 1 x AMD         | 18       | 21.18%  |
| 2 x Nvidia      | 3        | 3.53%   |
| Intel + Nvidia  | 3        | 3.53%   |
| Intel + AMD     | 3        | 3.53%   |
| 2 x AMD         | 1        | 1.18%   |
| Nvidia + ASPEED | 1        | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 58       | 69.88%  |
| Proprietary | 23       | 27.71%  |
| Unknown     | 2        | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 36.9%   |
| 1.01-2.0   | 13       | 15.48%  |
| 3.01-4.0   | 10       | 11.9%   |
| 7.01-8.0   | 8        | 9.52%   |
| 0.51-1.0   | 8        | 9.52%   |
| 8.01-16.0  | 7        | 8.33%   |
| 5.01-6.0   | 4        | 4.76%   |
| 0.01-0.5   | 3        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 24       | 29.63%  |
| Samsung Electronics  | 7        | 8.64%   |
| Goldstar             | 7        | 8.64%   |
| Acer                 | 7        | 8.64%   |
| Hewlett-Packard      | 4        | 4.94%   |
| AOC                  | 4        | 4.94%   |
| PRISM+               | 3        | 3.7%    |
| Denver               | 3        | 3.7%    |
| Philips              | 2        | 2.47%   |
| Lenovo Group Limited | 2        | 2.47%   |
| Ancor Communications | 2        | 2.47%   |
| Wacom                | 1        | 1.23%   |
| ViewSonic            | 1        | 1.23%   |
| Sony                 | 1        | 1.23%   |
| Sharp                | 1        | 1.23%   |
| SGT                  | 1        | 1.23%   |
| SAC                  | 1        | 1.23%   |
| RTK                  | 1        | 1.23%   |
| Pixio                | 1        | 1.23%   |
| MSI                  | 1        | 1.23%   |
| Lenovo               | 1        | 1.23%   |
| HPN                  | 1        | 1.23%   |
| CVT                  | 1        | 1.23%   |
| CHR                  | 1        | 1.23%   |
| BenQ                 | 1        | 1.23%   |
| AU Optronics         | 1        | 1.23%   |
| ASUSTek Computer     | 1        | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 3        | 3.57%   |
| PRISM+ X315 INN3200 2560x1440 697x393mm 31.5-inch                     | 2        | 2.38%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2        | 2.38%   |
| Denver F240v LHC0236 1920x1080 530x280mm 23.6-inch                    | 2        | 2.38%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                   | 2        | 2.38%   |
| Dell S2340L DELD058 1920x1080 510x290mm 23.1-inch                     | 2        | 2.38%   |
| Dell LCD Monitor P2217H 1920x1080                                     | 2        | 2.38%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                     | 2        | 2.38%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                      | 2        | 2.38%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                      | 2        | 2.38%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                   | 2        | 2.38%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1        | 1.19%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                             | 1        | 1.19%   |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                         | 1        | 1.19%   |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                      | 1        | 1.19%   |
| SGT AoXinYuan SGT0156 1920x1080 345x194mm 15.6-inch                   | 1        | 1.19%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1        | 1.19%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1        | 1.19%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1        | 1.19%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch | 1        | 1.19%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 1        | 1.19%   |
| Samsung Electronics LCD Monitor S27A950D 1920x1080                    | 1        | 1.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1        | 1.19%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 1.19%   |
| RTK FHD HDR RTKBC32 1920x1080 332x186mm 15.0-inch                     | 1        | 1.19%   |
| PRISM+ P270 INN2700 3840x2160 597x336mm 27.0-inch                     | 1        | 1.19%   |
| Pixio XRGB27WQ WAM2700 2560x1440 530x280mm 23.6-inch                  | 1        | 1.19%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch               | 1        | 1.19%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                 | 1        | 1.19%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                       | 1        | 1.19%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1        | 1.19%   |
| Lenovo Group Limited LCD Monitor LEN T27i-10 1920x1080                | 1        | 1.19%   |
| Lenovo Group Limited LCD Monitor LEN LS2323wA 1920x1080               | 1        | 1.19%   |
| HPN LCD Monitor HP E243 1920x1080                                     | 1        | 1.19%   |
| Hewlett-Packard L1950 HWP26E8 1280x1024 380x300mm 19.1-inch           | 1        | 1.19%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 1        | 1.19%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch            | 1        | 1.19%   |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch             | 1        | 1.19%   |
| Goldstar IPS224 GSM58D5 1920x1080 477x268mm 21.5-inch                 | 1        | 1.19%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1        | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 44       | 54.32%  |
| 2560x1440 (QHD)    | 12       | 14.81%  |
| 3840x2160 (4K)     | 11       | 13.58%  |
| 1600x900 (HD+)     | 7        | 8.64%   |
| 1360x768           | 2        | 2.47%   |
| 2560x1080          | 1        | 1.23%   |
| 1680x1050 (WSXGA+) | 1        | 1.23%   |
| 1440x900 (WXGA+)   | 1        | 1.23%   |
| 1366x768 (WXGA)    | 1        | 1.23%   |
| 1280x1024 (SXGA)   | 1        | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 13       | 16.25%  |
| 24      | 11       | 13.75%  |
| 23      | 11       | 13.75%  |
| Unknown | 11       | 13.75%  |
| 21      | 7        | 8.75%   |
| 20      | 6        | 7.5%    |
| 31      | 4        | 5%      |
| 18      | 4        | 5%      |
| 19      | 3        | 3.75%   |
| 28      | 2        | 2.5%    |
| 15      | 2        | 2.5%    |
| 84      | 1        | 1.25%   |
| 55      | 1        | 1.25%   |
| 39      | 1        | 1.25%   |
| 32      | 1        | 1.25%   |
| 25      | 1        | 1.25%   |
| 22      | 1        | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 36       | 45%     |
| 401-500     | 19       | 23.75%  |
| Unknown     | 11       | 13.75%  |
| 601-700     | 6        | 7.5%    |
| 351-400     | 2        | 2.5%    |
| 301-350     | 2        | 2.5%    |
| 801-900     | 1        | 1.25%   |
| 701-800     | 1        | 1.25%   |
| 1501-2000   | 1        | 1.25%   |
| 1001-1500   | 1        | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 61       | 78.21%  |
| Unknown | 10       | 12.82%  |
| 16/10   | 4        | 5.13%   |
| 6/5     | 1        | 1.28%   |
| 5/4     | 1        | 1.28%   |
| 21/9    | 1        | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 30.38%  |
| 301-350        | 13       | 16.46%  |
| 151-200        | 11       | 13.92%  |
| Unknown        | 11       | 13.92%  |
| 351-500        | 6        | 7.59%   |
| 251-300        | 6        | 7.59%   |
| 141-150        | 3        | 3.8%    |
| More than 1000 | 2        | 2.53%   |
| 101-110        | 2        | 2.53%   |
| 501-1000       | 1        | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 45       | 56.25%  |
| 101-120 | 12       | 15%     |
| Unknown | 11       | 13.75%  |
| 121-160 | 6        | 7.5%    |
| 161-240 | 5        | 6.25%   |
| 1-50    | 1        | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 74       | 88.1%   |
| 2     | 6        | 7.14%   |
| 0     | 4        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 49       | 40.83%  |
| Realtek Semiconductor | 46       | 38.33%  |
| Qualcomm Atheros      | 9        | 7.5%    |
| TP-Link               | 4        | 3.33%   |
| Broadcom              | 4        | 3.33%   |
| Samsung Electronics   | 2        | 1.67%   |
| Linksys               | 1        | 0.83%   |
| Hewlett-Packard       | 1        | 0.83%   |
| Fargo                 | 1        | 0.83%   |
| Exar                  | 1        | 0.83%   |
| Edimax Technology     | 1        | 0.83%   |
| Aquantia              | 1        | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 21.9%   |
| Intel Wi-Fi 6 AX200                                               | 13       | 9.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 5.11%   |
| Intel I211 Gigabit Network Connection                             | 7        | 5.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.38%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.92%   |
| Intel Ethernet Controller I225-V                                  | 3        | 2.19%   |
| Intel Ethernet Connection I217-V                                  | 3        | 2.19%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.19%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 2.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3        | 2.19%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 2        | 1.46%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 1.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.46%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 1.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 1.46%   |
| Intel Wireless 3165                                               | 2        | 1.46%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.46%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.73%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.73%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.73%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.73%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.73%   |
| Realtek 802.11ac NIC                                              | 1        | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.73%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.73%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.73%   |
| Intel Wireless-AC 9260                                            | 1        | 0.73%   |
| Intel Wireless 8260                                               | 1        | 0.73%   |
| Intel Wireless 7260                                               | 1        | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 22       | 51.16%  |
| Realtek Semiconductor | 7        | 16.28%  |
| TP-Link               | 4        | 9.3%    |
| Qualcomm Atheros      | 4        | 9.3%    |
| Broadcom              | 4        | 9.3%    |
| Linksys               | 1        | 2.33%   |
| Edimax Technology     | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13       | 30.23%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3        | 6.98%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 2        | 4.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2        | 4.65%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2        | 4.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2        | 4.65%   |
| Intel Wireless 3165                                            | 2        | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 2.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 2.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 2.33%   |
| Realtek 802.11ac NIC                                           | 1        | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 2.33%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 2.33%   |
| Intel Wireless-AC 9260                                         | 1        | 2.33%   |
| Intel Wireless 8260                                            | 1        | 2.33%   |
| Intel Wireless 7260                                            | 1        | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 2.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 2.33%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                           | 1        | 2.33%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 41       | 46.07%  |
| Intel                 | 39       | 43.82%  |
| Qualcomm Atheros      | 5        | 5.62%   |
| Samsung Electronics   | 2        | 2.25%   |
| Hewlett-Packard       | 1        | 1.12%   |
| Aquantia              | 1        | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 32.61%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7        | 7.61%   |
| Intel I211 Gigabit Network Connection                             | 7        | 7.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 6.52%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 4.35%   |
| Intel Ethernet Controller I225-V                                  | 3        | 3.26%   |
| Intel Ethernet Connection I217-V                                  | 3        | 3.26%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.26%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 3.26%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.17%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 2.17%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 2.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.09%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.09%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.09%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.09%   |
| Intel Ethernet Controller X550                                    | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.09%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.09%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.09%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.09%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.09%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1        | 1.09%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 65.08%  |
| WiFi     | 42       | 33.33%  |
| Modem    | 1        | 0.79%   |
| Unknown  | 1        | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 75.58%  |
| WiFi     | 20       | 23.26%  |
| Unknown  | 1        | 1.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 56.1%   |
| 2     | 31       | 37.8%   |
| 3     | 4        | 4.88%   |
| 0     | 1        | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 78       | 95.12%  |
| Yes  | 4        | 4.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 58.62%  |
| Cambridge Silicon Radio         | 5        | 17.24%  |
| TP-Link                         | 3        | 10.34%  |
| SINO WEALTH                     | 1        | 3.45%   |
| Realtek Semiconductor           | 1        | 3.45%   |
| Qualcomm Atheros Communications | 1        | 3.45%   |
| Broadcom                        | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 10       | 34.48%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 17.24%  |
| Intel Bluetooth wireless interface                  | 4        | 13.79%  |
| TP-Link UB500 Adapter                               | 3        | 10.34%  |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.45%   |
| Intel AX210 Bluetooth                               | 1        | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 56       | 43.41%  |
| Nvidia                      | 35       | 27.13%  |
| AMD                         | 28       | 21.71%  |
| XMOS                        | 1        | 0.78%   |
| Unknown                     | 1        | 0.78%   |
| SteelSeries ApS             | 1        | 0.78%   |
| Sony                        | 1        | 0.78%   |
| Samson Technologies         | 1        | 0.78%   |
| Realtek Semiconductor       | 1        | 0.78%   |
| Micro Star International    | 1        | 0.78%   |
| JMTek                       | 1        | 0.78%   |
| FiiO Electronics Technology | 1        | 0.78%   |
| C-Media Electronics         | 1        | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 7.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 6.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 4.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.97%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 3.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 3.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 2.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 2.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 2.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.99%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 1.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.99%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 1.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.99%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.99%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.32%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.32%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.32%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.32%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1        | 0.66%   |
| Unknown Realtek USB Audio Rear                                             | 1        | 0.66%   |
| Unknown Realtek USB Audio Front                                            | 1        | 0.66%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1        | 0.66%   |
| Sony WALKMAN                                                               | 1        | 0.66%   |
| Samson Technologies Meteor condenser microphone                            | 1        | 0.66%   |
| Realtek Semiconductor USB Audio                                            | 1        | 0.66%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.66%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.66%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Kingston                       | 10       | 18.52%  |
| G.Skill                        | 6        | 11.11%  |
| Crucial                        | 6        | 11.11%  |
| Corsair                        | 6        | 11.11%  |
| SK hynix                       | 5        | 9.26%   |
| Samsung Electronics            | 4        | 7.41%   |
| Micron Technology              | 4        | 7.41%   |
| Transcend                      | 2        | 3.7%    |
| Kingmax                        | 2        | 3.7%    |
| Unknown                        | 1        | 1.85%   |
| Qimonda                        | 1        | 1.85%   |
| Patriot                        | 1        | 1.85%   |
| Nanya Technology               | 1        | 1.85%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1        | 1.85%   |
| KLEVV                          | 1        | 1.85%   |
| Essencore Limited              | 1        | 1.85%   |
| ASint Technology               | 1        | 1.85%   |
| A-DATA Technology              | 1        | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                      | 2        | 3.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                 | 2        | 3.33%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s               | 2        | 3.33%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s              | 2        | 3.33%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s                 | 2        | 3.33%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                | 1        | 1.67%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1        | 1.67%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                    | 1        | 1.67%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                   | 1        | 1.67%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1        | 1.67%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 1.67%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1        | 1.67%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1        | 1.67%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1        | 1.67%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s                 | 1        | 1.67%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                 | 1        | 1.67%   |
| Samsung RAM M378A2K43CB1-CRC 16GB DIMM DDR4 2400MT/s                | 1        | 1.67%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                 | 1        | 1.67%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s              | 1        | 1.67%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s                    | 1        | 1.67%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s                  | 1        | 1.67%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s                  | 1        | 1.67%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER RAM Module 2048MB DIMM DDR3 1600MT/s | 1        | 1.67%   |
| Micron RAM TEAMGROUP-UD4-2133 16384MB DIMM DDR4 2134MT/s            | 1        | 1.67%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s                 | 1        | 1.67%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s                  | 1        | 1.67%   |
| Micron RAM 16ATF2G64AZ-2G6E1 16GB DIMM DDR4 2667MT/s                | 1        | 1.67%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s                  | 1        | 1.67%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 1        | 1.67%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s                 | 1        | 1.67%   |
| Kingston RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1        | 1.67%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3                        | 1        | 1.67%   |
| Kingston RAM 99U5469-051.A00LF 4GB SODIMM DDR3 1600MT/s             | 1        | 1.67%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s               | 1        | 1.67%   |
| Kingston RAM 9905417-082.A00G 4GB SODIMM DDR3 1600MT/s              | 1        | 1.67%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s               | 1        | 1.67%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s              | 1        | 1.67%   |
| G.Skill RAM F3-2400C11-8GXM 8192MB DIMM DDR3 2400MT/s               | 1        | 1.67%   |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s                  | 1        | 1.67%   |
| Essencore Limited RAM KD48GU880-32A160U 8GB DIMM DDR4 2667MT/s      | 1        | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 27       | 58.7%   |
| DDR3    | 15       | 32.61%  |
| DDR2    | 2        | 4.35%   |
| SDRAM   | 1        | 2.17%   |
| Unknown | 1        | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 44       | 97.78%  |
| SODIMM | 1        | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 33.33%  |
| 4096  | 14       | 27.45%  |
| 16384 | 11       | 21.57%  |
| 2048  | 5        | 9.8%    |
| 32768 | 3        | 5.88%   |
| 1024  | 1        | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 11       | 19.64%  |
| 2400  | 9        | 16.07%  |
| 3200  | 7        | 12.5%   |
| 3600  | 4        | 7.14%   |
| 2133  | 4        | 7.14%   |
| 2667  | 3        | 5.36%   |
| 3400  | 2        | 3.57%   |
| 2666  | 2        | 3.57%   |
| 2048  | 2        | 3.57%   |
| 1866  | 2        | 3.57%   |
| 1800  | 2        | 3.57%   |
| 1333  | 2        | 3.57%   |
| 4333  | 1        | 1.79%   |
| 3666  | 1        | 1.79%   |
| 2200  | 1        | 1.79%   |
| 2134  | 1        | 1.79%   |
| 1867  | 1        | 1.79%   |
| 667   | 1        | 1.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Samsung M2020 Series | 1        | 100%    |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech              | 3        | 60%     |
| Realtek Semiconductor | 1        | 20%     |
| Alcor Micro           | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech HD Webcam C615       | 2        | 40%     |
| Realtek Asus laptop camera    | 1        | 20%     |
| Logitech Webcam C310          | 1        | 20%     |
| Alcor Micro USB 2.0 PC Camera | 1        | 20%     |

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
| 0     | 70       | 85.37%  |
| 1     | 12       | 14.63%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 5        | 41.67%  |
| Unassigned class | 2        | 16.67%  |
| Network          | 2        | 16.67%  |
| Graphics card    | 2        | 16.67%  |
| Net/ethernet     | 1        | 8.33%   |


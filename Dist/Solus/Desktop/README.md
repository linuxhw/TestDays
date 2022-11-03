Solus - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Solus.

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

Total: 101

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock     | X570M Pro4                  | [087a173c0d](https://linux-hardware.org/?probe=087a173c0d) | Oct 08, 2022 |
| Unknown    | TB-4000                     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| Unknown    | TB-4000                     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Unknown    | TB-4000                     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| Lenovo     | CRESCENTBAY 31900058 STD    | [f42a689093](https://linux-hardware.org/?probe=f42a689093) | Jun 10, 2022 |
| Gigabyte   | Z68AP-D3                    | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| ASUSTek    | B85M-E                      | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| ASUSTek    | B85M-E                      | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| ASUSTek    | TUF Gaming X570-PRO         | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| MSI        | B450M MORTAR                | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Gigabyte   | F2A68HM-H                   | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu    | D3227-A1 S26361-D3227-A1    | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Gigabyte   | GA-MA770-UD3                | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Unknown    | HX90                        | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Unknown    | HX90                        | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown    | HX90                        | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| ASUSTek    | A88X-PRO                    | [fb6f0426c3](https://linux-hardware.org/?probe=fb6f0426c3) | Jan 20, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Dell       | 06X1TJ A00                  | [315e535dd5](https://linux-hardware.org/?probe=315e535dd5) | Dec 21, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [d65256bf72](https://linux-hardware.org/?probe=d65256bf72) | Dec 12, 2021 |
| Gigabyte   | H110M-DS2V-CF               | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte   | H110M-DS2V-CF               | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MEGA       | G41T-M7 LGT                 | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Gigabyte   | B85M-D3H                    | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| MSI        | B350 TOMAHAWK ARCTIC        | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| ASRock     | X470 Master SLI             | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| HP         | 805F                        | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| LattePanda | Alpha                       | [cfe529288b](https://linux-hardware.org/?probe=cfe529288b) | Oct 26, 2021 |
| Biostar    | H61MLV2                     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| Gigabyte   | GA-78LMT-USB3               | [99c69c213a](https://linux-hardware.org/?probe=99c69c213a) | Sep 05, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | [f7d38e2f91](https://linux-hardware.org/?probe=f7d38e2f91) | Aug 29, 2021 |
| Gigabyte   | P31-ES3G                    | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte   | P31-ES3G                    | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| eMachines  | EL1852G                     | [7683cbf5bb](https://linux-hardware.org/?probe=7683cbf5bb) | Aug 16, 2021 |
| eMachines  | EL1852G                     | [86003fc5b7](https://linux-hardware.org/?probe=86003fc5b7) | Aug 15, 2021 |
| Gigabyte   | H81M-S2V                    | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte   | H81M-S2V                    | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | [b6ae0cb479](https://linux-hardware.org/?probe=b6ae0cb479) | Aug 05, 2021 |
| Gigabyte   | B360M AORUS Gaming 3-CF     | [fc89bec579](https://linux-hardware.org/?probe=fc89bec579) | Jul 16, 2021 |
| Lenovo     | ThinkCentre M71e 3157G6S    | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| Biostar    | A320MH                      | [2c478119e9](https://linux-hardware.org/?probe=2c478119e9) | Jun 30, 2021 |
| Dell       | 06X1TJ A00                  | [4fc48865ef](https://linux-hardware.org/?probe=4fc48865ef) | Jun 15, 2021 |
| Gigabyte   | B360M AORUS Gaming 3-CF     | [f5c8f64400](https://linux-hardware.org/?probe=f5c8f64400) | Jun 03, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | [dfa5c022b3](https://linux-hardware.org/?probe=dfa5c022b3) | May 26, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | [a33e231e6b](https://linux-hardware.org/?probe=a33e231e6b) | May 23, 2021 |
| Shuttle    | FS35V4                      | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle    | FS35V4                      | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| ASUSTek    | P9X79 DELUXE                | [f759ad1793](https://linux-hardware.org/?probe=f759ad1793) | May 13, 2021 |
| ASUSTek    | P9X79 DELUXE                | [f28f1ea67d](https://linux-hardware.org/?probe=f28f1ea67d) | May 13, 2021 |
| Intel      | X99 V102                    | [bc57aedd09](https://linux-hardware.org/?probe=bc57aedd09) | May 02, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [b5f3f78ddb](https://linux-hardware.org/?probe=b5f3f78ddb) | Apr 25, 2021 |
| Dell       | 0FH884                      | [93acc58efb](https://linux-hardware.org/?probe=93acc58efb) | Apr 10, 2021 |
| ASUSTek    | PRIME Z390-P                | [accdafb993](https://linux-hardware.org/?probe=accdafb993) | Mar 08, 2021 |
| Gigabyte   | J4005ND2P-CF                | [f4e39d4730](https://linux-hardware.org/?probe=f4e39d4730) | Mar 04, 2021 |
| ASUSTek    | PRIME Z390-P                | [cdd0998f7c](https://linux-hardware.org/?probe=cdd0998f7c) | Feb 14, 2021 |
| ASUSTek    | PRIME Z390-P                | [f4ee71d37f](https://linux-hardware.org/?probe=f4ee71d37f) | Feb 12, 2021 |
| Gigabyte   | H61M-HD2                    | [78c877458a](https://linux-hardware.org/?probe=78c877458a) | Jan 28, 2021 |
| Gigabyte   | H61M-HD2                    | [6caba093b5](https://linux-hardware.org/?probe=6caba093b5) | Jan 24, 2021 |
| MSI        | 990FXA-GD65                 | [f8c2afa143](https://linux-hardware.org/?probe=f8c2afa143) | Jan 20, 2021 |
| ASRock     | B550M-ITX/ac                | [f69556d436](https://linux-hardware.org/?probe=f69556d436) | Jan 15, 2021 |
| Gigabyte   | Z390 D                      | [010be27c6a](https://linux-hardware.org/?probe=010be27c6a) | Jan 11, 2021 |
| ASRock     | X470 Master SLI             | [f2c8ec14c7](https://linux-hardware.org/?probe=f2c8ec14c7) | Jan 02, 2021 |
| MSI        | MAG B550 TOMAHAWK           | [8e3d2a963b](https://linux-hardware.org/?probe=8e3d2a963b) | Nov 18, 2020 |
| ASUSTek    | PRIME X370-A                | [c8f850e40f](https://linux-hardware.org/?probe=c8f850e40f) | Nov 15, 2020 |
| ASUSTek    | PRIME X370-A                | [c86804a559](https://linux-hardware.org/?probe=c86804a559) | Nov 14, 2020 |
| Gigabyte   | B85M-D3H                    | [cdd1a3be02](https://linux-hardware.org/?probe=cdd1a3be02) | Nov 07, 2020 |
| ASRock     | X570 Steel Legend           | [80550be62d](https://linux-hardware.org/?probe=80550be62d) | Sep 28, 2020 |
| ASRock     | X470 Master SLI             | [9968dc910c](https://linux-hardware.org/?probe=9968dc910c) | Sep 10, 2020 |
| ASRock     | X470 Master SLI             | [2ae445db73](https://linux-hardware.org/?probe=2ae445db73) | Sep 10, 2020 |
| Dell       | 0M017G A00                  | [e51b08ee63](https://linux-hardware.org/?probe=e51b08ee63) | Sep 08, 2020 |
| MSI        | B450M PRO-M2 V2             | [5e2142357f](https://linux-hardware.org/?probe=5e2142357f) | Sep 08, 2020 |
| MSI        | 990FXA-GD65                 | [e60be6cba2](https://linux-hardware.org/?probe=e60be6cba2) | Sep 06, 2020 |
| Gigabyte   | Z390 AORUS PRO WIFI-CF      | [4bf4f029df](https://linux-hardware.org/?probe=4bf4f029df) | Sep 03, 2020 |
| MSI        | B450 GAMING PRO CARBON A... | [aca54beb89](https://linux-hardware.org/?probe=aca54beb89) | Sep 02, 2020 |
| MSI        | B450 GAMING PRO CARBON A... | [d150d7a9ea](https://linux-hardware.org/?probe=d150d7a9ea) | Sep 02, 2020 |
| Pegatron   | IPM31G                      | [ed7c9fc9dc](https://linux-hardware.org/?probe=ed7c9fc9dc) | Jul 24, 2020 |
| MSI        | H87-G41 PC Mate             | [6081e4a770](https://linux-hardware.org/?probe=6081e4a770) | Jun 07, 2020 |
| MSI        | H310M PRO-M2 PLUS           | [5d852ecca8](https://linux-hardware.org/?probe=5d852ecca8) | Jun 06, 2020 |
| MSI        | H87-G41 PC Mate             | [b3513301a1](https://linux-hardware.org/?probe=b3513301a1) | May 08, 2020 |
| MSI        | H87-G41 PC Mate             | [acad555779](https://linux-hardware.org/?probe=acad555779) | Apr 01, 2020 |
| Lenovo     | IdeaCentre K320 10031       | [ef01565711](https://linux-hardware.org/?probe=ef01565711) | Apr 01, 2020 |
| Lenovo     | IdeaCentre K320 10031       | [7c54db2820](https://linux-hardware.org/?probe=7c54db2820) | Apr 01, 2020 |
| ASUSTek    | P5PL2                       | [19fbc6cfd3](https://linux-hardware.org/?probe=19fbc6cfd3) | Mar 25, 2020 |
| Gigabyte   | GA-890XA-UD3                | [e2cafdec0d](https://linux-hardware.org/?probe=e2cafdec0d) | Mar 09, 2020 |
| MSI        | 990FXA-GD65                 | [fdc69c0b70](https://linux-hardware.org/?probe=fdc69c0b70) | Feb 08, 2020 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [771600b1ae](https://linux-hardware.org/?probe=771600b1ae) | Feb 07, 2020 |
| MSI        | 990FXA-GD65                 | [4060a4338e](https://linux-hardware.org/?probe=4060a4338e) | Feb 05, 2020 |
| Gigabyte   | X570 AORUS MASTER           | [ad271d2feb](https://linux-hardware.org/?probe=ad271d2feb) | Dec 28, 2019 |
| Gigabyte   | X570 AORUS MASTER           | [627975dcd4](https://linux-hardware.org/?probe=627975dcd4) | Dec 18, 2019 |
| ASUSTek    | Maximus IV Extreme          | [b0d238eb2e](https://linux-hardware.org/?probe=b0d238eb2e) | Dec 11, 2019 |
| ASUSTek    | Maximus IV Extreme          | [9f6135476f](https://linux-hardware.org/?probe=9f6135476f) | Dec 10, 2019 |
| Gigabyte   | Z390 DESIGNARE-CF           | [2395d81be3](https://linux-hardware.org/?probe=2395d81be3) | Nov 15, 2019 |
| Gigabyte   | Z390 DESIGNARE-CF           | [7f6fec93cc](https://linux-hardware.org/?probe=7f6fec93cc) | Nov 15, 2019 |
| ASUSTek    | STRIX Z270I GAMING          | [9e0b67b32e](https://linux-hardware.org/?probe=9e0b67b32e) | May 05, 2019 |
| ASUSTek    | PRIME X470-PRO              | [d61154eabe](https://linux-hardware.org/?probe=d61154eabe) | Apr 16, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Solus 4.3 | 29       | 45.31%  |
| Solus 4.1 | 19       | 29.69%  |
| Solus 4.2 | 11       | 17.19%  |
| Solus 4.0 | 5        | 7.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Solus | 60       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.6.19-158.current  | 6        | 8.45%   |
| 5.15.32-213.current | 5        | 7.04%   |
| 5.14.21-210.current | 4        | 5.63%   |
| 5.14.16-205.current | 4        | 5.63%   |
| 5.6.19-159.current  | 3        | 4.23%   |
| 5.4.12-144.current  | 3        | 4.23%   |
| 5.13.12-193.current | 3        | 4.23%   |
| 5.11.12-177.current | 3        | 4.23%   |
| 5.6.13-153.current  | 2        | 2.82%   |
| 5.5.7-150.current   | 2        | 2.82%   |
| 5.15.50-216.current | 2        | 2.82%   |
| 5.15.43-215.current | 2        | 2.82%   |
| 5.15.30-212.current | 2        | 2.82%   |
| 5.14.14-202.current | 2        | 2.82%   |
| 5.13.6-190.current  | 2        | 2.82%   |
| 5.13.1-187.current  | 2        | 2.82%   |
| 5.11.16-178.current | 2        | 2.82%   |
| 5.10.7-168.current  | 2        | 2.82%   |
| 5.10.5-167.current  | 2        | 2.82%   |
| 5.10.15-172.current | 2        | 2.82%   |
| 5.6.4-152.current   | 1        | 1.41%   |
| 5.6.18-156.current  | 1        | 1.41%   |
| 5.5.11-151.current  | 1        | 1.41%   |
| 5.4.1-137.current   | 1        | 1.41%   |
| 5.3.8-133.current   | 1        | 1.41%   |
| 5.15.68-218.current | 1        | 1.41%   |
| 5.15.26-211.current | 1        | 1.41%   |
| 5.13.8-191.current  | 1        | 1.41%   |
| 5.12.13-185.current | 1        | 1.41%   |
| 5.11.22-180.current | 1        | 1.41%   |
| 5.11.21-179.current | 1        | 1.41%   |
| 5.10.9-169.current  | 1        | 1.41%   |
| 5.0.5-113.current   | 1        | 1.41%   |
| 4.9.168-129.lts     | 1        | 1.41%   |
| 4.20.16-112.current | 1        | 1.41%   |
| 4.14.189-161.lts    | 1        | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.6.19   | 9        | 12.68%  |
| 5.15.32  | 5        | 7.04%   |
| 5.14.21  | 4        | 5.63%   |
| 5.14.16  | 4        | 5.63%   |
| 5.4.12   | 3        | 4.23%   |
| 5.13.12  | 3        | 4.23%   |
| 5.11.12  | 3        | 4.23%   |
| 5.6.13   | 2        | 2.82%   |
| 5.5.7    | 2        | 2.82%   |
| 5.15.50  | 2        | 2.82%   |
| 5.15.43  | 2        | 2.82%   |
| 5.15.30  | 2        | 2.82%   |
| 5.14.14  | 2        | 2.82%   |
| 5.13.6   | 2        | 2.82%   |
| 5.13.1   | 2        | 2.82%   |
| 5.11.16  | 2        | 2.82%   |
| 5.10.7   | 2        | 2.82%   |
| 5.10.5   | 2        | 2.82%   |
| 5.10.15  | 2        | 2.82%   |
| 5.6.4    | 1        | 1.41%   |
| 5.6.18   | 1        | 1.41%   |
| 5.5.11   | 1        | 1.41%   |
| 5.4.1    | 1        | 1.41%   |
| 5.3.8    | 1        | 1.41%   |
| 5.15.68  | 1        | 1.41%   |
| 5.15.26  | 1        | 1.41%   |
| 5.13.8   | 1        | 1.41%   |
| 5.12.13  | 1        | 1.41%   |
| 5.11.22  | 1        | 1.41%   |
| 5.11.21  | 1        | 1.41%   |
| 5.10.9   | 1        | 1.41%   |
| 5.0.5    | 1        | 1.41%   |
| 4.9.168  | 1        | 1.41%   |
| 4.20.16  | 1        | 1.41%   |
| 4.14.189 | 1        | 1.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.6     | 12       | 17.39%  |
| 5.15    | 12       | 17.39%  |
| 5.14    | 10       | 14.49%  |
| 5.13    | 8        | 11.59%  |
| 5.11    | 7        | 10.14%  |
| 5.10    | 7        | 10.14%  |
| 5.4     | 4        | 5.8%    |
| 5.5     | 3        | 4.35%   |
| 5.3     | 1        | 1.45%   |
| 5.12    | 1        | 1.45%   |
| 5.0     | 1        | 1.45%   |
| 4.9     | 1        | 1.45%   |
| 4.20    | 1        | 1.45%   |
| 4.14    | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 60       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Budgie  | 42       | 67.74%  |
| KDE     | 6        | 9.68%   |
| GNOME   | 6        | 9.68%   |
| Unknown | 5        | 8.06%   |
| KDE5    | 2        | 3.23%   |
| MATE    | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 59       | 98.33%  |
| Wayland | 1        | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 81.97%  |
| LightDM | 6        | 9.84%   |
| TDM     | 3        | 4.92%   |
| SDDM    | 2        | 3.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 25       | 40.98%  |
| ru_RU   | 6        | 9.84%   |
| pt_BR   | 5        | 8.2%    |
| de_DE   | 5        | 8.2%    |
| fr_FR   | 4        | 6.56%   |
| es_ES   | 3        | 4.92%   |
| en_GB   | 2        | 3.28%   |
| Unknown | 2        | 3.28%   |
| pt_PT   | 1        | 1.64%   |
| pl_PL   | 1        | 1.64%   |
| nl_NL   | 1        | 1.64%   |
| es_VE   | 1        | 1.64%   |
| en_IE   | 1        | 1.64%   |
| en_DK   | 1        | 1.64%   |
| en_AU   | 1        | 1.64%   |
| ar_SA   | 1        | 1.64%   |
| ar_EG   | 1        | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 50%     |
| EFI  | 30       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 57       | 93.44%  |
| Unknown | 2        | 3.28%   |
| Xfs     | 1        | 1.64%   |
| Btrfs   | 1        | 1.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 52       | 82.54%  |
| GPT     | 7        | 11.11%  |
| MBR     | 4        | 6.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 90.16%  |
| Yes       | 6        | 9.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 78.13%  |
| Yes       | 14       | 21.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 17       | 28.33%  |
| ASUSTek Computer    | 13       | 21.67%  |
| MSI                 | 7        | 11.67%  |
| ASRock              | 6        | 10%     |
| Lenovo              | 3        | 5%      |
| Dell                | 3        | 5%      |
| Biostar             | 2        | 3.33%   |
| Unknown             | 2        | 3.33%   |
| Shuttle             | 1        | 1.67%   |
| Pegatron            | 1        | 1.67%   |
| MEGA                | 1        | 1.67%   |
| Intel               | 1        | 1.67%   |
| Hewlett-Packard     | 1        | 1.67%   |
| Fujitsu             | 1        | 1.67%   |
| eMachines           | 1        | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 2        | 3.33%   |
| Shuttle XS35V4                   | 1        | 1.67%   |
| Pegatron IPM31                   | 1        | 1.67%   |
| MSI MS-7C91                      | 1        | 1.67%   |
| MSI MS-7B89                      | 1        | 1.67%   |
| MSI MS-7B85                      | 1        | 1.67%   |
| MSI MS-7B84                      | 1        | 1.67%   |
| MSI MS-7A34                      | 1        | 1.67%   |
| MSI MS-7850                      | 1        | 1.67%   |
| MSI MS-7640                      | 1        | 1.67%   |
| MEGA G41T-M7 LGT                 | 1        | 1.67%   |
| Lenovo ThinkCentre M71e 3157G6S  | 1        | 1.67%   |
| Lenovo IdeaCentre K320 10031     | 1        | 1.67%   |
| Lenovo C50-30 F0B1002EFR         | 1        | 1.67%   |
| Intel X99 V102                   | 1        | 1.67%   |
| HP ProDesk 490 G3 MT Business PC | 1        | 1.67%   |
| Gigabyte Z68AP-D3                | 1        | 1.67%   |
| Gigabyte Z390 DESIGNARE          | 1        | 1.67%   |
| Gigabyte Z390 D                  | 1        | 1.67%   |
| Gigabyte Z390 AORUS PRO WIFI     | 1        | 1.67%   |
| Gigabyte Z390 AORUS ELITE        | 1        | 1.67%   |
| Gigabyte X570 AORUS MASTER       | 1        | 1.67%   |
| Gigabyte P31-ES3G                | 1        | 1.67%   |
| Gigabyte J4005ND2P-CF            | 1        | 1.67%   |
| Gigabyte H81M-S2V                | 1        | 1.67%   |
| Gigabyte H61M-HD2                | 1        | 1.67%   |
| Gigabyte H110M-DS2V              | 1        | 1.67%   |
| Gigabyte GA-MA770-UD3            | 1        | 1.67%   |
| Gigabyte GA-890XA-UD3            | 1        | 1.67%   |
| Gigabyte GA-78LMT-USB3 6.0       | 1        | 1.67%   |
| Gigabyte F2A68HM-H               | 1        | 1.67%   |
| Gigabyte B85M-D3H                | 1        | 1.67%   |
| Gigabyte B360M AORUS Gaming 3    | 1        | 1.67%   |
| Fujitsu CELSIUS W530             | 1        | 1.67%   |
| eMachines EL1852G                | 1        | 1.67%   |
| Dell Studio 540                  | 1        | 1.67%   |
| Dell OptiPlex GX620              | 1        | 1.67%   |
| Dell OptiPlex 9020               | 1        | 1.67%   |
| Biostar H61MLV2                  | 1        | 1.67%   |
| Biostar A320MH                   | 1        | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte Z390          | 4        | 6.67%   |
| ASUS PRIME             | 3        | 5%      |
| Dell OptiPlex          | 2        | 3.33%   |
| ASUS TUF               | 2        | 3.33%   |
| ASUS ROG               | 2        | 3.33%   |
| Unknown                | 2        | 3.33%   |
| Shuttle XS35V4         | 1        | 1.67%   |
| Pegatron IPM31         | 1        | 1.67%   |
| MSI MS-7C91            | 1        | 1.67%   |
| MSI MS-7B89            | 1        | 1.67%   |
| MSI MS-7B85            | 1        | 1.67%   |
| MSI MS-7B84            | 1        | 1.67%   |
| MSI MS-7A34            | 1        | 1.67%   |
| MSI MS-7850            | 1        | 1.67%   |
| MSI MS-7640            | 1        | 1.67%   |
| MEGA G41T-M7           | 1        | 1.67%   |
| Lenovo ThinkCentre     | 1        | 1.67%   |
| Lenovo IdeaCentre      | 1        | 1.67%   |
| Lenovo C50-30          | 1        | 1.67%   |
| Intel X99              | 1        | 1.67%   |
| HP ProDesk             | 1        | 1.67%   |
| Gigabyte Z68AP-D3      | 1        | 1.67%   |
| Gigabyte X570          | 1        | 1.67%   |
| Gigabyte P31-ES3G      | 1        | 1.67%   |
| Gigabyte J4005ND2P-CF  | 1        | 1.67%   |
| Gigabyte H81M-S2V      | 1        | 1.67%   |
| Gigabyte H61M-HD2      | 1        | 1.67%   |
| Gigabyte H110M-DS2V    | 1        | 1.67%   |
| Gigabyte GA-MA770-UD3  | 1        | 1.67%   |
| Gigabyte GA-890XA-UD3  | 1        | 1.67%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.67%   |
| Gigabyte F2A68HM-H     | 1        | 1.67%   |
| Gigabyte B85M-D3H      | 1        | 1.67%   |
| Gigabyte B360M         | 1        | 1.67%   |
| Fujitsu CELSIUS        | 1        | 1.67%   |
| eMachines EL1852G      | 1        | 1.67%   |
| Dell Studio            | 1        | 1.67%   |
| Biostar H61MLV2        | 1        | 1.67%   |
| Biostar A320MH         | 1        | 1.67%   |
| ASUS STRIX             | 1        | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 13       | 21.67%  |
| 2019 | 7        | 11.67%  |
| 2014 | 6        | 10%     |
| 2013 | 5        | 8.33%   |
| 2011 | 5        | 8.33%   |
| 2021 | 3        | 5%      |
| 2020 | 3        | 5%      |
| 2017 | 3        | 5%      |
| 2015 | 3        | 5%      |
| 2008 | 3        | 5%      |
| 2016 | 2        | 3.33%   |
| 2012 | 2        | 3.33%   |
| 2010 | 2        | 3.33%   |
| 2006 | 2        | 3.33%   |
| 2009 | 1        | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 60       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 60       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 21       | 34.43%  |
| 32.01-64.0 | 11       | 18.03%  |
| 3.01-4.0   | 10       | 16.39%  |
| 8.01-16.0  | 10       | 16.39%  |
| 4.01-8.0   | 6        | 9.84%   |
| 24.01-32.0 | 2        | 3.28%   |
| 2.01-3.0   | 1        | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 23       | 34.85%  |
| 2.01-3.0  | 13       | 19.7%   |
| 3.01-4.0  | 11       | 16.67%  |
| 4.01-8.0  | 9        | 13.64%  |
| 8.01-16.0 | 7        | 10.61%  |
| 0.51-1.0  | 3        | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 33.33%  |
| 1      | 15       | 23.81%  |
| 4      | 11       | 17.46%  |
| 3      | 8        | 12.7%   |
| 5      | 5        | 7.94%   |
| 6      | 2        | 3.17%   |
| 7      | 1        | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 55.74%  |
| Yes       | 27       | 44.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 55%     |
| Yes       | 27       | 45%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 62.3%   |
| Yes       | 23       | 37.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 8        | 13.33%  |
| Germany      | 8        | 13.33%  |
| Russia       | 5        | 8.33%   |
| Canada       | 5        | 8.33%   |
| Brazil       | 5        | 8.33%   |
| Sweden       | 4        | 6.67%   |
| France       | 3        | 5%      |
| Spain        | 2        | 3.33%   |
| Netherlands  | 2        | 3.33%   |
| Australia    | 2        | 3.33%   |
| Venezuela    | 1        | 1.67%   |
| Thailand     | 1        | 1.67%   |
| Saudi Arabia | 1        | 1.67%   |
| Portugal     | 1        | 1.67%   |
| Poland       | 1        | 1.67%   |
| Philippines  | 1        | 1.67%   |
| Norway       | 1        | 1.67%   |
| Mexico       | 1        | 1.67%   |
| Kazakhstan   | 1        | 1.67%   |
| Ireland      | 1        | 1.67%   |
| Iran         | 1        | 1.67%   |
| India        | 1        | 1.67%   |
| Guyana       | 1        | 1.67%   |
| Greece       | 1        | 1.67%   |
| Denmark      | 1        | 1.67%   |
| Albania      | 1        | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Toronto         | 2        | 3.17%   |
| Stockholm       | 2        | 3.17%   |
| Mainz           | 2        | 3.17%   |
| Guelph          | 2        | 3.17%   |
| Yekaterinburg   | 1        | 1.59%   |
| Weil am Rhein   | 1        | 1.59%   |
| Viby J          | 1        | 1.59%   |
| Vancouver       | 1        | 1.59%   |
| Uppsala         | 1        | 1.59%   |
| Thessaloniki    | 1        | 1.59%   |
| SГЈo Pedro    | 1        | 1.59%   |
| St Petersburg   | 1        | 1.59%   |
| Songkhla        | 1        | 1.59%   |
| Seville         | 1        | 1.59%   |
| Severna Park    | 1        | 1.59%   |
| Santa Maria     | 1        | 1.59%   |
| Santa Cruz      | 1        | 1.59%   |
| Portsmouth      | 1        | 1.59%   |
| Phoenix         | 1        | 1.59%   |
| Oslo            | 1        | 1.59%   |
| Orenburg        | 1        | 1.59%   |
| Ochten          | 1        | 1.59%   |
| Novosibirsk     | 1        | 1.59%   |
| New York        | 1        | 1.59%   |
| Munich          | 1        | 1.59%   |
| Moita Bonita    | 1        | 1.59%   |
| Millstadt       | 1        | 1.59%   |
| Mexico City     | 1        | 1.59%   |
| Martos          | 1        | 1.59%   |
| Martigues       | 1        | 1.59%   |
| Mandurah        | 1        | 1.59%   |
| Malmo           | 1        | 1.59%   |
| Lipa City       | 1        | 1.59%   |
| Lexington       | 1        | 1.59%   |
| Krefeld         | 1        | 1.59%   |
| Kolkata         | 1        | 1.59%   |
| Khobar          | 1        | 1.59%   |
| Huntington Park | 1        | 1.59%   |
| Hamburg         | 1        | 1.59%   |
| Gray-la-Ville   | 1        | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 42     | 20.16%  |
| Samsung Electronics | 25       | 53     | 20.16%  |
| Seagate             | 21       | 40     | 16.94%  |
| Kingston            | 9        | 13     | 7.26%   |
| Toshiba             | 7        | 9      | 5.65%   |
| Crucial             | 6        | 6      | 4.84%   |
| SanDisk             | 5        | 6      | 4.03%   |
| Unknown             | 4        | 6      | 3.23%   |
| Intel               | 4        | 4      | 3.23%   |
| Hitachi             | 3        | 3      | 2.42%   |
| A-DATA Technology   | 3        | 3      | 2.42%   |
| PNY                 | 2        | 2      | 1.61%   |
| China               | 2        | 2      | 1.61%   |
| SPCC Sol            | 1        | 1      | 0.81%   |
| Phison              | 1        | 1      | 0.81%   |
| Patriot             | 1        | 1      | 0.81%   |
| Micron Technology   | 1        | 1      | 0.81%   |
| Intenso             | 1        | 2      | 0.81%   |
| HGST                | 1        | 1      | 0.81%   |
| HFS512GD            | 1        | 1      | 0.81%   |
| Corsair             | 1        | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 7        | 4.58%   |
| Samsung NVMe SSD Drive 500GB     | 7        | 4.58%   |
| Samsung SSD 850 EVO 500GB        | 4        | 2.61%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3        | 1.96%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.96%   |
| Seagate ST31000528AS 1TB         | 3        | 1.96%   |
| Seagate ST2000DX002-2DV164 2TB   | 3        | 1.96%   |
| Samsung SSD 860 EVO 500GB        | 3        | 1.96%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 1.96%   |
| WDC WD5000AAKS-00A7B0 500GB      | 2        | 1.31%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 2        | 1.31%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 1.31%   |
| WDC WD10EADS-00M2B0 1TB          | 2        | 1.31%   |
| Unknown TP02000GB 2TB            | 2        | 1.31%   |
| Toshiba DT01ACA050 500GB         | 2        | 1.31%   |
| Seagate ST31000524AS 1TB         | 2        | 1.31%   |
| Seagate ST2000DX001-1NS164 2TB   | 2        | 1.31%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 1.31%   |
| SanDisk SDSSDA240G 240GB         | 2        | 1.31%   |
| Samsung NVMe SSD Drive 1TB       | 2        | 1.31%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 1.31%   |
| Intel NVMe SSD Drive 1024GB      | 2        | 1.31%   |
| Hitachi HTS545032B9A300 320GB    | 2        | 1.31%   |
| Crucial CT1000P1SSD8 1TB         | 2        | 1.31%   |
| Crucial CT1000MX500SSD1 1TB      | 2        | 1.31%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD | 1        | 0.65%   |
| WDC WD6400AAKS-75A7B2 640GB      | 1        | 0.65%   |
| WDC WD6400AAKS-65A7B2 640GB      | 1        | 0.65%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.65%   |
| WDC WD5000AVCS-632DY1 500GB      | 1        | 0.65%   |
| WDC WD5000AAKX-003CA0 500GB      | 1        | 0.65%   |
| WDC WD5000AAKX-001CA0 500GB      | 1        | 0.65%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.65%   |
| WDC WD3200AAJS-00YZCA0 320GB     | 1        | 0.65%   |
| WDC WD32 00AAJS-00L7A0 320GB     | 1        | 0.65%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1        | 0.65%   |
| WDC WD2500HHTZ-04N21V1 250GB     | 1        | 0.65%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.65%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1        | 0.65%   |
| WDC WD2002FAEX-007BA0 2TB        | 1        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 40     | 40.68%  |
| Seagate             | 21       | 40     | 35.59%  |
| Toshiba             | 6        | 8      | 10.17%  |
| Samsung Electronics | 3        | 3      | 5.08%   |
| Hitachi             | 3        | 3      | 5.08%   |
| Intenso             | 1        | 2      | 1.69%   |
| HGST                | 1        | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 33     | 42%     |
| Kingston            | 6        | 9      | 12%     |
| SanDisk             | 4        | 5      | 8%      |
| Crucial             | 4        | 4      | 8%      |
| A-DATA Technology   | 3        | 3      | 6%      |
| Unknown             | 2        | 2      | 4%      |
| PNY                 | 2        | 2      | 4%      |
| China               | 2        | 2      | 4%      |
| WDC                 | 1        | 1      | 2%      |
| SPCC Sol            | 1        | 1      | 2%      |
| Patriot             | 1        | 1      | 2%      |
| Micron Technology   | 1        | 1      | 2%      |
| Intel               | 1        | 1      | 2%      |
| Corsair             | 1        | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 47       | 97     | 42.34%  |
| SSD     | 41       | 66     | 36.94%  |
| NVMe    | 19       | 29     | 17.12%  |
| Unknown | 4        | 6      | 3.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 158    | 68.75%  |
| NVMe | 19       | 29     | 23.75%  |
| SAS  | 6        | 11     | 7.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 92     | 52.75%  |
| 0.51-1.0   | 22       | 31     | 24.18%  |
| 1.01-2.0   | 17       | 34     | 18.68%  |
| 3.01-4.0   | 3        | 5      | 3.3%    |
| 4.01-10.0  | 1        | 1      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 14       | 22.58%  |
| 501-1000       | 14       | 22.58%  |
| 101-250        | 13       | 20.97%  |
| More than 3000 | 7        | 11.29%  |
| 1001-2000      | 5        | 8.06%   |
| 2001-3000      | 4        | 6.45%   |
| 51-100         | 3        | 4.84%   |
| 21-50          | 2        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 15       | 23.81%  |
| 21-50          | 11       | 17.46%  |
| 101-250        | 10       | 15.87%  |
| 501-1000       | 8        | 12.7%   |
| 251-500        | 6        | 9.52%   |
| 1001-2000      | 5        | 7.94%   |
| 2001-3000      | 3        | 4.76%   |
| 51-100         | 3        | 4.76%   |
| More than 3000 | 2        | 3.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 16.67%  |
| WDC WD1002FAEX-00Y9A0 1TB             | 1        | 1      | 16.67%  |
| WDC WD1001FALS-75J7B0 1TB             | 1        | 1      | 16.67%  |
| Seagate ST2000DM001-9YN164 2TB        | 1        | 1      | 16.67%  |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 16.67%  |
| Crucial CT1000P1SSD8 1TB              | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 50%     |
| Seagate             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| Crucial             | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 4      | 60%     |
| NVMe | 2        | 2      | 40%     |

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
| Detected | 51       | 163    | 73.91%  |
| Works    | 13       | 29     | 18.84%  |
| Malfunc  | 5        | 6      | 7.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 36       | 42.35%  |
| AMD                          | 26       | 30.59%  |
| Samsung Electronics          | 10       | 11.76%  |
| Kingston Technology Company  | 3        | 3.53%   |
| Micron/Crucial Technology    | 2        | 2.35%   |
| Marvell Technology Group     | 2        | 2.35%   |
| JMicron Technology           | 2        | 2.35%   |
| Toshiba America Info Systems | 1        | 1.18%   |
| SanDisk                      | 1        | 1.18%   |
| Phison Electronics           | 1        | 1.18%   |
| ASMedia Technology           | 1        | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 16.51%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 7.34%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 7.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 6.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 5.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 4.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.75%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 1.83%   |
| Kingston Company KC2000 NVMe SSD                                                        | 2        | 1.83%   |
| Intel SSD 660P Series                                                                   | 2        | 1.83%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.83%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.92%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.92%   |
| Marvell Group 88SE9182 PCIe 2.0 x2 2-port SATA 6 Gb/s Controller                        | 1        | 0.92%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.92%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.92%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.92%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.92%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 1        | 0.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.92%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 0.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 0.92%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 58.33%  |
| NVMe | 20       | 23.81%  |
| IDE  | 13       | 15.48%  |
| RAID | 2        | 2.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 34       | 56.67%  |
| AMD    | 26       | 43.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 6.67%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 3.33%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 3.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 3.33%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.33%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 3.33%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 1.67%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz         | 1        | 1.67%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 1.67%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 1.67%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 1.67%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.67%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 1.67%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.67%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.67%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.67%   |
| Intel Core i7-3960X CPU @ 3.30GHz           | 1        | 1.67%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.67%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.67%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.67%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1        | 1.67%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.67%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.67%   |
| Intel Core i3-3210 CPU @ 3.20GHz            | 1        | 1.67%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.67%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 1.67%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.67%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.67%   |
| Intel Celeron J4005 CPU @ 2.00GHz           | 1        | 1.67%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1.67%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1        | 1.67%   |
| Intel Celeron CPU E3400 @ 2.60GHz           | 1        | 1.67%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 1        | 1.67%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1        | 1.67%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 1.67%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 7             | 9        | 15%     |
| AMD Ryzen 5             | 8        | 13.33%  |
| Intel Core i7           | 7        | 11.67%  |
| Intel Core i3           | 7        | 11.67%  |
| Intel Core i5           | 6        | 10%     |
| Intel Celeron           | 4        | 6.67%   |
| Intel Xeon              | 3        | 5%      |
| AMD Ryzen 9             | 3        | 5%      |
| Intel Pentium Dual-Core | 2        | 3.33%   |
| Intel Pentium D         | 2        | 3.33%   |
| Intel Core 2 Quad       | 2        | 3.33%   |
| AMD Phenom II X4        | 2        | 3.33%   |
| AMD FX                  | 2        | 3.33%   |
| AMD A10                 | 2        | 3.33%   |
| Intel Core i9           | 1        | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 18       | 30%     |
| 2      | 16       | 26.67%  |
| 8      | 12       | 20%     |
| 6      | 11       | 18.33%  |
| 16     | 1        | 1.67%   |
| 12     | 1        | 1.67%   |
| 3      | 1        | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 68.33%  |
| 1      | 19       | 31.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 59       | 98.33%  |
| Unknown        | 1        | 1.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 7        | 11.48%  |
| 0x08701021 | 5        | 8.2%    |
| 0x1067a    | 4        | 6.56%   |
| 0x0800820d | 4        | 6.56%   |
| Unknown    | 4        | 6.56%   |
| 0x206a7    | 3        | 4.92%   |
| 0x08701013 | 3        | 4.92%   |
| 0x906ec    | 2        | 3.28%   |
| 0x906e9    | 2        | 3.28%   |
| 0x306a9    | 2        | 3.28%   |
| 0x06003106 | 2        | 3.28%   |
| 0x06000852 | 2        | 3.28%   |
| 0xf64      | 1        | 1.64%   |
| 0xf62      | 1        | 1.64%   |
| 0x906ed    | 1        | 1.64%   |
| 0x906eb    | 1        | 1.64%   |
| 0x906ea    | 1        | 1.64%   |
| 0x706a1    | 1        | 1.64%   |
| 0x506e3    | 1        | 1.64%   |
| 0x40651    | 1        | 1.64%   |
| 0x30678    | 1        | 1.64%   |
| 0x206d7    | 1        | 1.64%   |
| 0x20655    | 1        | 1.64%   |
| 0x10677    | 1        | 1.64%   |
| 0x0a50000c | 1        | 1.64%   |
| 0x0a201204 | 1        | 1.64%   |
| 0x0a201009 | 1        | 1.64%   |
| 0x08600106 | 1        | 1.64%   |
| 0x08108109 | 1        | 1.64%   |
| 0x08101016 | 1        | 1.64%   |
| 0x0800820b | 1        | 1.64%   |
| 0x010000db | 1        | 1.64%   |
| 0x010000c8 | 1        | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 10       | 16.67%  |
| Haswell       | 9        | 15%     |
| KabyLake      | 8        | 13.33%  |
| Zen+          | 6        | 10%     |
| Penryn        | 5        | 8.33%   |
| SandyBridge   | 4        | 6.67%   |
| Zen 3         | 3        | 5%      |
| Steamroller   | 2        | 3.33%   |
| Piledriver    | 2        | 3.33%   |
| NetBurst      | 2        | 3.33%   |
| K10           | 2        | 3.33%   |
| IvyBridge     | 2        | 3.33%   |
| Zen           | 1        | 1.67%   |
| Westmere      | 1        | 1.67%   |
| Skylake       | 1        | 1.67%   |
| Silvermont    | 1        | 1.67%   |
| Goldmont plus | 1        | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 28       | 41.18%  |
| AMD    | 24       | 35.29%  |
| Intel  | 16       | 23.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 7.25%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 5.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 4.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 4.35%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.9%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.9%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.45%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.45%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.45%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.45%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.45%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.45%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1        | 1.45%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.45%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.45%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 1.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1        | 1.45%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.45%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.45%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.45%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.45%   |
| Intel HD Graphics 530                                                       | 1        | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.45%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.45%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.45%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 1.45%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.45%   |
| AMD Renoir                                                                  | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 26       | 41.94%  |
| 1 x AMD        | 22       | 35.48%  |
| 1 x Intel      | 9        | 14.52%  |
| Intel + Nvidia | 2        | 3.23%   |
| Intel + AMD    | 2        | 3.23%   |
| AMD + Nvidia   | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 65%     |
| Proprietary | 21       | 35%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 11       | 18.33%  |
| 0.51-1.0   | 10       | 16.67%  |
| 7.01-8.0   | 9        | 15%     |
| Unknown    | 9        | 15%     |
| 5.01-6.0   | 8        | 13.33%  |
| 3.01-4.0   | 4        | 6.67%   |
| 8.01-16.0  | 4        | 6.67%   |
| 2.01-3.0   | 3        | 5%      |
| 0.01-0.5   | 2        | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 14.29%  |
| Goldstar             | 10       | 14.29%  |
| AOC                  | 9        | 12.86%  |
| Dell                 | 8        | 11.43%  |
| Ancor Communications | 6        | 8.57%   |
| LG Electronics       | 4        | 5.71%   |
| BenQ                 | 4        | 5.71%   |
| Hewlett-Packard      | 3        | 4.29%   |
| Acer                 | 3        | 4.29%   |
| NEC Computers        | 2        | 2.86%   |
| ViewSonic            | 1        | 1.43%   |
| Unknown              | 1        | 1.43%   |
| Sharp                | 1        | 1.43%   |
| Philips              | 1        | 1.43%   |
| MSI                  | 1        | 1.43%   |
| Microstep            | 1        | 1.43%   |
| Lenovo               | 1        | 1.43%   |
| JRY                  | 1        | 1.43%   |
| Iiyama               | 1        | 1.43%   |
| ASUSTek Computer     | 1        | 1.43%   |
| Unknown              | 1        | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 24G1WG3 AOC2401 1920x1080 521x293mm 23.5-inch                    | 3        | 4%      |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2        | 2.67%   |
| Ancor Communications LCD Monitor MG248 1920x1080                     | 2        | 2.67%   |
| ViewSonic VP191b VSC0E11 1280x1024 376x301mm 19.0-inch               | 1        | 1.33%   |
| Unknown LCD Monitor HIC 3200x1080                                    | 1        | 1.33%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1        | 1.33%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 1.33%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 1.33%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1        | 1.33%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch   | 1        | 1.33%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch    | 1        | 1.33%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 1.33%   |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch     | 1        | 1.33%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1        | 1.33%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 1.33%   |
| Philips PHL 276E6 PHLC0FA 1920x1080 598x336mm 27.0-inch              | 1        | 1.33%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1        | 1.33%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1        | 1.33%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                      | 1        | 1.33%   |
| Microstep LCD Monitor MSI G241                                       | 1        | 1.33%   |
| LG Electronics LCD Monitor W1952 1440x900                            | 1        | 1.33%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3440x1440                    | 1        | 1.33%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                     | 1        | 1.33%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.33%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 1        | 1.33%   |
| JRY LCD Monitor JRY1950 1600x900 368x207mm 16.6-inch                 | 1        | 1.33%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                | 1        | 1.33%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 518x324mm 24.1-inch          | 1        | 1.33%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch           | 1        | 1.33%   |
| Hewlett-Packard 24y HPN3504 1920x1080 530x300mm 24.0-inch            | 1        | 1.33%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1        | 1.33%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1        | 1.33%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch             | 1        | 1.33%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 1.33%   |
| Goldstar T730SH GSM43CB 1280x960 310x230mm 15.2-inch                 | 1        | 1.33%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1        | 1.33%   |
| Goldstar E2241 GSM5819 1920x1080 477x268mm 21.5-inch                 | 1        | 1.33%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1        | 1.33%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch               | 1        | 1.33%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 40.58%  |
| 2560x1440 (QHD)    | 7        | 10.14%  |
| 1280x1024 (SXGA)   | 5        | 7.25%   |
| Unknown            | 5        | 7.25%   |
| 1600x900 (HD+)     | 4        | 5.8%    |
| 1366x768 (WXGA)    | 4        | 5.8%    |
| 1440x900 (WXGA+)   | 3        | 4.35%   |
| 2560x1080          | 2        | 2.9%    |
| 5760x1080          | 1        | 1.45%   |
| 4480x1440          | 1        | 1.45%   |
| 3840x2160 (4K)     | 1        | 1.45%   |
| 3840x1080          | 1        | 1.45%   |
| 3440x1440          | 1        | 1.45%   |
| 3200x1080          | 1        | 1.45%   |
| 1920x1200 (WUXGA)  | 1        | 1.45%   |
| 1680x1050 (WSXGA+) | 1        | 1.45%   |
| 1360x768           | 1        | 1.45%   |
| 1152x864           | 1        | 1.45%   |
| 1024x768 (XGA)     | 1        | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 29.69%  |
| 24      | 10       | 15.63%  |
| 27      | 6        | 9.38%   |
| 23      | 5        | 7.81%   |
| 21      | 5        | 7.81%   |
| 18      | 5        | 7.81%   |
| 20      | 3        | 4.69%   |
| 19      | 3        | 4.69%   |
| 15      | 2        | 3.13%   |
| 34      | 1        | 1.56%   |
| 31      | 1        | 1.56%   |
| 29      | 1        | 1.56%   |
| 25      | 1        | 1.56%   |
| 22      | 1        | 1.56%   |
| 17      | 1        | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 31.75%  |
| Unknown     | 19       | 30.16%  |
| 401-500     | 15       | 23.81%  |
| 601-700     | 3        | 4.76%   |
| 301-350     | 3        | 4.76%   |
| 351-400     | 2        | 3.17%   |
| 701-800     | 1        | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 31       | 47.69%  |
| Unknown | 19       | 29.23%  |
| 16/10   | 8        | 12.31%  |
| 5/4     | 2        | 3.08%   |
| 4/3     | 2        | 3.08%   |
| 21/9    | 2        | 3.08%   |
| 6/5     | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 19       | 29.23%  |
| 201-250        | 18       | 27.69%  |
| 151-200        | 8        | 12.31%  |
| 301-350        | 7        | 10.77%  |
| 251-300        | 5        | 7.69%   |
| 141-150        | 4        | 6.15%   |
| 351-500        | 2        | 3.08%   |
| 111-120        | 1        | 1.54%   |
| 101-110        | 1        | 1.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 34       | 53.97%  |
| Unknown | 19       | 30.16%  |
| 101-120 | 9        | 14.29%  |
| 161-240 | 1        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 72.13%  |
| 2     | 16       | 26.23%  |
| 3     | 1        | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 43       | 47.25%  |
| Intel                 | 24       | 26.37%  |
| Qualcomm Atheros      | 6        | 6.59%   |
| Xiaomi                | 2        | 2.2%    |
| TP-Link               | 2        | 2.2%    |
| Ralink Technology     | 2        | 2.2%    |
| MediaTek              | 2        | 2.2%    |
| Broadcom              | 2        | 2.2%    |
| NetGear               | 1        | 1.1%    |
| Microchip Technology  | 1        | 1.1%    |
| Linksys               | 1        | 1.1%    |
| Huawei Technologies   | 1        | 1.1%    |
| D-Link System         | 1        | 1.1%    |
| Broadcom Limited      | 1        | 1.1%    |
| Belkin Components     | 1        | 1.1%    |
| Aquantia              | 1        | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 36.54%  |
| Intel I211 Gigabit Network Connection                             | 9        | 8.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.88%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 2.88%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 1.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.92%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                  | 2        | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.96%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.96%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.96%   |
| Realtek 802.11ac NIC                                              | 1        | 0.96%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.96%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.96%   |
| NetGear A6150                                                     | 1        | 0.96%   |
| Microchip MCP2200 USB Serial Port Emulator                        | 1        | 0.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 0.96%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 1        | 0.96%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.96%   |
| Intel Wireless-AC 9260                                            | 1        | 0.96%   |
| Intel Wireless 7265                                               | 1        | 0.96%   |
| Intel Wireless 3165                                               | 1        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 0.96%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.96%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.96%   |
| Huawei LYA-L09                                                    | 1        | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 26.47%  |
| Realtek Semiconductor | 8        | 23.53%  |
| Qualcomm Atheros      | 5        | 14.71%  |
| TP-Link               | 2        | 5.88%   |
| Ralink Technology     | 2        | 5.88%   |
| MediaTek              | 2        | 5.88%   |
| NetGear               | 1        | 2.94%   |
| Linksys               | 1        | 2.94%   |
| D-Link System         | 1        | 2.94%   |
| Broadcom Limited      | 1        | 2.94%   |
| Broadcom              | 1        | 2.94%   |
| Belkin Components     | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 3        | 8.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                             | 2        | 5.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 5.88%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                        | 2        | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 2        | 5.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 2.94%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 1        | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1        | 2.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                              | 1        | 2.94%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 2.94%   |
| Realtek 802.11ac NIC                                                                    | 1        | 2.94%   |
| Ralink RT5372 Wireless Adapter                                                          | 1        | 2.94%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 1        | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1        | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1        | 2.94%   |
| NetGear A6150                                                                           | 1        | 2.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 1        | 2.94%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 2.94%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 2.94%   |
| Intel Wireless-AC 9260                                                                  | 1        | 2.94%   |
| Intel Wireless 7265                                                                     | 1        | 2.94%   |
| Intel Wireless 3165                                                                     | 1        | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 1        | 2.94%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 2.94%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                                  | 1        | 2.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 2.94%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 40       | 60.61%  |
| Intel                 | 20       | 30.3%   |
| Xiaomi                | 2        | 3.03%   |
| Qualcomm Atheros      | 1        | 1.52%   |
| Huawei Technologies   | 1        | 1.52%   |
| Broadcom              | 1        | 1.52%   |
| Aquantia              | 1        | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 55.07%  |
| Intel I211 Gigabit Network Connection                             | 9        | 13.04%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 4.35%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 4.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.9%    |
| Intel Ethernet Controller I225-V                                  | 2        | 2.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.45%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.45%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.45%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.45%   |
| Huawei LYA-L09                                                    | 1        | 1.45%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 68.18%  |
| WiFi     | 27       | 30.68%  |
| Modem    | 1        | 1.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 71.21%  |
| WiFi     | 19       | 28.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 67.21%  |
| 2     | 18       | 29.51%  |
| 3     | 2        | 3.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 52       | 82.54%  |
| Yes  | 11       | 17.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 34.62%  |
| Cambridge Silicon Radio         | 7        | 26.92%  |
| Broadcom                        | 3        | 11.54%  |
| Realtek Semiconductor           | 2        | 7.69%   |
| ASUSTek Computer                | 2        | 7.69%   |
| Qualcomm Atheros Communications | 1        | 3.85%   |
| MediaTek                        | 1        | 3.85%   |
| Apple                           | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 26.92%  |
| Intel AX200 Bluetooth                               | 3        | 11.54%  |
| Realtek Bluetooth Radio                             | 2        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 7.69%   |
| Intel Bluetooth wireless interface                  | 2        | 7.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 3.85%   |
| MediaTek Wireless_Device                            | 1        | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.85%   |
| Broadcom BCM92045B3 ROM                             | 1        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.85%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 3.85%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 3.85%   |
| Apple Bluetooth USB Host Controller                 | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 32       | 28.83%  |
| AMD                     | 32       | 28.83%  |
| Nvidia                  | 27       | 24.32%  |
| Blue Microphones        | 4        | 3.6%    |
| C-Media Electronics     | 3        | 2.7%    |
| Logitech                | 2        | 1.8%    |
| Yamaha                  | 1        | 0.9%    |
| Texas Instruments       | 1        | 0.9%    |
| Tenx Technology         | 1        | 0.9%    |
| SteelSeries ApS         | 1        | 0.9%    |
| SAVITECH                | 1        | 0.9%    |
| RME                     | 1        | 0.9%    |
| JMTek                   | 1        | 0.9%    |
| Creative Technology     | 1        | 0.9%    |
| Creative Labs           | 1        | 0.9%    |
| Cooler Master           | 1        | 0.9%    |
| BEHRINGER International | 1        | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 8.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 5.22%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 4.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 3.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.73%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 3.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 2.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 2.99%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 2.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 2.24%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3        | 2.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.49%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.49%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.49%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.49%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.49%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.49%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.49%   |
| Yamaha Steinberg UR44                                                      | 1        | 0.75%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1        | 0.75%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.75%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1        | 0.75%   |
| SAVITECH ODAC-revB                                                         | 1        | 0.75%   |
| RME Babyface Pro (71964113)                                                | 1        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.75%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Corsair           | 7        | 46.67%  |
| Unknown           | 2        | 13.33%  |
| Crucial           | 2        | 13.33%  |
| Transcend         | 1        | 6.67%   |
| Patriot           | 1        | 6.67%   |
| G.Skill           | 1        | 6.67%   |
| A-DATA Technology | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 2        | 10.53%  |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 5.26%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s              | 1        | 5.26%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s              | 1        | 5.26%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s         | 1        | 5.26%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s       | 1        | 5.26%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 1        | 5.26%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1        | 5.26%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 5.26%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8192MB DIMM DDR4 3200MT/s | 1        | 5.26%   |
| Corsair RAM CMY8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s       | 1        | 5.26%   |
| Corsair RAM CMX8GX3M2B1600C9 4096MB DIMM DDR3 1600MT/s    | 1        | 5.26%   |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s       | 1        | 5.26%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s     | 1        | 5.26%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s    | 1        | 5.26%   |
| Corsair RAM CMK16GX4M2Z3200C16 8192MB DIMM DDR4 3200MT/s  | 1        | 5.26%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s  | 1        | 5.26%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s               | 1        | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 8        | 57.14%  |
| DDR3 | 6        | 42.86%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 14       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 47.06%  |
| 4096  | 6        | 35.29%  |
| 16384 | 2        | 11.76%  |
| 2048  | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 27.78%  |
| 3200  | 3        | 16.67%  |
| 3466  | 2        | 11.11%  |
| 2400  | 2        | 11.11%  |
| 3866  | 1        | 5.56%   |
| 3600  | 1        | 5.56%   |
| 3266  | 1        | 5.56%   |
| 3000  | 1        | 5.56%   |
| 1800  | 1        | 5.56%   |
| 1066  | 1        | 5.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP DeskJet 3630 series | 1        | 33.33%  |
| Canon LBP7010C/7018C   | 1        | 33.33%  |
| Canon G3000 series     | 1        | 33.33%  |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 8        | 42.11%  |
| Microsoft           | 2        | 10.53%  |
| Microdia            | 2        | 10.53%  |
| Samsung Electronics | 1        | 5.26%   |
| MacroSilicon        | 1        | 5.26%   |
| LG Electronics      | 1        | 5.26%   |
| Hewlett-Packard     | 1        | 5.26%   |
| Apple               | 1        | 5.26%   |
| Acer                | 1        | 5.26%   |
| A4Tech              | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Microdia Camera                         | 2        | 10.53%  |
| Logitech Logitech Webcam C160           | 2        | 10.53%  |
| Logitech HD Pro Webcam C920             | 2        | 10.53%  |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 5.26%   |
| Microsoft Xbox NUI Camera               | 1        | 5.26%   |
| Microsoft LifeCam HD-3000               | 1        | 5.26%   |
| MacroSilicon ShadowCast                 | 1        | 5.26%   |
| Logitech Webcam C270                    | 1        | 5.26%   |
| Logitech StreamCam                      | 1        | 5.26%   |
| Logitech C922 Pro Stream Webcam         | 1        | 5.26%   |
| Logitech C920 PRO HD Webcam             | 1        | 5.26%   |
| LG Optimus (Various Models) MTP Mode    | 1        | 5.26%   |
| HP Webcam HD 2300                       | 1        | 5.26%   |
| Apple iPhone 5/5C/5S/6/SE               | 1        | 5.26%   |
| Acer LENOVO LBG 720P CAM                | 1        | 5.26%   |
| A4Tech FHD 1080P PC Camera              | 1        | 5.26%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| BIT4ID | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| BIT4ID miniLector EVO | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 51       | 82.26%  |
| 1     | 7        | 11.29%  |
| 2     | 3        | 4.84%   |
| 3     | 1        | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 7        | 43.75%  |
| Multimedia controller | 2        | 12.5%   |
| Graphics card         | 2        | 12.5%   |
| Unassigned class      | 1        | 6.25%   |
| Tv card               | 1        | 6.25%   |
| Network               | 1        | 6.25%   |
| Chipcard              | 1        | 6.25%   |
| Camera                | 1        | 6.25%   |


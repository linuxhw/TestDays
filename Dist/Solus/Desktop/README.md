Solus - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Solus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 95

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | F2A68HM-H                   | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu    | D3227-A1 S26361-D3227-A1    | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| ASRock     | H81 Pro BTC R2.0            | [9f5778e082](https://linux-hardware.org/?probe=9f5778e082) | Apr 11, 2022 |
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
| Lenovo     | Board                       | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
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
| MSI        | 990FXA-GD65                 | [0083f37f14](https://linux-hardware.org/?probe=0083f37f14) | Jan 05, 2021 |
| MSI        | 990FXA-GD65                 | [4db9c4da66](https://linux-hardware.org/?probe=4db9c4da66) | Jan 03, 2021 |
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
| Lenovo     | Board                       | [ef01565711](https://linux-hardware.org/?probe=ef01565711) | Apr 01, 2020 |
| Lenovo     | Board                       | [7c54db2820](https://linux-hardware.org/?probe=7c54db2820) | Apr 01, 2020 |
| ASUSTek    | P5PL2                       | [19fbc6cfd3](https://linux-hardware.org/?probe=19fbc6cfd3) | Mar 25, 2020 |
| MSI        | 990FXA-GD65                 | [868fa5cf23](https://linux-hardware.org/?probe=868fa5cf23) | Mar 15, 2020 |
| Gigabyte   | GA-890XA-UD3                | [e2cafdec0d](https://linux-hardware.org/?probe=e2cafdec0d) | Mar 09, 2020 |
| MSI        | 990FXA-GD65                 | [fdc69c0b70](https://linux-hardware.org/?probe=fdc69c0b70) | Feb 08, 2020 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [771600b1ae](https://linux-hardware.org/?probe=771600b1ae) | Feb 07, 2020 |
| MSI        | 990FXA-GD65                 | [4060a4338e](https://linux-hardware.org/?probe=4060a4338e) | Feb 05, 2020 |
| Gigabyte   | X570 AORUS MASTER           | [ad271d2feb](https://linux-hardware.org/?probe=ad271d2feb) | Dec 28, 2019 |
| Gigabyte   | X570 AORUS MASTER           | [b51c7d1ee8](https://linux-hardware.org/?probe=b51c7d1ee8) | Dec 20, 2019 |
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
| Solus 4.3 | 22       | 38.6%   |
| Solus 4.1 | 19       | 33.33%  |
| Solus 4.2 | 11       | 19.3%   |
| Solus 4.0 | 5        | 8.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Solus | 53       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.6.19-158.current  | 6        | 9.38%   |
| 5.14.21-210.current | 4        | 6.25%   |
| 5.14.16-205.current | 4        | 6.25%   |
| 5.6.19-159.current  | 3        | 4.69%   |
| 5.5.7-150.current   | 3        | 4.69%   |
| 5.4.12-144.current  | 3        | 4.69%   |
| 5.15.30-212.current | 3        | 4.69%   |
| 5.13.12-193.current | 3        | 4.69%   |
| 5.11.12-177.current | 3        | 4.69%   |
| 5.6.13-153.current  | 2        | 3.13%   |
| 5.14.14-202.current | 2        | 3.13%   |
| 5.13.6-190.current  | 2        | 3.13%   |
| 5.13.1-187.current  | 2        | 3.13%   |
| 5.11.16-178.current | 2        | 3.13%   |
| 5.10.5-167.current  | 2        | 3.13%   |
| 5.10.15-172.current | 2        | 3.13%   |
| 5.6.4-152.current   | 1        | 1.56%   |
| 5.6.18-156.current  | 1        | 1.56%   |
| 5.5.11-151.current  | 1        | 1.56%   |
| 5.4.1-137.current   | 1        | 1.56%   |
| 5.3.8-133.current   | 1        | 1.56%   |
| 5.15.32-213.current | 1        | 1.56%   |
| 5.15.26-211.current | 1        | 1.56%   |
| 5.13.8-191.current  | 1        | 1.56%   |
| 5.12.13-185.current | 1        | 1.56%   |
| 5.11.22-180.current | 1        | 1.56%   |
| 5.11.21-179.current | 1        | 1.56%   |
| 5.10.9-169.current  | 1        | 1.56%   |
| 5.10.7-168.current  | 1        | 1.56%   |
| 5.10.4-165.current  | 1        | 1.56%   |
| 5.0.5-113.current   | 1        | 1.56%   |
| 4.9.168-129.lts     | 1        | 1.56%   |
| 4.20.16-112.current | 1        | 1.56%   |
| 4.14.189-161.lts    | 1        | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.6.19   | 9        | 14.06%  |
| 5.14.21  | 4        | 6.25%   |
| 5.14.16  | 4        | 6.25%   |
| 5.5.7    | 3        | 4.69%   |
| 5.4.12   | 3        | 4.69%   |
| 5.15.30  | 3        | 4.69%   |
| 5.13.12  | 3        | 4.69%   |
| 5.11.12  | 3        | 4.69%   |
| 5.6.13   | 2        | 3.13%   |
| 5.14.14  | 2        | 3.13%   |
| 5.13.6   | 2        | 3.13%   |
| 5.13.1   | 2        | 3.13%   |
| 5.11.16  | 2        | 3.13%   |
| 5.10.5   | 2        | 3.13%   |
| 5.10.15  | 2        | 3.13%   |
| 5.6.4    | 1        | 1.56%   |
| 5.6.18   | 1        | 1.56%   |
| 5.5.11   | 1        | 1.56%   |
| 5.4.1    | 1        | 1.56%   |
| 5.3.8    | 1        | 1.56%   |
| 5.15.32  | 1        | 1.56%   |
| 5.15.26  | 1        | 1.56%   |
| 5.13.8   | 1        | 1.56%   |
| 5.12.13  | 1        | 1.56%   |
| 5.11.22  | 1        | 1.56%   |
| 5.11.21  | 1        | 1.56%   |
| 5.10.9   | 1        | 1.56%   |
| 5.10.7   | 1        | 1.56%   |
| 5.10.4   | 1        | 1.56%   |
| 5.0.5    | 1        | 1.56%   |
| 4.9.168  | 1        | 1.56%   |
| 4.20.16  | 1        | 1.56%   |
| 4.14.189 | 1        | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.6     | 12       | 19.05%  |
| 5.14    | 10       | 15.87%  |
| 5.13    | 8        | 12.7%   |
| 5.11    | 7        | 11.11%  |
| 5.10    | 7        | 11.11%  |
| 5.15    | 5        | 7.94%   |
| 5.5     | 4        | 6.35%   |
| 5.4     | 4        | 6.35%   |
| 5.3     | 1        | 1.59%   |
| 5.12    | 1        | 1.59%   |
| 5.0     | 1        | 1.59%   |
| 4.9     | 1        | 1.59%   |
| 4.20    | 1        | 1.59%   |
| 4.14    | 1        | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 53       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Budgie  | 37       | 67.27%  |
| KDE     | 6        | 10.91%  |
| Unknown | 5        | 9.09%   |
| GNOME   | 4        | 7.27%   |
| KDE5    | 2        | 3.64%   |
| MATE    | 1        | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 52       | 98.11%  |
| Wayland | 1        | 1.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 83.33%  |
| LightDM | 4        | 7.41%   |
| TDM     | 3        | 5.56%   |
| SDDM    | 2        | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 22       | 40.74%  |
| ru_RU   | 6        | 11.11%  |
| pt_BR   | 5        | 9.26%   |
| de_DE   | 5        | 9.26%   |
| fr_FR   | 3        | 5.56%   |
| es_ES   | 3        | 5.56%   |
| Unknown | 2        | 3.7%    |
| pt_PT   | 1        | 1.85%   |
| pl_PL   | 1        | 1.85%   |
| es_VE   | 1        | 1.85%   |
| en_IE   | 1        | 1.85%   |
| en_GB   | 1        | 1.85%   |
| en_AU   | 1        | 1.85%   |
| ar_SA   | 1        | 1.85%   |
| ar_EG   | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 27       | 50.94%  |
| BIOS | 26       | 49.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 50       | 92.59%  |
| Unknown | 2        | 3.7%    |
| Xfs     | 1        | 1.85%   |
| Btrfs   | 1        | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 46       | 82.14%  |
| GPT     | 6        | 10.71%  |
| MBR     | 4        | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 88.89%  |
| Yes       | 6        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 78.95%  |
| Yes       | 12       | 21.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 16       | 30.19%  |
| ASUSTek Computer    | 11       | 20.75%  |
| MSI                 | 6        | 11.32%  |
| ASRock              | 5        | 9.43%   |
| Dell                | 3        | 5.66%   |
| Lenovo              | 2        | 3.77%   |
| Biostar             | 2        | 3.77%   |
| Shuttle             | 1        | 1.89%   |
| Pegatron            | 1        | 1.89%   |
| MEGA                | 1        | 1.89%   |
| Intel               | 1        | 1.89%   |
| Hewlett-Packard     | 1        | 1.89%   |
| Fujitsu             | 1        | 1.89%   |
| eMachines           | 1        | 1.89%   |
| Unknown             | 1        | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Shuttle XS35V4                   | 1        | 1.89%   |
| Pegatron IPM31                   | 1        | 1.89%   |
| MSI MS-7C91                      | 1        | 1.89%   |
| MSI MS-7B85                      | 1        | 1.89%   |
| MSI MS-7B84                      | 1        | 1.89%   |
| MSI MS-7A34                      | 1        | 1.89%   |
| MSI MS-7850                      | 1        | 1.89%   |
| MSI MS-7640                      | 1        | 1.89%   |
| MEGA G41T-M7 LGT                 | 1        | 1.89%   |
| Lenovo ThinkCentre M71e 3157G6S  | 1        | 1.89%   |
| Lenovo IdeaCentre K320 10031     | 1        | 1.89%   |
| Intel X99 V102                   | 1        | 1.89%   |
| HP ProDesk 490 G3 MT Business PC | 1        | 1.89%   |
| Gigabyte Z390 DESIGNARE          | 1        | 1.89%   |
| Gigabyte Z390 D                  | 1        | 1.89%   |
| Gigabyte Z390 AORUS PRO WIFI     | 1        | 1.89%   |
| Gigabyte Z390 AORUS ELITE        | 1        | 1.89%   |
| Gigabyte X570 AORUS MASTER       | 1        | 1.89%   |
| Gigabyte P31-ES3G                | 1        | 1.89%   |
| Gigabyte J4005ND2P-CF            | 1        | 1.89%   |
| Gigabyte H81M-S2V                | 1        | 1.89%   |
| Gigabyte H61M-HD2                | 1        | 1.89%   |
| Gigabyte H110M-DS2V              | 1        | 1.89%   |
| Gigabyte GA-MA770-UD3            | 1        | 1.89%   |
| Gigabyte GA-890XA-UD3            | 1        | 1.89%   |
| Gigabyte GA-78LMT-USB3 6.0       | 1        | 1.89%   |
| Gigabyte F2A68HM-H               | 1        | 1.89%   |
| Gigabyte B85M-D3H                | 1        | 1.89%   |
| Gigabyte B360M AORUS Gaming 3    | 1        | 1.89%   |
| Fujitsu CELSIUS W530             | 1        | 1.89%   |
| eMachines EL1852G                | 1        | 1.89%   |
| Dell Studio 540                  | 1        | 1.89%   |
| Dell OptiPlex GX620              | 1        | 1.89%   |
| Dell OptiPlex 9020               | 1        | 1.89%   |
| Biostar H61MLV2                  | 1        | 1.89%   |
| Biostar A320MH                   | 1        | 1.89%   |
| ASUS TUF B450-PRO GAMING         | 1        | 1.89%   |
| ASUS STRIX Z270I GAMING          | 1        | 1.89%   |
| ASUS ROG STRIX B450-F GAMING     | 1        | 1.89%   |
| ASUS ROG CROSSHAIR VIII HERO     | 1        | 1.89%   |
| ASUS PRIME Z390-P                | 1        | 1.89%   |
| ASUS PRIME X470-PRO              | 1        | 1.89%   |
| ASUS PRIME X370-A                | 1        | 1.89%   |
| ASUS P9X79 DELUXE                | 1        | 1.89%   |
| ASUS P5PL2                       | 1        | 1.89%   |
| ASUS Maximus IV Extreme          | 1        | 1.89%   |
| ASUS A88X-PRO                    | 1        | 1.89%   |
| ASRock X570 Steel Legend         | 1        | 1.89%   |
| ASRock X470 Master SLI           | 1        | 1.89%   |
| ASRock H81 Pro BTC R2.0          | 1        | 1.89%   |
| ASRock B550M-ITX/ac              | 1        | 1.89%   |
| ASRock B450 Gaming-ITX/ac        | 1        | 1.89%   |
| Unknown                          | 1        | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Gigabyte Z390          | 4        | 7.55%   |
| ASUS PRIME             | 3        | 5.66%   |
| Dell OptiPlex          | 2        | 3.77%   |
| ASUS ROG               | 2        | 3.77%   |
| Shuttle XS35V4         | 1        | 1.89%   |
| Pegatron IPM31         | 1        | 1.89%   |
| MSI MS-7C91            | 1        | 1.89%   |
| MSI MS-7B85            | 1        | 1.89%   |
| MSI MS-7B84            | 1        | 1.89%   |
| MSI MS-7A34            | 1        | 1.89%   |
| MSI MS-7850            | 1        | 1.89%   |
| MSI MS-7640            | 1        | 1.89%   |
| MEGA G41T-M7           | 1        | 1.89%   |
| Lenovo ThinkCentre     | 1        | 1.89%   |
| Lenovo IdeaCentre      | 1        | 1.89%   |
| Intel X99              | 1        | 1.89%   |
| HP ProDesk             | 1        | 1.89%   |
| Gigabyte X570          | 1        | 1.89%   |
| Gigabyte P31-ES3G      | 1        | 1.89%   |
| Gigabyte J4005ND2P-CF  | 1        | 1.89%   |
| Gigabyte H81M-S2V      | 1        | 1.89%   |
| Gigabyte H61M-HD2      | 1        | 1.89%   |
| Gigabyte H110M-DS2V    | 1        | 1.89%   |
| Gigabyte GA-MA770-UD3  | 1        | 1.89%   |
| Gigabyte GA-890XA-UD3  | 1        | 1.89%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.89%   |
| Gigabyte F2A68HM-H     | 1        | 1.89%   |
| Gigabyte B85M-D3H      | 1        | 1.89%   |
| Gigabyte B360M         | 1        | 1.89%   |
| Fujitsu CELSIUS        | 1        | 1.89%   |
| eMachines EL1852G      | 1        | 1.89%   |
| Dell Studio            | 1        | 1.89%   |
| Biostar H61MLV2        | 1        | 1.89%   |
| Biostar A320MH         | 1        | 1.89%   |
| ASUS TUF               | 1        | 1.89%   |
| ASUS STRIX             | 1        | 1.89%   |
| ASUS P9X79             | 1        | 1.89%   |
| ASUS P5PL2             | 1        | 1.89%   |
| ASUS Maximus           | 1        | 1.89%   |
| ASUS A88X-PRO          | 1        | 1.89%   |
| ASRock X570            | 1        | 1.89%   |
| ASRock X470            | 1        | 1.89%   |
| ASRock H81             | 1        | 1.89%   |
| ASRock B550M-ITX       | 1        | 1.89%   |
| ASRock B450            | 1        | 1.89%   |
| Unknown                | 1        | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 13       | 24.53%  |
| 2019 | 6        | 11.32%  |
| 2014 | 5        | 9.43%   |
| 2013 | 4        | 7.55%   |
| 2017 | 3        | 5.66%   |
| 2015 | 3        | 5.66%   |
| 2012 | 3        | 5.66%   |
| 2011 | 3        | 5.66%   |
| 2008 | 3        | 5.66%   |
| 2021 | 2        | 3.77%   |
| 2020 | 2        | 3.77%   |
| 2010 | 2        | 3.77%   |
| 2006 | 2        | 3.77%   |
| 2016 | 1        | 1.89%   |
| 2009 | 1        | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 53       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 53       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 19       | 35.19%  |
| 32.01-64.0 | 10       | 18.52%  |
| 3.01-4.0   | 9        | 16.67%  |
| 8.01-16.0  | 8        | 14.81%  |
| 4.01-8.0   | 5        | 9.26%   |
| 24.01-32.0 | 2        | 3.7%    |
| 2.01-3.0   | 1        | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 19       | 32.2%   |
| 2.01-3.0  | 12       | 20.34%  |
| 4.01-8.0  | 9        | 15.25%  |
| 3.01-4.0  | 9        | 15.25%  |
| 8.01-16.0 | 7        | 11.86%  |
| 0.51-1.0  | 3        | 5.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 34.55%  |
| 1      | 14       | 25.45%  |
| 4      | 10       | 18.18%  |
| 3      | 6        | 10.91%  |
| 5      | 3        | 5.45%   |
| 6      | 2        | 3.64%   |
| 7      | 1        | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 57.41%  |
| Yes       | 23       | 42.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 58.49%  |
| Yes       | 22       | 41.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 62.96%  |
| Yes       | 20       | 37.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 7        | 13.21%  |
| Germany      | 6        | 11.32%  |
| Russia       | 5        | 9.43%   |
| Brazil       | 5        | 9.43%   |
| Canada       | 4        | 7.55%   |
| Sweden       | 3        | 5.66%   |
| France       | 3        | 5.66%   |
| Spain        | 2        | 3.77%   |
| Netherlands  | 2        | 3.77%   |
| Australia    | 2        | 3.77%   |
| Venezuela    | 1        | 1.89%   |
| Thailand     | 1        | 1.89%   |
| Saudi Arabia | 1        | 1.89%   |
| Portugal     | 1        | 1.89%   |
| Poland       | 1        | 1.89%   |
| Norway       | 1        | 1.89%   |
| Mexico       | 1        | 1.89%   |
| Kazakhstan   | 1        | 1.89%   |
| Ireland      | 1        | 1.89%   |
| Iran         | 1        | 1.89%   |
| India        | 1        | 1.89%   |
| Guyana       | 1        | 1.89%   |
| Greece       | 1        | 1.89%   |
| Albania      | 1        | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Mainz           | 2        | 3.57%   |
| Yekaterinburg   | 1        | 1.79%   |
| Waterloo        | 1        | 1.79%   |
| Vesoul          | 1        | 1.79%   |
| Vancouver       | 1        | 1.79%   |
| Toronto         | 1        | 1.79%   |
| Thessaloniki    | 1        | 1.79%   |
| SГЈo Pedro    | 1        | 1.79%   |
| St Petersburg   | 1        | 1.79%   |
| Seville         | 1        | 1.79%   |
| Severna Park    | 1        | 1.79%   |
| Santa Maria     | 1        | 1.79%   |
| Sadao           | 1        | 1.79%   |
| Portsmouth      | 1        | 1.79%   |
| Phoenix         | 1        | 1.79%   |
| Perth           | 1        | 1.79%   |
| Oslo            | 1        | 1.79%   |
| Orenburg        | 1        | 1.79%   |
| Novosibirsk     | 1        | 1.79%   |
| New York        | 1        | 1.79%   |
| Munich          | 1        | 1.79%   |
| Moita Bonita    | 1        | 1.79%   |
| Mittelbiberach  | 1        | 1.79%   |
| Mexico City     | 1        | 1.79%   |
| Martos          | 1        | 1.79%   |
| Martigues       | 1        | 1.79%   |
| Markham         | 1        | 1.79%   |
| Malmo           | 1        | 1.79%   |
| Loerrach        | 1        | 1.79%   |
| KungÃ¤lv      | 1        | 1.79%   |
| Kostanay        | 1        | 1.79%   |
| Kolkata         | 1        | 1.79%   |
| Irmo            | 1        | 1.79%   |
| Huntington Park | 1        | 1.79%   |
| Guelph          | 1        | 1.79%   |
| GoiГўnia      | 1        | 1.79%   |
| Georgetown      | 1        | 1.79%   |
| Gdansk          | 1        | 1.79%   |
| Funchal         | 1        | 1.79%   |
| Durrës         | 1        | 1.79%   |
| Dublin          | 1        | 1.79%   |
| Dijon           | 1        | 1.79%   |
| Dammam          | 1        | 1.79%   |
| Curitiba        | 1        | 1.79%   |
| Columbia        | 1        | 1.79%   |
| Clecy           | 1        | 1.79%   |
| Caracas         | 1        | 1.79%   |
| Caen            | 1        | 1.79%   |
| Bromma          | 1        | 1.79%   |
| Bladel          | 1        | 1.79%   |
| Berezniki       | 1        | 1.79%   |
| Bad Homburg     | 1        | 1.79%   |
| Arak            | 1        | 1.79%   |
| Alblasserdam    | 1        | 1.79%   |
| Adelaide        | 1        | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 50     | 20.95%  |
| WDC                 | 21       | 36     | 20%     |
| Seagate             | 17       | 40     | 16.19%  |
| Kingston            | 8        | 9      | 7.62%   |
| Toshiba             | 7        | 9      | 6.67%   |
| Unknown             | 4        | 6      | 3.81%   |
| SanDisk             | 4        | 5      | 3.81%   |
| Intel               | 4        | 4      | 3.81%   |
| Hitachi             | 3        | 3      | 2.86%   |
| Crucial             | 3        | 3      | 2.86%   |
| A-DATA Technology   | 3        | 3      | 2.86%   |
| China               | 2        | 2      | 1.9%    |
| PNY                 | 1        | 1      | 0.95%   |
| Phison              | 1        | 1      | 0.95%   |
| Patriot             | 1        | 1      | 0.95%   |
| Micron Technology   | 1        | 1      | 0.95%   |
| Intenso             | 1        | 2      | 0.95%   |
| HGST                | 1        | 1      | 0.95%   |
| Corsair             | 1        | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB        | 7        | 5.3%    |
| Samsung SSD 850 EVO 250GB           | 5        | 3.79%   |
| Samsung SSD 850 EVO 500GB           | 4        | 3.03%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 2.27%   |
| Seagate ST500DM002-1BD142 500GB     | 3        | 2.27%   |
| Seagate ST2000DX002-2DV164 2TB      | 3        | 2.27%   |
| Samsung SSD 860 EVO 500GB           | 3        | 2.27%   |
| WDC WD5000AAKS-00A7B0 500GB         | 2        | 1.52%   |
| WDC WD2003FZEX-00SRLA0 2TB          | 2        | 1.52%   |
| WDC WD10EADS-00M2B0 1TB             | 2        | 1.52%   |
| Unknown TP02000GB 2TB               | 2        | 1.52%   |
| Toshiba DT01ACA050 500GB            | 2        | 1.52%   |
| Seagate ST31000528AS 1TB            | 2        | 1.52%   |
| Seagate ST31000524AS 1TB            | 2        | 1.52%   |
| Seagate ST2000DX001-1NS164 2TB      | 2        | 1.52%   |
| SanDisk SDSSDA240G 240GB            | 2        | 1.52%   |
| Samsung NVMe SSD Drive 1TB          | 2        | 1.52%   |
| Kingston SA400S37240G 240GB SSD     | 2        | 1.52%   |
| Intel NVMe SSD Drive 1024GB         | 2        | 1.52%   |
| Hitachi HTS545032B9A300 320GB       | 2        | 1.52%   |
| WDC WD6400AAKS-75A7B2 640GB         | 1        | 0.76%   |
| WDC WD6400AAKS-65A7B2 640GB         | 1        | 0.76%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 0.76%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.76%   |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 0.76%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 1        | 0.76%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1        | 0.76%   |
| WDC WD32 00AAJS-00L7A0 320GB        | 1        | 0.76%   |
| WDC WD3000GLFS-01F8U0 304GB         | 1        | 0.76%   |
| WDC WD2500HHTZ-04N21V1 250GB        | 1        | 0.76%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 0.76%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 0.76%   |
| WDC WD2002FAEX-007BA0 2TB           | 1        | 0.76%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1        | 0.76%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 0.76%   |
| WDC WD10EADS-22M2B0 1TB             | 1        | 0.76%   |
| WDC WD1003FBYX-01Y7B0 1TB           | 1        | 0.76%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 0.76%   |
| WDC WD1001FALS-75J7B0 1TB           | 1        | 0.76%   |
| WDC WD My Passport 25F3 512GB       | 1        | 0.76%   |
| Unknown SATA3 SSD 128GB             | 1        | 0.76%   |
| Unknown R5M120G8 120GB SSD          | 1        | 0.76%   |
| Toshiba MQ01ABD050 500GB            | 1        | 0.76%   |
| Toshiba MK3276GSX 320GB             | 1        | 0.76%   |
| Toshiba MK3275GSX 320GB             | 1        | 0.76%   |
| Toshiba MK1665GSX 160GB             | 1        | 0.76%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 0.76%   |
| Toshiba DT01ACA100 1TB              | 1        | 0.76%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 0.76%   |
| Seagate ST5000DM000-1FK178 5TB      | 1        | 0.76%   |
| Seagate ST3500418AS 500GB           | 1        | 0.76%   |
| Seagate ST2000LM007-1R8174 2TB      | 1        | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB      | 1        | 0.76%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 0.76%   |
| Seagate ST2000DM005-2CW102 2TB      | 1        | 0.76%   |
| Seagate ST2000DM001-9YN164 2TB      | 1        | 0.76%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 0.76%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 0.76%   |
| Seagate Backup+ Hub BK 8TB          | 1        | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 35     | 39.22%  |
| Seagate             | 17       | 40     | 33.33%  |
| Toshiba             | 6        | 8      | 11.76%  |
| Samsung Electronics | 3        | 3      | 5.88%   |
| Hitachi             | 3        | 3      | 5.88%   |
| Intenso             | 1        | 2      | 1.96%   |
| HGST                | 1        | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 18       | 30     | 43.9%   |
| Kingston            | 5        | 5      | 12.2%   |
| SanDisk             | 4        | 5      | 9.76%   |
| A-DATA Technology   | 3        | 3      | 7.32%   |
| Unknown             | 2        | 2      | 4.88%   |
| Crucial             | 2        | 2      | 4.88%   |
| China               | 2        | 2      | 4.88%   |
| PNY                 | 1        | 1      | 2.44%   |
| Patriot             | 1        | 1      | 2.44%   |
| Micron Technology   | 1        | 1      | 2.44%   |
| Intel               | 1        | 1      | 2.44%   |
| Corsair             | 1        | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 41       | 92     | 42.71%  |
| SSD     | 35       | 54     | 36.46%  |
| NVMe    | 17       | 27     | 17.71%  |
| Unknown | 3        | 5      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 48       | 142    | 68.57%  |
| NVMe | 17       | 27     | 24.29%  |
| SAS  | 5        | 9      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 43       | 79     | 54.43%  |
| 0.51-1.0   | 19       | 27     | 24.05%  |
| 1.01-2.0   | 13       | 33     | 16.46%  |
| 4.01-10.0  | 2        | 2      | 2.53%   |
| 3.01-4.0   | 1        | 3      | 1.27%   |
| 2.01-3.0   | 1        | 2      | 1.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 14       | 25.45%  |
| 101-250        | 13       | 23.64%  |
| 501-1000       | 10       | 18.18%  |
| More than 3000 | 7        | 12.73%  |
| 2001-3000      | 4        | 7.27%   |
| 51-100         | 3        | 5.45%   |
| 21-50          | 2        | 3.64%   |
| 1001-2000      | 2        | 3.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 15       | 26.32%  |
| 21-50          | 10       | 17.54%  |
| 101-250        | 9        | 15.79%  |
| 251-500        | 6        | 10.53%  |
| 501-1000       | 6        | 10.53%  |
| 1001-2000      | 4        | 7.02%   |
| 2001-3000      | 3        | 5.26%   |
| More than 3000 | 2        | 3.51%   |
| 51-100         | 2        | 3.51%   |

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
| Detected | 45       | 146    | 72.58%  |
| Works    | 12       | 26     | 19.35%  |
| Malfunc  | 5        | 6      | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 33       | 43.42%  |
| AMD                          | 22       | 28.95%  |
| Samsung Electronics          | 10       | 13.16%  |
| Kingston Technology Company  | 3        | 3.95%   |
| Marvell Technology Group     | 2        | 2.63%   |
| JMicron Technology           | 2        | 2.63%   |
| Toshiba America Info Systems | 1        | 1.32%   |
| Phison Electronics           | 1        | 1.32%   |
| Micron/Crucial Technology    | 1        | 1.32%   |
| ASMedia Technology           | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 14.29%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 8.16%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 7.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 6.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 6.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 5.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 5.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 3.06%   |
| Kingston Company KC2000 NVMe SSD                                                        | 2        | 2.04%   |
| Intel SSD 660P Series                                                                   | 2        | 2.04%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.04%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.02%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.02%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 1.02%   |
| Marvell Group 88SE9182 PCIe 2.0 x2 2-port SATA 6 Gb/s Controller                        | 1        | 1.02%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 1.02%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 1.02%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.02%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 1.02%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.02%   |
| Intel Atom Processor E3800 Series SATA IDE Controller                                   | 1        | 1.02%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.02%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.02%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.02%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.02%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.02%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 43       | 57.33%  |
| NVMe | 18       | 24%     |
| IDE  | 12       | 16%     |
| RAID | 2        | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 58.49%  |
| AMD    | 22       | 41.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor              | 4        | 7.55%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 2        | 3.77%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 2        | 3.77%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 3.77%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 2        | 3.77%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz             | 1        | 1.89%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1        | 1.89%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz             | 1        | 1.89%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 1        | 1.89%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz     | 1        | 1.89%   |
| Intel Pentium D CPU 3.40GHz                     | 1        | 1.89%   |
| Intel Pentium D CPU 3.00GHz                     | 1        | 1.89%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 1        | 1.89%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 1        | 1.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 1.89%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1        | 1.89%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 1.89%   |
| Intel Core i7-3960X CPU @ 3.30GHz               | 1        | 1.89%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 1.89%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.89%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 1.89%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1.89%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 1.89%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 1.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 1.89%   |
| Intel Core i3-3210 CPU @ 3.20GHz                | 1        | 1.89%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 1.89%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 1        | 1.89%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 1.89%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 1        | 1.89%   |
| Intel Celeron J4005 CPU @ 2.00GHz               | 1        | 1.89%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 1        | 1.89%   |
| Intel Celeron CPU G3930 @ 2.90GHz               | 1        | 1.89%   |
| Intel Celeron CPU E3400 @ 2.60GHz               | 1        | 1.89%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 1        | 1.89%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1        | 1.89%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 1        | 1.89%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 1        | 1.89%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1        | 1.89%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 1.89%   |
| AMD Phenom II X4 955 Processor                  | 1        | 1.89%   |
| AMD Phenom II X4 925 Processor                  | 1        | 1.89%   |
| AMD FX-8320 Eight-Core Processor                | 1        | 1.89%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 1.89%   |
| AMD A10-7890K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.89%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 7        | 13.21%  |
| AMD Ryzen 7             | 7        | 13.21%  |
| AMD Ryzen 5             | 7        | 13.21%  |
| Intel Core i7           | 6        | 11.32%  |
| Intel Core i5           | 4        | 7.55%   |
| Intel Celeron           | 4        | 7.55%   |
| Intel Xeon              | 3        | 5.66%   |
| Intel Pentium Dual-Core | 2        | 3.77%   |
| Intel Pentium D         | 2        | 3.77%   |
| Intel Core 2 Quad       | 2        | 3.77%   |
| AMD Ryzen 9             | 2        | 3.77%   |
| AMD Phenom II X4        | 2        | 3.77%   |
| AMD FX                  | 2        | 3.77%   |
| AMD A10                 | 2        | 3.77%   |
| Intel Core i9           | 1        | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 16       | 30.19%  |
| 2      | 15       | 28.3%   |
| 8      | 10       | 18.87%  |
| 6      | 10       | 18.87%  |
| 16     | 1        | 1.89%   |
| 3      | 1        | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 35       | 66.04%  |
| 1      | 18       | 33.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 52       | 98.11%  |
| Unknown        | 1        | 1.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 6        | 11.32%  |
| 0x08701021 | 5        | 9.43%   |
| 0x1067a    | 4        | 7.55%   |
| 0x0800820d | 3        | 5.66%   |
| Unknown    | 3        | 5.66%   |
| 0x906ec    | 2        | 3.77%   |
| 0x906e9    | 2        | 3.77%   |
| 0x306a9    | 2        | 3.77%   |
| 0x206a7    | 2        | 3.77%   |
| 0x08701013 | 2        | 3.77%   |
| 0x06003106 | 2        | 3.77%   |
| 0x06000852 | 2        | 3.77%   |
| 0xf64      | 1        | 1.89%   |
| 0xf62      | 1        | 1.89%   |
| 0x906ed    | 1        | 1.89%   |
| 0x906eb    | 1        | 1.89%   |
| 0x906ea    | 1        | 1.89%   |
| 0x706a1    | 1        | 1.89%   |
| 0x506e3    | 1        | 1.89%   |
| 0x30678    | 1        | 1.89%   |
| 0x206d7    | 1        | 1.89%   |
| 0x20655    | 1        | 1.89%   |
| 0x10677    | 1        | 1.89%   |
| 0x0a50000c | 1        | 1.89%   |
| 0x0a201009 | 1        | 1.89%   |
| 0x08108109 | 1        | 1.89%   |
| 0x08101016 | 1        | 1.89%   |
| 0x0800820b | 1        | 1.89%   |
| 0x010000db | 1        | 1.89%   |
| 0x010000c8 | 1        | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 8        | 15.09%  |
| KabyLake      | 8        | 15.09%  |
| Haswell       | 7        | 13.21%  |
| Zen+          | 5        | 9.43%   |
| Penryn        | 5        | 9.43%   |
| SandyBridge   | 3        | 5.66%   |
| Zen 3         | 2        | 3.77%   |
| Steamroller   | 2        | 3.77%   |
| Piledriver    | 2        | 3.77%   |
| NetBurst      | 2        | 3.77%   |
| K10           | 2        | 3.77%   |
| IvyBridge     | 2        | 3.77%   |
| Zen           | 1        | 1.89%   |
| Westmere      | 1        | 1.89%   |
| Skylake       | 1        | 1.89%   |
| Silvermont    | 1        | 1.89%   |
| Goldmont plus | 1        | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 24       | 40.68%  |
| AMD    | 22       | 37.29%  |
| Intel  | 13       | 22.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 6.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 6.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 5%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.33%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 3.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.67%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.67%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.67%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 1.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.67%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.67%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.67%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.67%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 1.67%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.67%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.67%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.67%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.67%   |
| Intel HD Graphics 530                                                       | 1        | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.67%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.67%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 1.67%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.67%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.67%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.67%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 1.67%   |
| AMD Cezanne                                                                 | 1        | 1.67%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 1.67%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.67%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 23       | 41.82%  |
| 1 x AMD        | 20       | 36.36%  |
| 1 x Intel      | 8        | 14.55%  |
| Intel + AMD    | 2        | 3.64%   |
| Intel + Nvidia | 1        | 1.82%   |
| AMD + Nvidia   | 1        | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 35       | 66.04%  |
| Proprietary | 18       | 33.96%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 10       | 18.87%  |
| 7.01-8.0   | 9        | 16.98%  |
| 0.51-1.0   | 9        | 16.98%  |
| Unknown    | 8        | 15.09%  |
| 5.01-6.0   | 7        | 13.21%  |
| 3.01-4.0   | 3        | 5.66%   |
| 2.01-3.0   | 3        | 5.66%   |
| 8.01-16.0  | 3        | 5.66%   |
| 0.01-0.5   | 1        | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 16.13%  |
| Goldstar             | 10       | 16.13%  |
| AOC                  | 9        | 14.52%  |
| Dell                 | 8        | 12.9%   |
| Ancor Communications | 5        | 8.06%   |
| LG Electronics       | 4        | 6.45%   |
| Hewlett-Packard      | 3        | 4.84%   |
| Acer                 | 3        | 4.84%   |
| BenQ                 | 2        | 3.23%   |
| ViewSonic            | 1        | 1.61%   |
| Unknown              | 1        | 1.61%   |
| SHARP                | 1        | 1.61%   |
| Philips              | 1        | 1.61%   |
| NEC Computers        | 1        | 1.61%   |
| MSI                  | 1        | 1.61%   |
| JRY                  | 1        | 1.61%   |
| Iiyama               | 1        | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 3        | 4.62%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2        | 3.08%   |
| Ancor Communications LCD Monitor MG248 1920x1080                     | 2        | 3.08%   |
| ViewSonic VP191b VSC0E11 1280x1024 376x301mm 19.0-inch               | 1        | 1.54%   |
| Unknown LCD Monitor HIC 3200x1080                                    | 1        | 1.54%   |
| SHARP LCD Monitor HDMI 1920x1080                                     | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 1.54%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1        | 1.54%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch   | 1        | 1.54%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch    | 1        | 1.54%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 1.54%   |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch     | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 1.54%   |
| Philips PHL 276E6 PHLC0FA 1920x1080 598x336mm 27.0-inch              | 1        | 1.54%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1        | 1.54%   |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                      | 1        | 1.54%   |
| LG Electronics LCD Monitor W1952 1440x900                            | 1        | 1.54%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3440x1440                    | 1        | 1.54%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                     | 1        | 1.54%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.54%   |
| JRY HDMI JRY1950 1366x768 410x220mm 18.3-inch                        | 1        | 1.54%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                | 1        | 1.54%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 518x324mm 24.1-inch          | 1        | 1.54%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch           | 1        | 1.54%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1        | 1.54%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1        | 1.54%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1        | 1.54%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch             | 1        | 1.54%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch             | 1        | 1.54%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 1.54%   |
| Goldstar T730SH GSM43CB 1280x960 310x230mm 15.2-inch                 | 1        | 1.54%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                | 1        | 1.54%   |
| Goldstar E2241 GSM5819 1920x1080 477x268mm 21.5-inch                 | 1        | 1.54%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1        | 1.54%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 1.54%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                  | 1        | 1.54%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                  | 1        | 1.54%   |
| Dell S2719DGF DELD0E6 2560x1440 600x340mm 27.2-inch                  | 1        | 1.54%   |
| Dell S2009W DELA044 1600x900 443x249mm 20.0-inch                     | 1        | 1.54%   |
| Dell LCD Monitor UP2516D 2560x1440                                   | 1        | 1.54%   |
| Dell LCD Monitor U2412M                                              | 1        | 1.54%   |
| Dell LCD Monitor P1130 1280x1024                                     | 1        | 1.54%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1        | 1.54%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 530x300mm 24.0-inch              | 1        | 1.54%   |
| BenQ LCD Monitor GL2760 3840x1080                                    | 1        | 1.54%   |
| BenQ LCD Monitor GL2460                                              | 1        | 1.54%   |
| AOC Q29G2G5 AOC2902 2560x1080 681x287mm 29.1-inch                    | 1        | 1.54%   |
| AOC LCD Monitor 2757 1920x1080                                       | 1        | 1.54%   |
| AOC LCD Monitor 24B2W1                                               | 1        | 1.54%   |
| AOC 2481W AOC2481 1920x1080 527x296mm 23.8-inch                      | 1        | 1.54%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 1        | 1.54%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                     | 1        | 1.54%   |
| AOC 1970W-1 AOC1970 1366x768 410x230mm 18.5-inch                     | 1        | 1.54%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch     | 1        | 1.54%   |
| Ancor Communications LCD Monitor VX229                               | 1        | 1.54%   |
| Ancor Communications LCD Monitor ROG PG278Q 4480x1440                | 1        | 1.54%   |
| Acer V236HL ACR0350 1920x1080 509x286mm 23.0-inch                    | 1        | 1.54%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 1        | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 38.71%  |
| 2560x1440 (QHD)    | 7        | 11.29%  |
| 1366x768 (WXGA)    | 5        | 8.06%   |
| 1280x1024 (SXGA)   | 4        | 6.45%   |
| Unknown            | 4        | 6.45%   |
| 1600x900 (HD+)     | 3        | 4.84%   |
| 1440x900 (WXGA+)   | 3        | 4.84%   |
| 2560x1080          | 2        | 3.23%   |
| 4480x1440          | 1        | 1.61%   |
| 3840x2160 (4K)     | 1        | 1.61%   |
| 3840x1080          | 1        | 1.61%   |
| 3440x1440          | 1        | 1.61%   |
| 3200x1080          | 1        | 1.61%   |
| 1920x1200 (WUXGA)  | 1        | 1.61%   |
| 1680x1050 (WSXGA+) | 1        | 1.61%   |
| 1360x768           | 1        | 1.61%   |
| 1152x864           | 1        | 1.61%   |
| 1024x768 (XGA)     | 1        | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 27.59%  |
| 24      | 8        | 13.79%  |
| 27      | 6        | 10.34%  |
| 18      | 6        | 10.34%  |
| 23      | 5        | 8.62%   |
| 21      | 5        | 8.62%   |
| 20      | 3        | 5.17%   |
| 15      | 2        | 3.45%   |
| 34      | 1        | 1.72%   |
| 31      | 1        | 1.72%   |
| 29      | 1        | 1.72%   |
| 25      | 1        | 1.72%   |
| 22      | 1        | 1.72%   |
| 19      | 1        | 1.72%   |
| 17      | 1        | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 31.58%  |
| Unknown     | 16       | 28.07%  |
| 401-500     | 15       | 26.32%  |
| 601-700     | 3        | 5.26%   |
| 301-350     | 3        | 5.26%   |
| 701-800     | 1        | 1.75%   |
| 351-400     | 1        | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 50%     |
| Unknown | 16       | 27.59%  |
| 16/10   | 7        | 12.07%  |
| 4/3     | 2        | 3.45%   |
| 21/9    | 2        | 3.45%   |
| 6/5     | 1        | 1.72%   |
| 5/4     | 1        | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 27.59%  |
| Unknown        | 16       | 27.59%  |
| 301-350        | 7        | 12.07%  |
| 151-200        | 6        | 10.34%  |
| 251-300        | 4        | 6.9%    |
| 141-150        | 4        | 6.9%    |
| 351-500        | 2        | 3.45%   |
| 131-140        | 1        | 1.72%   |
| 111-120        | 1        | 1.72%   |
| 101-110        | 1        | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 54.39%  |
| Unknown | 16       | 28.07%  |
| 101-120 | 9        | 15.79%  |
| 161-240 | 1        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 75.93%  |
| 2     | 13       | 24.07%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 38       | 46.34%  |
| Intel                 | 21       | 25.61%  |
| Qualcomm Atheros      | 5        | 6.1%    |
| Xiaomi                | 2        | 2.44%   |
| TP-Link               | 2        | 2.44%   |
| Ralink Technology     | 2        | 2.44%   |
| MediaTek              | 2        | 2.44%   |
| Broadcom              | 2        | 2.44%   |
| NetGear               | 1        | 1.22%   |
| Microchip Technology  | 1        | 1.22%   |
| Linksys               | 1        | 1.22%   |
| Huawei Technologies   | 1        | 1.22%   |
| D-Link System         | 1        | 1.22%   |
| Broadcom Limited      | 1        | 1.22%   |
| Belkin Components     | 1        | 1.22%   |
| Aquantia              | 1        | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                       | 33       | 35.48%  |
| Intel I211 Gigabit Network Connection                                                   | 8        | 8.6%    |
| Realtek RTL8125 2.5GbE Controller                                                       | 3        | 3.23%   |
| Intel Ethernet Connection (7) I219-V                                                    | 3        | 3.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                          | 2        | 2.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                             | 2        | 2.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 2.15%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                        | 2        | 2.15%   |
| Intel Ethernet Connection I217-LM                                                       | 2        | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 2        | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 1.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 1        | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                              | 1        | 1.08%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                | 1        | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                   | 1        | 1.08%   |
| Realtek 802.11ac NIC                                                                    | 1        | 1.08%   |
| Ralink RT5372 Wireless Adapter                                                          | 1        | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1        | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1        | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                              | 1        | 1.08%   |
| NetGear A6150                                                                           | 1        | 1.08%   |
| Microchip MCP2200 USB Serial Port Emulator                                              | 1        | 1.08%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                                           | 1        | 1.08%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 1.08%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 1.08%   |
| Intel Wireless-AC 9260                                                                  | 1        | 1.08%   |
| Intel Wireless 7265                                                                     | 1        | 1.08%   |
| Intel Wireless 3165                                                                     | 1        | 1.08%   |
| Intel Wi-Fi 6 AX200                                                                     | 1        | 1.08%   |
| Intel Ethernet Controller I225-V                                                        | 1        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                                    | 1        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 1        | 1.08%   |
| Intel 82583V Gigabit Network Connection                                                 | 1        | 1.08%   |
| Intel 82579V Gigabit Network Connection                                                 | 1        | 1.08%   |
| Intel 82578DC Gigabit Network Connection                                                | 1        | 1.08%   |
| Huawei JAT-LX1                                                                          | 1        | 1.08%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 1.08%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                                 | 1        | 1.08%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                                  | 1        | 1.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 1.08%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 1.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                       | 1        | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 23.33%  |
| Intel                 | 7        | 23.33%  |
| Qualcomm Atheros      | 4        | 13.33%  |
| TP-Link               | 2        | 6.67%   |
| Ralink Technology     | 2        | 6.67%   |
| MediaTek              | 2        | 6.67%   |
| NetGear               | 1        | 3.33%   |
| Linksys               | 1        | 3.33%   |
| D-Link System         | 1        | 3.33%   |
| Broadcom Limited      | 1        | 3.33%   |
| Broadcom              | 1        | 3.33%   |
| Belkin Components     | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                             | 2        | 6.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2        | 6.67%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                        | 2        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 2        | 6.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 3.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 1        | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                              | 1        | 3.33%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1        | 3.33%   |
| Realtek 802.11ac NIC                                                                    | 1        | 3.33%   |
| Ralink RT5372 Wireless Adapter                                                          | 1        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                                         | 1        | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1        | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1        | 3.33%   |
| NetGear A6150                                                                           | 1        | 3.33%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                                           | 1        | 3.33%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1        | 3.33%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1        | 3.33%   |
| Intel Wireless-AC 9260                                                                  | 1        | 3.33%   |
| Intel Wireless 7265                                                                     | 1        | 3.33%   |
| Intel Wireless 3165                                                                     | 1        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                                     | 1        | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 1        | 3.33%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1        | 3.33%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                                  | 1        | 3.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 3.33%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 35       | 59.32%  |
| Intel                 | 18       | 30.51%  |
| Xiaomi                | 2        | 3.39%   |
| Qualcomm Atheros      | 1        | 1.69%   |
| Huawei Technologies   | 1        | 1.69%   |
| Broadcom              | 1        | 1.69%   |
| Aquantia              | 1        | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33       | 53.23%  |
| Intel I211 Gigabit Network Connection                             | 8        | 12.9%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 4.84%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 4.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.61%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.61%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.61%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.61%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.61%   |
| Huawei JAT-LX1                                                    | 1        | 1.61%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.61%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 68.83%  |
| WiFi     | 23       | 29.87%  |
| Modem    | 1        | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 71.01%  |
| WiFi     | 20       | 28.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 68.52%  |
| 2     | 15       | 27.78%  |
| 3     | 2        | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 81.82%  |
| Yes  | 10       | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 30.43%  |
| Cambridge Silicon Radio | 7        | 30.43%  |
| Broadcom                | 3        | 13.04%  |
| Realtek Semiconductor   | 2        | 8.7%    |
| ASUSTek Computer        | 2        | 8.7%    |
| MediaTek                | 1        | 4.35%   |
| Apple                   | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 30.43%  |
| Realtek Bluetooth Radio                             | 2        | 8.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 8.7%    |
| Intel Bluetooth wireless interface                  | 2        | 8.7%    |
| MediaTek Wireless_Device                            | 1        | 4.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.35%   |
| Intel AX200 Bluetooth                               | 1        | 4.35%   |
| Broadcom BCM92045B3 ROM                             | 1        | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.35%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 4.35%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 4.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.35%   |
| Apple Bluetooth USB Host Controller                 | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 29       | 29.9%   |
| AMD                     | 28       | 28.87%  |
| Nvidia                  | 24       | 24.74%  |
| Blue Microphones        | 3        | 3.09%   |
| Logitech                | 2        | 2.06%   |
| C-Media Electronics     | 2        | 2.06%   |
| Yamaha                  | 1        | 1.03%   |
| Tenx Technology         | 1        | 1.03%   |
| SteelSeries ApS         | 1        | 1.03%   |
| SAVITECH                | 1        | 1.03%   |
| RME                     | 1        | 1.03%   |
| JMTek                   | 1        | 1.03%   |
| Creative Technology     | 1        | 1.03%   |
| Creative Labs           | 1        | 1.03%   |
| BEHRINGER International | 1        | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 7.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 5.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 4.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 4.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 4.31%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 4.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 3.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.72%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 1.72%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.72%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2        | 1.72%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.72%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.72%   |
| Yamaha Steinberg UR44                                                      | 1        | 0.86%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.86%   |
| SteelSeries ApS Arctis 7 wireless adapter                                  | 1        | 0.86%   |
| SAVITECH ODAC-revB                                                         | 1        | 0.86%   |
| RME Babyface Pro (71964113)                                                | 1        | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.86%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.86%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.86%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.86%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.86%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 0.86%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 0.86%   |
| Logitech USB Headset                                                       | 1        | 0.86%   |
| JMTek USB PnP Audio Device(EEPROM)                                         | 1        | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.86%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 0.86%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 0.86%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 0.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.86%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 0.86%   |
| Creative Technology SB X-Fi Surround 5.1 Pro                               | 1        | 0.86%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 0.86%   |
| C-Media Electronics USB Advanced Audio Device                              | 1        | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.86%   |
| Blue Microphones Yeti Nano                                                 | 1        | 0.86%   |
| BEHRINGER International UMC202HD 192k                                      | 1        | 0.86%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 0.86%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 0.86%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 0.86%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Corsair           | 6        | 42.86%  |
| Unknown           | 2        | 14.29%  |
| Crucial           | 2        | 14.29%  |
| Transcend         | 1        | 7.14%   |
| Patriot           | 1        | 7.14%   |
| G.Skill           | 1        | 7.14%   |
| A-DATA Technology | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 2        | 11.11%  |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 5.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s              | 1        | 5.56%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s              | 1        | 5.56%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s         | 1        | 5.56%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s       | 1        | 5.56%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 1        | 5.56%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 1        | 5.56%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s  | 1        | 5.56%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8192MB DIMM DDR4 3200MT/s | 1        | 5.56%   |
| Corsair RAM CMY8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s       | 1        | 5.56%   |
| Corsair RAM CMX8GX3M2B1600C9 4GB DIMM 1600MT/s            | 1        | 5.56%   |
| Corsair RAM CMX8GX3M2A1600C9 4096MB DIMM DDR3 1800MT/s    | 1        | 5.56%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s     | 1        | 5.56%   |
| Corsair RAM CMK32GX4M2B3000C15 16384MB DIMM DDR4 3000MT/s | 1        | 5.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 5.56%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s               | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 7        | 53.85%  |
| DDR3 | 6        | 46.15%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 13       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 43.75%  |
| 4096  | 6        | 37.5%   |
| 16384 | 2        | 12.5%   |
| 2048  | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 23.53%  |
| 3466  | 2        | 11.76%  |
| 3200  | 2        | 11.76%  |
| 2400  | 2        | 11.76%  |
| 3866  | 1        | 5.88%   |
| 3600  | 1        | 5.88%   |
| 3266  | 1        | 5.88%   |
| 3000  | 1        | 5.88%   |
| 1800  | 1        | 5.88%   |
| 1333  | 1        | 5.88%   |
| 1066  | 1        | 5.88%   |

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
| Logitech            | 7        | 46.67%  |
| Microsoft           | 2        | 13.33%  |
| Microdia            | 2        | 13.33%  |
| Samsung Electronics | 1        | 6.67%   |
| LG Electronics      | 1        | 6.67%   |
| Hewlett-Packard     | 1        | 6.67%   |
| Apple               | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microdia Camera                      | 2        | 13.33%  |
| Logitech Logitech Webcam C160        | 2        | 13.33%  |
| Samsung Galaxy A5 (MTP)              | 1        | 6.67%   |
| Microsoft Xbox NUI Camera            | 1        | 6.67%   |
| Microsoft LifeCam HD-3000            | 1        | 6.67%   |
| Logitech Webcam C270                 | 1        | 6.67%   |
| Logitech StreamCam                   | 1        | 6.67%   |
| Logitech HD Pro Webcam C920          | 1        | 6.67%   |
| Logitech C922 Pro Stream Webcam      | 1        | 6.67%   |
| Logitech C920 PRO HD Webcam          | 1        | 6.67%   |
| LG Optimus (Various Models) MTP Mode | 1        | 6.67%   |
| HP Webcam HD 2300                    | 1        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE            | 1        | 6.67%   |

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
| 0     | 44       | 81.48%  |
| 1     | 6        | 11.11%  |
| 2     | 3        | 5.56%   |
| 3     | 1        | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 7        | 46.67%  |
| Graphics card         | 2        | 13.33%  |
| Unassigned class      | 1        | 6.67%   |
| Tv card               | 1        | 6.67%   |
| Network               | 1        | 6.67%   |
| Multimedia controller | 1        | 6.67%   |
| Chipcard              | 1        | 6.67%   |
| Camera                | 1        | 6.67%   |


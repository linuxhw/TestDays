Rocky Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

Total: 102

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Pro WS X570-ACE             | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [3734293144](https://linux-hardware.org/?probe=3734293144) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [72bedff7a6](https://linux-hardware.org/?probe=72bedff7a6) | Nov 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [650d69cdce](https://linux-hardware.org/?probe=650d69cdce) | Oct 31, 2023 |
| HP            | 1587h                       | [ecafcd1843](https://linux-hardware.org/?probe=ecafcd1843) | Oct 30, 2023 |
| HP            | 8653 A                      | [6d84c59a16](https://linux-hardware.org/?probe=6d84c59a16) | Oct 25, 2023 |
| Lenovo        | 31900058 STD                | [b6c589b413](https://linux-hardware.org/?probe=b6c589b413) | Oct 19, 2023 |
| Shenzhen M... | HX90G                       | [a6e9f6c7fc](https://linux-hardware.org/?probe=a6e9f6c7fc) | Oct 01, 2023 |
| Dell          | 0D24M8 A01                  | [214eb681ad](https://linux-hardware.org/?probe=214eb681ad) | Oct 01, 2023 |
| ASUSTek       | F1A55-M LX PLUS             | [a2aebc52bd](https://linux-hardware.org/?probe=a2aebc52bd) | Sep 03, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | [e584e6c368](https://linux-hardware.org/?probe=e584e6c368) | Aug 16, 2023 |
| ASRock        | X670E Pro RS                | [baa9e459cc](https://linux-hardware.org/?probe=baa9e459cc) | Aug 09, 2023 |
| Gigabyte      | H77N-WIFI                   | [32fd45f163](https://linux-hardware.org/?probe=32fd45f163) | Aug 04, 2023 |
| MSI           | PRO B650-P WIFI             | [92abff2d6e](https://linux-hardware.org/?probe=92abff2d6e) | Jul 31, 2023 |
| MSI           | PRO B650-P WIFI             | [d1c158eebc](https://linux-hardware.org/?probe=d1c158eebc) | Jul 31, 2023 |
| HP            | 0AECh D                     | [58f6dd1695](https://linux-hardware.org/?probe=58f6dd1695) | Jul 14, 2023 |
| ASUSTek       | M5A78L-M LX                 | [b4b1f263a8](https://linux-hardware.org/?probe=b4b1f263a8) | Jul 08, 2023 |
| Gigabyte      | H61M-DS2                    | [2310257292](https://linux-hardware.org/?probe=2310257292) | Jun 19, 2023 |
| Gigabyte      | H61M-DS2                    | [ee6f9906b5](https://linux-hardware.org/?probe=ee6f9906b5) | Jun 19, 2023 |
| Techvision    | TVI7309X B0                 | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [da8705e5a7](https://linux-hardware.org/?probe=da8705e5a7) | May 31, 2023 |
| HPE           | ProLiant MicroServer Gen... | [530b841978](https://linux-hardware.org/?probe=530b841978) | May 25, 2023 |
| ASRock        | AM1B-ITX                    | [a2e80bffac](https://linux-hardware.org/?probe=a2e80bffac) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | [d0633ac39d](https://linux-hardware.org/?probe=d0633ac39d) | May 19, 2023 |
| AZW           | MINI S                      | [d7ee12a01b](https://linux-hardware.org/?probe=d7ee12a01b) | May 08, 2023 |
| Dell          | 0D735T A00                  | [3070f4e7da](https://linux-hardware.org/?probe=3070f4e7da) | May 02, 2023 |
| Dell          | 06D7TR A00                  | [6fe7179a50](https://linux-hardware.org/?probe=6fe7179a50) | May 01, 2023 |
| Dell          | 0Y2MRG A00                  | [5f765d4d9c](https://linux-hardware.org/?probe=5f765d4d9c) | Apr 29, 2023 |
| Dell          | 0Y2MRG A00                  | [62a4a8b0b5](https://linux-hardware.org/?probe=62a4a8b0b5) | Apr 29, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [fd875a6058](https://linux-hardware.org/?probe=fd875a6058) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| AZW           | GTR V02                     | [fcd41fbe77](https://linux-hardware.org/?probe=fcd41fbe77) | Mar 10, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2               | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| HP            | 1587h                       | [312effb7b7](https://linux-hardware.org/?probe=312effb7b7) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| Dell          | 08HPGT A01                  | [bf2c6ebd43](https://linux-hardware.org/?probe=bf2c6ebd43) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| ASRock        | H610M-HDV/M.2               | [2936bb8fec](https://linux-hardware.org/?probe=2936bb8fec) | Jan 26, 2023 |
| Lenovo        | NOK                         | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| Dell          | 0Y2MRG A00                  | [784e2db087](https://linux-hardware.org/?probe=784e2db087) | Jan 25, 2023 |
| MSI           | H510M PRO-E                 | [c81f6adb11](https://linux-hardware.org/?probe=c81f6adb11) | Jan 20, 2023 |
| Unknown       | Unknown                     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| Dell          | 0VRWRC A00                  | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | 805D                        | [cf88e571df](https://linux-hardware.org/?probe=cf88e571df) | Dec 28, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| ASUSTek       | X99-WS/IPMI                 | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Intel         | D33217GKE G69901-202        | [f10d00e42a](https://linux-hardware.org/?probe=f10d00e42a) | Nov 12, 2022 |
| HP            | 8054                        | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                        | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| ASUSTek       | Crosshair V Formula         | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| Gigabyte      | H81M-S2PV                   | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| BESSTAR Te... | HM90                        | [fd411132f6](https://linux-hardware.org/?probe=fd411132f6) | Oct 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | PRIME H570-PLUS             | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| ASUSTek       | PRIME B550M-K               | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| ASUSTek       | P8B WS                      | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo        | 1046 NO DPK                 | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Gigabyte      | 970A-UD3P                   | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| Unknown       | X31_ICH7                    | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01                  | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 06CV2N A00                  | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3                  | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3                  | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1             | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| Dell          | 0NK70N A03                  | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Dell          | 0WN7Y6 A01                  | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02                  | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| ASRock        | B450M Pro4                  | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6               | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| AZW           | Gemini M                    | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M                    | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Tricky                      | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF                  | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Dell          | 0N4YC8 A00                  | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| ASUSTek       | PRIME B450M-A II            | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE                  | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | NOK                         | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Dell          | 0M5DCD A00                  | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| ASUSTek       | PRIME TRX40-PRO S           | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| HP            | 0B54h D                     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Rocky Linux 9.1 | 17       | 22.37%  |
| Rocky Linux 8.5 | 12       | 15.79%  |
| Rocky Linux 8.4 | 9        | 11.84%  |
| Rocky Linux 9.2 | 8        | 10.53%  |
| Rocky Linux 8.6 | 8        | 10.53%  |
| Rocky Linux 9.0 | 7        | 9.21%   |
| Rocky Linux 8.8 | 7        | 9.21%   |
| Rocky Linux 8.7 | 7        | 9.21%   |
| Rocky Linux 8.3 | 1        | 1.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 75       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 6        | 7.5%    |
| 4.18.0-348.12.2.el8_5.x86_64     | 6        | 7.5%    |
| 5.14.0-284.11.1.el9_2.x86_64     | 4        | 5%      |
| 5.14.0-162.18.1.el9_1.x86_64     | 4        | 5%      |
| 5.14.0-70.30.1.el9_0.x86_64      | 3        | 3.75%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 3        | 3.75%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 3        | 3.75%   |
| 4.18.0-477.27.1.el8_8.x86_64     | 3        | 3.75%   |
| 4.18.0-425.19.2.el8_7.x86_64     | 3        | 3.75%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3        | 3.75%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 3        | 3.75%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 2        | 2.5%    |
| 4.18.0-477.21.1.el8_8.x86_64     | 2        | 2.5%    |
| 4.18.0-477.15.1.el8_8.x86_64     | 2        | 2.5%    |
| 4.18.0-425.13.1.el8_7.x86_64     | 2        | 2.5%    |
| 4.18.0-425.10.1.el8_7.x86_64     | 2        | 2.5%    |
| 4.18.0-372.32.1.el8_6.x86_64     | 2        | 2.5%    |
| 4.18.0-372.26.1.el8_6.x86_64     | 2        | 2.5%    |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2        | 2.5%    |
| 4.18.0-348.20.1.el8_5.x86_64     | 2        | 2.5%    |
| 4.18.0-305.19.1.el8_4.x86_64     | 2        | 2.5%    |
| 4.18.0-305.12.1.el8_4.x86_64     | 2        | 2.5%    |
| 6.1.8-1.el9.elrepo.x86_64        | 1        | 1.25%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1        | 1.25%   |
| 6.0.10_tkg_bmq                   | 1        | 1.25%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1        | 1.25%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1        | 1.25%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 1        | 1.25%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1        | 1.25%   |
| 5.14.0-284.25.1.el9_2.x86_64     | 1        | 1.25%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 1        | 1.25%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 1        | 1.25%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1        | 1.25%   |
| 4.18.0-425.3.1.el8.x86_64        | 1        | 1.25%   |
| 4.18.0-372.9.1.el8.x86_64        | 1        | 1.25%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 1        | 1.25%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1        | 1.25%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 1        | 1.25%   |
| 4.18.0-240.22.1.el8.x86_64       | 1        | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 42       | 55.26%  |
| 5.14.0  | 29       | 38.16%  |
| 6.0.10  | 2        | 2.63%   |
| 6.1.8   | 1        | 1.32%   |
| 6.1.6   | 1        | 1.32%   |
| 5.14.1  | 1        | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 42       | 55.26%  |
| 5.14    | 30       | 39.47%  |
| 6.1     | 2        | 2.63%   |
| 6.0     | 2        | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 75       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 46       | 61.33%  |
| Unknown       | 15       | 20%     |
| KDE5          | 7        | 9.33%   |
| GNOME Classic | 4        | 5.33%   |
| MATE          | 2        | 2.67%   |
| XFCE          | 1        | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 36       | 45.57%  |
| X11     | 29       | 36.71%  |
| Unknown | 7        | 8.86%   |
| Tty     | 5        | 6.33%   |
| Web     | 2        | 2.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 46.67%  |
| GDM     | 33       | 44%     |
| SDDM    | 5        | 6.67%   |
| LightDM | 2        | 2.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 44       | 58.67%  |
| ru_RU   | 4        | 5.33%   |
| en_CA   | 4        | 5.33%   |
| en_IL   | 3        | 4%      |
| en_SG   | 2        | 2.67%   |
| en_GB   | 2        | 2.67%   |
| en_AU   | 2        | 2.67%   |
| C       | 2        | 2.67%   |
| Unknown | 2        | 2.67%   |
| zh_CN   | 1        | 1.33%   |
| pt_BR   | 1        | 1.33%   |
| pl_PL   | 1        | 1.33%   |
| ko_KR   | 1        | 1.33%   |
| ja_JP   | 1        | 1.33%   |
| es_CO   | 1        | 1.33%   |
| es_AR   | 1        | 1.33%   |
| en_ZA   | 1        | 1.33%   |
| en_IN   | 1        | 1.33%   |
| af_ZA   | 1        | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 43       | 56.58%  |
| BIOS | 33       | 43.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 62       | 82.67%  |
| Ext4 | 13       | 17.33%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 43       | 57.33%  |
| Unknown | 19       | 25.33%  |
| MBR     | 13       | 17.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 77.33%  |
| Yes       | 17       | 22.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 86.67%  |
| Yes       | 10       | 13.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 25.33%  |
| Dell                | 13       | 17.33%  |
| MSI                 | 8        | 10.67%  |
| Gigabyte Technology | 8        | 10.67%  |
| Hewlett-Packard     | 7        | 9.33%   |
| Lenovo              | 4        | 5.33%   |
| ASRock              | 4        | 5.33%   |
| AZW                 | 3        | 4%      |
| Unknown             | 2        | 2.67%   |
| Techvision          | 1        | 1.33%   |
| Sapphire            | 1        | 1.33%   |
| NCR                 | 1        | 1.33%   |
| Intel               | 1        | 1.33%   |
| HPE                 | 1        | 1.33%   |
| Google              | 1        | 1.33%   |
| BESSTAR Tech        | 1        | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| HP Z210 Workstation                 | 2        | 2.67%   |
| Dell OptiPlex 9020                  | 2        | 2.67%   |
| Unknown                             | 2        | 2.67%   |
| Techvision TVI7309X                 | 1        | 1.33%   |
| Sapphire PE-AM2RS690V2              | 1        | 1.33%   |
| NCR xxxx-xxxx-xxxx                  | 1        | 1.33%   |
| MSI MS-7D78                         | 1        | 1.33%   |
| MSI MS-7D46                         | 1        | 1.33%   |
| MSI MS-7D25                         | 1        | 1.33%   |
| MSI MS-7B89                         | 1        | 1.33%   |
| MSI MS-7B78                         | 1        | 1.33%   |
| MSI MS-7A94                         | 1        | 1.33%   |
| MSI MS-7917                         | 1        | 1.33%   |
| MSI H510M PRO-E                     | 1        | 1.33%   |
| Lenovo ThinkStation P620 30E0S0PR00 | 1        | 1.33%   |
| Lenovo ThinkStation P340 30DK000CUS | 1        | 1.33%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 1.33%   |
| Lenovo H535 10117                   | 1        | 1.33%   |
| Intel PRO412081                     | 1        | 1.33%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 1.33%   |
| HP Z800 Workstation                 | 1        | 1.33%   |
| HP Z600 Workstation                 | 1        | 1.33%   |
| HP ProDesk 600 G2 SFF               | 1        | 1.33%   |
| HP ENVY TE01-0xxx                   | 1        | 1.33%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.33%   |
| Google Tricky                       | 1        | 1.33%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 1.33%   |
| Gigabyte H87-D3H                    | 1        | 1.33%   |
| Gigabyte H81M-S2PV                  | 1        | 1.33%   |
| Gigabyte H61M-DS2                   | 1        | 1.33%   |
| Gigabyte G41MT-USB3                 | 1        | 1.33%   |
| Gigabyte EUROLINUX_V1               | 1        | 1.33%   |
| Gigabyte 970A-UD3P                  | 1        | 1.33%   |
| Gigabyte 970A-DS3P                  | 1        | 1.33%   |
| Dell XPS 8300                       | 1        | 1.33%   |
| Dell Vostro 430                     | 1        | 1.33%   |
| Dell Vostro 3681                    | 1        | 1.33%   |
| Dell Precision Tower 7810           | 1        | 1.33%   |
| Dell Precision T7610                | 1        | 1.33%   |
| Dell Precision T5610                | 1        | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 9        | 12%     |
| Dell OptiPlex          | 6        | 8%      |
| Dell Precision         | 4        | 5.33%   |
| Lenovo ThinkStation    | 2        | 2.67%   |
| HP Z210                | 2        | 2.67%   |
| Dell Vostro            | 2        | 2.67%   |
| ASUS ROG               | 2        | 2.67%   |
| Unknown                | 2        | 2.67%   |
| Techvision TVI7309X    | 1        | 1.33%   |
| Sapphire PE-AM2RS690V2 | 1        | 1.33%   |
| NCR xxxx-xxxx-xxxx     | 1        | 1.33%   |
| MSI MS-7D78            | 1        | 1.33%   |
| MSI MS-7D46            | 1        | 1.33%   |
| MSI MS-7D25            | 1        | 1.33%   |
| MSI MS-7B89            | 1        | 1.33%   |
| MSI MS-7B78            | 1        | 1.33%   |
| MSI MS-7A94            | 1        | 1.33%   |
| MSI MS-7917            | 1        | 1.33%   |
| MSI H510M              | 1        | 1.33%   |
| Lenovo ThinkCentre     | 1        | 1.33%   |
| Lenovo H535            | 1        | 1.33%   |
| Intel PRO412081        | 1        | 1.33%   |
| HPE ProLiant           | 1        | 1.33%   |
| HP Z800                | 1        | 1.33%   |
| HP Z600                | 1        | 1.33%   |
| HP ProDesk             | 1        | 1.33%   |
| HP ENVY                | 1        | 1.33%   |
| HP EliteDesk           | 1        | 1.33%   |
| Google Tricky          | 1        | 1.33%   |
| Gigabyte X570          | 1        | 1.33%   |
| Gigabyte H87-D3H       | 1        | 1.33%   |
| Gigabyte H81M-S2PV     | 1        | 1.33%   |
| Gigabyte H61M-DS2      | 1        | 1.33%   |
| Gigabyte G41MT-USB3    | 1        | 1.33%   |
| Gigabyte EUROLINUX     | 1        | 1.33%   |
| Gigabyte 970A-UD3P     | 1        | 1.33%   |
| Gigabyte 970A-DS3P     | 1        | 1.33%   |
| Dell XPS               | 1        | 1.33%   |
| BESSTAR Tech HM90      | 1        | 1.33%   |
| AZW MINI               | 1        | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 10       | 13.33%  |
| 2021 | 9        | 12%     |
| 2020 | 8        | 10.67%  |
| 2013 | 8        | 10.67%  |
| 2022 | 6        | 8%      |
| 2018 | 6        | 8%      |
| 2015 | 5        | 6.67%   |
| 2014 | 5        | 6.67%   |
| 2019 | 4        | 5.33%   |
| 2012 | 4        | 5.33%   |
| 2008 | 3        | 4%      |
| 2023 | 2        | 2.67%   |
| 2017 | 2        | 2.67%   |
| 2010 | 2        | 2.67%   |
| 2009 | 1        | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 75       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 70       | 93.33%  |
| Enabled  | 5        | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 74       | 98.67%  |
| Yes  | 1        | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 17       | 22.37%  |
| 4.01-8.0    | 13       | 17.11%  |
| 16.01-24.0  | 12       | 15.79%  |
| 8.01-16.0   | 12       | 15.79%  |
| 64.01-256.0 | 10       | 13.16%  |
| 3.01-4.0    | 4        | 5.26%   |
| 24.01-32.0  | 3        | 3.95%   |
| 1.01-2.0    | 3        | 3.95%   |
| 2.01-3.0    | 2        | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 23       | 29.11%  |
| 4.01-8.0   | 16       | 20.25%  |
| 3.01-4.0   | 15       | 18.99%  |
| 1.01-2.0   | 10       | 12.66%  |
| 0.51-1.0   | 5        | 6.33%   |
| 8.01-16.0  | 4        | 5.06%   |
| 32.01-64.0 | 2        | 2.53%   |
| 16.01-24.0 | 2        | 2.53%   |
| 0.01-0.5   | 2        | 2.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 43.42%  |
| 2      | 17       | 22.37%  |
| 4      | 11       | 14.47%  |
| 3      | 8        | 10.53%  |
| 6      | 3        | 3.95%   |
| 5      | 2        | 2.63%   |
| 9      | 1        | 1.32%   |
| 8      | 1        | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 61.33%  |
| Yes       | 29       | 38.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 74       | 98.67%  |
| No        | 1        | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 64.47%  |
| Yes       | 27       | 35.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 71.05%  |
| Yes       | 22       | 28.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 23       | 30.67%  |
| Canada       | 6        | 8%      |
| Russia       | 5        | 6.67%   |
| Singapore    | 3        | 4%      |
| Italy        | 3        | 4%      |
| Israel       | 3        | 4%      |
| Australia    | 3        | 4%      |
| UK           | 2        | 2.67%   |
| South Korea  | 2        | 2.67%   |
| South Africa | 2        | 2.67%   |
| Netherlands  | 2        | 2.67%   |
| Indonesia    | 2        | 2.67%   |
| India        | 2        | 2.67%   |
| Germany      | 2        | 2.67%   |
| France       | 2        | 2.67%   |
| Sweden       | 1        | 1.33%   |
| Portugal     | 1        | 1.33%   |
| Poland       | 1        | 1.33%   |
| Norway       | 1        | 1.33%   |
| Mexico       | 1        | 1.33%   |
| Japan        | 1        | 1.33%   |
| Hong Kong    | 1        | 1.33%   |
| Finland      | 1        | 1.33%   |
| Czechia      | 1        | 1.33%   |
| Colombia     | 1        | 1.33%   |
| Brazil       | 1        | 1.33%   |
| Austria      | 1        | 1.33%   |
| Argentina    | 1        | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 3        | 3.95%   |
| Toronto                | 2        | 2.63%   |
| Melbourne              | 2        | 2.63%   |
| Haifa                  | 2        | 2.63%   |
| Buckley                | 2        | 2.63%   |
| Yogyakarta             | 1        | 1.32%   |
| Yekaterinburg          | 1        | 1.32%   |
| Willowbrook            | 1        | 1.32%   |
| Wells                  | 1        | 1.32%   |
| Washington             | 1        | 1.32%   |
| Waltham                | 1        | 1.32%   |
| Voronezh               | 1        | 1.32%   |
| Vienna                 | 1        | 1.32%   |
| Vancouver              | 1        | 1.32%   |
| Tlaxcala City          | 1        | 1.32%   |
| Thoothukudi            | 1        | 1.32%   |
| St. John's             | 1        | 1.32%   |
| St Petersburg          | 1        | 1.32%   |
| Springfield            | 1        | 1.32%   |
| Sobral de Monte Agraco | 1        | 1.32%   |
| Simi Valley            | 1        | 1.32%   |
| Semarang               | 1        | 1.32%   |
| Sao Jose do Rio Claro  | 1        | 1.32%   |
| Rotterdam              | 1        | 1.32%   |
| Rome                   | 1        | 1.32%   |
| Rehovot                | 1        | 1.32%   |
| Prague                 | 1        | 1.32%   |
| Paris                  | 1        | 1.32%   |
| Ōtsu                  | 1        | 1.32%   |
| Oslo                   | 1        | 1.32%   |
| Newmarket              | 1        | 1.32%   |
| Moscow                 | 1        | 1.32%   |
| Monza                  | 1        | 1.32%   |
| Milan                  | 1        | 1.32%   |
| Mequon                 | 1        | 1.32%   |
| McAllen                | 1        | 1.32%   |
| Lebanon                | 1        | 1.32%   |
| Krasnodar              | 1        | 1.32%   |
| Krakow                 | 1        | 1.32%   |
| Johannesburg           | 1        | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 23       | 47     | 18.7%   |
| WDC                         | 20       | 35     | 16.26%  |
| Samsung Electronics         | 18       | 32     | 14.63%  |
| Toshiba                     | 8        | 10     | 6.5%    |
| Hitachi                     | 8        | 13     | 6.5%    |
| Crucial                     | 6        | 7      | 4.88%   |
| SanDisk                     | 5        | 5      | 4.07%   |
| Intel                       | 4        | 7      | 3.25%   |
| Kingston                    | 3        | 3      | 2.44%   |
| HGST                        | 3        | 3      | 2.44%   |
| Unknown                     | 2        | 4      | 1.63%   |
| SK hynix                    | 2        | 2      | 1.63%   |
| Gigabyte Technology         | 2        | 2      | 1.63%   |
| China                       | 2        | 2      | 1.63%   |
| Team                        | 1        | 1      | 0.81%   |
| PNY                         | 1        | 1      | 0.81%   |
| Phison                      | 1        | 1      | 0.81%   |
| MyDigitalSSD                | 1        | 1      | 0.81%   |
| Mobius                      | 1        | 2      | 0.81%   |
| Micron/Crucial Technology   | 1        | 2      | 0.81%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.81%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.81%   |
| KIOXIA                      | 1        | 1      | 0.81%   |
| Kingston Technology Company | 1        | 1      | 0.81%   |
| GOODRAM                     | 1        | 1      | 0.81%   |
| DUEX-120GB                  | 1        | 1      | 0.81%   |
| Digma                       | 1        | 1      | 0.81%   |
| Corsair                     | 1        | 1      | 0.81%   |
| Apacer                      | 1        | 1      | 0.81%   |
| ADATA SU                    | 1        | 1      | 0.81%   |
| A-DATA Technology           | 1        | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                    | 4        | 2.76%   |
| WDC WD2002FAEX-007BA0 2TB                          | 2        | 1.38%   |
| Seagate ST4000DM004-2CV104 4TB                     | 2        | 1.38%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2        | 1.38%   |
| Samsung SSD 860 EVO 1TB                            | 2        | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2        | 1.38%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD               | 2        | 1.38%   |
| Crucial CT240BX500SSD1 240GB                       | 2        | 1.38%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD                   | 1        | 0.69%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                   | 1        | 0.69%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1        | 0.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1        | 0.69%   |
| WDC WDS100T1X0E-00AFY0 1TB                         | 1        | 0.69%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                     | 1        | 0.69%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 1        | 0.69%   |
| WDC WD5000AUDX-63WNHY0 500GB                       | 1        | 0.69%   |
| WDC WD5000AAKX-75U6AA0 500GB                       | 1        | 0.69%   |
| WDC WD5000AAKX-001CA0 500GB                        | 1        | 0.69%   |
| WDC WD40EZRZ-00WN9B0 4TB                           | 1        | 0.69%   |
| WDC WD30EZRX-00D8PB0 3TB                           | 1        | 0.69%   |
| WDC WD2500AAJS-22VTA0 250GB                        | 1        | 0.69%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1        | 0.69%   |
| WDC WD20EZRX-00DC0B0 2TB                           | 1        | 0.69%   |
| WDC WD20EZBX-00AYRA0 2TB                           | 1        | 0.69%   |
| WDC WD20EFZX-68AWUN0 2TB                           | 1        | 0.69%   |
| WDC WD2003FZEX-00SRLA0 2TB                         | 1        | 0.69%   |
| WDC WD10EZEX-75M2NA0 1TB                           | 1        | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 1        | 0.69%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 1        | 0.69%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 1        | 0.69%   |
| WDC WD1001FALS-00J7B1 1TB                          | 1        | 0.69%   |
| WDC WD1001FALS-00J7B0 1TB                          | 1        | 0.69%   |
| WDC WD Blue SA510 M.2 2280 1000GB SSD              | 1        | 0.69%   |
| Unknown SD/MMC/M.S.PRO 32GB                        | 1        | 0.69%   |
| Unknown SD/MMC 2GB                                 | 1        | 0.69%   |
| Unknown M.S./M.S.Pro/HG 16GB                       | 1        | 0.69%   |
| Unknown BFDT50S 500GB                              | 1        | 0.69%   |
| Toshiba THNSNJ128GCSU 128GB SSD                    | 1        | 0.69%   |
| Toshiba MQ01ABF050 500GB                           | 1        | 0.69%   |
| Toshiba MQ01ABD100 1TB                             | 1        | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 47     | 37.7%   |
| WDC                 | 16       | 26     | 26.23%  |
| Hitachi             | 8        | 13     | 13.11%  |
| Toshiba             | 7        | 9      | 11.48%  |
| Samsung Electronics | 3        | 4      | 4.92%   |
| HGST                | 2        | 2      | 3.28%   |
| Unknown             | 1        | 1      | 1.64%   |
| Mobius              | 1        | 2      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 11     | 17.95%  |
| WDC                 | 5        | 8      | 12.82%  |
| Crucial             | 5        | 6      | 12.82%  |
| SanDisk             | 4        | 4      | 10.26%  |
| Kingston            | 2        | 2      | 5.13%   |
| Gigabyte Technology | 2        | 2      | 5.13%   |
| China               | 2        | 2      | 5.13%   |
| Toshiba             | 1        | 1      | 2.56%   |
| Team                | 1        | 1      | 2.56%   |
| SK hynix            | 1        | 1      | 2.56%   |
| PNY                 | 1        | 1      | 2.56%   |
| MyDigitalSSD        | 1        | 1      | 2.56%   |
| Intel               | 1        | 1      | 2.56%   |
| GOODRAM             | 1        | 1      | 2.56%   |
| DUEX-120GB          | 1        | 1      | 2.56%   |
| Digma               | 1        | 1      | 2.56%   |
| Corsair             | 1        | 1      | 2.56%   |
| Apacer              | 1        | 1      | 2.56%   |
| ADATA SU            | 1        | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 45       | 104    | 42.06%  |
| SSD     | 35       | 47     | 32.71%  |
| NVMe    | 25       | 37     | 23.36%  |
| Unknown | 2        | 4      | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 64       | 145    | 68.82%  |
| NVMe | 25       | 37     | 26.88%  |
| SAS  | 4        | 10     | 4.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 65     | 46.59%  |
| 0.51-1.0   | 23       | 42     | 26.14%  |
| 1.01-2.0   | 13       | 24     | 14.77%  |
| 3.01-4.0   | 6        | 14     | 6.82%   |
| 2.01-3.0   | 2        | 2      | 2.27%   |
| 20.01-50.0 | 1        | 2      | 1.14%   |
| 10.01-20.0 | 1        | 1      | 1.14%   |
| 4.01-10.0  | 1        | 1      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 25.97%  |
| 1001-2000      | 15       | 19.48%  |
| 501-1000       | 13       | 16.88%  |
| 251-500        | 11       | 14.29%  |
| More than 3000 | 8        | 10.39%  |
| 2001-3000      | 3        | 3.9%    |
| Unknown        | 3        | 3.9%    |
| 1-20           | 2        | 2.6%    |
| 51-100         | 2        | 2.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 24       | 30.38%  |
| 21-50          | 16       | 20.25%  |
| 51-100         | 13       | 16.46%  |
| 501-1000       | 7        | 8.86%   |
| More than 3000 | 6        | 7.59%   |
| 251-500        | 4        | 5.06%   |
| 101-250        | 3        | 3.8%    |
| Unknown        | 3        | 3.8%    |
| 1001-2000      | 2        | 2.53%   |
| 2001-3000      | 1        | 1.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD40EZRZ-00WN9B0 4TB       | 1        | 1      | 7.69%   |
| WDC WD1001FALS-00J7B1 1TB      | 1        | 2      | 7.69%   |
| WDC WD1001FALS-00J7B0 1TB      | 1        | 4      | 7.69%   |
| Toshiba MK1059GSM 1TB          | 1        | 1      | 7.69%   |
| Seagate ST9500325AS 500GB      | 1        | 1      | 7.69%   |
| Seagate ST9320325AS 320GB      | 1        | 1      | 7.69%   |
| Seagate ST31000528AS 1TB       | 1        | 2      | 7.69%   |
| Intel SSD 600P Series 256GB    | 1        | 2      | 7.69%   |
| Hitachi HTS727575A9E364 752GB  | 1        | 1      | 7.69%   |
| Hitachi HDS725050KLA360 500GB  | 1        | 1      | 7.69%   |
| Hitachi HDS721010CLA632 1TB    | 1        | 1      | 7.69%   |
| Crucial CT1050MX300SSD1 1050GB | 1        | 1      | 7.69%   |
| Corsair Neutron SSD 64GB       | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 7      | 23.08%  |
| Seagate | 3        | 4      | 23.08%  |
| Hitachi | 3        | 3      | 23.08%  |
| Toshiba | 1        | 1      | 7.69%   |
| Intel   | 1        | 2      | 7.69%   |
| Crucial | 1        | 1      | 7.69%   |
| Corsair | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 7      | 30%     |
| Seagate | 3        | 4      | 30%     |
| Hitachi | 3        | 3      | 30%     |
| Toshiba | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 15     | 72.73%  |
| SSD  | 2        | 2      | 18.18%  |
| NVMe | 1        | 2      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST9500420AS 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 53       | 122    | 60.92%  |
| Detected | 23       | 50     | 26.44%  |
| Malfunc  | 10       | 19     | 11.49%  |
| Failed   | 1        | 1      | 1.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 49       | 44.14%  |
| AMD                         | 27       | 24.32%  |
| Samsung Electronics         | 10       | 9.01%   |
| ASMedia Technology          | 4        | 3.6%    |
| Broadcom / LSI              | 3        | 2.7%    |
| SanDisk                     | 2        | 1.8%    |
| Micron/Crucial Technology   | 2        | 1.8%    |
| LSI Logic / Symbios Logic   | 2        | 1.8%    |
| KIOXIA                      | 2        | 1.8%    |
| Kingston Technology Company | 2        | 1.8%    |
| VIA Technologies            | 1        | 0.9%    |
| SK hynix                    | 1        | 0.9%    |
| Realtek Semiconductor       | 1        | 0.9%    |
| Phison Electronics          | 1        | 0.9%    |
| MAXIO Technology (Hangzhou) | 1        | 0.9%    |
| Marvell Technology Group    | 1        | 0.9%    |
| JMicron Technology          | 1        | 0.9%    |
| Adaptec                     | 1        | 0.9%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 11.76%  |
| Intel SATA Controller [RAID mode]                                                       | 7        | 5.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 3.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 2.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 2.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 2.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.21%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.21%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.47%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 1.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.47%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.47%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.47%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 0.74%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.74%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.74%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.74%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.74%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.74%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 0.74%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.74%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                          | 1        | 0.74%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.74%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 1        | 0.74%   |
| KIOXIA NVMe SSD                                                                         | 1        | 0.74%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 0.74%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                                  | 1        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 58       | 50.43%  |
| NVMe | 25       | 21.74%  |
| IDE  | 15       | 13.04%  |
| RAID | 11       | 9.57%   |
| SAS  | 4        | 3.48%   |
| SCSI | 2        | 1.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 48       | 64%     |
| AMD    | 27       | 36%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 5.33%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 2.67%   |
| Intel 12th Gen Core i5-12400F               | 2        | 2.67%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 2.67%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.67%   |
| Intel Xeon E-2244G CPU @ 3.80GHz            | 1        | 1.33%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 1.33%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 1.33%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 1.33%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 1.33%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 1.33%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 1.33%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 1.33%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.33%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.33%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1        | 1.33%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.33%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1        | 1.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.33%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.33%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.33%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.33%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.33%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1        | 1.33%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.33%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.33%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 1.33%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 1        | 1.33%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.33%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.33%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.33%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1        | 1.33%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.33%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.33%   |
| Intel Celeron N5105 @ 2.00GHz               | 1        | 1.33%   |
| Intel Celeron N5095A @ 2.00GHz              | 1        | 1.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 14       | 18.67%  |
| Intel Core i5           | 9        | 12%     |
| Intel Xeon              | 8        | 10.67%  |
| Other                   | 6        | 8%      |
| AMD Ryzen 7             | 6        | 8%      |
| AMD Ryzen 9             | 5        | 6.67%   |
| Intel Core i3           | 4        | 5.33%   |
| Intel Celeron           | 4        | 5.33%   |
| AMD FX                  | 3        | 4%      |
| AMD Ryzen Threadripper  | 2        | 2.67%   |
| AMD Ryzen 5             | 2        | 2.67%   |
| Intel Pentium Dual-Core | 1        | 1.33%   |
| Intel Pentium Dual      | 1        | 1.33%   |
| Intel Core i9           | 1        | 1.33%   |
| Intel Core 2 Quad       | 1        | 1.33%   |
| AMD Sempron             | 1        | 1.33%   |
| AMD Ryzen Embedded      | 1        | 1.33%   |
| AMD Ryzen 7 PRO         | 1        | 1.33%   |
| AMD Ryzen 3             | 1        | 1.33%   |
| AMD Phenom II X6        | 1        | 1.33%   |
| AMD Athlon II X2        | 1        | 1.33%   |
| AMD A8                  | 1        | 1.33%   |
| AMD A4                  | 1        | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 27       | 36%     |
| 8      | 13       | 17.33%  |
| 6      | 13       | 17.33%  |
| 2      | 12       | 16%     |
| 12     | 5        | 6.67%   |
| 16     | 2        | 2.67%   |
| 24     | 1        | 1.33%   |
| 10     | 1        | 1.33%   |
| 3      | 1        | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 96%     |
| 2      | 3        | 4%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 53       | 70.67%  |
| 1      | 22       | 29.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 75       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 8        | 10.67%  |
| 0x306c3    | 5        | 6.67%   |
| 0x506e3    | 3        | 4%      |
| 0x306a9    | 3        | 4%      |
| 0x0a601203 | 3        | 4%      |
| 0xa0671    | 2        | 2.67%   |
| 0xa0655    | 2        | 2.67%   |
| 0xa0653    | 2        | 2.67%   |
| 0x906ea    | 2        | 2.67%   |
| 0x906c0    | 2        | 2.67%   |
| 0x90672    | 2        | 2.67%   |
| 0x306e4    | 2        | 2.67%   |
| 0x206c2    | 2        | 2.67%   |
| 0x08600106 | 2        | 2.67%   |
| 0x0800820d | 2        | 2.67%   |
| 0x06000852 | 2        | 2.67%   |
| Unknown    | 2        | 2.67%   |
| 0x906ed    | 1        | 1.33%   |
| 0x90675    | 1        | 1.33%   |
| 0x706a8    | 1        | 1.33%   |
| 0x6fd      | 1        | 1.33%   |
| 0x50654    | 1        | 1.33%   |
| 0x406f1    | 1        | 1.33%   |
| 0x40651    | 1        | 1.33%   |
| 0x306f2    | 1        | 1.33%   |
| 0x106e5    | 1        | 1.33%   |
| 0x10677    | 1        | 1.33%   |
| 0x10676    | 1        | 1.33%   |
| 0x0a404102 | 1        | 1.33%   |
| 0x0a20120a | 1        | 1.33%   |
| 0x0a201016 | 1        | 1.33%   |
| 0x0a201009 | 1        | 1.33%   |
| 0x08701021 | 1        | 1.33%   |
| 0x0870100a | 1        | 1.33%   |
| 0x0830104d | 1        | 1.33%   |
| 0x08301039 | 1        | 1.33%   |
| 0x08108109 | 1        | 1.33%   |
| 0x08101016 | 1        | 1.33%   |
| 0x08001138 | 1        | 1.33%   |
| 0x0700010f | 1        | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 9        | 12%     |
| Haswell          | 8        | 10.67%  |
| Zen 2            | 6        | 8%      |
| IvyBridge        | 5        | 6.67%   |
| Skylake          | 4        | 5.33%   |
| Piledriver       | 4        | 5.33%   |
| CometLake        | 4        | 5.33%   |
| Unknown          | 4        | 5.33%   |
| Zen+             | 3        | 4%      |
| Zen 3            | 3        | 4%      |
| KabyLake         | 3        | 4%      |
| K10              | 3        | 4%      |
| Alderlake Hybrid | 3        | 4%      |
| Zen              | 2        | 2.67%   |
| Westmere         | 2        | 2.67%   |
| Tremont          | 2        | 2.67%   |
| Penryn           | 2        | 2.67%   |
| Icelake          | 2        | 2.67%   |
| Nehalem          | 1        | 1.33%   |
| K10 Llano        | 1        | 1.33%   |
| Jaguar           | 1        | 1.33%   |
| Goldmont plus    | 1        | 1.33%   |
| Core             | 1        | 1.33%   |
| Broadwell        | 1        | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 32       | 39.02%  |
| Intel             | 28       | 34.15%  |
| AMD               | 21       | 25.61%  |
| ASPEED Technology | 1        | 1.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5.95%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 3.57%   |
| Intel HD Graphics 530                                                       | 3        | 3.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 3.57%   |
| AMD Raphael                                                                 | 3        | 3.57%   |
| Nvidia GP107GL [Quadro P400]                                                | 2        | 2.38%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 2.38%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 2.38%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 2.38%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 2.38%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 2.38%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2        | 2.38%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 2.38%   |
| Nvidia TU117GL [T600]                                                       | 1        | 1.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.19%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.19%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.19%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.19%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.19%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.19%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.19%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.19%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.19%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.19%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.19%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.19%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 1.19%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.19%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.19%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1        | 1.19%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.19%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.19%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 26       | 34.67%  |
| 1 x Intel       | 25       | 33.33%  |
| 1 x AMD         | 17       | 22.67%  |
| 2 x AMD         | 2        | 2.67%   |
| Intel + Nvidia  | 2        | 2.67%   |
| AMD + Nvidia    | 2        | 2.67%   |
| Nvidia + ASPEED | 1        | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 57       | 75%     |
| Proprietary | 13       | 17.11%  |
| Unknown     | 6        | 7.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 41.33%  |
| 1.01-2.0   | 12       | 16%     |
| 0.01-0.5   | 11       | 14.67%  |
| 0.51-1.0   | 8        | 10.67%  |
| 7.01-8.0   | 3        | 4%      |
| 8.01-16.0  | 3        | 4%      |
| 3.01-4.0   | 2        | 2.67%   |
| 2.01-3.0   | 2        | 2.67%   |
| 32.01-64.0 | 1        | 1.33%   |
| 5.01-6.0   | 1        | 1.33%   |
| 16.01-24.0 | 1        | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 15.94%  |
| Dell                 | 9        | 13.04%  |
| Goldstar             | 7        | 10.14%  |
| Acer                 | 7        | 10.14%  |
| Hewlett-Packard      | 6        | 8.7%    |
| Ancor Communications | 5        | 7.25%   |
| Philips              | 3        | 4.35%   |
| Iiyama               | 3        | 4.35%   |
| ViewSonic            | 2        | 2.9%    |
| Eizo                 | 2        | 2.9%    |
| BenQ                 | 2        | 2.9%    |
| Xiaomi               | 1        | 1.45%   |
| Sony                 | 1        | 1.45%   |
| SGT                  | 1        | 1.45%   |
| Sceptre Tech         | 1        | 1.45%   |
| OEM                  | 1        | 1.45%   |
| NEC Computers        | 1        | 1.45%   |
| Lenovo               | 1        | 1.45%   |
| HUAWEI               | 1        | 1.45%   |
| HCL                  | 1        | 1.45%   |
| ASUSTek Computer     | 1        | 1.45%   |
| Apple                | 1        | 1.45%   |
| AOC                  | 1        | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                     | 1        | 1.39%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch            | 1        | 1.39%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1        | 1.39%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1        | 1.39%   |
| SGT LC156LF1L_03 SGT1560 1920x1080 345x194mm 15.6-inch                | 1        | 1.39%   |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch        | 1        | 1.39%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 1        | 1.39%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM062E 1280x1024 376x301mm 19.0-inch  | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1        | 1.39%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch  | 1        | 1.39%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1        | 1.39%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1        | 1.39%   |
| Samsung Electronics LC32G5xT SAM7080 2560x1440 698x393mm 31.5-inch    | 1        | 1.39%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 1.39%   |
| Philips PHL 275E2F PHLC23A 2560x1440 600x340mm 27.2-inch              | 1        | 1.39%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 1.39%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1        | 1.39%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 1        | 1.39%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch         | 1        | 1.39%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                   | 1        | 1.39%   |
| Iiyama PL2530H IVM6133 1920x1080 540x300mm 24.3-inch                  | 1        | 1.39%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1        | 1.39%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1        | 1.39%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                   | 1        | 1.39%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch            | 1        | 1.39%   |
| Hewlett-Packard P27v G4 HPN36AF 1920x1080 598x336mm 27.0-inch         | 1        | 1.39%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1        | 1.39%   |
| Hewlett-Packard L1502 HWP2600 1024x768 304x228mm 15.0-inch            | 1        | 1.39%   |
| Hewlett-Packard E190i HWP3118 1280x1024 374x299mm 18.9-inch           | 1        | 1.39%   |
| Hewlett-Packard 2509 HWP283B 1920x1080 553x311mm 25.0-inch            | 1        | 1.39%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                   | 1        | 1.39%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                   | 1        | 1.39%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1        | 1.39%   |
| Goldstar ULTRAWIDE GSM76FD 2560x1080 531x298mm 24.0-inch              | 1        | 1.39%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 1        | 1.39%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 1.39%   |
| Goldstar HDR 5K GSM7720 3440x1440 800x330mm 34.1-inch                 | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 34.29%  |
| 1280x1024 (SXGA)   | 7        | 10%     |
| 3840x2160 (4K)     | 6        | 8.57%   |
| 2560x1440 (QHD)    | 6        | 8.57%   |
| 1920x1200 (WUXGA)  | 4        | 5.71%   |
| 1600x900 (HD+)     | 4        | 5.71%   |
| 3440x1440          | 3        | 4.29%   |
| 3840x1080          | 2        | 2.86%   |
| 2560x1080          | 2        | 2.86%   |
| 1920x540           | 2        | 2.86%   |
| 1680x1050 (WSXGA+) | 2        | 2.86%   |
| 1440x900 (WXGA+)   | 2        | 2.86%   |
| 1366x768 (WXGA)    | 2        | 2.86%   |
| 1024x768 (XGA)     | 2        | 2.86%   |
| 1280x768           | 1        | 1.43%   |
| Unknown            | 1        | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 17.39%  |
| 27      | 10       | 14.49%  |
| 34      | 6        | 8.7%    |
| 23      | 6        | 8.7%    |
| 19      | 6        | 8.7%    |
| 31      | 4        | 5.8%    |
| 20      | 4        | 5.8%    |
| 17      | 4        | 5.8%    |
| 65      | 2        | 2.9%    |
| 22      | 2        | 2.9%    |
| 21      | 2        | 2.9%    |
| 18      | 2        | 2.9%    |
| Unknown | 2        | 2.9%    |
| 84      | 1        | 1.45%   |
| 48      | 1        | 1.45%   |
| 40      | 1        | 1.45%   |
| 28      | 1        | 1.45%   |
| 25      | 1        | 1.45%   |
| 15      | 1        | 1.45%   |
| 14      | 1        | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 27       | 39.71%  |
| 401-500     | 14       | 20.59%  |
| 701-800     | 6        | 8.82%   |
| 601-700     | 5        | 7.35%   |
| 301-350     | 5        | 7.35%   |
| 351-400     | 3        | 4.41%   |
| 1001-1500   | 3        | 4.41%   |
| Unknown     | 2        | 2.94%   |
| 801-900     | 1        | 1.47%   |
| 201-300     | 1        | 1.47%   |
| 1501-2000   | 1        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 61.54%  |
| 5/4     | 7        | 10.77%  |
| 16/10   | 7        | 10.77%  |
| 21/9    | 5        | 7.69%   |
| 4/3     | 2        | 3.08%   |
| Unknown | 2        | 3.08%   |
| 32/9    | 1        | 1.54%   |
| 3/2     | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 26.47%  |
| 351-500        | 10       | 14.71%  |
| 301-350        | 10       | 14.71%  |
| 151-200        | 10       | 14.71%  |
| 141-150        | 6        | 8.82%   |
| 251-300        | 4        | 5.88%   |
| More than 1000 | 3        | 4.41%   |
| 501-1000       | 3        | 4.41%   |
| Unknown        | 2        | 2.94%   |
| 111-120        | 1        | 1.47%   |
| 101-110        | 1        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 52       | 77.61%  |
| 101-120 | 7        | 10.45%  |
| 121-160 | 3        | 4.48%   |
| 1-50    | 2        | 2.99%   |
| Unknown | 2        | 2.99%   |
| 161-240 | 1        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 73.33%  |
| 0     | 12       | 16%     |
| 2     | 8        | 10.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 45       | 42.06%  |
| Realtek Semiconductor     | 39       | 36.45%  |
| MediaTek                  | 5        | 4.67%   |
| Broadcom                  | 4        | 3.74%   |
| Ralink Technology         | 2        | 1.87%   |
| Qualcomm Atheros          | 2        | 1.87%   |
| Marvell Technology Group  | 2        | 1.87%   |
| Linksys                   | 2        | 1.87%   |
| TP-Link                   | 1        | 0.93%   |
| Spreadtrum Communications | 1        | 0.93%   |
| Solarflare Communications | 1        | 0.93%   |
| Microsoft                 | 1        | 0.93%   |
| BUFFALO                   | 1        | 0.93%   |
| Aquantia                  | 1        | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 26.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 5.79%   |
| Intel I211 Gigabit Network Connection                             | 5        | 4.13%   |
| Intel Ethernet Controller I225-V                                  | 5        | 4.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.48%   |
| Intel Wireless 3165                                               | 3        | 2.48%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.65%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 1.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.65%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.65%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.65%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.65%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 1.65%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.83%   |
| Spreadtrum meizu C9                                               | 1        | 0.83%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.83%   |
| Realtek 802.11ac NIC                                              | 1        | 0.83%   |
| Ralink RT3071 Wireless Adapter                                    | 1        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 0.83%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.83%   |
| MediaTek WiFi                                                     | 1        | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.83%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 0.83%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.83%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.83%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 0.83%   |
| Intel Wireless 7260                                               | 1        | 0.83%   |
| Intel WiMAX Connection 2400m                                      | 1        | 0.83%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 33.33%  |
| Realtek Semiconductor | 5        | 16.67%  |
| MediaTek              | 5        | 16.67%  |
| Ralink Technology     | 2        | 6.67%   |
| Qualcomm Atheros      | 2        | 6.67%   |
| Linksys               | 2        | 6.67%   |
| TP-Link               | 1        | 3.33%   |
| Microsoft             | 1        | 3.33%   |
| BUFFALO               | 1        | 3.33%   |
| Broadcom              | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                            | 3        | 9.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 6.25%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 6.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2        | 6.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2        | 6.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2        | 6.25%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 6.25%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 3.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 3.13%   |
| Realtek 802.11ac NIC                                           | 1        | 3.13%   |
| Ralink RT3071 Wireless Adapter                                 | 1        | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 3.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 3.13%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1        | 3.13%   |
| MediaTek WiFi                                                  | 1        | 3.13%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 3.13%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 3.13%   |
| Intel Wireless 7260                                            | 1        | 3.13%   |
| Intel Centrino Wireless-N 2230                                 | 1        | 3.13%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]           | 1        | 3.13%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]       | 1        | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 40       | 45.98%  |
| Realtek Semiconductor     | 38       | 43.68%  |
| Broadcom                  | 4        | 4.6%    |
| Marvell Technology Group  | 2        | 2.3%    |
| Spreadtrum Communications | 1        | 1.15%   |
| Solarflare Communications | 1        | 1.15%   |
| Aquantia                  | 1        | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 35.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 7.87%   |
| Intel I211 Gigabit Network Connection                             | 5        | 5.62%   |
| Intel Ethernet Controller I225-V                                  | 5        | 5.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.37%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.25%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 2.25%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 2.25%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 2.25%   |
| Spreadtrum meizu C9                                               | 1        | 1.12%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.12%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.12%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.12%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 1.12%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.12%   |
| Intel WiMAX Connection 2400m                                      | 1        | 1.12%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.12%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.12%   |
| Intel Ethernet Controller I226-V                                  | 1        | 1.12%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.12%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.12%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.12%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.12%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.12%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.12%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.12%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.12%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 73.27%  |
| WiFi     | 27       | 26.73%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 84.21%  |
| WiFi     | 12       | 15.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 55.26%  |
| 2     | 25       | 32.89%  |
| 3     | 6        | 7.89%   |
| 4     | 2        | 2.63%   |
| 5     | 1        | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 80%     |
| Yes  | 15       | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 9        | 40.91%  |
| MediaTek                   | 4        | 18.18%  |
| Cambridge Silicon Radio    | 4        | 18.18%  |
| Realtek Semiconductor      | 1        | 4.55%   |
| Integrated System Solution | 1        | 4.55%   |
| IMC Networks               | 1        | 4.55%   |
| Foxconn / Hon Hai          | 1        | 4.55%   |
| Broadcom                   | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                              | 4        | 18.18%  |
| Intel Bluetooth wireless interface                    | 4        | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4        | 18.18%  |
| Intel AX210 Bluetooth                                 | 2        | 9.09%   |
| Intel AX200 Bluetooth                                 | 2        | 9.09%   |
| Realtek Bluetooth Radio                               | 1        | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 4.55%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 4.55%   |
| IMC Networks Bluetooth Device                         | 1        | 4.55%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 46       | 38.33%  |
| Nvidia              | 31       | 25.83%  |
| AMD                 | 29       | 24.17%  |
| C-Media Electronics | 3        | 2.5%    |
| Logitech            | 2        | 1.67%   |
| ASUSTek Computer    | 2        | 1.67%   |
| Texas Instruments   | 1        | 0.83%   |
| Setek Elektronik    | 1        | 0.83%   |
| Nektar              | 1        | 0.83%   |
| KTMicro             | 1        | 0.83%   |
| GYROCOM C&C         | 1        | 0.83%   |
| Creative Technology | 1        | 0.83%   |
| Creative Labs       | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9        | 6.52%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 5.07%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 4.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 3.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 3.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 3.62%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4        | 2.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 4        | 2.9%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 2.17%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 2.17%   |
| Intel Alder Lake-S HD Audio Controller                                            | 3        | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.45%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2        | 1.45%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.45%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 1.45%   |
| Intel Jasper Lake HD Audio                                                        | 2        | 1.45%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 1.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 1.45%   |
| C-Media Electronics TONOR TC30 Audio Device                                       | 2        | 1.45%   |
| ASUSTek Computer USB Audio                                                        | 2        | 1.45%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2        | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 1.45%   |
| AMD FCH Azalia Controller                                                         | 2        | 1.45%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.45%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.72%   |
| Setek Elektronik Realtek USB Audio Rear                                           | 1        | 0.72%   |
| Setek Elektronik Realtek USB Audio Front                                          | 1        | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia High Definition Audio Controller                                           | 1        | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 0.72%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.72%   |
| Nvidia GM200 High Definition Audio                                                | 1        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 9        | 14.06%  |
| Corsair             | 9        | 14.06%  |
| Unknown             | 8        | 12.5%   |
| Micron Technology   | 7        | 10.94%  |
| Kingston            | 7        | 10.94%  |
| G.Skill             | 7        | 10.94%  |
| SK hynix            | 3        | 4.69%   |
| Crucial             | 3        | 4.69%   |
| Unknown             | 2        | 3.13%   |
| Team                | 1        | 1.56%   |
| PNY                 | 1        | 1.56%   |
| Patriot             | 1        | 1.56%   |
| Nanya Technology    | 1        | 1.56%   |
| HPE                 | 1        | 1.56%   |
| Gold Key            | 1        | 1.56%   |
| Elpida              | 1        | 1.56%   |
| CUSO                | 1        | 1.56%   |
| A-DATA Technology   | 1        | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 2        | 2.99%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s               | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 1.49%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 1.49%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s              | 1        | 1.49%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s    | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s      | 1        | 1.49%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 1.49%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.49%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s    | 1        | 1.49%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 1.49%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s  | 1        | 1.49%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 1.49%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s     | 1        | 1.49%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s   | 1        | 1.49%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s  | 1        | 1.49%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 1.49%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3200MT/s    | 1        | 1.49%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s    | 1        | 1.49%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s    | 1        | 1.49%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s        | 1        | 1.49%   |
| Nanya RAM NT8GC72B4NB1NK-CG 8GB DIMM DDR3 1333MT/s      | 1        | 1.49%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 1.49%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 1.49%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s     | 1        | 1.49%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s      | 1        | 1.49%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s   | 1        | 1.49%   |
| Micron RAM 36KSZF1G72PZ-1G4D1 8GB DIMM DDR3 1333MT/s    | 1        | 1.49%   |
| Micron RAM 16ATF4G64AZ-2G6E1 32GB DIMM DDR4 2667MT/s    | 1        | 1.49%   |
| Kingston RAM KHX1866C9D3/4 4GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s     | 1        | 1.49%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 1        | 1.49%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s | 1        | 1.49%   |
| Kingston RAM 9965745-028.A00G 16GB DIMM DDR4 2667MT/s   | 1        | 1.49%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 1.49%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 54.72%  |
| DDR3    | 18       | 33.96%  |
| DDR5    | 3        | 5.66%   |
| DDR2    | 2        | 3.77%   |
| Unknown | 1        | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 44       | 83.02%  |
| SODIMM | 8        | 15.09%  |
| RIMM   | 1        | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 29.31%  |
| 16384 | 13       | 22.41%  |
| 4096  | 12       | 20.69%  |
| 32768 | 9        | 15.52%  |
| 2048  | 4        | 6.9%    |
| 1024  | 3        | 5.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 10       | 16.67%  |
| 2667  | 9        | 15%     |
| 1333  | 7        | 11.67%  |
| 1600  | 6        | 10%     |
| 2400  | 4        | 6.67%   |
| 2133  | 4        | 6.67%   |
| 4800  | 2        | 3.33%   |
| 3600  | 2        | 3.33%   |
| 3534  | 2        | 3.33%   |
| 2666  | 2        | 3.33%   |
| 667   | 2        | 3.33%   |
| 5600  | 1        | 1.67%   |
| 3733  | 1        | 1.67%   |
| 3666  | 1        | 1.67%   |
| 3100  | 1        | 1.67%   |
| 3000  | 1        | 1.67%   |
| 2800  | 1        | 1.67%   |
| 2200  | 1        | 1.67%   |
| 2048  | 1        | 1.67%   |
| 1866  | 1        | 1.67%   |
| 1800  | 1        | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson XP-4100 Series    | 1        | 33.33%  |
| Seiko Epson Printer           | 1        | 33.33%  |
| Brother HL-2030 Laser Printer | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| HP ScanJet 82x0C  | 1        | 50%     |
| HP OfficeJet 6110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 2        | 18.18%  |
| Logitech                      | 2        | 18.18%  |
| HD 2MP WEBCAM                 | 2        | 18.18%  |
| MacroSilicon                  | 1        | 9.09%   |
| KYE Systems (Mouse Systems)   | 1        | 9.09%   |
| Huawei Technologies           | 1        | 9.09%   |
| Generalplus Technology        | 1        | 9.09%   |
| Elgato Systems                | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| HD 2MP WEBCAM HD 2MP WEBCAM                | 2        | 18.18%  |
| Sunplus Full HD webcam                     | 1        | 9.09%   |
| Sunplus AUSDOM FHD Camera                  | 1        | 9.09%   |
| MacroSilicon USB Video                     | 1        | 9.09%   |
| Logitech Webcam C270                       | 1        | 9.09%   |
| Logitech HD Pro Webcam C920                | 1        | 9.09%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 9.09%   |
| Huawei UVC Camera                          | 1        | 9.09%   |
| Generalplus GENERAL WEBCAM                 | 1        | 9.09%   |
| Elgato Systems Elgato Facecam              | 1        | 9.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

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
| 0     | 53       | 69.74%  |
| 1     | 17       | 22.37%  |
| 2     | 5        | 6.58%   |
| 3     | 1        | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Graphics card       | 8        | 29.63%  |
| Net/wireless        | 6        | 22.22%  |
| Unassigned class    | 3        | 11.11%  |
| Sound               | 2        | 7.41%   |
| Firewire controller | 2        | 7.41%   |
| Storage/raid        | 1        | 3.7%    |
| Storage/ide         | 1        | 3.7%    |
| Storage             | 1        | 3.7%    |
| Net/ethernet        | 1        | 3.7%    |
| Fingerprint reader  | 1        | 3.7%    |
| Dvb card            | 1        | 3.7%    |


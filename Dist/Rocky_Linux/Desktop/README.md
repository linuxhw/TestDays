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

Total: 93

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Google        | Panther                     | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
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
| Rocky Linux 9.1 | 17       | 24.29%  |
| Rocky Linux 8.5 | 12       | 17.14%  |
| Rocky Linux 8.4 | 9        | 12.86%  |
| Rocky Linux 8.6 | 8        | 11.43%  |
| Rocky Linux 9.0 | 7        | 10%     |
| Rocky Linux 8.7 | 7        | 10%     |
| Rocky Linux 9.2 | 5        | 7.14%   |
| Rocky Linux 8.8 | 4        | 5.71%   |
| Rocky Linux 8.3 | 1        | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 69       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 6        | 8.22%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 6        | 8.22%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 4        | 5.48%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 3        | 4.11%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 3        | 4.11%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 3        | 4.11%   |
| 4.18.0-425.19.2.el8_7.x86_64     | 3        | 4.11%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3        | 4.11%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 3        | 4.11%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 2        | 2.74%   |
| 4.18.0-477.21.1.el8_8.x86_64     | 2        | 2.74%   |
| 4.18.0-477.15.1.el8_8.x86_64     | 2        | 2.74%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 2        | 2.74%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 2        | 2.74%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 2        | 2.74%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2        | 2.74%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2        | 2.74%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2        | 2.74%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2        | 2.74%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2        | 2.74%   |
| 6.1.8-1.el9.elrepo.x86_64        | 1        | 1.37%   |
| 6.1.6-1.el8.elrepo.x86_64        | 1        | 1.37%   |
| 6.0.10_tkg_bmq                   | 1        | 1.37%   |
| 6.0.10-1.el9.elrepo.x86_64       | 1        | 1.37%   |
| 5.14.1-1.el8.elrepo.x86_64       | 1        | 1.37%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 1        | 1.37%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 1        | 1.37%   |
| 5.14.0-284.25.1.el9_2.x86_64     | 1        | 1.37%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 1        | 1.37%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 1        | 1.37%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 1        | 1.37%   |
| 4.18.0-425.3.1.el8.x86_64        | 1        | 1.37%   |
| 4.18.0-372.9.1.el8.x86_64        | 1        | 1.37%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 1        | 1.37%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 1        | 1.37%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 1        | 1.37%   |
| 4.18.0-240.22.1.el8.x86_64       | 1        | 1.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 39       | 55.71%  |
| 5.14.0  | 26       | 37.14%  |
| 6.0.10  | 2        | 2.86%   |
| 6.1.8   | 1        | 1.43%   |
| 6.1.6   | 1        | 1.43%   |
| 5.14.1  | 1        | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 39       | 55.71%  |
| 5.14    | 27       | 38.57%  |
| 6.1     | 2        | 2.86%   |
| 6.0     | 2        | 2.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 69       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 42       | 60.87%  |
| Unknown       | 13       | 18.84%  |
| KDE5          | 7        | 10.14%  |
| GNOME Classic | 4        | 5.8%    |
| MATE          | 2        | 2.9%    |
| XFCE          | 1        | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 32       | 44.44%  |
| X11     | 28       | 38.89%  |
| Unknown | 6        | 8.33%   |
| Tty     | 4        | 5.56%   |
| Web     | 2        | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 46.38%  |
| GDM     | 30       | 43.48%  |
| SDDM    | 5        | 7.25%   |
| LightDM | 2        | 2.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 40       | 57.97%  |
| ru_RU   | 4        | 5.8%    |
| en_IL   | 3        | 4.35%   |
| en_CA   | 3        | 4.35%   |
| en_SG   | 2        | 2.9%    |
| en_GB   | 2        | 2.9%    |
| en_AU   | 2        | 2.9%    |
| C       | 2        | 2.9%    |
| Unknown | 2        | 2.9%    |
| pt_BR   | 1        | 1.45%   |
| pl_PL   | 1        | 1.45%   |
| ko_KR   | 1        | 1.45%   |
| ja_JP   | 1        | 1.45%   |
| es_CO   | 1        | 1.45%   |
| es_AR   | 1        | 1.45%   |
| en_ZA   | 1        | 1.45%   |
| en_IN   | 1        | 1.45%   |
| af_ZA   | 1        | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 38       | 54.29%  |
| BIOS | 32       | 45.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 57       | 82.61%  |
| Ext4 | 12       | 17.39%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 38       | 55.07%  |
| Unknown | 18       | 26.09%  |
| MBR     | 13       | 18.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 76.81%  |
| Yes       | 16       | 23.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 89.86%  |
| Yes       | 7        | 10.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 24.64%  |
| Dell                | 12       | 17.39%  |
| MSI                 | 8        | 11.59%  |
| Gigabyte Technology | 8        | 11.59%  |
| Hewlett-Packard     | 5        | 7.25%   |
| ASRock              | 4        | 5.8%    |
| Lenovo              | 3        | 4.35%   |
| AZW                 | 3        | 4.35%   |
| Unknown             | 2        | 2.9%    |
| Techvision          | 1        | 1.45%   |
| Sapphire            | 1        | 1.45%   |
| NCR                 | 1        | 1.45%   |
| Intel               | 1        | 1.45%   |
| HPE                 | 1        | 1.45%   |
| Google              | 1        | 1.45%   |
| BESSTAR Tech        | 1        | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 9020                  | 2        | 2.9%    |
| Unknown                             | 2        | 2.9%    |
| Techvision TVI7309X                 | 1        | 1.45%   |
| Sapphire PE-AM2RS690V2              | 1        | 1.45%   |
| NCR xxxx-xxxx-xxxx                  | 1        | 1.45%   |
| MSI MS-7D78                         | 1        | 1.45%   |
| MSI MS-7D46                         | 1        | 1.45%   |
| MSI MS-7D25                         | 1        | 1.45%   |
| MSI MS-7B89                         | 1        | 1.45%   |
| MSI MS-7B78                         | 1        | 1.45%   |
| MSI MS-7A94                         | 1        | 1.45%   |
| MSI MS-7917                         | 1        | 1.45%   |
| MSI H510M PRO-E                     | 1        | 1.45%   |
| Lenovo ThinkStation P620 30E0S0PR00 | 1        | 1.45%   |
| Lenovo ThinkStation P340 30DK000CUS | 1        | 1.45%   |
| Lenovo ThinkCentre M72e 36601Y8     | 1        | 1.45%   |
| Intel PRO412081                     | 1        | 1.45%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 1.45%   |
| HP Z800 Workstation                 | 1        | 1.45%   |
| HP Z600 Workstation                 | 1        | 1.45%   |
| HP Z210 Workstation                 | 1        | 1.45%   |
| HP ProDesk 600 G2 SFF               | 1        | 1.45%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.45%   |
| Google Panther                      | 1        | 1.45%   |
| Gigabyte X570 AORUS ULTRA           | 1        | 1.45%   |
| Gigabyte H87-D3H                    | 1        | 1.45%   |
| Gigabyte H81M-S2PV                  | 1        | 1.45%   |
| Gigabyte H61M-DS2                   | 1        | 1.45%   |
| Gigabyte G41MT-USB3                 | 1        | 1.45%   |
| Gigabyte EUROLINUX_V1               | 1        | 1.45%   |
| Gigabyte 970A-UD3P                  | 1        | 1.45%   |
| Gigabyte 970A-DS3P                  | 1        | 1.45%   |
| Dell XPS 8300                       | 1        | 1.45%   |
| Dell Vostro 430                     | 1        | 1.45%   |
| Dell Vostro 3681                    | 1        | 1.45%   |
| Dell Precision Tower 7810           | 1        | 1.45%   |
| Dell Precision T7610                | 1        | 1.45%   |
| Dell Precision T5610                | 1        | 1.45%   |
| Dell Precision T3600                | 1        | 1.45%   |
| Dell OptiPlex 990                   | 1        | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 9        | 13.04%  |
| Dell OptiPlex          | 5        | 7.25%   |
| Dell Precision         | 4        | 5.8%    |
| Lenovo ThinkStation    | 2        | 2.9%    |
| Dell Vostro            | 2        | 2.9%    |
| Unknown                | 2        | 2.9%    |
| Techvision TVI7309X    | 1        | 1.45%   |
| Sapphire PE-AM2RS690V2 | 1        | 1.45%   |
| NCR xxxx-xxxx-xxxx     | 1        | 1.45%   |
| MSI MS-7D78            | 1        | 1.45%   |
| MSI MS-7D46            | 1        | 1.45%   |
| MSI MS-7D25            | 1        | 1.45%   |
| MSI MS-7B89            | 1        | 1.45%   |
| MSI MS-7B78            | 1        | 1.45%   |
| MSI MS-7A94            | 1        | 1.45%   |
| MSI MS-7917            | 1        | 1.45%   |
| MSI H510M              | 1        | 1.45%   |
| Lenovo ThinkCentre     | 1        | 1.45%   |
| Intel PRO412081        | 1        | 1.45%   |
| HPE ProLiant           | 1        | 1.45%   |
| HP Z800                | 1        | 1.45%   |
| HP Z600                | 1        | 1.45%   |
| HP Z210                | 1        | 1.45%   |
| HP ProDesk             | 1        | 1.45%   |
| HP EliteDesk           | 1        | 1.45%   |
| Google Panther         | 1        | 1.45%   |
| Gigabyte X570          | 1        | 1.45%   |
| Gigabyte H87-D3H       | 1        | 1.45%   |
| Gigabyte H81M-S2PV     | 1        | 1.45%   |
| Gigabyte H61M-DS2      | 1        | 1.45%   |
| Gigabyte G41MT-USB3    | 1        | 1.45%   |
| Gigabyte EUROLINUX     | 1        | 1.45%   |
| Gigabyte 970A-UD3P     | 1        | 1.45%   |
| Gigabyte 970A-DS3P     | 1        | 1.45%   |
| Dell XPS               | 1        | 1.45%   |
| BESSTAR Tech HM90      | 1        | 1.45%   |
| AZW MINI               | 1        | 1.45%   |
| AZW GTR                | 1        | 1.45%   |
| AZW Gemini             | 1        | 1.45%   |
| ASUS ROG               | 1        | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 9        | 13.04%  |
| 2011 | 9        | 13.04%  |
| 2020 | 7        | 10.14%  |
| 2013 | 7        | 10.14%  |
| 2022 | 6        | 8.7%    |
| 2018 | 6        | 8.7%    |
| 2015 | 5        | 7.25%   |
| 2014 | 5        | 7.25%   |
| 2012 | 4        | 5.8%    |
| 2019 | 3        | 4.35%   |
| 2008 | 3        | 4.35%   |
| 2010 | 2        | 2.9%    |
| 2023 | 1        | 1.45%   |
| 2017 | 1        | 1.45%   |
| 2009 | 1        | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 69       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 65       | 94.2%   |
| Enabled  | 4        | 5.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 98.55%  |
| Yes  | 1        | 1.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 15       | 21.43%  |
| 4.01-8.0    | 12       | 17.14%  |
| 8.01-16.0   | 12       | 17.14%  |
| 16.01-24.0  | 11       | 15.71%  |
| 64.01-256.0 | 10       | 14.29%  |
| 3.01-4.0    | 4        | 5.71%   |
| 1.01-2.0    | 3        | 4.29%   |
| 24.01-32.0  | 2        | 2.86%   |
| 2.01-3.0    | 1        | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 20       | 27.78%  |
| 3.01-4.0   | 15       | 20.83%  |
| 4.01-8.0   | 14       | 19.44%  |
| 1.01-2.0   | 10       | 13.89%  |
| 0.51-1.0   | 4        | 5.56%   |
| 8.01-16.0  | 3        | 4.17%   |
| 32.01-64.0 | 2        | 2.78%   |
| 16.01-24.0 | 2        | 2.78%   |
| 0.01-0.5   | 2        | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 44.29%  |
| 2      | 15       | 21.43%  |
| 4      | 10       | 14.29%  |
| 3      | 8        | 11.43%  |
| 6      | 2        | 2.86%   |
| 5      | 2        | 2.86%   |
| 9      | 1        | 1.43%   |
| 8      | 1        | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 60.87%  |
| Yes       | 27       | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 98.55%  |
| No        | 1        | 1.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 67.14%  |
| Yes       | 23       | 32.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 72.86%  |
| Yes       | 19       | 27.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 19       | 27.54%  |
| Russia       | 5        | 7.25%   |
| Canada       | 5        | 7.25%   |
| Singapore    | 3        | 4.35%   |
| Italy        | 3        | 4.35%   |
| Israel       | 3        | 4.35%   |
| Australia    | 3        | 4.35%   |
| UK           | 2        | 2.9%    |
| South Korea  | 2        | 2.9%    |
| South Africa | 2        | 2.9%    |
| Netherlands  | 2        | 2.9%    |
| Indonesia    | 2        | 2.9%    |
| India        | 2        | 2.9%    |
| Germany      | 2        | 2.9%    |
| France       | 2        | 2.9%    |
| Sweden       | 1        | 1.45%   |
| Portugal     | 1        | 1.45%   |
| Poland       | 1        | 1.45%   |
| Norway       | 1        | 1.45%   |
| Mexico       | 1        | 1.45%   |
| Japan        | 1        | 1.45%   |
| Finland      | 1        | 1.45%   |
| Czechia      | 1        | 1.45%   |
| Colombia     | 1        | 1.45%   |
| Brazil       | 1        | 1.45%   |
| Austria      | 1        | 1.45%   |
| Argentina    | 1        | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 3        | 4.29%   |
| Toronto                | 2        | 2.86%   |
| Melbourne              | 2        | 2.86%   |
| Haifa                  | 2        | 2.86%   |
| Buckley                | 2        | 2.86%   |
| Yogyakarta             | 1        | 1.43%   |
| Yekaterinburg          | 1        | 1.43%   |
| Willowbrook            | 1        | 1.43%   |
| Wells                  | 1        | 1.43%   |
| Washington             | 1        | 1.43%   |
| Waltham                | 1        | 1.43%   |
| Voronezh               | 1        | 1.43%   |
| Vienna                 | 1        | 1.43%   |
| Vancouver              | 1        | 1.43%   |
| Tlaxcala City          | 1        | 1.43%   |
| Thoothukudi            | 1        | 1.43%   |
| St. John's             | 1        | 1.43%   |
| St Petersburg          | 1        | 1.43%   |
| Sobral de Monte Agraco | 1        | 1.43%   |
| Semarang               | 1        | 1.43%   |
| Sao Jose do Rio Claro  | 1        | 1.43%   |
| Rotterdam              | 1        | 1.43%   |
| Rome                   | 1        | 1.43%   |
| Rehovot                | 1        | 1.43%   |
| Prague                 | 1        | 1.43%   |
| Paris                  | 1        | 1.43%   |
| Ōtsu                  | 1        | 1.43%   |
| Oslo                   | 1        | 1.43%   |
| Moscow                 | 1        | 1.43%   |
| Monza                  | 1        | 1.43%   |
| Milan                  | 1        | 1.43%   |
| Mequon                 | 1        | 1.43%   |
| McAllen                | 1        | 1.43%   |
| Lebanon                | 1        | 1.43%   |
| Krasnodar              | 1        | 1.43%   |
| Krakow                 | 1        | 1.43%   |
| Johannesburg           | 1        | 1.43%   |
| Jamestown              | 1        | 1.43%   |
| Imphal                 | 1        | 1.43%   |
| Helsinki               | 1        | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 23       | 47     | 20.18%  |
| WDC                         | 19       | 34     | 16.67%  |
| Samsung Electronics         | 17       | 31     | 14.91%  |
| Hitachi                     | 8        | 13     | 7.02%   |
| Toshiba                     | 7        | 9      | 6.14%   |
| Crucial                     | 6        | 7      | 5.26%   |
| SanDisk                     | 3        | 3      | 2.63%   |
| Kingston                    | 3        | 3      | 2.63%   |
| Intel                       | 3        | 3      | 2.63%   |
| HGST                        | 3        | 3      | 2.63%   |
| SK hynix                    | 2        | 2      | 1.75%   |
| Gigabyte Technology         | 2        | 2      | 1.75%   |
| China                       | 2        | 2      | 1.75%   |
| Unknown                     | 1        | 1      | 0.88%   |
| Team                        | 1        | 1      | 0.88%   |
| PNY                         | 1        | 1      | 0.88%   |
| Phison                      | 1        | 1      | 0.88%   |
| MyDigitalSSD                | 1        | 1      | 0.88%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.88%   |
| KIOXIA-EXCERIA              | 1        | 1      | 0.88%   |
| KIOXIA                      | 1        | 1      | 0.88%   |
| Kingston Technology Company | 1        | 1      | 0.88%   |
| GOODRAM                     | 1        | 1      | 0.88%   |
| DUEX-120GB                  | 1        | 1      | 0.88%   |
| Digma                       | 1        | 1      | 0.88%   |
| Corsair                     | 1        | 1      | 0.88%   |
| Apacer                      | 1        | 1      | 0.88%   |
| ADATA SU                    | 1        | 1      | 0.88%   |
| A-DATA Technology           | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 4        | 3.01%   |
| WDC WD2002FAEX-007BA0 2TB                             | 2        | 1.5%    |
| Seagate ST4000DM004-2CV104 4TB                        | 2        | 1.5%    |
| Seagate ST1000DM010-2EP102 1TB                        | 2        | 1.5%    |
| Samsung SSD 860 EVO 1TB                               | 2        | 1.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 2        | 1.5%    |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD                  | 2        | 1.5%    |
| Crucial CT240BX500SSD1 240GB                          | 2        | 1.5%    |
| WDC WDS500G1R0A-68A4W0 500GB SSD                      | 1        | 0.75%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                      | 1        | 0.75%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 1        | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1        | 0.75%   |
| WDC WDS100T1X0E-00AFY0 1TB                            | 1        | 0.75%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                        | 1        | 0.75%   |
| WDC WD5000LPCX-24VHAT0 500GB                          | 1        | 0.75%   |
| WDC WD5000AUDX-63WNHY0 500GB                          | 1        | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB                          | 1        | 0.75%   |
| WDC WD5000AAKX-001CA0 500GB                           | 1        | 0.75%   |
| WDC WD40EZRZ-00WN9B0 4TB                              | 1        | 0.75%   |
| WDC WD30EZRX-00D8PB0 3TB                              | 1        | 0.75%   |
| WDC WD2500AAJS-22VTA0 250GB                           | 1        | 0.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 1        | 0.75%   |
| WDC WD20EZRX-00DC0B0 2TB                              | 1        | 0.75%   |
| WDC WD20EZBX-00AYRA0 2TB                              | 1        | 0.75%   |
| WDC WD20EFZX-68AWUN0 2TB                              | 1        | 0.75%   |
| WDC WD10EZEX-75M2NA0 1TB                              | 1        | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 1        | 0.75%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 1        | 0.75%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 1        | 0.75%   |
| WDC WD1001FALS-00J7B1 1TB                             | 1        | 0.75%   |
| WDC WD1001FALS-00J7B0 1TB                             | 1        | 0.75%   |
| WDC WD Blue SA510 M.2 2280 1000GB                     | 1        | 0.75%   |
| Unknown BFDT50S 500GB                                 | 1        | 0.75%   |
| Toshiba THNSNJ128GCSU 128GB SSD                       | 1        | 0.75%   |
| Toshiba MQ01ABD100 1TB                                | 1        | 0.75%   |
| Toshiba MK1059GSM 1TB                                 | 1        | 0.75%   |
| Toshiba MG07ACA12TE 12TB                              | 1        | 0.75%   |
| Toshiba MG04ACA400E 4TB                               | 1        | 0.75%   |
| Toshiba DT01ACA100 1TB                                | 1        | 0.75%   |
| Toshiba DT01ACA050 500GB                              | 1        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 47     | 39.66%  |
| WDC                 | 15       | 25     | 25.86%  |
| Hitachi             | 8        | 13     | 13.79%  |
| Toshiba             | 6        | 8      | 10.34%  |
| Samsung Electronics | 3        | 4      | 5.17%   |
| HGST                | 2        | 2      | 3.45%   |
| Unknown             | 1        | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 11     | 18.42%  |
| WDC                 | 5        | 8      | 13.16%  |
| Crucial             | 5        | 6      | 13.16%  |
| SanDisk             | 3        | 3      | 7.89%   |
| Kingston            | 2        | 2      | 5.26%   |
| Gigabyte Technology | 2        | 2      | 5.26%   |
| China               | 2        | 2      | 5.26%   |
| Toshiba             | 1        | 1      | 2.63%   |
| Team                | 1        | 1      | 2.63%   |
| SK hynix            | 1        | 1      | 2.63%   |
| PNY                 | 1        | 1      | 2.63%   |
| MyDigitalSSD        | 1        | 1      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| GOODRAM             | 1        | 1      | 2.63%   |
| DUEX-120GB          | 1        | 1      | 2.63%   |
| Digma               | 1        | 1      | 2.63%   |
| Corsair             | 1        | 1      | 2.63%   |
| Apacer              | 1        | 1      | 2.63%   |
| ADATA SU            | 1        | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 42       | 100    | 42.86%  |
| SSD     | 34       | 46     | 34.69%  |
| NVMe    | 21       | 29     | 21.43%  |
| Unknown | 1        | 1      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 60       | 140    | 71.43%  |
| NVMe | 21       | 29     | 25%     |
| SAS  | 3        | 7      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 63     | 46.43%  |
| 0.51-1.0   | 23       | 42     | 27.38%  |
| 1.01-2.0   | 12       | 23     | 14.29%  |
| 3.01-4.0   | 6        | 14     | 7.14%   |
| 2.01-3.0   | 2        | 2      | 2.38%   |
| 10.01-20.0 | 1        | 1      | 1.19%   |
| 4.01-10.0  | 1        | 1      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 17       | 23.94%  |
| 1001-2000      | 14       | 19.72%  |
| 501-1000       | 13       | 18.31%  |
| 251-500        | 10       | 14.08%  |
| More than 3000 | 7        | 9.86%   |
| 2001-3000      | 3        | 4.23%   |
| Unknown        | 3        | 4.23%   |
| 1-20           | 2        | 2.82%   |
| 51-100         | 2        | 2.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 29.17%  |
| 21-50          | 15       | 20.83%  |
| 51-100         | 11       | 15.28%  |
| 501-1000       | 7        | 9.72%   |
| More than 3000 | 5        | 6.94%   |
| 251-500        | 4        | 5.56%   |
| 101-250        | 3        | 4.17%   |
| Unknown        | 3        | 4.17%   |
| 1001-2000      | 2        | 2.78%   |
| 2001-3000      | 1        | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD40EZRZ-00WN9B0 4TB      | 1        | 1      | 8.33%   |
| WDC WD1001FALS-00J7B1 1TB     | 1        | 2      | 8.33%   |
| WDC WD1001FALS-00J7B0 1TB     | 1        | 4      | 8.33%   |
| Toshiba MK1059GSM 1TB         | 1        | 1      | 8.33%   |
| Seagate ST9500325AS 500GB     | 1        | 1      | 8.33%   |
| Seagate ST9320325AS 320GB     | 1        | 1      | 8.33%   |
| Seagate ST31000528AS 1TB      | 1        | 2      | 8.33%   |
| Hitachi HTS727575A9E364 752GB | 1        | 1      | 8.33%   |
| Hitachi HDS725050KLA360 500GB | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA632 1TB   | 1        | 1      | 8.33%   |
| Crucial CT1050MX300SSD1 1TB   | 1        | 1      | 8.33%   |
| Corsair Neutron SSD 64GB      | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 7      | 25%     |
| Seagate | 3        | 4      | 25%     |
| Hitachi | 3        | 3      | 25%     |
| Toshiba | 1        | 1      | 8.33%   |
| Crucial | 1        | 1      | 8.33%   |
| Corsair | 1        | 1      | 8.33%   |

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
| HDD  | 8        | 15     | 80%     |
| SSD  | 2        | 2      | 20%     |

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
| Works    | 49       | 114    | 61.25%  |
| Detected | 21       | 44     | 26.25%  |
| Malfunc  | 9        | 17     | 11.25%  |
| Failed   | 1        | 1      | 1.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 45       | 45%     |
| AMD                         | 24       | 24%     |
| Samsung Electronics         | 9        | 9%      |
| ASMedia Technology          | 4        | 4%      |
| LSI Logic / Symbios Logic   | 2        | 2%      |
| KIOXIA                      | 2        | 2%      |
| Kingston Technology Company | 2        | 2%      |
| Broadcom / LSI              | 2        | 2%      |
| VIA Technologies            | 1        | 1%      |
| SK hynix                    | 1        | 1%      |
| SanDisk                     | 1        | 1%      |
| Realtek Semiconductor       | 1        | 1%      |
| Phison Electronics          | 1        | 1%      |
| Micron/Crucial Technology   | 1        | 1%      |
| MAXIO Technology (Hangzhou) | 1        | 1%      |
| Marvell Technology Group    | 1        | 1%      |
| JMicron Technology          | 1        | 1%      |
| Adaptec                     | 1        | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 10.66%  |
| Intel SATA Controller [RAID mode]                                                       | 7        | 5.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 3.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 2.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 2.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.64%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 1.64%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.64%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.64%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.64%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.64%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.64%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.82%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.82%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.82%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.82%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 0.82%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 0.82%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.82%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                          | 1        | 0.82%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 1        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 1        | 0.82%   |
| KIOXIA NVMe SSD                                                                         | 1        | 0.82%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 0.82%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 0.82%   |
| JMicron JMB58x AHCI SATA controller                                                     | 1        | 0.82%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 1        | 0.82%   |
| Intel PCIe Data Center SSD                                                              | 1        | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 53       | 50.96%  |
| NVMe | 21       | 20.19%  |
| IDE  | 14       | 13.46%  |
| RAID | 10       | 9.62%   |
| SAS  | 4        | 3.85%   |
| SCSI | 2        | 1.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 45       | 65.22%  |
| AMD    | 24       | 34.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 5.8%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 2.9%    |
| Intel 12th Gen Core i5-12400F               | 2        | 2.9%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 2.9%    |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.9%    |
| Intel Xeon E-2244G CPU @ 3.80GHz            | 1        | 1.45%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 1.45%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 1.45%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 1.45%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 1.45%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 1.45%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 1.45%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 1.45%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.45%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1        | 1.45%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1        | 1.45%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.45%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.45%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.45%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.45%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.45%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.45%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 1        | 1.45%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 1        | 1.45%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.45%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.45%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.45%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1        | 1.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.45%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.45%   |
| Intel Celeron N5105 @ 2.00GHz               | 1        | 1.45%   |
| Intel Celeron N5095A @ 2.00GHz              | 1        | 1.45%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.45%   |
| Intel Celeron 2955U @ 1.40GHz               | 1        | 1.45%   |
| Intel 12th Gen Core i5-12400                | 1        | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 13       | 18.84%  |
| Intel Core i5           | 8        | 11.59%  |
| Intel Xeon              | 7        | 10.14%  |
| Other                   | 6        | 8.7%    |
| AMD Ryzen 7             | 5        | 7.25%   |
| Intel Core i3           | 4        | 5.8%    |
| Intel Celeron           | 4        | 5.8%    |
| AMD Ryzen 9             | 4        | 5.8%    |
| AMD FX                  | 3        | 4.35%   |
| AMD Ryzen Threadripper  | 2        | 2.9%    |
| AMD Ryzen 5             | 2        | 2.9%    |
| Intel Pentium Dual-Core | 1        | 1.45%   |
| Intel Pentium Dual      | 1        | 1.45%   |
| Intel Core i9           | 1        | 1.45%   |
| Intel Core 2 Quad       | 1        | 1.45%   |
| AMD Sempron             | 1        | 1.45%   |
| AMD Ryzen Embedded      | 1        | 1.45%   |
| AMD Ryzen 7 PRO         | 1        | 1.45%   |
| AMD Ryzen 3             | 1        | 1.45%   |
| AMD Phenom II X6        | 1        | 1.45%   |
| AMD Athlon II X2        | 1        | 1.45%   |
| AMD A4                  | 1        | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 25       | 36.23%  |
| 8      | 12       | 17.39%  |
| 6      | 12       | 17.39%  |
| 2      | 11       | 15.94%  |
| 12     | 4        | 5.8%    |
| 16     | 2        | 2.9%    |
| 24     | 1        | 1.45%   |
| 10     | 1        | 1.45%   |
| 3      | 1        | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 95.65%  |
| 2      | 3        | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 48       | 69.57%  |
| 1      | 21       | 30.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 69       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 7        | 10.14%  |
| 0x306c3    | 5        | 7.25%   |
| 0x306a9    | 3        | 4.35%   |
| 0xa0671    | 2        | 2.9%    |
| 0xa0655    | 2        | 2.9%    |
| 0xa0653    | 2        | 2.9%    |
| 0x906c0    | 2        | 2.9%    |
| 0x90672    | 2        | 2.9%    |
| 0x506e3    | 2        | 2.9%    |
| 0x306e4    | 2        | 2.9%    |
| 0x206c2    | 2        | 2.9%    |
| 0x0a601203 | 2        | 2.9%    |
| 0x08600106 | 2        | 2.9%    |
| 0x0800820d | 2        | 2.9%    |
| 0x06000852 | 2        | 2.9%    |
| Unknown    | 2        | 2.9%    |
| 0x906ed    | 1        | 1.45%   |
| 0x906ea    | 1        | 1.45%   |
| 0x90675    | 1        | 1.45%   |
| 0x706a8    | 1        | 1.45%   |
| 0x6fd      | 1        | 1.45%   |
| 0x50654    | 1        | 1.45%   |
| 0x406f1    | 1        | 1.45%   |
| 0x40651    | 1        | 1.45%   |
| 0x306f2    | 1        | 1.45%   |
| 0x106e5    | 1        | 1.45%   |
| 0x10677    | 1        | 1.45%   |
| 0x10676    | 1        | 1.45%   |
| 0x0a404102 | 1        | 1.45%   |
| 0x0a20120a | 1        | 1.45%   |
| 0x0a201016 | 1        | 1.45%   |
| 0x0a201009 | 1        | 1.45%   |
| 0x0870100a | 1        | 1.45%   |
| 0x0830104d | 1        | 1.45%   |
| 0x08301039 | 1        | 1.45%   |
| 0x08108109 | 1        | 1.45%   |
| 0x08101016 | 1        | 1.45%   |
| 0x08001138 | 1        | 1.45%   |
| 0x0700010f | 1        | 1.45%   |
| 0x06000822 | 1        | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 8        | 11.59%  |
| Haswell          | 8        | 11.59%  |
| Zen 2            | 5        | 7.25%   |
| IvyBridge        | 5        | 7.25%   |
| CometLake        | 4        | 5.8%    |
| Zen+             | 3        | 4.35%   |
| Zen 3            | 3        | 4.35%   |
| Skylake          | 3        | 4.35%   |
| Piledriver       | 3        | 4.35%   |
| K10              | 3        | 4.35%   |
| Alderlake Hybrid | 3        | 4.35%   |
| Unknown          | 3        | 4.35%   |
| Zen              | 2        | 2.9%    |
| Westmere         | 2        | 2.9%    |
| Tremont          | 2        | 2.9%    |
| Penryn           | 2        | 2.9%    |
| KabyLake         | 2        | 2.9%    |
| Icelake          | 2        | 2.9%    |
| Nehalem          | 1        | 1.45%   |
| K10 Llano        | 1        | 1.45%   |
| Jaguar           | 1        | 1.45%   |
| Goldmont plus    | 1        | 1.45%   |
| Core             | 1        | 1.45%   |
| Broadwell        | 1        | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 30       | 39.47%  |
| Intel             | 26       | 34.21%  |
| AMD               | 19       | 25%     |
| ASPEED Technology | 1        | 1.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 6.41%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 3.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 3.85%   |
| Nvidia GP107GL [Quadro P400]                                                | 2        | 2.56%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 2.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 2.56%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 2.56%   |
| Intel HD Graphics 530                                                       | 2        | 2.56%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 2.56%   |
| AMD Renoir                                                                  | 2        | 2.56%   |
| AMD Raphael                                                                 | 2        | 2.56%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 2.56%   |
| Nvidia TU117GL [T600]                                                       | 1        | 1.28%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.28%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.28%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.28%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.28%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.28%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.28%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.28%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.28%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.28%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 1.28%   |
| Nvidia GK107 [NVS 510]                                                      | 1        | 1.28%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.28%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 1.28%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.28%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 1.28%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.28%   |
| Nvidia GA102GL [RTX A6000]                                                  | 1        | 1.28%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.28%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.28%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.28%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 24       | 34.78%  |
| 1 x Intel       | 23       | 33.33%  |
| 1 x AMD         | 15       | 21.74%  |
| 2 x AMD         | 2        | 2.9%    |
| Intel + Nvidia  | 2        | 2.9%    |
| AMD + Nvidia    | 2        | 2.9%    |
| Nvidia + ASPEED | 1        | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 51       | 73.91%  |
| Proprietary | 12       | 17.39%  |
| Unknown     | 6        | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 42.03%  |
| 1.01-2.0   | 12       | 17.39%  |
| 0.01-0.5   | 10       | 14.49%  |
| 0.51-1.0   | 7        | 10.14%  |
| 7.01-8.0   | 3        | 4.35%   |
| 3.01-4.0   | 2        | 2.9%    |
| 8.01-16.0  | 2        | 2.9%    |
| 32.01-64.0 | 1        | 1.45%   |
| 5.01-6.0   | 1        | 1.45%   |
| 2.01-3.0   | 1        | 1.45%   |
| 16.01-24.0 | 1        | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 9        | 14.29%  |
| Dell                 | 8        | 12.7%   |
| Acer                 | 7        | 11.11%  |
| Goldstar             | 6        | 9.52%   |
| Hewlett-Packard      | 5        | 7.94%   |
| Ancor Communications | 5        | 7.94%   |
| Philips              | 3        | 4.76%   |
| Iiyama               | 3        | 4.76%   |
| ViewSonic            | 2        | 3.17%   |
| BenQ                 | 2        | 3.17%   |
| Xiaomi               | 1        | 1.59%   |
| Sony                 | 1        | 1.59%   |
| SGT                  | 1        | 1.59%   |
| Sceptre Tech         | 1        | 1.59%   |
| OEM                  | 1        | 1.59%   |
| NEC Computers        | 1        | 1.59%   |
| Lenovo               | 1        | 1.59%   |
| HUAWEI               | 1        | 1.59%   |
| HCL                  | 1        | 1.59%   |
| Eizo                 | 1        | 1.59%   |
| ASUSTek Computer     | 1        | 1.59%   |
| Apple                | 1        | 1.59%   |
| AOC                  | 1        | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                     | 1        | 1.54%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch            | 1        | 1.54%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1        | 1.54%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1        | 1.54%   |
| SGT LC156LF1L_03 SGT1560 1920x1080 345x194mm 15.6-inch                | 1        | 1.54%   |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch        | 1        | 1.54%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 1        | 1.54%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1        | 1.54%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1        | 1.54%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1        | 1.54%   |
| Samsung Electronics LF27T35 SAM7080 1920x1080 598x337mm 27.0-inch     | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1        | 1.54%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 1.54%   |
| Philips PHL 275E2F PHLC23A 2560x1440 600x340mm 27.2-inch              | 1        | 1.54%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 1.54%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1        | 1.54%   |
| OEM 24W_LCD_TV OEM3700 1920x1080                                      | 1        | 1.54%   |
| NEC Computers LCD1760NX NEC6604 1280x1024 338x270mm 17.0-inch         | 1        | 1.54%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                   | 1        | 1.54%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 1        | 1.54%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                  | 1        | 1.54%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 1        | 1.54%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                   | 1        | 1.54%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch            | 1        | 1.54%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch          | 1        | 1.54%   |
| Hewlett-Packard L1502 HWP2600 1024x768 304x228mm 15.0-inch            | 1        | 1.54%   |
| Hewlett-Packard E190i HWP3118 1280x1024 380x300mm 19.1-inch           | 1        | 1.54%   |
| Hewlett-Packard 2509 HWP283B 1920x1080 553x311mm 25.0-inch            | 1        | 1.54%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                   | 1        | 1.54%   |
| Goldstar WFHD GSM7748 2560x1080 798x334mm 34.1-inch                   | 1        | 1.54%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1        | 1.54%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 1        | 1.54%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 1.54%   |
| Goldstar HDR 5K GSM7720 3440x1440 800x330mm 34.1-inch                 | 1        | 1.54%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 1        | 1.54%   |
| Goldstar E2060 GSM4EBF 1600x900 443x249mm 20.0-inch                   | 1        | 1.54%   |
| Eizo CG247X ENC2801 1920x1200 520x330mm 24.2-inch                     | 1        | 1.54%   |
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                   | 1        | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 32.81%  |
| 3840x2160 (4K)     | 6        | 9.38%   |
| 2560x1440 (QHD)    | 6        | 9.38%   |
| 1280x1024 (SXGA)   | 6        | 9.38%   |
| 1920x1200 (WUXGA)  | 4        | 6.25%   |
| 1600x900 (HD+)     | 4        | 6.25%   |
| 3440x1440          | 3        | 4.69%   |
| 3840x1080          | 2        | 3.13%   |
| 1920x540           | 2        | 3.13%   |
| 1680x1050 (WSXGA+) | 2        | 3.13%   |
| 1440x900 (WXGA+)   | 2        | 3.13%   |
| 1366x768 (WXGA)    | 2        | 3.13%   |
| 2560x1080          | 1        | 1.56%   |
| 1280x768           | 1        | 1.56%   |
| 1024x768 (XGA)     | 1        | 1.56%   |
| Unknown            | 1        | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 11       | 17.74%  |
| 27      | 9        | 14.52%  |
| 34      | 5        | 8.06%   |
| 23      | 5        | 8.06%   |
| 19      | 5        | 8.06%   |
| 31      | 4        | 6.45%   |
| 20      | 4        | 6.45%   |
| 17      | 4        | 6.45%   |
| 65      | 2        | 3.23%   |
| 22      | 2        | 3.23%   |
| 21      | 2        | 3.23%   |
| 18      | 2        | 3.23%   |
| 84      | 1        | 1.61%   |
| 48      | 1        | 1.61%   |
| 40      | 1        | 1.61%   |
| 28      | 1        | 1.61%   |
| 25      | 1        | 1.61%   |
| 15      | 1        | 1.61%   |
| Unknown | 1        | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 39.34%  |
| 401-500     | 14       | 22.95%  |
| 701-800     | 5        | 8.2%    |
| 601-700     | 5        | 8.2%    |
| 301-350     | 5        | 8.2%    |
| 1001-1500   | 3        | 4.92%   |
| 351-400     | 2        | 3.28%   |
| 801-900     | 1        | 1.64%   |
| 1501-2000   | 1        | 1.64%   |
| Unknown     | 1        | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 37       | 63.79%  |
| 16/10   | 7        | 12.07%  |
| 5/4     | 6        | 10.34%  |
| 21/9    | 4        | 6.9%    |
| 4/3     | 1        | 1.72%   |
| 32/9    | 1        | 1.72%   |
| 3/2     | 1        | 1.72%   |
| Unknown | 1        | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 26.23%  |
| 351-500        | 9        | 14.75%  |
| 301-350        | 9        | 14.75%  |
| 151-200        | 9        | 14.75%  |
| 141-150        | 6        | 9.84%   |
| 251-300        | 4        | 6.56%   |
| More than 1000 | 3        | 4.92%   |
| 501-1000       | 3        | 4.92%   |
| 111-120        | 1        | 1.64%   |
| Unknown        | 1        | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 76.67%  |
| 101-120 | 7        | 11.67%  |
| 121-160 | 3        | 5%      |
| 1-50    | 2        | 3.33%   |
| 161-240 | 1        | 1.67%   |
| Unknown | 1        | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 71.01%  |
| 0     | 12       | 17.39%  |
| 2     | 8        | 11.59%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 40       | 40.82%  |
| Realtek Semiconductor     | 36       | 36.73%  |
| MediaTek                  | 4        | 4.08%   |
| Broadcom                  | 4        | 4.08%   |
| Ralink Technology         | 2        | 2.04%   |
| Qualcomm Atheros          | 2        | 2.04%   |
| Marvell Technology Group  | 2        | 2.04%   |
| Linksys                   | 2        | 2.04%   |
| TP-Link                   | 1        | 1.02%   |
| Spreadtrum Communications | 1        | 1.02%   |
| Solarflare Communications | 1        | 1.02%   |
| Microsoft                 | 1        | 1.02%   |
| BUFFALO                   | 1        | 1.02%   |
| Aquantia                  | 1        | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 26.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 5.5%    |
| Intel I211 Gigabit Network Connection                             | 4        | 3.67%   |
| Intel Ethernet Controller I225-V                                  | 4        | 3.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.75%   |
| Intel Wireless 3165                                               | 3        | 2.75%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.83%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 1.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 1.83%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.83%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.83%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.83%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.83%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 1.83%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 0.92%   |
| Spreadtrum Spreadtrum Phone                                       | 1        | 0.92%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.92%   |
| Realtek 802.11ac NIC                                              | 1        | 0.92%   |
| Ralink RT3071 Wireless Adapter                                    | 1        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 0.92%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.92%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 0.92%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.92%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.92%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 0.92%   |
| Intel Wireless 7260                                               | 1        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.92%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.92%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.92%   |
| Intel Ethernet Controller I226-V                                  | 1        | 0.92%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 30.77%  |
| Realtek Semiconductor | 4        | 15.38%  |
| MediaTek              | 4        | 15.38%  |
| Ralink Technology     | 2        | 7.69%   |
| Qualcomm Atheros      | 2        | 7.69%   |
| Linksys               | 2        | 7.69%   |
| TP-Link               | 1        | 3.85%   |
| Microsoft             | 1        | 3.85%   |
| BUFFALO               | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                            | 3        | 10.71%  |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2        | 7.14%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 7.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2        | 7.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2        | 7.14%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 7.14%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 1        | 3.57%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 3.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 3.57%   |
| Realtek 802.11ac NIC                                           | 1        | 3.57%   |
| Ralink RT3071 Wireless Adapter                                 | 1        | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 3.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 3.57%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1        | 3.57%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter            | 1        | 3.57%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 3.57%   |
| Intel Wireless 7260                                            | 1        | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 3.57%   |
| Intel Centrino Wireless-N 2230                                 | 1        | 3.57%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]       | 1        | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 35       | 44.3%   |
| Intel                     | 35       | 44.3%   |
| Broadcom                  | 4        | 5.06%   |
| Marvell Technology Group  | 2        | 2.53%   |
| Spreadtrum Communications | 1        | 1.27%   |
| Solarflare Communications | 1        | 1.27%   |
| Aquantia                  | 1        | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 35.8%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 7.41%   |
| Intel I211 Gigabit Network Connection                             | 4        | 4.94%   |
| Intel Ethernet Controller I225-V                                  | 4        | 4.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.47%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 2.47%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 2.47%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 2.47%   |
| Spreadtrum Spreadtrum Phone                                       | 1        | 1.23%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 1.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.23%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.23%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 1.23%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.23%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.23%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.23%   |
| Intel Ethernet Controller I226-V                                  | 1        | 1.23%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.23%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.23%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.23%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.23%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.23%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 74.73%  |
| WiFi     | 23       | 25.27%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 59       | 85.51%  |
| WiFi     | 10       | 14.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 56.52%  |
| 2     | 23       | 33.33%  |
| 3     | 4        | 5.8%    |
| 4     | 2        | 2.9%    |
| 5     | 1        | 1.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 79.71%  |
| Yes  | 14       | 20.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 8        | 42.11%  |
| MediaTek                   | 4        | 21.05%  |
| Cambridge Silicon Radio    | 4        | 21.05%  |
| Integrated System Solution | 1        | 5.26%   |
| IMC Networks               | 1        | 5.26%   |
| Broadcom                   | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                              | 4        | 21.05%  |
| Intel Bluetooth wireless interface                    | 4        | 21.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4        | 21.05%  |
| Intel AX200 Bluetooth                                 | 2        | 10.53%  |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 5.26%   |
| Intel AX210 Bluetooth                                 | 1        | 5.26%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 5.26%   |
| IMC Networks Bluetooth Device                         | 1        | 5.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 43       | 39.09%  |
| Nvidia              | 29       | 26.36%  |
| AMD                 | 26       | 23.64%  |
| C-Media Electronics | 3        | 2.73%   |
| Texas Instruments   | 1        | 0.91%   |
| Setek Elektronik    | 1        | 0.91%   |
| Nektar              | 1        | 0.91%   |
| Logitech            | 1        | 0.91%   |
| KTMicro             | 1        | 0.91%   |
| GYROCOM C&C         | 1        | 0.91%   |
| Creative Technology | 1        | 0.91%   |
| Creative Labs       | 1        | 0.91%   |
| ASUSTek Computer    | 1        | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 6.3%    |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 5.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 3.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 3.94%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 3.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 3.94%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 3.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4        | 3.15%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 2.36%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 2.36%   |
| Intel Alder Lake-S HD Audio Controller                                            | 3        | 2.36%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.36%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 3        | 2.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 2.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.57%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.57%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 1.57%   |
| Intel Jasper Lake HD Audio                                                        | 2        | 1.57%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 1.57%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 1.57%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 1.57%   |
| C-Media Electronics USB PnP Audio Device                                          | 2        | 1.57%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 2        | 1.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 1.57%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.57%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.79%   |
| Setek Elektronik Realtek USB Audio Rear                                           | 1        | 0.79%   |
| Setek Elektronik Realtek USB Audio Front                                          | 1        | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.79%   |
| Nvidia High Definition Audio Controller                                           | 1        | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.79%   |
| Nvidia GM200 High Definition Audio                                                | 1        | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 0.79%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 9        | 15%     |
| Unknown             | 8        | 13.33%  |
| Corsair             | 8        | 13.33%  |
| Kingston            | 7        | 11.67%  |
| G.Skill             | 7        | 11.67%  |
| Micron Technology   | 6        | 10%     |
| SK hynix            | 3        | 5%      |
| Crucial             | 3        | 5%      |
| Unknown             | 2        | 3.33%   |
| Team                | 1        | 1.67%   |
| PNY                 | 1        | 1.67%   |
| Patriot             | 1        | 1.67%   |
| Nanya Technology    | 1        | 1.67%   |
| HPE                 | 1        | 1.67%   |
| Gold Key            | 1        | 1.67%   |
| A-DATA Technology   | 1        | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 2        | 3.17%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s               | 1        | 1.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 1.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 1.59%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s          | 1        | 1.59%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 1.59%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 1.59%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s              | 1        | 1.59%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s    | 1        | 1.59%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s     | 1        | 1.59%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 1.59%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.59%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s    | 1        | 1.59%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 1.59%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s  | 1        | 1.59%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 1.59%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s     | 1        | 1.59%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s   | 1        | 1.59%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 1        | 1.59%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s    | 1        | 1.59%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3200MT/s    | 1        | 1.59%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s    | 1        | 1.59%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s    | 1        | 1.59%   |
| Patriot RAM 1333EL Series 8GB DIMM DDR3 1333MT/s        | 1        | 1.59%   |
| Nanya RAM NT8GC72B4NB1NK-CG 8GB DIMM DDR3 1333MT/s      | 1        | 1.59%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                | 1        | 1.59%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 1.59%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s     | 1        | 1.59%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s      | 1        | 1.59%   |
| Micron RAM 36KSZF1G72PZ-1G4D1 8GB DIMM DDR3 1333MT/s    | 1        | 1.59%   |
| Micron RAM 16ATF4G64AZ-2G6E1 32GB DIMM DDR4 2667MT/s    | 1        | 1.59%   |
| Kingston RAM KHX1866C9D3/4 4GB DIMM DDR3 1600MT/s       | 1        | 1.59%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s     | 1        | 1.59%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 1        | 1.59%   |
| Kingston RAM CBD32D4S2S8MF-16 16GB SODIMM DDR4 3200MT/s | 1        | 1.59%   |
| Kingston RAM 9965745-028.A00G 16GB DIMM DDR4 2666MT/s   | 1        | 1.59%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 1.59%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s   | 1        | 1.59%   |
| Kingston RAM 9905402-670.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 27       | 55.1%   |
| DDR3    | 17       | 34.69%  |
| DDR5    | 2        | 4.08%   |
| DDR2    | 2        | 4.08%   |
| Unknown | 1        | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 41       | 83.67%  |
| SODIMM | 7        | 14.29%  |
| RIMM   | 1        | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 31.48%  |
| 16384 | 11       | 20.37%  |
| 4096  | 10       | 18.52%  |
| 32768 | 9        | 16.67%  |
| 2048  | 4        | 7.41%   |
| 1024  | 3        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 10       | 17.86%  |
| 2667  | 7        | 12.5%   |
| 1333  | 7        | 12.5%   |
| 1600  | 5        | 8.93%   |
| 2400  | 4        | 7.14%   |
| 2133  | 4        | 7.14%   |
| 3600  | 2        | 3.57%   |
| 3534  | 2        | 3.57%   |
| 2666  | 2        | 3.57%   |
| 667   | 2        | 3.57%   |
| 5600  | 1        | 1.79%   |
| 4800  | 1        | 1.79%   |
| 3733  | 1        | 1.79%   |
| 3666  | 1        | 1.79%   |
| 3100  | 1        | 1.79%   |
| 3000  | 1        | 1.79%   |
| 2800  | 1        | 1.79%   |
| 2200  | 1        | 1.79%   |
| 2048  | 1        | 1.79%   |
| 1866  | 1        | 1.79%   |
| 1800  | 1        | 1.79%   |

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
| Logitech                      | 2        | 22.22%  |
| 2M UVC CAMERA                 | 2        | 22.22%  |
| Sunplus Innovation Technology | 1        | 11.11%  |
| KYE Systems (Mouse Systems)   | 1        | 11.11%  |
| Huawei Technologies           | 1        | 11.11%  |
| Generalplus Technology        | 1        | 11.11%  |
| Elgato Systems                | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| 2M UVC CAMERA Web Camera                  | 2        | 22.22%  |
| Sunplus Canyon CNS-CWC5 Webcam            | 1        | 11.11%  |
| Logitech Webcam C270                      | 1        | 11.11%  |
| Logitech HD Pro Webcam C920               | 1        | 11.11%  |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 11.11%  |
| Huawei HiCamera                           | 1        | 11.11%  |
| Generalplus CAMERA - UVC                  | 1        | 11.11%  |
| Elgato Systems Elgato Facecam             | 1        | 11.11%  |

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
| 0     | 47       | 68.12%  |
| 1     | 16       | 23.19%  |
| 2     | 5        | 7.25%   |
| 3     | 1        | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Graphics card       | 8        | 30.77%  |
| Net/wireless        | 6        | 23.08%  |
| Unassigned class    | 2        | 7.69%   |
| Sound               | 2        | 7.69%   |
| Firewire controller | 2        | 7.69%   |
| Storage/raid        | 1        | 3.85%   |
| Storage/ide         | 1        | 3.85%   |
| Storage             | 1        | 3.85%   |
| Net/ethernet        | 1        | 3.85%   |
| Fingerprint reader  | 1        | 3.85%   |
| Dvb card            | 1        | 3.85%   |


Solus 4.3 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Solus_4.3/Desktop/README.md) and [notebooks](/Dist/Solus_4.3/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 92

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Modern 14 B5M               | Notebook    | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [ef34a2a126](https://linux-hardware.org/?probe=ef34a2a126) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [12b14f3cbc](https://linux-hardware.org/?probe=12b14f3cbc) | Nov 06, 2022 |
| Quanta        | TWS                         | Notebook    | [a800f54191](https://linux-hardware.org/?probe=a800f54191) | Nov 06, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [087a173c0d](https://linux-hardware.org/?probe=087a173c0d) | Oct 08, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| Unknown       | TB-4000                     | Desktop     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Unknown       | TB-4000                     | Desktop     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Dell          | Latitude E5470              | Notebook    | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [9e0bbc26f4](https://linux-hardware.org/?probe=9e0bbc26f4) | Jul 22, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| AZW           | SEi                         | Notebook    | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [d0c0f4f120](https://linux-hardware.org/?probe=d0c0f4f120) | Jul 06, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [9d0dd21c70](https://linux-hardware.org/?probe=9d0dd21c70) | Jul 06, 2022 |
| Lenovo        | CRESCENTBAY 31900058 STD    | Desktop     | [f42a689093](https://linux-hardware.org/?probe=f42a689093) | Jun 10, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| Google        | Edgar                       | Notebook    | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [037b7180fd](https://linux-hardware.org/?probe=037b7180fd) | Apr 23, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [8e0d54760d](https://linux-hardware.org/?probe=8e0d54760d) | Apr 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [68eec83e55](https://linux-hardware.org/?probe=68eec83e55) | Apr 15, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [e60647876c](https://linux-hardware.org/?probe=e60647876c) | Apr 13, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| Unknown       | HX90                        | Desktop     | [ab8a381a52](https://linux-hardware.org/?probe=ab8a381a52) | Apr 08, 2022 |
| Unknown       | HX90                        | Desktop     | [a83217f763](https://linux-hardware.org/?probe=a83217f763) | Apr 07, 2022 |
| Unknown       | HX90                        | Desktop     | [fa9981d1bd](https://linux-hardware.org/?probe=fa9981d1bd) | Apr 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google        | Delbin                      | Notebook    | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [fb6f0426c3](https://linux-hardware.org/?probe=fb6f0426c3) | Jan 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba       | TECRA R840                  | Notebook    | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [315e535dd5](https://linux-hardware.org/?probe=315e535dd5) | Dec 21, 2021 |
| Sony          | VPCYB15AB                   | Notebook    | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d65256bf72](https://linux-hardware.org/?probe=d65256bf72) | Dec 12, 2021 |
| Dell          | Latitude 5580               | Notebook    | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| Framework     | Laptop                      | Notebook    | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| Dell          | Latitude E6220              | Notebook    | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| Framework     | Laptop                      | Notebook    | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| HP            | 805F                        | Desktop     | [f7bfb95642](https://linux-hardware.org/?probe=f7bfb95642) | Oct 26, 2021 |
| LattePanda    | Alpha                       | Desktop     | [cfe529288b](https://linux-hardware.org/?probe=cfe529288b) | Oct 26, 2021 |
| Biostar       | H61MLV2                     | Desktop     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| AZW           | SEi                         | Notebook    | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [99c69c213a](https://linux-hardware.org/?probe=99c69c213a) | Sep 05, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f7d38e2f91](https://linux-hardware.org/?probe=f7d38e2f91) | Aug 29, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| eMachines     | EL1852G                     | Desktop     | [7683cbf5bb](https://linux-hardware.org/?probe=7683cbf5bb) | Aug 16, 2021 |
| eMachines     | EL1852G                     | Desktop     | [86003fc5b7](https://linux-hardware.org/?probe=86003fc5b7) | Aug 15, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [14f7d2a3c6](https://linux-hardware.org/?probe=14f7d2a3c6) | Aug 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [488ebb20fc](https://linux-hardware.org/?probe=488ebb20fc) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b6ae0cb479](https://linux-hardware.org/?probe=b6ae0cb479) | Aug 05, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [fc89bec579](https://linux-hardware.org/?probe=fc89bec579) | Jul 16, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |
| Lenovo        | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.15.32-213.current | 8         | 12.7%   |
| 5.14.21-210.current | 7         | 11.11%  |
| 5.15.50-216.current | 6         | 9.52%   |
| 5.14.16-205.current | 6         | 9.52%   |
| 5.13.1-187.current  | 6         | 9.52%   |
| 5.13.6-190.current  | 5         | 7.94%   |
| 5.13.12-193.current | 5         | 7.94%   |
| 5.15.77-219.current | 3         | 4.76%   |
| 5.15.43-215.current | 2         | 3.17%   |
| 5.15.30-212.current | 2         | 3.17%   |
| 5.15.26-211.current | 2         | 3.17%   |
| 5.14.14-202.current | 2         | 3.17%   |
| 5.15.68-218.current | 1         | 1.59%   |
| 5.15.61-217.current | 1         | 1.59%   |
| 5.15.37-214.current | 1         | 1.59%   |
| 5.14.7-198.current  | 1         | 1.59%   |
| 5.14.16-204.current | 1         | 1.59%   |
| 5.14.15-203.current | 1         | 1.59%   |
| 5.14.12-201.current | 1         | 1.59%   |
| 5.13.8-191.current  | 1         | 1.59%   |
| 5.13.15-194.current | 1         | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.32 | 8         | 12.7%   |
| 5.14.21 | 7         | 11.11%  |
| 5.14.16 | 7         | 11.11%  |
| 5.15.50 | 6         | 9.52%   |
| 5.13.1  | 6         | 9.52%   |
| 5.13.6  | 5         | 7.94%   |
| 5.13.12 | 5         | 7.94%   |
| 5.15.77 | 3         | 4.76%   |
| 5.15.43 | 2         | 3.17%   |
| 5.15.30 | 2         | 3.17%   |
| 5.15.26 | 2         | 3.17%   |
| 5.14.14 | 2         | 3.17%   |
| 5.15.68 | 1         | 1.59%   |
| 5.15.61 | 1         | 1.59%   |
| 5.15.37 | 1         | 1.59%   |
| 5.14.7  | 1         | 1.59%   |
| 5.14.15 | 1         | 1.59%   |
| 5.14.12 | 1         | 1.59%   |
| 5.13.8  | 1         | 1.59%   |
| 5.13.15 | 1         | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 40.32%  |
| 5.14    | 19        | 30.65%  |
| 5.13    | 18        | 29.03%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 37        | 62.71%  |
| KDE5    | 5         | 8.47%   |
| GNOME   | 5         | 8.47%   |
| Unknown | 5         | 8.47%   |
| MATE    | 4         | 6.78%   |
| KDE     | 3         | 5.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 58        | 98.31%  |
| Wayland | 1         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 74.58%  |
| LightDM | 10        | 16.95%  |
| SDDM    | 4         | 6.78%   |
| GDM     | 1         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 35        | 58.33%  |
| en_GB | 5         | 8.33%   |
| de_DE | 5         | 8.33%   |
| fr_FR | 3         | 5%      |
| ru_RU | 2         | 3.33%   |
| pt_BR | 2         | 3.33%   |
| es_ES | 2         | 3.33%   |
| nl_NL | 1         | 1.67%   |
| es_VE | 1         | 1.67%   |
| en_IN | 1         | 1.67%   |
| en_DK | 1         | 1.67%   |
| ar_SA | 1         | 1.67%   |
| ar_EG | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 55.74%  |
| BIOS | 27        | 44.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 56        | 94.92%  |
| Xfs     | 1         | 1.69%   |
| Overlay | 1         | 1.69%   |
| Btrfs   | 1         | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 74.58%  |
| GPT     | 10        | 16.95%  |
| MBR     | 5         | 8.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 93.33%  |
| Yes       | 4         | 6.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 83.05%  |
| Yes       | 10        | 16.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 15.25%  |
| Gigabyte Technology | 8         | 13.56%  |
| Lenovo              | 7         | 11.86%  |
| ASUSTek Computer    | 6         | 10.17%  |
| MSI                 | 4         | 6.78%   |
| Hewlett-Packard     | 3         | 5.08%   |
| ASRock              | 3         | 5.08%   |
| Acer                | 3         | 5.08%   |
| Toshiba             | 2         | 3.39%   |
| Google              | 2         | 3.39%   |
| Unknown             | 2         | 3.39%   |
| Sony                | 1         | 1.69%   |
| MEGA                | 1         | 1.69%   |
| Intel               | 1         | 1.69%   |
| GPU Company         | 1         | 1.69%   |
| Fujitsu             | 1         | 1.69%   |
| Framework           | 1         | 1.69%   |
| eMachines           | 1         | 1.69%   |
| Biostar             | 1         | 1.69%   |
| AZW                 | 1         | 1.69%   |
| Apple               | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 2         | 3.39%   |
| Toshiba TECRA R840                    | 1         | 1.69%   |
| Toshiba Satellite L855                | 1         | 1.69%   |
| Sony VPCYB15AB                        | 1         | 1.69%   |
| MSI MS-7B89                           | 1         | 1.69%   |
| MSI MS-7B85                           | 1         | 1.69%   |
| MSI MS-7A34                           | 1         | 1.69%   |
| MSI Modern 14 B5M                     | 1         | 1.69%   |
| MEGA G41T-M7 LGT                      | 1         | 1.69%   |
| Lenovo Z50-70 20354                   | 1         | 1.69%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 1.69%   |
| Lenovo ThinkCentre M71e 3157G6S       | 1         | 1.69%   |
| Lenovo IdeaPad S340-15API 81NC        | 1         | 1.69%   |
| Lenovo IdeaPad 5 15ALC05 82LN         | 1         | 1.69%   |
| Lenovo IdeaPad 320-15ISK 80XH         | 1         | 1.69%   |
| Lenovo C50-30 F0B1002EFR              | 1         | 1.69%   |
| Intel D946GZIS AAD66165-302           | 1         | 1.69%   |
| HP ProDesk 490 G3 MT Business PC      | 1         | 1.69%   |
| HP ProBook 450 G5                     | 1         | 1.69%   |
| HP OMEN Laptop 15-en0xxx              | 1         | 1.69%   |
| GPU Company GWTC116-2                 | 1         | 1.69%   |
| Google Edgar                          | 1         | 1.69%   |
| Google Delbin                         | 1         | 1.69%   |
| Gigabyte Z68AP-D3                     | 1         | 1.69%   |
| Gigabyte P31-ES3G                     | 1         | 1.69%   |
| Gigabyte H81M-S2V                     | 1         | 1.69%   |
| Gigabyte H110M-DS2V                   | 1         | 1.69%   |
| Gigabyte GA-MA770-UD3                 | 1         | 1.69%   |
| Gigabyte GA-78LMT-USB3 6.0            | 1         | 1.69%   |
| Gigabyte F2A68HM-H                    | 1         | 1.69%   |
| Gigabyte B85M-D3H                     | 1         | 1.69%   |
| Fujitsu CELSIUS W530                  | 1         | 1.69%   |
| Framework Laptop                      | 1         | 1.69%   |
| eMachines EL1852G                     | 1         | 1.69%   |
| Dell XPS 13 9380                      | 1         | 1.69%   |
| Dell XPS 13 7390                      | 1         | 1.69%   |
| Dell Vostro 15-3568                   | 1         | 1.69%   |
| Dell OptiPlex 9020                    | 1         | 1.69%   |
| Dell Latitude E6220                   | 1         | 1.69%   |
| Dell Latitude E5470                   | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 3         | 5.08%   |
| Dell Latitude          | 3         | 5.08%   |
| Dell XPS               | 2         | 3.39%   |
| Dell Inspiron          | 2         | 3.39%   |
| ASUS TUF               | 2         | 3.39%   |
| Unknown                | 2         | 3.39%   |
| Toshiba TECRA          | 1         | 1.69%   |
| Toshiba Satellite      | 1         | 1.69%   |
| Sony VPCYB15AB         | 1         | 1.69%   |
| MSI MS-7B89            | 1         | 1.69%   |
| MSI MS-7B85            | 1         | 1.69%   |
| MSI MS-7A34            | 1         | 1.69%   |
| MSI Modern             | 1         | 1.69%   |
| MEGA G41T-M7           | 1         | 1.69%   |
| Lenovo Z50-70          | 1         | 1.69%   |
| Lenovo ThinkPad        | 1         | 1.69%   |
| Lenovo ThinkCentre     | 1         | 1.69%   |
| Lenovo C50-30          | 1         | 1.69%   |
| Intel D946GZIS         | 1         | 1.69%   |
| HP ProDesk             | 1         | 1.69%   |
| HP ProBook             | 1         | 1.69%   |
| HP OMEN                | 1         | 1.69%   |
| GPU Company GWTC116-2  | 1         | 1.69%   |
| Google Edgar           | 1         | 1.69%   |
| Google Delbin          | 1         | 1.69%   |
| Gigabyte Z68AP-D3      | 1         | 1.69%   |
| Gigabyte P31-ES3G      | 1         | 1.69%   |
| Gigabyte H81M-S2V      | 1         | 1.69%   |
| Gigabyte H110M-DS2V    | 1         | 1.69%   |
| Gigabyte GA-MA770-UD3  | 1         | 1.69%   |
| Gigabyte GA-78LMT-USB3 | 1         | 1.69%   |
| Gigabyte F2A68HM-H     | 1         | 1.69%   |
| Gigabyte B85M-D3H      | 1         | 1.69%   |
| Fujitsu CELSIUS        | 1         | 1.69%   |
| Framework Laptop       | 1         | 1.69%   |
| eMachines EL1852G      | 1         | 1.69%   |
| Dell Vostro            | 1         | 1.69%   |
| Dell OptiPlex          | 1         | 1.69%   |
| Biostar H61MLV2        | 1         | 1.69%   |
| AZW SEi                | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 9         | 15.25%  |
| 2019 | 7         | 11.86%  |
| 2018 | 7         | 11.86%  |
| 2014 | 6         | 10.17%  |
| 2011 | 6         | 10.17%  |
| 2020 | 4         | 6.78%   |
| 2017 | 4         | 6.78%   |
| 2016 | 4         | 6.78%   |
| 2015 | 3         | 5.08%   |
| 2008 | 3         | 5.08%   |
| 2013 | 2         | 3.39%   |
| 2012 | 2         | 3.39%   |
| 2010 | 1         | 1.69%   |
| 2006 | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 30        | 50.85%  |
| Notebook   | 28        | 47.46%  |
| All in one | 1         | 1.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 59        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 96.61%  |
| Yes  | 2         | 3.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 12        | 20.34%  |
| 16.01-24.0 | 12        | 20.34%  |
| 8.01-16.0  | 12        | 20.34%  |
| 4.01-8.0   | 10        | 16.95%  |
| 32.01-64.0 | 8         | 13.56%  |
| 2.01-3.0   | 2         | 3.39%   |
| 1.01-2.0   | 2         | 3.39%   |
| 24.01-32.0 | 1         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 22        | 34.92%  |
| 2.01-3.0  | 19        | 30.16%  |
| 4.01-8.0  | 9         | 14.29%  |
| 3.01-4.0  | 9         | 14.29%  |
| 8.01-16.0 | 2         | 3.17%   |
| 0.51-1.0  | 2         | 3.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 52.46%  |
| 2      | 15        | 24.59%  |
| 4      | 7         | 11.48%  |
| 3      | 5         | 8.2%    |
| 5      | 2         | 3.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 64.41%  |
| Yes       | 21        | 35.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 83.05%  |
| No        | 10        | 16.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 71.19%  |
| No        | 17        | 28.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 62.71%  |
| No        | 22        | 37.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 13        | 22.03%  |
| Germany      | 6         | 10.17%  |
| India        | 4         | 6.78%   |
| Netherlands  | 3         | 5.08%   |
| Brazil       | 3         | 5.08%   |
| UK           | 2         | 3.39%   |
| Norway       | 2         | 3.39%   |
| France       | 2         | 3.39%   |
| Vietnam      | 1         | 1.69%   |
| Venezuela    | 1         | 1.69%   |
| Ukraine      | 1         | 1.69%   |
| Thailand     | 1         | 1.69%   |
| Switzerland  | 1         | 1.69%   |
| Sweden       | 1         | 1.69%   |
| Spain        | 1         | 1.69%   |
| Saudi Arabia | 1         | 1.69%   |
| Russia       | 1         | 1.69%   |
| Poland       | 1         | 1.69%   |
| Philippines  | 1         | 1.69%   |
| Nepal        | 1         | 1.69%   |
| Mexico       | 1         | 1.69%   |
| Kazakhstan   | 1         | 1.69%   |
| Iran         | 1         | 1.69%   |
| Guyana       | 1         | 1.69%   |
| Greece       | 1         | 1.69%   |
| Denmark      | 1         | 1.69%   |
| Czechia      | 1         | 1.69%   |
| Canada       | 1         | 1.69%   |
| Belgium      | 1         | 1.69%   |
| Australia    | 1         | 1.69%   |
| Argentina    | 1         | 1.69%   |
| Albania      | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Oslo                     | 2         | 3.28%   |
| Yverdon-les-Bains        | 1         | 1.64%   |
| Wendell                  | 1         | 1.64%   |
| Weil am Rhein            | 1         | 1.64%   |
| Vineland                 | 1         | 1.64%   |
| Viby J                   | 1         | 1.64%   |
| Vasco da Gama            | 1         | 1.64%   |
| Toronto                  | 1         | 1.64%   |
| Thessaloniki             | 1         | 1.64%   |
| Stockholm                | 1         | 1.64%   |
| Stare Babice             | 1         | 1.64%   |
| Songkhla                 | 1         | 1.64%   |
| Seville                  | 1         | 1.64%   |
| Severna Park             | 1         | 1.64%   |
| San Justo                | 1         | 1.64%   |
| Saint-Just-Saint-Rambert | 1         | 1.64%   |
| Red Oak                  | 1         | 1.64%   |
| Portsmouth               | 1         | 1.64%   |
| Pomeroy                  | 1         | 1.64%   |
| Phoenix                  | 1         | 1.64%   |
| Orenburg                 | 1         | 1.64%   |
| Ochten                   | 1         | 1.64%   |
| Mohali                   | 1         | 1.64%   |
| Milwaukee                | 1         | 1.64%   |
| Miami                    | 1         | 1.64%   |
| Melbourne                | 1         | 1.64%   |
| Lviv                     | 1         | 1.64%   |
| Luckenwalde              | 1         | 1.64%   |
| Lipa City                | 1         | 1.64%   |
| Linter                   | 1         | 1.64%   |
| Lexington                | 1         | 1.64%   |
| Krefeld                  | 1         | 1.64%   |
| Kolkata                  | 1         | 1.64%   |
| Khobar                   | 1         | 1.64%   |
| Kathmandu                | 1         | 1.64%   |
| Ilford                   | 1         | 1.64%   |
| Huntington Park          | 1         | 1.64%   |
| Hanoi                    | 1         | 1.64%   |
| Hamburg                  | 1         | 1.64%   |
| Guanajuato City          | 1         | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 27     | 19.8%   |
| Samsung Electronics | 17        | 23     | 16.83%  |
| Seagate             | 10        | 10     | 9.9%    |
| SanDisk             | 8         | 10     | 7.92%   |
| Kingston            | 8         | 11     | 7.92%   |
| Toshiba             | 6         | 6      | 5.94%   |
| SK hynix            | 4         | 4      | 3.96%   |
| Crucial             | 4         | 4      | 3.96%   |
| Unknown             | 3         | 3      | 2.97%   |
| PNY                 | 3         | 3      | 2.97%   |
| Intel               | 3         | 4      | 2.97%   |
| Phison              | 2         | 2      | 1.98%   |
| Hitachi             | 2         | 2      | 1.98%   |
| SPCC Sol            | 1         | 1      | 0.99%   |
| Silicon Motion      | 1         | 1      | 0.99%   |
| SABRENT             | 1         | 1      | 0.99%   |
| Micron Technology   | 1         | 1      | 0.99%   |
| Maxtor              | 1         | 1      | 0.99%   |
| KIOXIA              | 1         | 1      | 0.99%   |
| Intenso             | 1         | 2      | 0.99%   |
| HFS512GD            | 1         | 1      | 0.99%   |
| China               | 1         | 1      | 0.99%   |
| Apple               | 1         | 1      | 0.99%   |
| Advantech           | 1         | 1      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 4         | 3.57%   |
| Samsung NVMe SSD Drive 500GB     | 3         | 2.68%   |
| Kingston SA400S37240G 240GB SSD  | 3         | 2.68%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 1.79%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2         | 1.79%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.79%   |
| SK hynix NVMe SSD Drive 128GB    | 2         | 1.79%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.79%   |
| PNY CS900 240GB SSD              | 2         | 1.79%   |
| Kingston SA400S37480G 480GB SSD  | 2         | 1.79%   |
| Crucial CT1000P1SSD8 1TB         | 2         | 1.79%   |
| Crucial CT1000MX500SSD1 1TB      | 2         | 1.79%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD | 1         | 0.89%   |
| WDC WD6400AAKS-75A7B2 640GB      | 1         | 0.89%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 0.89%   |
| WDC WD5000AVCS-632DY1 500GB      | 1         | 0.89%   |
| WDC WD5000AAKX-003CA0 500GB      | 1         | 0.89%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1         | 0.89%   |
| WDC WD3200BEVT-75ZCT2 320GB      | 1         | 0.89%   |
| WDC WD3200AAJS-00YZCA0 320GB     | 1         | 0.89%   |
| WDC WD32 00AAJS-00L7A0 320GB     | 1         | 0.89%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1         | 0.89%   |
| WDC WD2500HHTZ-04N21V1 250GB     | 1         | 0.89%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1         | 0.89%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1         | 0.89%   |
| WDC WD1600AAJS-00M0A0 160GB      | 1         | 0.89%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.89%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 0.89%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.89%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1         | 0.89%   |
| WDC WD10EADS-00P8B0 1TB          | 1         | 0.89%   |
| WDC WD10EADS-00M2B0 1TB          | 1         | 0.89%   |
| WDC WD1003FBYX-01Y7B0 1TB        | 1         | 0.89%   |
| WDC WD My Passport 25F3 512GB    | 1         | 0.89%   |
| Unknown USB DISK 3.2 1TB         | 1         | 0.89%   |
| Unknown MMC Card  64GB           | 1         | 0.89%   |
| Unknown MMC Card  128GB          | 1         | 0.89%   |
| Toshiba XS700 240GB              | 1         | 0.89%   |
| Toshiba MQ01ABF050 500GB         | 1         | 0.89%   |
| Toshiba KXG60ZNV512G NVMe 512GB  | 1         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 25     | 50%     |
| Seagate             | 10        | 10     | 26.32%  |
| Toshiba             | 4         | 4      | 10.53%  |
| Hitachi             | 2         | 2      | 5.26%   |
| Samsung Electronics | 1         | 1      | 2.63%   |
| Maxtor              | 1         | 1      | 2.63%   |
| Intenso             | 1         | 2      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 38.71%  |
| Kingston            | 5         | 8      | 16.13%  |
| SanDisk             | 3         | 3      | 9.68%   |
| PNY                 | 3         | 3      | 9.68%   |
| Crucial             | 2         | 2      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| SPCC Sol            | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| China               | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |
| Advantech           | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 32        | 45     | 36.78%  |
| NVMe    | 25        | 32     | 28.74%  |
| SSD     | 23        | 37     | 26.44%  |
| Unknown | 4         | 4      | 4.6%    |
| MMC     | 3         | 3      | 3.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 76     | 53.95%  |
| NVMe | 25        | 31     | 32.89%  |
| SAS  | 7         | 11     | 9.21%   |
| MMC  | 3         | 3      | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 50     | 51.72%  |
| 0.51-1.0   | 18        | 21     | 31.03%  |
| 1.01-2.0   | 7         | 7      | 12.07%  |
| 3.01-4.0   | 2         | 2      | 3.45%   |
| 2.01-3.0   | 1         | 2      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 17        | 27.87%  |
| 101-250        | 14        | 22.95%  |
| 501-1000       | 14        | 22.95%  |
| 1001-2000      | 6         | 9.84%   |
| More than 3000 | 3         | 4.92%   |
| 21-50          | 3         | 4.92%   |
| 51-100         | 3         | 4.92%   |
| 2001-3000      | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 34.92%  |
| 21-50          | 11        | 17.46%  |
| 101-250        | 8         | 12.7%   |
| 251-500        | 6         | 9.52%   |
| 501-1000       | 6         | 9.52%   |
| 51-100         | 5         | 7.94%   |
| 1001-2000      | 4         | 6.35%   |
| More than 3000 | 1         | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |
| Crucial CT1000P1SSD8 1TB  | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 47        | 101    | 74.6%   |
| Works    | 14        | 18     | 22.22%  |
| Malfunc  | 2         | 2      | 3.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 32        | 42.11%  |
| AMD                          | 20        | 26.32%  |
| Samsung Electronics          | 6         | 7.89%   |
| SK hynix                     | 4         | 5.26%   |
| SanDisk                      | 4         | 5.26%   |
| Kingston Technology Company  | 3         | 3.95%   |
| Toshiba America Info Systems | 2         | 2.63%   |
| Phison Electronics           | 2         | 2.63%   |
| Micron/Crucial Technology    | 2         | 2.63%   |
| Silicon Motion               | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 15.73%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 6.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 5.62%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 5.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 4.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 3.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 3.37%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 2.25%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 2.25%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 2.25%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2         | 2.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2         | 2.25%   |
| Intel SSD 600P Series                                                                   | 2         | 2.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 2.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 2.25%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                             | 1         | 1.12%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.12%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 1.12%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.12%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.12%   |
| Samsung Electronics SATA controller                                                     | 1         | 1.12%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.12%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.12%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 1.12%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 1.12%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1         | 1.12%   |
| Intel SSD 660P Series                                                                   | 1         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.12%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 1.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 45        | 57.69%  |
| NVMe | 24        | 30.77%  |
| IDE  | 8         | 10.26%  |
| RAID | 1         | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 64.41%  |
| AMD    | 21        | 35.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 3.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 3.39%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2         | 3.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 3.39%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 3.39%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz         | 1         | 1.69%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1.69%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.69%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.69%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.69%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 1.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 1.69%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1         | 1.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.69%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.69%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1         | 1.69%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.69%   |
| Intel Core i3-3210 CPU @ 3.20GHz            | 1         | 1.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.69%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.69%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.69%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1         | 1.69%   |
| Intel Celeron CPU E3400 @ 2.60GHz           | 1         | 1.69%   |
| Intel Celeron CPU E3300 @ 2.50GHz           | 1         | 1.69%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 1.69%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 1.69%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz           | 1         | 1.69%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 1         | 1.69%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1         | 1.69%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.69%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1         | 1.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 1         | 1.69%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 9         | 15.25%  |
| Intel Core i5           | 9         | 15.25%  |
| AMD Ryzen 7             | 8         | 13.56%  |
| Intel Celeron           | 7         | 11.86%  |
| AMD Ryzen 5             | 6         | 10.17%  |
| Intel Core i3           | 5         | 8.47%   |
| Other                   | 3         | 5.08%   |
| AMD Ryzen 9             | 2         | 3.39%   |
| AMD A10                 | 2         | 3.39%   |
| Intel Xeon              | 1         | 1.69%   |
| Intel Pentium Silver    | 1         | 1.69%   |
| Intel Pentium Dual-Core | 1         | 1.69%   |
| Intel Core 2 Quad       | 1         | 1.69%   |
| Intel Atom              | 1         | 1.69%   |
| AMD Phenom II X4        | 1         | 1.69%   |
| AMD FX                  | 1         | 1.69%   |
| AMD E                   | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 22        | 37.29%  |
| 2      | 21        | 35.59%  |
| 8      | 8         | 13.56%  |
| 6      | 5         | 8.47%   |
| 12     | 1         | 1.69%   |
| 3      | 1         | 1.69%   |
| 1      | 1         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 59        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 43        | 72.88%  |
| 1      | 16        | 27.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 59        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 6         | 9.84%   |
| Unknown    | 6         | 9.84%   |
| 0x206a7    | 5         | 8.2%    |
| 0x1067a    | 4         | 6.56%   |
| 0x806ec    | 3         | 4.92%   |
| 0x806c1    | 3         | 4.92%   |
| 0x0800820d | 3         | 4.92%   |
| 0x906e9    | 2         | 3.28%   |
| 0x806ea    | 2         | 3.28%   |
| 0x506e3    | 2         | 3.28%   |
| 0x40651    | 2         | 3.28%   |
| 0x0a50000c | 2         | 3.28%   |
| 0x08701021 | 2         | 3.28%   |
| 0x08701013 | 2         | 3.28%   |
| 0x08600106 | 2         | 3.28%   |
| 0x06003106 | 2         | 3.28%   |
| 0x906c0    | 1         | 1.64%   |
| 0x706a8    | 1         | 1.64%   |
| 0x706a1    | 1         | 1.64%   |
| 0x406e3    | 1         | 1.64%   |
| 0x306a9    | 1         | 1.64%   |
| 0x10661    | 1         | 1.64%   |
| 0x0a201204 | 1         | 1.64%   |
| 0x08608103 | 1         | 1.64%   |
| 0x08108109 | 1         | 1.64%   |
| 0x08108102 | 1         | 1.64%   |
| 0x06000852 | 1         | 1.64%   |
| 0x05000029 | 1         | 1.64%   |
| 0x010000c8 | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 13.56%  |
| Haswell       | 8         | 13.56%  |
| Zen 2         | 6         | 10.17%  |
| Zen+          | 5         | 8.47%   |
| SandyBridge   | 5         | 8.47%   |
| Skylake       | 4         | 6.78%   |
| Penryn        | 4         | 6.78%   |
| Zen 3         | 3         | 5.08%   |
| TigerLake     | 3         | 5.08%   |
| Steamroller   | 2         | 3.39%   |
| Goldmont plus | 2         | 3.39%   |
| Unknown       | 2         | 3.39%   |
| Tremont       | 1         | 1.69%   |
| Silvermont    | 1         | 1.69%   |
| Piledriver    | 1         | 1.69%   |
| K10           | 1         | 1.69%   |
| IvyBridge     | 1         | 1.69%   |
| Core          | 1         | 1.69%   |
| Bobcat        | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 43.66%  |
| AMD    | 24        | 33.8%   |
| Nvidia | 16        | 22.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.78%   |
| Intel HD Graphics 530                                                                    | 2         | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.78%   |
| AMD Renoir                                                                               | 2         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.78%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 2.78%   |
| AMD Lucienne                                                                             | 2         | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 2.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.39%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.39%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 1.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.39%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.39%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.39%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.39%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1         | 1.39%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 1         | 1.39%   |
| Nvidia GF119 [GeForce 605]                                                               | 1         | 1.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.39%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.39%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 1         | 1.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.39%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.39%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.39%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.39%   |
| Intel HD Graphics 630                                                                    | 1         | 1.39%   |
| Intel HD Graphics 620                                                                    | 1         | 1.39%   |
| Intel HD Graphics 520                                                                    | 1         | 1.39%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 35.59%  |
| 1 x AMD        | 20        | 33.9%   |
| 1 x Nvidia     | 9         | 15.25%  |
| Intel + Nvidia | 5         | 8.47%   |
| Intel + AMD    | 2         | 3.39%   |
| AMD + Nvidia   | 2         | 3.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 48        | 81.36%  |
| Proprietary | 11        | 18.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 40.68%  |
| 1.01-2.0   | 11        | 18.64%  |
| 0.51-1.0   | 8         | 13.56%  |
| 0.01-0.5   | 5         | 8.47%   |
| 3.01-4.0   | 4         | 6.78%   |
| 5.01-6.0   | 3         | 5.08%   |
| 7.01-8.0   | 2         | 3.39%   |
| 8.01-16.0  | 2         | 3.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 9         | 13.04%  |
| Chimei Innolux          | 7         | 10.14%  |
| AOC                     | 7         | 10.14%  |
| AU Optronics            | 6         | 8.7%    |
| Goldstar                | 5         | 7.25%   |
| BOE                     | 5         | 7.25%   |
| Ancor Communications    | 4         | 5.8%    |
| Dell                    | 3         | 4.35%   |
| Acer                    | 3         | 4.35%   |
| NEC Computers           | 2         | 2.9%    |
| LG Display              | 2         | 2.9%    |
| Lenovo                  | 2         | 2.9%    |
| BenQ                    | 2         | 2.9%    |
| Toshiba                 | 1         | 1.45%   |
| Sharp                   | 1         | 1.45%   |
| Philips                 | 1         | 1.45%   |
| PANDA                   | 1         | 1.45%   |
| Microstep               | 1         | 1.45%   |
| LG Electronics          | 1         | 1.45%   |
| Hewlett-Packard         | 1         | 1.45%   |
| CSO                     | 1         | 1.45%   |
| Chi Mei Optoelectronics | 1         | 1.45%   |
| ASUSTek Computer        | 1         | 1.45%   |
| Apple                   | 1         | 1.45%   |
| Unknown                 | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 3         | 4.11%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch            | 1         | 1.37%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 1.37%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 1.37%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch    | 1         | 1.37%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch    | 1         | 1.37%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                | 1         | 1.37%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch              | 1         | 1.37%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1         | 1.37%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1         | 1.37%   |
| Microstep LCD Monitor MSI G241                                       | 1         | 1.37%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1         | 1.37%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch         | 1         | 1.37%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 1         | 1.37%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                  | 1         | 1.37%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1         | 1.37%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1         | 1.37%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1         | 1.37%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1         | 1.37%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1         | 1.37%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1         | 1.37%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                  | 1         | 1.37%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                  | 1         | 1.37%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1         | 1.37%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch     | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 46.27%  |
| 1366x768 (WXGA)    | 14        | 20.9%   |
| 3840x2160 (4K)     | 4         | 5.97%   |
| 2560x1440 (QHD)    | 4         | 5.97%   |
| 1280x1024 (SXGA)   | 3         | 4.48%   |
| 5760x1080          | 1         | 1.49%   |
| 2560x1080          | 1         | 1.49%   |
| 2256x1504          | 1         | 1.49%   |
| 1920x1200 (WUXGA)  | 1         | 1.49%   |
| 1680x1050 (WSXGA+) | 1         | 1.49%   |
| 1600x900 (HD+)     | 1         | 1.49%   |
| 1440x900 (WXGA+)   | 1         | 1.49%   |
| 1360x768           | 1         | 1.49%   |
| 1280x800 (WXGA)    | 1         | 1.49%   |
| 1024x768 (XGA)     | 1         | 1.49%   |
| Unknown            | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 28.79%  |
| 24      | 9         | 13.64%  |
| Unknown | 7         | 10.61%  |
| 13      | 5         | 7.58%   |
| 27      | 4         | 6.06%   |
| 23      | 4         | 6.06%   |
| 21      | 4         | 6.06%   |
| 18      | 4         | 6.06%   |
| 14      | 2         | 3.03%   |
| 11      | 2         | 3.03%   |
| 31      | 1         | 1.52%   |
| 29      | 1         | 1.52%   |
| 22      | 1         | 1.52%   |
| 20      | 1         | 1.52%   |
| 19      | 1         | 1.52%   |
| 17      | 1         | 1.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 34.85%  |
| 501-600     | 17        | 25.76%  |
| 401-500     | 10        | 15.15%  |
| Unknown     | 7         | 10.61%  |
| 201-300     | 5         | 7.58%   |
| 601-700     | 2         | 3.03%   |
| 351-400     | 2         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 44        | 68.75%  |
| 16/10   | 8         | 12.5%   |
| Unknown | 7         | 10.94%  |
| 5/4     | 2         | 3.13%   |
| 4/3     | 1         | 1.56%   |
| 3/2     | 1         | 1.56%   |
| 21/9    | 1         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 28.36%  |
| 201-250        | 13        | 19.4%   |
| Unknown        | 7         | 10.45%  |
| 81-90          | 5         | 7.46%   |
| 301-350        | 5         | 7.46%   |
| 251-300        | 5         | 7.46%   |
| 151-200        | 4         | 5.97%   |
| 141-150        | 4         | 5.97%   |
| 71-80          | 2         | 2.99%   |
| 51-60          | 2         | 2.99%   |
| 351-500        | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 25        | 39.68%  |
| 121-160       | 13        | 20.63%  |
| 101-120       | 12        | 19.05%  |
| Unknown       | 7         | 11.11%  |
| 161-240       | 4         | 6.35%   |
| More than 240 | 2         | 3.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 74.58%  |
| 2     | 13        | 22.03%  |
| 3     | 2         | 3.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 39.08%  |
| Intel                    | 25        | 28.74%  |
| Qualcomm Atheros         | 10        | 11.49%  |
| MediaTek                 | 4         | 4.6%    |
| Broadcom                 | 3         | 3.45%   |
| Xiaomi                   | 1         | 1.15%   |
| TP-Link                  | 1         | 1.15%   |
| T & A Mobile Phones      | 1         | 1.15%   |
| Ralink Technology        | 1         | 1.15%   |
| Marvell Technology Group | 1         | 1.15%   |
| Linksys                  | 1         | 1.15%   |
| Huawei Technologies      | 1         | 1.15%   |
| Dell                     | 1         | 1.15%   |
| D-Link System            | 1         | 1.15%   |
| Belkin Components        | 1         | 1.15%   |
| ASIX Electronics         | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 26.47%  |
| Intel Wi-Fi 6 AX200                                               | 6         | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 4         | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.96%   |
| Intel Wireless 3165                                               | 2         | 1.96%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.96%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.98%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.98%   |
| T & A Mobile Phones A509DL                                        | 1         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.98%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.98%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.98%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 1         | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.98%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.98%   |
| Intel Wireless-AC 9260                                            | 1         | 0.98%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.98%   |
| Intel Wireless 8260                                               | 1         | 0.98%   |
| Intel Wireless 7265                                               | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 39.58%  |
| Realtek Semiconductor | 10        | 20.83%  |
| Qualcomm Atheros      | 8         | 16.67%  |
| MediaTek              | 4         | 8.33%   |
| Broadcom              | 3         | 6.25%   |
| Ralink Technology     | 1         | 2.08%   |
| Linksys               | 1         | 2.08%   |
| D-Link System         | 1         | 2.08%   |
| Belkin Components     | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 6         | 12.5%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                              | 3         | 6.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2         | 4.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 2         | 4.17%   |
| Intel Wireless 3165                                                                     | 2         | 4.17%   |
| Intel Wi-Fi 6 AX201                                                                     | 2         | 4.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 1         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1         | 2.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                | 1         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1         | 2.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                         | 1         | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1         | 2.08%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1         | 2.08%   |
| Realtek 802.11n WLAN Adapter                                                            | 1         | 2.08%   |
| Ralink MT7601U Wireless Adapter                                                         | 1         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1         | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 1         | 2.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1         | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                           | 1         | 2.08%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1         | 2.08%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1         | 2.08%   |
| Intel Wireless-AC 9260                                                                  | 1         | 2.08%   |
| Intel Wireless 8265 / 8275                                                              | 1         | 2.08%   |
| Intel Wireless 8260                                                                     | 1         | 2.08%   |
| Intel Wireless 7265                                                                     | 1         | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 1         | 2.08%   |
| Intel Wi-Fi 6 AX201 160MHz                                                              | 1         | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1         | 2.08%   |
| Intel Centrino Ultimate-N 6300                                                          | 1         | 2.08%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                           | 1         | 2.08%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1         | 2.08%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                             | 1         | 2.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1         | 2.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                                         | 1         | 2.08%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 55.77%  |
| Intel                    | 14        | 26.92%  |
| Qualcomm Atheros         | 3         | 5.77%   |
| Xiaomi                   | 1         | 1.92%   |
| TP-Link                  | 1         | 1.92%   |
| Marvell Technology Group | 1         | 1.92%   |
| Huawei Technologies      | 1         | 1.92%   |
| Broadcom                 | 1         | 1.92%   |
| ASIX Electronics         | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 51.92%  |
| Intel I211 Gigabit Network Connection                             | 4         | 7.69%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.85%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.92%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.92%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.92%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.92%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.92%   |
| Huawei SNE-LX1                                                    | 1         | 1.92%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 52.13%  |
| WiFi     | 43        | 45.74%  |
| Modem    | 1         | 1.06%   |
| Unknown  | 1         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 53.97%  |
| Ethernet | 29        | 46.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 32        | 54.24%  |
| 2     | 25        | 42.37%  |
| 3     | 1         | 1.69%   |
| 0     | 1         | 1.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 73.33%  |
| Yes  | 16        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 43.59%  |
| Qualcomm Atheros Communications | 4         | 10.26%  |
| Realtek Semiconductor           | 3         | 7.69%   |
| Cambridge Silicon Radio         | 3         | 7.69%   |
| MediaTek                        | 2         | 5.13%   |
| Lite-On Technology              | 2         | 5.13%   |
| Broadcom                        | 2         | 5.13%   |
| Toshiba                         | 1         | 2.56%   |
| IMC Networks                    | 1         | 2.56%   |
| Foxconn / Hon Hai               | 1         | 2.56%   |
| Dell                            | 1         | 2.56%   |
| ASUSTek Computer                | 1         | 2.56%   |
| Apple                           | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 6         | 15.38%  |
| Intel Bluetooth wireless interface                  | 5         | 12.82%  |
| Intel AX201 Bluetooth                               | 3         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.13%   |
| MediaTek Wireless_Device                            | 2         | 5.13%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.56%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.56%   |
| Realtek Bluetooth Radio                             | 1         | 2.56%   |
| Lite-On Wireless_Device                             | 1         | 2.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.56%   |
| Intel AX210 Bluetooth                               | 1         | 2.56%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.56%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.56%   |
| Broadcom BCM92045B3 ROM                             | 1         | 2.56%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.56%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 38        | 44.71%  |
| AMD                 | 25        | 29.41%  |
| Nvidia              | 13        | 15.29%  |
| C-Media Electronics | 2         | 2.35%   |
| Blue Microphones    | 2         | 2.35%   |
| Texas Instruments   | 1         | 1.18%   |
| Tenx Technology     | 1         | 1.18%   |
| Samsung Electronics | 1         | 1.18%   |
| Cooler Master       | 1         | 1.18%   |
| Conexant Systems    | 1         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 7.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.63%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 4.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 3.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.85%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.85%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.85%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2         | 1.85%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.85%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.85%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.85%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1         | 0.93%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.93%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.93%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.93%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.93%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 29.17%  |
| SK hynix            | 3         | 12.5%   |
| Crucial             | 3         | 12.5%   |
| Unknown             | 2         | 8.33%   |
| Micron Technology   | 2         | 8.33%   |
| A-DATA Technology   | 2         | 8.33%   |
| Transcend           | 1         | 4.17%   |
| Team                | 1         | 4.17%   |
| Patriot             | 1         | 4.17%   |
| G.Skill             | 1         | 4.17%   |
| Corsair             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 4.17%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 4.17%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s                | 1         | 4.17%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 4.17%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 4.17%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.17%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.17%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 4.17%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 4.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.17%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4.17%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4.17%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 4.17%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s              | 1         | 4.17%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 4.17%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 4.17%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 4.17%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 4.17%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 4.17%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8192MB DIMM DDR4 3200MT/s        | 1         | 4.17%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s            | 1         | 4.17%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 4.17%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 47.62%  |
| DDR3   | 5         | 23.81%  |
| LPDDR3 | 3         | 14.29%  |
| LPDDR4 | 1         | 4.76%   |
| DDR2   | 1         | 4.76%   |
| DDR    | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 55%     |
| DIMM         | 6         | 30%     |
| Row Of Chips | 3         | 15%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 38.1%   |
| 4096  | 6         | 28.57%  |
| 16384 | 4         | 19.05%  |
| 32768 | 1         | 4.76%   |
| 2048  | 1         | 4.76%   |
| 1024  | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 6         | 27.27%  |
| 2133    | 4         | 18.18%  |
| 1600    | 4         | 18.18%  |
| 2400    | 2         | 9.09%   |
| 4267    | 1         | 4.55%   |
| 2667    | 1         | 4.55%   |
| 1867    | 1         | 4.55%   |
| 1333    | 1         | 4.55%   |
| 667     | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Logitech                               | 5         | 14.71%  |
| Realtek Semiconductor                  | 4         | 11.76%  |
| Quanta                                 | 4         | 11.76%  |
| Sunplus Innovation Technology          | 3         | 8.82%   |
| Microdia                               | 3         | 8.82%   |
| IMC Networks                           | 2         | 5.88%   |
| Chicony Electronics                    | 2         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.88%   |
| Acer                                   | 2         | 5.88%   |
| Syntek                                 | 1         | 2.94%   |
| MacroSilicon                           | 1         | 2.94%   |
| LG Electronics                         | 1         | 2.94%   |
| Importek                               | 1         | 2.94%   |
| Hewlett-Packard                        | 1         | 2.94%   |
| Apple                                  | 1         | 2.94%   |
| A4Tech                                 | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                    | 2         | 5.88%   |
| Quanta HD User Facing                                           | 2         | 5.88%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 5.88%   |
| Logitech Webcam C270                                            | 2         | 5.88%   |
| Syntek Integrated Camera                                        | 1         | 2.94%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 2.94%   |
| Realtek Laptop Camera                                           | 1         | 2.94%   |
| Realtek Integrated Webcam_HD                                    | 1         | 2.94%   |
| Realtek Integrated Webcam                                       | 1         | 2.94%   |
| Realtek HD WebCam                                               | 1         | 2.94%   |
| Quanta VGA WebCam                                               | 1         | 2.94%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 2.94%   |
| Microdia Hy-HD-Camera                                           | 1         | 2.94%   |
| MacroSilicon ShadowCast                                         | 1         | 2.94%   |
| Logitech HD Pro Webcam C920                                     | 1         | 2.94%   |
| Logitech C922 Pro Stream Webcam                                 | 1         | 2.94%   |
| Logitech C920 PRO HD Webcam                                     | 1         | 2.94%   |
| LG Optimus (Various Models) MTP Mode                            | 1         | 2.94%   |
| Importek TOSHIBA Web Camera - HD                                | 1         | 2.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 2.94%   |
| IMC Networks Integrated Camera                                  | 1         | 2.94%   |
| HP Webcam HD 2300                                               | 1         | 2.94%   |
| Chicony Sony Visual Communication Camera                        | 1         | 2.94%   |
| Chicony EasyCamera                                              | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 2.94%   |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 2.94%   |
| Acer LENOVO LBG 720P CAM                                        | 1         | 2.94%   |
| Acer Lenovo EasyCamera                                          | 1         | 2.94%   |
| A4Tech FHD 1080P PC Camera                                      | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Synaptics                  | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |
| AuthenTec                  | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 20%     |
| Validity Sensors VFS Fingerprint sensor           | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 20%     |
| AuthenTec Fingerprint Sensor                      | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 45        | 75%     |
| 1     | 9         | 15%     |
| 2     | 5         | 8.33%   |
| 3     | 1         | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 8         | 30.77%  |
| Multimedia controller | 5         | 19.23%  |
| Fingerprint reader    | 5         | 19.23%  |
| Chipcard              | 4         | 15.38%  |
| Unassigned class      | 1         | 3.85%   |
| Storage               | 1         | 3.85%   |
| Graphics card         | 1         | 3.85%   |
| Camera                | 1         | 3.85%   |


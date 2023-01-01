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

Total: 96

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 2B47                        | Desktop     | [8980bff4e8](https://linux-hardware.org/?probe=8980bff4e8) | Dec 21, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7d42818fc5](https://linux-hardware.org/?probe=7d42818fc5) | Dec 06, 2022 |
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
| 5.15.32-213.current | 8         | 11.94%  |
| 5.14.21-210.current | 7         | 10.45%  |
| 5.15.50-216.current | 6         | 8.96%   |
| 5.14.16-205.current | 6         | 8.96%   |
| 5.13.1-187.current  | 6         | 8.96%   |
| 5.13.6-190.current  | 5         | 7.46%   |
| 5.13.12-193.current | 5         | 7.46%   |
| 6.0.11-225.current  | 4         | 5.97%   |
| 5.15.77-219.current | 3         | 4.48%   |
| 5.15.43-215.current | 2         | 2.99%   |
| 5.15.30-212.current | 2         | 2.99%   |
| 5.15.26-211.current | 2         | 2.99%   |
| 5.14.14-202.current | 2         | 2.99%   |
| 5.15.68-218.current | 1         | 1.49%   |
| 5.15.61-217.current | 1         | 1.49%   |
| 5.15.37-214.current | 1         | 1.49%   |
| 5.14.7-198.current  | 1         | 1.49%   |
| 5.14.16-204.current | 1         | 1.49%   |
| 5.14.15-203.current | 1         | 1.49%   |
| 5.14.12-201.current | 1         | 1.49%   |
| 5.13.8-191.current  | 1         | 1.49%   |
| 5.13.15-194.current | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.32 | 8         | 11.94%  |
| 5.14.21 | 7         | 10.45%  |
| 5.14.16 | 7         | 10.45%  |
| 5.15.50 | 6         | 8.96%   |
| 5.13.1  | 6         | 8.96%   |
| 5.13.6  | 5         | 7.46%   |
| 5.13.12 | 5         | 7.46%   |
| 6.0.11  | 4         | 5.97%   |
| 5.15.77 | 3         | 4.48%   |
| 5.15.43 | 2         | 2.99%   |
| 5.15.30 | 2         | 2.99%   |
| 5.15.26 | 2         | 2.99%   |
| 5.14.14 | 2         | 2.99%   |
| 5.15.68 | 1         | 1.49%   |
| 5.15.61 | 1         | 1.49%   |
| 5.15.37 | 1         | 1.49%   |
| 5.14.7  | 1         | 1.49%   |
| 5.14.15 | 1         | 1.49%   |
| 5.14.12 | 1         | 1.49%   |
| 5.13.8  | 1         | 1.49%   |
| 5.13.15 | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 37.88%  |
| 5.14    | 19        | 28.79%  |
| 5.13    | 18        | 27.27%  |
| 6.0     | 4         | 6.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 62        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 38        | 60.32%  |
| MATE    | 7         | 11.11%  |
| KDE5    | 5         | 7.94%   |
| GNOME   | 5         | 7.94%   |
| Unknown | 5         | 7.94%   |
| KDE     | 3         | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 61        | 98.39%  |
| Wayland | 1         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 73.02%  |
| LightDM | 12        | 19.05%  |
| SDDM    | 4         | 6.35%   |
| GDM     | 1         | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 36        | 57.14%  |
| en_GB | 5         | 7.94%   |
| de_DE | 5         | 7.94%   |
| es_ES | 4         | 6.35%   |
| fr_FR | 3         | 4.76%   |
| ru_RU | 2         | 3.17%   |
| pt_BR | 2         | 3.17%   |
| nl_NL | 1         | 1.59%   |
| es_VE | 1         | 1.59%   |
| en_IN | 1         | 1.59%   |
| en_DK | 1         | 1.59%   |
| ar_SA | 1         | 1.59%   |
| ar_EG | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 35        | 54.69%  |
| BIOS | 29        | 45.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 59        | 95.16%  |
| Xfs     | 1         | 1.61%   |
| Overlay | 1         | 1.61%   |
| Btrfs   | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 74.19%  |
| GPT     | 11        | 17.74%  |
| MBR     | 5         | 8.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 92.06%  |
| Yes       | 5         | 7.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 83.87%  |
| Yes       | 10        | 16.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 14.52%  |
| Gigabyte Technology | 8         | 12.9%   |
| Lenovo              | 7         | 11.29%  |
| ASUSTek Computer    | 7         | 11.29%  |
| MSI                 | 4         | 6.45%   |
| Hewlett-Packard     | 4         | 6.45%   |
| ASRock              | 3         | 4.84%   |
| Acer                | 3         | 4.84%   |
| Toshiba             | 2         | 3.23%   |
| Google              | 2         | 3.23%   |
| Unknown             | 2         | 3.23%   |
| Sony                | 1         | 1.61%   |
| Samsung Electronics | 1         | 1.61%   |
| MEGA                | 1         | 1.61%   |
| Intel               | 1         | 1.61%   |
| GPU Company         | 1         | 1.61%   |
| Fujitsu             | 1         | 1.61%   |
| Framework           | 1         | 1.61%   |
| eMachines           | 1         | 1.61%   |
| Biostar             | 1         | 1.61%   |
| AZW                 | 1         | 1.61%   |
| Apple               | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 2         | 3.23%   |
| Toshiba TECRA R840                    | 1         | 1.61%   |
| Toshiba Satellite L855                | 1         | 1.61%   |
| Sony VPCYB15AB                        | 1         | 1.61%   |
| Samsung R430/P430/R480                | 1         | 1.61%   |
| MSI MS-7B89                           | 1         | 1.61%   |
| MSI MS-7B85                           | 1         | 1.61%   |
| MSI MS-7A34                           | 1         | 1.61%   |
| MSI Modern 14 B5M                     | 1         | 1.61%   |
| MEGA G41T-M7 LGT                      | 1         | 1.61%   |
| Lenovo Z50-70 20354                   | 1         | 1.61%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 1.61%   |
| Lenovo ThinkCentre M71e 3157G6S       | 1         | 1.61%   |
| Lenovo IdeaPad S340-15API 81NC        | 1         | 1.61%   |
| Lenovo IdeaPad 5 15ALC05 82LN         | 1         | 1.61%   |
| Lenovo IdeaPad 320-15ISK 80XH         | 1         | 1.61%   |
| Lenovo C50-30 F0B1002EFR              | 1         | 1.61%   |
| Intel D946GZIS AAD66165-302           | 1         | 1.61%   |
| HP ProDesk 490 G3 MT Business PC      | 1         | 1.61%   |
| HP ProBook 450 G5                     | 1         | 1.61%   |
| HP OMEN Laptop 15-en0xxx              | 1         | 1.61%   |
| HP 750-171                            | 1         | 1.61%   |
| GPU Company GWTC116-2                 | 1         | 1.61%   |
| Google Edgar                          | 1         | 1.61%   |
| Google Delbin                         | 1         | 1.61%   |
| Gigabyte Z68AP-D3                     | 1         | 1.61%   |
| Gigabyte P31-ES3G                     | 1         | 1.61%   |
| Gigabyte H81M-S2V                     | 1         | 1.61%   |
| Gigabyte H110M-DS2V                   | 1         | 1.61%   |
| Gigabyte GA-MA770-UD3                 | 1         | 1.61%   |
| Gigabyte GA-78LMT-USB3 6.0            | 1         | 1.61%   |
| Gigabyte F2A68HM-H                    | 1         | 1.61%   |
| Gigabyte B85M-D3H                     | 1         | 1.61%   |
| Fujitsu CELSIUS W530                  | 1         | 1.61%   |
| Framework Laptop                      | 1         | 1.61%   |
| eMachines EL1852G                     | 1         | 1.61%   |
| Dell XPS 13 9380                      | 1         | 1.61%   |
| Dell XPS 13 7390                      | 1         | 1.61%   |
| Dell Vostro 15-3568                   | 1         | 1.61%   |
| Dell OptiPlex 9020                    | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 3         | 4.84%   |
| Dell Latitude          | 3         | 4.84%   |
| Dell XPS               | 2         | 3.23%   |
| Dell Inspiron          | 2         | 3.23%   |
| ASUS TUF               | 2         | 3.23%   |
| Unknown                | 2         | 3.23%   |
| Toshiba TECRA          | 1         | 1.61%   |
| Toshiba Satellite      | 1         | 1.61%   |
| Sony VPCYB15AB         | 1         | 1.61%   |
| Samsung R430           | 1         | 1.61%   |
| MSI MS-7B89            | 1         | 1.61%   |
| MSI MS-7B85            | 1         | 1.61%   |
| MSI MS-7A34            | 1         | 1.61%   |
| MSI Modern             | 1         | 1.61%   |
| MEGA G41T-M7           | 1         | 1.61%   |
| Lenovo Z50-70          | 1         | 1.61%   |
| Lenovo ThinkPad        | 1         | 1.61%   |
| Lenovo ThinkCentre     | 1         | 1.61%   |
| Lenovo C50-30          | 1         | 1.61%   |
| Intel D946GZIS         | 1         | 1.61%   |
| HP ProDesk             | 1         | 1.61%   |
| HP ProBook             | 1         | 1.61%   |
| HP OMEN                | 1         | 1.61%   |
| HP 750-171             | 1         | 1.61%   |
| GPU Company GWTC116-2  | 1         | 1.61%   |
| Google Edgar           | 1         | 1.61%   |
| Google Delbin          | 1         | 1.61%   |
| Gigabyte Z68AP-D3      | 1         | 1.61%   |
| Gigabyte P31-ES3G      | 1         | 1.61%   |
| Gigabyte H81M-S2V      | 1         | 1.61%   |
| Gigabyte H110M-DS2V    | 1         | 1.61%   |
| Gigabyte GA-MA770-UD3  | 1         | 1.61%   |
| Gigabyte GA-78LMT-USB3 | 1         | 1.61%   |
| Gigabyte F2A68HM-H     | 1         | 1.61%   |
| Gigabyte B85M-D3H      | 1         | 1.61%   |
| Fujitsu CELSIUS        | 1         | 1.61%   |
| Framework Laptop       | 1         | 1.61%   |
| eMachines EL1852G      | 1         | 1.61%   |
| Dell Vostro            | 1         | 1.61%   |
| Dell OptiPlex          | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 9         | 14.52%  |
| 2018 | 8         | 12.9%   |
| 2019 | 7         | 11.29%  |
| 2014 | 6         | 9.68%   |
| 2011 | 6         | 9.68%   |
| 2020 | 4         | 6.45%   |
| 2017 | 4         | 6.45%   |
| 2016 | 4         | 6.45%   |
| 2015 | 3         | 4.84%   |
| 2010 | 3         | 4.84%   |
| 2008 | 3         | 4.84%   |
| 2013 | 2         | 3.23%   |
| 2012 | 2         | 3.23%   |
| 2006 | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 32        | 51.61%  |
| Notebook   | 29        | 46.77%  |
| All in one | 1         | 1.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 62        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 96.77%  |
| Yes  | 2         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 22.58%  |
| 16.01-24.0 | 13        | 20.97%  |
| 8.01-16.0  | 12        | 19.35%  |
| 4.01-8.0   | 10        | 16.13%  |
| 32.01-64.0 | 8         | 12.9%   |
| 2.01-3.0   | 2         | 3.23%   |
| 1.01-2.0   | 2         | 3.23%   |
| 24.01-32.0 | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 23        | 34.85%  |
| 2.01-3.0  | 20        | 30.3%   |
| 4.01-8.0  | 9         | 13.64%  |
| 3.01-4.0  | 9         | 13.64%  |
| 0.51-1.0  | 3         | 4.55%   |
| 8.01-16.0 | 2         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 53.13%  |
| 2      | 15        | 23.44%  |
| 4      | 8         | 12.5%   |
| 3      | 5         | 7.81%   |
| 5      | 2         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 64.52%  |
| Yes       | 22        | 35.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 83.87%  |
| No        | 10        | 16.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 72.58%  |
| No        | 17        | 27.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 62.9%   |
| No        | 23        | 37.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 22.58%  |
| Germany      | 6         | 9.68%   |
| India        | 4         | 6.45%   |
| Netherlands  | 3         | 4.84%   |
| Brazil       | 3         | 4.84%   |
| Argentina    | 3         | 4.84%   |
| UK           | 2         | 3.23%   |
| Norway       | 2         | 3.23%   |
| France       | 2         | 3.23%   |
| Vietnam      | 1         | 1.61%   |
| Venezuela    | 1         | 1.61%   |
| Ukraine      | 1         | 1.61%   |
| Thailand     | 1         | 1.61%   |
| Switzerland  | 1         | 1.61%   |
| Sweden       | 1         | 1.61%   |
| Spain        | 1         | 1.61%   |
| Saudi Arabia | 1         | 1.61%   |
| Russia       | 1         | 1.61%   |
| Poland       | 1         | 1.61%   |
| Philippines  | 1         | 1.61%   |
| Nepal        | 1         | 1.61%   |
| Mexico       | 1         | 1.61%   |
| Kazakhstan   | 1         | 1.61%   |
| Iran         | 1         | 1.61%   |
| Guyana       | 1         | 1.61%   |
| Greece       | 1         | 1.61%   |
| Denmark      | 1         | 1.61%   |
| Czechia      | 1         | 1.61%   |
| Canada       | 1         | 1.61%   |
| Belgium      | 1         | 1.61%   |
| Australia    | 1         | 1.61%   |
| Albania      | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| San Justo                | 2         | 3.08%   |
| Oslo                     | 2         | 3.08%   |
| Yverdon-les-Bains        | 1         | 1.54%   |
| Wendell                  | 1         | 1.54%   |
| Weil am Rhein            | 1         | 1.54%   |
| Vineland                 | 1         | 1.54%   |
| Viby J                   | 1         | 1.54%   |
| Vasco da Gama            | 1         | 1.54%   |
| Toronto                  | 1         | 1.54%   |
| Thessaloniki             | 1         | 1.54%   |
| Stockholm                | 1         | 1.54%   |
| Stare Babice             | 1         | 1.54%   |
| Songkhla                 | 1         | 1.54%   |
| Seville                  | 1         | 1.54%   |
| Severna Park             | 1         | 1.54%   |
| Saint-Just-Saint-Rambert | 1         | 1.54%   |
| Red Oak                  | 1         | 1.54%   |
| Portsmouth               | 1         | 1.54%   |
| Pomeroy                  | 1         | 1.54%   |
| Phoenix                  | 1         | 1.54%   |
| Orenburg                 | 1         | 1.54%   |
| Ochten                   | 1         | 1.54%   |
| Mohali                   | 1         | 1.54%   |
| Milwaukee                | 1         | 1.54%   |
| Miami                    | 1         | 1.54%   |
| Melbourne                | 1         | 1.54%   |
| Lviv                     | 1         | 1.54%   |
| Luckenwalde              | 1         | 1.54%   |
| Lipa City                | 1         | 1.54%   |
| Linter                   | 1         | 1.54%   |
| Lexington                | 1         | 1.54%   |
| León                    | 1         | 1.54%   |
| Krefeld                  | 1         | 1.54%   |
| Kolkata                  | 1         | 1.54%   |
| Khobar                   | 1         | 1.54%   |
| Kathmandu                | 1         | 1.54%   |
| Isidro Casanova          | 1         | 1.54%   |
| Ilford                   | 1         | 1.54%   |
| Huntington Park          | 1         | 1.54%   |
| Hanoi                    | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 30     | 21.5%   |
| Samsung Electronics | 17        | 23     | 15.89%  |
| Seagate             | 10        | 11     | 9.35%   |
| SanDisk             | 9         | 11     | 8.41%   |
| Kingston            | 9         | 12     | 8.41%   |
| Toshiba             | 6         | 6      | 5.61%   |
| Unknown             | 4         | 4      | 3.74%   |
| SK hynix            | 4         | 4      | 3.74%   |
| Crucial             | 4         | 4      | 3.74%   |
| PNY                 | 3         | 3      | 2.8%    |
| Intel               | 3         | 4      | 2.8%    |
| Phison              | 2         | 2      | 1.87%   |
| Hitachi             | 2         | 2      | 1.87%   |
| SPCC Sol            | 1         | 1      | 0.93%   |
| Silicon Motion      | 1         | 1      | 0.93%   |
| SABRENT             | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| Maxtor              | 1         | 1      | 0.93%   |
| KIOXIA              | 1         | 1      | 0.93%   |
| Intenso             | 1         | 2      | 0.93%   |
| HFS512GD            | 1         | 1      | 0.93%   |
| China               | 1         | 1      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |
| Advantech           | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 4         | 3.39%   |
| Samsung NVMe SSD Drive 500GB     | 3         | 2.54%   |
| Kingston SA400S37240G 240GB SSD  | 3         | 2.54%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 1.69%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2         | 1.69%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.69%   |
| SK hynix NVMe SSD Drive 128GB    | 2         | 1.69%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.69%   |
| PNY CS900 240GB SSD              | 2         | 1.69%   |
| Kingston SA400S37480G 480GB SSD  | 2         | 1.69%   |
| Crucial CT1000P1SSD8 1TB         | 2         | 1.69%   |
| Crucial CT1000MX500SSD1 1TB      | 2         | 1.69%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD | 1         | 0.85%   |
| WDC WD6400AAKS-75A7B2 640GB      | 1         | 0.85%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 0.85%   |
| WDC WD5000AVCS-632DY1 500GB      | 1         | 0.85%   |
| WDC WD5000AAKX-003CA0 500GB      | 1         | 0.85%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1         | 0.85%   |
| WDC WD3200BEVT-75ZCT2 320GB      | 1         | 0.85%   |
| WDC WD3200AAJS-00YZCA0 320GB     | 1         | 0.85%   |
| WDC WD32 00AAJS-00L7A0 320GB     | 1         | 0.85%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1         | 0.85%   |
| WDC WD2500HHTZ-04N21V1 250GB     | 1         | 0.85%   |
| WDC WD2500BEVT-22ZCT0 250GB      | 1         | 0.85%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 1         | 0.85%   |
| WDC WD2003FZEX-00SRLA0 2TB       | 1         | 0.85%   |
| WDC WD1600AAJS-00PSA0 160GB      | 1         | 0.85%   |
| WDC WD1600AAJS-00M0A0 160GB      | 1         | 0.85%   |
| WDC WD140EFGX-68B0GN0 14TB       | 1         | 0.85%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 0.85%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 0.85%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 0.85%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1         | 0.85%   |
| WDC WD10EADS-00P8B0 1TB          | 1         | 0.85%   |
| WDC WD10EADS-00M2B0 1TB          | 1         | 0.85%   |
| WDC WD1003FBYX-01Y7B0 1TB        | 1         | 0.85%   |
| WDC WD My Passport 25F3 512GB    | 1         | 0.85%   |
| Unknown USB DISK 3.2 1TB         | 1         | 0.85%   |
| Unknown SD/MMC/MS PRO 64GB       | 1         | 0.85%   |
| Unknown MMC Card  64GB           | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 28     | 52.38%  |
| Seagate             | 10        | 11     | 23.81%  |
| Toshiba             | 4         | 4      | 9.52%   |
| Hitachi             | 2         | 2      | 4.76%   |
| Unknown             | 1         | 1      | 2.38%   |
| Samsung Electronics | 1         | 1      | 2.38%   |
| Maxtor              | 1         | 1      | 2.38%   |
| Intenso             | 1         | 2      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 36.36%  |
| Kingston            | 6         | 9      | 18.18%  |
| SanDisk             | 4         | 4      | 12.12%  |
| PNY                 | 3         | 3      | 9.09%   |
| Crucial             | 2         | 2      | 6.06%   |
| WDC                 | 1         | 1      | 3.03%   |
| SPCC Sol            | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |
| Advantech           | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 35        | 50     | 38.46%  |
| NVMe    | 25        | 32     | 27.47%  |
| SSD     | 24        | 39     | 26.37%  |
| Unknown | 4         | 4      | 4.4%    |
| MMC     | 3         | 3      | 3.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 82     | 55%     |
| NVMe | 25        | 31     | 31.25%  |
| SAS  | 8         | 12     | 10%     |
| MMC  | 3         | 3      | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 56     | 53.23%  |
| 0.51-1.0   | 19        | 23     | 30.65%  |
| 1.01-2.0   | 7         | 7      | 11.29%  |
| 3.01-4.0   | 2         | 2      | 3.23%   |
| 10.01-20.0 | 1         | 1      | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 17        | 26.56%  |
| 101-250        | 16        | 25%     |
| 501-1000       | 14        | 21.88%  |
| 1001-2000      | 6         | 9.38%   |
| More than 3000 | 4         | 6.25%   |
| 21-50          | 3         | 4.69%   |
| 51-100         | 3         | 4.69%   |
| 2001-3000      | 1         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 33.33%  |
| 21-50          | 11        | 16.67%  |
| 101-250        | 9         | 13.64%  |
| 251-500        | 6         | 9.09%   |
| 501-1000       | 6         | 9.09%   |
| 51-100         | 6         | 9.09%   |
| 1001-2000      | 5         | 7.58%   |
| More than 3000 | 1         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 2      | 50%     |
| Crucial CT1000P1SSD8 1TB  | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 50%     |
| Crucial | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| HDD  | 1         | 2      | 50%     |

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
| Detected | 50        | 104    | 74.63%  |
| Works    | 15        | 21     | 22.39%  |
| Malfunc  | 2         | 3      | 2.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 35        | 44.3%   |
| AMD                          | 20        | 25.32%  |
| Samsung Electronics          | 6         | 7.59%   |
| SK hynix                     | 4         | 5.06%   |
| SanDisk                      | 4         | 5.06%   |
| Kingston Technology Company  | 3         | 3.8%    |
| Toshiba America Info Systems | 2         | 2.53%   |
| Phison Electronics           | 2         | 2.53%   |
| Micron/Crucial Technology    | 2         | 2.53%   |
| Silicon Motion               | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 15.05%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 6.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 6.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 5.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 5.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 4.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.23%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.15%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.15%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.15%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 2.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.15%   |
| Intel SSD 600P Series                                                          | 2         | 2.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 2.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 2.15%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 1.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 1.08%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.08%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.08%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.08%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.08%   |
| Samsung Electronics SATA controller                                            | 1         | 1.08%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.08%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.08%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 1.08%   |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 1.08%   |
| Intel SSD 660P Series                                                          | 1         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 47        | 58.02%  |
| NVMe | 24        | 29.63%  |
| IDE  | 9         | 11.11%  |
| RAID | 1         | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 66.13%  |
| AMD    | 21        | 33.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 3.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 3.23%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2         | 3.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 3.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 3.23%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz         | 1         | 1.61%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1         | 1.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.61%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.61%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 1.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 1.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 1.61%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1         | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.61%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.61%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1         | 1.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.61%   |
| Intel Core i3-3210 CPU @ 3.20GHz            | 1         | 1.61%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.61%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.61%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1         | 1.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.61%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.61%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1         | 1.61%   |
| Intel Celeron CPU E3400 @ 2.60GHz           | 1         | 1.61%   |
| Intel Celeron CPU E3300 @ 2.50GHz           | 1         | 1.61%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 1.61%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 1.61%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz           | 1         | 1.61%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 1         | 1.61%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1         | 1.61%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 10        | 16.13%  |
| Intel Core i5           | 9         | 14.52%  |
| AMD Ryzen 7             | 8         | 12.9%   |
| Intel Celeron           | 7         | 11.29%  |
| AMD Ryzen 5             | 6         | 9.68%   |
| Intel Core i3           | 5         | 8.06%   |
| Other                   | 3         | 4.84%   |
| Intel Pentium Dual-Core | 2         | 3.23%   |
| AMD Ryzen 9             | 2         | 3.23%   |
| AMD A10                 | 2         | 3.23%   |
| Intel Xeon              | 1         | 1.61%   |
| Intel Pentium Silver    | 1         | 1.61%   |
| Intel Core 2 Quad       | 1         | 1.61%   |
| Intel Core 2            | 1         | 1.61%   |
| Intel Atom              | 1         | 1.61%   |
| AMD Phenom II X4        | 1         | 1.61%   |
| AMD FX                  | 1         | 1.61%   |
| AMD E                   | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 23        | 37.1%   |
| 2      | 23        | 37.1%   |
| 8      | 8         | 12.9%   |
| 6      | 5         | 8.06%   |
| 12     | 1         | 1.61%   |
| 3      | 1         | 1.61%   |
| 1      | 1         | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 44        | 70.97%  |
| 1      | 18        | 29.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 62        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 6         | 9.38%   |
| Unknown    | 6         | 9.38%   |
| 0x206a7    | 5         | 7.81%   |
| 0x1067a    | 5         | 7.81%   |
| 0x806ec    | 3         | 4.69%   |
| 0x806c1    | 3         | 4.69%   |
| 0x506e3    | 3         | 4.69%   |
| 0x0800820d | 3         | 4.69%   |
| 0x906e9    | 2         | 3.13%   |
| 0x806ea    | 2         | 3.13%   |
| 0x40651    | 2         | 3.13%   |
| 0x0a50000c | 2         | 3.13%   |
| 0x08701021 | 2         | 3.13%   |
| 0x08701013 | 2         | 3.13%   |
| 0x08600106 | 2         | 3.13%   |
| 0x06003106 | 2         | 3.13%   |
| 0x906c0    | 1         | 1.56%   |
| 0x706a8    | 1         | 1.56%   |
| 0x706a1    | 1         | 1.56%   |
| 0x6f2      | 1         | 1.56%   |
| 0x406e3    | 1         | 1.56%   |
| 0x306a9    | 1         | 1.56%   |
| 0x10661    | 1         | 1.56%   |
| 0x0a201204 | 1         | 1.56%   |
| 0x08608103 | 1         | 1.56%   |
| 0x08108109 | 1         | 1.56%   |
| 0x08108102 | 1         | 1.56%   |
| 0x06000852 | 1         | 1.56%   |
| 0x05000029 | 1         | 1.56%   |
| 0x010000c8 | 1         | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 12.9%   |
| Haswell       | 8         | 12.9%   |
| Zen 2         | 6         | 9.68%   |
| Zen+          | 5         | 8.06%   |
| Skylake       | 5         | 8.06%   |
| SandyBridge   | 5         | 8.06%   |
| Penryn        | 5         | 8.06%   |
| Zen 3         | 3         | 4.84%   |
| TigerLake     | 3         | 4.84%   |
| Steamroller   | 2         | 3.23%   |
| Goldmont plus | 2         | 3.23%   |
| Core          | 2         | 3.23%   |
| Unknown       | 2         | 3.23%   |
| Tremont       | 1         | 1.61%   |
| Silvermont    | 1         | 1.61%   |
| Piledriver    | 1         | 1.61%   |
| K10           | 1         | 1.61%   |
| IvyBridge     | 1         | 1.61%   |
| Bobcat        | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 44.59%  |
| AMD    | 25        | 33.78%  |
| Nvidia | 16        | 21.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 5.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3         | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.67%   |
| Intel HD Graphics 530                                                       | 2         | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.67%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 2.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.67%   |
| AMD Renoir                                                                  | 2         | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 2.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2         | 2.67%   |
| AMD Lucienne                                                                | 2         | 2.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 2.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 1.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.33%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1         | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.33%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 1.33%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 1.33%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 1.33%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1         | 1.33%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 1.33%   |
| Nvidia GF119 [GeForce 605]                                                  | 1         | 1.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.33%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 1.33%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1         | 1.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.33%   |
| Intel UHD Graphics 620                                                      | 1         | 1.33%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 1         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.33%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 1.33%   |
| Intel HD Graphics 630                                                       | 1         | 1.33%   |
| Intel HD Graphics 620                                                       | 1         | 1.33%   |
| Intel HD Graphics 520                                                       | 1         | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 37.1%   |
| 1 x AMD        | 21        | 33.87%  |
| 1 x Nvidia     | 9         | 14.52%  |
| Intel + Nvidia | 5         | 8.06%   |
| Intel + AMD    | 2         | 3.23%   |
| AMD + Nvidia   | 2         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 82.26%  |
| Proprietary | 11        | 17.74%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 41.94%  |
| 1.01-2.0   | 11        | 17.74%  |
| 0.51-1.0   | 8         | 12.9%   |
| 3.01-4.0   | 5         | 8.06%   |
| 0.01-0.5   | 5         | 8.06%   |
| 5.01-6.0   | 3         | 4.84%   |
| 7.01-8.0   | 2         | 3.23%   |
| 8.01-16.0  | 2         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 15.28%  |
| Chimei Innolux          | 8         | 11.11%  |
| AOC                     | 7         | 9.72%   |
| AU Optronics            | 6         | 8.33%   |
| Goldstar                | 5         | 6.94%   |
| BOE                     | 5         | 6.94%   |
| Ancor Communications    | 4         | 5.56%   |
| Dell                    | 3         | 4.17%   |
| Acer                    | 3         | 4.17%   |
| NEC Computers           | 2         | 2.78%   |
| LG Display              | 2         | 2.78%   |
| Lenovo                  | 2         | 2.78%   |
| BenQ                    | 2         | 2.78%   |
| Toshiba                 | 1         | 1.39%   |
| Sharp                   | 1         | 1.39%   |
| Philips                 | 1         | 1.39%   |
| PANDA                   | 1         | 1.39%   |
| Microstep               | 1         | 1.39%   |
| LG Electronics          | 1         | 1.39%   |
| Hewlett-Packard         | 1         | 1.39%   |
| CSO                     | 1         | 1.39%   |
| Chi Mei Optoelectronics | 1         | 1.39%   |
| ASUSTek Computer        | 1         | 1.39%   |
| Apple                   | 1         | 1.39%   |
| Unknown                 | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 3         | 3.95%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch            | 1         | 1.32%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1         | 1.32%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1         | 1.32%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1         | 1.32%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1         | 1.32%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 1.32%   |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1         | 1.32%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 1.32%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch    | 1         | 1.32%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch    | 1         | 1.32%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                | 1         | 1.32%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch              | 1         | 1.32%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1         | 1.32%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1         | 1.32%   |
| Microstep LCD Monitor MSI G241                                       | 1         | 1.32%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1         | 1.32%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch         | 1         | 1.32%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch         | 1         | 1.32%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 1         | 1.32%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                  | 1         | 1.32%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1         | 1.32%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1         | 1.32%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1         | 1.32%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1         | 1.32%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1         | 1.32%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1         | 1.32%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                  | 1         | 1.32%   |
| Dell S3222DGM DELD110 2560x1440 697x392mm 31.5-inch                  | 1         | 1.32%   |
| Dell 1908WFP DELF007 1440x900 408x255mm 18.9-inch                    | 1         | 1.32%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch     | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 45.71%  |
| 1366x768 (WXGA)    | 15        | 21.43%  |
| 3840x2160 (4K)     | 4         | 5.71%   |
| 2560x1440 (QHD)    | 4         | 5.71%   |
| 1280x1024 (SXGA)   | 4         | 5.71%   |
| 5760x1080          | 1         | 1.43%   |
| 2560x1080          | 1         | 1.43%   |
| 2256x1504          | 1         | 1.43%   |
| 1920x1200 (WUXGA)  | 1         | 1.43%   |
| 1680x1050 (WSXGA+) | 1         | 1.43%   |
| 1600x900 (HD+)     | 1         | 1.43%   |
| 1440x900 (WXGA+)   | 1         | 1.43%   |
| 1360x768           | 1         | 1.43%   |
| 1280x800 (WXGA)    | 1         | 1.43%   |
| 1024x768 (XGA)     | 1         | 1.43%   |
| Unknown            | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 27.54%  |
| 24      | 9         | 13.04%  |
| Unknown | 7         | 10.14%  |
| 27      | 5         | 7.25%   |
| 13      | 5         | 7.25%   |
| 23      | 4         | 5.8%    |
| 21      | 4         | 5.8%    |
| 18      | 4         | 5.8%    |
| 14      | 3         | 4.35%   |
| 17      | 2         | 2.9%    |
| 11      | 2         | 2.9%    |
| 31      | 1         | 1.45%   |
| 29      | 1         | 1.45%   |
| 22      | 1         | 1.45%   |
| 20      | 1         | 1.45%   |
| 19      | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 36.23%  |
| 501-600     | 18        | 26.09%  |
| 401-500     | 10        | 14.49%  |
| Unknown     | 7         | 10.14%  |
| 201-300     | 5         | 7.25%   |
| 601-700     | 2         | 2.9%    |
| 351-400     | 2         | 2.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46        | 68.66%  |
| 16/10   | 8         | 11.94%  |
| Unknown | 7         | 10.45%  |
| 5/4     | 3         | 4.48%   |
| 4/3     | 1         | 1.49%   |
| 3/2     | 1         | 1.49%   |
| 21/9    | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 27.14%  |
| 201-250        | 13        | 18.57%  |
| Unknown        | 7         | 10%     |
| 81-90          | 6         | 8.57%   |
| 301-350        | 6         | 8.57%   |
| 251-300        | 5         | 7.14%   |
| 141-150        | 5         | 7.14%   |
| 151-200        | 4         | 5.71%   |
| 71-80          | 2         | 2.86%   |
| 51-60          | 2         | 2.86%   |
| 351-500        | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 27        | 40.91%  |
| 121-160       | 13        | 19.7%   |
| 101-120       | 13        | 19.7%   |
| Unknown       | 7         | 10.61%  |
| 161-240       | 4         | 6.06%   |
| More than 240 | 2         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 47        | 75.81%  |
| 2     | 13        | 20.97%  |
| 3     | 2         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 35        | 38.04%  |
| Intel                    | 26        | 28.26%  |
| Qualcomm Atheros         | 12        | 13.04%  |
| MediaTek                 | 4         | 4.35%   |
| Broadcom                 | 3         | 3.26%   |
| Marvell Technology Group | 2         | 2.17%   |
| Xiaomi                   | 1         | 1.09%   |
| TP-Link                  | 1         | 1.09%   |
| T & A Mobile Phones      | 1         | 1.09%   |
| Ralink Technology        | 1         | 1.09%   |
| Linksys                  | 1         | 1.09%   |
| Huawei Technologies      | 1         | 1.09%   |
| Dell                     | 1         | 1.09%   |
| D-Link System            | 1         | 1.09%   |
| Belkin Components        | 1         | 1.09%   |
| ASIX Electronics         | 1         | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 25.69%  |
| Intel Wi-Fi 6 AX200                                               | 7         | 6.42%   |
| Intel I211 Gigabit Network Connection                             | 4         | 3.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 2.75%   |
| Intel Wireless 3165                                               | 3         | 2.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.83%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.83%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.83%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.83%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.92%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.92%   |
| T & A Mobile Phones A509DL                                        | 1         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.92%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.92%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.92%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.92%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.92%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 1         | 0.92%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.92%   |
| Intel Wireless-AC 9260                                            | 1         | 0.92%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 39.22%  |
| Realtek Semiconductor | 10        | 19.61%  |
| Qualcomm Atheros      | 10        | 19.61%  |
| MediaTek              | 4         | 7.84%   |
| Broadcom              | 3         | 5.88%   |
| Ralink Technology     | 1         | 1.96%   |
| Linksys               | 1         | 1.96%   |
| D-Link System         | 1         | 1.96%   |
| Belkin Components     | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 7         | 13.46%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                              | 3         | 5.77%   |
| Intel Wireless 3165                                                                     | 3         | 5.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 2         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                              | 2         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                          | 2         | 3.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                 | 2         | 3.85%   |
| Intel Wi-Fi 6 AX201                                                                     | 2         | 3.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1         | 1.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                | 1         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1         | 1.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                         | 1         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 1         | 1.92%   |
| Realtek RTL8187 Wireless Adapter                                                        | 1         | 1.92%   |
| Realtek 802.11n WLAN Adapter                                                            | 1         | 1.92%   |
| Ralink MT7601U Wireless Adapter                                                         | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 1         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1         | 1.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                        | 1         | 1.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                           | 1         | 1.92%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                                      | 1         | 1.92%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                     | 1         | 1.92%   |
| Intel Wireless-AC 9260                                                                  | 1         | 1.92%   |
| Intel Wireless 8265 / 8275                                                              | 1         | 1.92%   |
| Intel Wireless 8260                                                                     | 1         | 1.92%   |
| Intel Wireless 7265                                                                     | 1         | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 1         | 1.92%   |
| Intel Wi-Fi 6 AX201 160MHz                                                              | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 1         | 1.92%   |
| Intel Centrino Ultimate-N 6300                                                          | 1         | 1.92%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                           | 1         | 1.92%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]              | 1         | 1.92%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                             | 1         | 1.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1         | 1.92%   |
| Broadcom BCM4311 802.11b/g WLAN                                                         | 1         | 1.92%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 54.55%  |
| Intel                    | 14        | 25.45%  |
| Qualcomm Atheros         | 4         | 7.27%   |
| Marvell Technology Group | 2         | 3.64%   |
| Xiaomi                   | 1         | 1.82%   |
| TP-Link                  | 1         | 1.82%   |
| Huawei Technologies      | 1         | 1.82%   |
| Broadcom                 | 1         | 1.82%   |
| ASIX Electronics         | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 50.91%  |
| Intel I211 Gigabit Network Connection                             | 4         | 7.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 3.64%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.64%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.82%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.82%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.82%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.82%   |
| Huawei STK-L21                                                    | 1         | 1.82%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 52        | 52%     |
| WiFi     | 46        | 46%     |
| Modem    | 1         | 1%      |
| Unknown  | 1         | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 54.55%  |
| Ethernet | 30        | 45.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 32        | 51.61%  |
| 2     | 27        | 43.55%  |
| 3     | 2         | 3.23%   |
| 0     | 1         | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 73.02%  |
| Yes  | 17        | 26.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 43.9%   |
| Qualcomm Atheros Communications | 4         | 9.76%   |
| Realtek Semiconductor           | 3         | 7.32%   |
| Cambridge Silicon Radio         | 3         | 7.32%   |
| Broadcom                        | 3         | 7.32%   |
| MediaTek                        | 2         | 4.88%   |
| Lite-On Technology              | 2         | 4.88%   |
| Toshiba                         | 1         | 2.44%   |
| IMC Networks                    | 1         | 2.44%   |
| Foxconn / Hon Hai               | 1         | 2.44%   |
| Dell                            | 1         | 2.44%   |
| ASUSTek Computer                | 1         | 2.44%   |
| Apple                           | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 14.63%  |
| Intel AX200 Bluetooth                               | 6         | 14.63%  |
| Intel AX201 Bluetooth                               | 3         | 7.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 7.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.88%   |
| MediaTek Wireless_Device                            | 2         | 4.88%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.44%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.44%   |
| Realtek Bluetooth Radio                             | 1         | 2.44%   |
| Lite-On Wireless_Device                             | 1         | 2.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.44%   |
| Intel AX210 Bluetooth                               | 1         | 2.44%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.44%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.44%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.44%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 2.44%   |
| Broadcom BCM92045B3 ROM                             | 1         | 2.44%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.44%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 41        | 46.07%  |
| AMD                 | 26        | 29.21%  |
| Nvidia              | 13        | 14.61%  |
| C-Media Electronics | 2         | 2.25%   |
| Blue Microphones    | 2         | 2.25%   |
| Texas Instruments   | 1         | 1.12%   |
| Tenx Technology     | 1         | 1.12%   |
| Samsung Electronics | 1         | 1.12%   |
| Cooler Master       | 1         | 1.12%   |
| Conexant Systems    | 1         | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 7.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 5.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 4.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 4.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.68%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 2.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.79%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.79%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.79%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2         | 1.79%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.79%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.79%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.79%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1         | 0.89%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.89%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.89%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.89%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.89%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.89%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.89%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 32%     |
| SK hynix            | 3         | 12%     |
| Crucial             | 3         | 12%     |
| Unknown             | 2         | 8%      |
| Micron Technology   | 2         | 8%      |
| A-DATA Technology   | 2         | 8%      |
| Transcend           | 1         | 4%      |
| Team                | 1         | 4%      |
| Patriot             | 1         | 4%      |
| G.Skill             | 1         | 4%      |
| Corsair             | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 4%      |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 4%      |
| Transcend RAM JM1333KLN-4G 4GB DIMM 1600MT/s                     | 1         | 4%      |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 4%      |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 4%      |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4%      |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4%      |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 4%      |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 4%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4%      |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4%      |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4%      |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s              | 1         | 4%      |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4%      |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 4%      |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s              | 1         | 4%      |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 4%      |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 4%      |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 4%      |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 4%      |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 4%      |
| Crucial RAM BLS8G4D32AESBK.M8FE 8GB DIMM DDR4 3200MT/s           | 1         | 4%      |
| Corsair RAM CMK16GX4M2Z3200C16 8192MB DIMM DDR4 3200MT/s         | 1         | 4%      |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 4%      |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 45.45%  |
| DDR3   | 6         | 27.27%  |
| LPDDR3 | 3         | 13.64%  |
| LPDDR4 | 1         | 4.55%   |
| DDR2   | 1         | 4.55%   |
| DDR    | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 52.38%  |
| DIMM         | 7         | 33.33%  |
| Row Of Chips | 3         | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 9         | 40.91%  |
| 4096  | 6         | 27.27%  |
| 16384 | 4         | 18.18%  |
| 32768 | 1         | 4.55%   |
| 2048  | 1         | 4.55%   |
| 1024  | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 6         | 26.09%  |
| 1600    | 5         | 21.74%  |
| 2133    | 4         | 17.39%  |
| 2400    | 2         | 8.7%    |
| 4267    | 1         | 4.35%   |
| 2667    | 1         | 4.35%   |
| 1867    | 1         | 4.35%   |
| 1333    | 1         | 4.35%   |
| 667     | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

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
| Logitech                               | 5         | 14.29%  |
| Realtek Semiconductor                  | 4         | 11.43%  |
| Quanta                                 | 4         | 11.43%  |
| Sunplus Innovation Technology          | 3         | 8.57%   |
| Microdia                               | 3         | 8.57%   |
| IMC Networks                           | 2         | 5.71%   |
| Chicony Electronics                    | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| Acer                                   | 2         | 5.71%   |
| Z-Star Microelectronics                | 1         | 2.86%   |
| Syntek                                 | 1         | 2.86%   |
| MacroSilicon                           | 1         | 2.86%   |
| LG Electronics                         | 1         | 2.86%   |
| Importek                               | 1         | 2.86%   |
| Hewlett-Packard                        | 1         | 2.86%   |
| Apple                                  | 1         | 2.86%   |
| A4Tech                                 | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                    | 2         | 5.71%   |
| Quanta HD User Facing                                           | 2         | 5.71%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 5.71%   |
| Logitech Webcam C270                                            | 2         | 5.71%   |
| Z-Star Webcam                                                   | 1         | 2.86%   |
| Syntek Integrated Camera                                        | 1         | 2.86%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 2.86%   |
| Realtek Laptop Camera                                           | 1         | 2.86%   |
| Realtek Integrated Webcam_HD                                    | 1         | 2.86%   |
| Realtek Integrated Webcam                                       | 1         | 2.86%   |
| Realtek HD WebCam                                               | 1         | 2.86%   |
| Quanta VGA WebCam                                               | 1         | 2.86%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 2.86%   |
| Microdia USB 2.0 Camera                                         | 1         | 2.86%   |
| MacroSilicon ShadowCast                                         | 1         | 2.86%   |
| Logitech HD Pro Webcam C920                                     | 1         | 2.86%   |
| Logitech C922 Pro Stream Webcam                                 | 1         | 2.86%   |
| Logitech C920 PRO HD Webcam                                     | 1         | 2.86%   |
| LG Optimus (Various Models) MTP Mode                            | 1         | 2.86%   |
| Importek TOSHIBA Web Camera - HD                                | 1         | 2.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 2.86%   |
| IMC Networks Integrated Camera                                  | 1         | 2.86%   |
| HP Webcam HD 2300                                               | 1         | 2.86%   |
| Chicony Sony Visual Communication Camera                        | 1         | 2.86%   |
| Chicony EasyCamera                                              | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.86%   |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 2.86%   |
| Acer LENOVO LBG 720P CAM                                        | 1         | 2.86%   |
| Acer Lenovo EasyCamera                                          | 1         | 2.86%   |
| A4Tech FHD 1080P PC Camera                                      | 1         | 2.86%   |

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
| 0     | 48        | 76.19%  |
| 1     | 9         | 14.29%  |
| 2     | 5         | 7.94%   |
| 3     | 1         | 1.59%   |

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


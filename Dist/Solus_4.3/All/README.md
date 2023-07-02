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

Total: 112

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3420               | Notebook    | [730bdb05fe](https://linux-hardware.org/?probe=730bdb05fe) | Jun 23, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [137d8d57ee](https://linux-hardware.org/?probe=137d8d57ee) | May 18, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [299733170c](https://linux-hardware.org/?probe=299733170c) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [dbf0b56c64](https://linux-hardware.org/?probe=dbf0b56c64) | Mar 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [db0f4c6df3](https://linux-hardware.org/?probe=db0f4c6df3) | Mar 16, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [73a3777352](https://linux-hardware.org/?probe=73a3777352) | Mar 06, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [da7b0aca1f](https://linux-hardware.org/?probe=da7b0aca1f) | Feb 03, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [10f14c4cbd](https://linux-hardware.org/?probe=10f14c4cbd) | Jan 23, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [13ce0469f3](https://linux-hardware.org/?probe=13ce0469f3) | Jan 23, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [141874b125](https://linux-hardware.org/?probe=141874b125) | Jan 08, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [55db2decf3](https://linux-hardware.org/?probe=55db2decf3) | Jan 07, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [fa5bdcfc4c](https://linux-hardware.org/?probe=fa5bdcfc4c) | Jan 06, 2023 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [acbd8114d2](https://linux-hardware.org/?probe=acbd8114d2) | Jan 04, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [d89c5688d2](https://linux-hardware.org/?probe=d89c5688d2) | Jan 03, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [3fb1b015e3](https://linux-hardware.org/?probe=3fb1b015e3) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [cdb2bf4725](https://linux-hardware.org/?probe=cdb2bf4725) | Jan 02, 2023 |
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
| 6.0.11-225.current  | 8         | 10%     |
| 5.15.32-213.current | 8         | 10%     |
| 5.14.21-210.current | 7         | 8.75%   |
| 5.13.1-187.current  | 7         | 8.75%   |
| 5.15.50-216.current | 6         | 7.5%    |
| 5.14.16-205.current | 6         | 7.5%    |
| 6.1.5-229.current   | 5         | 6.25%   |
| 5.13.6-190.current  | 5         | 6.25%   |
| 5.13.12-193.current | 5         | 6.25%   |
| 5.15.77-219.current | 3         | 3.75%   |
| 5.15.43-215.current | 2         | 2.5%    |
| 5.15.37-214.current | 2         | 2.5%    |
| 5.15.30-212.current | 2         | 2.5%    |
| 5.15.26-211.current | 2         | 2.5%    |
| 5.14.14-202.current | 2         | 2.5%    |
| 6.2.14-232.current  | 1         | 1.25%   |
| 6.1.2-228.current   | 1         | 1.25%   |
| 5.15.68-218.current | 1         | 1.25%   |
| 5.15.61-217.current | 1         | 1.25%   |
| 5.14.7-198.current  | 1         | 1.25%   |
| 5.14.16-204.current | 1         | 1.25%   |
| 5.14.15-203.current | 1         | 1.25%   |
| 5.14.12-201.current | 1         | 1.25%   |
| 5.13.8-191.current  | 1         | 1.25%   |
| 5.13.15-194.current | 1         | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.11  | 8         | 10%     |
| 5.15.32 | 8         | 10%     |
| 5.14.21 | 7         | 8.75%   |
| 5.14.16 | 7         | 8.75%   |
| 5.13.1  | 7         | 8.75%   |
| 5.15.50 | 6         | 7.5%    |
| 6.1.5   | 5         | 6.25%   |
| 5.13.6  | 5         | 6.25%   |
| 5.13.12 | 5         | 6.25%   |
| 5.15.77 | 3         | 3.75%   |
| 5.15.43 | 2         | 2.5%    |
| 5.15.37 | 2         | 2.5%    |
| 5.15.30 | 2         | 2.5%    |
| 5.15.26 | 2         | 2.5%    |
| 5.14.14 | 2         | 2.5%    |
| 6.2.14  | 1         | 1.25%   |
| 6.1.2   | 1         | 1.25%   |
| 5.15.68 | 1         | 1.25%   |
| 5.15.61 | 1         | 1.25%   |
| 5.14.7  | 1         | 1.25%   |
| 5.14.15 | 1         | 1.25%   |
| 5.14.12 | 1         | 1.25%   |
| 5.13.8  | 1         | 1.25%   |
| 5.13.15 | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 26        | 32.91%  |
| 5.14    | 19        | 24.05%  |
| 5.13    | 19        | 24.05%  |
| 6.0     | 8         | 10.13%  |
| 6.1     | 6         | 7.59%   |
| 6.2     | 1         | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 73        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 42        | 56.76%  |
| GNOME   | 9         | 12.16%  |
| MATE    | 7         | 9.46%   |
| KDE5    | 7         | 9.46%   |
| Unknown | 5         | 6.76%   |
| KDE     | 4         | 5.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 72        | 98.63%  |
| Wayland | 1         | 1.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 71.62%  |
| LightDM | 13        | 17.57%  |
| SDDM    | 4         | 5.41%   |
| GDM     | 4         | 5.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 40        | 54.05%  |
| de_DE | 7         | 9.46%   |
| en_GB | 5         | 6.76%   |
| es_ES | 4         | 5.41%   |
| ru_RU | 3         | 4.05%   |
| ro_RO | 3         | 4.05%   |
| fr_FR | 3         | 4.05%   |
| pt_BR | 2         | 2.7%    |
| nl_NL | 1         | 1.35%   |
| fi_FI | 1         | 1.35%   |
| es_VE | 1         | 1.35%   |
| en_IN | 1         | 1.35%   |
| en_DK | 1         | 1.35%   |
| ar_SA | 1         | 1.35%   |
| ar_EG | 1         | 1.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 41        | 54.67%  |
| BIOS | 34        | 45.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 94.52%  |
| Overlay | 2         | 2.74%   |
| Xfs     | 1         | 1.37%   |
| Btrfs   | 1         | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 68.92%  |
| GPT     | 14        | 18.92%  |
| MBR     | 9         | 12.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 90.54%  |
| Yes       | 7         | 9.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 83.56%  |
| Yes       | 12        | 16.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 11        | 15.07%  |
| Gigabyte Technology | 10        | 13.7%   |
| Lenovo              | 9         | 12.33%  |
| ASUSTek Computer    | 9         | 12.33%  |
| ASRock              | 6         | 8.22%   |
| MSI                 | 4         | 5.48%   |
| Hewlett-Packard     | 4         | 5.48%   |
| Acer                | 3         | 4.11%   |
| Toshiba             | 2         | 2.74%   |
| Google              | 2         | 2.74%   |
| Unknown             | 2         | 2.74%   |
| Sony                | 1         | 1.37%   |
| Samsung Electronics | 1         | 1.37%   |
| MEGA                | 1         | 1.37%   |
| Intel               | 1         | 1.37%   |
| GPU Company         | 1         | 1.37%   |
| Fujitsu             | 1         | 1.37%   |
| Framework           | 1         | 1.37%   |
| eMachines           | 1         | 1.37%   |
| Biostar             | 1         | 1.37%   |
| AZW                 | 1         | 1.37%   |
| Apple               | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 2         | 2.74%   |
| Toshiba TECRA R840                    | 1         | 1.37%   |
| Toshiba Satellite L855                | 1         | 1.37%   |
| Sony VPCYB15AB                        | 1         | 1.37%   |
| Samsung R430/P430/R480                | 1         | 1.37%   |
| MSI MS-7B89                           | 1         | 1.37%   |
| MSI MS-7B85                           | 1         | 1.37%   |
| MSI MS-7A34                           | 1         | 1.37%   |
| MSI Modern 14 B5M                     | 1         | 1.37%   |
| MEGA G41T-M7 LGT                      | 1         | 1.37%   |
| Lenovo Z50-70 20354                   | 1         | 1.37%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 1.37%   |
| Lenovo ThinkPad T14 Gen 1 20S00013FR  | 1         | 1.37%   |
| Lenovo ThinkCentre M71e 3157G6S       | 1         | 1.37%   |
| Lenovo IdeaPad S340-15API 81NC        | 1         | 1.37%   |
| Lenovo IdeaPad 530S-14ARR 81H1        | 1         | 1.37%   |
| Lenovo IdeaPad 5 15ALC05 82LN         | 1         | 1.37%   |
| Lenovo IdeaPad 320-15ISK 80XH         | 1         | 1.37%   |
| Lenovo C50-30 F0B1002EFR              | 1         | 1.37%   |
| Intel D946GZIS AAD66165-302           | 1         | 1.37%   |
| HP ProDesk 490 G3 MT Business PC      | 1         | 1.37%   |
| HP ProBook 450 G5                     | 1         | 1.37%   |
| HP OMEN Laptop 15-en0xxx              | 1         | 1.37%   |
| HP 750-171                            | 1         | 1.37%   |
| GPU Company GWTC116-2                 | 1         | 1.37%   |
| Google Edgar                          | 1         | 1.37%   |
| Google Delbin                         | 1         | 1.37%   |
| Gigabyte Z68AP-D3                     | 1         | 1.37%   |
| Gigabyte P31-ES3G                     | 1         | 1.37%   |
| Gigabyte H81M-S2V                     | 1         | 1.37%   |
| Gigabyte H110M-DS2V                   | 1         | 1.37%   |
| Gigabyte GA-MA770-UD3                 | 1         | 1.37%   |
| Gigabyte GA-78LMT-USB3 6.0            | 1         | 1.37%   |
| Gigabyte F2A68HM-H                    | 1         | 1.37%   |
| Gigabyte EP45-UD3P                    | 1         | 1.37%   |
| Gigabyte B85M-D3H                     | 1         | 1.37%   |
| Gigabyte B550M AORUS PRO-P            | 1         | 1.37%   |
| Fujitsu CELSIUS W530                  | 1         | 1.37%   |
| Framework Laptop                      | 1         | 1.37%   |
| eMachines EL1852G                     | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 4         | 5.48%   |
| Dell Latitude          | 4         | 5.48%   |
| Dell Inspiron          | 3         | 4.11%   |
| ASUS TUF               | 3         | 4.11%   |
| Lenovo ThinkPad        | 2         | 2.74%   |
| Dell XPS               | 2         | 2.74%   |
| Unknown                | 2         | 2.74%   |
| Toshiba TECRA          | 1         | 1.37%   |
| Toshiba Satellite      | 1         | 1.37%   |
| Sony VPCYB15AB         | 1         | 1.37%   |
| Samsung R430           | 1         | 1.37%   |
| MSI MS-7B89            | 1         | 1.37%   |
| MSI MS-7B85            | 1         | 1.37%   |
| MSI MS-7A34            | 1         | 1.37%   |
| MSI Modern             | 1         | 1.37%   |
| MEGA G41T-M7           | 1         | 1.37%   |
| Lenovo Z50-70          | 1         | 1.37%   |
| Lenovo ThinkCentre     | 1         | 1.37%   |
| Lenovo C50-30          | 1         | 1.37%   |
| Intel D946GZIS         | 1         | 1.37%   |
| HP ProDesk             | 1         | 1.37%   |
| HP ProBook             | 1         | 1.37%   |
| HP OMEN                | 1         | 1.37%   |
| HP 750-171             | 1         | 1.37%   |
| GPU Company GWTC116-2  | 1         | 1.37%   |
| Google Edgar           | 1         | 1.37%   |
| Google Delbin          | 1         | 1.37%   |
| Gigabyte Z68AP-D3      | 1         | 1.37%   |
| Gigabyte P31-ES3G      | 1         | 1.37%   |
| Gigabyte H81M-S2V      | 1         | 1.37%   |
| Gigabyte H110M-DS2V    | 1         | 1.37%   |
| Gigabyte GA-MA770-UD3  | 1         | 1.37%   |
| Gigabyte GA-78LMT-USB3 | 1         | 1.37%   |
| Gigabyte F2A68HM-H     | 1         | 1.37%   |
| Gigabyte EP45-UD3P     | 1         | 1.37%   |
| Gigabyte B85M-D3H      | 1         | 1.37%   |
| Gigabyte B550M         | 1         | 1.37%   |
| Fujitsu CELSIUS        | 1         | 1.37%   |
| Framework Laptop       | 1         | 1.37%   |
| eMachines EL1852G      | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 10        | 13.7%   |
| 2018 | 10        | 13.7%   |
| 2020 | 7         | 9.59%   |
| 2019 | 7         | 9.59%   |
| 2014 | 7         | 9.59%   |
| 2017 | 6         | 8.22%   |
| 2011 | 6         | 8.22%   |
| 2016 | 4         | 5.48%   |
| 2015 | 4         | 5.48%   |
| 2008 | 4         | 5.48%   |
| 2010 | 3         | 4.11%   |
| 2013 | 2         | 2.74%   |
| 2012 | 2         | 2.74%   |
| 2006 | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 39        | 53.42%  |
| Notebook   | 33        | 45.21%  |
| All in one | 1         | 1.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 73        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 97.26%  |
| Yes  | 2         | 2.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 17        | 23.29%  |
| 3.01-4.0   | 15        | 20.55%  |
| 4.01-8.0   | 13        | 17.81%  |
| 8.01-16.0  | 12        | 16.44%  |
| 32.01-64.0 | 10        | 13.7%   |
| 24.01-32.0 | 2         | 2.74%   |
| 2.01-3.0   | 2         | 2.74%   |
| 1.01-2.0   | 2         | 2.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 27        | 34.62%  |
| 2.01-3.0  | 23        | 29.49%  |
| 4.01-8.0  | 11        | 14.1%   |
| 3.01-4.0  | 11        | 14.1%   |
| 8.01-16.0 | 3         | 3.85%   |
| 0.51-1.0  | 3         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 51.32%  |
| 2      | 16        | 21.05%  |
| 4      | 11        | 14.47%  |
| 3      | 6         | 7.89%   |
| 5      | 3         | 3.95%   |
| 6      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 67.57%  |
| Yes       | 24        | 32.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 84.93%  |
| No        | 11        | 15.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 73.97%  |
| No        | 19        | 26.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 63.51%  |
| No        | 27        | 36.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 21.92%  |
| Germany      | 8         | 10.96%  |
| India        | 4         | 5.48%   |
| Brazil       | 4         | 5.48%   |
| Russia       | 3         | 4.11%   |
| Romania      | 3         | 4.11%   |
| Netherlands  | 3         | 4.11%   |
| Argentina    | 3         | 4.11%   |
| UK           | 2         | 2.74%   |
| Norway       | 2         | 2.74%   |
| France       | 2         | 2.74%   |
| Vietnam      | 1         | 1.37%   |
| Venezuela    | 1         | 1.37%   |
| Ukraine      | 1         | 1.37%   |
| Thailand     | 1         | 1.37%   |
| Switzerland  | 1         | 1.37%   |
| Sweden       | 1         | 1.37%   |
| Spain        | 1         | 1.37%   |
| Saudi Arabia | 1         | 1.37%   |
| Poland       | 1         | 1.37%   |
| Philippines  | 1         | 1.37%   |
| Nepal        | 1         | 1.37%   |
| Mexico       | 1         | 1.37%   |
| Kazakhstan   | 1         | 1.37%   |
| Iran         | 1         | 1.37%   |
| Guyana       | 1         | 1.37%   |
| Greece       | 1         | 1.37%   |
| Finland      | 1         | 1.37%   |
| Denmark      | 1         | 1.37%   |
| Czechia      | 1         | 1.37%   |
| Canada       | 1         | 1.37%   |
| Belgium      | 1         | 1.37%   |
| Australia    | 1         | 1.37%   |
| Albania      | 1         | 1.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Constanța               | 3         | 3.9%    |
| San Justo                | 2         | 2.6%    |
| Oslo                     | 2         | 2.6%    |
| Yverdon-les-Bains        | 1         | 1.3%    |
| Wendell                  | 1         | 1.3%    |
| Weil am Rhein            | 1         | 1.3%    |
| Warrensburg              | 1         | 1.3%    |
| Vineland                 | 1         | 1.3%    |
| Viby J                   | 1         | 1.3%    |
| Vasco da Gama            | 1         | 1.3%    |
| Uberlândia              | 1         | 1.3%    |
| Toronto                  | 1         | 1.3%    |
| Thessaloniki             | 1         | 1.3%    |
| Stockholm                | 1         | 1.3%    |
| Stare Babice             | 1         | 1.3%    |
| Songkhla                 | 1         | 1.3%    |
| Seville                  | 1         | 1.3%    |
| Severna Park             | 1         | 1.3%    |
| Saint-Just-Saint-Rambert | 1         | 1.3%    |
| Red Oak                  | 1         | 1.3%    |
| Portsmouth               | 1         | 1.3%    |
| Pomeroy                  | 1         | 1.3%    |
| Phoenix                  | 1         | 1.3%    |
| Perm                     | 1         | 1.3%    |
| Orenburg                 | 1         | 1.3%    |
| Ochten                   | 1         | 1.3%    |
| Mohali                   | 1         | 1.3%    |
| Milwaukee                | 1         | 1.3%    |
| Miami                    | 1         | 1.3%    |
| Melbourne                | 1         | 1.3%    |
| Mainz                    | 1         | 1.3%    |
| Lviv                     | 1         | 1.3%    |
| Luckenwalde              | 1         | 1.3%    |
| Lübeck                  | 1         | 1.3%    |
| Lohja                    | 1         | 1.3%    |
| Lipa City                | 1         | 1.3%    |
| Linter                   | 1         | 1.3%    |
| Lexington                | 1         | 1.3%    |
| León                    | 1         | 1.3%    |
| Krefeld                  | 1         | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 26        | 35     | 19.55%  |
| Samsung Electronics         | 20        | 30     | 15.04%  |
| Seagate                     | 13        | 16     | 9.77%   |
| SanDisk                     | 11        | 13     | 8.27%   |
| Kingston                    | 10        | 13     | 7.52%   |
| Toshiba                     | 6         | 6      | 4.51%   |
| SK hynix                    | 6         | 6      | 4.51%   |
| Crucial                     | 6         | 6      | 4.51%   |
| Unknown                     | 4         | 4      | 3.01%   |
| Intel                       | 4         | 5      | 3.01%   |
| PNY                         | 3         | 3      | 2.26%   |
| Kingston Technology Company | 3         | 3      | 2.26%   |
| Silicon Motion              | 2         | 2      | 1.5%    |
| Phison                      | 2         | 2      | 1.5%    |
| Hitachi                     | 2         | 2      | 1.5%    |
| A-DATA Technology           | 2         | 2      | 1.5%    |
| SPCC Sol                    | 1         | 1      | 0.75%   |
| SABRENT                     | 1         | 1      | 0.75%   |
| Phison Electronics          | 1         | 1      | 0.75%   |
| Patriot                     | 1         | 1      | 0.75%   |
| Micron Technology           | 1         | 1      | 0.75%   |
| Maxtor                      | 1         | 1      | 0.75%   |
| KIOXIA                      | 1         | 1      | 0.75%   |
| Intenso                     | 1         | 2      | 0.75%   |
| HFS512GD                    | 1         | 1      | 0.75%   |
| Emtec                       | 1         | 1      | 0.75%   |
| China                       | 1         | 1      | 0.75%   |
| Apple                       | 1         | 1      | 0.75%   |
| Advantech                   | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB             | 5         | 3.42%   |
| Seagate ST4000DM004-2CV104 4TB        | 3         | 2.05%   |
| Seagate ST2000DM006-2DM164 2TB        | 3         | 2.05%   |
| Samsung NVMe SSD Drive 500GB          | 3         | 2.05%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 2.05%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 1.37%   |
| WDC WD10EZEX-08M2NA0 1TB              | 2         | 1.37%   |
| Toshiba DT01ACA050 500GB              | 2         | 1.37%   |
| SK hynix NVMe SSD Drive 128GB         | 2         | 1.37%   |
| SanDisk NVMe SSD Drive 256GB          | 2         | 1.37%   |
| PNY CS900 240GB SSD                   | 2         | 1.37%   |
| Kingston Company A2000 NVMe SSD 250GB | 2         | 1.37%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 1.37%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 1.37%   |
| Crucial CT1000MX500SSD1 1TB           | 2         | 1.37%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD      | 1         | 0.68%   |
| WDC WD6400AAKS-75A7B2 640GB           | 1         | 0.68%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 0.68%   |
| WDC WD5000AVCS-632DY1 500GB           | 1         | 0.68%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 0.68%   |
| WDC WD40EZRZ-00GXCB0 4TB              | 1         | 0.68%   |
| WDC WD3200BEVT-75ZCT2 320GB           | 1         | 0.68%   |
| WDC WD3200AAJS-00YZCA0 320GB          | 1         | 0.68%   |
| WDC WD32 00AAJS-00L7A0 320GB          | 1         | 0.68%   |
| WDC WD3000GLFS-01F8U0 304GB           | 1         | 0.68%   |
| WDC WD2500HHTZ-04N21V1 250GB          | 1         | 0.68%   |
| WDC WD2500BEVT-22ZCT0 250GB           | 1         | 0.68%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 0.68%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 0.68%   |
| WDC WD2003FZEX-00SRLA0 2TB            | 1         | 0.68%   |
| WDC WD1600AAJS-00PSA0 160GB           | 1         | 0.68%   |
| WDC WD1600AAJS-00M0A0 160GB           | 1         | 0.68%   |
| WDC WD140EFGX-68B0GN0 14TB            | 1         | 0.68%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 0.68%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.68%   |
| WDC WD10SPSX-00A6WT0 1TB              | 1         | 0.68%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 0.68%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 0.68%   |
| WDC WD10EZEX-21WN4A0 1TB              | 1         | 0.68%   |
| WDC WD10EADS-00P8B0 1TB               | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 33     | 51.02%  |
| Seagate             | 13        | 16     | 26.53%  |
| Toshiba             | 4         | 4      | 8.16%   |
| Samsung Electronics | 2         | 2      | 4.08%   |
| Hitachi             | 2         | 2      | 4.08%   |
| Unknown             | 1         | 1      | 2.04%   |
| Maxtor              | 1         | 1      | 2.04%   |
| Intenso             | 1         | 2      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 20     | 33.33%  |
| Kingston            | 7         | 10     | 16.67%  |
| SanDisk             | 4         | 4      | 9.52%   |
| Crucial             | 4         | 4      | 9.52%   |
| PNY                 | 3         | 3      | 7.14%   |
| WDC                 | 1         | 1      | 2.38%   |
| SPCC Sol            | 1         | 1      | 2.38%   |
| SK hynix            | 1         | 1      | 2.38%   |
| Patriot             | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| Emtec               | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| Apple               | 1         | 1      | 2.38%   |
| Advantech           | 1         | 1      | 2.38%   |
| A-DATA Technology   | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 40        | 61     | 36.36%  |
| NVMe    | 32        | 43     | 29.09%  |
| SSD     | 31        | 51     | 28.18%  |
| Unknown | 4         | 4      | 3.64%   |
| MMC     | 3         | 3      | 2.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 104    | 54.17%  |
| NVMe | 32        | 42     | 33.33%  |
| SAS  | 9         | 13     | 9.38%   |
| MMC  | 3         | 3      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 66     | 50.67%  |
| 0.51-1.0   | 22        | 28     | 29.33%  |
| 1.01-2.0   | 9         | 10     | 12%     |
| 3.01-4.0   | 4         | 5      | 5.33%   |
| 10.01-20.0 | 1         | 1      | 1.33%   |
| 4.01-10.0  | 1         | 2      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 26.67%  |
| 251-500        | 18        | 24%     |
| 501-1000       | 15        | 20%     |
| 1001-2000      | 8         | 10.67%  |
| More than 3000 | 5         | 6.67%   |
| 21-50          | 3         | 4%      |
| 51-100         | 3         | 4%      |
| 2001-3000      | 2         | 2.67%   |
| Unknown        | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 23        | 29.49%  |
| 21-50          | 13        | 16.67%  |
| 101-250        | 9         | 11.54%  |
| 1001-2000      | 9         | 11.54%  |
| 51-100         | 8         | 10.26%  |
| 251-500        | 7         | 8.97%   |
| 501-1000       | 7         | 8.97%   |
| More than 3000 | 1         | 1.28%   |
| Unknown        | 1         | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB  | 1         | 1      | 33.33%  |
| Seagate ST9320325AS 320GB | 1         | 2      | 33.33%  |
| Crucial CT1000P1SSD8 1TB  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 2      | 33.33%  |
| Crucial | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 3      | 66.67%  |
| NVMe | 1         | 1      | 33.33%  |

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
| Detected | 56        | 125    | 69.14%  |
| Works    | 22        | 33     | 27.16%  |
| Malfunc  | 3         | 4      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 39.39%  |
| AMD                          | 26        | 26.26%  |
| SanDisk                      | 6         | 6.06%   |
| Samsung Electronics          | 6         | 6.06%   |
| Kingston Technology Company  | 6         | 6.06%   |
| SK hynix                     | 5         | 5.05%   |
| Phison Electronics           | 3         | 3.03%   |
| Toshiba America Info Systems | 2         | 2.02%   |
| Silicon Motion               | 2         | 2.02%   |
| Micron/Crucial Technology    | 2         | 2.02%   |
| JMicron Technology           | 1         | 1.01%   |
| ADATA Technology             | 1         | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 14.66%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 5.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 5.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 4.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 4.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.59%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.72%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.72%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.72%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 1.72%   |
| Kingston Company KC2000 NVMe SSD                                               | 2         | 1.72%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.72%   |
| Intel SSD 600P Series                                                          | 2         | 1.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.72%   |
| AMD FCH IDE Controller                                                         | 2         | 1.72%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.72%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.86%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.86%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.86%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.86%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.86%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.86%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.86%   |
| Samsung Electronics SATA controller                                            | 1         | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.86%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.86%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.86%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 55        | 55.56%  |
| NVMe | 31        | 31.31%  |
| IDE  | 12        | 12.12%  |
| RAID | 1         | 1.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 61.64%  |
| AMD    | 28        | 38.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 4.11%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 2         | 2.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.74%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2         | 2.74%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2         | 2.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.74%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz         | 1         | 1.37%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1.37%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.37%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1         | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.37%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.37%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.37%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 1.37%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 1.37%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 1.37%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1         | 1.37%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.37%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.37%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1         | 1.37%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 1.37%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.37%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.37%   |
| Intel Core i3-3210 CPU @ 3.20GHz            | 1         | 1.37%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.37%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.37%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 1         | 1.37%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1         | 1.37%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.37%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.37%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 1         | 1.37%   |
| Intel Celeron CPU E3400 @ 2.60GHz           | 1         | 1.37%   |
| Intel Celeron CPU E3300 @ 2.50GHz           | 1         | 1.37%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 1.37%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 1.37%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz           | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 12        | 16.44%  |
| AMD Ryzen 7             | 11        | 15.07%  |
| Intel Core i5           | 9         | 12.33%  |
| Intel Celeron           | 7         | 9.59%   |
| AMD Ryzen 5             | 7         | 9.59%   |
| Intel Core i3           | 5         | 6.85%   |
| Other                   | 4         | 5.48%   |
| AMD A10                 | 3         | 4.11%   |
| Intel Pentium Dual-Core | 2         | 2.74%   |
| Intel Core 2 Quad       | 2         | 2.74%   |
| AMD Ryzen 9             | 2         | 2.74%   |
| Intel Xeon              | 1         | 1.37%   |
| Intel Pentium Silver    | 1         | 1.37%   |
| Intel Core 2            | 1         | 1.37%   |
| Intel Atom              | 1         | 1.37%   |
| AMD Ryzen 3             | 1         | 1.37%   |
| AMD Phenom II X4        | 1         | 1.37%   |
| AMD FX                  | 1         | 1.37%   |
| AMD E                   | 1         | 1.37%   |
| AMD A8                  | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 29        | 39.73%  |
| 2      | 26        | 35.62%  |
| 8      | 10        | 13.7%   |
| 6      | 5         | 6.85%   |
| 12     | 1         | 1.37%   |
| 3      | 1         | 1.37%   |
| 1      | 1         | 1.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 73.97%  |
| 1      | 19        | 26.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 73        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 9.21%   |
| 0x306c3    | 6         | 7.89%   |
| 0x206a7    | 5         | 6.58%   |
| 0x1067a    | 5         | 6.58%   |
| 0x806ec    | 4         | 5.26%   |
| 0x806c1    | 4         | 5.26%   |
| 0x506e3    | 3         | 3.95%   |
| 0x0a50000c | 3         | 3.95%   |
| 0x08600106 | 3         | 3.95%   |
| 0x0800820d | 3         | 3.95%   |
| 0x06003106 | 3         | 3.95%   |
| 0x906e9    | 2         | 2.63%   |
| 0x806ea    | 2         | 2.63%   |
| 0x40651    | 2         | 2.63%   |
| 0x08701021 | 2         | 2.63%   |
| 0x08701013 | 2         | 2.63%   |
| 0x08108109 | 2         | 2.63%   |
| 0x906c0    | 1         | 1.32%   |
| 0x806e9    | 1         | 1.32%   |
| 0x706a8    | 1         | 1.32%   |
| 0x706a1    | 1         | 1.32%   |
| 0x6f2      | 1         | 1.32%   |
| 0x406e3    | 1         | 1.32%   |
| 0x306a9    | 1         | 1.32%   |
| 0x10661    | 1         | 1.32%   |
| 0x0a201204 | 1         | 1.32%   |
| 0x0a201016 | 1         | 1.32%   |
| 0x08608103 | 1         | 1.32%   |
| 0x08108102 | 1         | 1.32%   |
| 0x0810100b | 1         | 1.32%   |
| 0x0800820b | 1         | 1.32%   |
| 0x06001119 | 1         | 1.32%   |
| 0x06000852 | 1         | 1.32%   |
| 0x05000029 | 1         | 1.32%   |
| 0x010000c8 | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 13.7%   |
| Haswell       | 8         | 10.96%  |
| Zen 2         | 7         | 9.59%   |
| Zen+          | 6         | 8.22%   |
| Penryn        | 6         | 8.22%   |
| Zen 3         | 5         | 6.85%   |
| Skylake       | 5         | 6.85%   |
| SandyBridge   | 5         | 6.85%   |
| TigerLake     | 4         | 5.48%   |
| Steamroller   | 3         | 4.11%   |
| Piledriver    | 2         | 2.74%   |
| Goldmont plus | 2         | 2.74%   |
| Core          | 2         | 2.74%   |
| Unknown       | 2         | 2.74%   |
| Zen           | 1         | 1.37%   |
| Tremont       | 1         | 1.37%   |
| Silvermont    | 1         | 1.37%   |
| K10           | 1         | 1.37%   |
| IvyBridge     | 1         | 1.37%   |
| Bobcat        | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 42.35%  |
| AMD    | 31        | 36.47%  |
| Nvidia | 18        | 21.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 3.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 3.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3         | 3.49%   |
| AMD Renoir                                                                  | 3         | 3.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 3.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 3.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.33%   |
| Intel HD Graphics 620                                                       | 2         | 2.33%   |
| Intel HD Graphics 530                                                       | 2         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2         | 2.33%   |
| AMD Lucienne                                                                | 2         | 2.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2         | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 2.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 1.16%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.16%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1         | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.16%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 1.16%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 1.16%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 1.16%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1         | 1.16%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 1.16%   |
| Nvidia GF119 [GeForce 605]                                                  | 1         | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.16%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 1.16%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.16%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1         | 1.16%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 1         | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.16%   |
| Intel UHD Graphics 620                                                      | 1         | 1.16%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 1         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 27        | 36.99%  |
| 1 x Intel      | 26        | 35.62%  |
| 1 x Nvidia     | 11        | 15.07%  |
| Intel + Nvidia | 5         | 6.85%   |
| Intel + AMD    | 2         | 2.74%   |
| AMD + Nvidia   | 2         | 2.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 61        | 83.56%  |
| Proprietary | 12        | 16.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 41.1%   |
| 1.01-2.0   | 13        | 17.81%  |
| 0.51-1.0   | 9         | 12.33%  |
| 0.01-0.5   | 6         | 8.22%   |
| 3.01-4.0   | 5         | 6.85%   |
| 7.01-8.0   | 4         | 5.48%   |
| 5.01-6.0   | 3         | 4.11%   |
| 8.01-16.0  | 3         | 4.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 12        | 13.64%  |
| Chimei Innolux          | 9         | 10.23%  |
| AOC                     | 9         | 10.23%  |
| Goldstar                | 8         | 9.09%   |
| BOE                     | 6         | 6.82%   |
| AU Optronics            | 6         | 6.82%   |
| Ancor Communications    | 5         | 5.68%   |
| LG Display              | 4         | 4.55%   |
| Dell                    | 4         | 4.55%   |
| Acer                    | 4         | 4.55%   |
| Lenovo                  | 3         | 3.41%   |
| Philips                 | 2         | 2.27%   |
| NEC Computers           | 2         | 2.27%   |
| BenQ                    | 2         | 2.27%   |
| Unknown                 | 2         | 2.27%   |
| Toshiba                 | 1         | 1.14%   |
| Sharp                   | 1         | 1.14%   |
| PANDA                   | 1         | 1.14%   |
| Microstep               | 1         | 1.14%   |
| LG Electronics          | 1         | 1.14%   |
| Hewlett-Packard         | 1         | 1.14%   |
| CSO                     | 1         | 1.14%   |
| Chi Mei Optoelectronics | 1         | 1.14%   |
| ASUSTek Computer        | 1         | 1.14%   |
| Apple                   | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 3         | 3.26%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                 | 2         | 2.17%   |
| Unknown                                                              | 2         | 2.17%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch            | 1         | 1.09%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM029A 1920x1200 582x364mm 27.0-inch | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 1.09%   |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1         | 1.09%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 1.09%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch    | 1         | 1.09%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch    | 1         | 1.09%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                | 1         | 1.09%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                   | 1         | 1.09%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch              | 1         | 1.09%   |
| NEC Computers LCD Monitor LCD92VM 1280x1024                          | 1         | 1.09%   |
| NEC Computers EA191M NEC673E 1280x1024 376x301mm 19.0-inch           | 1         | 1.09%   |
| Microstep LCD Monitor MSI G241                                       | 1         | 1.09%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1         | 1.09%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch         | 1         | 1.09%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch           | 1         | 1.09%   |
| Lenovo LEN L220xwC LEN1151 1920x1200 474x296mm 22.0-inch             | 1         | 1.09%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                  | 1         | 1.09%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1         | 1.09%   |
| Goldstar W1942 GSM4B70 1440x900 408x255mm 18.9-inch                  | 1         | 1.09%   |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                  | 1         | 1.09%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 1         | 1.09%   |
| Goldstar L227W GSM566F 1680x1050 474x296mm 22.0-inch                 | 1         | 1.09%   |
| Goldstar E2050 GSM4EAE 1600x900 443x249mm 20.0-inch                  | 1         | 1.09%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1         | 1.09%   |
| Dell U4919DW DELA109 3840x1080 1198x337mm 49.0-inch                  | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 43.02%  |
| 1366x768 (WXGA)    | 15        | 17.44%  |
| 2560x1440 (QHD)    | 6         | 6.98%   |
| 3840x2160 (4K)     | 5         | 5.81%   |
| 1680x1050 (WSXGA+) | 4         | 4.65%   |
| 1280x1024 (SXGA)   | 4         | 4.65%   |
| 1920x1200 (WUXGA)  | 3         | 3.49%   |
| 3840x1080          | 2         | 2.33%   |
| Unknown            | 2         | 2.33%   |
| 5760x1080          | 1         | 1.16%   |
| 2560x1080          | 1         | 1.16%   |
| 2256x1504          | 1         | 1.16%   |
| 1600x900 (HD+)     | 1         | 1.16%   |
| 1440x900 (WXGA+)   | 1         | 1.16%   |
| 1360x768           | 1         | 1.16%   |
| 1280x800 (WXGA)    | 1         | 1.16%   |
| 1024x768 (XGA)     | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 22.62%  |
| 24      | 9         | 10.71%  |
| 27      | 8         | 9.52%   |
| Unknown | 8         | 9.52%   |
| 14      | 6         | 7.14%   |
| 13      | 6         | 7.14%   |
| 23      | 5         | 5.95%   |
| 21      | 5         | 5.95%   |
| 22      | 4         | 4.76%   |
| 18      | 4         | 4.76%   |
| 31      | 2         | 2.38%   |
| 17      | 2         | 2.38%   |
| 11      | 2         | 2.38%   |
| 49      | 1         | 1.19%   |
| 29      | 1         | 1.19%   |
| 20      | 1         | 1.19%   |
| 19      | 1         | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 34.52%  |
| 501-600     | 21        | 25%     |
| 401-500     | 15        | 17.86%  |
| Unknown     | 8         | 9.52%   |
| 201-300     | 5         | 5.95%   |
| 601-700     | 3         | 3.57%   |
| 351-400     | 2         | 2.38%   |
| 1001-1500   | 1         | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 65%     |
| 16/10   | 12        | 15%     |
| Unknown | 8         | 10%     |
| 5/4     | 3         | 3.75%   |
| 3/2     | 2         | 2.5%    |
| 4/3     | 1         | 1.25%   |
| 32/9    | 1         | 1.25%   |
| 21/9    | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 22.35%  |
| 201-250        | 17        | 20%     |
| 81-90          | 10        | 11.76%  |
| 301-350        | 9         | 10.59%  |
| Unknown        | 8         | 9.41%   |
| 251-300        | 5         | 5.88%   |
| 151-200        | 5         | 5.88%   |
| 141-150        | 5         | 5.88%   |
| 71-80          | 2         | 2.35%   |
| 51-60          | 2         | 2.35%   |
| 351-500        | 2         | 2.35%   |
| 501-1000       | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 34        | 41.98%  |
| 121-160       | 17        | 20.99%  |
| 101-120       | 16        | 19.75%  |
| Unknown       | 8         | 9.88%   |
| 161-240       | 4         | 4.94%   |
| More than 240 | 2         | 2.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 53        | 72.6%   |
| 2     | 18        | 24.66%  |
| 3     | 2         | 2.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 43        | 38.74%  |
| Intel                      | 32        | 28.83%  |
| Qualcomm Atheros           | 16        | 14.41%  |
| MediaTek                   | 4         | 3.6%    |
| Broadcom                   | 3         | 2.7%    |
| Marvell Technology Group   | 2         | 1.8%    |
| ZTE WCDMA Technologies MSM | 1         | 0.9%    |
| Xiaomi                     | 1         | 0.9%    |
| TP-Link                    | 1         | 0.9%    |
| T & A Mobile Phones        | 1         | 0.9%    |
| Ralink Technology          | 1         | 0.9%    |
| Linksys                    | 1         | 0.9%    |
| Huawei Technologies        | 1         | 0.9%    |
| Dell                       | 1         | 0.9%    |
| D-Link System              | 1         | 0.9%    |
| Belkin Components          | 1         | 0.9%    |
| ASIX Electronics           | 1         | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 26.15%  |
| Intel Wi-Fi 6 AX200                                               | 8         | 6.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.08%   |
| Intel I211 Gigabit Network Connection                             | 4         | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.31%   |
| Intel Wireless 3165                                               | 3         | 2.31%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.54%   |
| Intel Wireless 7265                                               | 2         | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.54%   |
| ZTE WCDMA MSM Yota Router                                         | 1         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.77%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.77%   |
| T & A Mobile Phones 5007Z                                         | 1         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.77%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.77%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.77%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.77%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.77%   |
| Realtek 802.11ac NIC                                              | 1         | 0.77%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.77%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.77%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 42.62%  |
| Qualcomm Atheros      | 13        | 21.31%  |
| Realtek Semiconductor | 11        | 18.03%  |
| MediaTek              | 4         | 6.56%   |
| Broadcom              | 3         | 4.92%   |
| Ralink Technology     | 1         | 1.64%   |
| Linksys               | 1         | 1.64%   |
| D-Link System         | 1         | 1.64%   |
| Belkin Components     | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 8         | 12.9%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 4         | 6.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 3         | 4.84%   |
| Intel Wireless 3165                                                        | 3         | 4.84%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 4.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 2         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 3.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                    | 2         | 3.23%   |
| Intel Wireless 7265                                                        | 2         | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2         | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 1.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                            | 1         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 1.61%   |
| Realtek RTL8187 Wireless Adapter                                           | 1         | 1.61%   |
| Realtek 802.11n WLAN Adapter                                               | 1         | 1.61%   |
| Realtek 802.11ac NIC                                                       | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1         | 1.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 1.61%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                 | 1         | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1         | 1.61%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1         | 1.61%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                        | 1         | 1.61%   |
| Intel Wireless-AC 9260                                                     | 1         | 1.61%   |
| Intel Wireless 8265 / 8275                                                 | 1         | 1.61%   |
| Intel Wireless 8260                                                        | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                             | 1         | 1.61%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                              | 1         | 1.61%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 1.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                            | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 38        | 57.58%  |
| Intel                      | 15        | 22.73%  |
| Qualcomm Atheros           | 5         | 7.58%   |
| Marvell Technology Group   | 2         | 3.03%   |
| ZTE WCDMA Technologies MSM | 1         | 1.52%   |
| Xiaomi                     | 1         | 1.52%   |
| TP-Link                    | 1         | 1.52%   |
| Huawei Technologies        | 1         | 1.52%   |
| Broadcom                   | 1         | 1.52%   |
| ASIX Electronics           | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 51.52%  |
| Intel I211 Gigabit Network Connection                             | 4         | 6.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 3.03%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.03%   |
| ZTE WCDMA MSM Yota Router                                         | 1         | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.52%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.52%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.52%   |
| Huawei LLD-L21                                                    | 1         | 1.52%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 62        | 52.1%   |
| WiFi     | 55        | 46.22%  |
| Modem    | 1         | 0.84%   |
| Unknown  | 1         | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 51.28%  |
| Ethernet | 38        | 48.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 36        | 49.32%  |
| 1     | 34        | 46.58%  |
| 3     | 2         | 2.74%   |
| 0     | 1         | 1.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 70.27%  |
| Yes  | 22        | 29.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 46.94%  |
| Qualcomm Atheros Communications | 6         | 12.24%  |
| Cambridge Silicon Radio         | 4         | 8.16%   |
| Realtek Semiconductor           | 3         | 6.12%   |
| MediaTek                        | 2         | 4.08%   |
| Lite-On Technology              | 2         | 4.08%   |
| Broadcom                        | 2         | 4.08%   |
| Toshiba                         | 1         | 2.04%   |
| ISSC                            | 1         | 2.04%   |
| IMC Networks                    | 1         | 2.04%   |
| Foxconn / Hon Hai               | 1         | 2.04%   |
| Dell                            | 1         | 2.04%   |
| ASUSTek Computer                | 1         | 2.04%   |
| Apple                           | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 14.29%  |
| Intel AX200 Bluetooth                               | 7         | 14.29%  |
| Intel AX201 Bluetooth                               | 5         | 10.2%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 8.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.08%   |
| MediaTek Wireless_Device                            | 2         | 4.08%   |
| Intel AX210 Bluetooth                               | 2         | 4.08%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.04%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.04%   |
| Realtek Bluetooth Radio                             | 1         | 2.04%   |
| Lite-On Wireless_Device                             | 1         | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.04%   |
| ISSC Bluetooth Device                               | 1         | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.04%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.04%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.04%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 2.04%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.04%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 45        | 44.12%  |
| AMD                 | 33        | 32.35%  |
| Nvidia              | 14        | 13.73%  |
| Texas Instruments   | 2         | 1.96%   |
| C-Media Electronics | 2         | 1.96%   |
| Blue Microphones    | 2         | 1.96%   |
| Tenx Technology     | 1         | 0.98%   |
| Samsung Electronics | 1         | 0.98%   |
| Cooler Master       | 1         | 0.98%   |
| Conexant Systems    | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 9.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.58%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 4.58%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 4.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 3.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.05%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.05%   |
| AMD FCH Azalia Controller                                                  | 4         | 3.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 2.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.53%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.53%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.53%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2         | 1.53%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 1.53%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.53%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.53%   |
| Texas Instruments PCM2904 Audio Codec                                      | 1         | 0.76%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.76%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.76%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.76%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 27.27%  |
| Unknown             | 4         | 12.12%  |
| Crucial             | 4         | 12.12%  |
| SK hynix            | 3         | 9.09%   |
| Micron Technology   | 3         | 9.09%   |
| A-DATA Technology   | 3         | 9.09%   |
| Kingston            | 2         | 6.06%   |
| Transcend           | 1         | 3.03%   |
| Team                | 1         | 3.03%   |
| Patriot             | 1         | 3.03%   |
| G.Skill             | 1         | 3.03%   |
| Corsair             | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 2.86%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 2.86%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 2.86%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s               | 1         | 2.86%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s                | 1         | 2.86%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 2.86%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.86%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.86%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.86%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 2.86%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 2.86%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 2.86%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.86%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.86%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.86%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s              | 1         | 2.86%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.86%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 2.86%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s              | 1         | 2.86%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 2.86%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 2.86%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 2.86%   |
| Kingston RAM KHX1866C9D3/4GX 4GB DIMM DDR3 1867MT/s              | 1         | 2.86%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s              | 1         | 2.86%   |
| Kingston RAM 9905403-176.A00LF 2GB DIMM DDR3 1333MT/s            | 1         | 2.86%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 2.86%   |
| Crucial RAM CT8G4SFS824A.M8FJ 8GB SODIMM DDR4 2400MT/s           | 1         | 2.86%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s            | 1         | 2.86%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 2.86%   |
| Crucial RAM BLS8G4D32AESBK.M8FE 8GB DIMM DDR4 3400MT/s           | 1         | 2.86%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s            | 1         | 2.86%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 2.86%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1         | 2.86%   |
| A-DATA RAM AL1P32NCST2-B87S 16GB SODIMM DDR4 3200MT/s            | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 48.28%  |
| DDR3    | 8         | 27.59%  |
| LPDDR3  | 3         | 10.34%  |
| LPDDR4  | 1         | 3.45%   |
| DDR2    | 1         | 3.45%   |
| DDR     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 50%     |
| DIMM         | 11        | 39.29%  |
| Row Of Chips | 3         | 10.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 11        | 35.48%  |
| 4096  | 8         | 25.81%  |
| 16384 | 6         | 19.35%  |
| 32768 | 2         | 6.45%   |
| 2048  | 2         | 6.45%   |
| 1024  | 2         | 6.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 7         | 21.88%  |
| 1600    | 5         | 15.63%  |
| 2133    | 4         | 12.5%   |
| 2400    | 3         | 9.38%   |
| 2667    | 2         | 6.25%   |
| 1867    | 2         | 6.25%   |
| 1333    | 2         | 6.25%   |
| 667     | 2         | 6.25%   |
| 4267    | 1         | 3.13%   |
| 3600    | 1         | 3.13%   |
| 3400    | 1         | 3.13%   |
| 1866    | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 1018 | 1         | 100%    |

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
| Realtek Semiconductor                  | 5         | 12.5%   |
| Logitech                               | 5         | 12.5%   |
| Quanta                                 | 4         | 10%     |
| Microdia                               | 4         | 10%     |
| Sunplus Innovation Technology          | 3         | 7.5%    |
| IMC Networks                           | 3         | 7.5%    |
| Chicony Electronics                    | 3         | 7.5%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5%      |
| Z-Star Microelectronics                | 1         | 2.5%    |
| Syntek                                 | 1         | 2.5%    |
| Microsoft                              | 1         | 2.5%    |
| MacroSilicon                           | 1         | 2.5%    |
| LG Electronics                         | 1         | 2.5%    |
| Importek                               | 1         | 2.5%    |
| Hewlett-Packard                        | 1         | 2.5%    |
| Bison Electronics                      | 1         | 2.5%    |
| Apple                                  | 1         | 2.5%    |
| Acer                                   | 1         | 2.5%    |
| A4Tech                                 | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 3         | 7.5%    |
| Sunplus Integrated_Webcam_HD                                    | 2         | 5%      |
| Quanta HD User Facing                                           | 2         | 5%      |
| Logitech Webcam C270                                            | 2         | 5%      |
| IMC Networks Integrated Camera                                  | 2         | 5%      |
| Z-Star Webcam                                                   | 1         | 2.5%    |
| Syntek Integrated Camera                                        | 1         | 2.5%    |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 2.5%    |
| Realtek Laptop Camera                                           | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD                                    | 1         | 2.5%    |
| Realtek Integrated Webcam_HD                                    | 1         | 2.5%    |
| Realtek Integrated Webcam                                       | 1         | 2.5%    |
| Realtek HD WebCam                                               | 1         | 2.5%    |
| Quanta VGA WebCam                                               | 1         | 2.5%    |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 2.5%    |
| Microsoft LifeCam Studio                                        | 1         | 2.5%    |
| Microdia REDRAGON Live Camera Audio                             | 1         | 2.5%    |
| MacroSilicon ShadowCast                                         | 1         | 2.5%    |
| Logitech HD Pro Webcam C920                                     | 1         | 2.5%    |
| Logitech C922 Pro Stream Webcam                                 | 1         | 2.5%    |
| Logitech C920 PRO HD Webcam                                     | 1         | 2.5%    |
| LG Optimus (Various Models) MTP Mode                            | 1         | 2.5%    |
| Importek TOSHIBA Web Camera - HD                                | 1         | 2.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 2.5%    |
| HP Webcam HD 2300                                               | 1         | 2.5%    |
| Chicony Sony Visual Communication Camera                        | 1         | 2.5%    |
| Chicony Integrated Camera                                       | 1         | 2.5%    |
| Chicony EasyCamera                                              | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.5%    |
| Bison LENOVO LBG 720P CAM                                       | 1         | 2.5%    |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 2.5%    |
| Acer Lenovo EasyCamera                                          | 1         | 2.5%    |
| A4Tech FHD 1080P PC Camera                                      | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 28.57%  |
| Synaptics                  | 2         | 28.57%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| Focal-systems.Corp         | 1         | 14.29%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 14.29%  |
| Validity Sensors VFS Fingerprint sensor           | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 14.29%  |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 14.29%  |
| AuthenTec Fingerprint Sensor                      | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 33.33%  |
| Alcor Micro | 2         | 33.33%  |
| O2 Micro    | 1         | 16.67%  |
| Aktiv       | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |
| Broadcom 5880                                  | 1         | 16.67%  |
| Aktiv Rutoken lite                             | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 55        | 74.32%  |
| 1     | 11        | 14.86%  |
| 2     | 7         | 9.46%   |
| 3     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 9         | 28.13%  |
| Fingerprint reader    | 7         | 21.88%  |
| Chipcard              | 6         | 18.75%  |
| Multimedia controller | 5         | 15.63%  |
| Graphics card         | 2         | 6.25%   |
| Unassigned class      | 1         | 3.13%   |
| Storage               | 1         | 3.13%   |
| Camera                | 1         | 3.13%   |


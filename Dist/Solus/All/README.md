Solus - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Solus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Solus/Desktop/README.md) and [notebooks](/Dist/Solus/Notebook/README.md).

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

Total: 253

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
| Dell          | Vostro 15-3568              | Notebook    | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [53fef6a61a](https://linux-hardware.org/?probe=53fef6a61a) | Jul 08, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [48cb73de41](https://linux-hardware.org/?probe=48cb73de41) | Jul 01, 2021 |
| Biostar       | A320MH                      | Desktop     | [2c478119e9](https://linux-hardware.org/?probe=2c478119e9) | Jun 30, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [6fc3976633](https://linux-hardware.org/?probe=6fc3976633) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [4fc48865ef](https://linux-hardware.org/?probe=4fc48865ef) | Jun 15, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [f5c8f64400](https://linux-hardware.org/?probe=f5c8f64400) | Jun 03, 2021 |
| Howard Com... | W350                        | Notebook    | [3e55c8284e](https://linux-hardware.org/?probe=3e55c8284e) | May 28, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [dfa5c022b3](https://linux-hardware.org/?probe=dfa5c022b3) | May 26, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [ce04df7bae](https://linux-hardware.org/?probe=ce04df7bae) | May 23, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [a33e231e6b](https://linux-hardware.org/?probe=a33e231e6b) | May 23, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e53c63ba89](https://linux-hardware.org/?probe=e53c63ba89) | May 19, 2021 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [f759ad1793](https://linux-hardware.org/?probe=f759ad1793) | May 13, 2021 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [f28f1ea67d](https://linux-hardware.org/?probe=f28f1ea67d) | May 13, 2021 |
| Intel         | X99 V102                    | Desktop     | [bc57aedd09](https://linux-hardware.org/?probe=bc57aedd09) | May 02, 2021 |
| Gigabyte      | AORUS 17G KB                | Notebook    | [fd9385ff3c](https://linux-hardware.org/?probe=fd9385ff3c) | Apr 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b5f3f78ddb](https://linux-hardware.org/?probe=b5f3f78ddb) | Apr 25, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [5c51b7f289](https://linux-hardware.org/?probe=5c51b7f289) | Apr 25, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | Notebook    | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| Dell          | 0FH884                      | Desktop     | [93acc58efb](https://linux-hardware.org/?probe=93acc58efb) | Apr 10, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e8b5a1786b](https://linux-hardware.org/?probe=e8b5a1786b) | Apr 08, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [c7c0f7323d](https://linux-hardware.org/?probe=c7c0f7323d) | Mar 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [accdafb993](https://linux-hardware.org/?probe=accdafb993) | Mar 08, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f4e39d4730](https://linux-hardware.org/?probe=f4e39d4730) | Mar 04, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [e507a57307](https://linux-hardware.org/?probe=e507a57307) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f1c277189f](https://linux-hardware.org/?probe=f1c277189f) | Feb 16, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [d8b7b99dd0](https://linux-hardware.org/?probe=d8b7b99dd0) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [cdd0998f7c](https://linux-hardware.org/?probe=cdd0998f7c) | Feb 14, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f4ee71d37f](https://linux-hardware.org/?probe=f4ee71d37f) | Feb 12, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [7a2993f67a](https://linux-hardware.org/?probe=7a2993f67a) | Feb 03, 2021 |
| Gigabyte      | H61M-HD2                    | Desktop     | [78c877458a](https://linux-hardware.org/?probe=78c877458a) | Jan 28, 2021 |
| Lenovo        | ThinkPad T410 2522Y1L       | Notebook    | [3c4543a94f](https://linux-hardware.org/?probe=3c4543a94f) | Jan 26, 2021 |
| Gigabyte      | H61M-HD2                    | Desktop     | [6caba093b5](https://linux-hardware.org/?probe=6caba093b5) | Jan 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd5bdfd31f](https://linux-hardware.org/?probe=bd5bdfd31f) | Jan 21, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [f8c2afa143](https://linux-hardware.org/?probe=f8c2afa143) | Jan 20, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [f69556d436](https://linux-hardware.org/?probe=f69556d436) | Jan 15, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [010be27c6a](https://linux-hardware.org/?probe=010be27c6a) | Jan 11, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [56d39c0f21](https://linux-hardware.org/?probe=56d39c0f21) | Jan 02, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [f2c8ec14c7](https://linux-hardware.org/?probe=f2c8ec14c7) | Jan 02, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [0173204c7f](https://linux-hardware.org/?probe=0173204c7f) | Dec 23, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [26447067ee](https://linux-hardware.org/?probe=26447067ee) | Dec 20, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [5f78418b58](https://linux-hardware.org/?probe=5f78418b58) | Dec 19, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [708eaf5602](https://linux-hardware.org/?probe=708eaf5602) | Dec 14, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [3d3a517e96](https://linux-hardware.org/?probe=3d3a517e96) | Dec 11, 2020 |
| Sony          | VPCEB1S1E                   | Notebook    | [ebcb16e616](https://linux-hardware.org/?probe=ebcb16e616) | Nov 27, 2020 |
| HP            | Elite Dragonfly             | Convertible | [ce851e2475](https://linux-hardware.org/?probe=ce851e2475) | Nov 25, 2020 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [cba289e868](https://linux-hardware.org/?probe=cba289e868) | Nov 22, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8e3d2a963b](https://linux-hardware.org/?probe=8e3d2a963b) | Nov 18, 2020 |
| ASUSTek       | PRIME X370-A                | Desktop     | [c8f850e40f](https://linux-hardware.org/?probe=c8f850e40f) | Nov 15, 2020 |
| ASUSTek       | PRIME X370-A                | Desktop     | [c86804a559](https://linux-hardware.org/?probe=c86804a559) | Nov 14, 2020 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [3a3a530ac9](https://linux-hardware.org/?probe=3a3a530ac9) | Nov 08, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [cdd1a3be02](https://linux-hardware.org/?probe=cdd1a3be02) | Nov 07, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Timi          | TM1701                      | Notebook    | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [b21d4ca9d0](https://linux-hardware.org/?probe=b21d4ca9d0) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [eb1b0d459f](https://linux-hardware.org/?probe=eb1b0d459f) | Oct 25, 2020 |
| Toshiba       | PORTEGE Z20T-B              | Notebook    | [9d789eba3c](https://linux-hardware.org/?probe=9d789eba3c) | Oct 12, 2020 |
| Toshiba       | Satellite P50-A             | Notebook    | [884731a198](https://linux-hardware.org/?probe=884731a198) | Sep 28, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [80550be62d](https://linux-hardware.org/?probe=80550be62d) | Sep 28, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C5A... | Notebook    | [2f729ef2af](https://linux-hardware.org/?probe=2f729ef2af) | Sep 11, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [9968dc910c](https://linux-hardware.org/?probe=9968dc910c) | Sep 10, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [2ae445db73](https://linux-hardware.org/?probe=2ae445db73) | Sep 10, 2020 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [bcc44c581c](https://linux-hardware.org/?probe=bcc44c581c) | Sep 09, 2020 |
| Dell          | 0M017G A00                  | Desktop     | [e51b08ee63](https://linux-hardware.org/?probe=e51b08ee63) | Sep 08, 2020 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [5e2142357f](https://linux-hardware.org/?probe=5e2142357f) | Sep 08, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [e60be6cba2](https://linux-hardware.org/?probe=e60be6cba2) | Sep 06, 2020 |
| Dell          | Inspiron 5577               | Notebook    | [b46a79f93e](https://linux-hardware.org/?probe=b46a79f93e) | Sep 03, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [4bf4f029df](https://linux-hardware.org/?probe=4bf4f029df) | Sep 03, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [aca54beb89](https://linux-hardware.org/?probe=aca54beb89) | Sep 02, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d150d7a9ea](https://linux-hardware.org/?probe=d150d7a9ea) | Sep 02, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [793085b89a](https://linux-hardware.org/?probe=793085b89a) | Aug 15, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| Pegatron      | IPM31G                      | Desktop     | [ed7c9fc9dc](https://linux-hardware.org/?probe=ed7c9fc9dc) | Jul 24, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fda411a3d7](https://linux-hardware.org/?probe=fda411a3d7) | Jul 24, 2020 |
| Avell High... | Avell G1750 MUV / C65 MU... | Notebook    | [cf035fee07](https://linux-hardware.org/?probe=cf035fee07) | Jul 24, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7744b749d9](https://linux-hardware.org/?probe=7744b749d9) | Jul 09, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | Presario C700               | Notebook    | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| ASUSTek       | K45A                        | Notebook    | [57c5b7b4bd](https://linux-hardware.org/?probe=57c5b7b4bd) | Jun 08, 2020 |
| MSI           | H87-G41 PC Mate             | Desktop     | [6081e4a770](https://linux-hardware.org/?probe=6081e4a770) | Jun 07, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [5d852ecca8](https://linux-hardware.org/?probe=5d852ecca8) | Jun 06, 2020 |
| Acer          | Predator PH315-52           | Notebook    | [b5e7780315](https://linux-hardware.org/?probe=b5e7780315) | Jun 04, 2020 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [cb0fe570e2](https://linux-hardware.org/?probe=cb0fe570e2) | May 22, 2020 |
| Dell          | Latitude 7390               | Notebook    | [49112c8937](https://linux-hardware.org/?probe=49112c8937) | May 20, 2020 |
| HP            | ProBook 6470b               | Notebook    | [59db0f436f](https://linux-hardware.org/?probe=59db0f436f) | May 13, 2020 |
| MSI           | H87-G41 PC Mate             | Desktop     | [b3513301a1](https://linux-hardware.org/?probe=b3513301a1) | May 08, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [e98c6a162c](https://linux-hardware.org/?probe=e98c6a162c) | May 03, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [32a9d86996](https://linux-hardware.org/?probe=32a9d86996) | May 02, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [670ddc1e5c](https://linux-hardware.org/?probe=670ddc1e5c) | Apr 13, 2020 |
| HP            | Pavilion dv6                | Notebook    | [6939cb8715](https://linux-hardware.org/?probe=6939cb8715) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [328b82f240](https://linux-hardware.org/?probe=328b82f240) | Apr 11, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0c6dc861d6](https://linux-hardware.org/?probe=0c6dc861d6) | Apr 06, 2020 |
| MSI           | H87-G41 PC Mate             | Desktop     | [acad555779](https://linux-hardware.org/?probe=acad555779) | Apr 01, 2020 |
| Lenovo        | IdeaCentre K320 10031       | Desktop     | [ef01565711](https://linux-hardware.org/?probe=ef01565711) | Apr 01, 2020 |
| Lenovo        | IdeaCentre K320 10031       | Desktop     | [7c54db2820](https://linux-hardware.org/?probe=7c54db2820) | Apr 01, 2020 |
| HP            | Pavilion dv6                | Notebook    | [3d9d707ea7](https://linux-hardware.org/?probe=3d9d707ea7) | Mar 30, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [f7cfd1b163](https://linux-hardware.org/?probe=f7cfd1b163) | Mar 26, 2020 |
| ASUSTek       | P5PL2                       | Desktop     | [19fbc6cfd3](https://linux-hardware.org/?probe=19fbc6cfd3) | Mar 25, 2020 |
| Acer          | Swift SF314-56              | Notebook    | [3826e4d14c](https://linux-hardware.org/?probe=3826e4d14c) | Mar 24, 2020 |
| Google        | Kip                         | Notebook    | [4f62ee34a3](https://linux-hardware.org/?probe=4f62ee34a3) | Mar 22, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [96e42952bb](https://linux-hardware.org/?probe=96e42952bb) | Mar 17, 2020 |
| Dell          | Vostro 3446                 | Notebook    | [c42d273e36](https://linux-hardware.org/?probe=c42d273e36) | Mar 12, 2020 |
| Gigabyte      | GA-890XA-UD3                | Desktop     | [e2cafdec0d](https://linux-hardware.org/?probe=e2cafdec0d) | Mar 09, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [0c527b2640](https://linux-hardware.org/?probe=0c527b2640) | Mar 08, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [3924df2c92](https://linux-hardware.org/?probe=3924df2c92) | Feb 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [1281c8c30d](https://linux-hardware.org/?probe=1281c8c30d) | Feb 26, 2020 |
| Lenovo        | ThinkPad T480 20L5S08L00    | Notebook    | [3c23e0d823](https://linux-hardware.org/?probe=3c23e0d823) | Feb 20, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [fdc69c0b70](https://linux-hardware.org/?probe=fdc69c0b70) | Feb 08, 2020 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [771600b1ae](https://linux-hardware.org/?probe=771600b1ae) | Feb 07, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [4060a4338e](https://linux-hardware.org/?probe=4060a4338e) | Feb 05, 2020 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [eb8bd4a219](https://linux-hardware.org/?probe=eb8bd4a219) | Jan 20, 2020 |
| ASUSTek       | X556UQK                     | Notebook    | [5070b3831b](https://linux-hardware.org/?probe=5070b3831b) | Dec 29, 2019 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [ad271d2feb](https://linux-hardware.org/?probe=ad271d2feb) | Dec 28, 2019 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [b039aefd9e](https://linux-hardware.org/?probe=b039aefd9e) | Dec 25, 2019 |
| Lenovo        | ThinkPad X301 4057WHQ       | Notebook    | [badcab7790](https://linux-hardware.org/?probe=badcab7790) | Dec 22, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [627975dcd4](https://linux-hardware.org/?probe=627975dcd4) | Dec 18, 2019 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [b0d238eb2e](https://linux-hardware.org/?probe=b0d238eb2e) | Dec 11, 2019 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9f6135476f](https://linux-hardware.org/?probe=9f6135476f) | Dec 10, 2019 |
| Howard Com... | W350                        | Notebook    | [7434be9250](https://linux-hardware.org/?probe=7434be9250) | Dec 10, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [99d56262c0](https://linux-hardware.org/?probe=99d56262c0) | Dec 03, 2019 |
| HP            | Pavilion 17                 | Notebook    | [09c3d61b20](https://linux-hardware.org/?probe=09c3d61b20) | Nov 18, 2019 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [372f025649](https://linux-hardware.org/?probe=372f025649) | Nov 18, 2019 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [2395d81be3](https://linux-hardware.org/?probe=2395d81be3) | Nov 15, 2019 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [7f6fec93cc](https://linux-hardware.org/?probe=7f6fec93cc) | Nov 15, 2019 |
| HP            | 255 G1                      | Notebook    | [0a0d476781](https://linux-hardware.org/?probe=0a0d476781) | Nov 06, 2019 |
| HP            | 255 G1                      | Notebook    | [2aa8aaffc1](https://linux-hardware.org/?probe=2aa8aaffc1) | Nov 04, 2019 |
| Acer          | Swift SF315-52              | Notebook    | [c5950fe2b2](https://linux-hardware.org/?probe=c5950fe2b2) | Oct 20, 2019 |
| Toshiba       | Unknown                     | Notebook    | [64c90921de](https://linux-hardware.org/?probe=64c90921de) | Oct 18, 2019 |
| Dell          | Latitude 7490               | Notebook    | [2381ee7707](https://linux-hardware.org/?probe=2381ee7707) | Oct 14, 2019 |
| HP            | ENVY dv7                    | Notebook    | [1f13304239](https://linux-hardware.org/?probe=1f13304239) | Oct 06, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4e34d8767a](https://linux-hardware.org/?probe=4e34d8767a) | Aug 03, 2019 |
| Dell          | XPS 15 9560                 | Notebook    | [65f14ca77f](https://linux-hardware.org/?probe=65f14ca77f) | Jun 11, 2019 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [9e0b67b32e](https://linux-hardware.org/?probe=9e0b67b32e) | May 05, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [d61154eabe](https://linux-hardware.org/?probe=d61154eabe) | Apr 16, 2019 |
| HP            | EliteBook 8770w             | Notebook    | [fdba82a5b5](https://linux-hardware.org/?probe=fdba82a5b5) | Apr 01, 2019 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [4aced2b19a](https://linux-hardware.org/?probe=4aced2b19a) | Feb 28, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [0ffa9711e1](https://linux-hardware.org/?probe=0ffa9711e1) | Jan 07, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [46de1b2636](https://linux-hardware.org/?probe=46de1b2636) | Jan 07, 2019 |
| Acer          | Aspire E1-532P              | Notebook    | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Solus 4.1    | 65        | 36.72%  |
| Solus 4.3    | 62        | 35.03%  |
| Solus 4.2    | 25        | 14.12%  |
| Solus 4.0    | 23        | 12.99%  |
| Solus 3.9999 | 2         | 1.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Solus | 167       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 15        | 7.89%   |
| 5.6.19-159.current  | 10        | 5.26%   |
| 5.15.32-213.current | 8         | 4.21%   |
| 5.5.7-150.current   | 7         | 3.68%   |
| 5.14.21-210.current | 7         | 3.68%   |
| 5.6.4-152.current   | 6         | 3.16%   |
| 5.6.13-153.current  | 6         | 3.16%   |
| 5.15.50-216.current | 6         | 3.16%   |
| 5.14.16-205.current | 6         | 3.16%   |
| 5.13.1-187.current  | 6         | 3.16%   |
| 5.6.18-156.current  | 5         | 2.63%   |
| 5.4.12-144.current  | 5         | 2.63%   |
| 5.13.6-190.current  | 5         | 2.63%   |
| 5.13.12-193.current | 5         | 2.63%   |
| 5.11.12-177.current | 5         | 2.63%   |
| 6.0.11-225.current  | 4         | 2.11%   |
| 5.5.11-151.current  | 4         | 2.11%   |
| 5.11.22-180.current | 4         | 2.11%   |
| 5.10.15-172.current | 4         | 2.11%   |
| 5.3.7-132.current   | 3         | 1.58%   |
| 5.3.15-138.current  | 3         | 1.58%   |
| 5.2.20-130.current  | 3         | 1.58%   |
| 5.15.77-219.current | 3         | 1.58%   |
| 5.10.7-168.current  | 3         | 1.58%   |
| 5.5.4-148.current   | 2         | 1.05%   |
| 5.4.1-137.current   | 2         | 1.05%   |
| 5.3.10-134.current  | 2         | 1.05%   |
| 5.2.2-122.current   | 2         | 1.05%   |
| 5.15.43-215.current | 2         | 1.05%   |
| 5.15.30-212.current | 2         | 1.05%   |
| 5.15.26-211.current | 2         | 1.05%   |
| 5.14.14-202.current | 2         | 1.05%   |
| 5.13.0-186.current  | 2         | 1.05%   |
| 5.12.10-182.current | 2         | 1.05%   |
| 5.11.9-176.current  | 2         | 1.05%   |
| 5.11.21-179.current | 2         | 1.05%   |
| 5.11.16-178.current | 2         | 1.05%   |
| 5.10.5-167.current  | 2         | 1.05%   |
| 5.10.12-171.current | 2         | 1.05%   |
| 4.20.16-112.current | 2         | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6.19  | 25        | 13.16%  |
| 5.15.32 | 8         | 4.21%   |
| 5.5.7   | 7         | 3.68%   |
| 5.14.21 | 7         | 3.68%   |
| 5.14.16 | 7         | 3.68%   |
| 5.6.4   | 6         | 3.16%   |
| 5.6.18  | 6         | 3.16%   |
| 5.6.13  | 6         | 3.16%   |
| 5.4.12  | 6         | 3.16%   |
| 5.15.50 | 6         | 3.16%   |
| 5.13.1  | 6         | 3.16%   |
| 5.13.6  | 5         | 2.63%   |
| 5.13.12 | 5         | 2.63%   |
| 5.11.12 | 5         | 2.63%   |
| 6.0.11  | 4         | 2.11%   |
| 5.5.11  | 4         | 2.11%   |
| 5.11.22 | 4         | 2.11%   |
| 5.10.15 | 4         | 2.11%   |
| 5.3.7   | 3         | 1.58%   |
| 5.3.15  | 3         | 1.58%   |
| 5.2.20  | 3         | 1.58%   |
| 5.15.77 | 3         | 1.58%   |
| 5.10.7  | 3         | 1.58%   |
| 5.5.4   | 2         | 1.05%   |
| 5.4.1   | 2         | 1.05%   |
| 5.3.10  | 2         | 1.05%   |
| 5.2.2   | 2         | 1.05%   |
| 5.15.43 | 2         | 1.05%   |
| 5.15.30 | 2         | 1.05%   |
| 5.15.26 | 2         | 1.05%   |
| 5.14.14 | 2         | 1.05%   |
| 5.13.0  | 2         | 1.05%   |
| 5.12.10 | 2         | 1.05%   |
| 5.11.9  | 2         | 1.05%   |
| 5.11.21 | 2         | 1.05%   |
| 5.11.16 | 2         | 1.05%   |
| 5.10.5  | 2         | 1.05%   |
| 5.10.12 | 2         | 1.05%   |
| 4.20.16 | 2         | 1.05%   |
| 5.5.3   | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6     | 42        | 22.58%  |
| 5.15    | 25        | 13.44%  |
| 5.14    | 19        | 10.22%  |
| 5.13    | 19        | 10.22%  |
| 5.5     | 14        | 7.53%   |
| 5.11    | 14        | 7.53%   |
| 5.10    | 13        | 6.99%   |
| 5.3     | 9         | 4.84%   |
| 5.4     | 8         | 4.3%    |
| 5.2     | 6         | 3.23%   |
| 6.0     | 4         | 2.15%   |
| 5.12    | 3         | 1.61%   |
| 4.20    | 3         | 1.61%   |
| 4.14    | 3         | 1.61%   |
| 5.0     | 2         | 1.08%   |
| 4.9     | 1         | 0.54%   |
| 4.18    | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 167       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 99        | 56.57%  |
| Unknown | 30        | 17.14%  |
| KDE     | 15        | 8.57%   |
| MATE    | 13        | 7.43%   |
| GNOME   | 13        | 7.43%   |
| KDE5    | 5         | 2.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 166       | 98.81%  |
| Wayland | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 126       | 73.68%  |
| TDM     | 19        | 11.11%  |
| LightDM | 17        | 9.94%   |
| SDDM    | 6         | 3.51%   |
| GDM     | 3         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 84        | 49.7%   |
| Unknown | 13        | 7.69%   |
| de_DE   | 9         | 5.33%   |
| pt_BR   | 8         | 4.73%   |
| es_ES   | 8         | 4.73%   |
| en_GB   | 8         | 4.73%   |
| ru_RU   | 7         | 4.14%   |
| fr_FR   | 7         | 4.14%   |
| en_AU   | 4         | 2.37%   |
| pl_PL   | 3         | 1.78%   |
| tr_TR   | 2         | 1.18%   |
| it_IT   | 2         | 1.18%   |
| en_NZ   | 2         | 1.18%   |
| uk_UA   | 1         | 0.59%   |
| pt_PT   | 1         | 0.59%   |
| nl_NL   | 1         | 0.59%   |
| es_VE   | 1         | 0.59%   |
| es_CL   | 1         | 0.59%   |
| en_IN   | 1         | 0.59%   |
| en_IE   | 1         | 0.59%   |
| en_DK   | 1         | 0.59%   |
| en_CA   | 1         | 0.59%   |
| de_AT   | 1         | 0.59%   |
| ar_SA   | 1         | 0.59%   |
| ar_EG   | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 97        | 57.06%  |
| BIOS | 73        | 42.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 157       | 92.9%   |
| Unknown | 9         | 5.33%   |
| Xfs     | 1         | 0.59%   |
| Overlay | 1         | 0.59%   |
| Btrfs   | 1         | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 119       | 68.79%  |
| GPT     | 43        | 24.86%  |
| MBR     | 11        | 6.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 154       | 91.67%  |
| Yes       | 14        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 81.29%  |
| Yes       | 32        | 18.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 22        | 13.17%  |
| Hewlett-Packard        | 21        | 12.57%  |
| ASUSTek Computer       | 20        | 11.98%  |
| Dell                   | 19        | 11.38%  |
| Gigabyte Technology    | 18        | 10.78%  |
| Acer                   | 15        | 8.98%   |
| MSI                    | 8         | 4.79%   |
| Toshiba                | 6         | 3.59%   |
| ASRock                 | 6         | 3.59%   |
| Samsung Electronics    | 3         | 1.8%    |
| Intel                  | 3         | 1.8%    |
| Google                 | 3         | 1.8%    |
| Apple                  | 3         | 1.8%    |
| Sony                   | 2         | 1.2%    |
| Biostar                | 2         | 1.2%    |
| Unknown                | 2         | 1.2%    |
| Timi                   | 1         | 0.6%    |
| Shuttle                | 1         | 0.6%    |
| Pegatron               | 1         | 0.6%    |
| Panasonic              | 1         | 0.6%    |
| Packard Bell           | 1         | 0.6%    |
| MEGA                   | 1         | 0.6%    |
| Howard Computers       | 1         | 0.6%    |
| GPU Company            | 1         | 0.6%    |
| Fujitsu                | 1         | 0.6%    |
| Framework              | 1         | 0.6%    |
| eMachines              | 1         | 0.6%    |
| Chuwi                  | 1         | 0.6%    |
| AZW                    | 1         | 0.6%    |
| Avell High Performance | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 3         | 1.8%    |
| HP ProBook 450 G5                                     | 2         | 1.2%    |
| Acer Aspire E5-575G                                   | 2         | 1.2%    |
| Toshiba TECRA R840                                    | 1         | 0.6%    |
| Toshiba Satellite P50-A                               | 1         | 0.6%    |
| Toshiba Satellite L855                                | 1         | 0.6%    |
| Toshiba Satellite L655                                | 1         | 0.6%    |
| Toshiba PORTEGE Z20T-B                                | 1         | 0.6%    |
| Timi TM1701                                           | 1         | 0.6%    |
| Sony VPCYB15AB                                        | 1         | 0.6%    |
| Sony VPCEB1S1E                                        | 1         | 0.6%    |
| Shuttle XS35V4                                        | 1         | 0.6%    |
| Samsung R430/P430/R480                                | 1         | 0.6%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.6%    |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 0.6%    |
| Pegatron IPM31                                        | 1         | 0.6%    |
| Panasonic CF-C2CCEZXCM                                | 1         | 0.6%    |
| Packard Bell EasyNote TS11HR                          | 1         | 0.6%    |
| MSI MS-7C91                                           | 1         | 0.6%    |
| MSI MS-7B89                                           | 1         | 0.6%    |
| MSI MS-7B85                                           | 1         | 0.6%    |
| MSI MS-7B84                                           | 1         | 0.6%    |
| MSI MS-7A34                                           | 1         | 0.6%    |
| MSI MS-7850                                           | 1         | 0.6%    |
| MSI MS-7640                                           | 1         | 0.6%    |
| MSI Modern 14 B5M                                     | 1         | 0.6%    |
| MEGA G41T-M7 LGT                                      | 1         | 0.6%    |
| Lenovo Z51-70 80K6                                    | 1         | 0.6%    |
| Lenovo Z50-70 20354                                   | 1         | 0.6%    |
| Lenovo Yoga 730-13IKB 81CT                            | 1         | 0.6%    |
| Lenovo Yoga 510-14ISK 80S7                            | 1         | 0.6%    |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.6%    |
| Lenovo ThinkPad W530 243852U                          | 1         | 0.6%    |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 0.6%    |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 0.6%    |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 0.6%    |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 0.6%    |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 0.6%    |
| Lenovo ThinkPad Edge E440 20C5A03300                  | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 9         | 5.39%   |
| Acer Aspire            | 9         | 5.39%   |
| HP ProBook             | 5         | 2.99%   |
| Dell Latitude          | 5         | 2.99%   |
| Dell Inspiron          | 5         | 2.99%   |
| Lenovo IdeaPad         | 4         | 2.4%    |
| HP Pavilion            | 4         | 2.4%    |
| Gigabyte Z390          | 4         | 2.4%    |
| Dell XPS               | 4         | 2.4%    |
| Toshiba Satellite      | 3         | 1.8%    |
| ASUS TUF               | 3         | 1.8%    |
| ASUS PRIME             | 3         | 1.8%    |
| Acer Swift             | 3         | 1.8%    |
| Unknown                | 3         | 1.8%    |
| Lenovo Yoga            | 2         | 1.2%    |
| HP ENVY                | 2         | 1.2%    |
| HP EliteBook           | 2         | 1.2%    |
| Dell Vostro            | 2         | 1.2%    |
| Dell OptiPlex          | 2         | 1.2%    |
| ASUS ROG               | 2         | 1.2%    |
| Toshiba TECRA          | 1         | 0.6%    |
| Toshiba PORTEGE        | 1         | 0.6%    |
| Timi TM1701            | 1         | 0.6%    |
| Sony VPCYB15AB         | 1         | 0.6%    |
| Sony VPCEB1S1E         | 1         | 0.6%    |
| Shuttle XS35V4         | 1         | 0.6%    |
| Samsung R430           | 1         | 0.6%    |
| Samsung 300E5EV        | 1         | 0.6%    |
| Samsung 270E5K         | 1         | 0.6%    |
| Pegatron IPM31         | 1         | 0.6%    |
| Panasonic CF-C2CCEZXCM | 1         | 0.6%    |
| Packard Bell EasyNote  | 1         | 0.6%    |
| MSI MS-7C91            | 1         | 0.6%    |
| MSI MS-7B89            | 1         | 0.6%    |
| MSI MS-7B85            | 1         | 0.6%    |
| MSI MS-7B84            | 1         | 0.6%    |
| MSI MS-7A34            | 1         | 0.6%    |
| MSI MS-7850            | 1         | 0.6%    |
| MSI MS-7640            | 1         | 0.6%    |
| MSI Modern             | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 28        | 16.77%  |
| 2019 | 18        | 10.78%  |
| 2016 | 15        | 8.98%   |
| 2017 | 13        | 7.78%   |
| 2014 | 13        | 7.78%   |
| 2013 | 11        | 6.59%   |
| 2012 | 11        | 6.59%   |
| 2021 | 10        | 5.99%   |
| 2011 | 10        | 5.99%   |
| 2020 | 9         | 5.39%   |
| 2010 | 8         | 4.79%   |
| 2008 | 7         | 4.19%   |
| 2015 | 6         | 3.59%   |
| 2009 | 4         | 2.4%    |
| 2006 | 3         | 1.8%    |
| 2007 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 95        | 56.89%  |
| Desktop     | 63        | 37.72%  |
| Convertible | 6         | 3.59%   |
| Tablet      | 1         | 0.6%    |
| Mini pc     | 1         | 0.6%    |
| All in one  | 1         | 0.6%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 167       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 98.2%   |
| Yes  | 3         | 1.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 42        | 24.85%  |
| 3.01-4.0    | 39        | 23.08%  |
| 8.01-16.0   | 33        | 19.53%  |
| 4.01-8.0    | 27        | 15.98%  |
| 32.01-64.0  | 18        | 10.65%  |
| 24.01-32.0  | 3         | 1.78%   |
| 2.01-3.0    | 3         | 1.78%   |
| 1.01-2.0    | 3         | 1.78%   |
| 64.01-256.0 | 1         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 65        | 36.11%  |
| 2.01-3.0  | 46        | 25.56%  |
| 4.01-8.0  | 24        | 13.33%  |
| 3.01-4.0  | 23        | 12.78%  |
| 8.01-16.0 | 11        | 6.11%   |
| 0.51-1.0  | 11        | 6.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 53.49%  |
| 2      | 50        | 29.07%  |
| 4      | 12        | 6.98%   |
| 3      | 10        | 5.81%   |
| 5      | 5         | 2.91%   |
| 6      | 2         | 1.16%   |
| 7      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 60.71%  |
| Yes       | 66        | 39.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 86.23%  |
| No        | 23        | 13.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 79.64%  |
| No        | 34        | 20.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 64.88%  |
| No        | 59        | 35.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 30        | 17.96%  |
| Brazil       | 11        | 6.59%   |
| Germany      | 10        | 5.99%   |
| India        | 9         | 5.39%   |
| Netherlands  | 8         | 4.79%   |
| Russia       | 7         | 4.19%   |
| France       | 6         | 3.59%   |
| Canada       | 6         | 3.59%   |
| Sweden       | 5         | 2.99%   |
| Spain        | 5         | 2.99%   |
| Australia    | 5         | 2.99%   |
| Poland       | 4         | 2.4%    |
| Norway       | 4         | 2.4%    |
| UK           | 3         | 1.8%    |
| Turkey       | 3         | 1.8%    |
| Switzerland  | 3         | 1.8%    |
| New Zealand  | 3         | 1.8%    |
| Argentina    | 3         | 1.8%    |
| Venezuela    | 2         | 1.2%    |
| Ukraine      | 2         | 1.2%    |
| Saudi Arabia | 2         | 1.2%    |
| Mexico       | 2         | 1.2%    |
| Iran         | 2         | 1.2%    |
| Indonesia    | 2         | 1.2%    |
| Guatemala    | 2         | 1.2%    |
| Greece       | 2         | 1.2%    |
| Chile        | 2         | 1.2%    |
| Albania      | 2         | 1.2%    |
| Vietnam      | 1         | 0.6%    |
| Thailand     | 1         | 0.6%    |
| Portugal     | 1         | 0.6%    |
| Philippines  | 1         | 0.6%    |
| Peru         | 1         | 0.6%    |
| Oman         | 1         | 0.6%    |
| Nepal        | 1         | 0.6%    |
| Latvia       | 1         | 0.6%    |
| Kazakhstan   | 1         | 0.6%    |
| Japan        | 1         | 0.6%    |
| Italy        | 1         | 0.6%    |
| Ireland      | 1         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toronto                | 3         | 1.69%   |
| Oslo                   | 3         | 1.69%   |
| Melbourne              | 3         | 1.69%   |
| Amsterdam              | 3         | 1.69%   |
| Zurich                 | 2         | 1.13%   |
| Stockholm              | 2         | 1.13%   |
| St Petersburg          | 2         | 1.13%   |
| Severna Park           | 2         | 1.13%   |
| San Justo              | 2         | 1.13%   |
| New York               | 2         | 1.13%   |
| Mainz                  | 2         | 1.13%   |
| Guelph                 | 2         | 1.13%   |
| Guatemala City         | 2         | 1.13%   |
| Curitiba               | 2         | 1.13%   |
| Columbus               | 2         | 1.13%   |
| Caracas                | 2         | 1.13%   |
| Auckland               | 2         | 1.13%   |
| Zhytomyr               | 1         | 0.56%   |
| Yverdon-les-Bains      | 1         | 0.56%   |
| Yekaterinburg          | 1         | 0.56%   |
| Wendell                | 1         | 0.56%   |
| Weil am Rhein          | 1         | 0.56%   |
| Vineland               | 1         | 0.56%   |
| Vienna                 | 1         | 0.56%   |
| Viby J                 | 1         | 0.56%   |
| Vasco da Gama          | 1         | 0.56%   |
| Vancouver              | 1         | 0.56%   |
| Uppsala                | 1         | 0.56%   |
| Trondheim              | 1         | 0.56%   |
| Trabzon                | 1         | 0.56%   |
| Tirana                 | 1         | 0.56%   |
| Thessaloniki           | 1         | 0.56%   |
| The Hague              | 1         | 0.56%   |
| Terranuova Bracciolini | 1         | 0.56%   |
| Teresopolis            | 1         | 0.56%   |
| Tehran                 | 1         | 0.56%   |
| SГЈo Pedro           | 1         | 0.56%   |
| Stroudsburg            | 1         | 0.56%   |
| Stare Babice           | 1         | 0.56%   |
| Songkhla               | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 64     | 17.36%  |
| Samsung Electronics | 41        | 70     | 15.47%  |
| Seagate             | 32        | 54     | 12.08%  |
| Toshiba             | 23        | 28     | 8.68%   |
| Kingston            | 18        | 22     | 6.79%   |
| SanDisk             | 17        | 23     | 6.42%   |
| Unknown             | 15        | 17     | 5.66%   |
| Intel               | 13        | 16     | 4.91%   |
| Crucial             | 9         | 10     | 3.4%    |
| SK hynix            | 8         | 8      | 3.02%   |
| Micron Technology   | 6         | 7      | 2.26%   |
| Hitachi             | 5         | 5      | 1.89%   |
| A-DATA Technology   | 4         | 4      | 1.51%   |
| PNY                 | 3         | 3      | 1.13%   |
| Silicon Motion      | 2         | 2      | 0.75%   |
| Phison              | 2         | 2      | 0.75%   |
| HGST                | 2         | 2      | 0.75%   |
| China               | 2         | 2      | 0.75%   |
| Apple               | 2         | 6      | 0.75%   |
| Transcend           | 1         | 1      | 0.38%   |
| SPCC Sol            | 1         | 1      | 0.38%   |
| SABRENT             | 1         | 1      | 0.38%   |
| Patriot             | 1         | 1      | 0.38%   |
| Maxtor              | 1         | 1      | 0.38%   |
| Lenovo              | 1         | 1      | 0.38%   |
| KIOXIA              | 1         | 1      | 0.38%   |
| KingFast            | 1         | 1      | 0.38%   |
| Intenso             | 1         | 2      | 0.38%   |
| HFS512GD            | 1         | 1      | 0.38%   |
| Gigabyte Technology | 1         | 1      | 0.38%   |
| FORESEE             | 1         | 1      | 0.38%   |
| Corsair             | 1         | 1      | 0.38%   |
| Advantech           | 1         | 1      | 0.38%   |
| AAPL                | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB               | 8         | 2.68%   |
| Samsung NVMe SSD Drive 500GB            | 7         | 2.35%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 2.01%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.68%   |
| Samsung SSD 850 EVO 500GB               | 5         | 1.68%   |
| Samsung SSD 860 EVO 500GB               | 4         | 1.34%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 1.01%   |
| SK hynix NVMe SSD Drive 128GB           | 3         | 1.01%   |
| Seagate ST500DM002-1BD142 500GB         | 3         | 1.01%   |
| Seagate ST31000528AS 1TB                | 3         | 1.01%   |
| Seagate ST2000DX002-2DV164 2TB          | 3         | 1.01%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 1.01%   |
| Samsung SSD 860 EVO 250GB               | 3         | 1.01%   |
| Intel NVMe SSD Drive 256GB              | 3         | 1.01%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.01%   |
| WDC WD5000AAKS-00A7B0 500GB             | 2         | 0.67%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 2         | 0.67%   |
| WDC WD2003FZEX-00SRLA0 2TB              | 2         | 0.67%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 0.67%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.67%   |
| WDC WD10EZEX-08M2NA0 1TB                | 2         | 0.67%   |
| WDC WD10EADS-00M2B0 1TB                 | 2         | 0.67%   |
| Unknown TP02000GB 2TB                   | 2         | 0.67%   |
| Unknown MMC Card  32GB                  | 2         | 0.67%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 0.67%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.67%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB | 2         | 0.67%   |
| Seagate ST31000524AS 1TB                | 2         | 0.67%   |
| Seagate ST2000DX001-1NS164 2TB          | 2         | 0.67%   |
| Seagate ST2000DM006-2DM164 2TB          | 2         | 0.67%   |
| SanDisk SDSSDA240G 240GB                | 2         | 0.67%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.67%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.67%   |
| PNY CS900 240GB SSD                     | 2         | 0.67%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.67%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.67%   |
| Intel NVMe SSD Drive 1024GB             | 2         | 0.67%   |
| Hitachi HTS545032B9A300 320GB           | 2         | 0.67%   |
| Crucial CT1000P1SSD8 1TB                | 2         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 41        | 58     | 40.2%   |
| Seagate             | 32        | 54     | 31.37%  |
| Toshiba             | 15        | 20     | 14.71%  |
| Hitachi             | 5         | 5      | 4.9%    |
| Samsung Electronics | 3         | 3      | 2.94%   |
| HGST                | 2         | 2      | 1.96%   |
| Unknown             | 1         | 1      | 0.98%   |
| Maxtor              | 1         | 1      | 0.98%   |
| Intenso             | 1         | 2      | 0.98%   |
| AAPL                | 1         | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 42     | 32.61%  |
| Kingston            | 12        | 15     | 13.04%  |
| SanDisk             | 10        | 14     | 10.87%  |
| Crucial             | 7         | 8      | 7.61%   |
| Micron Technology   | 5         | 6      | 5.43%   |
| Intel               | 4         | 5      | 4.35%   |
| WDC                 | 3         | 3      | 3.26%   |
| PNY                 | 3         | 3      | 3.26%   |
| A-DATA Technology   | 3         | 3      | 3.26%   |
| Unknown             | 2         | 2      | 2.17%   |
| Toshiba             | 2         | 2      | 2.17%   |
| China               | 2         | 2      | 2.17%   |
| Apple               | 2         | 6      | 2.17%   |
| Transcend           | 1         | 1      | 1.09%   |
| SPCC Sol            | 1         | 1      | 1.09%   |
| Patriot             | 1         | 1      | 1.09%   |
| Gigabyte Technology | 1         | 1      | 1.09%   |
| FORESEE             | 1         | 1      | 1.09%   |
| Corsair             | 1         | 1      | 1.09%   |
| Advantech           | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 88        | 147    | 36.67%  |
| SSD     | 79        | 118    | 32.92%  |
| NVMe    | 56        | 76     | 23.33%  |
| MMC     | 10        | 11     | 4.17%   |
| Unknown | 7         | 9      | 2.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 124       | 253    | 61.08%  |
| NVMe | 56        | 75     | 27.59%  |
| SAS  | 13        | 22     | 6.4%    |
| MMC  | 10        | 11     | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 98        | 157    | 57.65%  |
| 0.51-1.0   | 49        | 67     | 28.82%  |
| 1.01-2.0   | 18        | 34     | 10.59%  |
| 3.01-4.0   | 2         | 4      | 1.18%   |
| 4.01-10.0  | 2         | 2      | 1.18%   |
| 10.01-20.0 | 1         | 1      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 35.09%  |
| 251-500        | 37        | 21.64%  |
| 501-1000       | 30        | 17.54%  |
| 1001-2000      | 13        | 7.6%    |
| More than 3000 | 8         | 4.68%   |
| 51-100         | 8         | 4.68%   |
| 21-50          | 6         | 3.51%   |
| 2001-3000      | 5         | 2.92%   |
| 1-20           | 2         | 1.17%   |
| Unknown        | 2         | 1.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 58        | 32.77%  |
| 21-50          | 32        | 18.08%  |
| 101-250        | 24        | 13.56%  |
| 251-500        | 18        | 10.17%  |
| 51-100         | 18        | 10.17%  |
| 501-1000       | 11        | 6.21%   |
| 1001-2000      | 9         | 5.08%   |
| 2001-3000      | 3         | 1.69%   |
| More than 3000 | 2         | 1.13%   |
| Unknown        | 2         | 1.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB                    | 1         | 1      | 9.09%   |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 9.09%   |
| WDC WD1002FAEX-00Y9A0 1TB                      | 1         | 1      | 9.09%   |
| WDC WD1001FALS-75J7B0 1TB                      | 1         | 1      | 9.09%   |
| Seagate ST9320325AS 320GB                      | 1         | 2      | 9.09%   |
| Seagate ST2000DM001-9YN164 2TB                 | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 970 EVO 500GB          | 1         | 1      | 9.09%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB   | 1         | 1      | 9.09%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 9.09%   |
| Crucial CT1000P1SSD8 1TB                       | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 2         | 3      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Micron Technology   | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| Crucial             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 57.14%  |
| Seagate | 2         | 3      | 28.57%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 8      | 60%     |
| NVMe | 3         | 3      | 30%     |
| SSD  | 1         | 1      | 10%     |

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
| Detected | 127       | 274    | 68.65%  |
| Works    | 48        | 75     | 25.95%  |
| Malfunc  | 10        | 12     | 5.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 115       | 54.25%  |
| AMD                          | 37        | 17.45%  |
| Samsung Electronics          | 18        | 8.49%   |
| SK hynix                     | 8         | 3.77%   |
| Toshiba America Info Systems | 6         | 2.83%   |
| SanDisk                      | 6         | 2.83%   |
| Kingston Technology Company  | 6         | 2.83%   |
| JMicron Technology           | 3         | 1.42%   |
| Silicon Motion               | 2         | 0.94%   |
| Phison Electronics           | 2         | 0.94%   |
| Micron/Crucial Technology    | 2         | 0.94%   |
| Marvell Technology Group     | 2         | 0.94%   |
| Nvidia                       | 1         | 0.47%   |
| Micron Technology            | 1         | 0.47%   |
| Lenovo                       | 1         | 0.47%   |
| ASMedia Technology           | 1         | 0.47%   |
| ADATA Technology             | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28        | 11.52%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 5.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12        | 4.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 4.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8         | 3.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 3.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8         | 3.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 2.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 2.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 2.06%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 4         | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 1.65%   |
| Intel SSD 660P Series                                                                   | 4         | 1.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.65%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 3         | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.23%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.82%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 2         | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.82%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2         | 0.82%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.82%   |
| Kingston Company KC2000 NVMe SSD                                                        | 2         | 0.82%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 2         | 0.82%   |
| Intel SSD 600P Series                                                                   | 2         | 0.82%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 129       | 61.72%  |
| NVMe | 56        | 26.79%  |
| IDE  | 18        | 8.61%   |
| RAID | 6         | 2.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 128       | 76.65%  |
| AMD    | 39        | 23.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 3.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.4%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 2.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.2%    |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 1.2%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 1.2%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.2%    |
| Intel Core i7-2600K CPU @ 3.40GHz             | 2         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.2%    |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 1.2%    |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 1.2%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.2%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.2%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.2%    |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.2%    |
| AMD Ryzen 5 2600X Six-Core Processor          | 2         | 1.2%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.2%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.6%    |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz           | 1         | 0.6%    |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.6%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1         | 0.6%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.6%    |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.6%    |
| Intel Pentium D CPU 3.00GHz                   | 1         | 0.6%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.6%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.6%    |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.6%    |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.6%    |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.6%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 1         | 0.6%    |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 23.95%  |
| Intel Core i7           | 34        | 20.36%  |
| AMD Ryzen 7             | 14        | 8.38%   |
| Intel Core i3           | 13        | 7.78%   |
| Intel Celeron           | 13        | 7.78%   |
| AMD Ryzen 5             | 13        | 7.78%   |
| Other                   | 4         | 2.4%    |
| Intel Pentium           | 4         | 2.4%    |
| Intel Core 2 Duo        | 4         | 2.4%    |
| Intel Xeon              | 3         | 1.8%    |
| Intel Pentium Dual-Core | 3         | 1.8%    |
| AMD Ryzen 9             | 3         | 1.8%    |
| Intel Pentium D         | 2         | 1.2%    |
| Intel Core 2 Quad       | 2         | 1.2%    |
| Intel Atom              | 2         | 1.2%    |
| AMD Phenom II X4        | 2         | 1.2%    |
| AMD FX                  | 2         | 1.2%    |
| AMD A10                 | 2         | 1.2%    |
| Intel Pentium Silver    | 1         | 0.6%    |
| Intel Pentium Dual      | 1         | 0.6%    |
| Intel Core M            | 1         | 0.6%    |
| Intel Core i9           | 1         | 0.6%    |
| Intel Core 2            | 1         | 0.6%    |
| AMD E1                  | 1         | 0.6%    |
| AMD E                   | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 73        | 43.71%  |
| 4      | 59        | 35.33%  |
| 6      | 16        | 9.58%   |
| 8      | 15        | 8.98%   |
| 16     | 1         | 0.6%    |
| 12     | 1         | 0.6%    |
| 3      | 1         | 0.6%    |
| 1      | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 167       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 122       | 73.05%  |
| 1      | 45        | 26.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 162       | 96.43%  |
| Unknown        | 6         | 3.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 7.02%   |
| 0x806ea    | 11        | 6.43%   |
| 0x306c3    | 11        | 6.43%   |
| 0x306a9    | 10        | 5.85%   |
| 0x206a7    | 10        | 5.85%   |
| 0x1067a    | 8         | 4.68%   |
| 0x806e9    | 6         | 3.51%   |
| 0x40651    | 6         | 3.51%   |
| 0x906e9    | 5         | 2.92%   |
| 0x506e3    | 5         | 2.92%   |
| 0x20655    | 5         | 2.92%   |
| 0x08701021 | 5         | 2.92%   |
| 0x906ea    | 4         | 2.34%   |
| 0x806ec    | 4         | 2.34%   |
| 0x706a1    | 4         | 2.34%   |
| 0x406e3    | 4         | 2.34%   |
| 0x0800820d | 4         | 2.34%   |
| 0x806c1    | 3         | 1.75%   |
| 0x306d4    | 3         | 1.75%   |
| 0x30678    | 3         | 1.75%   |
| 0x08701013 | 3         | 1.75%   |
| 0x08108102 | 3         | 1.75%   |
| 0x906ec    | 2         | 1.17%   |
| 0x6fd      | 2         | 1.17%   |
| 0x0a50000c | 2         | 1.17%   |
| 0x08600106 | 2         | 1.17%   |
| 0x08108109 | 2         | 1.17%   |
| 0x0810100b | 2         | 1.17%   |
| 0x06003106 | 2         | 1.17%   |
| 0x06000852 | 2         | 1.17%   |
| 0xf64      | 1         | 0.58%   |
| 0xf62      | 1         | 0.58%   |
| 0xa0652    | 1         | 0.58%   |
| 0x906ed    | 1         | 0.58%   |
| 0x906eb    | 1         | 0.58%   |
| 0x906c0    | 1         | 0.58%   |
| 0x806eb    | 1         | 0.58%   |
| 0x706a8    | 1         | 0.58%   |
| 0x6f2      | 1         | 0.58%   |
| 0x506c9    | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 38        | 22.75%  |
| Haswell       | 19        | 11.38%  |
| Zen 2         | 11        | 6.59%   |
| SandyBridge   | 11        | 6.59%   |
| Zen+          | 10        | 5.99%   |
| Penryn        | 10        | 5.99%   |
| IvyBridge     | 10        | 5.99%   |
| Skylake       | 9         | 5.39%   |
| Westmere      | 6         | 3.59%   |
| Silvermont    | 5         | 2.99%   |
| Goldmont plus | 5         | 2.99%   |
| Zen 3         | 4         | 2.4%    |
| Core          | 4         | 2.4%    |
| Zen           | 3         | 1.8%    |
| TigerLake     | 3         | 1.8%    |
| Broadwell     | 3         | 1.8%    |
| Steamroller   | 2         | 1.2%    |
| Piledriver    | 2         | 1.2%    |
| NetBurst      | 2         | 1.2%    |
| K10           | 2         | 1.2%    |
| Bobcat        | 2         | 1.2%    |
| Unknown       | 2         | 1.2%    |
| Tremont       | 1         | 0.6%    |
| Goldmont      | 1         | 0.6%    |
| Excavator     | 1         | 0.6%    |
| CometLake     | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 49.28%  |
| Nvidia | 57        | 27.54%  |
| AMD    | 48        | 23.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 10        | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8         | 3.81%   |
| Intel HD Graphics 620                                                       | 7         | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 3.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5         | 2.38%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 1.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4         | 1.9%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 1.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.43%   |
| Nvidia GM108M [GeForce 940MX]                                               | 3         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.43%   |
| Intel HD Graphics 630                                                       | 3         | 1.43%   |
| Intel HD Graphics 530                                                       | 3         | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.43%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 1.43%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.95%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.95%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.95%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 0.95%   |
| Nvidia GM108M [GeForce 930MX]                                               | 2         | 0.95%   |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 0.95%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 2         | 0.95%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 0.95%   |
| Nvidia GF108M [GeForce GT 540M]                                             | 2         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 0.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 0.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 0.95%   |
| Intel HD Graphics 5500                                                      | 2         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 0.95%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                            | 2         | 0.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 39.05%  |
| 1 x AMD        | 39        | 23.08%  |
| 1 x Nvidia     | 27        | 15.98%  |
| Intel + Nvidia | 27        | 15.98%  |
| Intel + AMD    | 6         | 3.55%   |
| AMD + Nvidia   | 4         | 2.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 128       | 76.65%  |
| Proprietary | 39        | 23.35%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 42.26%  |
| 1.01-2.0   | 28        | 16.67%  |
| 0.51-1.0   | 21        | 12.5%   |
| 3.01-4.0   | 12        | 7.14%   |
| 5.01-6.0   | 11        | 6.55%   |
| 7.01-8.0   | 9         | 5.36%   |
| 0.01-0.5   | 9         | 5.36%   |
| 8.01-16.0  | 4         | 2.38%   |
| 2.01-3.0   | 3         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 14.95%  |
| Samsung Electronics     | 25        | 12.89%  |
| LG Display              | 16        | 8.25%   |
| BOE                     | 15        | 7.73%   |
| Goldstar                | 14        | 7.22%   |
| Chimei Innolux          | 14        | 7.22%   |
| AOC                     | 11        | 5.67%   |
| Dell                    | 9         | 4.64%   |
| Ancor Communications    | 8         | 4.12%   |
| BenQ                    | 6         | 3.09%   |
| Lenovo                  | 5         | 2.58%   |
| Sharp                   | 4         | 2.06%   |
| LG Electronics          | 4         | 2.06%   |
| Acer                    | 4         | 2.06%   |
| Hewlett-Packard         | 3         | 1.55%   |
| ASUSTek Computer        | 3         | 1.55%   |
| Apple                   | 3         | 1.55%   |
| Unknown                 | 2         | 1.03%   |
| Philips                 | 2         | 1.03%   |
| PANDA                   | 2         | 1.03%   |
| NEC Computers           | 2         | 1.03%   |
| Chi Mei Optoelectronics | 2         | 1.03%   |
| ___                     | 1         | 0.52%   |
| ViewSonic               | 1         | 0.52%   |
| Toshiba                 | 1         | 0.52%   |
| Sony                    | 1         | 0.52%   |
| MSI                     | 1         | 0.52%   |
| Microstep               | 1         | 0.52%   |
| JRY                     | 1         | 0.52%   |
| Iiyama                  | 1         | 0.52%   |
| GKK                     | 1         | 0.52%   |
| CSO                     | 1         | 0.52%   |
| Unknown                 | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 3         | 1.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 2         | 1%      |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 1%      |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1%      |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1%      |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1%      |
| Ancor Communications LCD Monitor MG248 1920x1080                      | 2         | 1%      |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.5%    |
| ViewSonic VP191b VSC0E11 1280x1024 376x301mm 19.0-inch                | 1         | 0.5%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.5%    |
| Unknown LCD Monitor HIC 3200x1080                                     | 1         | 0.5%    |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch             | 1         | 0.5%    |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.5%    |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.5%    |
| Sharp LCD Monitor HDMI 1920x1080                                      | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch  | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch  | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch  | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch   | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.5%    |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch   | 1         | 0.5%    |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.5%    |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1         | 0.5%    |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch    | 1         | 0.5%    |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch     | 1         | 0.5%    |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch     | 1         | 0.5%    |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch      | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4250 1920x1080 276x156mm 12.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 80        | 43.72%  |
| 1366x768 (WXGA)    | 39        | 21.31%  |
| 1600x900 (HD+)     | 11        | 6.01%   |
| 2560x1440 (QHD)    | 8         | 4.37%   |
| 1280x1024 (SXGA)   | 7         | 3.83%   |
| 3840x2160 (4K)     | 6         | 3.28%   |
| 1440x900 (WXGA+)   | 6         | 3.28%   |
| Unknown            | 5         | 2.73%   |
| 2560x1080          | 3         | 1.64%   |
| 1280x800 (WXGA)    | 3         | 1.64%   |
| 1920x1200 (WUXGA)  | 2         | 1.09%   |
| 1680x1050 (WSXGA+) | 2         | 1.09%   |
| 1360x768           | 2         | 1.09%   |
| 5760x1080          | 1         | 0.55%   |
| 4480x1440          | 1         | 0.55%   |
| 3840x1080          | 1         | 0.55%   |
| 3440x1440          | 1         | 0.55%   |
| 3200x1080          | 1         | 0.55%   |
| 2560x1600          | 1         | 0.55%   |
| 2256x1504          | 1         | 0.55%   |
| 1152x864           | 1         | 0.55%   |
| 1024x768 (XGA)     | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 56        | 29.95%  |
| 13      | 24        | 12.83%  |
| Unknown | 20        | 10.7%   |
| 24      | 14        | 7.49%   |
| 27      | 11        | 5.88%   |
| 14      | 11        | 5.88%   |
| 17      | 10        | 5.35%   |
| 21      | 9         | 4.81%   |
| 23      | 8         | 4.28%   |
| 18      | 6         | 3.21%   |
| 20      | 3         | 1.6%    |
| 19      | 3         | 1.6%    |
| 34      | 2         | 1.07%   |
| 12      | 2         | 1.07%   |
| 11      | 2         | 1.07%   |
| 72      | 1         | 0.53%   |
| 40      | 1         | 0.53%   |
| 31      | 1         | 0.53%   |
| 29      | 1         | 0.53%   |
| 25      | 1         | 0.53%   |
| 22      | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 79        | 42.7%   |
| 501-600     | 31        | 16.76%  |
| 401-500     | 21        | 11.35%  |
| Unknown     | 20        | 10.81%  |
| 201-300     | 16        | 8.65%   |
| 351-400     | 11        | 5.95%   |
| 601-700     | 3         | 1.62%   |
| 701-800     | 2         | 1.08%   |
| 801-900     | 1         | 0.54%   |
| 1501-2000   | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 126       | 73.26%  |
| Unknown | 19        | 11.05%  |
| 16/10   | 15        | 8.72%   |
| 5/4     | 4         | 2.33%   |
| 21/9    | 3         | 1.74%   |
| 4/3     | 2         | 1.16%   |
| 3/2     | 2         | 1.16%   |
| 6/5     | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 54        | 28.72%  |
| 201-250        | 27        | 14.36%  |
| 81-90          | 25        | 13.3%   |
| Unknown        | 20        | 10.64%  |
| 301-350        | 12        | 6.38%   |
| 71-80          | 10        | 5.32%   |
| 151-200        | 9         | 4.79%   |
| 141-150        | 7         | 3.72%   |
| 121-130        | 7         | 3.72%   |
| 251-300        | 6         | 3.19%   |
| 351-500        | 3         | 1.6%    |
| 61-70          | 2         | 1.06%   |
| 51-60          | 2         | 1.06%   |
| More than 1000 | 1         | 0.53%   |
| 111-120        | 1         | 0.53%   |
| 501-1000       | 1         | 0.53%   |
| 91-100         | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 54        | 29.67%  |
| 101-120       | 46        | 25.27%  |
| 121-160       | 44        | 24.18%  |
| Unknown       | 20        | 10.99%  |
| 161-240       | 13        | 7.14%   |
| More than 240 | 4         | 2.2%    |
| 1-50          | 1         | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 134       | 79.29%  |
| 2     | 32        | 18.93%  |
| 3     | 3         | 1.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 93        | 35.5%   |
| Intel                         | 79        | 30.15%  |
| Qualcomm Atheros              | 38        | 14.5%   |
| Broadcom                      | 13        | 4.96%   |
| MediaTek                      | 4         | 1.53%   |
| Marvell Technology Group      | 4         | 1.53%   |
| TP-Link                       | 3         | 1.15%   |
| Ralink Technology             | 3         | 1.15%   |
| Xiaomi                        | 2         | 0.76%   |
| Ralink                        | 2         | 0.76%   |
| Dell                          | 2         | 0.76%   |
| T & A Mobile Phones           | 1         | 0.38%   |
| Sierra Wireless               | 1         | 0.38%   |
| Samsung Electronics           | 1         | 0.38%   |
| Qualcomm                      | 1         | 0.38%   |
| OnePlus Technology (Shenzhen) | 1         | 0.38%   |
| Nvidia                        | 1         | 0.38%   |
| NetGear                       | 1         | 0.38%   |
| Microchip Technology          | 1         | 0.38%   |
| Linksys                       | 1         | 0.38%   |
| Lenovo                        | 1         | 0.38%   |
| Jolla Oy                      | 1         | 0.38%   |
| Huawei Technologies           | 1         | 0.38%   |
| Hewlett-Packard               | 1         | 0.38%   |
| D-Link System                 | 1         | 0.38%   |
| Broadcom Limited              | 1         | 0.38%   |
| Belkin Components             | 1         | 0.38%   |
| ASIX Electronics              | 1         | 0.38%   |
| Aquantia                      | 1         | 0.38%   |
| Android                       | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 22.73%  |
| Intel Wi-Fi 6 AX200                                               | 10        | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.92%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.92%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.62%   |
| Intel Wireless 7265                                               | 5         | 1.62%   |
| Intel Wireless 7260                                               | 5         | 1.62%   |
| Intel Wireless 3165                                               | 5         | 1.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.97%   |
| Intel Wireless 8260                                               | 3         | 0.97%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.65%   |
| Realtek RTL8187 Wireless Adapter                                  | 2         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.65%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                  | 2         | 0.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.65%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.65%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 43.45%  |
| Qualcomm Atheros      | 34        | 23.45%  |
| Realtek Semiconductor | 19        | 13.1%   |
| Broadcom              | 10        | 6.9%    |
| MediaTek              | 4         | 2.76%   |
| Ralink Technology     | 3         | 2.07%   |
| TP-Link               | 2         | 1.38%   |
| Ralink                | 2         | 1.38%   |
| Sierra Wireless       | 1         | 0.69%   |
| NetGear               | 1         | 0.69%   |
| Linksys               | 1         | 0.69%   |
| Hewlett-Packard       | 1         | 0.69%   |
| Dell                  | 1         | 0.69%   |
| D-Link System         | 1         | 0.69%   |
| Broadcom Limited      | 1         | 0.69%   |
| Belkin Components     | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 10        | 6.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 6.16%   |
| Intel Wireless 8265 / 8275                                     | 9         | 6.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 4.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 4.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 3.42%   |
| Intel Wireless 7265                                            | 5         | 3.42%   |
| Intel Wireless 7260                                            | 5         | 3.42%   |
| Intel Wireless 3165                                            | 5         | 3.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 2.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.05%   |
| Intel Wireless 8260                                            | 3         | 2.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.37%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 1.37%   |
| Qualcomm Atheros AR922X Wireless Network Adapter               | 2         | 1.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 1.37%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.37%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.37%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.37%   |
| Sierra Wireless EM7305                                         | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.68%   |
| Realtek 802.11ac NIC                                           | 1         | 0.68%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 84        | 54.19%  |
| Intel                    | 43        | 27.74%  |
| Qualcomm Atheros         | 7         | 4.52%   |
| Broadcom                 | 5         | 3.23%   |
| Marvell Technology Group | 4         | 2.58%   |
| Xiaomi                   | 2         | 1.29%   |
| TP-Link                  | 1         | 0.65%   |
| Samsung Electronics      | 1         | 0.65%   |
| Qualcomm                 | 1         | 0.65%   |
| Nvidia                   | 1         | 0.65%   |
| Lenovo                   | 1         | 0.65%   |
| Jolla Oy                 | 1         | 0.65%   |
| Huawei Technologies      | 1         | 0.65%   |
| ASIX Electronics         | 1         | 0.65%   |
| Aquantia                 | 1         | 0.65%   |
| Android                  | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 70        | 44.3%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 5.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 3.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.9%    |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.9%    |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 1.27%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.27%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.63%   |
| Qualcomm Nokia 5.4                                                             | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.63%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.63%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.63%   |
| Lenovo Thinkpad LAN                                                            | 1         | 0.63%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 0.63%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.63%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.63%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.63%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 144       | 51.25%  |
| WiFi     | 133       | 47.33%  |
| Modem    | 2         | 0.71%   |
| Unknown  | 2         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 64%     |
| Ethernet | 63        | 36%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 95        | 56.55%  |
| 1     | 67        | 39.88%  |
| 3     | 4         | 2.38%   |
| 0     | 2         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 150       | 87.72%  |
| Yes  | 21        | 12.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 46.43%  |
| Qualcomm Atheros Communications | 11        | 9.82%   |
| Lite-On Technology              | 9         | 8.04%   |
| Cambridge Silicon Radio         | 8         | 7.14%   |
| Broadcom                        | 8         | 7.14%   |
| Realtek Semiconductor           | 7         | 6.25%   |
| Apple                           | 4         | 3.57%   |
| IMC Networks                    | 3         | 2.68%   |
| MediaTek                        | 2         | 1.79%   |
| Foxconn / Hon Hai               | 2         | 1.79%   |
| ASUSTek Computer                | 2         | 1.79%   |
| Toshiba                         | 1         | 0.89%   |
| Ralink                          | 1         | 0.89%   |
| Hewlett-Packard                 | 1         | 0.89%   |
| Dell                            | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 27        | 24.11%  |
| Intel AX200 Bluetooth                                                               | 9         | 8.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 7.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 4.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.68%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.68%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.68%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.68%   |
| Intel AX201 Bluetooth                                                               | 3         | 2.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.79%   |
| MediaTek Wireless_Device                                                            | 2         | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.79%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.79%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.79%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.89%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.89%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.89%   |
| Lite-On Wireless_Device                                                             | 1         | 0.89%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.89%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.89%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.89%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.89%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.89%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.89%   |
| Broadcom BCM92045B3 ROM                                                             | 1         | 0.89%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.89%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.89%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.89%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 124       | 51.88%  |
| AMD                     | 52        | 21.76%  |
| Nvidia                  | 40        | 16.74%  |
| Blue Microphones        | 4         | 1.67%   |
| C-Media Electronics     | 3         | 1.26%   |
| Logitech                | 2         | 0.84%   |
| Yamaha                  | 1         | 0.42%   |
| Texas Instruments       | 1         | 0.42%   |
| Tenx Technology         | 1         | 0.42%   |
| SteelSeries ApS         | 1         | 0.42%   |
| SAVITECH                | 1         | 0.42%   |
| Samsung Electronics     | 1         | 0.42%   |
| RME                     | 1         | 0.42%   |
| JMTek                   | 1         | 0.42%   |
| GYROCOM C&C             | 1         | 0.42%   |
| Creative Technology     | 1         | 0.42%   |
| Creative Labs           | 1         | 0.42%   |
| Cooler Master           | 1         | 0.42%   |
| Conexant Systems        | 1         | 0.42%   |
| BEHRINGER International | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 7.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 4.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 3.86%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 3.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 2.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.46%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.46%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.75%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.75%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.4%    |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.05%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.05%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.05%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3         | 1.05%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 23.68%  |
| SK hynix            | 10        | 13.16%  |
| Unknown             | 7         | 9.21%   |
| Corsair             | 7         | 9.21%   |
| Crucial             | 6         | 7.89%   |
| A-DATA Technology   | 6         | 7.89%   |
| Micron Technology   | 5         | 6.58%   |
| Kingston            | 5         | 6.58%   |
| Nanya Technology    | 3         | 3.95%   |
| Ramaxel Technology  | 2         | 2.63%   |
| G.Skill             | 2         | 2.63%   |
| Elpida              | 2         | 2.63%   |
| Transcend           | 1         | 1.32%   |
| Team                | 1         | 1.32%   |
| Patriot             | 1         | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 2.5%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 2.5%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 2         | 2.5%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1867MT/s                   | 1         | 1.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.25%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.25%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.25%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                     | 1         | 1.25%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                     | 1         | 1.25%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.25%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM 1600MT/s                     | 1         | 1.25%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 1.25%   |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 1.25%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.25%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.25%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.25%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.25%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.25%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 1         | 1.25%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.25%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.25%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.25%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.25%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.25%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.25%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.25%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s              | 1         | 1.25%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.25%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 1.25%   |
| Ramaxel RAM RMT3170EB68E9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 31        | 48.44%  |
| DDR3   | 23        | 35.94%  |
| LPDDR3 | 5         | 7.81%   |
| DDR2   | 2         | 3.13%   |
| SDRAM  | 1         | 1.56%   |
| LPDDR4 | 1         | 1.56%   |
| DDR    | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 69.84%  |
| DIMM         | 15        | 23.81%  |
| Row Of Chips | 4         | 6.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 41.18%  |
| 4096  | 21        | 30.88%  |
| 16384 | 8         | 11.76%  |
| 2048  | 8         | 11.76%  |
| 32768 | 2         | 2.94%   |
| 1024  | 1         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 18        | 25%     |
| 2667    | 9         | 12.5%   |
| 3200    | 8         | 11.11%  |
| 2400    | 8         | 11.11%  |
| 2133    | 8         | 11.11%  |
| 3466    | 2         | 2.78%   |
| 1867    | 2         | 2.78%   |
| 1334    | 2         | 2.78%   |
| Unknown | 2         | 2.78%   |
| 4267    | 1         | 1.39%   |
| 3866    | 1         | 1.39%   |
| 3733    | 1         | 1.39%   |
| 3600    | 1         | 1.39%   |
| 3266    | 1         | 1.39%   |
| 3000    | 1         | 1.39%   |
| 2048    | 1         | 1.39%   |
| 1800    | 1         | 1.39%   |
| 1333    | 1         | 1.39%   |
| 1067    | 1         | 1.39%   |
| 1066    | 1         | 1.39%   |
| 800     | 1         | 1.39%   |
| 667     | 1         | 1.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 50%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP DeskJet 3630 series | 1         | 25%     |
| Canon LBP7010C/7018C   | 1         | 25%     |
| Canon G3000 series     | 1         | 25%     |
| Brother MFC-9330CDW    | 1         | 25%     |

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
| Chicony Electronics                    | 23        | 20.35%  |
| Microdia                               | 11        | 9.73%   |
| Logitech                               | 11        | 9.73%   |
| Realtek Semiconductor                  | 10        | 8.85%   |
| IMC Networks                           | 8         | 7.08%   |
| Quanta                                 | 6         | 5.31%   |
| Acer                                   | 6         | 5.31%   |
| Sunplus Innovation Technology          | 5         | 4.42%   |
| Suyin                                  | 4         | 3.54%   |
| Lite-On Technology                     | 4         | 3.54%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.54%   |
| Apple                                  | 3         | 2.65%   |
| Syntek                                 | 2         | 1.77%   |
| Microsoft                              | 2         | 1.77%   |
| Lenovo                                 | 2         | 1.77%   |
| Importek                               | 2         | 1.77%   |
| Z-Star Microelectronics                | 1         | 0.88%   |
| Unknown                                | 1         | 0.88%   |
| Silicon Motion                         | 1         | 0.88%   |
| Samsung Electronics                    | 1         | 0.88%   |
| MacroSilicon                           | 1         | 0.88%   |
| Luxvisions Innotech Limited            | 1         | 0.88%   |
| LG Electronics                         | 1         | 0.88%   |
| Intel                                  | 1         | 0.88%   |
| Hewlett-Packard                        | 1         | 0.88%   |
| A4Tech                                 | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 6         | 5.22%   |
| Microdia Integrated_Webcam_HD                 | 4         | 3.48%   |
| Chicony Integrated Camera                     | 4         | 3.48%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 2.61%   |
| Realtek HD WebCam                             | 3         | 2.61%   |
| Logitech HD Pro Webcam C920                   | 3         | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam             | 3         | 2.61%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 1.74%   |
| Realtek Integrated Webcam_HD                  | 2         | 1.74%   |
| Quanta HD User Facing                         | 2         | 1.74%   |
| Microdia USB 2.0 Camera                       | 2         | 1.74%   |
| Microdia Camera                               | 2         | 1.74%   |
| Logitech Webcam C270                          | 2         | 1.74%   |
| Logitech Logitech Webcam C160                 | 2         | 1.74%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 1.74%   |
| IMC Networks Integrated Camera                | 2         | 1.74%   |
| Chicony VGA WebCam                            | 2         | 1.74%   |
| Chicony EasyCamera                            | 2         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 1.74%   |
| Apple FaceTime HD Camera (Built-in)           | 2         | 1.74%   |
| Z-Star Webcam                                 | 1         | 0.87%   |
| Unknown ATIV VGA CAMERA                       | 1         | 0.87%   |
| Syntek USB2.0 Camera                          | 1         | 0.87%   |
| Syntek Integrated Camera                      | 1         | 0.87%   |
| Suyin HP TrueVision FHD RGB-IR                | 1         | 0.87%   |
| Suyin 1.3M HD WebCam                          | 1         | 0.87%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.87%   |
| Sunplus Laptop Integrated WebCam HD           | 1         | 0.87%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.87%   |
| Samsung Galaxy A5 (MTP)                       | 1         | 0.87%   |
| Realtek USB2.0 HD UVC WebCam                  | 1         | 0.87%   |
| Realtek Laptop Camera                         | 1         | 0.87%   |
| Realtek Integrated_Webcam_HD                  | 1         | 0.87%   |
| Realtek Integrated Webcam                     | 1         | 0.87%   |
| Realtek Integrated Camera                     | 1         | 0.87%   |
| Quanta VGA WebCam                             | 1         | 0.87%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 0.87%   |
| Quanta HP Wide Vision HD Camera               | 1         | 0.87%   |
| Quanta HP TrueVision HD Webcam                | 1         | 0.87%   |
| Microsoft Xbox NUI Camera                     | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 47.83%  |
| Synaptics                  | 3         | 13.04%  |
| Upek                       | 2         | 8.7%    |
| LighTuning Technology      | 2         | 8.7%    |
| Elan Microelectronics      | 2         | 8.7%    |
| AuthenTec                  | 2         | 8.7%    |
| Shenzhen Goodix Technology | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 17.39%  |
| Validity Sensors Fingerprint scanner                   | 2         | 8.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 8.7%    |
| Elan ELAN:Fingerprint                                  | 2         | 8.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.35%   |
| Validity Sensors VFS491                                | 1         | 4.35%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.35%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.35%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.35%   |
| Synaptics  WBDI                                        | 1         | 4.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.35%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 4.35%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.35%   |
| AuthenTec AES2810                                      | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 2         | 22.22%  |
| Broadcom    | 2         | 22.22%  |
| Alcor Micro | 2         | 22.22%  |
| O2 Micro    | 1         | 11.11%  |
| Lenovo      | 1         | 11.11%  |
| BIT4ID      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 11.11%  |
| Broadcom 5880                                              | 1         | 11.11%  |
| BIT4ID miniLector EVO                                      | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 119       | 70.41%  |
| 1     | 35        | 20.71%  |
| 2     | 14        | 8.28%   |
| 3     | 1         | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 23        | 33.82%  |
| Net/wireless          | 16        | 23.53%  |
| Chipcard              | 8         | 11.76%  |
| Multimedia controller | 7         | 10.29%  |
| Graphics card         | 5         | 7.35%   |
| Unassigned class      | 2         | 2.94%   |
| Camera                | 2         | 2.94%   |
| Tv card               | 1         | 1.47%   |
| Storage               | 1         | 1.47%   |
| Network               | 1         | 1.47%   |
| Net/ethernet          | 1         | 1.47%   |
| Bluetooth             | 1         | 1.47%   |


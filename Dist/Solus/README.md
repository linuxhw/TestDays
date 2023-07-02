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

Total: 270

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3420               | Notebook    | [730bdb05fe](https://linux-hardware.org/?probe=730bdb05fe) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d7e8503e88](https://linux-hardware.org/?probe=d7e8503e88) | Jun 23, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Solus 4.3    | 73        | 38.62%  |
| Solus 4.1    | 65        | 34.39%  |
| Solus 4.2    | 25        | 13.23%  |
| Solus 4.0    | 23        | 12.17%  |
| Solus 3.9999 | 2         | 1.06%   |
| Solus 4.4    | 1         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Solus | 178       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 15        | 7.35%   |
| 5.6.19-159.current  | 10        | 4.9%    |
| 6.0.11-225.current  | 8         | 3.92%   |
| 5.15.32-213.current | 8         | 3.92%   |
| 5.13.1-187.current  | 8         | 3.92%   |
| 5.5.7-150.current   | 7         | 3.43%   |
| 5.14.21-210.current | 7         | 3.43%   |
| 5.6.4-152.current   | 6         | 2.94%   |
| 5.6.13-153.current  | 6         | 2.94%   |
| 5.15.50-216.current | 6         | 2.94%   |
| 5.14.16-205.current | 6         | 2.94%   |
| 6.1.5-229.current   | 5         | 2.45%   |
| 5.6.18-156.current  | 5         | 2.45%   |
| 5.4.12-144.current  | 5         | 2.45%   |
| 5.13.6-190.current  | 5         | 2.45%   |
| 5.13.12-193.current | 5         | 2.45%   |
| 5.11.12-177.current | 5         | 2.45%   |
| 5.5.11-151.current  | 4         | 1.96%   |
| 5.11.22-180.current | 4         | 1.96%   |
| 5.10.15-172.current | 4         | 1.96%   |
| 5.3.7-132.current   | 3         | 1.47%   |
| 5.3.15-138.current  | 3         | 1.47%   |
| 5.2.20-130.current  | 3         | 1.47%   |
| 5.15.77-219.current | 3         | 1.47%   |
| 5.10.7-168.current  | 3         | 1.47%   |
| 5.5.4-148.current   | 2         | 0.98%   |
| 5.4.1-137.current   | 2         | 0.98%   |
| 5.3.10-134.current  | 2         | 0.98%   |
| 5.2.2-122.current   | 2         | 0.98%   |
| 5.15.43-215.current | 2         | 0.98%   |
| 5.15.37-214.current | 2         | 0.98%   |
| 5.15.30-212.current | 2         | 0.98%   |
| 5.15.26-211.current | 2         | 0.98%   |
| 5.14.14-202.current | 2         | 0.98%   |
| 5.13.0-186.current  | 2         | 0.98%   |
| 5.12.10-182.current | 2         | 0.98%   |
| 5.11.9-176.current  | 2         | 0.98%   |
| 5.11.21-179.current | 2         | 0.98%   |
| 5.11.16-178.current | 2         | 0.98%   |
| 5.10.5-167.current  | 2         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6.19  | 25        | 12.25%  |
| 6.0.11  | 8         | 3.92%   |
| 5.15.32 | 8         | 3.92%   |
| 5.13.1  | 8         | 3.92%   |
| 5.5.7   | 7         | 3.43%   |
| 5.14.21 | 7         | 3.43%   |
| 5.14.16 | 7         | 3.43%   |
| 5.6.4   | 6         | 2.94%   |
| 5.6.18  | 6         | 2.94%   |
| 5.6.13  | 6         | 2.94%   |
| 5.4.12  | 6         | 2.94%   |
| 5.15.50 | 6         | 2.94%   |
| 6.1.5   | 5         | 2.45%   |
| 5.13.6  | 5         | 2.45%   |
| 5.13.12 | 5         | 2.45%   |
| 5.11.12 | 5         | 2.45%   |
| 5.5.11  | 4         | 1.96%   |
| 5.11.22 | 4         | 1.96%   |
| 5.10.15 | 4         | 1.96%   |
| 5.3.7   | 3         | 1.47%   |
| 5.3.15  | 3         | 1.47%   |
| 5.2.20  | 3         | 1.47%   |
| 5.15.77 | 3         | 1.47%   |
| 5.10.7  | 3         | 1.47%   |
| 5.5.4   | 2         | 0.98%   |
| 5.4.1   | 2         | 0.98%   |
| 5.3.10  | 2         | 0.98%   |
| 5.2.2   | 2         | 0.98%   |
| 5.15.43 | 2         | 0.98%   |
| 5.15.37 | 2         | 0.98%   |
| 5.15.30 | 2         | 0.98%   |
| 5.15.26 | 2         | 0.98%   |
| 5.14.14 | 2         | 0.98%   |
| 5.13.0  | 2         | 0.98%   |
| 5.12.10 | 2         | 0.98%   |
| 5.11.9  | 2         | 0.98%   |
| 5.11.21 | 2         | 0.98%   |
| 5.11.16 | 2         | 0.98%   |
| 5.10.5  | 2         | 0.98%   |
| 5.10.12 | 2         | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6     | 42        | 21%     |
| 5.15    | 26        | 13%     |
| 5.13    | 21        | 10.5%   |
| 5.14    | 19        | 9.5%    |
| 5.5     | 14        | 7%      |
| 5.11    | 14        | 7%      |
| 5.10    | 13        | 6.5%    |
| 5.3     | 9         | 4.5%    |
| 6.0     | 8         | 4%      |
| 5.4     | 8         | 4%      |
| 6.1     | 6         | 3%      |
| 5.2     | 6         | 3%      |
| 5.12    | 3         | 1.5%    |
| 4.20    | 3         | 1.5%    |
| 4.14    | 3         | 1.5%    |
| 5.0     | 2         | 1%      |
| 6.2     | 1         | 0.5%    |
| 4.9     | 1         | 0.5%    |
| 4.18    | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 178       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 103       | 55.38%  |
| Unknown | 30        | 16.13%  |
| GNOME   | 17        | 9.14%   |
| KDE     | 16        | 8.6%    |
| MATE    | 13        | 6.99%   |
| KDE5    | 7         | 3.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 177       | 98.88%  |
| Wayland | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 132       | 72.53%  |
| TDM     | 19        | 10.44%  |
| LightDM | 19        | 10.44%  |
| SDDM    | 6         | 3.3%    |
| GDM     | 6         | 3.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 89        | 49.17%  |
| Unknown | 13        | 7.18%   |
| de_DE   | 11        | 6.08%   |
| ru_RU   | 8         | 4.42%   |
| pt_BR   | 8         | 4.42%   |
| es_ES   | 8         | 4.42%   |
| en_GB   | 8         | 4.42%   |
| fr_FR   | 7         | 3.87%   |
| en_AU   | 4         | 2.21%   |
| ro_RO   | 3         | 1.66%   |
| pl_PL   | 3         | 1.66%   |
| tr_TR   | 2         | 1.1%    |
| it_IT   | 2         | 1.1%    |
| en_NZ   | 2         | 1.1%    |
| uk_UA   | 1         | 0.55%   |
| pt_PT   | 1         | 0.55%   |
| nl_NL   | 1         | 0.55%   |
| fi_FI   | 1         | 0.55%   |
| es_VE   | 1         | 0.55%   |
| es_CL   | 1         | 0.55%   |
| en_IN   | 1         | 0.55%   |
| en_IE   | 1         | 0.55%   |
| en_DK   | 1         | 0.55%   |
| en_CA   | 1         | 0.55%   |
| de_AT   | 1         | 0.55%   |
| ar_SA   | 1         | 0.55%   |
| ar_EG   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 103       | 56.91%  |
| BIOS | 78        | 43.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 92.78%  |
| Unknown | 9         | 5%      |
| Overlay | 2         | 1.11%   |
| Xfs     | 1         | 0.56%   |
| Btrfs   | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 66.49%  |
| GPT     | 47        | 25.41%  |
| MBR     | 15        | 8.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 91.06%  |
| Yes       | 16        | 8.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 80.77%  |
| Yes       | 35        | 19.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 24        | 13.48%  |
| ASUSTek Computer       | 22        | 12.36%  |
| Hewlett-Packard        | 21        | 11.8%   |
| Dell                   | 21        | 11.8%   |
| Gigabyte Technology    | 20        | 11.24%  |
| Acer                   | 15        | 8.43%   |
| ASRock                 | 9         | 5.06%   |
| MSI                    | 8         | 4.49%   |
| Toshiba                | 6         | 3.37%   |
| Samsung Electronics    | 3         | 1.69%   |
| Intel                  | 3         | 1.69%   |
| Google                 | 3         | 1.69%   |
| Apple                  | 3         | 1.69%   |
| Sony                   | 2         | 1.12%   |
| Biostar                | 2         | 1.12%   |
| Unknown                | 2         | 1.12%   |
| Timi                   | 1         | 0.56%   |
| Shuttle                | 1         | 0.56%   |
| Pegatron               | 1         | 0.56%   |
| Panasonic              | 1         | 0.56%   |
| Packard Bell           | 1         | 0.56%   |
| MEGA                   | 1         | 0.56%   |
| Howard Computers       | 1         | 0.56%   |
| GPU Company            | 1         | 0.56%   |
| Fujitsu                | 1         | 0.56%   |
| Framework              | 1         | 0.56%   |
| eMachines              | 1         | 0.56%   |
| Chuwi                  | 1         | 0.56%   |
| AZW                    | 1         | 0.56%   |
| Avell High Performance | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 3         | 1.69%   |
| HP ProBook 450 G5                                     | 2         | 1.12%   |
| Acer Aspire E5-575G                                   | 2         | 1.12%   |
| Toshiba TECRA R840                                    | 1         | 0.56%   |
| Toshiba Satellite P50-A                               | 1         | 0.56%   |
| Toshiba Satellite L855                                | 1         | 0.56%   |
| Toshiba Satellite L655                                | 1         | 0.56%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 0.56%   |
| Timi TM1701                                           | 1         | 0.56%   |
| Sony VPCYB15AB                                        | 1         | 0.56%   |
| Sony VPCEB1S1E                                        | 1         | 0.56%   |
| Shuttle XS35V4                                        | 1         | 0.56%   |
| Samsung R430/P430/R480                                | 1         | 0.56%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.56%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 0.56%   |
| Pegatron IPM31                                        | 1         | 0.56%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 0.56%   |
| Packard Bell EasyNote TS11HR                          | 1         | 0.56%   |
| MSI MS-7C91                                           | 1         | 0.56%   |
| MSI MS-7B89                                           | 1         | 0.56%   |
| MSI MS-7B85                                           | 1         | 0.56%   |
| MSI MS-7B84                                           | 1         | 0.56%   |
| MSI MS-7A34                                           | 1         | 0.56%   |
| MSI MS-7850                                           | 1         | 0.56%   |
| MSI MS-7640                                           | 1         | 0.56%   |
| MSI Modern 14 B5M                                     | 1         | 0.56%   |
| MEGA G41T-M7 LGT                                      | 1         | 0.56%   |
| Lenovo Z51-70 80K6                                    | 1         | 0.56%   |
| Lenovo Z50-70 20354                                   | 1         | 0.56%   |
| Lenovo Yoga 730-13IKB 81CT                            | 1         | 0.56%   |
| Lenovo Yoga 510-14ISK 80S7                            | 1         | 0.56%   |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.56%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 0.56%   |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 0.56%   |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 0.56%   |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 0.56%   |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 0.56%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 0.56%   |
| Lenovo ThinkPad T14 Gen 1 20S00013FR                  | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 5.62%   |
| Acer Aspire            | 9         | 5.06%   |
| Dell Latitude          | 6         | 3.37%   |
| Dell Inspiron          | 6         | 3.37%   |
| Lenovo IdeaPad         | 5         | 2.81%   |
| HP ProBook             | 5         | 2.81%   |
| HP Pavilion            | 4         | 2.25%   |
| Gigabyte Z390          | 4         | 2.25%   |
| Dell XPS               | 4         | 2.25%   |
| ASUS TUF               | 4         | 2.25%   |
| Toshiba Satellite      | 3         | 1.69%   |
| ASUS PRIME             | 3         | 1.69%   |
| Acer Swift             | 3         | 1.69%   |
| Unknown                | 3         | 1.69%   |
| Lenovo Yoga            | 2         | 1.12%   |
| HP ENVY                | 2         | 1.12%   |
| HP EliteBook           | 2         | 1.12%   |
| Dell Vostro            | 2         | 1.12%   |
| Dell OptiPlex          | 2         | 1.12%   |
| ASUS VivoBook          | 2         | 1.12%   |
| ASUS ROG               | 2         | 1.12%   |
| Toshiba TECRA          | 1         | 0.56%   |
| Toshiba PORTEGE        | 1         | 0.56%   |
| Timi TM1701            | 1         | 0.56%   |
| Sony VPCYB15AB         | 1         | 0.56%   |
| Sony VPCEB1S1E         | 1         | 0.56%   |
| Shuttle XS35V4         | 1         | 0.56%   |
| Samsung R430           | 1         | 0.56%   |
| Samsung 300E5EV        | 1         | 0.56%   |
| Samsung 270E5K         | 1         | 0.56%   |
| Pegatron IPM31         | 1         | 0.56%   |
| Panasonic CF-C2CCEZXCM | 1         | 0.56%   |
| Packard Bell EasyNote  | 1         | 0.56%   |
| MSI MS-7C91            | 1         | 0.56%   |
| MSI MS-7B89            | 1         | 0.56%   |
| MSI MS-7B85            | 1         | 0.56%   |
| MSI MS-7B84            | 1         | 0.56%   |
| MSI MS-7A34            | 1         | 0.56%   |
| MSI MS-7850            | 1         | 0.56%   |
| MSI MS-7640            | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 30        | 16.85%  |
| 2019 | 18        | 10.11%  |
| 2016 | 15        | 8.43%   |
| 2017 | 14        | 7.87%   |
| 2014 | 14        | 7.87%   |
| 2021 | 12        | 6.74%   |
| 2020 | 12        | 6.74%   |
| 2012 | 12        | 6.74%   |
| 2013 | 10        | 5.62%   |
| 2011 | 10        | 5.62%   |
| 2010 | 8         | 4.49%   |
| 2008 | 8         | 4.49%   |
| 2015 | 7         | 3.93%   |
| 2009 | 4         | 2.25%   |
| 2006 | 3         | 1.69%   |
| 2007 | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 100       | 56.18%  |
| Desktop     | 69        | 38.76%  |
| Convertible | 6         | 3.37%   |
| Tablet      | 1         | 0.56%   |
| Mini pc     | 1         | 0.56%   |
| All in one  | 1         | 0.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 178       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 98.31%  |
| Yes  | 3         | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 46        | 25.41%  |
| 3.01-4.0    | 40        | 22.1%   |
| 8.01-16.0   | 34        | 18.78%  |
| 4.01-8.0    | 30        | 16.57%  |
| 32.01-64.0  | 20        | 11.05%  |
| 24.01-32.0  | 4         | 2.21%   |
| 2.01-3.0    | 3         | 1.66%   |
| 1.01-2.0    | 3         | 1.66%   |
| 64.01-256.0 | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 69        | 35.75%  |
| 2.01-3.0  | 50        | 25.91%  |
| 4.01-8.0  | 26        | 13.47%  |
| 3.01-4.0  | 25        | 12.95%  |
| 8.01-16.0 | 12        | 6.22%   |
| 0.51-1.0  | 11        | 5.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 98        | 53.26%  |
| 2      | 51        | 27.72%  |
| 4      | 14        | 7.61%   |
| 3      | 11        | 5.98%   |
| 5      | 6         | 3.26%   |
| 6      | 3         | 1.63%   |
| 7      | 1         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 62.22%  |
| Yes       | 68        | 37.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 86.52%  |
| No        | 24        | 13.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 79.78%  |
| No        | 36        | 20.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 65%     |
| No        | 63        | 35%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 32        | 17.98%  |
| Germany      | 12        | 6.74%   |
| Brazil       | 12        | 6.74%   |
| Netherlands  | 9         | 5.06%   |
| India        | 9         | 5.06%   |
| Russia       | 8         | 4.49%   |
| France       | 6         | 3.37%   |
| Canada       | 6         | 3.37%   |
| Sweden       | 5         | 2.81%   |
| Spain        | 5         | 2.81%   |
| Australia    | 5         | 2.81%   |
| Poland       | 4         | 2.25%   |
| Norway       | 4         | 2.25%   |
| UK           | 3         | 1.69%   |
| Turkey       | 3         | 1.69%   |
| Switzerland  | 3         | 1.69%   |
| Romania      | 3         | 1.69%   |
| New Zealand  | 3         | 1.69%   |
| Argentina    | 3         | 1.69%   |
| Venezuela    | 2         | 1.12%   |
| Ukraine      | 2         | 1.12%   |
| Saudi Arabia | 2         | 1.12%   |
| Mexico       | 2         | 1.12%   |
| Iran         | 2         | 1.12%   |
| Indonesia    | 2         | 1.12%   |
| Guatemala    | 2         | 1.12%   |
| Greece       | 2         | 1.12%   |
| Finland      | 2         | 1.12%   |
| Chile        | 2         | 1.12%   |
| Albania      | 2         | 1.12%   |
| Vietnam      | 1         | 0.56%   |
| Thailand     | 1         | 0.56%   |
| Portugal     | 1         | 0.56%   |
| Philippines  | 1         | 0.56%   |
| Peru         | 1         | 0.56%   |
| Oman         | 1         | 0.56%   |
| Nepal        | 1         | 0.56%   |
| Latvia       | 1         | 0.56%   |
| Kazakhstan   | 1         | 0.56%   |
| Japan        | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toronto                | 3         | 1.58%   |
| Oslo                   | 3         | 1.58%   |
| Melbourne              | 3         | 1.58%   |
| Mainz                  | 3         | 1.58%   |
| Constanța             | 3         | 1.58%   |
| Amsterdam              | 3         | 1.58%   |
| Zurich                 | 2         | 1.05%   |
| The Hague              | 2         | 1.05%   |
| Stockholm              | 2         | 1.05%   |
| St Petersburg          | 2         | 1.05%   |
| Severna Park           | 2         | 1.05%   |
| San Justo              | 2         | 1.05%   |
| New York               | 2         | 1.05%   |
| Guelph                 | 2         | 1.05%   |
| Guatemala City         | 2         | 1.05%   |
| Curitiba               | 2         | 1.05%   |
| Columbus               | 2         | 1.05%   |
| Caracas                | 2         | 1.05%   |
| Auckland               | 2         | 1.05%   |
| Zhytomyr               | 1         | 0.53%   |
| Yverdon-les-Bains      | 1         | 0.53%   |
| Yekaterinburg          | 1         | 0.53%   |
| Wendell                | 1         | 0.53%   |
| Weil am Rhein          | 1         | 0.53%   |
| Warrensburg            | 1         | 0.53%   |
| Vineland               | 1         | 0.53%   |
| Vienna                 | 1         | 0.53%   |
| Viby J                 | 1         | 0.53%   |
| Vasco da Gama          | 1         | 0.53%   |
| Vancouver              | 1         | 0.53%   |
| Uppsala                | 1         | 0.53%   |
| Uberlândia            | 1         | 0.53%   |
| Trondheim              | 1         | 0.53%   |
| Trabzon                | 1         | 0.53%   |
| Tirana                 | 1         | 0.53%   |
| Thessaloniki           | 1         | 0.53%   |
| Terranuova Bracciolini | 1         | 0.53%   |
| Teresopolis            | 1         | 0.53%   |
| Tehran                 | 1         | 0.53%   |
| SГЈo Pedro           | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 49        | 69     | 16.96%  |
| Samsung Electronics         | 43        | 77     | 14.88%  |
| Seagate                     | 34        | 59     | 11.76%  |
| Toshiba                     | 23        | 28     | 7.96%   |
| SanDisk                     | 19        | 25     | 6.57%   |
| Kingston                    | 19        | 23     | 6.57%   |
| Unknown                     | 15        | 17     | 5.19%   |
| Intel                       | 14        | 18     | 4.84%   |
| Crucial                     | 11        | 12     | 3.81%   |
| SK hynix                    | 10        | 10     | 3.46%   |
| Micron Technology           | 6         | 7      | 2.08%   |
| A-DATA Technology           | 6         | 6      | 2.08%   |
| Hitachi                     | 5         | 5      | 1.73%   |
| Silicon Motion              | 3         | 3      | 1.04%   |
| PNY                         | 3         | 3      | 1.04%   |
| Kingston Technology Company | 3         | 3      | 1.04%   |
| Phison                      | 2         | 2      | 0.69%   |
| Patriot                     | 2         | 2      | 0.69%   |
| HGST                        | 2         | 2      | 0.69%   |
| China                       | 2         | 2      | 0.69%   |
| Apple                       | 2         | 6      | 0.69%   |
| Transcend                   | 1         | 1      | 0.35%   |
| SPCC Sol                    | 1         | 1      | 0.35%   |
| SABRENT                     | 1         | 1      | 0.35%   |
| Phison Electronics          | 1         | 1      | 0.35%   |
| Maxtor                      | 1         | 1      | 0.35%   |
| Lenovo                      | 1         | 1      | 0.35%   |
| KIOXIA                      | 1         | 1      | 0.35%   |
| KingFast                    | 1         | 1      | 0.35%   |
| Intenso                     | 1         | 2      | 0.35%   |
| HFS512GD                    | 1         | 1      | 0.35%   |
| Gigabyte Technology         | 1         | 1      | 0.35%   |
| FORESEE                     | 1         | 1      | 0.35%   |
| Emtec                       | 1         | 1      | 0.35%   |
| Corsair                     | 1         | 1      | 0.35%   |
| Advantech                   | 1         | 1      | 0.35%   |
| AAPL                        | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB               | 9         | 2.77%   |
| Samsung NVMe SSD Drive 500GB            | 7         | 2.15%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 1.85%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.54%   |
| Samsung SSD 850 EVO 500GB               | 5         | 1.54%   |
| Samsung SSD 860 EVO 500GB               | 4         | 1.23%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 0.92%   |
| SK hynix NVMe SSD Drive 128GB           | 3         | 0.92%   |
| Seagate ST500DM002-1BD142 500GB         | 3         | 0.92%   |
| Seagate ST4000DM004-2CV104 4TB          | 3         | 0.92%   |
| Seagate ST31000528AS 1TB                | 3         | 0.92%   |
| Seagate ST2000DX002-2DV164 2TB          | 3         | 0.92%   |
| Seagate ST2000DM006-2DM164 2TB          | 3         | 0.92%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 0.92%   |
| Samsung SSD 860 EVO 250GB               | 3         | 0.92%   |
| Intel NVMe SSD Drive 256GB              | 3         | 0.92%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.92%   |
| WDC WD5000AAKS-00A7B0 500GB             | 2         | 0.62%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 2         | 0.62%   |
| WDC WD20EARX-00PASB0 2TB                | 2         | 0.62%   |
| WDC WD2003FZEX-00SRLA0 2TB              | 2         | 0.62%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 0.62%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.62%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.62%   |
| WDC WD10EZEX-08M2NA0 1TB                | 2         | 0.62%   |
| WDC WD10EADS-00M2B0 1TB                 | 2         | 0.62%   |
| Unknown TP02000GB 2TB                   | 2         | 0.62%   |
| Unknown MMC Card  32GB                  | 2         | 0.62%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 0.62%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.62%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB | 2         | 0.62%   |
| Seagate ST31000524AS 1TB                | 2         | 0.62%   |
| Seagate ST2000DX001-1NS164 2TB          | 2         | 0.62%   |
| SanDisk SDSSDA240G 240GB                | 2         | 0.62%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.62%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.62%   |
| PNY CS900 240GB SSD                     | 2         | 0.62%   |
| Kingston Company A2000 NVMe SSD 250GB   | 2         | 0.62%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.62%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 63     | 41.12%  |
| Seagate             | 34        | 59     | 31.78%  |
| Toshiba             | 15        | 20     | 14.02%  |
| Hitachi             | 5         | 5      | 4.67%   |
| Samsung Electronics | 3         | 4      | 2.8%    |
| HGST                | 2         | 2      | 1.87%   |
| Unknown             | 1         | 1      | 0.93%   |
| Maxtor              | 1         | 1      | 0.93%   |
| Intenso             | 1         | 2      | 0.93%   |
| AAPL                | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 47     | 31.68%  |
| Kingston            | 13        | 16     | 12.87%  |
| SanDisk             | 10        | 14     | 9.9%    |
| Crucial             | 9         | 10     | 8.91%   |
| Micron Technology   | 5         | 6      | 4.95%   |
| Intel               | 4         | 5      | 3.96%   |
| A-DATA Technology   | 4         | 4      | 3.96%   |
| WDC                 | 3         | 3      | 2.97%   |
| PNY                 | 3         | 3      | 2.97%   |
| Unknown             | 2         | 2      | 1.98%   |
| Toshiba             | 2         | 2      | 1.98%   |
| Patriot             | 2         | 2      | 1.98%   |
| China               | 2         | 2      | 1.98%   |
| Apple               | 2         | 6      | 1.98%   |
| Transcend           | 1         | 1      | 0.99%   |
| SPCC Sol            | 1         | 1      | 0.99%   |
| SK hynix            | 1         | 1      | 0.99%   |
| Gigabyte Technology | 1         | 1      | 0.99%   |
| FORESEE             | 1         | 1      | 0.99%   |
| Emtec               | 1         | 1      | 0.99%   |
| Corsair             | 1         | 1      | 0.99%   |
| Advantech           | 1         | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 158    | 35.66%  |
| SSD     | 86        | 130    | 33.33%  |
| NVMe    | 63        | 88     | 24.42%  |
| MMC     | 10        | 11     | 3.88%   |
| Unknown | 7         | 9      | 2.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 275    | 60.37%  |
| NVMe | 63        | 87     | 29.03%  |
| SAS  | 13        | 23     | 5.99%   |
| MMC  | 10        | 11     | 4.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 167    | 56.91%  |
| 0.51-1.0   | 51        | 72     | 28.18%  |
| 1.01-2.0   | 19        | 37     | 10.5%   |
| 3.01-4.0   | 4         | 7      | 2.21%   |
| 4.01-10.0  | 3         | 4      | 1.66%   |
| 10.01-20.0 | 1         | 1      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 34.97%  |
| 251-500        | 38        | 20.77%  |
| 501-1000       | 31        | 16.94%  |
| 1001-2000      | 15        | 8.2%    |
| More than 3000 | 9         | 4.92%   |
| 51-100         | 9         | 4.92%   |
| 21-50          | 6         | 3.28%   |
| 2001-3000      | 6         | 3.28%   |
| Unknown        | 3         | 1.64%   |
| 1-20           | 2         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 60        | 31.58%  |
| 21-50          | 34        | 17.89%  |
| 101-250        | 24        | 12.63%  |
| 51-100         | 20        | 10.53%  |
| 251-500        | 19        | 10%     |
| 1001-2000      | 13        | 6.84%   |
| 501-1000       | 12        | 6.32%   |
| 2001-3000      | 3         | 1.58%   |
| Unknown        | 3         | 1.58%   |
| More than 3000 | 2         | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB                    | 1         | 1      | 8.33%   |
| WDC WD20EARX-00PASB0 2TB                       | 1         | 1      | 8.33%   |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 8.33%   |
| WDC WD1002FAEX-00Y9A0 1TB                      | 1         | 1      | 8.33%   |
| WDC WD1001FALS-75J7B0 1TB                      | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                      | 1         | 2      | 8.33%   |
| Seagate ST2000DM001-9YN164 2TB                 | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO 500GB          | 1         | 1      | 8.33%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB   | 1         | 1      | 8.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 8.33%   |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 8.33%   |
| Crucial CT1000P1SSD8 1TB                       | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 41.67%  |
| Seagate             | 2         | 3      | 16.67%  |
| Samsung Electronics | 2         | 2      | 16.67%  |
| Micron Technology   | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 62.5%   |
| Seagate | 2         | 3      | 25%     |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 9      | 63.64%  |
| NVMe | 3         | 3      | 27.27%  |
| SSD  | 1         | 1      | 9.09%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 132       | 295    | 66.33%  |
| Works    | 56        | 88     | 28.14%  |
| Malfunc  | 11        | 13     | 5.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 119       | 51.29%  |
| AMD                          | 43        | 18.53%  |
| Samsung Electronics          | 18        | 7.76%   |
| SK hynix                     | 9         | 3.88%   |
| Kingston Technology Company  | 9         | 3.88%   |
| SanDisk                      | 8         | 3.45%   |
| Toshiba America Info Systems | 6         | 2.59%   |
| JMicron Technology           | 4         | 1.72%   |
| Silicon Motion               | 3         | 1.29%   |
| Phison Electronics           | 3         | 1.29%   |
| Micron/Crucial Technology    | 2         | 0.86%   |
| Marvell Technology Group     | 2         | 0.86%   |
| ADATA Technology             | 2         | 0.86%   |
| Nvidia                       | 1         | 0.43%   |
| Micron Technology            | 1         | 0.43%   |
| Lenovo                       | 1         | 0.43%   |
| ASMedia Technology           | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 32        | 12.03%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 5.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 4.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 4.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 8         | 3.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.01%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 3.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.5%    |
| Intel SSD 660P Series                                                          | 4         | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.5%    |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.5%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 3         | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.13%   |
| Kingston Company KC2000 NVMe SSD                                               | 3         | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.75%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.75%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.75%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 0.75%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.75%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2         | 0.75%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 59.91%  |
| NVMe | 63        | 27.75%  |
| IDE  | 21        | 9.25%   |
| RAID | 7         | 3.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 132       | 74.16%  |
| AMD    | 46        | 25.84%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 3.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.25%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.25%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 2.25%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.12%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 1.12%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 1.12%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.12%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 2         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.12%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 1.12%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 1.12%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.12%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 1.12%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.12%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.12%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.12%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 2         | 1.12%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.12%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.56%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz           | 1         | 0.56%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.56%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1         | 0.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.56%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.56%   |
| Intel Pentium D CPU 3.00GHz                   | 1         | 0.56%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.56%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.56%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.56%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.56%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 22.47%  |
| Intel Core i7           | 36        | 20.22%  |
| AMD Ryzen 7             | 17        | 9.55%   |
| AMD Ryzen 5             | 14        | 7.87%   |
| Intel Core i3           | 13        | 7.3%    |
| Intel Celeron           | 13        | 7.3%    |
| Other                   | 5         | 2.81%   |
| Intel Pentium           | 4         | 2.25%   |
| Intel Core 2 Duo        | 4         | 2.25%   |
| Intel Xeon              | 3         | 1.69%   |
| Intel Pentium Dual-Core | 3         | 1.69%   |
| Intel Core 2 Quad       | 3         | 1.69%   |
| AMD Ryzen 9             | 3         | 1.69%   |
| AMD A10                 | 3         | 1.69%   |
| Intel Pentium D         | 2         | 1.12%   |
| Intel Atom              | 2         | 1.12%   |
| AMD Phenom II X4        | 2         | 1.12%   |
| AMD FX                  | 2         | 1.12%   |
| Intel Pentium Silver    | 1         | 0.56%   |
| Intel Pentium Dual      | 1         | 0.56%   |
| Intel Core M            | 1         | 0.56%   |
| Intel Core i9           | 1         | 0.56%   |
| Intel Core 2            | 1         | 0.56%   |
| AMD Ryzen 3             | 1         | 0.56%   |
| AMD E1                  | 1         | 0.56%   |
| AMD E                   | 1         | 0.56%   |
| AMD A8                  | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 76        | 42.7%   |
| 4      | 64        | 35.96%  |
| 8      | 17        | 9.55%   |
| 6      | 17        | 9.55%   |
| 16     | 1         | 0.56%   |
| 12     | 1         | 0.56%   |
| 3      | 1         | 0.56%   |
| 1      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 178       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 132       | 74.16%  |
| 1      | 46        | 25.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 173       | 96.65%  |
| Unknown        | 6         | 3.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 7.1%    |
| 0x806ea    | 11        | 6.01%   |
| 0x306c3    | 11        | 6.01%   |
| 0x306a9    | 10        | 5.46%   |
| 0x206a7    | 10        | 5.46%   |
| 0x1067a    | 8         | 4.37%   |
| 0x806e9    | 7         | 3.83%   |
| 0x40651    | 6         | 3.28%   |
| 0x906e9    | 5         | 2.73%   |
| 0x806ec    | 5         | 2.73%   |
| 0x506e3    | 5         | 2.73%   |
| 0x20655    | 5         | 2.73%   |
| 0x08701021 | 5         | 2.73%   |
| 0x906ea    | 4         | 2.19%   |
| 0x806c1    | 4         | 2.19%   |
| 0x706a1    | 4         | 2.19%   |
| 0x406e3    | 4         | 2.19%   |
| 0x0a50000c | 4         | 2.19%   |
| 0x0800820d | 4         | 2.19%   |
| 0x306d4    | 3         | 1.64%   |
| 0x30678    | 3         | 1.64%   |
| 0x08701013 | 3         | 1.64%   |
| 0x08600106 | 3         | 1.64%   |
| 0x08108102 | 3         | 1.64%   |
| 0x0810100b | 3         | 1.64%   |
| 0x06003106 | 3         | 1.64%   |
| 0x906ec    | 2         | 1.09%   |
| 0x6fd      | 2         | 1.09%   |
| 0x08108109 | 2         | 1.09%   |
| 0x0800820b | 2         | 1.09%   |
| 0x06000852 | 2         | 1.09%   |
| 0xf64      | 1         | 0.55%   |
| 0xf62      | 1         | 0.55%   |
| 0xa0652    | 1         | 0.55%   |
| 0x906ed    | 1         | 0.55%   |
| 0x906eb    | 1         | 0.55%   |
| 0x906c0    | 1         | 0.55%   |
| 0x806eb    | 1         | 0.55%   |
| 0x706a8    | 1         | 0.55%   |
| 0x6f2      | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 40        | 22.47%  |
| Haswell       | 19        | 10.67%  |
| Zen 2         | 12        | 6.74%   |
| SandyBridge   | 11        | 6.18%   |
| Penryn        | 11        | 6.18%   |
| Zen+          | 10        | 5.62%   |
| IvyBridge     | 10        | 5.62%   |
| Skylake       | 9         | 5.06%   |
| Zen 3         | 7         | 3.93%   |
| Westmere      | 6         | 3.37%   |
| Silvermont    | 5         | 2.81%   |
| Goldmont plus | 5         | 2.81%   |
| Zen           | 4         | 2.25%   |
| TigerLake     | 4         | 2.25%   |
| Core          | 4         | 2.25%   |
| Steamroller   | 3         | 1.69%   |
| Piledriver    | 3         | 1.69%   |
| Broadwell     | 3         | 1.69%   |
| NetBurst      | 2         | 1.12%   |
| K10           | 2         | 1.12%   |
| Bobcat        | 2         | 1.12%   |
| Unknown       | 2         | 1.12%   |
| Tremont       | 1         | 0.56%   |
| Goldmont      | 1         | 0.56%   |
| Excavator     | 1         | 0.56%   |
| CometLake     | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 105       | 47.95%  |
| Nvidia | 60        | 27.4%   |
| AMD    | 54        | 24.66%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 10        | 4.5%    |
| Intel HD Graphics 620                                                       | 8         | 3.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8         | 3.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 3.15%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 3.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5         | 2.25%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 2.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 2.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 1.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4         | 1.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 1.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 1.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.35%   |
| Nvidia GM108M [GeForce 940MX]                                               | 3         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 1.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.35%   |
| Intel HD Graphics 630                                                       | 3         | 1.35%   |
| Intel HD Graphics 530                                                       | 3         | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.35%   |
| AMD Renoir                                                                  | 3         | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.35%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.9%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 0.9%    |
| Nvidia GM108M [GeForce 930MX]                                               | 2         | 0.9%    |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 0.9%    |
| Nvidia GK208M [GeForce GT 740M]                                             | 2         | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 0.9%    |
| Nvidia GF108M [GeForce GT 540M]                                             | 2         | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 0.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 38.33%  |
| 1 x AMD        | 44        | 24.44%  |
| 1 x Nvidia     | 29        | 16.11%  |
| Intel + Nvidia | 27        | 15%     |
| Intel + AMD    | 6         | 3.33%   |
| AMD + Nvidia   | 5         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 138       | 77.53%  |
| Proprietary | 40        | 22.47%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 41.67%  |
| 1.01-2.0   | 30        | 16.67%  |
| 0.51-1.0   | 22        | 12.22%  |
| 3.01-4.0   | 12        | 6.67%   |
| 7.01-8.0   | 11        | 6.11%   |
| 5.01-6.0   | 11        | 6.11%   |
| 0.01-0.5   | 11        | 6.11%   |
| 8.01-16.0  | 5         | 2.78%   |
| 2.01-3.0   | 3         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 13.81%  |
| Samsung Electronics     | 27        | 12.86%  |
| LG Display              | 18        | 8.57%   |
| Goldstar                | 16        | 7.62%   |
| BOE                     | 16        | 7.62%   |
| Chimei Innolux          | 15        | 7.14%   |
| AOC                     | 13        | 6.19%   |
| Dell                    | 10        | 4.76%   |
| Ancor Communications    | 9         | 4.29%   |
| Lenovo                  | 6         | 2.86%   |
| BenQ                    | 6         | 2.86%   |
| Acer                    | 5         | 2.38%   |
| Sharp                   | 4         | 1.9%    |
| LG Electronics          | 4         | 1.9%    |
| Philips                 | 3         | 1.43%   |
| Hewlett-Packard         | 3         | 1.43%   |
| ASUSTek Computer        | 3         | 1.43%   |
| Apple                   | 3         | 1.43%   |
| Unknown                 | 2         | 0.95%   |
| PANDA                   | 2         | 0.95%   |
| NEC Computers           | 2         | 0.95%   |
| Chi Mei Optoelectronics | 2         | 0.95%   |
| Unknown                 | 2         | 0.95%   |
| ___                     | 1         | 0.48%   |
| ViewSonic               | 1         | 0.48%   |
| Toshiba                 | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| Microstep               | 1         | 0.48%   |
| JRY                     | 1         | 0.48%   |
| Iiyama                  | 1         | 0.48%   |
| GKK                     | 1         | 0.48%   |
| CSO                     | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 3         | 1.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2         | 0.93%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                 | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 2         | 0.93%   |
| Ancor Communications LCD Monitor MG248 1920x1080                     | 2         | 0.93%   |
| Unknown                                                              | 2         | 0.93%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1         | 0.46%   |
| ViewSonic VP191b VSC0E11 1280x1024 376x301mm 19.0-inch               | 1         | 0.46%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.46%   |
| Unknown LCD Monitor HIC 3200x1080                                    | 1         | 0.46%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch            | 1         | 0.46%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                | 1         | 0.46%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch              | 1         | 0.46%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.46%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 1         | 0.46%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM029A 1920x1200 582x364mm 27.0-inch | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 0.46%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch  | 1         | 0.46%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 0.46%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch   | 1         | 0.46%   |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1         | 0.46%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch    | 1         | 0.46%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1         | 0.46%   |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 86        | 43%     |
| 1366x768 (WXGA)    | 39        | 19.5%   |
| 1600x900 (HD+)     | 11        | 5.5%    |
| 2560x1440 (QHD)    | 10        | 5%      |
| 3840x2160 (4K)     | 7         | 3.5%    |
| 1280x1024 (SXGA)   | 7         | 3.5%    |
| 1440x900 (WXGA+)   | 6         | 3%      |
| Unknown            | 6         | 3%      |
| 1680x1050 (WSXGA+) | 5         | 2.5%    |
| 1920x1200 (WUXGA)  | 4         | 2%      |
| 3840x1080          | 3         | 1.5%    |
| 2560x1080          | 3         | 1.5%    |
| 1280x800 (WXGA)    | 3         | 1.5%    |
| 1360x768           | 2         | 1%      |
| 5760x1080          | 1         | 0.5%    |
| 4480x1440          | 1         | 0.5%    |
| 3440x1440          | 1         | 0.5%    |
| 3200x1080          | 1         | 0.5%    |
| 2560x1600          | 1         | 0.5%    |
| 2256x1504          | 1         | 0.5%    |
| 1152x864           | 1         | 0.5%    |
| 1024x768 (XGA)     | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57        | 28.08%  |
| 13      | 25        | 12.32%  |
| Unknown | 21        | 10.34%  |
| 24      | 14        | 6.9%    |
| 14      | 14        | 6.9%    |
| 27      | 12        | 5.91%   |
| 21      | 10        | 4.93%   |
| 17      | 10        | 4.93%   |
| 23      | 9         | 4.43%   |
| 18      | 6         | 2.96%   |
| 22      | 4         | 1.97%   |
| 40      | 3         | 1.48%   |
| 20      | 3         | 1.48%   |
| 19      | 3         | 1.48%   |
| 34      | 2         | 0.99%   |
| 31      | 2         | 0.99%   |
| 12      | 2         | 0.99%   |
| 11      | 2         | 0.99%   |
| 72      | 1         | 0.49%   |
| 49      | 1         | 0.49%   |
| 29      | 1         | 0.49%   |
| 25      | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 42%     |
| 501-600     | 32        | 16%     |
| 401-500     | 25        | 12.5%   |
| Unknown     | 21        | 10.5%   |
| 201-300     | 16        | 8%      |
| 351-400     | 11        | 5.5%    |
| 601-700     | 4         | 2%      |
| 801-900     | 3         | 1.5%    |
| 701-800     | 2         | 1%      |
| 1501-2000   | 1         | 0.5%    |
| 1001-1500   | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 132       | 71.35%  |
| Unknown | 20        | 10.81%  |
| 16/10   | 19        | 10.27%  |
| 5/4     | 4         | 2.16%   |
| 3/2     | 3         | 1.62%   |
| 21/9    | 3         | 1.62%   |
| 4/3     | 2         | 1.08%   |
| 6/5     | 1         | 0.54%   |
| 32/9    | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 27.09%  |
| 201-250        | 30        | 14.78%  |
| 81-90          | 29        | 14.29%  |
| Unknown        | 21        | 10.34%  |
| 301-350        | 13        | 6.4%    |
| 71-80          | 10        | 4.93%   |
| 151-200        | 10        | 4.93%   |
| 141-150        | 7         | 3.45%   |
| 121-130        | 7         | 3.45%   |
| 251-300        | 6         | 2.96%   |
| 351-500        | 4         | 1.97%   |
| 501-1000       | 4         | 1.97%   |
| 61-70          | 2         | 0.99%   |
| 51-60          | 2         | 0.99%   |
| More than 1000 | 1         | 0.49%   |
| 111-120        | 1         | 0.49%   |
| 91-100         | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 61        | 31.12%  |
| 121-160       | 49        | 25%     |
| 101-120       | 47        | 23.98%  |
| Unknown       | 21        | 10.71%  |
| 161-240       | 13        | 6.63%   |
| More than 240 | 4         | 2.04%   |
| 1-50          | 1         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 140       | 77.78%  |
| 2     | 37        | 20.56%  |
| 3     | 3         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 100       | 35.59%  |
| Intel                         | 84        | 29.89%  |
| Qualcomm Atheros              | 42        | 14.95%  |
| Broadcom                      | 13        | 4.63%   |
| MediaTek                      | 5         | 1.78%   |
| Marvell Technology Group      | 4         | 1.42%   |
| Xiaomi                        | 3         | 1.07%   |
| TP-Link                       | 3         | 1.07%   |
| Ralink Technology             | 3         | 1.07%   |
| Ralink                        | 2         | 0.71%   |
| Dell                          | 2         | 0.71%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.36%   |
| T & A Mobile Phones           | 1         | 0.36%   |
| Sierra Wireless               | 1         | 0.36%   |
| Samsung Electronics           | 1         | 0.36%   |
| Qualcomm                      | 1         | 0.36%   |
| OnePlus Technology (Shenzhen) | 1         | 0.36%   |
| Nvidia                        | 1         | 0.36%   |
| NetGear                       | 1         | 0.36%   |
| Microchip Technology          | 1         | 0.36%   |
| Linksys                       | 1         | 0.36%   |
| Lenovo                        | 1         | 0.36%   |
| LeEco                         | 1         | 0.36%   |
| Jolla Oy                      | 1         | 0.36%   |
| Huawei Technologies           | 1         | 0.36%   |
| Hewlett-Packard               | 1         | 0.36%   |
| D-Link System                 | 1         | 0.36%   |
| Broadcom Limited              | 1         | 0.36%   |
| Belkin Components             | 1         | 0.36%   |
| ASIX Electronics              | 1         | 0.36%   |
| Aquantia                      | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 22.73%  |
| Intel Wi-Fi 6 AX200                                               | 11        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.73%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.82%   |
| Intel Wireless 7265                                               | 6         | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.52%   |
| Intel Wireless 7260                                               | 5         | 1.52%   |
| Intel Wireless 3165                                               | 5         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.91%   |
| Intel Wireless 8260                                               | 3         | 0.91%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.91%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.61%   |
| Realtek RTL8187 Wireless Adapter                                  | 2         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.61%   |
| Realtek 802.11ac NIC                                              | 2         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.61%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                  | 2         | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.61%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 43.87%  |
| Qualcomm Atheros      | 37        | 23.87%  |
| Realtek Semiconductor | 20        | 12.9%   |
| Broadcom              | 10        | 6.45%   |
| MediaTek              | 5         | 3.23%   |
| Ralink Technology     | 3         | 1.94%   |
| TP-Link               | 2         | 1.29%   |
| Ralink                | 2         | 1.29%   |
| Sierra Wireless       | 1         | 0.65%   |
| NetGear               | 1         | 0.65%   |
| Linksys               | 1         | 0.65%   |
| Hewlett-Packard       | 1         | 0.65%   |
| Dell                  | 1         | 0.65%   |
| D-Link System         | 1         | 0.65%   |
| Broadcom Limited      | 1         | 0.65%   |
| Belkin Components     | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 7.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 6.37%   |
| Intel Wireless 8265 / 8275                                     | 9         | 5.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 5.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.82%   |
| Intel Wireless 7265                                            | 6         | 3.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 3.18%   |
| Intel Wireless 7260                                            | 5         | 3.18%   |
| Intel Wireless 3165                                            | 5         | 3.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.91%   |
| Intel Wireless 8260                                            | 3         | 1.91%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.27%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 1.27%   |
| Realtek 802.11ac NIC                                           | 2         | 1.27%   |
| Qualcomm Atheros AR922X Wireless Network Adapter               | 2         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.27%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.27%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.27%   |
| Sierra Wireless EM7305                                         | 1         | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.64%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.64%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 91        | 55.15%  |
| Intel                      | 44        | 26.67%  |
| Qualcomm Atheros           | 8         | 4.85%   |
| Broadcom                   | 5         | 3.03%   |
| Marvell Technology Group   | 4         | 2.42%   |
| Xiaomi                     | 3         | 1.82%   |
| ZTE WCDMA Technologies MSM | 1         | 0.61%   |
| TP-Link                    | 1         | 0.61%   |
| Qualcomm                   | 1         | 0.61%   |
| Nvidia                     | 1         | 0.61%   |
| Lenovo                     | 1         | 0.61%   |
| LeEco                      | 1         | 0.61%   |
| Jolla Oy                   | 1         | 0.61%   |
| Huawei Technologies        | 1         | 0.61%   |
| ASIX Electronics           | 1         | 0.61%   |
| Aquantia                   | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 75        | 44.64%  |
| Intel I211 Gigabit Network Connection                                          | 9         | 5.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 2.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.79%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.79%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.19%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.19%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.19%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 1.19%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.19%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.19%   |
| ZTE WCDMA MSM Yota Router                                                      | 1         | 0.6%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.6%    |
| Qualcomm Android                                                               | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.6%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.6%    |
| Lenovo Thinkpad LAN                                                            | 1         | 0.6%    |
| LeEco Android                                                                  | 1         | 0.6%    |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 0.6%    |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.6%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.6%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.6%    |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.6%    |
| Intel Ethernet Connection I217-V                                               | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 154       | 51.16%  |
| WiFi     | 142       | 47.18%  |
| Modem    | 3         | 1%      |
| Unknown  | 2         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 115       | 61.5%   |
| Ethernet | 72        | 38.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 103       | 57.54%  |
| 1     | 70        | 39.11%  |
| 3     | 4         | 2.23%   |
| 0     | 2         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 156       | 85.71%  |
| Yes  | 26        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 46.67%  |
| Qualcomm Atheros Communications | 13        | 10.83%  |
| Lite-On Technology              | 9         | 7.5%    |
| Cambridge Silicon Radio         | 9         | 7.5%    |
| Realtek Semiconductor           | 7         | 5.83%   |
| Broadcom                        | 7         | 5.83%   |
| IMC Networks                    | 4         | 3.33%   |
| Apple                           | 4         | 3.33%   |
| MediaTek                        | 2         | 1.67%   |
| Foxconn / Hon Hai               | 2         | 1.67%   |
| ASUSTek Computer                | 2         | 1.67%   |
| Toshiba                         | 1         | 0.83%   |
| Ralink                          | 1         | 0.83%   |
| ISSC                            | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |
| Dell                            | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 28        | 23.14%  |
| Intel AX200 Bluetooth                                                               | 10        | 8.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 7.44%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 4.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 4.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.13%   |
| Intel AX201 Bluetooth                                                               | 5         | 4.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 3.31%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.48%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.48%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.65%   |
| MediaTek Wireless_Device                                                            | 2         | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.65%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.65%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.65%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.65%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.83%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.83%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.83%   |
| Lite-On Wireless_Device                                                             | 1         | 0.83%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.83%   |
| ISSC Bluetooth Device                                                               | 1         | 0.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.83%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.83%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.83%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.83%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 128       | 50.79%  |
| AMD                     | 59        | 23.41%  |
| Nvidia                  | 41        | 16.27%  |
| Blue Microphones        | 4         | 1.59%   |
| C-Media Electronics     | 3         | 1.19%   |
| Texas Instruments       | 2         | 0.79%   |
| Logitech                | 2         | 0.79%   |
| Yamaha                  | 1         | 0.4%    |
| Tenx Technology         | 1         | 0.4%    |
| SteelSeries ApS         | 1         | 0.4%    |
| SAVITECH                | 1         | 0.4%    |
| Samsung Electronics     | 1         | 0.4%    |
| RME                     | 1         | 0.4%    |
| JMTek                   | 1         | 0.4%    |
| GYROCOM C&C             | 1         | 0.4%    |
| Creative Technology     | 1         | 0.4%    |
| Creative Labs           | 1         | 0.4%    |
| Cooler Master           | 1         | 0.4%    |
| Conexant Systems        | 1         | 0.4%    |
| BEHRINGER International | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 22        | 7.24%   |
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 5.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 2.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.3%    |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.3%    |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 1.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.64%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.64%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.64%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.99%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.99%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.99%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3         | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 23.53%  |
| SK hynix            | 10        | 11.76%  |
| Unknown             | 9         | 10.59%  |
| Kingston            | 7         | 8.24%   |
| Crucial             | 7         | 8.24%   |
| Corsair             | 7         | 8.24%   |
| A-DATA Technology   | 7         | 8.24%   |
| Micron Technology   | 6         | 7.06%   |
| Nanya Technology    | 3         | 3.53%   |
| Ramaxel Technology  | 2         | 2.35%   |
| G.Skill             | 2         | 2.35%   |
| Elpida              | 2         | 2.35%   |
| Transcend           | 1         | 1.18%   |
| Team                | 1         | 1.18%   |
| Patriot             | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 2.2%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 2.2%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 2         | 2.2%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1867MT/s                   | 1         | 1.1%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                     | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.1%    |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                     | 1         | 1.1%    |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.1%    |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 1.1%    |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s               | 1         | 1.1%    |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s                | 1         | 1.1%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 1.1%    |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 1.1%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.1%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.1%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.1%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.1%    |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.1%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.1%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.1%    |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 1         | 1.1%    |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.1%    |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.1%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.1%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.1%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.1%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.1%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.1%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.1%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 36        | 50%     |
| DDR3    | 25        | 34.72%  |
| LPDDR3  | 5         | 6.94%   |
| DDR2    | 2         | 2.78%   |
| SDRAM   | 1         | 1.39%   |
| LPDDR4  | 1         | 1.39%   |
| DDR     | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 67.61%  |
| DIMM         | 19        | 26.76%  |
| Row Of Chips | 4         | 5.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 39.74%  |
| 4096  | 23        | 29.49%  |
| 16384 | 10        | 12.82%  |
| 2048  | 9         | 11.54%  |
| 32768 | 3         | 3.85%   |
| 1024  | 2         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 18        | 21.95%  |
| 3200    | 10        | 12.2%   |
| 2667    | 10        | 12.2%   |
| 2400    | 9         | 10.98%  |
| 2133    | 8         | 9.76%   |
| 1867    | 3         | 3.66%   |
| 3600    | 2         | 2.44%   |
| 3533    | 2         | 2.44%   |
| 1334    | 2         | 2.44%   |
| 1333    | 2         | 2.44%   |
| 667     | 2         | 2.44%   |
| Unknown | 2         | 2.44%   |
| 4267    | 1         | 1.22%   |
| 3866    | 1         | 1.22%   |
| 3733    | 1         | 1.22%   |
| 3400    | 1         | 1.22%   |
| 3266    | 1         | 1.22%   |
| 3000    | 1         | 1.22%   |
| 2048    | 1         | 1.22%   |
| 1866    | 1         | 1.22%   |
| 1800    | 1         | 1.22%   |
| 1067    | 1         | 1.22%   |
| 1066    | 1         | 1.22%   |
| 800     | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Canon              | 2         | 40%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP LaserJet 1018       | 1         | 20%     |
| HP DeskJet 3630 series | 1         | 20%     |
| Canon LBP7010C/7018C   | 1         | 20%     |
| Canon G3000 series     | 1         | 20%     |
| Brother MFC-9330CDW    | 1         | 20%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 24        | 20.17%  |
| Microdia                               | 12        | 10.08%  |
| Realtek Semiconductor                  | 11        | 9.24%   |
| Logitech                               | 11        | 9.24%   |
| IMC Networks                           | 10        | 8.4%    |
| Quanta                                 | 6         | 5.04%   |
| Sunplus Innovation Technology          | 5         | 4.2%    |
| Suyin                                  | 4         | 3.36%   |
| Lite-On Technology                     | 4         | 3.36%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.36%   |
| Bison Electronics                      | 4         | 3.36%   |
| Microsoft                              | 3         | 2.52%   |
| Apple                                  | 3         | 2.52%   |
| Syntek                                 | 2         | 1.68%   |
| Lenovo                                 | 2         | 1.68%   |
| Importek                               | 2         | 1.68%   |
| Acer                                   | 2         | 1.68%   |
| Z-Star Microelectronics                | 1         | 0.84%   |
| Unknown                                | 1         | 0.84%   |
| Silicon Motion                         | 1         | 0.84%   |
| Samsung Electronics                    | 1         | 0.84%   |
| MacroSilicon                           | 1         | 0.84%   |
| Luxvisions Innotech Limited            | 1         | 0.84%   |
| LG Electronics                         | 1         | 0.84%   |
| Intel                                  | 1         | 0.84%   |
| Hewlett-Packard                        | 1         | 0.84%   |
| A4Tech                                 | 1         | 0.84%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 6         | 4.96%   |
| Chicony Integrated Camera                     | 5         | 4.13%   |
| Microdia Integrated_Webcam_HD                 | 4         | 3.31%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 3.31%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 2.48%   |
| Realtek HD WebCam                             | 3         | 2.48%   |
| Logitech HD Pro Webcam C920                   | 3         | 2.48%   |
| IMC Networks Integrated Camera                | 3         | 2.48%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 1.65%   |
| Realtek Integrated Webcam_HD                  | 2         | 1.65%   |
| Quanta HD User Facing                         | 2         | 1.65%   |
| Microdia Camera                               | 2         | 1.65%   |
| Logitech Webcam C270                          | 2         | 1.65%   |
| Logitech Logitech Webcam C160                 | 2         | 1.65%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 1.65%   |
| Chicony VGA WebCam                            | 2         | 1.65%   |
| Chicony EasyCamera                            | 2         | 1.65%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 1.65%   |
| Apple FaceTime HD Camera (Built-in)           | 2         | 1.65%   |
| Z-Star Webcam                                 | 1         | 0.83%   |
| Unknown ATIV VGA CAMERA                       | 1         | 0.83%   |
| Syntek USB2.0 Camera                          | 1         | 0.83%   |
| Syntek Integrated Camera                      | 1         | 0.83%   |
| Suyin HP TrueVision FHD RGB-IR                | 1         | 0.83%   |
| Suyin 1.3M HD WebCam                          | 1         | 0.83%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.83%   |
| Sunplus Laptop Integrated WebCam HD           | 1         | 0.83%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.83%   |
| Samsung Galaxy A5 (MTP)                       | 1         | 0.83%   |
| Realtek Laptop Camera                         | 1         | 0.83%   |
| Realtek Integrated_Webcam_HD                  | 1         | 0.83%   |
| Realtek Integrated Webcam HD                  | 1         | 0.83%   |
| Realtek Integrated Webcam                     | 1         | 0.83%   |
| Realtek Integrated Camera                     | 1         | 0.83%   |
| Realtek HP Truevision HD                      | 1         | 0.83%   |
| Quanta VGA WebCam                             | 1         | 0.83%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 0.83%   |
| Quanta HP Wide Vision HD Camera               | 1         | 0.83%   |
| Quanta HP TrueVision HD Webcam                | 1         | 0.83%   |
| Microsoft Xbox NUI Camera                     | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 44%     |
| Synaptics                  | 4         | 16%     |
| Upek                       | 2         | 8%      |
| LighTuning Technology      | 2         | 8%      |
| Elan Microelectronics      | 2         | 8%      |
| AuthenTec                  | 2         | 8%      |
| Shenzhen Goodix Technology | 1         | 4%      |
| Focal-systems.Corp         | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 16%     |
| Validity Sensors Fingerprint scanner                   | 2         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 8%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 8%      |
| Elan ELAN:Fingerprint                                  | 2         | 8%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4%      |
| Validity Sensors VFS491                                | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4%      |
| Upek TCS5B Fingerprint sensor                          | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4%      |
| Synaptics  WBDI                                        | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4%      |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 4%      |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 4%      |
| AuthenTec Fingerprint Sensor                           | 1         | 4%      |
| AuthenTec AES2810                                      | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 27.27%  |
| Upek        | 2         | 18.18%  |
| Broadcom    | 2         | 18.18%  |
| O2 Micro    | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |
| BIT4ID      | 1         | 9.09%   |
| Aktiv       | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 27.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 9.09%   |
| Broadcom 5880                                              | 1         | 9.09%   |
| BIT4ID miniLector EVO                                      | 1         | 9.09%   |
| Aktiv Rutoken lite                                         | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 125       | 69.44%  |
| 1     | 38        | 21.11%  |
| 2     | 16        | 8.89%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 25        | 33.33%  |
| Net/wireless          | 18        | 24%     |
| Chipcard              | 10        | 13.33%  |
| Multimedia controller | 7         | 9.33%   |
| Graphics card         | 6         | 8%      |
| Unassigned class      | 2         | 2.67%   |
| Camera                | 2         | 2.67%   |
| Tv card               | 1         | 1.33%   |
| Storage               | 1         | 1.33%   |
| Network               | 1         | 1.33%   |
| Net/ethernet          | 1         | 1.33%   |
| Bluetooth             | 1         | 1.33%   |


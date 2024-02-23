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

Total: 294

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Positivo      | POS-EINM10CB POSITIVO       | Desktop     | [efe2537d0f](https://linux-hardware.org/?probe=efe2537d0f) | Jan 28, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d8e2dd481d](https://linux-hardware.org/?probe=d8e2dd481d) | Dec 28, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [20f689bbac](https://linux-hardware.org/?probe=20f689bbac) | Nov 11, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [b44384b1ba](https://linux-hardware.org/?probe=b44384b1ba) | Oct 05, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [96c62ad87e](https://linux-hardware.org/?probe=96c62ad87e) | Oct 03, 2023 |
| Google        | Kip                         | Notebook    | [344f7b3eda](https://linux-hardware.org/?probe=344f7b3eda) | Sep 21, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [4425992293](https://linux-hardware.org/?probe=4425992293) | Sep 21, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [31c6babc26](https://linux-hardware.org/?probe=31c6babc26) | Sep 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d16f2005c0](https://linux-hardware.org/?probe=d16f2005c0) | Sep 05, 2023 |
| Intel         | X99H                        | Desktop     | [e020530bc8](https://linux-hardware.org/?probe=e020530bc8) | Sep 01, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d3bc465020](https://linux-hardware.org/?probe=d3bc465020) | Aug 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a1b816015e](https://linux-hardware.org/?probe=a1b816015e) | Aug 23, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [f69a3b4363](https://linux-hardware.org/?probe=f69a3b4363) | Aug 17, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [af4abf9f1d](https://linux-hardware.org/?probe=af4abf9f1d) | Aug 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [738a42f72e](https://linux-hardware.org/?probe=738a42f72e) | Aug 05, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [fda8d0a543](https://linux-hardware.org/?probe=fda8d0a543) | Aug 02, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [0a72297cb9](https://linux-hardware.org/?probe=0a72297cb9) | Jul 19, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [488495f486](https://linux-hardware.org/?probe=488495f486) | Jul 15, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [2662eb02e7](https://linux-hardware.org/?probe=2662eb02e7) | Jul 13, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [b3f84b24e7](https://linux-hardware.org/?probe=b3f84b24e7) | Jul 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [b7af0e09ea](https://linux-hardware.org/?probe=b7af0e09ea) | Jul 12, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [33a8b4ab02](https://linux-hardware.org/?probe=33a8b4ab02) | Jul 08, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [21a805fe1d](https://linux-hardware.org/?probe=21a805fe1d) | Jul 08, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [6a51948293](https://linux-hardware.org/?probe=6a51948293) | Jul 03, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Solus 4.3    | 73        | 35.27%  |
| Solus 4.1    | 65        | 31.4%   |
| Solus 4.2    | 25        | 12.08%  |
| Solus 4.0    | 23        | 11.11%  |
| Solus 4.4    | 17        | 8.21%   |
| Solus 4.5    | 2         | 0.97%   |
| Solus 3.9999 | 2         | 0.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Solus | 192       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 15        | 6.76%   |
| 5.6.19-159.current  | 10        | 4.5%    |
| 6.0.11-225.current  | 8         | 3.6%    |
| 5.15.32-213.current | 8         | 3.6%    |
| 5.13.1-187.current  | 8         | 3.6%    |
| 5.5.7-150.current   | 7         | 3.15%   |
| 5.14.21-210.current | 7         | 3.15%   |
| 6.3.8-240.current   | 6         | 2.7%    |
| 5.6.4-152.current   | 6         | 2.7%    |
| 5.6.13-153.current  | 6         | 2.7%    |
| 5.15.50-216.current | 6         | 2.7%    |
| 5.14.16-205.current | 6         | 2.7%    |
| 6.1.5-229.current   | 5         | 2.25%   |
| 5.6.18-156.current  | 5         | 2.25%   |
| 5.4.12-144.current  | 5         | 2.25%   |
| 5.13.6-190.current  | 5         | 2.25%   |
| 5.13.12-193.current | 5         | 2.25%   |
| 5.11.12-177.current | 5         | 2.25%   |
| 5.5.11-151.current  | 4         | 1.8%    |
| 5.11.22-180.current | 4         | 1.8%    |
| 5.10.15-172.current | 4         | 1.8%    |
| 5.3.7-132.current   | 3         | 1.35%   |
| 5.3.15-138.current  | 3         | 1.35%   |
| 5.2.20-130.current  | 3         | 1.35%   |
| 5.15.77-219.current | 3         | 1.35%   |
| 5.10.7-168.current  | 3         | 1.35%   |
| 6.5.5-258.current   | 2         | 0.9%    |
| 6.4.15-254.current  | 2         | 0.9%    |
| 5.5.4-148.current   | 2         | 0.9%    |
| 5.4.1-137.current   | 2         | 0.9%    |
| 5.3.10-134.current  | 2         | 0.9%    |
| 5.2.2-122.current   | 2         | 0.9%    |
| 5.15.43-215.current | 2         | 0.9%    |
| 5.15.37-214.current | 2         | 0.9%    |
| 5.15.30-212.current | 2         | 0.9%    |
| 5.15.26-211.current | 2         | 0.9%    |
| 5.14.14-202.current | 2         | 0.9%    |
| 5.13.0-186.current  | 2         | 0.9%    |
| 5.12.10-182.current | 2         | 0.9%    |
| 5.11.9-176.current  | 2         | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6.19  | 25        | 11.26%  |
| 6.0.11  | 8         | 3.6%    |
| 5.15.32 | 8         | 3.6%    |
| 5.13.1  | 8         | 3.6%    |
| 5.5.7   | 7         | 3.15%   |
| 5.14.21 | 7         | 3.15%   |
| 5.14.16 | 7         | 3.15%   |
| 6.3.8   | 6         | 2.7%    |
| 5.6.4   | 6         | 2.7%    |
| 5.6.18  | 6         | 2.7%    |
| 5.6.13  | 6         | 2.7%    |
| 5.4.12  | 6         | 2.7%    |
| 5.15.50 | 6         | 2.7%    |
| 6.1.5   | 5         | 2.25%   |
| 5.13.6  | 5         | 2.25%   |
| 5.13.12 | 5         | 2.25%   |
| 5.11.12 | 5         | 2.25%   |
| 5.5.11  | 4         | 1.8%    |
| 5.11.22 | 4         | 1.8%    |
| 5.10.15 | 4         | 1.8%    |
| 5.3.7   | 3         | 1.35%   |
| 5.3.15  | 3         | 1.35%   |
| 5.2.20  | 3         | 1.35%   |
| 5.15.77 | 3         | 1.35%   |
| 5.10.7  | 3         | 1.35%   |
| 6.5.5   | 2         | 0.9%    |
| 6.4.15  | 2         | 0.9%    |
| 6.3.12  | 2         | 0.9%    |
| 5.5.4   | 2         | 0.9%    |
| 5.4.1   | 2         | 0.9%    |
| 5.3.10  | 2         | 0.9%    |
| 5.2.2   | 2         | 0.9%    |
| 5.15.43 | 2         | 0.9%    |
| 5.15.37 | 2         | 0.9%    |
| 5.15.30 | 2         | 0.9%    |
| 5.15.26 | 2         | 0.9%    |
| 5.14.14 | 2         | 0.9%    |
| 5.13.0  | 2         | 0.9%    |
| 5.12.10 | 2         | 0.9%    |
| 5.11.9  | 2         | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6     | 42        | 19.27%  |
| 5.15    | 27        | 12.39%  |
| 5.13    | 21        | 9.63%   |
| 5.14    | 19        | 8.72%   |
| 5.5     | 14        | 6.42%   |
| 5.11    | 14        | 6.42%   |
| 5.10    | 13        | 5.96%   |
| 5.3     | 9         | 4.13%   |
| 6.3     | 8         | 3.67%   |
| 6.0     | 8         | 3.67%   |
| 5.4     | 8         | 3.67%   |
| 6.1     | 6         | 2.75%   |
| 5.2     | 6         | 2.75%   |
| 6.4     | 4         | 1.83%   |
| 6.5     | 3         | 1.38%   |
| 5.12    | 3         | 1.38%   |
| 4.20    | 3         | 1.38%   |
| 4.14    | 3         | 1.38%   |
| 6.6     | 2         | 0.92%   |
| 5.0     | 2         | 0.92%   |
| 6.2     | 1         | 0.46%   |
| 4.9     | 1         | 0.46%   |
| 4.18    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 192       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 110       | 55%     |
| Unknown | 30        | 15%     |
| GNOME   | 20        | 10%     |
| KDE     | 16        | 8%      |
| MATE    | 14        | 7%      |
| KDE5    | 10        | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 189       | 96.92%  |
| Wayland | 4         | 2.05%   |
| Unknown | 2         | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 139       | 70.56%  |
| LightDM | 23        | 11.68%  |
| TDM     | 19        | 9.64%   |
| SDDM    | 8         | 4.06%   |
| GDM     | 8         | 4.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 99        | 50.77%  |
| Unknown | 13        | 6.67%   |
| de_DE   | 11        | 5.64%   |
| pt_BR   | 10        | 5.13%   |
| ru_RU   | 8         | 4.1%    |
| fr_FR   | 8         | 4.1%    |
| es_ES   | 8         | 4.1%    |
| en_GB   | 8         | 4.1%    |
| en_AU   | 4         | 2.05%   |
| ro_RO   | 3         | 1.54%   |
| pl_PL   | 3         | 1.54%   |
| tr_TR   | 2         | 1.03%   |
| it_IT   | 2         | 1.03%   |
| en_NZ   | 2         | 1.03%   |
| uk_UA   | 1         | 0.51%   |
| pt_PT   | 1         | 0.51%   |
| nl_NL   | 1         | 0.51%   |
| id_ID   | 1         | 0.51%   |
| fi_FI   | 1         | 0.51%   |
| es_VE   | 1         | 0.51%   |
| es_CL   | 1         | 0.51%   |
| en_IN   | 1         | 0.51%   |
| en_IE   | 1         | 0.51%   |
| en_DK   | 1         | 0.51%   |
| en_CA   | 1         | 0.51%   |
| de_AT   | 1         | 0.51%   |
| ar_SA   | 1         | 0.51%   |
| ar_EG   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 112       | 57.44%  |
| BIOS | 83        | 42.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 179       | 91.79%  |
| Unknown | 9         | 4.62%   |
| Overlay | 3         | 1.54%   |
| Tmpfs   | 2         | 1.03%   |
| Xfs     | 1         | 0.51%   |
| Btrfs   | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 130       | 65%     |
| GPT     | 53        | 26.5%   |
| MBR     | 17        | 8.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 91.19%  |
| Yes       | 17        | 8.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 160       | 81.63%  |
| Yes       | 36        | 18.37%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 26        | 13.54%  |
| ASUSTek Computer       | 23        | 11.98%  |
| Hewlett-Packard        | 22        | 11.46%  |
| Dell                   | 22        | 11.46%  |
| Gigabyte Technology    | 20        | 10.42%  |
| Acer                   | 16        | 8.33%   |
| ASRock                 | 9         | 4.69%   |
| MSI                    | 8         | 4.17%   |
| Toshiba                | 6         | 3.13%   |
| Intel                  | 4         | 2.08%   |
| Google                 | 4         | 2.08%   |
| Apple                  | 4         | 2.08%   |
| Sony                   | 3         | 1.56%   |
| Samsung Electronics    | 3         | 1.56%   |
| Packard Bell           | 2         | 1.04%   |
| Biostar                | 2         | 1.04%   |
| Unknown                | 2         | 1.04%   |
| Valve                  | 1         | 0.52%   |
| Timi                   | 1         | 0.52%   |
| Shuttle                | 1         | 0.52%   |
| Positivo               | 1         | 0.52%   |
| Pegatron               | 1         | 0.52%   |
| Panasonic              | 1         | 0.52%   |
| MEGA                   | 1         | 0.52%   |
| HUAWEI                 | 1         | 0.52%   |
| Howard Computers       | 1         | 0.52%   |
| GPU Company            | 1         | 0.52%   |
| Fujitsu                | 1         | 0.52%   |
| Framework              | 1         | 0.52%   |
| eMachines              | 1         | 0.52%   |
| Chuwi                  | 1         | 0.52%   |
| AZW                    | 1         | 0.52%   |
| Avell High Performance | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 3         | 1.56%   |
| HP ProBook 450 G5                                     | 2         | 1.04%   |
| Google Kip                                            | 2         | 1.04%   |
| Acer Nitro AN515-45                                   | 2         | 1.04%   |
| Acer Aspire E5-575G                                   | 2         | 1.04%   |
| Valve Jupiter                                         | 1         | 0.52%   |
| Toshiba TECRA R840                                    | 1         | 0.52%   |
| Toshiba Satellite P50-A                               | 1         | 0.52%   |
| Toshiba Satellite L855                                | 1         | 0.52%   |
| Toshiba Satellite L655                                | 1         | 0.52%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 0.52%   |
| Timi TM1701                                           | 1         | 0.52%   |
| Sony VPCYB15AB                                        | 1         | 0.52%   |
| Sony VPCF236FM                                        | 1         | 0.52%   |
| Sony VPCEB1S1E                                        | 1         | 0.52%   |
| Shuttle XS35V4                                        | 1         | 0.52%   |
| Samsung R430/P430/R480                                | 1         | 0.52%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.52%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 0.52%   |
| Positivo POS-EINM10CB                                 | 1         | 0.52%   |
| Pegatron IPM31                                        | 1         | 0.52%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 0.52%   |
| Packard Bell EasyNote TS11HR                          | 1         | 0.52%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.52%   |
| MSI MS-7C91                                           | 1         | 0.52%   |
| MSI MS-7B89                                           | 1         | 0.52%   |
| MSI MS-7B85                                           | 1         | 0.52%   |
| MSI MS-7B84                                           | 1         | 0.52%   |
| MSI MS-7A34                                           | 1         | 0.52%   |
| MSI MS-7850                                           | 1         | 0.52%   |
| MSI MS-7640                                           | 1         | 0.52%   |
| MSI Modern 14 B5M                                     | 1         | 0.52%   |
| MEGA G41T-M7 LGT                                      | 1         | 0.52%   |
| Lenovo Z51-70 80K6                                    | 1         | 0.52%   |
| Lenovo Z50-70 20354                                   | 1         | 0.52%   |
| Lenovo Yoga 730-13IKB 81CT                            | 1         | 0.52%   |
| Lenovo Yoga 7 15ITL5 82BJ                             | 1         | 0.52%   |
| Lenovo Yoga 510-14ISK 80S7                            | 1         | 0.52%   |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 5.21%   |
| Acer Aspire            | 9         | 4.69%   |
| Dell Latitude          | 7         | 3.65%   |
| Dell Inspiron          | 6         | 3.13%   |
| Lenovo IdeaPad         | 5         | 2.6%    |
| HP ProBook             | 5         | 2.6%    |
| HP Pavilion            | 4         | 2.08%   |
| Gigabyte Z390          | 4         | 2.08%   |
| Dell XPS               | 4         | 2.08%   |
| ASUS TUF               | 4         | 2.08%   |
| Toshiba Satellite      | 3         | 1.56%   |
| Lenovo Yoga            | 3         | 1.56%   |
| ASUS PRIME             | 3         | 1.56%   |
| Acer Swift             | 3         | 1.56%   |
| Unknown                | 3         | 1.56%   |
| Packard Bell EasyNote  | 2         | 1.04%   |
| Intel X99              | 2         | 1.04%   |
| HP Stream              | 2         | 1.04%   |
| HP ENVY                | 2         | 1.04%   |
| HP EliteBook           | 2         | 1.04%   |
| Google Kip             | 2         | 1.04%   |
| Dell Vostro            | 2         | 1.04%   |
| Dell OptiPlex          | 2         | 1.04%   |
| ASUS VivoBook          | 2         | 1.04%   |
| ASUS ROG               | 2         | 1.04%   |
| Acer Nitro             | 2         | 1.04%   |
| Valve Jupiter          | 1         | 0.52%   |
| Toshiba TECRA          | 1         | 0.52%   |
| Toshiba PORTEGE        | 1         | 0.52%   |
| Timi TM1701            | 1         | 0.52%   |
| Sony VPCYB15AB         | 1         | 0.52%   |
| Sony VPCF236FM         | 1         | 0.52%   |
| Sony VPCEB1S1E         | 1         | 0.52%   |
| Shuttle XS35V4         | 1         | 0.52%   |
| Samsung R430           | 1         | 0.52%   |
| Samsung 300E5EV        | 1         | 0.52%   |
| Samsung 270E5K         | 1         | 0.52%   |
| Positivo POS-EINM10CB  | 1         | 0.52%   |
| Pegatron IPM31         | 1         | 0.52%   |
| Panasonic CF-C2CCEZXCM | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 30        | 15.63%  |
| 2019 | 18        | 9.38%   |
| 2014 | 18        | 9.38%   |
| 2017 | 15        | 7.81%   |
| 2021 | 14        | 7.29%   |
| 2016 | 14        | 7.29%   |
| 2012 | 14        | 7.29%   |
| 2020 | 13        | 6.77%   |
| 2011 | 12        | 6.25%   |
| 2013 | 9         | 4.69%   |
| 2008 | 9         | 4.69%   |
| 2010 | 8         | 4.17%   |
| 2015 | 5         | 2.6%    |
| 2009 | 4         | 2.08%   |
| 2022 | 3         | 1.56%   |
| 2006 | 3         | 1.56%   |
| 2007 | 2         | 1.04%   |
| 2023 | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 108       | 56.25%  |
| Desktop     | 71        | 36.98%  |
| Convertible | 9         | 4.69%   |
| All in one  | 2         | 1.04%   |
| Tablet      | 1         | 0.52%   |
| Mini pc     | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 188       | 97.92%  |
| Enabled  | 4         | 2.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 188       | 97.92%  |
| Yes  | 4         | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 47        | 24.1%   |
| 3.01-4.0    | 44        | 22.56%  |
| 8.01-16.0   | 39        | 20%     |
| 4.01-8.0    | 32        | 16.41%  |
| 32.01-64.0  | 20        | 10.26%  |
| 1.01-2.0    | 5         | 2.56%   |
| 24.01-32.0  | 4         | 2.05%   |
| 2.01-3.0    | 3         | 1.54%   |
| 64.01-256.0 | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 74        | 35.58%  |
| 2.01-3.0   | 55        | 26.44%  |
| 3.01-4.0   | 28        | 13.46%  |
| 4.01-8.0   | 26        | 12.5%   |
| 8.01-16.0  | 12        | 5.77%   |
| 0.51-1.0   | 12        | 5.77%   |
| 16.01-24.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 109       | 54.77%  |
| 2      | 54        | 27.14%  |
| 4      | 14        | 7.04%   |
| 3      | 11        | 5.53%   |
| 5      | 7         | 3.52%   |
| 6      | 3         | 1.51%   |
| 7      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 123       | 63.08%  |
| Yes       | 72        | 36.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 85.42%  |
| No        | 28        | 14.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 80.83%  |
| No        | 37        | 19.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 65.98%  |
| No        | 66        | 34.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 36        | 18.75%  |
| Brazil       | 14        | 7.29%   |
| Germany      | 12        | 6.25%   |
| Netherlands  | 10        | 5.21%   |
| Russia       | 9         | 4.69%   |
| India        | 9         | 4.69%   |
| France       | 7         | 3.65%   |
| Canada       | 6         | 3.13%   |
| Sweden       | 5         | 2.6%    |
| Spain        | 5         | 2.6%    |
| Australia    | 5         | 2.6%    |
| Poland       | 4         | 2.08%   |
| Norway       | 4         | 2.08%   |
| UK           | 3         | 1.56%   |
| Turkey       | 3         | 1.56%   |
| Switzerland  | 3         | 1.56%   |
| Romania      | 3         | 1.56%   |
| New Zealand  | 3         | 1.56%   |
| Mexico       | 3         | 1.56%   |
| Indonesia    | 3         | 1.56%   |
| Chile        | 3         | 1.56%   |
| Argentina    | 3         | 1.56%   |
| Venezuela    | 2         | 1.04%   |
| Ukraine      | 2         | 1.04%   |
| Saudi Arabia | 2         | 1.04%   |
| Iran         | 2         | 1.04%   |
| Guatemala    | 2         | 1.04%   |
| Greece       | 2         | 1.04%   |
| Finland      | 2         | 1.04%   |
| China        | 2         | 1.04%   |
| Austria      | 2         | 1.04%   |
| Albania      | 2         | 1.04%   |
| Vietnam      | 1         | 0.52%   |
| Thailand     | 1         | 0.52%   |
| Portugal     | 1         | 0.52%   |
| Philippines  | 1         | 0.52%   |
| Peru         | 1         | 0.52%   |
| Oman         | 1         | 0.52%   |
| Nepal        | 1         | 0.52%   |
| Latvia       | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Melbourne                 | 4         | 1.93%   |
| Toronto                   | 3         | 1.45%   |
| The Hague                 | 3         | 1.45%   |
| Oslo                      | 3         | 1.45%   |
| Mainz                     | 3         | 1.45%   |
| Constanța                | 3         | 1.45%   |
| Amsterdam                 | 3         | 1.45%   |
| Zurich                    | 2         | 0.97%   |
| Vienna                    | 2         | 0.97%   |
| Stockholm                 | 2         | 0.97%   |
| St Petersburg             | 2         | 0.97%   |
| Severna Park              | 2         | 0.97%   |
| San Justo                 | 2         | 0.97%   |
| San Francisco del Rincón | 2         | 0.97%   |
| New York                  | 2         | 0.97%   |
| Guelph                    | 2         | 0.97%   |
| Guatemala City            | 2         | 0.97%   |
| Curitiba                  | 2         | 0.97%   |
| Columbus                  | 2         | 0.97%   |
| Caracas                   | 2         | 0.97%   |
| Beijing                   | 2         | 0.97%   |
| Auckland                  | 2         | 0.97%   |
| Zhytomyr                  | 1         | 0.48%   |
| Yverdon-les-Bains         | 1         | 0.48%   |
| Yekaterinburg             | 1         | 0.48%   |
| Wendell                   | 1         | 0.48%   |
| Weil am Rhein             | 1         | 0.48%   |
| Warrensburg               | 1         | 0.48%   |
| Vineland                  | 1         | 0.48%   |
| Viby J                    | 1         | 0.48%   |
| Vasco da Gama             | 1         | 0.48%   |
| Vancouver                 | 1         | 0.48%   |
| Uppsala                   | 1         | 0.48%   |
| Uberlândia               | 1         | 0.48%   |
| Trondheim                 | 1         | 0.48%   |
| Trabzon                   | 1         | 0.48%   |
| Tirana                    | 1         | 0.48%   |
| Thessaloniki              | 1         | 0.48%   |
| Terranuova Bracciolini    | 1         | 0.48%   |
| Teresopolis               | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 50        | 75     | 16.34%  |
| Samsung Electronics         | 44        | 83     | 14.38%  |
| Seagate                     | 35        | 61     | 11.44%  |
| Toshiba                     | 24        | 29     | 7.84%   |
| Kingston                    | 20        | 24     | 6.54%   |
| Unknown                     | 19        | 21     | 6.21%   |
| SanDisk                     | 19        | 25     | 6.21%   |
| Intel                       | 15        | 19     | 4.9%    |
| SK hynix                    | 11        | 11     | 3.59%   |
| Crucial                     | 11        | 14     | 3.59%   |
| Micron Technology           | 6         | 7      | 1.96%   |
| A-DATA Technology           | 6         | 6      | 1.96%   |
| Hitachi                     | 5         | 5      | 1.63%   |
| Silicon Motion              | 3         | 3      | 0.98%   |
| PNY                         | 3         | 3      | 0.98%   |
| Kingston Technology Company | 3         | 3      | 0.98%   |
| China                       | 3         | 3      | 0.98%   |
| Phison Electronics          | 2         | 3      | 0.65%   |
| Phison                      | 2         | 2      | 0.65%   |
| Patriot                     | 2         | 3      | 0.65%   |
| Maxtor                      | 2         | 2      | 0.65%   |
| HGST                        | 2         | 2      | 0.65%   |
| Gigabyte Technology         | 2         | 2      | 0.65%   |
| Apple                       | 2         | 6      | 0.65%   |
| Transcend                   | 1         | 1      | 0.33%   |
| SPCC Sol                    | 1         | 1      | 0.33%   |
| SABRENT                     | 1         | 1      | 0.33%   |
| O2 Micro                    | 1         | 1      | 0.33%   |
| Micron/Crucial Technology   | 1         | 1      | 0.33%   |
| Lenovo                      | 1         | 1      | 0.33%   |
| KIOXIA                      | 1         | 1      | 0.33%   |
| KingFast                    | 1         | 1      | 0.33%   |
| Intenso                     | 1         | 2      | 0.33%   |
| HFS512GD                    | 1         | 1      | 0.33%   |
| FORESEE                     | 1         | 1      | 0.33%   |
| Emtec                       | 1         | 1      | 0.33%   |
| Corsair                     | 1         | 1      | 0.33%   |
| Advantech                   | 1         | 1      | 0.33%   |
| AAPL                        | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                         | 9         | 2.61%   |
| Samsung NVMe SSD Drive 500GB                      | 7         | 2.03%   |
| Kingston SA400S37240G 240GB SSD                   | 6         | 1.74%   |
| Toshiba MQ01ABD100 1TB                            | 5         | 1.45%   |
| Samsung SSD 850 EVO 500GB                         | 5         | 1.45%   |
| Unknown MMC Card  32GB                            | 4         | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                   | 4         | 1.16%   |
| Samsung SSD 860 EVO 500GB                         | 4         | 1.16%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3         | 0.87%   |
| SK hynix NVMe SSD Drive 128GB                     | 3         | 0.87%   |
| Seagate ST4000DM004-2CV104 4TB                    | 3         | 0.87%   |
| Seagate ST31000528AS 1TB                          | 3         | 0.87%   |
| Seagate ST2000DX002-2DV164 2TB                    | 3         | 0.87%   |
| Seagate ST2000DM006-2DM164 2TB                    | 3         | 0.87%   |
| SanDisk NVMe SSD Drive 256GB                      | 3         | 0.87%   |
| Samsung SSD 860 EVO 250GB                         | 3         | 0.87%   |
| Intel NVMe SSD Drive 256GB                        | 3         | 0.87%   |
| Crucial CT1000MX500SSD1 1TB                       | 3         | 0.87%   |
| WDC WD5000AAKS-00A7B0 500GB                       | 2         | 0.58%   |
| WDC WD2500BEVT-22ZCT0 250GB                       | 2         | 0.58%   |
| WDC WD20EARX-00PASB0 2TB                          | 2         | 0.58%   |
| WDC WD2003FZEX-00SRLA0 2TB                        | 2         | 0.58%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                            | 2         | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.58%   |
| WDC WD10EZEX-08M2NA0 1TB                          | 2         | 0.58%   |
| WDC WD10EADS-00M2B0 1TB                           | 2         | 0.58%   |
| Unknown TP02000GB 2TB                             | 2         | 0.58%   |
| Unknown MMC Card  128GB                           | 2         | 0.58%   |
| Toshiba NVMe SSD Drive 256GB                      | 2         | 0.58%   |
| Toshiba DT01ACA050 500GB                          | 2         | 0.58%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB           | 2         | 0.58%   |
| Seagate ST31000524AS 1TB                          | 2         | 0.58%   |
| Seagate ST2000DX001-1NS164 2TB                    | 2         | 0.58%   |
| SanDisk SDSSDA240G 240GB                          | 2         | 0.58%   |
| Samsung SSD 860 EVO 1TB                           | 2         | 0.58%   |
| Samsung NVMe SSD Drive 1TB                        | 2         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.58%   |
| PNY CS900 240GB SSD                               | 2         | 0.58%   |
| Phison E12 NVMe Controller 1TB                    | 2         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 45        | 68     | 40.54%  |
| Seagate             | 35        | 61     | 31.53%  |
| Toshiba             | 16        | 21     | 14.41%  |
| Hitachi             | 5         | 5      | 4.5%    |
| Samsung Electronics | 3         | 5      | 2.7%    |
| Maxtor              | 2         | 2      | 1.8%    |
| HGST                | 2         | 2      | 1.8%    |
| Unknown             | 1         | 1      | 0.9%    |
| Intenso             | 1         | 2      | 0.9%    |
| AAPL                | 1         | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 49     | 30.19%  |
| Kingston            | 14        | 17     | 13.21%  |
| SanDisk             | 10        | 14     | 9.43%   |
| Crucial             | 9         | 12     | 8.49%   |
| Micron Technology   | 5         | 6      | 4.72%   |
| Intel               | 4         | 5      | 3.77%   |
| A-DATA Technology   | 4         | 4      | 3.77%   |
| WDC                 | 3         | 3      | 2.83%   |
| PNY                 | 3         | 3      | 2.83%   |
| China               | 3         | 3      | 2.83%   |
| Unknown             | 2         | 2      | 1.89%   |
| Toshiba             | 2         | 2      | 1.89%   |
| SK hynix            | 2         | 2      | 1.89%   |
| Patriot             | 2         | 3      | 1.89%   |
| Gigabyte Technology | 2         | 2      | 1.89%   |
| Apple               | 2         | 6      | 1.89%   |
| Transcend           | 1         | 1      | 0.94%   |
| SPCC Sol            | 1         | 1      | 0.94%   |
| SABRENT             | 1         | 1      | 0.94%   |
| FORESEE             | 1         | 1      | 0.94%   |
| Emtec               | 1         | 1      | 0.94%   |
| Corsair             | 1         | 1      | 0.94%   |
| Advantech           | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 95        | 168    | 34.67%  |
| SSD     | 90        | 140    | 32.85%  |
| NVMe    | 68        | 96     | 24.82%  |
| MMC     | 13        | 14     | 4.74%   |
| Unknown | 8         | 10     | 2.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 138       | 294    | 59.23%  |
| NVMe | 68        | 96     | 29.18%  |
| SAS  | 14        | 24     | 6.01%   |
| MMC  | 13        | 14     | 5.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 109       | 178    | 58.29%  |
| 0.51-1.0   | 51        | 76     | 27.27%  |
| 1.01-2.0   | 19        | 42     | 10.16%  |
| 3.01-4.0   | 4         | 7      | 2.14%   |
| 4.01-10.0  | 2         | 2      | 1.07%   |
| 2.01-3.0   | 1         | 2      | 0.53%   |
| 10.01-20.0 | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 33.84%  |
| 251-500        | 41        | 20.71%  |
| 501-1000       | 33        | 16.67%  |
| 1001-2000      | 16        | 8.08%   |
| 51-100         | 11        | 5.56%   |
| More than 3000 | 9         | 4.55%   |
| 21-50          | 8         | 4.04%   |
| 2001-3000      | 7         | 3.54%   |
| Unknown        | 4         | 2.02%   |
| 1-20           | 2         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 65        | 31.71%  |
| 21-50          | 38        | 18.54%  |
| 101-250        | 26        | 12.68%  |
| 51-100         | 22        | 10.73%  |
| 251-500        | 20        | 9.76%   |
| 1001-2000      | 13        | 6.34%   |
| 501-1000       | 12        | 5.85%   |
| Unknown        | 4         | 1.95%   |
| 2001-3000      | 3         | 1.46%   |
| More than 3000 | 2         | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB                    | 1         | 1      | 7.69%   |
| WDC WD20EARX-00PASB0 2TB                       | 1         | 1      | 7.69%   |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 7.69%   |
| WDC WD1002FAEX-00Y9A0 1TB                      | 1         | 1      | 7.69%   |
| WDC WD1001FALS-75J7B0 1TB                      | 1         | 1      | 7.69%   |
| Toshiba MK7559GSXP 752GB                       | 1         | 1      | 7.69%   |
| Seagate ST9320325AS 320GB                      | 1         | 2      | 7.69%   |
| Seagate ST2000DM001-9YN164 2TB                 | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 970 EVO 500GB          | 1         | 1      | 7.69%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB   | 1         | 1      | 7.69%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 7.69%   |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 7.69%   |
| Crucial CT1000P1SSD8 1TB                       | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 38.46%  |
| Seagate             | 2         | 3      | 15.38%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| Toshiba             | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 55.56%  |
| Seagate | 2         | 3      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 66.67%  |
| NVMe | 3         | 3      | 25%     |
| SSD  | 1         | 1      | 8.33%   |

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
| Detected | 142       | 314    | 66.36%  |
| Works    | 60        | 100    | 28.04%  |
| Malfunc  | 12        | 14     | 5.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 128       | 51.82%  |
| AMD                          | 44        | 17.81%  |
| Samsung Electronics          | 19        | 7.69%   |
| SK hynix                     | 9         | 3.64%   |
| Kingston Technology Company  | 9         | 3.64%   |
| SanDisk                      | 8         | 3.24%   |
| Toshiba America Info Systems | 6         | 2.43%   |
| Phison Electronics           | 4         | 1.62%   |
| JMicron Technology           | 4         | 1.62%   |
| Silicon Motion               | 3         | 1.21%   |
| Micron/Crucial Technology    | 3         | 1.21%   |
| Marvell Technology Group     | 2         | 0.81%   |
| ADATA Technology             | 2         | 0.81%   |
| Solidigm                     | 1         | 0.4%    |
| O2 Micro                     | 1         | 0.4%    |
| Nvidia                       | 1         | 0.4%    |
| Micron Technology            | 1         | 0.4%    |
| Lenovo                       | 1         | 0.4%    |
| ASMedia Technology           | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 11.7%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 5.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 4.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 3.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9         | 3.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 3.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 2.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 2.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.77%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.42%   |
| Intel SSD 660P Series                                                          | 4         | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.42%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.42%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 3         | 1.06%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 1.06%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.06%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                               | 3         | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.71%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 0.71%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 2         | 0.71%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 2         | 0.71%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 2         | 0.71%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 143       | 59.09%  |
| NVMe | 68        | 28.1%   |
| IDE  | 23        | 9.5%    |
| RAID | 8         | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 144       | 75%     |
| AMD    | 48        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 3.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.08%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 2.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.56%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.04%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 1.04%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 1.04%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.04%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 2         | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.04%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 1.04%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 1.04%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.04%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 1.04%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.04%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.04%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 1.04%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.04%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 1.04%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.04%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 2         | 1.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.04%   |
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.52%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz           | 1         | 0.52%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.52%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1         | 0.52%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.52%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.52%   |
| Intel Pentium D CPU 3.00GHz                   | 1         | 0.52%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 41        | 21.35%  |
| Intel Core i7           | 37        | 19.27%  |
| AMD Ryzen 7             | 17        | 8.85%   |
| Intel Celeron           | 15        | 7.81%   |
| AMD Ryzen 5             | 15        | 7.81%   |
| Intel Core i3           | 13        | 6.77%   |
| Other                   | 9         | 4.69%   |
| Intel Core 2 Duo        | 6         | 3.13%   |
| Intel Pentium           | 5         | 2.6%    |
| Intel Xeon              | 4         | 2.08%   |
| Intel Pentium Dual-Core | 3         | 1.56%   |
| Intel Core 2 Quad       | 3         | 1.56%   |
| Intel Atom              | 3         | 1.56%   |
| AMD Ryzen 9             | 3         | 1.56%   |
| AMD A10                 | 3         | 1.56%   |
| Intel Pentium D         | 2         | 1.04%   |
| AMD Phenom II X4        | 2         | 1.04%   |
| AMD FX                  | 2         | 1.04%   |
| Intel Pentium Silver    | 1         | 0.52%   |
| Intel Pentium Dual      | 1         | 0.52%   |
| Intel Core M            | 1         | 0.52%   |
| Intel Core i9           | 1         | 0.52%   |
| Intel Core 2            | 1         | 0.52%   |
| AMD Ryzen 3             | 1         | 0.52%   |
| AMD E1                  | 1         | 0.52%   |
| AMD E                   | 1         | 0.52%   |
| AMD A8                  | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 82        | 42.71%  |
| 4      | 69        | 35.94%  |
| 6      | 18        | 9.38%   |
| 8      | 17        | 8.85%   |
| 10     | 2         | 1.04%   |
| 16     | 1         | 0.52%   |
| 12     | 1         | 0.52%   |
| 3      | 1         | 0.52%   |
| 1      | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 192       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 139       | 72.4%   |
| 1      | 53        | 27.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 96.89%  |
| Unknown        | 6         | 3.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 12.12%  |
| 0x806ea    | 11        | 5.56%   |
| 0x306c3    | 11        | 5.56%   |
| 0x306a9    | 10        | 5.05%   |
| 0x206a7    | 10        | 5.05%   |
| 0x1067a    | 9         | 4.55%   |
| 0x806e9    | 7         | 3.54%   |
| 0x40651    | 6         | 3.03%   |
| 0x906e9    | 5         | 2.53%   |
| 0x806ec    | 5         | 2.53%   |
| 0x506e3    | 5         | 2.53%   |
| 0x20655    | 5         | 2.53%   |
| 0x0a50000c | 5         | 2.53%   |
| 0x08701021 | 5         | 2.53%   |
| 0x906ea    | 4         | 2.02%   |
| 0x806c1    | 4         | 2.02%   |
| 0x706a1    | 4         | 2.02%   |
| 0x406e3    | 4         | 2.02%   |
| 0x0800820d | 4         | 2.02%   |
| 0x306d4    | 3         | 1.52%   |
| 0x30678    | 3         | 1.52%   |
| 0x08701013 | 3         | 1.52%   |
| 0x08600106 | 3         | 1.52%   |
| 0x08108102 | 3         | 1.52%   |
| 0x0810100b | 3         | 1.52%   |
| 0x06003106 | 3         | 1.52%   |
| 0x906ec    | 2         | 1.01%   |
| 0x6fd      | 2         | 1.01%   |
| 0x08108109 | 2         | 1.01%   |
| 0x0800820b | 2         | 1.01%   |
| 0x06000852 | 2         | 1.01%   |
| 0xf64      | 1         | 0.51%   |
| 0xf62      | 1         | 0.51%   |
| 0xa0652    | 1         | 0.51%   |
| 0x906ed    | 1         | 0.51%   |
| 0x906eb    | 1         | 0.51%   |
| 0x906c0    | 1         | 0.51%   |
| 0x806eb    | 1         | 0.51%   |
| 0x706a8    | 1         | 0.51%   |
| 0x6f2      | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 21.35%  |
| Haswell          | 19        | 9.9%    |
| SandyBridge      | 13        | 6.77%   |
| Zen 2            | 12        | 6.25%   |
| Penryn           | 12        | 6.25%   |
| Zen+             | 10        | 5.21%   |
| IvyBridge        | 10        | 5.21%   |
| Skylake          | 9         | 4.69%   |
| Zen 3            | 8         | 4.17%   |
| Silvermont       | 7         | 3.65%   |
| Westmere         | 6         | 3.13%   |
| TigerLake        | 6         | 3.13%   |
| Goldmont plus    | 5         | 2.6%    |
| Core             | 5         | 2.6%    |
| Zen              | 4         | 2.08%   |
| Broadwell        | 4         | 2.08%   |
| Steamroller      | 3         | 1.56%   |
| Piledriver       | 3         | 1.56%   |
| Unknown          | 3         | 1.56%   |
| NetBurst         | 2         | 1.04%   |
| K10              | 2         | 1.04%   |
| Bobcat           | 2         | 1.04%   |
| Tremont          | 1         | 0.52%   |
| Goldmont         | 1         | 0.52%   |
| Excavator        | 1         | 0.52%   |
| CometLake        | 1         | 0.52%   |
| Bonnell          | 1         | 0.52%   |
| Alderlake Hybrid | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 113       | 48.09%  |
| Nvidia | 63        | 26.81%  |
| AMD    | 59        | 25.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 11        | 4.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 3.77%   |
| Intel HD Graphics 620                                                       | 8         | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 2.93%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 2.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5         | 2.09%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 2.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5         | 2.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 2.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4         | 1.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 1.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.26%   |
| Nvidia GM108M [GeForce 940MX]                                               | 3         | 1.26%   |
| Nvidia GF108M [GeForce GT 540M]                                             | 3         | 1.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.26%   |
| Intel HD Graphics 630                                                       | 3         | 1.26%   |
| Intel HD Graphics 530                                                       | 3         | 1.26%   |
| Intel Core Processor Integrated Graphics Controller                         | 3         | 1.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 1.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.26%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 3         | 1.26%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 1.26%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.84%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 0.84%   |
| Nvidia GM108M [GeForce 930MX]                                               | 2         | 0.84%   |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 0.84%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 2         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 0.84%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 0.84%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 2         | 0.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 39.49%  |
| 1 x AMD        | 48        | 24.62%  |
| 1 x Nvidia     | 31        | 15.9%   |
| Intel + Nvidia | 27        | 13.85%  |
| Intel + AMD    | 6         | 3.08%   |
| AMD + Nvidia   | 6         | 3.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 152       | 78.76%  |
| Proprietary | 41        | 21.24%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 84        | 42.64%  |
| 1.01-2.0   | 30        | 15.23%  |
| 0.51-1.0   | 24        | 12.18%  |
| 3.01-4.0   | 14        | 7.11%   |
| 0.01-0.5   | 14        | 7.11%   |
| 7.01-8.0   | 12        | 6.09%   |
| 5.01-6.0   | 11        | 5.58%   |
| 8.01-16.0  | 5         | 2.54%   |
| 2.01-3.0   | 3         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 13.22%  |
| Samsung Electronics     | 28        | 12.33%  |
| BOE                     | 21        | 9.25%   |
| LG Display              | 18        | 7.93%   |
| Goldstar                | 16        | 7.05%   |
| Chimei Innolux          | 16        | 7.05%   |
| AOC                     | 13        | 5.73%   |
| Dell                    | 11        | 4.85%   |
| Ancor Communications    | 9         | 3.96%   |
| Lenovo                  | 7         | 3.08%   |
| BenQ                    | 6         | 2.64%   |
| Acer                    | 5         | 2.2%    |
| Sharp                   | 4         | 1.76%   |
| LG Electronics          | 4         | 1.76%   |
| Apple                   | 4         | 1.76%   |
| Philips                 | 3         | 1.32%   |
| Hewlett-Packard         | 3         | 1.32%   |
| Chi Mei Optoelectronics | 3         | 1.32%   |
| ASUSTek Computer        | 3         | 1.32%   |
| Unknown                 | 2         | 0.88%   |
| PANDA                   | 2         | 0.88%   |
| NEC Computers           | 2         | 0.88%   |
| Unknown                 | 2         | 0.88%   |
| ___                     | 1         | 0.44%   |
| ViewSonic               | 1         | 0.44%   |
| Valve                   | 1         | 0.44%   |
| Toshiba                 | 1         | 0.44%   |
| Sony                    | 1         | 0.44%   |
| Positivo                | 1         | 0.44%   |
| MStar                   | 1         | 0.44%   |
| MSI                     | 1         | 0.44%   |
| Microstep               | 1         | 0.44%   |
| Mi                      | 1         | 0.44%   |
| LG Philips              | 1         | 0.44%   |
| JRY                     | 1         | 0.44%   |
| Iiyama                  | 1         | 0.44%   |
| GKK                     | 1         | 0.44%   |
| CSO                     | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 3         | 1.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2         | 0.86%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                 | 2         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 2         | 0.86%   |
| BOE LCD Monitor BOE0638 1920x1080 309x173mm 13.9-inch                | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.86%   |
| Ancor Communications LCD Monitor MG248 1920x1080                     | 2         | 0.86%   |
| Unknown                                                              | 2         | 0.86%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1         | 0.43%   |
| ViewSonic VP191b VSC0E11 1280x1024 376x301mm 19.0-inch               | 1         | 0.43%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.43%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.43%   |
| Unknown LCD Monitor HIC 3200x1080                                    | 1         | 0.43%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch            | 1         | 0.43%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                | 1         | 0.43%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch              | 1         | 0.43%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.43%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 1         | 0.43%   |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM029A 1920x1200 582x364mm 27.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 0.43%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch  | 1         | 0.43%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 0.43%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch   | 1         | 0.43%   |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1         | 0.43%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch    | 1         | 0.43%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1         | 0.43%   |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 93        | 43.26%  |
| 1366x768 (WXGA)    | 41        | 19.07%  |
| 1600x900 (HD+)     | 11        | 5.12%   |
| 2560x1440 (QHD)    | 10        | 4.65%   |
| 3840x2160 (4K)     | 8         | 3.72%   |
| 1440x900 (WXGA+)   | 7         | 3.26%   |
| 1280x1024 (SXGA)   | 7         | 3.26%   |
| 1680x1050 (WSXGA+) | 6         | 2.79%   |
| Unknown            | 6         | 2.79%   |
| 1920x1200 (WUXGA)  | 5         | 2.33%   |
| 3840x1080          | 3         | 1.4%    |
| 2560x1080          | 3         | 1.4%    |
| 1360x768           | 3         | 1.4%    |
| 1280x800 (WXGA)    | 3         | 1.4%    |
| 800x1280           | 1         | 0.47%   |
| 5760x1080          | 1         | 0.47%   |
| 4480x1440          | 1         | 0.47%   |
| 3440x1440          | 1         | 0.47%   |
| 3200x1080          | 1         | 0.47%   |
| 2560x1600          | 1         | 0.47%   |
| 2256x1504          | 1         | 0.47%   |
| 1152x864           | 1         | 0.47%   |
| 1024x768 (XGA)     | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 61        | 27.85%  |
| 13      | 27        | 12.33%  |
| Unknown | 21        | 9.59%   |
| 14      | 16        | 7.31%   |
| 24      | 14        | 6.39%   |
| 27      | 12        | 5.48%   |
| 23      | 11        | 5.02%   |
| 21      | 10        | 4.57%   |
| 17      | 10        | 4.57%   |
| 18      | 7         | 3.2%    |
| 22      | 4         | 1.83%   |
| 20      | 4         | 1.83%   |
| 40      | 3         | 1.37%   |
| 19      | 3         | 1.37%   |
| 11      | 3         | 1.37%   |
| 34      | 2         | 0.91%   |
| 31      | 2         | 0.91%   |
| 12      | 2         | 0.91%   |
| 72      | 1         | 0.46%   |
| 52      | 1         | 0.46%   |
| 49      | 1         | 0.46%   |
| 29      | 1         | 0.46%   |
| 25      | 1         | 0.46%   |
| 16      | 1         | 0.46%   |
| 7       | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 42.59%  |
| 501-600     | 34        | 15.74%  |
| 401-500     | 27        | 12.5%   |
| Unknown     | 21        | 9.72%   |
| 201-300     | 17        | 7.87%   |
| 351-400     | 12        | 5.56%   |
| 601-700     | 4         | 1.85%   |
| 801-900     | 3         | 1.39%   |
| 701-800     | 2         | 0.93%   |
| 1001-1500   | 2         | 0.93%   |
| 1501-2000   | 1         | 0.46%   |
| 1-100       | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 143       | 71.5%   |
| 16/10   | 22        | 11%     |
| Unknown | 20        | 10%     |
| 5/4     | 4         | 2%      |
| 3/2     | 3         | 1.5%    |
| 21/9    | 3         | 1.5%    |
| 4/3     | 2         | 1%      |
| 6/5     | 1         | 0.5%    |
| 32/9    | 1         | 0.5%    |
| 0.67    | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 26.94%  |
| 81-90          | 33        | 15.07%  |
| 201-250        | 32        | 14.61%  |
| Unknown        | 21        | 9.59%   |
| 301-350        | 13        | 5.94%   |
| 151-200        | 11        | 5.02%   |
| 71-80          | 10        | 4.57%   |
| 141-150        | 8         | 3.65%   |
| 121-130        | 7         | 3.2%    |
| 251-300        | 6         | 2.74%   |
| 351-500        | 4         | 1.83%   |
| 501-1000       | 4         | 1.83%   |
| 51-60          | 3         | 1.37%   |
| More than 1000 | 2         | 0.91%   |
| 61-70          | 2         | 0.91%   |
| 111-120        | 2         | 0.91%   |
| 1-40           | 1         | 0.46%   |
| 91-100         | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 66        | 31.13%  |
| 121-160       | 57        | 26.89%  |
| 101-120       | 47        | 22.17%  |
| Unknown       | 21        | 9.91%   |
| 161-240       | 15        | 7.08%   |
| More than 240 | 4         | 1.89%   |
| 1-50          | 2         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 153       | 78.46%  |
| 2     | 39        | 20%     |
| 3     | 3         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 107       | 34.97%  |
| Intel                         | 91        | 29.74%  |
| Qualcomm Atheros              | 42        | 13.73%  |
| Broadcom                      | 16        | 5.23%   |
| MediaTek                      | 6         | 1.96%   |
| Marvell Technology Group      | 5         | 1.63%   |
| TP-Link                       | 4         | 1.31%   |
| Ralink Technology             | 4         | 1.31%   |
| Xiaomi                        | 3         | 0.98%   |
| Ralink                        | 2         | 0.65%   |
| Dell                          | 2         | 0.65%   |
| Broadcom Limited              | 2         | 0.65%   |
| ASIX Electronics              | 2         | 0.65%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.33%   |
| T & A Mobile Phones           | 1         | 0.33%   |
| Sierra Wireless               | 1         | 0.33%   |
| Samsung Electronics           | 1         | 0.33%   |
| Qualcomm                      | 1         | 0.33%   |
| OnePlus Technology (Shenzhen) | 1         | 0.33%   |
| Nvidia                        | 1         | 0.33%   |
| NetGear                       | 1         | 0.33%   |
| Microchip Technology          | 1         | 0.33%   |
| Linksys                       | 1         | 0.33%   |
| Lenovo                        | 1         | 0.33%   |
| LeEco                         | 1         | 0.33%   |
| Jolla Oy                      | 1         | 0.33%   |
| Huawei Technologies           | 1         | 0.33%   |
| Hewlett-Packard               | 1         | 0.33%   |
| Google                        | 1         | 0.33%   |
| DisplayLink                   | 1         | 0.33%   |
| D-Link System                 | 1         | 0.33%   |
| Belkin Components             | 1         | 0.33%   |
| Aquantia                      | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 76        | 21.35%  |
| Intel Wi-Fi 6 AX200                                                    | 11        | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 10        | 2.81%   |
| Intel Wireless 8265 / 8275                                             | 10        | 2.81%   |
| Intel I211 Gigabit Network Connection                                  | 9         | 2.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 1.69%   |
| Intel Wireless 7265                                                    | 6         | 1.69%   |
| Intel Wireless 7260                                                    | 6         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.4%    |
| Intel Wireless 3165                                                    | 5         | 1.4%    |
| Intel Wi-Fi 6 AX201                                                    | 5         | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 0.84%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.84%   |
| Intel Wireless 8260                                                    | 3         | 0.84%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 0.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 2         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.56%   |
| Realtek RTL8187 Wireless Adapter                                       | 2         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.56%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.56%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                       | 2         | 0.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 43.79%  |
| Qualcomm Atheros      | 37        | 21.89%  |
| Realtek Semiconductor | 22        | 13.02%  |
| Broadcom              | 12        | 7.1%    |
| MediaTek              | 6         | 3.55%   |
| Ralink Technology     | 4         | 2.37%   |
| TP-Link               | 3         | 1.78%   |
| Ralink                | 2         | 1.18%   |
| Broadcom Limited      | 2         | 1.18%   |
| Sierra Wireless       | 1         | 0.59%   |
| NetGear               | 1         | 0.59%   |
| Linksys               | 1         | 0.59%   |
| Hewlett-Packard       | 1         | 0.59%   |
| Dell                  | 1         | 0.59%   |
| D-Link System         | 1         | 0.59%   |
| Belkin Components     | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 6.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 5.81%   |
| Intel Wireless 8265 / 8275                                     | 10        | 5.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 4.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.49%   |
| Intel Wireless 7265                                            | 6         | 3.49%   |
| Intel Wireless 7260                                            | 6         | 3.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 2.91%   |
| Intel Wireless 3165                                            | 5         | 2.91%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 2.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.74%   |
| Intel Wireless 8260                                            | 3         | 1.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.16%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 1.16%   |
| Realtek 802.11ac NIC                                           | 2         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 1.16%   |
| Qualcomm Atheros AR922X Wireless Network Adapter               | 2         | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 1.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 1.16%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.16%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.16%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.58%   |
| Sierra Wireless EM7305                                         | 1         | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.58%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.58%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 96        | 53.93%  |
| Intel                      | 45        | 25.28%  |
| Qualcomm Atheros           | 8         | 4.49%   |
| Broadcom                   | 6         | 3.37%   |
| Marvell Technology Group   | 5         | 2.81%   |
| Xiaomi                     | 3         | 1.69%   |
| ASIX Electronics           | 2         | 1.12%   |
| ZTE WCDMA Technologies MSM | 1         | 0.56%   |
| TP-Link                    | 1         | 0.56%   |
| T & A Mobile Phones        | 1         | 0.56%   |
| Samsung Electronics        | 1         | 0.56%   |
| Qualcomm                   | 1         | 0.56%   |
| Nvidia                     | 1         | 0.56%   |
| Lenovo                     | 1         | 0.56%   |
| LeEco                      | 1         | 0.56%   |
| Jolla Oy                   | 1         | 0.56%   |
| Huawei Technologies        | 1         | 0.56%   |
| Google                     | 1         | 0.56%   |
| DisplayLink                | 1         | 0.56%   |
| Aquantia                   | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 76        | 41.99%  |
| Intel I211 Gigabit Network Connection                                          | 9         | 4.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.87%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 2.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.66%   |
| Realtek Killer E2600 GbE Controller                                            | 3         | 1.66%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.66%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.1%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.1%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 1.1%    |
| Intel Ethernet Controller I225-V                                               | 2         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.1%    |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.1%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.1%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.1%    |
| ZTE WCDMA MSM Yota Router                                                      | 1         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.55%   |
| T & A Mobile Phones TCL 20E                                                    | 1         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.55%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.55%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.55%   |
| Qualcomm Android                                                               | 1         | 0.55%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.55%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.55%   |
| Lenovo Thinkpad LAN                                                            | 1         | 0.55%   |
| LeEco Android                                                                  | 1         | 0.55%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 0.55%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 164       | 50.77%  |
| WiFi     | 156       | 48.3%   |
| Modem    | 2         | 0.62%   |
| Unknown  | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 61.19%  |
| Ethernet | 78        | 38.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 109       | 56.19%  |
| 1     | 79        | 40.72%  |
| 3     | 4         | 2.06%   |
| 0     | 2         | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 83.67%  |
| Yes  | 32        | 16.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 46.56%  |
| Qualcomm Atheros Communications | 13        | 9.92%   |
| Lite-On Technology              | 10        | 7.63%   |
| Cambridge Silicon Radio         | 10        | 7.63%   |
| Broadcom                        | 9         | 6.87%   |
| Realtek Semiconductor           | 7         | 5.34%   |
| IMC Networks                    | 5         | 3.82%   |
| Apple                           | 5         | 3.82%   |
| MediaTek                        | 2         | 1.53%   |
| Foxconn / Hon Hai               | 2         | 1.53%   |
| Dell                            | 2         | 1.53%   |
| ASUSTek Computer                | 2         | 1.53%   |
| Toshiba                         | 1         | 0.76%   |
| Ralink                          | 1         | 0.76%   |
| Hewlett-Packard                 | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 22.73%  |
| Intel AX200 Bluetooth                                                               | 10        | 7.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 7.58%   |
| Intel AX201 Bluetooth                                                               | 8         | 6.06%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 3.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 3.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.27%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.27%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.52%   |
| MediaTek Wireless_Device                                                            | 2         | 1.52%   |
| Lite-On Wireless_Device                                                             | 2         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.52%   |
| Intel Bluetooth Device                                                              | 2         | 1.52%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.52%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.52%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.52%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.76%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.76%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.76%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.76%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.76%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.76%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.76%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.76%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.76%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.76%   |
| Broadcom BCM92045B3 ROM                                                             | 1         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 140       | 51.47%  |
| AMD                     | 62        | 22.79%  |
| Nvidia                  | 43        | 15.81%  |
| Blue Microphones        | 4         | 1.47%   |
| C-Media Electronics     | 3         | 1.1%    |
| Texas Instruments       | 2         | 0.74%   |
| Logitech                | 2         | 0.74%   |
| Conexant Systems        | 2         | 0.74%   |
| Yamaha                  | 1         | 0.37%   |
| Tenx Technology         | 1         | 0.37%   |
| SteelSeries ApS         | 1         | 0.37%   |
| SAVITECH                | 1         | 0.37%   |
| Samsung Electronics     | 1         | 0.37%   |
| RME                     | 1         | 0.37%   |
| Ploopy                  | 1         | 0.37%   |
| JMTek                   | 1         | 0.37%   |
| GYROCOM C&C             | 1         | 0.37%   |
| Creative Technology     | 1         | 0.37%   |
| Creative Labs           | 1         | 0.37%   |
| Cooler Master           | 1         | 0.37%   |
| BEHRINGER International | 1         | 0.37%   |
| ASUSTek Computer        | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 23        | 7.06%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 5.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 3.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 3.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.15%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.15%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.53%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.53%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.53%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.53%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.92%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.92%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3         | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 23.08%  |
| SK hynix            | 11        | 12.09%  |
| Unknown             | 10        | 10.99%  |
| Kingston            | 8         | 8.79%   |
| Crucial             | 8         | 8.79%   |
| Corsair             | 7         | 7.69%   |
| A-DATA Technology   | 7         | 7.69%   |
| Micron Technology   | 6         | 6.59%   |
| Nanya Technology    | 3         | 3.3%    |
| Ramaxel Technology  | 2         | 2.2%    |
| G.Skill             | 2         | 2.2%    |
| Elpida              | 2         | 2.2%    |
| Transcend           | 1         | 1.1%    |
| Team                | 1         | 1.1%    |
| Patriot             | 1         | 1.1%    |
| ChangXin Memory     | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 2         | 2.04%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s             | 2         | 2.04%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 2         | 2.04%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1867MT/s                      | 1         | 1.02%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 1.02%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1.02%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.02%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 1.02%   |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                        | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 1.02%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                        | 1         | 1.02%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 1.02%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                 | 1         | 1.02%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s                  | 1         | 1.02%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s                   | 1         | 1.02%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 1         | 1.02%   |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                      | 1         | 1.02%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.02%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.02%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.02%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.02%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 1.02%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.02%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.02%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 1.02%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.02%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 1.02%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.02%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.02%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 1.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.02%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.02%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.02%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.02%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.02%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.02%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 39        | 50%     |
| DDR3    | 26        | 33.33%  |
| LPDDR3  | 5         | 6.41%   |
| SDRAM   | 2         | 2.56%   |
| LPDDR4  | 2         | 2.56%   |
| DDR2    | 2         | 2.56%   |
| DDR     | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 67.11%  |
| DIMM         | 19        | 25%     |
| Row Of Chips | 6         | 7.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 39.53%  |
| 4096  | 26        | 30.23%  |
| 16384 | 11        | 12.79%  |
| 2048  | 9         | 10.47%  |
| 32768 | 3         | 3.49%   |
| 1024  | 3         | 3.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 19        | 21.59%  |
| 3200    | 12        | 13.64%  |
| 2667    | 11        | 12.5%   |
| 2400    | 9         | 10.23%  |
| 2133    | 8         | 9.09%   |
| 1867    | 3         | 3.41%   |
| Unknown | 3         | 3.41%   |
| 3733    | 2         | 2.27%   |
| 3600    | 2         | 2.27%   |
| 3533    | 2         | 2.27%   |
| 1334    | 2         | 2.27%   |
| 1333    | 2         | 2.27%   |
| 667     | 2         | 2.27%   |
| 4267    | 1         | 1.14%   |
| 3866    | 1         | 1.14%   |
| 3400    | 1         | 1.14%   |
| 3266    | 1         | 1.14%   |
| 3000    | 1         | 1.14%   |
| 2048    | 1         | 1.14%   |
| 1866    | 1         | 1.14%   |
| 1800    | 1         | 1.14%   |
| 1067    | 1         | 1.14%   |
| 1066    | 1         | 1.14%   |
| 800     | 1         | 1.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Canon              | 2         | 40%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 28        | 21.54%  |
| Realtek Semiconductor                  | 12        | 9.23%   |
| Microdia                               | 12        | 9.23%   |
| IMC Networks                           | 12        | 9.23%   |
| Logitech                               | 11        | 8.46%   |
| Quanta                                 | 7         | 5.38%   |
| Bison Electronics                      | 6         | 4.62%   |
| Sunplus Innovation Technology          | 5         | 3.85%   |
| Suyin                                  | 4         | 3.08%   |
| Lite-On Technology                     | 4         | 3.08%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.08%   |
| Apple                                  | 4         | 3.08%   |
| Syntek                                 | 3         | 2.31%   |
| Microsoft                              | 3         | 2.31%   |
| Lenovo                                 | 2         | 1.54%   |
| Importek                               | 2         | 1.54%   |
| Z-Star Microelectronics                | 1         | 0.77%   |
| Unknown                                | 1         | 0.77%   |
| Silicon Motion                         | 1         | 0.77%   |
| Samsung Electronics                    | 1         | 0.77%   |
| Ricoh                                  | 1         | 0.77%   |
| MacroSilicon                           | 1         | 0.77%   |
| Luxvisions Innotech Limited            | 1         | 0.77%   |
| LG Electronics                         | 1         | 0.77%   |
| Intel                                  | 1         | 0.77%   |
| Hewlett-Packard                        | 1         | 0.77%   |
| A4Tech                                 | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 7         | 5.3%    |
| Chicony Integrated Camera                     | 6         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 3.79%   |
| Microdia Integrated_Webcam_HD                 | 4         | 3.03%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 2.27%   |
| Realtek HD WebCam                             | 3         | 2.27%   |
| Logitech HD Pro Webcam C920                   | 3         | 2.27%   |
| IMC Networks Integrated Camera                | 3         | 2.27%   |
| Syntek Integrated Camera                      | 2         | 1.52%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 1.52%   |
| Realtek Integrated_Webcam_HD                  | 2         | 1.52%   |
| Realtek Integrated Webcam_HD                  | 2         | 1.52%   |
| Quanta HP TrueVision HD Webcam                | 2         | 1.52%   |
| Quanta HD User Facing                         | 2         | 1.52%   |
| Microdia Camera                               | 2         | 1.52%   |
| Logitech Webcam C270                          | 2         | 1.52%   |
| Logitech Logitech Webcam C160                 | 2         | 1.52%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 1.52%   |
| Chicony VGA WebCam                            | 2         | 1.52%   |
| Chicony HP Truevision HD camera               | 2         | 1.52%   |
| Chicony EasyCamera                            | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 1.52%   |
| Apple FaceTime HD Camera (Built-in)           | 2         | 1.52%   |
| Z-Star Webcam                                 | 1         | 0.76%   |
| Unknown ATIV VGA CAMERA                       | 1         | 0.76%   |
| Syntek USB2.0 Camera                          | 1         | 0.76%   |
| Suyin HP TrueVision FHD RGB-IR                | 1         | 0.76%   |
| Suyin 1.3M HD WebCam                          | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.76%   |
| Sunplus Laptop Integrated WebCam HD           | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)       | 1         | 0.76%   |
| Ricoh USB2.0 Camera                           | 1         | 0.76%   |
| Realtek Laptop Camera                         | 1         | 0.76%   |
| Realtek Integrated Webcam                     | 1         | 0.76%   |
| Realtek Integrated Camera                     | 1         | 0.76%   |
| Realtek HP Truevision HD                      | 1         | 0.76%   |
| Realtek Dell_Monitor_IR_Webcam                | 1         | 0.76%   |
| Quanta VGA WebCam                             | 1         | 0.76%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 37.93%  |
| Synaptics                  | 5         | 17.24%  |
| Shenzhen Goodix Technology | 3         | 10.34%  |
| Elan Microelectronics      | 3         | 10.34%  |
| Upek                       | 2         | 6.9%    |
| LighTuning Technology      | 2         | 6.9%    |
| AuthenTec                  | 2         | 6.9%    |
| Focal-systems.Corp         | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 13.79%  |
| Elan ELAN:Fingerprint                                  | 3         | 10.34%  |
| Validity Sensors Fingerprint scanner                   | 2         | 6.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 6.9%    |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 6.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 6.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.45%   |
| Validity Sensors VFS491                                | 1         | 3.45%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.45%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.45%   |
| Synaptics WBDI                                         | 1         | 3.45%   |
| Synaptics  WBDI                                        | 1         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 3.45%   |
| Focal-systems.Corp FT9201Fingerprint.Ì              | 1         | 3.45%   |
| AuthenTec Fingerprint Sensor                           | 1         | 3.45%   |
| AuthenTec AES2810                                      | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 25%     |
| Alcor Micro | 3         | 25%     |
| Upek        | 2         | 16.67%  |
| O2 Micro    | 1         | 8.33%   |
| Lenovo      | 1         | 8.33%   |
| Bit4id      | 1         | 8.33%   |
| Aktiv       | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 8.33%   |
| Broadcom 5880                                              | 1         | 8.33%   |
| Bit4id miniLector EVO                                      | 1         | 8.33%   |
| Aktiv Rutoken lite                                         | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 132       | 67.35%  |
| 1     | 46        | 23.47%  |
| 2     | 17        | 8.67%   |
| 3     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 29        | 34.52%  |
| Net/wireless          | 21        | 25%     |
| Chipcard              | 11        | 13.1%   |
| Multimedia controller | 7         | 8.33%   |
| Graphics card         | 7         | 8.33%   |
| Unassigned class      | 2         | 2.38%   |
| Camera                | 2         | 2.38%   |
| Tv card               | 1         | 1.19%   |
| Storage               | 1         | 1.19%   |
| Network               | 1         | 1.19%   |
| Net/ethernet          | 1         | 1.19%   |
| Bluetooth             | 1         | 1.19%   |


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

Total: 318

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5550              | Notebook    | [cb0a51f3fc](https://linux-hardware.org/?probe=cb0a51f3fc) | Dec 23, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [9ac7ef6ed0](https://linux-hardware.org/?probe=9ac7ef6ed0) | Dec 06, 2024 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [f518a2fbc3](https://linux-hardware.org/?probe=f518a2fbc3) | Nov 30, 2024 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [43af28812b](https://linux-hardware.org/?probe=43af28812b) | Nov 16, 2024 |
| MSI           | Z97 GAMING 5                | Desktop     | [62aa62c973](https://linux-hardware.org/?probe=62aa62c973) | Oct 25, 2024 |
| Google        | Pirika                      | Notebook    | [e41945c3f4](https://linux-hardware.org/?probe=e41945c3f4) | Oct 16, 2024 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [4f00b3769d](https://linux-hardware.org/?probe=4f00b3769d) | Sep 19, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [492b40fefb](https://linux-hardware.org/?probe=492b40fefb) | Sep 13, 2024 |
| Toshiba       | Satellite Pro C850-1J2      | Notebook    | [95322ce7fc](https://linux-hardware.org/?probe=95322ce7fc) | Sep 02, 2024 |
| Dell          | Latitude E5470              | Notebook    | [42433b40f6](https://linux-hardware.org/?probe=42433b40f6) | Aug 31, 2024 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [87961c091a](https://linux-hardware.org/?probe=87961c091a) | Aug 15, 2024 |
| Dell          | Latitude 5590               | Notebook    | [9963ff0d8f](https://linux-hardware.org/?probe=9963ff0d8f) | Jun 06, 2024 |
| Dell          | Latitude 5590               | Notebook    | [452b9560aa](https://linux-hardware.org/?probe=452b9560aa) | May 29, 2024 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [53c26896f2](https://linux-hardware.org/?probe=53c26896f2) | May 25, 2024 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [3a7873efe4](https://linux-hardware.org/?probe=3a7873efe4) | May 24, 2024 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [c19c792972](https://linux-hardware.org/?probe=c19c792972) | Apr 29, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [c065f8efda](https://linux-hardware.org/?probe=c065f8efda) | Mar 31, 2024 |
| Packard Be... | EasyNote MH36               | Notebook    | [db4c360048](https://linux-hardware.org/?probe=db4c360048) | Mar 30, 2024 |
| MSI           | Z170A PC MATE               | Desktop     | [927a9e8dee](https://linux-hardware.org/?probe=927a9e8dee) | Mar 27, 2024 |
| Dell          | Latitude E5470              | Notebook    | [844e9a99df](https://linux-hardware.org/?probe=844e9a99df) | Mar 24, 2024 |
| Dell          | Latitude E5470              | Notebook    | [a268f7138b](https://linux-hardware.org/?probe=a268f7138b) | Mar 24, 2024 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [33a07105de](https://linux-hardware.org/?probe=33a07105de) | Mar 24, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [7f9c1e49a4](https://linux-hardware.org/?probe=7f9c1e49a4) | Mar 03, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [c3230ba277](https://linux-hardware.org/?probe=c3230ba277) | Mar 03, 2024 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Solus 4.3    | 73        | 32.16%  |
| Solus 4.1    | 65        | 28.63%  |
| Solus 4.2    | 25        | 11.01%  |
| Solus 4.0    | 23        | 10.13%  |
| Solus 4.4    | 17        | 7.49%   |
| Solus 4.5    | 16        | 7.05%   |
| Solus 4.6    | 6         | 2.64%   |
| Solus 3.9999 | 2         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Solus | 211       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 15        | 6.12%   |
| 5.6.19-159.current  | 10        | 4.08%   |
| 6.0.11-225.current  | 8         | 3.27%   |
| 5.15.32-213.current | 8         | 3.27%   |
| 5.13.1-187.current  | 8         | 3.27%   |
| 5.5.7-150.current   | 7         | 2.86%   |
| 5.14.21-210.current | 7         | 2.86%   |
| 6.3.8-240.current   | 6         | 2.45%   |
| 5.6.4-152.current   | 6         | 2.45%   |
| 5.6.13-153.current  | 6         | 2.45%   |
| 5.15.50-216.current | 6         | 2.45%   |
| 5.14.16-205.current | 6         | 2.45%   |
| 6.1.5-229.current   | 5         | 2.04%   |
| 5.6.18-156.current  | 5         | 2.04%   |
| 5.4.12-144.current  | 5         | 2.04%   |
| 5.13.6-190.current  | 5         | 2.04%   |
| 5.13.12-193.current | 5         | 2.04%   |
| 5.11.12-177.current | 5         | 2.04%   |
| 5.5.11-151.current  | 4         | 1.63%   |
| 5.11.22-180.current | 4         | 1.63%   |
| 5.10.15-172.current | 4         | 1.63%   |
| 6.8.10-291.current  | 3         | 1.22%   |
| 6.6.21-280.current  | 3         | 1.22%   |
| 6.11.10-310.current | 3         | 1.22%   |
| 5.3.7-132.current   | 3         | 1.22%   |
| 5.3.15-138.current  | 3         | 1.22%   |
| 5.2.20-130.current  | 3         | 1.22%   |
| 5.15.77-219.current | 3         | 1.22%   |
| 5.10.7-168.current  | 3         | 1.22%   |
| 6.6.22-281.current  | 2         | 0.82%   |
| 6.5.5-258.current   | 2         | 0.82%   |
| 6.4.15-254.current  | 2         | 0.82%   |
| 6.10.6-300.current  | 2         | 0.82%   |
| 6.10.13-304.current | 2         | 0.82%   |
| 5.5.4-148.current   | 2         | 0.82%   |
| 5.4.1-137.current   | 2         | 0.82%   |
| 5.3.10-134.current  | 2         | 0.82%   |
| 5.2.2-122.current   | 2         | 0.82%   |
| 5.15.43-215.current | 2         | 0.82%   |
| 5.15.37-214.current | 2         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6.19  | 25        | 10.2%   |
| 6.0.11  | 8         | 3.27%   |
| 5.15.32 | 8         | 3.27%   |
| 5.13.1  | 8         | 3.27%   |
| 5.5.7   | 7         | 2.86%   |
| 5.14.21 | 7         | 2.86%   |
| 5.14.16 | 7         | 2.86%   |
| 6.3.8   | 6         | 2.45%   |
| 5.6.4   | 6         | 2.45%   |
| 5.6.18  | 6         | 2.45%   |
| 5.6.13  | 6         | 2.45%   |
| 5.4.12  | 6         | 2.45%   |
| 5.15.50 | 6         | 2.45%   |
| 6.1.5   | 5         | 2.04%   |
| 5.13.6  | 5         | 2.04%   |
| 5.13.12 | 5         | 2.04%   |
| 5.11.12 | 5         | 2.04%   |
| 5.5.11  | 4         | 1.63%   |
| 5.11.22 | 4         | 1.63%   |
| 5.10.15 | 4         | 1.63%   |
| 6.8.10  | 3         | 1.22%   |
| 6.6.21  | 3         | 1.22%   |
| 6.11.10 | 3         | 1.22%   |
| 5.3.7   | 3         | 1.22%   |
| 5.3.15  | 3         | 1.22%   |
| 5.2.20  | 3         | 1.22%   |
| 5.15.77 | 3         | 1.22%   |
| 5.10.7  | 3         | 1.22%   |
| 6.6.22  | 2         | 0.82%   |
| 6.5.5   | 2         | 0.82%   |
| 6.4.15  | 2         | 0.82%   |
| 6.3.12  | 2         | 0.82%   |
| 6.10.6  | 2         | 0.82%   |
| 6.10.13 | 2         | 0.82%   |
| 5.5.4   | 2         | 0.82%   |
| 5.4.1   | 2         | 0.82%   |
| 5.3.10  | 2         | 0.82%   |
| 5.2.2   | 2         | 0.82%   |
| 5.15.43 | 2         | 0.82%   |
| 5.15.37 | 2         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.6     | 42        | 17.5%   |
| 5.15    | 27        | 11.25%  |
| 5.13    | 21        | 8.75%   |
| 5.14    | 19        | 7.92%   |
| 5.5     | 14        | 5.83%   |
| 5.11    | 14        | 5.83%   |
| 5.10    | 13        | 5.42%   |
| 6.6     | 9         | 3.75%   |
| 5.3     | 9         | 3.75%   |
| 6.3     | 8         | 3.33%   |
| 6.0     | 8         | 3.33%   |
| 5.4     | 8         | 3.33%   |
| 6.10    | 6         | 2.5%    |
| 6.1     | 6         | 2.5%    |
| 5.2     | 6         | 2.5%    |
| 6.8     | 4         | 1.67%   |
| 6.4     | 4         | 1.67%   |
| 6.11    | 4         | 1.67%   |
| 6.5     | 3         | 1.25%   |
| 5.12    | 3         | 1.25%   |
| 4.20    | 3         | 1.25%   |
| 4.14    | 3         | 1.25%   |
| 5.0     | 2         | 0.83%   |
| 6.9     | 1         | 0.42%   |
| 6.2     | 1         | 0.42%   |
| 4.9     | 1         | 0.42%   |
| 4.18    | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 211       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Budgie  | 117       | 53.42%  |
| Unknown | 30        | 13.7%   |
| GNOME   | 27        | 12.33%  |
| KDE     | 16        | 7.31%   |
| MATE    | 15        | 6.85%   |
| KDE5    | 10        | 4.57%   |
| KDE6    | 4         | 1.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 199       | 92.99%  |
| Wayland | 12        | 5.61%   |
| Unknown | 3         | 1.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 152       | 70.37%  |
| LightDM | 26        | 12.04%  |
| TDM     | 19        | 8.8%    |
| GDM     | 11        | 5.09%   |
| SDDM    | 8         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 103       | 47.91%  |
| Unknown | 13        | 6.05%   |
| de_DE   | 12        | 5.58%   |
| pt_BR   | 10        | 4.65%   |
| fr_FR   | 10        | 4.65%   |
| en_GB   | 10        | 4.65%   |
| ru_RU   | 8         | 3.72%   |
| es_ES   | 8         | 3.72%   |
| pl_PL   | 7         | 3.26%   |
| it_IT   | 5         | 2.33%   |
| en_AU   | 4         | 1.86%   |
| ro_RO   | 3         | 1.4%    |
| tr_TR   | 2         | 0.93%   |
| fi_FI   | 2         | 0.93%   |
| en_NZ   | 2         | 0.93%   |
| en_IN   | 2         | 0.93%   |
| uk_UA   | 1         | 0.47%   |
| pt_PT   | 1         | 0.47%   |
| nl_NL   | 1         | 0.47%   |
| id_ID   | 1         | 0.47%   |
| es_VE   | 1         | 0.47%   |
| es_MX   | 1         | 0.47%   |
| es_CL   | 1         | 0.47%   |
| en_SG   | 1         | 0.47%   |
| en_IE   | 1         | 0.47%   |
| en_DK   | 1         | 0.47%   |
| en_CA   | 1         | 0.47%   |
| de_AT   | 1         | 0.47%   |
| ar_SA   | 1         | 0.47%   |
| ar_EG   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 123       | 57.21%  |
| BIOS | 92        | 42.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 189       | 87.91%  |
| Unknown | 10        | 4.65%   |
| Tmpfs   | 8         | 3.72%   |
| Overlay | 3         | 1.4%    |
| Btrfs   | 3         | 1.4%    |
| Xfs     | 2         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 64.84%  |
| GPT     | 57        | 26.03%  |
| MBR     | 20        | 9.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 193       | 91.04%  |
| Yes       | 19        | 8.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 179       | 83.26%  |
| Yes       | 36        | 16.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 29        | 13.74%  |
| Dell                   | 26        | 12.32%  |
| Hewlett-Packard        | 24        | 11.37%  |
| ASUSTek Computer       | 24        | 11.37%  |
| Gigabyte Technology    | 20        | 9.48%   |
| Acer                   | 17        | 8.06%   |
| MSI                    | 10        | 4.74%   |
| ASRock                 | 9         | 4.27%   |
| Toshiba                | 7         | 3.32%   |
| Apple                  | 6         | 2.84%   |
| Google                 | 5         | 2.37%   |
| Intel                  | 4         | 1.9%    |
| Sony                   | 3         | 1.42%   |
| Samsung Electronics    | 3         | 1.42%   |
| Packard Bell           | 3         | 1.42%   |
| HUAWEI                 | 2         | 0.95%   |
| Biostar                | 2         | 0.95%   |
| Unknown                | 2         | 0.95%   |
| Valve                  | 1         | 0.47%   |
| Timi                   | 1         | 0.47%   |
| Shuttle                | 1         | 0.47%   |
| Positivo               | 1         | 0.47%   |
| Pegatron               | 1         | 0.47%   |
| Panasonic              | 1         | 0.47%   |
| MEGA                   | 1         | 0.47%   |
| Howard Computers       | 1         | 0.47%   |
| GPU Company            | 1         | 0.47%   |
| Fujitsu                | 1         | 0.47%   |
| Framework              | 1         | 0.47%   |
| eMachines              | 1         | 0.47%   |
| Chuwi                  | 1         | 0.47%   |
| AZW                    | 1         | 0.47%   |
| Avell High Performance | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 3         | 1.42%   |
| HP ProBook 450 G5                                     | 2         | 0.95%   |
| Google Kip                                            | 2         | 0.95%   |
| Dell Latitude E5470                                   | 2         | 0.95%   |
| Acer Nitro AN515-45                                   | 2         | 0.95%   |
| Acer Aspire E5-575G                                   | 2         | 0.95%   |
| Valve Jupiter                                         | 1         | 0.47%   |
| Toshiba TECRA R840                                    | 1         | 0.47%   |
| Toshiba Satellite Pro C850-1J2                        | 1         | 0.47%   |
| Toshiba Satellite P50-A                               | 1         | 0.47%   |
| Toshiba Satellite L855                                | 1         | 0.47%   |
| Toshiba Satellite L655                                | 1         | 0.47%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 0.47%   |
| Timi TM1701                                           | 1         | 0.47%   |
| Sony VPCYB15AB                                        | 1         | 0.47%   |
| Sony VPCF236FM                                        | 1         | 0.47%   |
| Sony VPCEB1S1E                                        | 1         | 0.47%   |
| Shuttle XS35V4                                        | 1         | 0.47%   |
| Samsung R430/P430/R480                                | 1         | 0.47%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.47%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 0.47%   |
| Positivo POS-EINM10CB                                 | 1         | 0.47%   |
| Pegatron IPM31                                        | 1         | 0.47%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 0.47%   |
| Packard Bell EasyNote TS11HR                          | 1         | 0.47%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.47%   |
| Packard Bell EasyNote MH36                            | 1         | 0.47%   |
| MSI MS-7C91                                           | 1         | 0.47%   |
| MSI MS-7B89                                           | 1         | 0.47%   |
| MSI MS-7B85                                           | 1         | 0.47%   |
| MSI MS-7B84                                           | 1         | 0.47%   |
| MSI MS-7A34                                           | 1         | 0.47%   |
| MSI MS-7971                                           | 1         | 0.47%   |
| MSI MS-7917                                           | 1         | 0.47%   |
| MSI MS-7850                                           | 1         | 0.47%   |
| MSI MS-7640                                           | 1         | 0.47%   |
| MSI Modern 14 B5M                                     | 1         | 0.47%   |
| MEGA G41T-M7 LGT                                      | 1         | 0.47%   |
| Lenovo Z51-70 80K6                                    | 1         | 0.47%   |
| Lenovo Z50-70 20354                                   | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 11        | 5.21%   |
| Dell Latitude          | 10        | 4.74%   |
| Acer Aspire            | 10        | 4.74%   |
| Dell Inspiron          | 7         | 3.32%   |
| Lenovo IdeaPad         | 6         | 2.84%   |
| HP ProBook             | 5         | 2.37%   |
| HP Pavilion            | 5         | 2.37%   |
| Toshiba Satellite      | 4         | 1.9%    |
| Lenovo Yoga            | 4         | 1.9%    |
| Gigabyte Z390          | 4         | 1.9%    |
| Dell XPS               | 4         | 1.9%    |
| ASUS TUF               | 4         | 1.9%    |
| Packard Bell EasyNote  | 3         | 1.42%   |
| ASUS PRIME             | 3         | 1.42%   |
| Acer Swift             | 3         | 1.42%   |
| Unknown                | 3         | 1.42%   |
| Intel X99              | 2         | 0.95%   |
| HP Stream              | 2         | 0.95%   |
| HP ENVY                | 2         | 0.95%   |
| HP EliteBook           | 2         | 0.95%   |
| Google Kip             | 2         | 0.95%   |
| Dell Vostro            | 2         | 0.95%   |
| Dell OptiPlex          | 2         | 0.95%   |
| ASUS VivoBook          | 2         | 0.95%   |
| ASUS ROG               | 2         | 0.95%   |
| Acer Nitro             | 2         | 0.95%   |
| Valve Jupiter          | 1         | 0.47%   |
| Toshiba TECRA          | 1         | 0.47%   |
| Toshiba PORTEGE        | 1         | 0.47%   |
| Timi TM1701            | 1         | 0.47%   |
| Sony VPCYB15AB         | 1         | 0.47%   |
| Sony VPCF236FM         | 1         | 0.47%   |
| Sony VPCEB1S1E         | 1         | 0.47%   |
| Shuttle XS35V4         | 1         | 0.47%   |
| Samsung R430           | 1         | 0.47%   |
| Samsung 300E5EV        | 1         | 0.47%   |
| Samsung 270E5K         | 1         | 0.47%   |
| Positivo POS-EINM10CB  | 1         | 0.47%   |
| Pegatron IPM31         | 1         | 0.47%   |
| Panasonic CF-C2CCEZXCM | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 32        | 15.17%  |
| 2014 | 20        | 9.48%   |
| 2019 | 18        | 8.53%   |
| 2021 | 15        | 7.11%   |
| 2017 | 15        | 7.11%   |
| 2016 | 15        | 7.11%   |
| 2012 | 15        | 7.11%   |
| 2020 | 13        | 6.16%   |
| 2011 | 12        | 5.69%   |
| 2008 | 12        | 5.69%   |
| 2013 | 9         | 4.27%   |
| 2015 | 8         | 3.79%   |
| 2010 | 8         | 3.79%   |
| 2009 | 6         | 2.84%   |
| 2022 | 5         | 2.37%   |
| 2006 | 4         | 1.9%    |
| 2023 | 2         | 0.95%   |
| 2007 | 2         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 123       | 58.29%  |
| Desktop     | 74        | 35.07%  |
| Convertible | 10        | 4.74%   |
| All in one  | 2         | 0.95%   |
| Tablet      | 1         | 0.47%   |
| Mini pc     | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 205       | 97.16%  |
| Enabled  | 6         | 2.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 206       | 97.63%  |
| Yes  | 5         | 2.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 51        | 23.83%  |
| 3.01-4.0    | 50        | 23.36%  |
| 8.01-16.0   | 41        | 19.16%  |
| 4.01-8.0    | 35        | 16.36%  |
| 32.01-64.0  | 22        | 10.28%  |
| 1.01-2.0    | 6         | 2.8%    |
| 24.01-32.0  | 4         | 1.87%   |
| 2.01-3.0    | 4         | 1.87%   |
| 64.01-256.0 | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 78        | 33.91%  |
| 2.01-3.0   | 61        | 26.52%  |
| 3.01-4.0   | 33        | 14.35%  |
| 4.01-8.0   | 29        | 12.61%  |
| 8.01-16.0  | 14        | 6.09%   |
| 0.51-1.0   | 14        | 6.09%   |
| 16.01-24.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 55.05%  |
| 2      | 62        | 28.44%  |
| 4      | 14        | 6.42%   |
| 3      | 11        | 5.05%   |
| 5      | 7         | 3.21%   |
| 6      | 3         | 1.38%   |
| 7      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 62.62%  |
| Yes       | 80        | 37.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 85.31%  |
| No        | 31        | 14.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 81.13%  |
| No        | 40        | 18.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 66.2%   |
| No        | 72        | 33.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 40        | 18.96%  |
| Brazil       | 14        | 6.64%   |
| Germany      | 13        | 6.16%   |
| Netherlands  | 10        | 4.74%   |
| India        | 10        | 4.74%   |
| Russia       | 9         | 4.27%   |
| France       | 9         | 4.27%   |
| Poland       | 8         | 3.79%   |
| Canada       | 6         | 2.84%   |
| Sweden       | 5         | 2.37%   |
| Spain        | 5         | 2.37%   |
| Australia    | 5         | 2.37%   |
| UK           | 4         | 1.9%    |
| Norway       | 4         | 1.9%    |
| Mexico       | 4         | 1.9%    |
| Turkey       | 3         | 1.42%   |
| Switzerland  | 3         | 1.42%   |
| Romania      | 3         | 1.42%   |
| New Zealand  | 3         | 1.42%   |
| Italy        | 3         | 1.42%   |
| Indonesia    | 3         | 1.42%   |
| Finland      | 3         | 1.42%   |
| Chile        | 3         | 1.42%   |
| Austria      | 3         | 1.42%   |
| Argentina    | 3         | 1.42%   |
| Venezuela    | 2         | 0.95%   |
| Ukraine      | 2         | 0.95%   |
| Saudi Arabia | 2         | 0.95%   |
| Iran         | 2         | 0.95%   |
| Guatemala    | 2         | 0.95%   |
| Greece       | 2         | 0.95%   |
| China        | 2         | 0.95%   |
| Albania      | 2         | 0.95%   |
| Vietnam      | 1         | 0.47%   |
| Thailand     | 1         | 0.47%   |
| Singapore    | 1         | 0.47%   |
| Portugal     | 1         | 0.47%   |
| Philippines  | 1         | 0.47%   |
| Peru         | 1         | 0.47%   |
| Oman         | 1         | 0.47%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Melbourne                 | 4         | 1.77%   |
| Toronto                   | 3         | 1.33%   |
| The Hague                 | 3         | 1.33%   |
| Oslo                      | 3         | 1.33%   |
| Mainz                     | 3         | 1.33%   |
| Constanța                | 3         | 1.33%   |
| Amsterdam                 | 3         | 1.33%   |
| Zurich                    | 2         | 0.88%   |
| Vienna                    | 2         | 0.88%   |
| Stockholm                 | 2         | 0.88%   |
| St Petersburg             | 2         | 0.88%   |
| Severna Park              | 2         | 0.88%   |
| San Justo                 | 2         | 0.88%   |
| San Francisco del Rincón | 2         | 0.88%   |
| New York                  | 2         | 0.88%   |
| Hyderabad                 | 2         | 0.88%   |
| Hrubieszów               | 2         | 0.88%   |
| Guelph                    | 2         | 0.88%   |
| Guatemala City            | 2         | 0.88%   |
| Curitiba                  | 2         | 0.88%   |
| Columbus                  | 2         | 0.88%   |
| Caracas                   | 2         | 0.88%   |
| Beijing                   | 2         | 0.88%   |
| Auckland                  | 2         | 0.88%   |
| Zhytomyr                  | 1         | 0.44%   |
| Yverdon-les-Bains         | 1         | 0.44%   |
| Yekaterinburg             | 1         | 0.44%   |
| Wendell                   | 1         | 0.44%   |
| Weil am Rhein             | 1         | 0.44%   |
| Warrensburg               | 1         | 0.44%   |
| Vineland                  | 1         | 0.44%   |
| Viby J                    | 1         | 0.44%   |
| Vasco da Gama             | 1         | 0.44%   |
| Vancouver                 | 1         | 0.44%   |
| Uppsala                   | 1         | 0.44%   |
| Uberlândia               | 1         | 0.44%   |
| Trondheim                 | 1         | 0.44%   |
| Trabzon                   | 1         | 0.44%   |
| Toluca                    | 1         | 0.44%   |
| Tirana                    | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 51        | 76     | 15.5%   |
| Samsung Electronics          | 49        | 89     | 14.89%  |
| Seagate                      | 37        | 63     | 11.25%  |
| Toshiba                      | 26        | 31     | 7.9%    |
| Kingston                     | 21        | 26     | 6.38%   |
| Unknown                      | 20        | 22     | 6.08%   |
| SanDisk                      | 20        | 26     | 6.08%   |
| Intel                        | 16        | 23     | 4.86%   |
| SK hynix                     | 12        | 13     | 3.65%   |
| Crucial                      | 12        | 15     | 3.65%   |
| Hitachi                      | 7         | 7      | 2.13%   |
| Micron Technology            | 6         | 7      | 1.82%   |
| A-DATA Technology            | 6         | 6      | 1.82%   |
| Silicon Motion               | 3         | 3      | 0.91%   |
| PNY                          | 3         | 3      | 0.91%   |
| Patriot                      | 3         | 5      | 0.91%   |
| Kingston Technology Company  | 3         | 3      | 0.91%   |
| HGST                         | 3         | 3      | 0.91%   |
| China                        | 3         | 3      | 0.91%   |
| Apple                        | 3         | 7      | 0.91%   |
| Phison Electronics           | 2         | 3      | 0.61%   |
| Phison                       | 2         | 2      | 0.61%   |
| Maxtor                       | 2         | 2      | 0.61%   |
| Gigabyte Technology          | 2         | 2      | 0.61%   |
| Transcend                    | 1         | 1      | 0.3%    |
| SPCC Sol                     | 1         | 1      | 0.3%    |
| Shenzhen Longsys Electronics | 1         | 1      | 0.3%    |
| SABRENT                      | 1         | 1      | 0.3%    |
| O2 Micro                     | 1         | 1      | 0.3%    |
| Micron/Crucial Technology    | 1         | 1      | 0.3%    |
| Lenovo                       | 1         | 1      | 0.3%    |
| KIOXIA                       | 1         | 1      | 0.3%    |
| KingFast                     | 1         | 1      | 0.3%    |
| Intenso                      | 1         | 2      | 0.3%    |
| Hypertec                     | 1         | 1      | 0.3%    |
| HFS512GD                     | 1         | 1      | 0.3%    |
| FORESEE                      | 1         | 1      | 0.3%    |
| Emtec                        | 1         | 1      | 0.3%    |
| Corsair                      | 1         | 1      | 0.3%    |
| Advantech                    | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 9         | 2.44%   |
| Samsung NVMe SSD Drive 500GB                        | 7         | 1.9%    |
| Toshiba MQ01ABD100 1TB                              | 6         | 1.63%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 1.63%   |
| Samsung SSD 850 EVO 500GB                           | 5         | 1.36%   |
| Unknown MMC Card  32GB                              | 4         | 1.08%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.08%   |
| Samsung SSD 860 EVO 500GB                           | 4         | 1.08%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 0.81%   |
| Unknown MMC Card  128GB                             | 3         | 0.81%   |
| SK hynix NVMe SSD Drive 128GB                       | 3         | 0.81%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3         | 0.81%   |
| Seagate ST31000528AS 1TB                            | 3         | 0.81%   |
| Seagate ST2000DX002-2DV164 2TB                      | 3         | 0.81%   |
| Seagate ST2000DM006-2DM164 2TB                      | 3         | 0.81%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.81%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.81%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 0.81%   |
| Intel NVMe SSD Drive 256GB                          | 3         | 0.81%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.81%   |
| WDC WD5000AAKS-00A7B0 500GB                         | 2         | 0.54%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 2         | 0.54%   |
| WDC WD20EARX-00PASB0 2TB                            | 2         | 0.54%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 2         | 0.54%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 2         | 0.54%   |
| WDC WD10SPZX-24Z10 1TB                              | 2         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.54%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 2         | 0.54%   |
| WDC WD10EADS-00M2B0 1TB                             | 2         | 0.54%   |
| Unknown TP02000GB 2TB                               | 2         | 0.54%   |
| Toshiba NVMe SSD Drive 256GB                        | 2         | 0.54%   |
| Toshiba DT01ACA100 1TB                              | 2         | 0.54%   |
| Toshiba DT01ACA050 500GB                            | 2         | 0.54%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 0.54%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB             | 2         | 0.54%   |
| Seagate ST31000524AS 1TB                            | 2         | 0.54%   |
| Seagate ST2000DX001-1NS164 2TB                      | 2         | 0.54%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 0.54%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 69     | 38.02%  |
| Seagate             | 37        | 63     | 30.58%  |
| Toshiba             | 18        | 23     | 14.88%  |
| Hitachi             | 7         | 7      | 5.79%   |
| Samsung Electronics | 4         | 6      | 3.31%   |
| HGST                | 3         | 3      | 2.48%   |
| Maxtor              | 2         | 2      | 1.65%   |
| Unknown             | 1         | 1      | 0.83%   |
| SABRENT             | 1         | 1      | 0.83%   |
| Intenso             | 1         | 2      | 0.83%   |
| AAPL                | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 50     | 29.73%  |
| Kingston            | 14        | 17     | 12.61%  |
| SanDisk             | 10        | 14     | 9.01%   |
| Crucial             | 10        | 13     | 9.01%   |
| Micron Technology   | 5         | 6      | 4.5%    |
| Intel               | 4         | 5      | 3.6%    |
| A-DATA Technology   | 4         | 4      | 3.6%    |
| WDC                 | 3         | 3      | 2.7%    |
| SK hynix            | 3         | 4      | 2.7%    |
| PNY                 | 3         | 3      | 2.7%    |
| Patriot             | 3         | 5      | 2.7%    |
| China               | 3         | 3      | 2.7%    |
| Apple               | 3         | 7      | 2.7%    |
| Unknown             | 2         | 2      | 1.8%    |
| Toshiba             | 2         | 2      | 1.8%    |
| Gigabyte Technology | 2         | 2      | 1.8%    |
| Transcend           | 1         | 1      | 0.9%    |
| SPCC Sol            | 1         | 1      | 0.9%    |
| Hypertec            | 1         | 1      | 0.9%    |
| FORESEE             | 1         | 1      | 0.9%    |
| Emtec               | 1         | 1      | 0.9%    |
| Corsair             | 1         | 1      | 0.9%    |
| Advantech           | 1         | 1      | 0.9%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 105       | 178    | 35.47%  |
| SSD     | 95        | 147    | 32.09%  |
| NVMe    | 74        | 108    | 25%     |
| MMC     | 14        | 15     | 4.73%   |
| Unknown | 8         | 10     | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 151       | 311    | 59.45%  |
| NVMe | 74        | 107    | 29.13%  |
| SAS  | 15        | 25     | 5.91%   |
| MMC  | 14        | 15     | 5.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 189    | 57.92%  |
| 0.51-1.0   | 56        | 83     | 27.72%  |
| 1.01-2.0   | 21        | 41     | 10.4%   |
| 3.01-4.0   | 6         | 10     | 2.97%   |
| 10.01-20.0 | 1         | 1      | 0.5%    |
| 4.01-10.0  | 1         | 1      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 72        | 32.88%  |
| 251-500        | 49        | 22.37%  |
| 501-1000       | 37        | 16.89%  |
| 1001-2000      | 17        | 7.76%   |
| 51-100         | 11        | 5.02%   |
| More than 3000 | 9         | 4.11%   |
| 2001-3000      | 9         | 4.11%   |
| 21-50          | 8         | 3.65%   |
| Unknown        | 5         | 2.28%   |
| 1-20           | 2         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 66        | 29.07%  |
| 21-50          | 46        | 20.26%  |
| 101-250        | 30        | 13.22%  |
| 251-500        | 24        | 10.57%  |
| 51-100         | 24        | 10.57%  |
| 1001-2000      | 13        | 5.73%   |
| 501-1000       | 13        | 5.73%   |
| Unknown        | 5         | 2.2%    |
| 2001-3000      | 4         | 1.76%   |
| More than 3000 | 2         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 55.56%  |
| Seagate | 2         | 3      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 160       | 341    | 68.38%  |
| Works    | 62        | 103    | 26.5%   |
| Malfunc  | 12        | 14     | 5.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 142       | 52.99%  |
| AMD                          | 45        | 16.79%  |
| Samsung Electronics          | 22        | 8.21%   |
| Kingston Technology Company  | 10        | 3.73%   |
| SK hynix                     | 9         | 3.36%   |
| SanDisk                      | 9         | 3.36%   |
| Toshiba America Info Systems | 6         | 2.24%   |
| Phison Electronics           | 4         | 1.49%   |
| JMicron Technology           | 4         | 1.49%   |
| Silicon Motion               | 3         | 1.12%   |
| Micron/Crucial Technology    | 3         | 1.12%   |
| Marvell Technology Group     | 2         | 0.75%   |
| ADATA Technology             | 2         | 0.75%   |
| Solidigm                     | 1         | 0.37%   |
| Shenzhen Longsys Electronics | 1         | 0.37%   |
| O2 Micro                     | 1         | 0.37%   |
| Nvidia                       | 1         | 0.37%   |
| Micron Technology            | 1         | 0.37%   |
| Lenovo                       | 1         | 0.37%   |
| ASMedia Technology           | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 11.11%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 5.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 4.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 3.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9         | 2.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 2.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 2.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.61%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 2.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 2.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.63%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.31%   |
| Intel SSD 660P Series                                                          | 4         | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.31%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 3         | 0.98%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 0.98%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.98%   |
| Kingston Company KC2000/KC2500 NVMe SSD [SM2262EN]                             | 3         | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.98%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.65%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.65%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 155       | 58.27%  |
| NVMe | 74        | 27.82%  |
| IDE  | 26        | 9.77%   |
| RAID | 11        | 4.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 161       | 76.3%   |
| AMD    | 50        | 23.7%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 2.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 1.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.42%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.42%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.95%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.95%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.95%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.95%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 0.95%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.95%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.95%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 2         | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.95%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.95%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.95%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 0.95%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.95%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.95%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.95%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.95%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.95%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 0.95%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.95%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 2         | 0.95%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.95%   |
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz           | 1         | 0.47%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.47%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz           | 1         | 0.47%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49        | 23.22%  |
| Intel Core i7           | 39        | 18.48%  |
| AMD Ryzen 7             | 18        | 8.53%   |
| AMD Ryzen 5             | 16        | 7.58%   |
| Intel Celeron           | 15        | 7.11%   |
| Intel Core i3           | 13        | 6.16%   |
| Other                   | 10        | 4.74%   |
| Intel Core 2 Duo        | 7         | 3.32%   |
| Intel Pentium Dual-Core | 6         | 2.84%   |
| Intel Pentium           | 5         | 2.37%   |
| Intel Xeon              | 4         | 1.9%    |
| Intel Core 2 Quad       | 3         | 1.42%   |
| Intel Atom              | 3         | 1.42%   |
| AMD Ryzen 9             | 3         | 1.42%   |
| AMD A10                 | 3         | 1.42%   |
| Intel Pentium Silver    | 2         | 0.95%   |
| Intel Pentium D         | 2         | 0.95%   |
| Intel Core 2            | 2         | 0.95%   |
| AMD Phenom II X4        | 2         | 0.95%   |
| AMD FX                  | 2         | 0.95%   |
| Intel Pentium Dual      | 1         | 0.47%   |
| Intel Core M            | 1         | 0.47%   |
| Intel Core i9           | 1         | 0.47%   |
| AMD Ryzen 3             | 1         | 0.47%   |
| AMD E1                  | 1         | 0.47%   |
| AMD E                   | 1         | 0.47%   |
| AMD A8                  | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 92        | 43.6%   |
| 4      | 76        | 36.02%  |
| 6      | 19        | 9%      |
| 8      | 18        | 8.53%   |
| 10     | 2         | 0.95%   |
| 16     | 1         | 0.47%   |
| 12     | 1         | 0.47%   |
| 3      | 1         | 0.47%   |
| 1      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 211       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 150       | 71.09%  |
| 1      | 61        | 28.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 206       | 97.17%  |
| Unknown        | 6         | 2.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 19.82%  |
| 0x806ea    | 11        | 5.07%   |
| 0x306c3    | 11        | 5.07%   |
| 0x306a9    | 10        | 4.61%   |
| 0x206a7    | 10        | 4.61%   |
| 0x1067a    | 9         | 4.15%   |
| 0x806e9    | 7         | 3.23%   |
| 0x40651    | 6         | 2.76%   |
| 0x906e9    | 5         | 2.3%    |
| 0x806ec    | 5         | 2.3%    |
| 0x506e3    | 5         | 2.3%    |
| 0x20655    | 5         | 2.3%    |
| 0x0a50000c | 5         | 2.3%    |
| 0x08701021 | 5         | 2.3%    |
| 0x906ea    | 4         | 1.84%   |
| 0x806c1    | 4         | 1.84%   |
| 0x706a1    | 4         | 1.84%   |
| 0x406e3    | 4         | 1.84%   |
| 0x0800820d | 4         | 1.84%   |
| 0x306d4    | 3         | 1.38%   |
| 0x30678    | 3         | 1.38%   |
| 0x08701013 | 3         | 1.38%   |
| 0x08600106 | 3         | 1.38%   |
| 0x08108102 | 3         | 1.38%   |
| 0x0810100b | 3         | 1.38%   |
| 0x06003106 | 3         | 1.38%   |
| 0x906ec    | 2         | 0.92%   |
| 0x6fd      | 2         | 0.92%   |
| 0x08108109 | 2         | 0.92%   |
| 0x0800820b | 2         | 0.92%   |
| 0x06000852 | 2         | 0.92%   |
| 0xf64      | 1         | 0.46%   |
| 0xf62      | 1         | 0.46%   |
| 0xa0652    | 1         | 0.46%   |
| 0x906ed    | 1         | 0.46%   |
| 0x906eb    | 1         | 0.46%   |
| 0x906c0    | 1         | 0.46%   |
| 0x806eb    | 1         | 0.46%   |
| 0x706a8    | 1         | 0.46%   |
| 0x6f2      | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 19.91%  |
| Haswell          | 20        | 9.48%   |
| Penryn           | 16        | 7.58%   |
| SandyBridge      | 13        | 6.16%   |
| Zen 2            | 12        | 5.69%   |
| Skylake          | 12        | 5.69%   |
| IvyBridge        | 11        | 5.21%   |
| Zen+             | 10        | 4.74%   |
| Zen 3            | 9         | 4.27%   |
| Westmere         | 7         | 3.32%   |
| TigerLake        | 7         | 3.32%   |
| Silvermont       | 7         | 3.32%   |
| Core             | 6         | 2.84%   |
| Broadwell        | 6         | 2.84%   |
| Goldmont plus    | 5         | 2.37%   |
| Zen              | 4         | 1.9%    |
| Unknown          | 4         | 1.9%    |
| Steamroller      | 3         | 1.42%   |
| Piledriver       | 3         | 1.42%   |
| Tremont          | 2         | 0.95%   |
| NetBurst         | 2         | 0.95%   |
| K10              | 2         | 0.95%   |
| Bobcat           | 2         | 0.95%   |
| IceLake          | 1         | 0.47%   |
| Goldmont         | 1         | 0.47%   |
| Excavator        | 1         | 0.47%   |
| CometLake        | 1         | 0.47%   |
| Bonnell          | 1         | 0.47%   |
| Alderlake Hybrid | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 125       | 49.21%  |
| Nvidia | 66        | 25.98%  |
| AMD    | 63        | 24.8%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 12        | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 9         | 3.46%   |
| Intel HD Graphics 620                                                     | 8         | 3.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 7         | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 7         | 2.69%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 2.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 5         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 5         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 5         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                       | 4         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 1.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 4         | 1.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 4         | 1.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 4         | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 3         | 1.15%   |
| Nvidia GM108M [GeForce 940MX]                                             | 3         | 1.15%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 3         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 1.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 1.15%   |
| Intel HD Graphics 630                                                     | 3         | 1.15%   |
| Intel HD Graphics 5500                                                    | 3         | 1.15%   |
| Intel HD Graphics 530                                                     | 3         | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 1.15%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 3         | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.15%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 0.77%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 2         | 0.77%   |
| Nvidia GM108M [GeForce 930MX]                                             | 2         | 0.77%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 2         | 0.77%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 41.59%  |
| 1 x AMD        | 52        | 24.3%   |
| 1 x Nvidia     | 34        | 15.89%  |
| Intel + Nvidia | 27        | 12.62%  |
| Intel + AMD    | 6         | 2.8%    |
| AMD + Nvidia   | 6         | 2.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 169       | 79.72%  |
| Proprietary | 43        | 20.28%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 44.91%  |
| 1.01-2.0   | 33        | 15.28%  |
| 0.51-1.0   | 25        | 11.57%  |
| 0.01-0.5   | 15        | 6.94%   |
| 3.01-4.0   | 14        | 6.48%   |
| 7.01-8.0   | 12        | 5.56%   |
| 5.01-6.0   | 12        | 5.56%   |
| 8.01-16.0  | 5         | 2.31%   |
| 2.01-3.0   | 3         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 31        | 12.6%   |
| AU Optronics            | 30        | 12.2%   |
| BOE                     | 25        | 10.16%  |
| LG Display              | 20        | 8.13%   |
| Goldstar                | 18        | 7.32%   |
| Chimei Innolux          | 16        | 6.5%    |
| AOC                     | 13        | 5.28%   |
| Dell                    | 11        | 4.47%   |
| Ancor Communications    | 9         | 3.66%   |
| Lenovo                  | 8         | 3.25%   |
| BenQ                    | 7         | 2.85%   |
| Apple                   | 6         | 2.44%   |
| Acer                    | 5         | 2.03%   |
| Sharp                   | 4         | 1.63%   |
| LG Electronics          | 4         | 1.63%   |
| Philips                 | 3         | 1.22%   |
| Hewlett-Packard         | 3         | 1.22%   |
| Chi Mei Optoelectronics | 3         | 1.22%   |
| ASUSTek Computer        | 3         | 1.22%   |
| Unknown                 | 2         | 0.81%   |
| PANDA                   | 2         | 0.81%   |
| NEC Computers           | 2         | 0.81%   |
| LG Philips              | 2         | 0.81%   |
| Iiyama                  | 2         | 0.81%   |
| CSO                     | 2         | 0.81%   |
| Unknown                 | 2         | 0.81%   |
| ___                     | 1         | 0.41%   |
| ViewSonic               | 1         | 0.41%   |
| Valve                   | 1         | 0.41%   |
| Toshiba                 | 1         | 0.41%   |
| Sony                    | 1         | 0.41%   |
| Positivo                | 1         | 0.41%   |
| MStar                   | 1         | 0.41%   |
| MSI                     | 1         | 0.41%   |
| Microstep               | 1         | 0.41%   |
| Mi                      | 1         | 0.41%   |
| JRY                     | 1         | 0.41%   |
| GKK                     | 1         | 0.41%   |
| CPT                     | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 3         | 1.19%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 2         | 0.79%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 2         | 0.79%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch              | 2         | 0.79%   |
| Goldstar L227W GSM566E 1680x1050 474x296mm 22.0-inch                 | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch     | 2         | 0.79%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                | 2         | 0.79%   |
| BOE LCD Monitor BOE0638 1920x1080 309x173mm 13.9-inch                | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.79%   |
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 2         | 0.79%   |
| Ancor Communications LCD Monitor MG248 1920x1080                     | 2         | 0.79%   |
| Unknown                                                              | 2         | 0.79%   |
| ___ LCD TV ___9000 1360x768                                          | 1         | 0.4%    |
| ViewSonic VP191b VSC0E11 1280x1024 376x301mm 19.0-inch               | 1         | 0.4%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.4%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.4%    |
| Unknown LCD Monitor HIC 3200x1080                                    | 1         | 0.4%    |
| Toshiba Internal LCD TOS5091 1366x768 309x174mm 14.0-inch            | 1         | 0.4%    |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                | 1         | 0.4%    |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 1         | 0.4%    |
| Sharp LCD Monitor HDMI 1920x1080                                     | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM029A 1920x1200 582x364mm 27.0-inch | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 1         | 0.4%    |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch  | 1         | 0.4%    |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 0.4%    |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch   | 1         | 0.4%    |
| Samsung Electronics S27D590C SAM0BEA 1920x1080 598x336mm 27.0-inch   | 1         | 0.4%    |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch    | 1         | 0.4%    |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1         | 0.4%    |
| Samsung Electronics S19C200 SAM09B3 1440x900 408x255mm 18.9-inch     | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SM2333TN 1920x1080                   | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 100       | 42.74%  |
| 1366x768 (WXGA)    | 44        | 18.8%   |
| 1600x900 (HD+)     | 11        | 4.7%    |
| 2560x1440 (QHD)    | 10        | 4.27%   |
| 3840x2160 (4K)     | 8         | 3.42%   |
| 1440x900 (WXGA+)   | 8         | 3.42%   |
| 1280x1024 (SXGA)   | 7         | 2.99%   |
| 1920x1200 (WUXGA)  | 6         | 2.56%   |
| 1680x1050 (WSXGA+) | 6         | 2.56%   |
| 1280x800 (WXGA)    | 6         | 2.56%   |
| Unknown            | 6         | 2.56%   |
| 2560x1080          | 4         | 1.71%   |
| 3840x1080          | 3         | 1.28%   |
| 1360x768           | 3         | 1.28%   |
| 2560x1600          | 2         | 0.85%   |
| 800x1280           | 1         | 0.43%   |
| 5760x1080          | 1         | 0.43%   |
| 4480x1440          | 1         | 0.43%   |
| 3440x1440          | 1         | 0.43%   |
| 3200x1080          | 1         | 0.43%   |
| 3000x2000          | 1         | 0.43%   |
| 2880x1620          | 1         | 0.43%   |
| 2256x1504          | 1         | 0.43%   |
| 1152x864           | 1         | 0.43%   |
| 1024x768 (XGA)     | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 66        | 27.73%  |
| 13      | 31        | 13.03%  |
| Unknown | 21        | 8.82%   |
| 14      | 19        | 7.98%   |
| 24      | 16        | 6.72%   |
| 27      | 12        | 5.04%   |
| 17      | 11        | 4.62%   |
| 23      | 10        | 4.2%    |
| 21      | 10        | 4.2%    |
| 18      | 8         | 3.36%   |
| 22      | 4         | 1.68%   |
| 20      | 4         | 1.68%   |
| 19      | 4         | 1.68%   |
| 40      | 3         | 1.26%   |
| 34      | 3         | 1.26%   |
| 31      | 3         | 1.26%   |
| 11      | 3         | 1.26%   |
| 16      | 2         | 0.84%   |
| 12      | 2         | 0.84%   |
| 72      | 1         | 0.42%   |
| 52      | 1         | 0.42%   |
| 49      | 1         | 0.42%   |
| 29      | 1         | 0.42%   |
| 25      | 1         | 0.42%   |
| 7       | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 42.98%  |
| 501-600     | 36        | 15.32%  |
| 401-500     | 29        | 12.34%  |
| Unknown     | 21        | 8.94%   |
| 201-300     | 20        | 8.51%   |
| 351-400     | 14        | 5.96%   |
| 601-700     | 4         | 1.7%    |
| 801-900     | 3         | 1.28%   |
| 701-800     | 3         | 1.28%   |
| 1001-1500   | 2         | 0.85%   |
| 1501-2000   | 1         | 0.43%   |
| 1-100       | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 153       | 69.86%  |
| 16/10   | 29        | 13.24%  |
| Unknown | 20        | 9.13%   |
| 5/4     | 4         | 1.83%   |
| 3/2     | 4         | 1.83%   |
| 21/9    | 4         | 1.83%   |
| 4/3     | 2         | 0.91%   |
| 6/5     | 1         | 0.46%   |
| 32/9    | 1         | 0.46%   |
| 0.67    | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 64        | 26.89%  |
| 81-90          | 40        | 16.81%  |
| 201-250        | 32        | 13.45%  |
| Unknown        | 21        | 8.82%   |
| 301-350        | 13        | 5.46%   |
| 151-200        | 12        | 5.04%   |
| 71-80          | 10        | 4.2%    |
| 141-150        | 9         | 3.78%   |
| 121-130        | 8         | 3.36%   |
| 251-300        | 7         | 2.94%   |
| 351-500        | 6         | 2.52%   |
| 501-1000       | 4         | 1.68%   |
| 51-60          | 3         | 1.26%   |
| 111-120        | 3         | 1.26%   |
| More than 1000 | 2         | 0.84%   |
| 61-70          | 2         | 0.84%   |
| 1-40           | 1         | 0.42%   |
| 91-100         | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 70        | 30.3%   |
| 121-160       | 64        | 27.71%  |
| 101-120       | 52        | 22.51%  |
| Unknown       | 21        | 9.09%   |
| 161-240       | 16        | 6.93%   |
| More than 240 | 5         | 2.16%   |
| 1-50          | 3         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 170       | 79.44%  |
| 2     | 40        | 18.69%  |
| 3     | 3         | 1.4%    |
| 0     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 113       | 34.04%  |
| Intel                           | 99        | 29.82%  |
| Qualcomm Atheros                | 44        | 13.25%  |
| Broadcom                        | 20        | 6.02%   |
| MediaTek                        | 7         | 2.11%   |
| Marvell Technology Group        | 7         | 2.11%   |
| TP-Link                         | 4         | 1.2%    |
| Ralink Technology               | 4         | 1.2%    |
| Xiaomi                          | 3         | 0.9%    |
| Ralink                          | 3         | 0.9%    |
| Broadcom Limited                | 3         | 0.9%    |
| Dell                            | 2         | 0.6%    |
| ASIX Electronics                | 2         | 0.6%    |
| ZTE WCDMA Technologies MSM      | 1         | 0.3%    |
| T & A Mobile Phones             | 1         | 0.3%    |
| Sierra Wireless                 | 1         | 0.3%    |
| Samsung Electronics             | 1         | 0.3%    |
| Qualcomm Atheros Communications | 1         | 0.3%    |
| Qualcomm                        | 1         | 0.3%    |
| OnePlus Technology (Shenzhen)   | 1         | 0.3%    |
| Nvidia                          | 1         | 0.3%    |
| NetGear                         | 1         | 0.3%    |
| Microchip Technology            | 1         | 0.3%    |
| Linksys                         | 1         | 0.3%    |
| Lenovo                          | 1         | 0.3%    |
| LeEco                           | 1         | 0.3%    |
| Jolla Oy                        | 1         | 0.3%    |
| Huawei Technologies             | 1         | 0.3%    |
| Hewlett-Packard                 | 1         | 0.3%    |
| Google                          | 1         | 0.3%    |
| DisplayLink                     | 1         | 0.3%    |
| D-Link System                   | 1         | 0.3%    |
| Belkin Components               | 1         | 0.3%    |
| Aquantia                        | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 80        | 20.57%  |
| Intel Wireless 8265 / 8275                                             | 11        | 2.83%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 10        | 2.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 2.31%   |
| Intel I211 Gigabit Network Connection                                  | 9         | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 2.06%   |
| Intel Wireless 7265                                                    | 7         | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 1.54%   |
| Intel Wireless 7260                                                    | 6         | 1.54%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.29%   |
| Intel Wireless 3165                                                    | 5         | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.03%   |
| Intel Wireless 8260                                                    | 4         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.77%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 0.77%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 0.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 2         | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2         | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 2         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.51%   |
| Realtek RTL8187 Wireless Adapter                                       | 2         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.51%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.51%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.51%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 44.09%  |
| Qualcomm Atheros                | 38        | 20.43%  |
| Realtek Semiconductor           | 25        | 13.44%  |
| Broadcom                        | 14        | 7.53%   |
| MediaTek                        | 6         | 3.23%   |
| Ralink Technology               | 4         | 2.15%   |
| TP-Link                         | 3         | 1.61%   |
| Ralink                          | 3         | 1.61%   |
| Broadcom Limited                | 3         | 1.61%   |
| Sierra Wireless                 | 1         | 0.54%   |
| Qualcomm Atheros Communications | 1         | 0.54%   |
| NetGear                         | 1         | 0.54%   |
| Linksys                         | 1         | 0.54%   |
| Hewlett-Packard                 | 1         | 0.54%   |
| Dell                            | 1         | 0.54%   |
| D-Link System                   | 1         | 0.54%   |
| Belkin Components               | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 11        | 5.82%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 5.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 5.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 4.23%   |
| Intel Wireless 7265                                            | 7         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.17%   |
| Intel Wireless 7260                                            | 6         | 3.17%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 3.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 2.65%   |
| Intel Wireless 3165                                            | 5         | 2.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 2.12%   |
| Intel Wireless 8260                                            | 4         | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.06%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.06%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 1.06%   |
| Realtek 802.11ac NIC                                           | 2         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 1.06%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 1.06%   |
| Qualcomm Atheros AR922X Wireless Network Adapter               | 2         | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 1.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 1.06%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 1.06%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 1.06%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.06%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.06%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 1.06%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 1.06%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.06%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.53%   |
| Sierra Wireless EM7305                                         | 1         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 102       | 52.85%  |
| Intel                      | 49        | 25.39%  |
| Qualcomm Atheros           | 9         | 4.66%   |
| Broadcom                   | 8         | 4.15%   |
| Marvell Technology Group   | 7         | 3.63%   |
| Xiaomi                     | 3         | 1.55%   |
| ASIX Electronics           | 2         | 1.04%   |
| ZTE WCDMA Technologies MSM | 1         | 0.52%   |
| TP-Link                    | 1         | 0.52%   |
| T & A Mobile Phones        | 1         | 0.52%   |
| Qualcomm                   | 1         | 0.52%   |
| Nvidia                     | 1         | 0.52%   |
| MediaTek                   | 1         | 0.52%   |
| Lenovo                     | 1         | 0.52%   |
| LeEco                      | 1         | 0.52%   |
| Jolla Oy                   | 1         | 0.52%   |
| Huawei Technologies        | 1         | 0.52%   |
| Google                     | 1         | 0.52%   |
| DisplayLink                | 1         | 0.52%   |
| Aquantia                   | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 80        | 40.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 4.59%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 2.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.53%   |
| Realtek Killer E2600 GbE Controller                                            | 3         | 1.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 1.53%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.53%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.02%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 1.02%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.02%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.02%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.02%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.02%   |
| ZTE WCDMA MSM Yota Router                                                      | 1         | 0.51%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.51%   |
| T & A Mobile Phones TCL 30 Z                                                   | 1         | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.51%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1         | 0.51%   |
| Qualcomm POCO F3                                                               | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.51%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.51%   |
| Lenovo Thinkpad LAN                                                            | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 180       | 50.56%  |
| WiFi     | 172       | 48.31%  |
| Modem    | 3         | 0.84%   |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 61.82%  |
| Ethernet | 84        | 38.18%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 121       | 56.81%  |
| 1     | 86        | 40.38%  |
| 3     | 4         | 1.88%   |
| 0     | 2         | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 176       | 81.86%  |
| Yes  | 39        | 18.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 46.53%  |
| Qualcomm Atheros Communications | 13        | 9.03%   |
| Cambridge Silicon Radio         | 11        | 7.64%   |
| Lite-On Technology              | 10        | 6.94%   |
| Realtek Semiconductor           | 8         | 5.56%   |
| Broadcom                        | 8         | 5.56%   |
| Apple                           | 7         | 4.86%   |
| IMC Networks                    | 5         | 3.47%   |
| Foxconn / Hon Hai               | 3         | 2.08%   |
| Toshiba                         | 2         | 1.39%   |
| MediaTek                        | 2         | 1.39%   |
| Hewlett-Packard                 | 2         | 1.39%   |
| Dell                            | 2         | 1.39%   |
| ASUSTek Computer                | 2         | 1.39%   |
| SiW                             | 1         | 0.69%   |
| Ralink                          | 1         | 0.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 33        | 22.76%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 7.59%   |
| Intel AX201 Bluetooth                                                               | 10        | 6.9%    |
| Intel AX200 Bluetooth                                                               | 10        | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 4.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.76%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.07%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.07%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.07%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.07%   |
| Toshiba RT Bluetooth Radio                                                          | 2         | 1.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.38%   |
| MediaTek Wireless_Device                                                            | 2         | 1.38%   |
| Lite-On Wireless_Device                                                             | 2         | 1.38%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.38%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.38%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.38%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.38%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.38%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.38%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.38%   |
| SiW SiW                                                                             | 1         | 0.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.69%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.69%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.69%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.69%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.69%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.69%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.69%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.69%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.69%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 156       | 52.35%  |
| AMD                     | 66        | 22.15%  |
| Nvidia                  | 46        | 15.44%  |
| Blue Microphones        | 4         | 1.34%   |
| C-Media Electronics     | 3         | 1.01%   |
| Texas Instruments       | 2         | 0.67%   |
| Logitech                | 2         | 0.67%   |
| JMTek                   | 2         | 0.67%   |
| Conexant Systems        | 2         | 0.67%   |
| Yamaha                  | 1         | 0.34%   |
| Tenx Technology         | 1         | 0.34%   |
| SteelSeries ApS         | 1         | 0.34%   |
| SmartlinkTechnology     | 1         | 0.34%   |
| SAVITECH                | 1         | 0.34%   |
| Samsung Electronics     | 1         | 0.34%   |
| RME                     | 1         | 0.34%   |
| Raspberry Pi            | 1         | 0.34%   |
| Mark of the Unicorn     | 1         | 0.34%   |
| GYROCOM C&C             | 1         | 0.34%   |
| Creative Technology     | 1         | 0.34%   |
| Creative Labs           | 1         | 0.34%   |
| Cooler Master           | 1         | 0.34%   |
| BEHRINGER International | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 25        | 7.02%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 21        | 5.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 3.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 3.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 2.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 8         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 2.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.97%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.4%    |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.4%    |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.4%    |
| AMD FCH Azalia Controller                                                  | 5         | 1.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.84%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.84%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3         | 0.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 0.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 23.66%  |
| SK hynix            | 12        | 12.9%   |
| Unknown             | 10        | 10.75%  |
| Kingston            | 8         | 8.6%    |
| Crucial             | 8         | 8.6%    |
| Corsair             | 7         | 7.53%   |
| A-DATA Technology   | 7         | 7.53%   |
| Micron Technology   | 6         | 6.45%   |
| Nanya Technology    | 3         | 3.23%   |
| Ramaxel Technology  | 2         | 2.15%   |
| G.Skill             | 2         | 2.15%   |
| Elpida              | 2         | 2.15%   |
| Transcend           | 1         | 1.08%   |
| Team                | 1         | 1.08%   |
| Patriot             | 1         | 1.08%   |
| ChangXin Memory     | 1         | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 2         | 2%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s               | 2         | 2%      |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 2         | 2%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s               | 2         | 2%      |
| Unknown RAM Module 8192MB SODIMM DDR3 1867MT/s                      | 1         | 1%      |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 1%      |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1%      |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1%      |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 1%      |
| Unknown RAM Module 4096MB DIMM DDR3 1066MT/s                        | 1         | 1%      |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 1%      |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                        | 1         | 1%      |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 1%      |
| Unknown RAM Module 1GB DIMM 667MT/s                                 | 1         | 1%      |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s                  | 1         | 1%      |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s                   | 1         | 1%      |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 1%      |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                      | 1         | 1%      |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s              | 1         | 1%      |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1%      |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 1%      |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 1%      |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1%      |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1%      |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 1%      |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 1         | 1%      |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 1%      |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1%      |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1%      |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 1         | 1%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 1%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1%      |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1%      |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1%      |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1%      |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 51.85%  |
| DDR3    | 26        | 32.1%   |
| LPDDR3  | 5         | 6.17%   |
| SDRAM   | 2         | 2.47%   |
| LPDDR4  | 2         | 2.47%   |
| DDR2    | 2         | 2.47%   |
| DDR     | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 67.95%  |
| DIMM         | 19        | 24.36%  |
| Row Of Chips | 6         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 39.77%  |
| 4096  | 25        | 28.41%  |
| 16384 | 13        | 14.77%  |
| 2048  | 9         | 10.23%  |
| 32768 | 3         | 3.41%   |
| 1024  | 3         | 3.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 18        | 20.22%  |
| 2667    | 13        | 14.61%  |
| 3200    | 12        | 13.48%  |
| 2400    | 11        | 12.36%  |
| 2133    | 7         | 7.87%   |
| 3600    | 3         | 3.37%   |
| 1867    | 3         | 3.37%   |
| Unknown | 3         | 3.37%   |
| 3733    | 2         | 2.25%   |
| 1334    | 2         | 2.25%   |
| 1333    | 2         | 2.25%   |
| 667     | 2         | 2.25%   |
| 4267    | 1         | 1.12%   |
| 3866    | 1         | 1.12%   |
| 3400    | 1         | 1.12%   |
| 3266    | 1         | 1.12%   |
| 3000    | 1         | 1.12%   |
| 2048    | 1         | 1.12%   |
| 1866    | 1         | 1.12%   |
| 1800    | 1         | 1.12%   |
| 1067    | 1         | 1.12%   |
| 1066    | 1         | 1.12%   |
| 800     | 1         | 1.12%   |

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
| Chicony Electronics                    | 29        | 20.42%  |
| Realtek Semiconductor                  | 14        | 9.86%   |
| Microdia                               | 13        | 9.15%   |
| IMC Networks                           | 13        | 9.15%   |
| Logitech                               | 11        | 7.75%   |
| Quanta                                 | 7         | 4.93%   |
| Sunplus Innovation Technology          | 6         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.23%   |
| Syntek                                 | 5         | 3.52%   |
| Suyin                                  | 5         | 3.52%   |
| Lite-On Technology                     | 5         | 3.52%   |
| Bison Electronics                      | 5         | 3.52%   |
| Apple                                  | 4         | 2.82%   |
| Microsoft                              | 3         | 2.11%   |
| Lenovo                                 | 2         | 1.41%   |
| Importek                               | 2         | 1.41%   |
| Z-Star Microelectronics                | 1         | 0.7%    |
| Unknown                                | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Samsung Electronics                    | 1         | 0.7%    |
| Ricoh                                  | 1         | 0.7%    |
| MacroSilicon                           | 1         | 0.7%    |
| Luxvisions Innotech Limited            | 1         | 0.7%    |
| LG Electronics                         | 1         | 0.7%    |
| Intel                                  | 1         | 0.7%    |
| Hewlett-Packard                        | 1         | 0.7%    |
| Acer                                   | 1         | 0.7%    |
| A4Tech                                 | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 7         | 4.86%   |
| IMC Networks USB2.0 HD UVC WebCam             | 6         | 4.17%   |
| Chicony Integrated Camera                     | 6         | 4.17%   |
| Syntek Integrated Camera                      | 4         | 2.78%   |
| Sunplus Integrated_Webcam_HD                  | 4         | 2.78%   |
| Microdia Integrated_Webcam_HD                 | 4         | 2.78%   |
| Logitech HD Pro Webcam C920                   | 4         | 2.78%   |
| Realtek Integrated Webcam_HD                  | 3         | 2.08%   |
| Realtek HD WebCam                             | 3         | 2.08%   |
| IMC Networks Integrated Camera                | 3         | 2.08%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 1.39%   |
| Realtek Integrated_Webcam_HD                  | 2         | 1.39%   |
| Quanta HP TrueVision HD Webcam                | 2         | 1.39%   |
| Quanta HD User Facing                         | 2         | 1.39%   |
| Microdia USB 2.0 Camera                       | 2         | 1.39%   |
| Microdia Camera                               | 2         | 1.39%   |
| Logitech Webcam C270                          | 2         | 1.39%   |
| Logitech Logitech Webcam C160                 | 2         | 1.39%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 1.39%   |
| Chicony VGA WebCam                            | 2         | 1.39%   |
| Chicony HP Truevision HD camera               | 2         | 1.39%   |
| Chicony EasyCamera                            | 2         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 1.39%   |
| Apple FaceTime HD Camera (Built-in)           | 2         | 1.39%   |
| Z-Star Webcam                                 | 1         | 0.69%   |
| Unknown ATIV VGA CAMERA                       | 1         | 0.69%   |
| Syntek USB2.0 Camera                          | 1         | 0.69%   |
| Suyin HP TrueVision FHD RGB-IR                | 1         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 0.69%   |
| Suyin 1.3M HD WebCam                          | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.69%   |
| Sunplus Laptop Integrated WebCam HD           | 1         | 0.69%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.69%   |
| Samsung Galaxy series, misc. (MTP mode)       | 1         | 0.69%   |
| Ricoh USB2.0 Camera                           | 1         | 0.69%   |
| Realtek Laptop Camera                         | 1         | 0.69%   |
| Realtek Integrated Webcam HD                  | 1         | 0.69%   |
| Realtek Integrated Webcam                     | 1         | 0.69%   |
| Realtek Integrated Camera                     | 1         | 0.69%   |
| Realtek HP Truevision HD                      | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 35.48%  |
| Synaptics                  | 5         | 16.13%  |
| Shenzhen Goodix Technology | 4         | 12.9%   |
| Elan Microelectronics      | 3         | 9.68%   |
| AuthenTec                  | 3         | 9.68%   |
| Upek                       | 2         | 6.45%   |
| LighTuning Technology      | 2         | 6.45%   |
| Focal-systems.Corp         | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 12.9%   |
| Elan ELAN:Fingerprint                                  | 3         | 9.68%   |
| Validity Sensors Fingerprint scanner                   | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 6.45%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 6.45%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 6.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 6.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.23%   |
| Validity Sensors VFS491                                | 1         | 3.23%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 3.23%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.23%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.23%   |
| Synaptics WBDI                                         | 1         | 3.23%   |
| Synaptics  WBDI                                        | 1         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 3.23%   |
| Focal-systems.Corp FT9201Fingerprint.Ì              | 1         | 3.23%   |
| AuthenTec Fingerprint Sensor                           | 1         | 3.23%   |
| AuthenTec AES2810                                      | 1         | 3.23%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 30.77%  |
| Alcor Micro | 3         | 23.08%  |
| Upek        | 2         | 15.38%  |
| O2 Micro    | 1         | 7.69%   |
| Lenovo      | 1         | 7.69%   |
| Bit4id      | 1         | 7.69%   |
| Aktiv       | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 23.08%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 7.69%   |
| Broadcom 5880                                              | 1         | 7.69%   |
| Bit4id miniLector EVO                                      | 1         | 7.69%   |
| Aktiv Rutoken lite                                         | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 148       | 68.84%  |
| 1     | 47        | 21.86%  |
| 2     | 19        | 8.84%   |
| 3     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 34.83%  |
| Net/wireless             | 21        | 23.6%   |
| Chipcard                 | 12        | 13.48%  |
| Multimedia controller    | 9         | 10.11%  |
| Graphics card            | 6         | 6.74%   |
| Unassigned class         | 2         | 2.25%   |
| Camera                   | 2         | 2.25%   |
| Tv card                  | 1         | 1.12%   |
| Storage                  | 1         | 1.12%   |
| Network                  | 1         | 1.12%   |
| Net/ethernet             | 1         | 1.12%   |
| Communication controller | 1         | 1.12%   |
| Bluetooth                | 1         | 1.12%   |


Lubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_22.04/Notebook/README.md).

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

Total: 696

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0N4YC8 A00                  | Desktop     | [f722edf7a9](https://linux-hardware.org/?probe=f722edf7a9) | Jan 01, 2025 |
| Medion        | S6421 MD60703               | Notebook    | [609c73a176](https://linux-hardware.org/?probe=609c73a176) | Dec 19, 2024 |
| HP            | 2000                        | Notebook    | [3c20e6e18c](https://linux-hardware.org/?probe=3c20e6e18c) | Dec 11, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [cbf6bf1b48](https://linux-hardware.org/?probe=cbf6bf1b48) | Dec 06, 2024 |
| MSI           | H410M BOMBER                | Desktop     | [0fdf3b3e0b](https://linux-hardware.org/?probe=0fdf3b3e0b) | Nov 21, 2024 |
| MSI           | H410M BOMBER                | Desktop     | [97ed06f147](https://linux-hardware.org/?probe=97ed06f147) | Nov 21, 2024 |
| ASUSTek       | PRIME H510M-E R2.0          | Desktop     | [98d4a70c46](https://linux-hardware.org/?probe=98d4a70c46) | Nov 20, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [ba64567726](https://linux-hardware.org/?probe=ba64567726) | Nov 18, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [815225e627](https://linux-hardware.org/?probe=815225e627) | Nov 18, 2024 |
| Medion        | E3215 MD60929               | Convertible | [4445d09a20](https://linux-hardware.org/?probe=4445d09a20) | Nov 17, 2024 |
| Supermicro    | X8DTT-H                     | Server      | [05f8ebdf95](https://linux-hardware.org/?probe=05f8ebdf95) | Nov 06, 2024 |
| Dell          | Latitude E7240              | Notebook    | [82e1ee846b](https://linux-hardware.org/?probe=82e1ee846b) | Nov 02, 2024 |
| Intel         | H61                         | Desktop     | [0e1936ef18](https://linux-hardware.org/?probe=0e1936ef18) | Oct 31, 2024 |
| Lenovo        | ThinkPad E15 20RD005VRT     | Notebook    | [0faadd1106](https://linux-hardware.org/?probe=0faadd1106) | Oct 24, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [53c668190f](https://linux-hardware.org/?probe=53c668190f) | Oct 23, 2024 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [df61da6a87](https://linux-hardware.org/?probe=df61da6a87) | Oct 22, 2024 |
| Medion        | S6421 MD60703               | Notebook    | [c92c3514b3](https://linux-hardware.org/?probe=c92c3514b3) | Oct 22, 2024 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fb9c9f4215](https://linux-hardware.org/?probe=fb9c9f4215) | Oct 06, 2024 |
| Dell          | Vostro 1500                 | Notebook    | [6680201494](https://linux-hardware.org/?probe=6680201494) | Oct 06, 2024 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [3fefc80707](https://linux-hardware.org/?probe=3fefc80707) | Oct 05, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [582f0a4f04](https://linux-hardware.org/?probe=582f0a4f04) | Oct 04, 2024 |
| MSI           | MS-B0621 100                | All in one  | [3d6c67056e](https://linux-hardware.org/?probe=3d6c67056e) | Oct 04, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [1faf24f4b7](https://linux-hardware.org/?probe=1faf24f4b7) | Oct 01, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [1ce63743fd](https://linux-hardware.org/?probe=1ce63743fd) | Oct 01, 2024 |
| Lenovo        | ThinkPad T480s 20L8S3SW0... | Notebook    | [d3f2558562](https://linux-hardware.org/?probe=d3f2558562) | Sep 28, 2024 |
| Gateway       | IPISB-VR                    | Desktop     | [bc45b7939c](https://linux-hardware.org/?probe=bc45b7939c) | Sep 23, 2024 |
| Dell          | Latitude E6410              | Notebook    | [92cd0e0eee](https://linux-hardware.org/?probe=92cd0e0eee) | Sep 17, 2024 |
| Dell          | Latitude E6410              | Notebook    | [d9385745e8](https://linux-hardware.org/?probe=d9385745e8) | Sep 17, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [a5aeb5f264](https://linux-hardware.org/?probe=a5aeb5f264) | Sep 10, 2024 |
| Samsung       | RV415                       | Notebook    | [e3d0816997](https://linux-hardware.org/?probe=e3d0816997) | Sep 07, 2024 |
| Fujitsu Si... | D2151-A2 S26361-D2151-A2    | Desktop     | [d15a8e878e](https://linux-hardware.org/?probe=d15a8e878e) | Sep 06, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [70ad6eb824](https://linux-hardware.org/?probe=70ad6eb824) | Sep 03, 2024 |
| Dell          | Latitude 5285               | Notebook    | [ece411e4e4](https://linux-hardware.org/?probe=ece411e4e4) | Aug 27, 2024 |
| Dell          | 0HY9JP A00                  | Desktop     | [dae885b643](https://linux-hardware.org/?probe=dae885b643) | Aug 25, 2024 |
| HP            | Pavilion dv6                | Notebook    | [8745b6a8a6](https://linux-hardware.org/?probe=8745b6a8a6) | Aug 22, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [5d217cd410](https://linux-hardware.org/?probe=5d217cd410) | Aug 22, 2024 |
| HP            | Compaq Presario CQ60        | Notebook    | [d0e97b8772](https://linux-hardware.org/?probe=d0e97b8772) | Aug 13, 2024 |
| SK hynix      | HT14CCIC42E                 | Notebook    | [eb41114fc3](https://linux-hardware.org/?probe=eb41114fc3) | Aug 10, 2024 |
| Acer          | Aspire 5715Z                | Notebook    | [32b3360c63](https://linux-hardware.org/?probe=32b3360c63) | Aug 07, 2024 |
| Acer          | Aspire 5715Z                | Notebook    | [387c8e5fe4](https://linux-hardware.org/?probe=387c8e5fe4) | Aug 07, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [ef1df870ea](https://linux-hardware.org/?probe=ef1df870ea) | Aug 07, 2024 |
| Dell          | 0V8DVD A00                  | All in one  | [6ac88acf00](https://linux-hardware.org/?probe=6ac88acf00) | Aug 06, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [c390f98098](https://linux-hardware.org/?probe=c390f98098) | Aug 03, 2024 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f5fb19db6b](https://linux-hardware.org/?probe=f5fb19db6b) | Jul 27, 2024 |
| HP            | Pavilion x2 Detachable      | Notebook    | [8f6ba78b79](https://linux-hardware.org/?probe=8f6ba78b79) | Jul 25, 2024 |
| HP            | 2AF7                        | Desktop     | [d00c713358](https://linux-hardware.org/?probe=d00c713358) | Jul 23, 2024 |
| Acer          | Aspire A515-57G             | Notebook    | [e7fba30a89](https://linux-hardware.org/?probe=e7fba30a89) | Jul 23, 2024 |
| Dell          | 0MN1TX A01                  | Desktop     | [99e899cbb0](https://linux-hardware.org/?probe=99e899cbb0) | Jul 22, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [7599f8d0d5](https://linux-hardware.org/?probe=7599f8d0d5) | Jul 20, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [722e7132bd](https://linux-hardware.org/?probe=722e7132bd) | Jul 20, 2024 |
| HP            | 240 G4                      | Notebook    | [74ad43cd86](https://linux-hardware.org/?probe=74ad43cd86) | Jul 19, 2024 |
| Dell          | 0PC5F7 A01                  | Desktop     | [57944fa9c9](https://linux-hardware.org/?probe=57944fa9c9) | Jul 16, 2024 |
| Microsoft     | Surface Laptop Go           | Tablet      | [414019b989](https://linux-hardware.org/?probe=414019b989) | Jul 11, 2024 |
| Lenovo        | ThinkPad L13 Gen 1 20R4S... | Notebook    | [4cc52bfb25](https://linux-hardware.org/?probe=4cc52bfb25) | Jul 07, 2024 |
| Notebook      | PB50_70EF,ED,EC             | Notebook    | [9d7e31a9f6](https://linux-hardware.org/?probe=9d7e31a9f6) | Jul 06, 2024 |
| Dell          | XPS M1330                   | Notebook    | [a01b178b3a](https://linux-hardware.org/?probe=a01b178b3a) | Jul 06, 2024 |
| Acer          | Aspire V5-471P              | Notebook    | [f8a09477f0](https://linux-hardware.org/?probe=f8a09477f0) | Jul 05, 2024 |
| ASUSTek       | K50AD                       | Notebook    | [0fd561ca3c](https://linux-hardware.org/?probe=0fd561ca3c) | Jul 05, 2024 |
| Dell          | Latitude E6410              | Notebook    | [6f8ffa83ce](https://linux-hardware.org/?probe=6f8ffa83ce) | Jul 01, 2024 |
| HP            | Pavilion 10 TS              | Notebook    | [c2bd71447d](https://linux-hardware.org/?probe=c2bd71447d) | Jun 30, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [3eed7f4afe](https://linux-hardware.org/?probe=3eed7f4afe) | Jun 30, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3a1445300b](https://linux-hardware.org/?probe=3a1445300b) | Jun 28, 2024 |
| Dell          | Latitude 3190               | Notebook    | [41e83ac5c5](https://linux-hardware.org/?probe=41e83ac5c5) | Jun 27, 2024 |
| RWC           | DA-T118-SR                  | Notebook    | [05f141e671](https://linux-hardware.org/?probe=05f141e671) | Jun 26, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [16c26f1386](https://linux-hardware.org/?probe=16c26f1386) | Jun 26, 2024 |
| Teclast       | tPAD                        | Notebook    | [7fcbabfefd](https://linux-hardware.org/?probe=7fcbabfefd) | Jun 25, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [35d8e69b80](https://linux-hardware.org/?probe=35d8e69b80) | Jun 20, 2024 |
| Insyde        | Braswell                    | Notebook    | [fb1a3d94f3](https://linux-hardware.org/?probe=fb1a3d94f3) | Jun 19, 2024 |
| Dell          | 07WP95 A01                  | Desktop     | [220e02a4f2](https://linux-hardware.org/?probe=220e02a4f2) | Jun 19, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3e4d7f9fbc](https://linux-hardware.org/?probe=3e4d7f9fbc) | Jun 01, 2024 |
| ASUSTek       | X550WAK                     | Notebook    | [1a64c5c27f](https://linux-hardware.org/?probe=1a64c5c27f) | May 31, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [01934266f4](https://linux-hardware.org/?probe=01934266f4) | May 31, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [3414247f17](https://linux-hardware.org/?probe=3414247f17) | May 31, 2024 |
| Lenovo        | ThinkPad X200 2024B67       | Notebook    | [6d2d7fbbb5](https://linux-hardware.org/?probe=6d2d7fbbb5) | May 28, 2024 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [424447b0e3](https://linux-hardware.org/?probe=424447b0e3) | May 27, 2024 |
| ASUSTek       | GL552VX                     | Notebook    | [9f2697991a](https://linux-hardware.org/?probe=9f2697991a) | May 26, 2024 |
| Itautec       | NT 2030                     | Desktop     | [956753c602](https://linux-hardware.org/?probe=956753c602) | May 25, 2024 |
| MSI           | MS-B0A81                    | Desktop     | [3b16ea46f0](https://linux-hardware.org/?probe=3b16ea46f0) | May 20, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [dc9f14663c](https://linux-hardware.org/?probe=dc9f14663c) | May 18, 2024 |
| Lenovo        | ThinkPad L490 20Q5002GGE    | Notebook    | [c92390a81b](https://linux-hardware.org/?probe=c92390a81b) | May 15, 2024 |
| Dell          | Inspiron 13-5378            | Notebook    | [fcb1c00cb1](https://linux-hardware.org/?probe=fcb1c00cb1) | May 15, 2024 |
| Sony          | VPCW216AG                   | Notebook    | [0e3674f67f](https://linux-hardware.org/?probe=0e3674f67f) | May 14, 2024 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [abf8f16050](https://linux-hardware.org/?probe=abf8f16050) | May 13, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [345ddaf7ed](https://linux-hardware.org/?probe=345ddaf7ed) | May 13, 2024 |
| Intel         | H61                         | Desktop     | [274a448032](https://linux-hardware.org/?probe=274a448032) | May 09, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [93da978d38](https://linux-hardware.org/?probe=93da978d38) | May 04, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [e163aa8e32](https://linux-hardware.org/?probe=e163aa8e32) | May 03, 2024 |
| HP            | Pavilion dm1                | Notebook    | [ba07809953](https://linux-hardware.org/?probe=ba07809953) | May 02, 2024 |
| ASUSTek       | K45A                        | Notebook    | [7bed7e12ab](https://linux-hardware.org/?probe=7bed7e12ab) | Apr 27, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [e93fe83f01](https://linux-hardware.org/?probe=e93fe83f01) | Apr 24, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [216cd2fc72](https://linux-hardware.org/?probe=216cd2fc72) | Apr 24, 2024 |
| ASUSTek       | X555QG                      | Notebook    | [c905efd379](https://linux-hardware.org/?probe=c905efd379) | Apr 23, 2024 |
| ASUSTek       | X555QG                      | Notebook    | [26b8da2305](https://linux-hardware.org/?probe=26b8da2305) | Apr 23, 2024 |
| ASUSTek       | K42F                        | Notebook    | [f29299723c](https://linux-hardware.org/?probe=f29299723c) | Apr 23, 2024 |
| ASUSTek       | K42F                        | Notebook    | [63b454fa02](https://linux-hardware.org/?probe=63b454fa02) | Apr 23, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [8049fc6b37](https://linux-hardware.org/?probe=8049fc6b37) | Apr 23, 2024 |
| HP            | 8265                        | Desktop     | [17dd357578](https://linux-hardware.org/?probe=17dd357578) | Apr 21, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [bf1e4f8d6a](https://linux-hardware.org/?probe=bf1e4f8d6a) | Apr 20, 2024 |
| HP            | EliteBook 6930p             | Notebook    | [263d72f3c6](https://linux-hardware.org/?probe=263d72f3c6) | Apr 17, 2024 |
| Unknown       | Unknown                     | Notebook    | [10d92e98c0](https://linux-hardware.org/?probe=10d92e98c0) | Apr 16, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [c1bd4e2de3](https://linux-hardware.org/?probe=c1bd4e2de3) | Apr 14, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [caf43c2754](https://linux-hardware.org/?probe=caf43c2754) | Apr 14, 2024 |
| HP            | 250 G4 Notebook PC          | Notebook    | [2fcb542c43](https://linux-hardware.org/?probe=2fcb542c43) | Apr 14, 2024 |
| Prestigio     | Smartbook PSB116A           | Desktop     | [cc592e784e](https://linux-hardware.org/?probe=cc592e784e) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [94f12b2951](https://linux-hardware.org/?probe=94f12b2951) | Apr 11, 2024 |
| Unknown       | M-140BI3                    | Notebook    | [491b1013ab](https://linux-hardware.org/?probe=491b1013ab) | Apr 11, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8f232e4e6c](https://linux-hardware.org/?probe=8f232e4e6c) | Apr 11, 2024 |
| Biostar       | TA75M+                      | Desktop     | [24de8dbd0b](https://linux-hardware.org/?probe=24de8dbd0b) | Apr 10, 2024 |
| HP            | Pavilion g7                 | Notebook    | [6d84e70e34](https://linux-hardware.org/?probe=6d84e70e34) | Apr 10, 2024 |
| Lenovo        | ThinkPad X201 3680A44       | Notebook    | [db6aadf372](https://linux-hardware.org/?probe=db6aadf372) | Apr 10, 2024 |
| Dell          | Latitude E6410              | Notebook    | [7c4144e1df](https://linux-hardware.org/?probe=7c4144e1df) | Apr 05, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [82fa2b1397](https://linux-hardware.org/?probe=82fa2b1397) | Apr 04, 2024 |
| Acer          | Extensa 5630                | Notebook    | [224d74c060](https://linux-hardware.org/?probe=224d74c060) | Apr 04, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [7a19eed833](https://linux-hardware.org/?probe=7a19eed833) | Apr 03, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [0ece65fa78](https://linux-hardware.org/?probe=0ece65fa78) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [b909136c03](https://linux-hardware.org/?probe=b909136c03) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [d93ff94b95](https://linux-hardware.org/?probe=d93ff94b95) | Mar 27, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4e434bb17](https://linux-hardware.org/?probe=b4e434bb17) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [47de08fbc7](https://linux-hardware.org/?probe=47de08fbc7) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [4e7f4f9166](https://linux-hardware.org/?probe=4e7f4f9166) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [4533e58601](https://linux-hardware.org/?probe=4533e58601) | Mar 26, 2024 |
| Acer          | Extensa 2540                | Notebook    | [3e49d36612](https://linux-hardware.org/?probe=3e49d36612) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [d380208ff7](https://linux-hardware.org/?probe=d380208ff7) | Mar 26, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [46b79e7d26](https://linux-hardware.org/?probe=46b79e7d26) | Mar 26, 2024 |
| HP            | Laptop 14-em0xxx            | Notebook    | [3f937a527b](https://linux-hardware.org/?probe=3f937a527b) | Mar 23, 2024 |
| Samsung       | N100                        | Notebook    | [d7a66b3835](https://linux-hardware.org/?probe=d7a66b3835) | Mar 22, 2024 |
| Sony          | VGN-TZ21MN_N                | Notebook    | [1e1a62727b](https://linux-hardware.org/?probe=1e1a62727b) | Mar 19, 2024 |
| Unknown       | Unknown                     | Notebook    | [27317f4bcf](https://linux-hardware.org/?probe=27317f4bcf) | Mar 18, 2024 |
| Sony          | VPCW216AG                   | Notebook    | [c607fc8a6b](https://linux-hardware.org/?probe=c607fc8a6b) | Mar 16, 2024 |
| HP            | Split 13 x2 PC              | Notebook    | [447e4a6951](https://linux-hardware.org/?probe=447e4a6951) | Mar 14, 2024 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [c63473fd10](https://linux-hardware.org/?probe=c63473fd10) | Mar 12, 2024 |
| HP            | Notebook                    | Notebook    | [51a929c53a](https://linux-hardware.org/?probe=51a929c53a) | Mar 08, 2024 |
| Sony          | SVF1521NSTB                 | Notebook    | [b9f4d235c9](https://linux-hardware.org/?probe=b9f4d235c9) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [025b54a984](https://linux-hardware.org/?probe=025b54a984) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [5f90d8f25b](https://linux-hardware.org/?probe=5f90d8f25b) | Mar 06, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [326d4bbffb](https://linux-hardware.org/?probe=326d4bbffb) | Mar 05, 2024 |
| Fujitsu       | FMVC05005                   | Notebook    | [af1cd1c78b](https://linux-hardware.org/?probe=af1cd1c78b) | Mar 04, 2024 |
| Sony          | VPCEB3C4R                   | Notebook    | [f63a65b29f](https://linux-hardware.org/?probe=f63a65b29f) | Mar 04, 2024 |
| MSI           | MS-168A                     | Notebook    | [1625072479](https://linux-hardware.org/?probe=1625072479) | Mar 02, 2024 |
| MSI           | MS-168A                     | Notebook    | [cae162bcad](https://linux-hardware.org/?probe=cae162bcad) | Mar 02, 2024 |
| HP            | 250 G1                      | Notebook    | [805489bf43](https://linux-hardware.org/?probe=805489bf43) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7c9a199867](https://linux-hardware.org/?probe=7c9a199867) | Feb 21, 2024 |
| Sony          | VPCEB3C4R                   | Notebook    | [93a9016bf3](https://linux-hardware.org/?probe=93a9016bf3) | Feb 20, 2024 |
| Dell          | Inspiron 531s               | Desktop     | [0d9877a337](https://linux-hardware.org/?probe=0d9877a337) | Feb 19, 2024 |
| HP            | 83DD                        | Mini pc     | [71dc39d477](https://linux-hardware.org/?probe=71dc39d477) | Feb 17, 2024 |
| HP            | 83DD                        | Mini pc     | [8a763f4ef6](https://linux-hardware.org/?probe=8a763f4ef6) | Feb 17, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [edc56f85b9](https://linux-hardware.org/?probe=edc56f85b9) | Feb 17, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d18785d54f](https://linux-hardware.org/?probe=d18785d54f) | Feb 16, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d21dee5d98](https://linux-hardware.org/?probe=d21dee5d98) | Feb 13, 2024 |
| Digibras      | NH4CU53                     | Notebook    | [1e3d9f1795](https://linux-hardware.org/?probe=1e3d9f1795) | Feb 10, 2024 |
| Dell          | Latitude E5430 vPro         | Notebook    | [9e120d90b8](https://linux-hardware.org/?probe=9e120d90b8) | Feb 09, 2024 |
| ASRock        | H110M Combo-G               | Desktop     | [319e01fd31](https://linux-hardware.org/?probe=319e01fd31) | Feb 09, 2024 |
| MSI           | MS-7309                     | Desktop     | [dd1dea1c0e](https://linux-hardware.org/?probe=dd1dea1c0e) | Feb 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5fa467241b](https://linux-hardware.org/?probe=5fa467241b) | Feb 05, 2024 |
| Itautec       | Infoway w7430               | Notebook    | [4928095170](https://linux-hardware.org/?probe=4928095170) | Feb 05, 2024 |
| Acer          | Aspire 5951G                | Notebook    | [e583f21b3a](https://linux-hardware.org/?probe=e583f21b3a) | Feb 05, 2024 |
| HP            | Pavilion dv6                | Notebook    | [52c0814c31](https://linux-hardware.org/?probe=52c0814c31) | Feb 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [d477732dfa](https://linux-hardware.org/?probe=d477732dfa) | Feb 03, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [e7f247621c](https://linux-hardware.org/?probe=e7f247621c) | Feb 02, 2024 |
| Lenovo        | G405 20239                  | Notebook    | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [793c3d3b4c](https://linux-hardware.org/?probe=793c3d3b4c) | Jan 31, 2024 |
| Lenovo        | G575 20081                  | Notebook    | [162e1f81cf](https://linux-hardware.org/?probe=162e1f81cf) | Jan 31, 2024 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [a72292c97b](https://linux-hardware.org/?probe=a72292c97b) | Jan 31, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | Notebook    | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [f181c086e3](https://linux-hardware.org/?probe=f181c086e3) | Jan 23, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [5a172ff7ec](https://linux-hardware.org/?probe=5a172ff7ec) | Jan 22, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [c0eb7c0861](https://linux-hardware.org/?probe=c0eb7c0861) | Jan 21, 2024 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [9b6eb3d320](https://linux-hardware.org/?probe=9b6eb3d320) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | Desktop     | [5d46b8d1b3](https://linux-hardware.org/?probe=5d46b8d1b3) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | Desktop     | [cf089739df](https://linux-hardware.org/?probe=cf089739df) | Jan 19, 2024 |
| ZOTAC         | NM10                        | Desktop     | [e185a9b292](https://linux-hardware.org/?probe=e185a9b292) | Jan 18, 2024 |
| Intel         | H61                         | Desktop     | [1d639194e4](https://linux-hardware.org/?probe=1d639194e4) | Jan 17, 2024 |
| HP            | 3397                        | Desktop     | [a46224b9bc](https://linux-hardware.org/?probe=a46224b9bc) | Jan 17, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [817daf41f7](https://linux-hardware.org/?probe=817daf41f7) | Jan 16, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [87ad2c7889](https://linux-hardware.org/?probe=87ad2c7889) | Jan 16, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [c0f0afd78c](https://linux-hardware.org/?probe=c0f0afd78c) | Jan 14, 2024 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [82175efff8](https://linux-hardware.org/?probe=82175efff8) | Jan 14, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [5654e285db](https://linux-hardware.org/?probe=5654e285db) | Jan 10, 2024 |
| iRU           | 15TLI                       | Notebook    | [d318923a72](https://linux-hardware.org/?probe=d318923a72) | Jan 09, 2024 |
| ASUSTek       | K53U                        | Notebook    | [df631caaa2](https://linux-hardware.org/?probe=df631caaa2) | Jan 09, 2024 |
| Lenovo        | ThinkPad T430 23477C7       | Notebook    | [db1c43a6a6](https://linux-hardware.org/?probe=db1c43a6a6) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | Notebook    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| Dell          | 0CRH6C A00                  | Desktop     | [6c4bafe7b1](https://linux-hardware.org/?probe=6c4bafe7b1) | Jan 04, 2024 |
| Google        | Electro                     | Notebook    | [74ed1caffe](https://linux-hardware.org/?probe=74ed1caffe) | Jan 04, 2024 |
| Packard Be... | EasyNote LM85               | Notebook    | [e756bb57ba](https://linux-hardware.org/?probe=e756bb57ba) | Jan 03, 2024 |
| HP            | Notebook                    | Notebook    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | Notebook    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | Notebook    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| Chuwi         | GemiBook Plus               | Notebook    | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8f6b669800](https://linux-hardware.org/?probe=8f6b669800) | Dec 27, 2023 |
| Google        | Swanky                      | Notebook    | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [0b4e0e5e2b](https://linux-hardware.org/?probe=0b4e0e5e2b) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ba98d8db9](https://linux-hardware.org/?probe=3ba98d8db9) | Dec 24, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [538aa9126b](https://linux-hardware.org/?probe=538aa9126b) | Dec 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [65d7452931](https://linux-hardware.org/?probe=65d7452931) | Dec 17, 2023 |
| PELADN        | HA-3                        | Desktop     | [cd40102512](https://linux-hardware.org/?probe=cd40102512) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [acdb6ef8aa](https://linux-hardware.org/?probe=acdb6ef8aa) | Dec 17, 2023 |
| HP            | ZBook 17                    | Notebook    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Lenovo        | 3111 SDK0J40700 WIN 3258... | Mini pc     | [52be4d3e15](https://linux-hardware.org/?probe=52be4d3e15) | Dec 12, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [e126cdbf4b](https://linux-hardware.org/?probe=e126cdbf4b) | Dec 10, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [5ebbbca196](https://linux-hardware.org/?probe=5ebbbca196) | Dec 04, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | Notebook    | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Chuwi         | X312B                       | Notebook    | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| eMachines     | EL1358                      | Desktop     | [f22b0b98c3](https://linux-hardware.org/?probe=f22b0b98c3) | Nov 23, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | Notebook    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | Notebook    | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| Acer          | Extensa 5620                | Notebook    | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| MSI           | MS-7309                     | Desktop     | [c6ca259cae](https://linux-hardware.org/?probe=c6ca259cae) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | Notebook    | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| PCChips       | P49G                        | Desktop     | [6b1de00356](https://linux-hardware.org/?probe=6b1de00356) | Nov 02, 2023 |
| ZOTAC         | NM10                        | Desktop     | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4f0b8be2f6](https://linux-hardware.org/?probe=4f0b8be2f6) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [3fa8a23f12](https://linux-hardware.org/?probe=3fa8a23f12) | Oct 29, 2023 |
| Intel         | H61                         | Desktop     | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [712511f568](https://linux-hardware.org/?probe=712511f568) | Oct 27, 2023 |
| Dixonsxp      | Unknown                     | Notebook    | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| ZOTAC         | NM10                        | Desktop     | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| HP            | 8265                        | Desktop     | [f1bdedb075](https://linux-hardware.org/?probe=f1bdedb075) | Oct 20, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | Notebook    | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | Notebook    | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | Notebook    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | Notebook    | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | Notebook    | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [f8ad7736e2](https://linux-hardware.org/?probe=f8ad7736e2) | Oct 07, 2023 |
| Insyde        | Braswell                    | Notebook    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bf8761b854](https://linux-hardware.org/?probe=bf8761b854) | Oct 06, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [f88a18cfef](https://linux-hardware.org/?probe=f88a18cfef) | Oct 06, 2023 |
| Getac         | X500G3                      | Notebook    | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | Notebook    | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| ASUSTek       | E1600WKA                    | All in one  | [43c8a9b758](https://linux-hardware.org/?probe=43c8a9b758) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| Intel         | H61                         | Desktop     | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| ASUSTek       | X451MA                      | Notebook    | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [7b1aae3e2b](https://linux-hardware.org/?probe=7b1aae3e2b) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | Notebook    | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [47d423039b](https://linux-hardware.org/?probe=47d423039b) | Sep 19, 2023 |
| Dell          | Precision 3570              | Notebook    | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| HP            | 15                          | Notebook    | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| HP            | 2000                        | Notebook    | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | Notebook    | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| eMachines     | eM350                       | Notebook    | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [69fec63660](https://linux-hardware.org/?probe=69fec63660) | Sep 04, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [ea00f871b9](https://linux-hardware.org/?probe=ea00f871b9) | Sep 04, 2023 |
| HP            | 255 G2                      | Notebook    | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | Notebook    | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | Notebook    | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Compal        | PBL20                       | Notebook    | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | Notebook    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | Notebook    | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | Notebook    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | Notebook    | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dd8d164747](https://linux-hardware.org/?probe=dd8d164747) | Aug 17, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | Desktop     | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Apple         | Mac-F223BEC8                | Desktop     | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| HP            | Pavilion g7                 | Notebook    | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| Toshiba       | Satellite L875D             | Notebook    | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Dell          | Inspiron 1520               | Notebook    | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| HP            | 3646h                       | Desktop     | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | Notebook    | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | Notebook    | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Unknown       | Unknown                     | Other       | [f49e789b52](https://linux-hardware.org/?probe=f49e789b52) | Jul 04, 2023 |
| Google        | Pyro                        | Notebook    | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [7c6c7cff66](https://linux-hardware.org/?probe=7c6c7cff66) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Dell          | Precision 3570              | Notebook    | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| HP            | 3646h                       | Desktop     | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 3646h                       | Desktop     | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Dell          | Latitude E6430              | Notebook    | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | Notebook    | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Acer          | EQ45M                       | Desktop     | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [9709c9cf35](https://linux-hardware.org/?probe=9709c9cf35) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-43-generic | 36        | 6.29%   |
| 5.15.0-56-generic | 19        | 3.32%   |
| 5.15.0-25-generic | 17        | 2.97%   |
| 5.19.0-32-generic | 16        | 2.8%    |
| 5.15.0-60-generic | 14        | 2.45%   |
| 6.5.0-18-generic  | 13        | 2.27%   |
| 6.2.0-26-generic  | 13        | 2.27%   |
| 5.15.0-47-generic | 13        | 2.27%   |
| 5.15.0-58-generic | 12        | 2.1%    |
| 6.5.0-41-generic  | 11        | 1.92%   |
| 6.2.0-34-generic  | 10        | 1.75%   |
| 5.15.0-30-generic | 10        | 1.75%   |
| 6.5.0-27-generic  | 9         | 1.57%   |
| 6.2.0-39-generic  | 9         | 1.57%   |
| 5.19.0-46-generic | 9         | 1.57%   |
| 5.19.0-41-generic | 9         | 1.57%   |
| 5.15.0-52-generic | 9         | 1.57%   |
| 5.15.0-46-generic | 9         | 1.57%   |
| 5.15.0-41-generic | 9         | 1.57%   |
| 5.15.0-27-generic | 9         | 1.57%   |
| 6.5.0-28-generic  | 8         | 1.4%    |
| 6.5.0-14-generic  | 8         | 1.4%    |
| 5.19.0-50-generic | 8         | 1.4%    |
| 5.19.0-35-generic | 8         | 1.4%    |
| 5.15.0-53-generic | 8         | 1.4%    |
| 6.5.0-15-generic  | 7         | 1.22%   |
| 6.2.0-37-generic  | 7         | 1.22%   |
| 5.19.0-43-generic | 7         | 1.22%   |
| 6.8.0-48-generic  | 6         | 1.05%   |
| 6.8.0-40-generic  | 6         | 1.05%   |
| 6.5.0-35-generic  | 6         | 1.05%   |
| 6.5.0-25-generic  | 6         | 1.05%   |
| 6.5.0-17-generic  | 6         | 1.05%   |
| 6.2.0-36-generic  | 6         | 1.05%   |
| 6.2.0-35-generic  | 6         | 1.05%   |
| 5.15.0-91-generic | 6         | 1.05%   |
| 5.15.0-73-generic | 6         | 1.05%   |
| 5.15.0-67-generic | 6         | 1.05%   |
| 5.15.0-50-generic | 6         | 1.05%   |
| 5.15.0-48-generic | 6         | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 272       | 50.56%  |
| 6.5.0   | 90        | 16.73%  |
| 5.19.0  | 75        | 13.94%  |
| 6.2.0   | 60        | 11.15%  |
| 6.8.0   | 20        | 3.72%   |
| 6.7.8   | 1         | 0.19%   |
| 6.7.6   | 1         | 0.19%   |
| 6.7.0   | 1         | 0.19%   |
| 6.6.0   | 1         | 0.19%   |
| 6.4.12  | 1         | 0.19%   |
| 6.3.3   | 1         | 0.19%   |
| 6.2.8   | 1         | 0.19%   |
| 6.10.6  | 1         | 0.19%   |
| 6.1.46  | 1         | 0.19%   |
| 6.1.26  | 1         | 0.19%   |
| 6.1.12  | 1         | 0.19%   |
| 6.1.0   | 1         | 0.19%   |
| 6.0.8   | 1         | 0.19%   |
| 6.0.14  | 1         | 0.19%   |
| 6.0.12  | 1         | 0.19%   |
| 6.0.10  | 1         | 0.19%   |
| 5.4.0   | 1         | 0.19%   |
| 5.19.8  | 1         | 0.19%   |
| 5.19.11 | 1         | 0.19%   |
| 5.18.0  | 1         | 0.19%   |
| 5.14.0  | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 272       | 50.56%  |
| 6.5     | 90        | 16.73%  |
| 5.19    | 77        | 14.31%  |
| 6.2     | 61        | 11.34%  |
| 6.8     | 20        | 3.72%   |
| 6.1     | 4         | 0.74%   |
| 6.0     | 4         | 0.74%   |
| 6.7     | 3         | 0.56%   |
| 6.6     | 1         | 0.19%   |
| 6.4     | 1         | 0.19%   |
| 6.3     | 1         | 0.19%   |
| 6.10    | 1         | 0.19%   |
| 5.4     | 1         | 0.19%   |
| 5.18    | 1         | 0.19%   |
| 5.14    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 513       | 99.03%  |
| aarch64 | 5         | 0.97%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| LXQt           | 488       | 94.03%  |
| LXDE           | 17        | 3.28%   |
| GNOME          | 6         | 1.16%   |
| X-Cinnamon     | 2         | 0.39%   |
| XFCE           | 1         | 0.19%   |
| ratflow        | 1         | 0.19%   |
| Lubuntu        | 1         | 0.19%   |
| KDE5           | 1         | 0.19%   |
| i3-with-shmlog | 1         | 0.19%   |
| i3             | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 499       | 95.78%  |
| Tty         | 18        | 3.45%   |
| Wayland     | 3         | 0.58%   |
| Unspecified | 1         | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 434       | 83.14%  |
| Unknown | 37        | 7.09%   |
| LightDM | 28        | 5.36%   |
| GDM3    | 17        | 3.26%   |
| XDM     | 3         | 0.57%   |
| LXDM    | 2         | 0.38%   |
| SLiM    | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 164       | 31.42%  |
| fr_FR  | 61        | 11.69%  |
| de_DE  | 34        | 6.51%   |
| en_GB  | 31        | 5.94%   |
| C      | 31        | 5.94%   |
| it_IT  | 29        | 5.56%   |
| pt_BR  | 22        | 4.21%   |
| ru_RU  | 14        | 2.68%   |
| es_MX  | 13        | 2.49%   |
| pl_PL  | 11        | 2.11%   |
| es_ES  | 11        | 2.11%   |
| en_CA  | 10        | 1.92%   |
| en_AG  | 10        | 1.92%   |
| es_AR  | 9         | 1.72%   |
| en_AU  | 9         | 1.72%   |
| tr_TR  | 6         | 1.15%   |
| nl_BE  | 4         | 0.77%   |
| es_CR  | 4         | 0.77%   |
| es_CO  | 3         | 0.57%   |
| es_CL  | 3         | 0.57%   |
| en_PH  | 3         | 0.57%   |
| cs_CZ  | 3         | 0.57%   |
| zh_TW  | 2         | 0.38%   |
| sv_SE  | 2         | 0.38%   |
| sk_SK  | 2         | 0.38%   |
| nl_NL  | 2         | 0.38%   |
| ja_JP  | 2         | 0.38%   |
| fr_CA  | 2         | 0.38%   |
| fi_FI  | 2         | 0.38%   |
| el_GR  | 2         | 0.38%   |
| zh_CN  | 1         | 0.19%   |
| vi_VN  | 1         | 0.19%   |
| ru_UA  | 1         | 0.19%   |
| ro_RO  | 1         | 0.19%   |
| lzh_TW | 1         | 0.19%   |
| hu_HU  | 1         | 0.19%   |
| fr_CH  | 1         | 0.19%   |
| es_VE  | 1         | 0.19%   |
| es_UY  | 1         | 0.19%   |
| es_PE  | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 317       | 60.73%  |
| EFI  | 205       | 39.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 411       | 77.84%  |
| Tmpfs   | 84        | 15.91%  |
| Overlay | 24        | 4.55%   |
| Btrfs   | 5         | 0.95%   |
| XXX4    | 1         | 0.19%   |
| Xfs     | 1         | 0.19%   |
| Nfs     | 1         | 0.19%   |
| Ext2    | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 290       | 55.34%  |
| MBR     | 162       | 30.92%  |
| Unknown | 72        | 13.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 458       | 87.24%  |
| Yes       | 67        | 12.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 381       | 72.99%  |
| Yes       | 141       | 27.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 72        | 13.9%   |
| Lenovo                  | 65        | 12.55%  |
| Dell                    | 65        | 12.55%  |
| ASUSTek Computer        | 58        | 11.2%   |
| Acer                    | 38        | 7.34%   |
| MSI                     | 23        | 4.44%   |
| Apple                   | 18        | 3.47%   |
| Unknown                 | 15        | 2.9%    |
| Google                  | 13        | 2.51%   |
| ASRock                  | 10        | 1.93%   |
| Toshiba                 | 8         | 1.54%   |
| Sony                    | 8         | 1.54%   |
| Intel                   | 8         | 1.54%   |
| Fujitsu                 | 8         | 1.54%   |
| Gigabyte Technology     | 7         | 1.35%   |
| Supermicro              | 5         | 0.97%   |
| Samsung Electronics     | 5         | 0.97%   |
| AMI                     | 5         | 0.97%   |
| Positivo                | 4         | 0.77%   |
| Pegatron                | 4         | 0.77%   |
| Packard Bell            | 4         | 0.77%   |
| Mediacom                | 4         | 0.77%   |
| Gateway                 | 4         | 0.77%   |
| Raspberry Pi Foundation | 3         | 0.58%   |
| Microsoft               | 3         | 0.58%   |
| Chuwi                   | 3         | 0.58%   |
| Thomson                 | 2         | 0.39%   |
| SGIN                    | 2         | 0.39%   |
| OEM                     | 2         | 0.39%   |
| Medion                  | 2         | 0.39%   |
| Itautec                 | 2         | 0.39%   |
| HUAWEI                  | 2         | 0.39%   |
| Hampoo                  | 2         | 0.39%   |
| GPU Company             | 2         | 0.39%   |
| Getac                   | 2         | 0.39%   |
| Fujitsu Siemens         | 2         | 0.39%   |
| eMachines               | 2         | 0.39%   |
| Digibras                | 2         | 0.39%   |
| ZOTAC                   | 1         | 0.19%   |
| YANYU                   | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 17        | 3.28%   |
| HP Notebook                            | 5         | 0.97%   |
| Supermicro X8DTT-IBX                   | 4         | 0.77%   |
| Dell Latitude E6410                    | 4         | 0.77%   |
| Apple MacBookPro8,1                    | 4         | 0.77%   |
| MSI MS-7C37                            | 3         | 0.58%   |
| Mediacom WinPad 11,6 FullHD- WPU11     | 3         | 0.58%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS    | 3         | 0.58%   |
| HP Pavilion 15                         | 3         | 0.58%   |
| HP 2000                                | 3         | 0.58%   |
| Apple iMac7,1                          | 3         | 0.58%   |
| Toshiba Satellite C660                 | 2         | 0.39%   |
| RPi Raspberry Pi 4 Model B Rev 1.5     | 2         | 0.39%   |
| MSI MS-7309                            | 2         | 0.39%   |
| Lenovo G50-30 80G0                     | 2         | 0.39%   |
| Intel H61                              | 2         | 0.39%   |
| HP Pavilion g6                         | 2         | 0.39%   |
| HP Pavilion dv6                        | 2         | 0.39%   |
| HP 255 G2                              | 2         | 0.39%   |
| Fujitsu LIFEBOOK A3510                 | 2         | 0.39%   |
| Dell XPS M1330                         | 2         | 0.39%   |
| Dell OptiPlex 9020                     | 2         | 0.39%   |
| Dell OptiPlex 790                      | 2         | 0.39%   |
| Dell OptiPlex 7010                     | 2         | 0.39%   |
| Dell Latitude 3190                     | 2         | 0.39%   |
| Dell Inspiron N5110                    | 2         | 0.39%   |
| Dell Dimension 9100                    | 2         | 0.39%   |
| Apple MacBook4,1                       | 2         | 0.39%   |
| Acer Aspire SW3-013                    | 2         | 0.39%   |
| Acer Aspire A314-23P                   | 2         | 0.39%   |
| ZOTAC NM10                             | 1         | 0.19%   |
| YANYU ITX-S192                         | 1         | 0.19%   |
| TrekStor SurfTab wintron 7.0 ST70416-6 | 1         | 0.19%   |
| Toshiba Satellite Radius P55W-B        | 1         | 0.19%   |
| Toshiba Satellite Pro S500             | 1         | 0.19%   |
| Toshiba Satellite P770                 | 1         | 0.19%   |
| Toshiba Satellite P70-A                | 1         | 0.19%   |
| Toshiba Satellite L875D                | 1         | 0.19%   |
| Toshiba Satellite L40                  | 1         | 0.19%   |
| Thomson NEO14-4W64                     | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 26        | 5.02%   |
| Lenovo ThinkPad       | 25        | 4.83%   |
| Lenovo IdeaPad        | 20        | 3.86%   |
| Dell Latitude         | 18        | 3.47%   |
| Unknown               | 17        | 3.28%   |
| HP Pavilion           | 14        | 2.7%    |
| Dell OptiPlex         | 12        | 2.32%   |
| Dell Inspiron         | 12        | 2.32%   |
| HP Laptop             | 9         | 1.74%   |
| Toshiba Satellite     | 8         | 1.54%   |
| HP EliteBook          | 6         | 1.16%   |
| HP Compaq             | 6         | 1.16%   |
| Dell XPS              | 6         | 1.16%   |
| Dell Vostro           | 6         | 1.16%   |
| Dell Precision        | 6         | 1.16%   |
| HP Notebook           | 5         | 0.97%   |
| ASUS PRIME            | 5         | 0.97%   |
| Supermicro X8DTT-IBX  | 4         | 0.77%   |
| HP ProBook            | 4         | 0.77%   |
| HP 250                | 4         | 0.77%   |
| Fujitsu LIFEBOOK      | 4         | 0.77%   |
| ASUS VivoBook         | 4         | 0.77%   |
| ASUS ROG              | 4         | 0.77%   |
| Apple MacBookPro8     | 4         | 0.77%   |
| Acer Extensa          | 4         | 0.77%   |
| RPi Raspberry         | 3         | 0.58%   |
| Packard Bell EasyNote | 3         | 0.58%   |
| MSI MS-7C37           | 3         | 0.58%   |
| Microsoft Surface     | 3         | 0.58%   |
| Mediacom WinPad       | 3         | 0.58%   |
| Lenovo ThinkCentre    | 3         | 0.58%   |
| HP 240                | 3         | 0.58%   |
| HP 2000               | 3         | 0.58%   |
| Apple iMac7           | 3         | 0.58%   |
| MSI MS-7309           | 2         | 0.39%   |
| Lenovo MIIX           | 2         | 0.39%   |
| Lenovo G50-30         | 2         | 0.39%   |
| Intel H61             | 2         | 0.39%   |
| HP ZBook              | 2         | 0.39%   |
| HP 255                | 2         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 43        | 8.3%    |
| 2012    | 43        | 8.3%    |
| 2011    | 42        | 8.11%   |
| 2010    | 42        | 8.11%   |
| 2021    | 34        | 6.56%   |
| 2017    | 32        | 6.18%   |
| 2016    | 31        | 5.98%   |
| 2009    | 31        | 5.98%   |
| 2022    | 29        | 5.6%    |
| 2015    | 28        | 5.41%   |
| 2019    | 27        | 5.21%   |
| 2014    | 27        | 5.21%   |
| 2008    | 27        | 5.21%   |
| 2007    | 21        | 4.05%   |
| 2020    | 19        | 3.67%   |
| 2018    | 18        | 3.47%   |
| 2023    | 13        | 2.51%   |
| 2006    | 6         | 1.16%   |
| Unknown | 4         | 0.77%   |
| 2001    | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 331       | 63.9%   |
| Desktop        | 139       | 26.83%  |
| All in one     | 11        | 2.12%   |
| Mini pc        | 10        | 1.93%   |
| Convertible    | 8         | 1.54%   |
| Tablet         | 7         | 1.35%   |
| Server         | 6         | 1.16%   |
| System on chip | 5         | 0.97%   |
| Other          | 1         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 489       | 93.86%  |
| Enabled  | 32        | 6.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 504       | 97.3%   |
| Yes  | 14        | 2.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 172       | 32.82%  |
| 4.01-8.0    | 125       | 23.85%  |
| 1.01-2.0    | 65        | 12.4%   |
| 8.01-16.0   | 52        | 9.92%   |
| 16.01-24.0  | 51        | 9.73%   |
| 32.01-64.0  | 24        | 4.58%   |
| 2.01-3.0    | 18        | 3.44%   |
| 64.01-256.0 | 8         | 1.53%   |
| 24.01-32.0  | 5         | 0.95%   |
| 0.51-1.0    | 4         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 250       | 45.87%  |
| 2.01-3.0   | 113       | 20.73%  |
| 0.51-1.0   | 109       | 20%     |
| 4.01-8.0   | 34        | 6.24%   |
| 3.01-4.0   | 26        | 4.77%   |
| 8.01-16.0  | 7         | 1.28%   |
| 0.01-0.5   | 5         | 0.92%   |
| 32.01-64.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 369       | 70.55%  |
| 2      | 108       | 20.65%  |
| 3      | 23        | 4.4%    |
| 0      | 9         | 1.72%   |
| 5      | 5         | 0.96%   |
| 4      | 5         | 0.96%   |
| 7      | 2         | 0.38%   |
| 12     | 1         | 0.19%   |
| 6      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 303       | 58.05%  |
| Yes       | 219       | 41.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 426       | 81.77%  |
| No        | 95        | 18.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 403       | 77.65%  |
| No        | 116       | 22.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 280       | 53.54%  |
| No        | 243       | 46.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 89        | 17.18%  |
| France       | 62        | 11.97%  |
| Germany      | 49        | 9.46%   |
| Italy        | 37        | 7.14%   |
| Brazil       | 26        | 5.02%   |
| UK           | 21        | 4.05%   |
| Russia       | 21        | 4.05%   |
| Poland       | 19        | 3.67%   |
| Canada       | 15        | 2.9%    |
| Spain        | 14        | 2.7%    |
| Argentina    | 11        | 2.12%   |
| Turkey       | 8         | 1.54%   |
| Indonesia    | 8         | 1.54%   |
| Australia    | 8         | 1.54%   |
| Mexico       | 7         | 1.35%   |
| Sweden       | 6         | 1.16%   |
| Netherlands  | 6         | 1.16%   |
| Belgium      | 6         | 1.16%   |
| Ukraine      | 5         | 0.97%   |
| Hungary      | 5         | 0.97%   |
| Czechia      | 5         | 0.97%   |
| Costa Rica   | 5         | 0.97%   |
| Colombia     | 5         | 0.97%   |
| Slovakia     | 4         | 0.77%   |
| Finland      | 4         | 0.77%   |
| Chile        | 4         | 0.77%   |
| Vietnam      | 3         | 0.58%   |
| Romania      | 3         | 0.58%   |
| Portugal     | 3         | 0.58%   |
| Philippines  | 3         | 0.58%   |
| Peru         | 3         | 0.58%   |
| Pakistan     | 3         | 0.58%   |
| Malaysia     | 3         | 0.58%   |
| Japan        | 3         | 0.58%   |
| Venezuela    | 2         | 0.39%   |
| UAE          | 2         | 0.39%   |
| Thailand     | 2         | 0.39%   |
| Taiwan       | 2         | 0.39%   |
| Switzerland  | 2         | 0.39%   |
| South Africa | 2         | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 13        | 2.43%   |
| Moscow           | 5         | 0.93%   |
| Bruhl            | 5         | 0.93%   |
| Warsaw           | 4         | 0.75%   |
| Santiago         | 4         | 0.75%   |
| Milan            | 4         | 0.75%   |
| Melbourne        | 4         | 0.75%   |
| Kyiv             | 4         | 0.75%   |
| Heredia          | 4         | 0.75%   |
| Chambersburg     | 4         | 0.75%   |
| Sao Paulo        | 3         | 0.56%   |
| Rome             | 3         | 0.56%   |
| Prague           | 3         | 0.56%   |
| New York         | 3         | 0.56%   |
| Lyon             | 3         | 0.56%   |
| Ghent            | 3         | 0.56%   |
| Chicago          | 3         | 0.56%   |
| Bratislava       | 3         | 0.56%   |
| Bogotá          | 3         | 0.56%   |
| Valencia         | 2         | 0.37%   |
| Uberlândia      | 2         | 0.37%   |
| Tychy            | 2         | 0.37%   |
| Toronto          | 2         | 0.37%   |
| Tehran           | 2         | 0.37%   |
| Taipei           | 2         | 0.37%   |
| Stuttgart        | 2         | 0.37%   |
| St Petersburg    | 2         | 0.37%   |
| Sarospatak       | 2         | 0.37%   |
| Porto Alegre     | 2         | 0.37%   |
| Ottawa           | 2         | 0.37%   |
| Novosibirsk      | 2         | 0.37%   |
| Novo Gama        | 2         | 0.37%   |
| Munich           | 2         | 0.37%   |
| Montreal         | 2         | 0.37%   |
| Monheim am Rhein | 2         | 0.37%   |
| Minato-ku        | 2         | 0.37%   |
| Milano           | 2         | 0.37%   |
| Mexico City      | 2         | 0.37%   |
| Madrid           | 2         | 0.37%   |
| Lisbon           | 2         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 90        | 120    | 13.91%  |
| Seagate                     | 82        | 105    | 12.67%  |
| Unknown                     | 72        | 97     | 11.13%  |
| Samsung Electronics         | 68        | 96     | 10.51%  |
| Toshiba                     | 35        | 41     | 5.41%   |
| Kingston                    | 35        | 45     | 5.41%   |
| Hitachi                     | 34        | 43     | 5.26%   |
| SanDisk                     | 28        | 29     | 4.33%   |
| Crucial                     | 18        | 20     | 2.78%   |
| HGST                        | 14        | 15     | 2.16%   |
| Micron Technology           | 13        | 14     | 2.01%   |
| SK hynix                    | 10        | 11     | 1.55%   |
| Unknown                     | 10        | 11     | 1.55%   |
| A-DATA Technology           | 9         | 9      | 1.39%   |
| Intel                       | 8         | 9      | 1.24%   |
| China                       | 6         | 7      | 0.93%   |
| Transcend                   | 5         | 7      | 0.77%   |
| PNY                         | 5         | 5      | 0.77%   |
| Patriot                     | 5         | 5      | 0.77%   |
| Apacer                      | 5         | 5      | 0.77%   |
| GOODRAM                     | 4         | 4      | 0.62%   |
| Apple                       | 4         | 5      | 0.62%   |
| Team                        | 3         | 3      | 0.46%   |
| SPCC                        | 3         | 4      | 0.46%   |
| Silicon Motion              | 3         | 3      | 0.46%   |
| NGFF                        | 3         | 3      | 0.46%   |
| LITEONIT                    | 3         | 3      | 0.46%   |
| KIOXIA                      | 3         | 3      | 0.46%   |
| Fujitsu                     | 3         | 3      | 0.46%   |
| UMIS                        | 2         | 2      | 0.31%   |
| Phison                      | 2         | 2      | 0.31%   |
| Netac                       | 2         | 2      | 0.31%   |
| Micron/Crucial Technology   | 2         | 3      | 0.31%   |
| Maxtor                      | 2         | 2      | 0.31%   |
| LITEON                      | 2         | 2      | 0.31%   |
| Kingston Technology Company | 2         | 2      | 0.31%   |
| Intenso                     | 2         | 2      | 0.31%   |
| ExcelStor                   | 2         | 2      | 0.31%   |
| Emtec                       | 2         | 2      | 0.31%   |
| BR                          | 2         | 3      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 15        | 2.14%   |
| Unknown MMC Card  32GB             | 13        | 1.85%   |
| Kingston SA400S37240G 240GB SSD    | 13        | 1.85%   |
| Unknown                            | 10        | 1.42%   |
| SanDisk DF4032  32GB               | 7         | 1%      |
| Seagate ST500DM002-1BD142 500GB    | 6         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.85%   |
| Unknown NCard  32GB                | 5         | 0.71%   |
| Seagate ST9500325AS 500GB          | 5         | 0.71%   |
| Micron 2450_MTFDKBA512TFK 512GB    | 5         | 0.71%   |
| HGST HTS545050A7E680 500GB         | 5         | 0.71%   |
| Unknown SD/MMC/MS PRO 128GB        | 4         | 0.57%   |
| Unknown MMC Card  16GB             | 4         | 0.57%   |
| Unknown DA4032  32GB               | 4         | 0.57%   |
| Toshiba MQ01ABD050 500GB           | 4         | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.57%   |
| Samsung SSD 850 EVO 250GB          | 4         | 0.57%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.57%   |
| Kingston SA400S37120G 120GB SSD    | 4         | 0.57%   |
| Crucial CT240BX500SSD1 240GB       | 4         | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 3         | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 0.43%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 3         | 0.43%   |
| Unknown DA4064  64GB               | 3         | 0.43%   |
| Toshiba MQ01ABF050 500GB           | 3         | 0.43%   |
| Toshiba MQ01ABD100 1TB             | 3         | 0.43%   |
| Toshiba DT01ACA100 1TB             | 3         | 0.43%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 0.43%   |
| Seagate ST3500418AS 500GB          | 3         | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 0.43%   |
| Seagate Expansion 1TB              | 3         | 0.43%   |
| SanDisk DF4064  64GB               | 3         | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB     | 3         | 0.43%   |
| Samsung SSD 870 EVO 500GB          | 3         | 0.43%   |
| Kingston SA400S37960G 960GB SSD    | 3         | 0.43%   |
| Crucial CT1000MX500SSD1 1TB        | 3         | 0.43%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 2         | 0.28%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 2         | 0.28%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 2         | 0.28%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 2         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 103    | 30.22%  |
| WDC                 | 75        | 96     | 27.99%  |
| Hitachi             | 34        | 43     | 12.69%  |
| Toshiba             | 32        | 38     | 11.94%  |
| Samsung Electronics | 14        | 21     | 5.22%   |
| HGST                | 14        | 15     | 5.22%   |
| Unknown             | 4         | 4      | 1.49%   |
| Fujitsu             | 3         | 3      | 1.12%   |
| Maxtor              | 2         | 2      | 0.75%   |
| ExcelStor           | 2         | 2      | 0.75%   |
| WD MediaMax         | 1         | 1      | 0.37%   |
| TO Exter            | 1         | 1      | 0.37%   |
| RSH-319             | 1         | 1      | 0.37%   |
| External            | 1         | 1      | 0.37%   |
| ASMT                | 1         | 1      | 0.37%   |
| Apricorn            | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 46     | 16.59%  |
| Kingston            | 30        | 40     | 14.63%  |
| SanDisk             | 15        | 16     | 7.32%   |
| Crucial             | 13        | 15     | 6.34%   |
| WDC                 | 12        | 15     | 5.85%   |
| A-DATA Technology   | 8         | 8      | 3.9%    |
| Transcend           | 5         | 7      | 2.44%   |
| PNY                 | 5         | 5      | 2.44%   |
| Intel               | 5         | 5      | 2.44%   |
| Apacer              | 5         | 5      | 2.44%   |
| Patriot             | 4         | 4      | 1.95%   |
| Micron Technology   | 4         | 4      | 1.95%   |
| GOODRAM             | 4         | 4      | 1.95%   |
| China               | 4         | 4      | 1.95%   |
| Toshiba             | 3         | 3      | 1.46%   |
| Team                | 3         | 3      | 1.46%   |
| SPCC                | 3         | 4      | 1.46%   |
| NGFF                | 3         | 3      | 1.46%   |
| LITEONIT            | 3         | 3      | 1.46%   |
| Netac               | 2         | 2      | 0.98%   |
| LITEON              | 2         | 2      | 0.98%   |
| Emtec               | 2         | 2      | 0.98%   |
| Apple               | 2         | 2      | 0.98%   |
| XrayDisk            | 1         | 1      | 0.49%   |
| WDC WDS2            | 1         | 1      | 0.49%   |
| W800S               | 1         | 1      | 0.49%   |
| Varro               | 1         | 1      | 0.49%   |
| USB3.0              | 1         | 1      | 0.49%   |
| Teclast             | 1         | 1      | 0.49%   |
| SK hynix            | 1         | 2      | 0.49%   |
| Rogueware           | 1         | 1      | 0.49%   |
| Plextor             | 1         | 1      | 0.49%   |
| OWC                 | 1         | 1      | 0.49%   |
| Neo Forza           | 1         | 1      | 0.49%   |
| MidasForce          | 1         | 1      | 0.49%   |
| Lexar               | 1         | 1      | 0.49%   |
| Leqixiang           | 1         | 1      | 0.49%   |
| Lenovo              | 1         | 1      | 0.49%   |
| Kston               | 1         | 3      | 0.49%   |
| KingSpec            | 1         | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 236       | 334    | 39.2%   |
| SSD     | 190       | 243    | 31.56%  |
| MMC     | 89        | 118    | 14.78%  |
| NVMe    | 77        | 92     | 12.79%  |
| Unknown | 10        | 16     | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 385       | 561    | 67.31%  |
| MMC  | 89        | 118    | 15.56%  |
| NVMe | 76        | 90     | 13.29%  |
| SAS  | 22        | 34     | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 309       | 393    | 68.97%  |
| 0.51-1.0   | 96        | 124    | 21.43%  |
| 1.01-2.0   | 25        | 36     | 5.58%   |
| 3.01-4.0   | 6         | 8      | 1.34%   |
| 4.01-10.0  | 6         | 9      | 1.34%   |
| 2.01-3.0   | 4         | 5      | 0.89%   |
| 10.01-20.0 | 2         | 2      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 169       | 31.83%  |
| 251-500        | 116       | 21.85%  |
| 51-100         | 56        | 10.55%  |
| 501-1000       | 53        | 9.98%   |
| 1-20           | 42        | 7.91%   |
| 21-50          | 41        | 7.72%   |
| 1001-2000      | 21        | 3.95%   |
| More than 3000 | 19        | 3.58%   |
| 2001-3000      | 9         | 1.69%   |
| Unknown        | 5         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 263       | 48.43%  |
| 21-50          | 107       | 19.71%  |
| 51-100         | 53        | 9.76%   |
| 101-250        | 47        | 8.66%   |
| 251-500        | 23        | 4.24%   |
| 501-1000       | 18        | 3.31%   |
| 1001-2000      | 12        | 2.21%   |
| More than 3000 | 10        | 1.84%   |
| 2001-3000      | 5         | 0.92%   |
| Unknown        | 5         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 6      | 6.67%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2         | 2      | 2.67%   |
| Toshiba MQ01ABD050 500GB            | 2         | 2      | 2.67%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 2.67%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 2.67%   |
| Apacer 16GB SATA Flash Drive SSD    | 2         | 2      | 2.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 1      | 1.33%   |
| WDC WD60EFRX-68L0BN1 6TB            | 1         | 2      | 1.33%   |
| WDC WD5000LPCX-60VHAT1 500GB        | 1         | 1      | 1.33%   |
| WDC WD5000BPVT-75HXZT1 500GB        | 1         | 1      | 1.33%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 1.33%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1      | 1.33%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 1         | 1      | 1.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 1      | 1.33%   |
| WDC WD3200AACS-00M6B0 320GB         | 1         | 1      | 1.33%   |
| WDC WD2003FYYS-02W0B0 2TB           | 1         | 1      | 1.33%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1      | 1.33%   |
| WDC WD10SPZX-08Z10 1TB              | 1         | 1      | 1.33%   |
| WDC WD10SPCX-21KHST0 1TB            | 1         | 1      | 1.33%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 1.33%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 1.33%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1         | 1      | 1.33%   |
| WDC WD10EACS-00D6B1 1TB             | 1         | 1      | 1.33%   |
| Transcend TS256GSSD720 256GB        | 1         | 1      | 1.33%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.33%   |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 1.33%   |
| Toshiba MK6459GSXP 640GB            | 1         | 1      | 1.33%   |
| Toshiba MK2556GSY 250GB             | 1         | 1      | 1.33%   |
| Toshiba MK1652GSX 160GB             | 1         | 1      | 1.33%   |
| Toshiba DT01ACA050 500GB            | 1         | 1      | 1.33%   |
| Seagate ST9500420AS 500GB           | 1         | 1      | 1.33%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.33%   |
| Seagate ST640LM000 HM641JI 640GB    | 1         | 1      | 1.33%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.33%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.33%   |
| Seagate ST4000DM004-2CV104 4TB      | 1         | 1      | 1.33%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 1.33%   |
| Seagate ST320LT012-9WS14C 320GB     | 1         | 1      | 1.33%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 23     | 30.14%  |
| WDC                 | 17        | 20     | 23.29%  |
| Hitachi             | 9         | 9      | 12.33%  |
| Toshiba             | 8         | 8      | 10.96%  |
| Samsung Electronics | 2         | 7      | 2.74%   |
| Intel               | 2         | 2      | 2.74%   |
| HGST                | 2         | 2      | 2.74%   |
| Apacer              | 2         | 2      | 2.74%   |
| Transcend           | 1         | 1      | 1.37%   |
| Plextor             | 1         | 1      | 1.37%   |
| NGFF                | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 1      | 1.37%   |
| Maxtor              | 1         | 1      | 1.37%   |
| Kingmax             | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 1      | 1.37%   |
| Apple               | 1         | 1      | 1.37%   |
| A-DATA Technology   | 1         | 1      | 1.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 23     | 35.48%  |
| WDC                 | 16        | 19     | 25.81%  |
| Hitachi             | 9         | 9      | 14.52%  |
| Toshiba             | 8         | 8      | 12.9%   |
| Samsung Electronics | 2         | 7      | 3.23%   |
| HGST                | 2         | 2      | 3.23%   |
| Maxtor              | 1         | 1      | 1.61%   |
| Fujitsu             | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 71     | 84.72%  |
| SSD  | 11        | 11     | 15.28%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 259       | 415    | 47.01%  |
| Works    | 217       | 303    | 39.38%  |
| Malfunc  | 72        | 82     | 13.07%  |
| Failed   | 3         | 3      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 343       | 63.05%  |
| AMD                              | 84        | 15.44%  |
| Samsung Electronics              | 21        | 3.86%   |
| Nvidia                           | 15        | 2.76%   |
| Micron Technology                | 10        | 1.84%   |
| SanDisk                          | 9         | 1.65%   |
| Micron/Crucial Technology        | 7         | 1.29%   |
| Kingston Technology Company      | 7         | 1.29%   |
| ASMedia Technology               | 7         | 1.29%   |
| SK hynix                         | 6         | 1.1%    |
| JMicron Technology               | 6         | 1.1%    |
| VIA Technologies                 | 3         | 0.55%   |
| Silicon Motion                   | 3         | 0.55%   |
| Silicon Image                    | 3         | 0.55%   |
| KIOXIA                           | 3         | 0.55%   |
| Union Memory (Shenzhen)          | 2         | 0.37%   |
| Phison Electronics               | 2         | 0.37%   |
| Marvell Technology Group         | 2         | 0.37%   |
| LSI Logic / Symbios Logic        | 2         | 0.37%   |
| Broadcom / LSI                   | 2         | 0.37%   |
| Solid State Storage Technology   | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Shenzhen Longsys Electronics     | 1         | 0.18%   |
| Seagate Technology               | 1         | 0.18%   |
| Hosin Global Electronics         | 1         | 0.18%   |
| Apple                            | 1         | 0.18%   |
| ADATA Technology                 | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 56        | 8.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 36        | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 3.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 2.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 19        | 2.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 2.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 18        | 2.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 17        | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 2.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 14        | 2.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 13        | 2.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 1.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 12        | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 11        | 1.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9         | 1.4%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 8         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 8         | 1.25%   |
| Nvidia MCP61 SATA Controller                                                     | 7         | 1.09%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 7         | 1.09%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 1.09%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 7         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 7         | 1.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 6         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 0.93%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 6         | 0.93%   |
| Nvidia MCP61 IDE                                                                 | 5         | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 0.78%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5         | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 0.78%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 0.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 0.62%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 4         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 370       | 65.26%  |
| IDE  | 90        | 15.87%  |
| NVMe | 75        | 13.23%  |
| RAID | 30        | 5.29%   |
| SAS  | 1         | 0.18%   |
| SCSI | 1         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 406       | 78.38%  |
| AMD    | 107       | 20.66%  |
| ARM    | 5         | 0.97%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N3350 @ 1.10GHz           | 10        | 1.93%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 10        | 1.93%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 9         | 1.74%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 9         | 1.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 7         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 0.97%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 0.97%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 5         | 0.97%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 5         | 0.97%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 5         | 0.97%   |
| Intel Atom CPU N450 @ 1.66GHz               | 5         | 0.97%   |
| ARM Processor                               | 5         | 0.97%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 4         | 0.77%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 4         | 0.77%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 4         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 0.77%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 4         | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 0.77%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 4         | 0.77%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 4         | 0.77%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 4         | 0.77%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 4         | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 0.77%   |
| AMD E1-2100 APU with Radeon HD Graphics     | 4         | 0.77%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 3         | 0.58%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 3         | 0.58%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 3         | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 3         | 0.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3         | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 0.58%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 0.58%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 3         | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.58%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 0.58%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 3         | 0.58%   |
| Intel Celeron N4500 @ 1.10GHz               | 3         | 0.58%   |
| Intel Celeron N4120 CPU @ 1.10GHz           | 3         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 94        | 18.15%  |
| Intel Celeron           | 83        | 16.02%  |
| Intel Atom              | 43        | 8.3%    |
| Intel Core i7           | 42        | 8.11%   |
| Intel Core i3           | 39        | 7.53%   |
| Intel Core 2 Duo        | 35        | 6.76%   |
| Other                   | 19        | 3.67%   |
| AMD Ryzen 7             | 15        | 2.9%    |
| Intel Pentium           | 14        | 2.7%    |
| Intel Xeon              | 12        | 2.32%   |
| AMD Ryzen 5             | 12        | 2.32%   |
| AMD A6                  | 9         | 1.74%   |
| Intel Pentium Dual-Core | 8         | 1.54%   |
| Intel Pentium Dual      | 7         | 1.35%   |
| AMD E                   | 7         | 1.35%   |
| AMD E1                  | 6         | 1.16%   |
| AMD Athlon 64 X2        | 6         | 1.16%   |
| AMD A8                  | 5         | 0.97%   |
| AMD A10                 | 5         | 0.97%   |
| Intel Core 2 Quad       | 4         | 0.77%   |
| Intel Core 2            | 4         | 0.77%   |
| AMD Ryzen 9             | 4         | 0.77%   |
| AMD E2                  | 4         | 0.77%   |
| AMD Athlon              | 4         | 0.77%   |
| AMD A4                  | 4         | 0.77%   |
| AMD Phenom II X4        | 3         | 0.58%   |
| AMD FX                  | 3         | 0.58%   |
| Intel Pentium D         | 2         | 0.39%   |
| Intel Genuine           | 2         | 0.39%   |
| AMD Sempron             | 2         | 0.39%   |
| AMD Phenom II X6        | 2         | 0.39%   |
| AMD GX                  | 2         | 0.39%   |
| AMD C-60                | 2         | 0.39%   |
| AMD Athlon II X2        | 2         | 0.39%   |
| Intel Pentium Silver    | 1         | 0.19%   |
| Intel Pentium Gold      | 1         | 0.19%   |
| Intel Core m3           | 1         | 0.19%   |
| Intel Core i9           | 1         | 0.19%   |
| Intel Celeron Dual-Core | 1         | 0.19%   |
| AMD Ryzen 7 PRO         | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 290       | 55.98%  |
| 4       | 153       | 29.54%  |
| 8       | 23        | 4.44%   |
| 6       | 20        | 3.86%   |
| 1       | 17        | 3.28%   |
| 10      | 4         | 0.77%   |
| Unknown | 4         | 0.77%   |
| 3       | 3         | 0.58%   |
| 12      | 2         | 0.39%   |
| 16      | 1         | 0.19%   |
| 14      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 507       | 97.88%  |
| 2       | 7         | 1.35%   |
| Unknown | 4         | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 282       | 54.44%  |
| 2       | 232       | 44.79%  |
| Unknown | 4         | 0.77%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 517       | 99.81%  |
| 64-bit         | 1         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 288       | 54.96%  |
| 0x306a9    | 21        | 4.01%   |
| 0x206a7    | 15        | 2.86%   |
| 0x406c4    | 12        | 2.29%   |
| 0x1067a    | 12        | 2.29%   |
| 0x0700010f | 10        | 1.91%   |
| 0x406c3    | 9         | 1.72%   |
| 0x706a8    | 8         | 1.53%   |
| 0x05000119 | 7         | 1.34%   |
| 0x6fd      | 6         | 1.15%   |
| 0x306c3    | 6         | 1.15%   |
| 0x30678    | 5         | 0.95%   |
| 0x20655    | 5         | 0.95%   |
| 0x106ca    | 5         | 0.95%   |
| 0x0a50000c | 5         | 0.95%   |
| 0x906ea    | 4         | 0.76%   |
| 0x906c0    | 4         | 0.76%   |
| 0x806ec    | 4         | 0.76%   |
| 0x706e5    | 4         | 0.76%   |
| 0x706a1    | 4         | 0.76%   |
| 0x506c9    | 4         | 0.76%   |
| 0x40651    | 4         | 0.76%   |
| 0x806ea    | 3         | 0.57%   |
| 0x806c1    | 3         | 0.57%   |
| 0x6fb      | 3         | 0.57%   |
| 0x506e3    | 3         | 0.57%   |
| 0x406e3    | 3         | 0.57%   |
| 0x30679    | 3         | 0.57%   |
| 0x0a50000d | 3         | 0.57%   |
| 0x08608103 | 3         | 0.57%   |
| 0x07030105 | 3         | 0.57%   |
| 0x06006705 | 3         | 0.57%   |
| 0x06001119 | 3         | 0.57%   |
| 0x906a4    | 2         | 0.38%   |
| 0x806e9    | 2         | 0.38%   |
| 0x10676    | 2         | 0.38%   |
| 0x0a50000b | 2         | 0.38%   |
| 0x0a201009 | 2         | 0.38%   |
| 0x08a00008 | 2         | 0.38%   |
| 0x0800820d | 2         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 61        | 11.78%  |
| IvyBridge        | 47        | 9.07%   |
| Penryn           | 35        | 6.76%   |
| SandyBridge      | 33        | 6.37%   |
| KabyLake         | 32        | 6.18%   |
| Haswell          | 30        | 5.79%   |
| Core             | 30        | 5.79%   |
| Westmere         | 29        | 5.6%    |
| Goldmont plus    | 23        | 4.44%   |
| Unknown          | 17        | 3.28%   |
| Goldmont         | 15        | 2.9%    |
| Zen 3            | 14        | 2.7%    |
| Skylake          | 14        | 2.7%    |
| Bonnell          | 13        | 2.51%   |
| K10              | 12        | 2.32%   |
| Excavator        | 12        | 2.32%   |
| Jaguar           | 11        | 2.12%   |
| Bobcat           | 11        | 2.12%   |
| Nehalem          | 8         | 1.54%   |
| Piledriver       | 7         | 1.35%   |
| K8 Hammer        | 7         | 1.35%   |
| IceLake          | 6         | 1.16%   |
| Broadwell        | 6         | 1.16%   |
| Alderlake Hybrid | 6         | 1.16%   |
| Zen+             | 5         | 0.97%   |
| Tremont          | 5         | 0.97%   |
| Zen              | 4         | 0.77%   |
| TigerLake        | 4         | 0.77%   |
| Puma             | 4         | 0.77%   |
| CometLake        | 4         | 0.77%   |
| Zen 2            | 3         | 0.58%   |
| Steamroller      | 2         | 0.39%   |
| NetBurst         | 2         | 0.39%   |
| K10 Llano        | 2         | 0.39%   |
| Gracemont        | 2         | 0.39%   |
| K8 & K10 hybrid  | 1         | 0.19%   |
| Bulldozer        | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 341       | 60.14%  |
| AMD                        | 126       | 22.22%  |
| Nvidia                     | 94        | 16.58%  |
| Matrox Electronics Systems | 6         | 1.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 40        | 6.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 5.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 5.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 3.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 3.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 3.53%   |
| Intel HD Graphics 500                                                                    | 14        | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 2.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 2.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 2.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 2.02%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 8         | 1.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.18%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.18%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.18%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.01%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 1.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.01%   |
| AMD Lucienne                                                                             | 6         | 1.01%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.84%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5         | 0.84%   |
| Intel UHD Graphics 620                                                                   | 5         | 0.84%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.84%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 5         | 0.84%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 0.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.67%   |
| Intel HD Graphics 620                                                                    | 4         | 0.67%   |
| AMD Mendocino                                                                            | 4         | 0.67%   |
| AMD Kabini [Radeon HD 8210]                                                              | 4         | 0.67%   |
| Nvidia GT218 [ION]                                                                       | 3         | 0.5%    |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 3         | 0.5%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 3         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 287       | 55.3%   |
| 1 x AMD            | 93        | 17.92%  |
| 1 x Nvidia         | 61        | 11.75%  |
| Intel + Nvidia     | 28        | 5.39%   |
| Intel + AMD        | 16        | 3.08%   |
| 2 x AMD            | 12        | 2.31%   |
| Other              | 10        | 1.93%   |
| 1 x Matrox         | 6         | 1.16%   |
| AMD + Nvidia       | 4         | 0.77%   |
| Intel + 2 x Nvidia | 1         | 0.19%   |
| Intel + 2 x AMD    | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 473       | 91.31%  |
| Proprietary | 27        | 5.21%   |
| Unknown     | 18        | 3.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 390       | 74.71%  |
| 0.01-0.5   | 59        | 11.3%   |
| 0.51-1.0   | 26        | 4.98%   |
| 1.01-2.0   | 23        | 4.41%   |
| 7.01-8.0   | 6         | 1.15%   |
| 3.01-4.0   | 6         | 1.15%   |
| 5.01-6.0   | 5         | 0.96%   |
| 8.01-16.0  | 4         | 0.77%   |
| 2.01-3.0   | 3         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 77        | 15.28%  |
| Samsung Electronics     | 65        | 12.9%   |
| LG Display              | 62        | 12.3%   |
| BOE                     | 52        | 10.32%  |
| Chimei Innolux          | 39        | 7.74%   |
| Dell                    | 22        | 4.37%   |
| Acer                    | 17        | 3.37%   |
| Apple                   | 15        | 2.98%   |
| Hewlett-Packard         | 14        | 2.78%   |
| Goldstar                | 14        | 2.78%   |
| Lenovo                  | 11        | 2.18%   |
| Philips                 | 9         | 1.79%   |
| Chi Mei Optoelectronics | 8         | 1.59%   |
| Ancor Communications    | 8         | 1.59%   |
| Sharp                   | 7         | 1.39%   |
| CPT                     | 5         | 0.99%   |
| BenQ                    | 5         | 0.99%   |
| Toshiba                 | 4         | 0.79%   |
| InfoVision              | 4         | 0.79%   |
| Vizio                   | 3         | 0.6%    |
| ViewSonic               | 3         | 0.6%    |
| Sony                    | 3         | 0.6%    |
| LG Philips              | 3         | 0.6%    |
| Iiyama                  | 3         | 0.6%    |
| HKC                     | 3         | 0.6%    |
| HannStar                | 3         | 0.6%    |
| Eizo                    | 3         | 0.6%    |
| Unknown                 | 2         | 0.4%    |
| MSI                     | 2         | 0.4%    |
| Insignia                | 2         | 0.4%    |
| InnoLux Display         | 2         | 0.4%    |
| ASUSTek Computer        | 2         | 0.4%    |
| AOC                     | 2         | 0.4%    |
| XKX                     | 1         | 0.2%    |
| Westinghouse            | 1         | 0.2%    |
| VHT                     | 1         | 0.2%    |
| Unknown (ADA)           | 1         | 0.2%    |
| SNC                     | 1         | 0.2%    |
| SFX                     | 1         | 0.2%    |
| Sceptre Tech            | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 6         | 1.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.98%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 4         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.78%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 0.78%   |
| Acer H213H ACR0087 1920x1080 531x299mm 24.0-inch                         | 4         | 0.78%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.59%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.59%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.59%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch       | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.39%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 2         | 0.39%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.39%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch              | 2         | 0.39%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.39%   |
| Dell S2721HSX DEL4202 1920x1080 598x336mm 27.0-inch                      | 2         | 0.39%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 2         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.39%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                    | 2         | 0.39%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.39%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                     | 2         | 0.39%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch           | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO243C 1366x768 309x173mm 13.9-inch            | 2         | 0.39%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 169       | 34%     |
| 1920x1080 (FHD)    | 152       | 30.58%  |
| 1280x800 (WXGA)    | 38        | 7.65%   |
| 1600x900 (HD+)     | 33        | 6.64%   |
| 3840x2160 (4K)     | 16        | 3.22%   |
| 1280x1024 (SXGA)   | 15        | 3.02%   |
| 1440x900 (WXGA+)   | 14        | 2.82%   |
| 1680x1050 (WSXGA+) | 13        | 2.62%   |
| 2560x1440 (QHD)    | 10        | 2.01%   |
| 1360x768           | 8         | 1.61%   |
| 1920x1200 (WUXGA)  | 5         | 1.01%   |
| 1024x768 (XGA)     | 3         | 0.6%    |
| 3200x1800 (QHD+)   | 2         | 0.4%    |
| 2160x1440          | 2         | 0.4%    |
| 1024x600           | 2         | 0.4%    |
| 800x600            | 1         | 0.2%    |
| 3440x1440          | 1         | 0.2%    |
| 3200x1200          | 1         | 0.2%    |
| 3000x2000          | 1         | 0.2%    |
| 2880x1920          | 1         | 0.2%    |
| 2560x1600          | 1         | 0.2%    |
| 2560x1080          | 1         | 0.2%    |
| 2288x1287          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1920x1280          | 1         | 0.2%    |
| 1528x1222          | 1         | 0.2%    |
| 1400x1050          | 1         | 0.2%    |
| 1280x768           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 135       | 26.84%  |
| 14      | 57        | 11.33%  |
| 13      | 55        | 10.93%  |
| 17      | 28        | 5.57%   |
| 24      | 26        | 5.17%   |
| 11      | 25        | 4.97%   |
| 27      | 21        | 4.17%   |
| 23      | 21        | 4.17%   |
| 19      | 20        | 3.98%   |
| 12      | 18        | 3.58%   |
| 21      | 17        | 3.38%   |
| 22      | 10        | 1.99%   |
| 18      | 10        | 1.99%   |
| Unknown | 10        | 1.99%   |
| 20      | 8         | 1.59%   |
| 31      | 6         | 1.19%   |
| 10      | 6         | 1.19%   |
| 84      | 3         | 0.6%    |
| 72      | 3         | 0.6%    |
| 32      | 3         | 0.6%    |
| 49      | 2         | 0.4%    |
| 42      | 2         | 0.4%    |
| 28      | 2         | 0.4%    |
| 26      | 2         | 0.4%    |
| 142     | 1         | 0.2%    |
| 60      | 1         | 0.2%    |
| 54      | 1         | 0.2%    |
| 52      | 1         | 0.2%    |
| 47      | 1         | 0.2%    |
| 46      | 1         | 0.2%    |
| 44      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 34      | 1         | 0.2%    |
| 16      | 1         | 0.2%    |
| 9       | 1         | 0.2%    |
| 8       | 1         | 0.2%    |
| 7       | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 220       | 43.82%  |
| 201-300        | 77        | 15.34%  |
| 501-600        | 68        | 13.55%  |
| 401-500        | 56        | 11.16%  |
| 351-400        | 36        | 7.17%   |
| 601-700        | 10        | 1.99%   |
| Unknown        | 10        | 1.99%   |
| 1001-1500      | 7         | 1.39%   |
| 1501-2000      | 6         | 1.2%    |
| 701-800        | 4         | 0.8%    |
| 901-1000       | 4         | 0.8%    |
| 101-200        | 3         | 0.6%    |
| More than 2000 | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 366       | 77.87%  |
| 16/10   | 65        | 13.83%  |
| 5/4     | 13        | 2.77%   |
| 3/2     | 9         | 1.91%   |
| Unknown | 8         | 1.7%    |
| 4/3     | 7         | 1.49%   |
| 21/9    | 1         | 0.21%   |
| 1.00    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 133       | 26.49%  |
| 81-90          | 97        | 19.32%  |
| 201-250        | 64        | 12.75%  |
| 151-200        | 33        | 6.57%   |
| 51-60          | 25        | 4.98%   |
| 301-350        | 22        | 4.38%   |
| 121-130        | 20        | 3.98%   |
| 61-70          | 18        | 3.59%   |
| 71-80          | 14        | 2.79%   |
| More than 1000 | 12        | 2.39%   |
| 141-150        | 12        | 2.39%   |
| 351-500        | 10        | 1.99%   |
| Unknown        | 10        | 1.99%   |
| 251-300        | 8         | 1.59%   |
| 41-50          | 7         | 1.39%   |
| 501-1000       | 7         | 1.39%   |
| 131-140        | 5         | 1%      |
| 1-40           | 2         | 0.4%    |
| 91-100         | 2         | 0.4%    |
| 111-120        | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 190       | 38.46%  |
| 51-100        | 141       | 28.54%  |
| 121-160       | 110       | 22.27%  |
| 161-240       | 25        | 5.06%   |
| 1-50          | 15        | 3.04%   |
| Unknown       | 10        | 2.02%   |
| More than 240 | 3         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 455       | 87.16%  |
| 2     | 49        | 9.39%   |
| 0     | 17        | 3.26%   |
| 3     | 1         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 271       | 34.61%  |
| Intel                           | 190       | 24.27%  |
| Qualcomm Atheros                | 104       | 13.28%  |
| Broadcom                        | 60        | 7.66%   |
| Marvell Technology Group        | 16        | 2.04%   |
| TP-Link                         | 13        | 1.66%   |
| Nvidia                          | 13        | 1.66%   |
| MediaTek                        | 11        | 1.4%    |
| Broadcom Limited                | 11        | 1.4%    |
| Ralink                          | 10        | 1.28%   |
| Samsung Electronics             | 8         | 1.02%   |
| Ralink Technology               | 8         | 1.02%   |
| Xiaomi                          | 6         | 0.77%   |
| Qualcomm Atheros Communications | 5         | 0.64%   |
| Mellanox Technologies           | 5         | 0.64%   |
| ASIX Electronics                | 5         | 0.64%   |
| OPPO Electronics                | 4         | 0.51%   |
| NetGear                         | 4         | 0.51%   |
| Belkin Components               | 4         | 0.51%   |
| Dell                            | 3         | 0.38%   |
| ASUSTek Computer                | 3         | 0.38%   |
| VIA Technologies                | 2         | 0.26%   |
| Qualcomm                        | 2         | 0.26%   |
| JMicron Technology              | 2         | 0.26%   |
| ICS Advent                      | 2         | 0.26%   |
| D-Link                          | 2         | 0.26%   |
| ZTopInc                         | 1         | 0.13%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.13%   |
| Trident Microsystems            | 1         | 0.13%   |
| Texas Instruments               | 1         | 0.13%   |
| Spreadtrum Communications       | 1         | 0.13%   |
| Sierra Wireless                 | 1         | 0.13%   |
| Seeed Technology                | 1         | 0.13%   |
| Motorola PCS                    | 1         | 0.13%   |
| Microsoft                       | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| MCS                             | 1         | 0.13%   |
| Linksys                         | 1         | 0.13%   |
| Hangzhou Silan Microelectronics | 1         | 0.13%   |
| Fibocom                         | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156       | 17.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50        | 5.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 21        | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 18        | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 16        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 1.53%   |
| Intel Wireless 7260                                                    | 14        | 1.53%   |
| Intel Wireless 7265                                                    | 12        | 1.31%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 1.09%   |
| Intel Wireless 3165                                                    | 10        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 9         | 0.98%   |
| Intel Wireless 8265 / 8275                                             | 9         | 0.98%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                           | 7         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 7         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 7         | 0.77%   |
| Intel Centrino Advanced-N 6200                                         | 7         | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 6         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 0.66%   |
| Nvidia MCP61 Ethernet                                                  | 6         | 0.66%   |
| Intel Wireless 8260                                                    | 6         | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 0.66%   |
| Broadcom BCM4321 802.11a/b/g/n                                         | 6         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 6         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 5         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 5         | 0.55%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 0.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 143       | 33.18%  |
| Realtek Semiconductor                 | 88        | 20.42%  |
| Qualcomm Atheros                      | 88        | 20.42%  |
| Broadcom                              | 40        | 9.28%   |
| TP-Link                               | 11        | 2.55%   |
| Ralink                                | 10        | 2.32%   |
| MediaTek                              | 10        | 2.32%   |
| Ralink Technology                     | 8         | 1.86%   |
| Broadcom Limited                      | 6         | 1.39%   |
| Qualcomm Atheros Communications       | 5         | 1.16%   |
| Belkin Components                     | 4         | 0.93%   |
| NetGear                               | 3         | 0.7%    |
| ASUSTek Computer                      | 3         | 0.7%    |
| Dell                                  | 2         | 0.46%   |
| D-Link                                | 2         | 0.46%   |
| ZTopInc                               | 1         | 0.23%   |
| Sierra Wireless                       | 1         | 0.23%   |
| Microsoft                             | 1         | 0.23%   |
| Micro Star International              | 1         | 0.23%   |
| Marvell Technology Group              | 1         | 0.23%   |
| Linksys                               | 1         | 0.23%   |
| Fibocom                               | 1         | 0.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 21        | 4.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 18        | 4.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 3.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 3.21%   |
| Intel Wireless 7260                                            | 14        | 3.21%   |
| Intel Wireless 7265                                            | 12        | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.52%   |
| Intel Wireless 3165                                            | 10        | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 2.06%   |
| Intel Wireless 8265 / 8275                                     | 9         | 2.06%   |
| Realtek 802.11n WLAN Adapter                                   | 7         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7         | 1.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.61%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 1.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 1.38%   |
| Intel Wireless 8260                                            | 6         | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 1.38%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 6         | 1.38%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.15%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 1.15%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 5         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.92%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 4         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 0.92%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.92%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 233       | 50.43%  |
| Intel                           | 95        | 20.56%  |
| Qualcomm Atheros                | 32        | 6.93%   |
| Broadcom                        | 28        | 6.06%   |
| Marvell Technology Group        | 15        | 3.25%   |
| Nvidia                          | 13        | 2.81%   |
| Xiaomi                          | 6         | 1.3%    |
| Samsung Electronics             | 6         | 1.3%    |
| Broadcom Limited                | 5         | 1.08%   |
| ASIX Electronics                | 5         | 1.08%   |
| OPPO Electronics                | 4         | 0.87%   |
| VIA Technologies                | 2         | 0.43%   |
| TP-Link                         | 2         | 0.43%   |
| Qualcomm                        | 2         | 0.43%   |
| JMicron Technology              | 2         | 0.43%   |
| ICS Advent                      | 2         | 0.43%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.22%   |
| Trident Microsystems            | 1         | 0.22%   |
| Spreadtrum Communications       | 1         | 0.22%   |
| NetGear                         | 1         | 0.22%   |
| Motorola PCS                    | 1         | 0.22%   |
| Mellanox Technologies           | 1         | 0.22%   |
| MediaTek                        | 1         | 0.22%   |
| Hangzhou Silan Microelectronics | 1         | 0.22%   |
| DisplayLink                     | 1         | 0.22%   |
| Accton Technology               | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156       | 33.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50        | 10.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 4.29%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 2.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 2.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 2.15%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 1.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 1.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 1.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 1.29%   |
| Nvidia MCP61 Ethernet                                                  | 6         | 1.29%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 5         | 1.07%   |
| Intel Ethernet Controller I225-V                                       | 5         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.86%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 4         | 0.86%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.86%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.86%   |
| Intel 82576 Gigabit Network Connection                                 | 4         | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 0.64%   |
| OPPO OnePlus Nord 4                                                    | 3         | 0.64%   |
| Nvidia MCP77 Ethernet                                                  | 3         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.64%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 3         | 0.64%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 3         | 0.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2         | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 425       | 50.54%  |
| WiFi     | 404       | 48.04%  |
| Modem    | 8         | 0.95%   |
| Unknown  | 4         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 311       | 60.51%  |
| Ethernet | 203       | 39.49%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 275       | 53.09%  |
| 1     | 184       | 35.52%  |
| 0     | 43        | 8.3%    |
| 3     | 14        | 2.7%    |
| 4     | 2         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 364       | 69.87%  |
| Yes  | 157       | 30.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 34.98%  |
| Realtek Semiconductor           | 37        | 13.07%  |
| Qualcomm Atheros Communications | 29        | 10.25%  |
| Broadcom                        | 17        | 6.01%   |
| Lite-On Technology              | 16        | 5.65%   |
| Apple                           | 16        | 5.65%   |
| IMC Networks                    | 12        | 4.24%   |
| Foxconn / Hon Hai               | 11        | 3.89%   |
| Cambridge Silicon Radio         | 9         | 3.18%   |
| Dell                            | 8         | 2.83%   |
| Ralink                          | 6         | 2.12%   |
| Hewlett-Packard                 | 6         | 2.12%   |
| MediaTek                        | 3         | 1.06%   |
| Alps Electric                   | 3         | 1.06%   |
| TP-Link                         | 2         | 0.71%   |
| Toshiba                         | 2         | 0.71%   |
| Marvell Semiconductor           | 2         | 0.71%   |
| Syntek                          | 1         | 0.35%   |
| Qcom                            | 1         | 0.35%   |
| Logitech                        | 1         | 0.35%   |
| Integrated System Solution      | 1         | 0.35%   |
| ASUSTek Computer                | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 55        | 19.3%   |
| Realtek Bluetooth Radio                                                             | 25        | 8.77%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 4.91%   |
| Intel AX201 Bluetooth                                                               | 13        | 4.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 3.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 3.16%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 2.46%   |
| Apple Bluetooth Host Controller                                                     | 7         | 2.46%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.11%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 2.11%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 2.11%   |
| Intel AX200 Bluetooth                                                               | 5         | 1.75%   |
| Apple Bluetooth HCI                                                                 | 5         | 1.75%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 1.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.4%    |
| IMC Networks Bluetooth Device                                                       | 4         | 1.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.4%    |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.05%   |
| MediaTek Wireless_Device                                                            | 3         | 1.05%   |
| Lite-On Wireless_Device                                                             | 3         | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.05%   |
| Intel AX211 Bluetooth                                                               | 3         | 1.05%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.05%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.05%   |
| TP-Link TP-Link Bluetooth USB Adapter                                               | 2         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.7%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.7%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.7%    |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.7%    |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.7%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.7%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 363       | 62.37%  |
| AMD                                          | 112       | 19.24%  |
| Nvidia                                       | 67        | 11.51%  |
| C-Media Electronics                          | 8         | 1.37%   |
| GN Netcom                                    | 4         | 0.69%   |
| VIA Technologies                             | 3         | 0.52%   |
| Texas Instruments                            | 3         | 0.52%   |
| ASUSTek Computer                             | 3         | 0.52%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.34%   |
| Razer USA                                    | 2         | 0.34%   |
| JMTek                                        | 2         | 0.34%   |
| Sony                                         | 1         | 0.17%   |
| Plantronics                                  | 1         | 0.17%   |
| MosArt Semiconductor                         | 1         | 0.17%   |
| Microsoft                                    | 1         | 0.17%   |
| Micro Star International                     | 1         | 0.17%   |
| Logitech                                     | 1         | 0.17%   |
| KTMicro                                      | 1         | 0.17%   |
| Kingston Technology                          | 1         | 0.17%   |
| Jieli Technology                             | 1         | 0.17%   |
| Focusrite-Novation                           | 1         | 0.17%   |
| Ensoniq                                      | 1         | 0.17%   |
| EGO SYStems                                  | 1         | 0.17%   |
| Creative Labs                                | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 46        | 6.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 31        | 4.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 30        | 4.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 27        | 3.91%   |
| AMD FCH Azalia Controller                                                                         | 27        | 3.91%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 24        | 3.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 23        | 3.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 3.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 2.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 2.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 20        | 2.89%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 2.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 2.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 2.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 2.03%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 1.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.16%   |
| Nvidia MCP61 High Definition Audio                                                                | 7         | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 7         | 1.01%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 1.01%   |
| AMD High Definition Audio Controller                                                              | 7         | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 0.87%   |
| Intel Jasper Lake HD Audio                                                                        | 6         | 0.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.87%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 0.87%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 6         | 0.87%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.72%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 0.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 81        | 20.61%  |
| SK hynix            | 76        | 19.34%  |
| Unknown             | 51        | 12.98%  |
| Micron Technology   | 40        | 10.18%  |
| Kingston            | 28        | 7.12%   |
| Unknown (ABCD)      | 16        | 4.07%   |
| Crucial             | 13        | 3.31%   |
| Nanya Technology    | 11        | 2.8%    |
| Elpida              | 9         | 2.29%   |
| Corsair             | 9         | 2.29%   |
| Unknown             | 9         | 2.29%   |
| G.Skill             | 8         | 2.04%   |
| A-DATA Technology   | 6         | 1.53%   |
| Smart               | 5         | 1.27%   |
| Ramaxel Technology  | 5         | 1.27%   |
| PUSKILL             | 2         | 0.51%   |
| PNY                 | 2         | 0.51%   |
| Patriot             | 2         | 0.51%   |
| High Bridge         | 2         | 0.51%   |
| fef5                | 2         | 0.51%   |
| Wilk                | 1         | 0.25%   |
| Unknown (AB)        | 1         | 0.25%   |
| Unifosa             | 1         | 0.25%   |
| Transcend           | 1         | 0.25%   |
| Toshiba             | 1         | 0.25%   |
| Timetec             | 1         | 0.25%   |
| Teikon              | 1         | 0.25%   |
| TakeMS              | 1         | 0.25%   |
| Novatech            | 1         | 0.25%   |
| Kllisre             | 1         | 0.25%   |
| Kingmax             | 1         | 0.25%   |
| HMD                 | 1         | 0.25%   |
| GOODRAM             | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |
| AMD                 | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 10        | 2.38%   |
| Unknown                                                          | 9         | 2.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.9%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 6         | 1.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 6         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 1.19%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 1.19%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 4         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.95%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.95%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.71%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 3         | 0.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.71%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.71%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 3         | 0.71%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 3         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 2         | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 2         | 0.48%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.48%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 2         | 0.48%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.48%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.48%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.48%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.48%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.48%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 2         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 2         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 162       | 46.29%  |
| DDR4    | 95        | 27.14%  |
| DDR2    | 29        | 8.29%   |
| LPDDR4  | 28        | 8%      |
| SDRAM   | 13        | 3.71%   |
| Unknown | 8         | 2.29%   |
| LPDDR5  | 6         | 1.71%   |
| LPDDR3  | 4         | 1.14%   |
| DDR5    | 3         | 0.86%   |
| DDR     | 2         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 231       | 67.15%  |
| DIMM         | 87        | 25.29%  |
| Row Of Chips | 20        | 5.81%   |
| Unknown      | 5         | 1.45%   |
| Chip         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 121       | 31.76%  |
| 8192  | 110       | 28.87%  |
| 2048  | 91        | 23.88%  |
| 16384 | 28        | 7.35%   |
| 1024  | 21        | 5.51%   |
| 32768 | 6         | 1.57%   |
| 512   | 2         | 0.52%   |
| 12288 | 1         | 0.26%   |
| 3072  | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 109       | 29.3%   |
| 3200    | 36        | 9.68%   |
| 2400    | 34        | 9.14%   |
| 1333    | 31        | 8.33%   |
| 2667    | 25        | 6.72%   |
| 667     | 17        | 4.57%   |
| 1334    | 14        | 3.76%   |
| 1066    | 12        | 3.23%   |
| 800     | 11        | 2.96%   |
| Unknown | 10        | 2.69%   |
| 2133    | 7         | 1.88%   |
| 1866    | 7         | 1.88%   |
| 1067    | 7         | 1.88%   |
| 6400    | 5         | 1.34%   |
| 4267    | 5         | 1.34%   |
| 3266    | 5         | 1.34%   |
| 2048    | 5         | 1.34%   |
| 4800    | 3         | 0.81%   |
| 3400    | 3         | 0.81%   |
| 1867    | 3         | 0.81%   |
| 975     | 3         | 0.81%   |
| 4266    | 2         | 0.54%   |
| 4199    | 2         | 0.54%   |
| 3600    | 2         | 0.54%   |
| 3066    | 2         | 0.54%   |
| 2666    | 2         | 0.54%   |
| 533     | 2         | 0.54%   |
| 5500    | 1         | 0.27%   |
| 4000    | 1         | 0.27%   |
| 3933    | 1         | 0.27%   |
| 3666    | 1         | 0.27%   |
| 3534    | 1         | 0.27%   |
| 2933    | 1         | 0.27%   |
| 2800    | 1         | 0.27%   |
| 333     | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 36.36%  |
| Canon               | 3         | 27.27%  |
| Hewlett-Packard     | 2         | 18.18%  |
| STMicroelectronics  | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 9.09%   |
| Samsung SCX-4200 series                                   | 1         | 9.09%   |
| HP LaserJet P1102                                         | 1         | 9.09%   |
| HP DeskJet 6980 series                                    | 1         | 9.09%   |
| Canon PIXMA MP250                                         | 1         | 9.09%   |
| Canon MF3110                                              | 1         | 9.09%   |
| Canon CanoScan LiDE 300                                   | 1         | 9.09%   |
| Brother MFC-7340                                          | 1         | 9.09%   |
| Brother HL-L2380DW                                        | 1         | 9.09%   |
| Brother HL-2230 series                                    | 1         | 9.09%   |
| Brother DCP-7055W                                         | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Seiko Epson    | 1         | 50%     |
| Mustek Systems | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Mustek Systems ScanExpress A3 USB             | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 77        | 25.16%  |
| Realtek Semiconductor                  | 30        | 9.8%    |
| Microdia                               | 23        | 7.52%   |
| Sunplus Innovation Technology          | 18        | 5.88%   |
| Apple                                  | 15        | 4.9%    |
| Quanta                                 | 13        | 4.25%   |
| Bison Electronics                      | 13        | 4.25%   |
| Syntek                                 | 12        | 3.92%   |
| Suyin                                  | 12        | 3.92%   |
| IMC Networks                           | 12        | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.59%   |
| Logitech                               | 9         | 2.94%   |
| Alcor Micro                            | 8         | 2.61%   |
| Silicon Motion                         | 7         | 2.29%   |
| Lite-On Technology                     | 6         | 1.96%   |
| Lenovo                                 | 4         | 1.31%   |
| ALi                                    | 4         | 1.31%   |
| Ricoh                                  | 3         | 0.98%   |
| Microsoft                              | 3         | 0.98%   |
| icSpring                               | 3         | 0.98%   |
| Z-Star Microelectronics                | 2         | 0.65%   |
| USB Camera CS                          | 2         | 0.65%   |
| OmniVision Technologies                | 2         | 0.65%   |
| Luxvisions Innotech Limited            | 2         | 0.65%   |
| GEMBIRD                                | 2         | 0.65%   |
| Y Media                                | 1         | 0.33%   |
| WaveRider Communications               | 1         | 0.33%   |
| SunplusIT                              | 1         | 0.33%   |
| Sunplus Technology                     | 1         | 0.33%   |
| Sonix Technology                       | 1         | 0.33%   |
| Santa Barbara Instrument Group         | 1         | 0.33%   |
| Pixart Imaging                         | 1         | 0.33%   |
| KYT-221229-A                           | 1         | 0.33%   |
| Generalplus Technology                 | 1         | 0.33%   |
| Denron                                 | 1         | 0.33%   |
| Cubeternet                             | 1         | 0.33%   |
| AVerMedia Technologies                 | 1         | 0.33%   |
| Acer                                   | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 12        | 3.9%    |
| Chicony HD WebCam                                       | 8         | 2.6%    |
| Sunplus HD WebCam                                       | 6         | 1.95%   |
| Chicony HP TrueVision HD Camera                         | 6         | 1.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 5         | 1.62%   |
| Apple Built-in iSight                                   | 5         | 1.62%   |
| Silicon Motion 300k Pixel Camera                        | 4         | 1.3%    |
| Realtek Integrated_Webcam_HD                            | 4         | 1.3%    |
| Microdia Integrated_Webcam_HD                           | 4         | 1.3%    |
| Microdia Integrated Webcam                              | 4         | 1.3%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.3%    |
| Chicony HP TrueVision HD                                | 4         | 1.3%    |
| Bison Integrated Camera                                 | 4         | 1.3%    |
| Apple FaceTime HD Camera                                | 4         | 1.3%    |
| Alcor Micro USB 2.0 Camera                              | 4         | 1.3%    |
| Syntek USB Camera Device                                | 3         | 0.97%   |
| Syntek Lenovo EasyCamera                                | 3         | 0.97%   |
| Realtek USB Camera                                      | 3         | 0.97%   |
| Realtek Integrated Webcam HD                            | 3         | 0.97%   |
| Microdia Lenovo EasyCamera                              | 3         | 0.97%   |
| Logitech Webcam C270                                    | 3         | 0.97%   |
| Lenovo Integrated Webcam                                | 3         | 0.97%   |
| icSpring camera                                         | 3         | 0.97%   |
| Chicony VGA Webcam                                      | 3         | 0.97%   |
| Chicony FJ Camera                                       | 3         | 0.97%   |
| Chicony EasyCamera                                      | 3         | 0.97%   |
| Chicony ACER HD User Facing                             | 3         | 0.97%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 3         | 0.97%   |
| Bison Lenovo EasyCamera                                 | 3         | 0.97%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 0.97%   |
| ALi WebCam                                              | 3         | 0.97%   |
| Z-Star Webcam                                           | 2         | 0.65%   |
| USB Camera CS USB Camera CS                             | 2         | 0.65%   |
| Syntek Integrated Camera                                | 2         | 0.65%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.65%   |
| Silicon Motion WebCam SCB-1100N                         | 2         | 0.65%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870]     | 2         | 0.65%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 0.65%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.65%   |
| Realtek HP Truevision HD                                | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 30.56%  |
| Upek                       | 6         | 16.67%  |
| Synaptics                  | 5         | 13.89%  |
| AuthenTec                  | 5         | 13.89%  |
| STMicroelectronics         | 4         | 11.11%  |
| Shenzhen Goodix Technology | 2         | 5.56%   |
| LighTuning Technology      | 2         | 5.56%   |
| Elan Microelectronics      | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 6         | 16.67%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 5.56%   |
| Synaptics WBDI                                         | 2         | 5.56%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 5.56%   |
| AuthenTec AES2810                                      | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.78%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.78%   |
| Validity Sensors VFS300 Fingerprint Reader             | 1         | 2.78%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.78%   |
| Synaptics UWP WBDI                                     | 1         | 2.78%   |
| Synaptics TouchPad                                     | 1         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 2.78%   |
| LighTuning Fingerprint Reader                          | 1         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.78%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.78%   |
| AuthenTec Fingerprint Sensor                           | 1         | 2.78%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.78%   |
| AuthenTec AES1600                                      | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 10        | 43.48%  |
| Alcor Micro           | 6         | 26.09%  |
| O2 Micro              | 2         | 8.7%    |
| Lenovo                | 2         | 8.7%    |
| CHERRY                | 2         | 8.7%    |
| Gemalto (was Gemplus) | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 21.74%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 21.74%  |
| Broadcom 5880                                                                | 3         | 13.04%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8.7%    |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8.7%    |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 8.7%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |
| Broadcom 58200                                                               | 1         | 4.35%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 397       | 76.49%  |
| 1     | 103       | 19.85%  |
| 2     | 17        | 3.28%   |
| 4     | 1         | 0.19%   |
| 3     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 35        | 25%     |
| Graphics card            | 29        | 20.71%  |
| Chipcard                 | 20        | 14.29%  |
| Net/wireless             | 15        | 10.71%  |
| Bluetooth                | 11        | 7.86%   |
| Camera                   | 10        | 7.14%   |
| Multimedia controller    | 4         | 2.86%   |
| Storage                  | 3         | 2.14%   |
| Net/ethernet             | 3         | 2.14%   |
| Dvb card                 | 3         | 2.14%   |
| Network                  | 2         | 1.43%   |
| Communication controller | 2         | 1.43%   |
| Unassigned class         | 1         | 0.71%   |
| Storage/raid             | 1         | 0.71%   |
| Sound                    | 1         | 0.71%   |

